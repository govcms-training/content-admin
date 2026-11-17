# Revisions

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

Each time you select **Save** when editing a piece of content, it creates a new **revision** that's saved in the **revision log**.

This allows the system to maintain an audit log of all changes to your website content.

You can also provide **revision log messages** when you're editing content, which are displayed on the Revisions page.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-04 at 1.38.51 pm.png" alt="" width="369"><figcaption><p>An example of a revision log being added while editing</p></figcaption></figure>

The revision log for each page also allows you to compare two revisions against each other to see what was changed.

You can access the **revision log** by selecting the **Revision tab** when editing or viewing content.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-16 at 1.49.09 pm.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-06-04 at 1.39.52 pm.png" alt=""><figcaption><p>The Revision page shows various content revisions</p></figcaption></figure>

In the above instance we can see a page had two **Draft** changes saved, it was then **Published**, then **Archived**, and then finally republished.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/488356227?h=8914972327" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn how to manage content revisions.

We'll cover the following four topics: How to view revisions How to view the differences between two revisions How to revert to an older revision and how to add a revision log message

GovCMS creates a new revision every time content such as standard page, event and so on is saved. This allows you to track how the content has changed over time on your website, with a new revision created every time content is updated.

To view and manage revisions, go into a page, and you should see a "Revisions" tab here. However, when there's only a single revision you won't see the tab. You'll also need to make sure you have permission to view the revisions.

Let's go ahead and make a change to this event, click on edit. And add some text into the body field. Then scroll down to the bottom and click on save.

Click on the revisions tab to see all of the revisions. At this point, there are only a few revisions, but if you were to save the page a few times, this list will grow.

When you're on the revisions page you can see what the revision looks like by clicking on the date: Here you can see the original version But let's go back and click on the latest revision. And now you can see the current revision with the new line.

You can also compare between revisions, choose the ones you want to compare by selecting the radio button. If you can't see the radio buttons and the "Compare selected revisions" button, it means you do not have the Diff module installed. You'll need to get that module installed and configured.

Make sure you have selected two revisions and click on "Compare selected revisions". And here we can see the two differences between the revisions.

And from the layout dropdown, if you change it to unified fields, you can see the different HTML between the two revisions.

You can also at any time revert to an older published revision. All you need to do is click on the Revert button.

So let's revert to the first published revision. Simply click on Revert... And click on Revert in the confirmation step.

The revision that we reverted to is just copied as the current revision. And that's why the message says "copy of the revision from..." then the date. The revision that we just reverted was automatically published as the current revision because it's a published revision. However, you can't set a draft or needs review revision as the current revision. Only published revisions can be current.

So to demonstrate all of this, click edit... And add "draft" into the body field. Then scroll down and save it as a draft revision and click on Save.

Go and edit the page again. And replace Draft with "Needs Review" in the body field. Then scroll down to the bottom and save it as Needs Review and then click on Save.

If we go to the revisions page we should see, both the draft and needs review revision.

If we were to revert to the draft revision... The current revision hasn't changed, and here you can see a copy of the draft revision.

And that's the same for this revision as well, which is set to "needs review". If we were to click on set as current revision. It is simply copied. But the current revision is still this published revision.

If you want to publish a draft or a "needs review" revision, you will need to publish it using the content moderation workflow.

To do that... simply edit this page, and scroll all the way down to the bottom, and select Published and click on Save.

When you save a page, you can add a log message, which will be displayed on the revisions page. On the right-hand side you should see the "Revision log message" text area. If you can't see the text area when you log in, then please liaise within your organisation and raise a service desk ticket. To add a log message, all you need to do is add some text.

So let's add "updated body field" as the message. It's a good idea to add a meaningful message here whenever you create a revision, so that others or you, months later, can see why you changed the page and what your changes were, without having to actually view the previous revision.

Let's publish this revision. Scroll to the bottom, select "Published" and click on Save And if we go to the revisions tab... ...we should see the published revision with our message right here.

Let's now recap what we covered in this video. First, you learnt how to access the revisions by clicking on the Revisions tab. Then you learnt how to compare the different revisions. After that, we looked at how to revert to an older revision. And finally, you learnt how to add a revision log message from the content edit form.

</details>
