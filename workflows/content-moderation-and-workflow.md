# Content moderation and workflow

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

A **content moderation workflow** allows content to go through an approval process before it’s posted live on a website. This means that content can be authored by one person and reviewed by another before it's approved.&#x20;

The content is then only visible to the public (site visitors) once it's approved.

By default GovCMS comes with a [standard workflow](workflow-in-practice.md), however your developers can create custom workflows with unique states available to different roles and different content types.

GovCMS also includes [Scheduled Transitions](scheduled-publishing.md), allowing you to schedule the transition from **Needs Review** to **Published** to happen at a set time in the future.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/501677909?h=11c584caba" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn about the content moderation system in GovCMS.

We'll cover the following three topics: What content moderation is in GovCMS. How to change the moderation state on content. How to view moderated content.

A content moderation workflow allows content to go through an approval process before it's posted live on a website.

GovCMS comes with a default workflow which consists of four states: Draft, Needs Review, Published and Archived If you want to publish a piece of content it must go from draft to needs review and then published. If you want to archive a page, it must be published first, then archived.

User roles have different permissions when it comes to the content workflow. For example, the content editor role cannot publish content — only the content approver role can publish it. A content editor can create a page and set it to draft or needs review, but they can't publish it. This default workflow is often changed to suit content teams, so the moderation states might be a little different on your site.

You can change the moderation state from the content edit form. To demonstrate, let's create a standard page. I'll enter "Content moderation" as the title, and paste some test content into the Body field. Then scroll down to the "Save-as" dropdown. We can select two states: draft or needs review. Let's leave it as draft and click on Save.

So far, we've created a standard page and set it to draft. Let's go back and edit the page again. Scroll down, and we can see that the current state is set to draft. Let's change it to "Needs review".

Let's go back and edit the page. Scroll down, and the current state is "Needs review". But now we can change the state to published, which will make this page publicly accessible. Remember, the default workflow is to first set the state to draft or needs review. Then "Needs review" to published.

Let's select Published from the "Change to" dropdown, and click on Save. We've now published this page.

At this point, we've created a page and published it. Now, if we go and create a draft or needs review revision, we'll end up with two versions of this page.

Let's go and edit this page, and add a line into the body field, so we can see that something has changed, Then scroll down and select draft, and click on Save.

The draft version is visible from the "latest version" tab. Take note of this bit of text right here, new line. If we click on view, we see the published version and you can't see the two words, new line, in between these two paragraphs.

The published version is still publicly accessible, whereas you'll need to be logged in with the correct permissions to access the "latest version" tab.

Also, if you go to the content management area and then go to moderated content, you can view any revision which is set to draft, needs review or archived. Let's go ahead and edit our content moderation page, which we just created. Let's change it to needs review, and then click on save. You can see that the moderation state is set to needs review.

Then, if we edit it again and change it to published, we can no longer see this revision because it has been published. This moderated page is a great way to keep track of all draft, needs review and archived content.

If you need to look for any of your published content, you can do so from the content management area.

Let's now recap what we covered in this video. First, we discussed how content moderation works in GovCMS. Then you learnt how to change the moderation state. And finally, you learnt how to view moderated content from the content management area.

</details>
