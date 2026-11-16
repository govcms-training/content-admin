# Replacing files associated with media

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

{% hint style="info" %}
The Media Entity File Replace module is an optional module in the GovCMS distribution. If you do **not** see the **Replace file** field when editing a media entity, you'll need to contact your developer to get the module enabled.
{% endhint %}

The Media Entity File Replace module allows you to replace the file associated with a media entity, ensuring that your media asset always has the most up-to-date file attached.

This is very useful if you have a media asset (such as a publication) that's embedded in multiple places around your website, but you need to upload a newer version of the file.

If you upload a new media asset, you'd then need to go through your entire website and find all the places where your original media asset was used and then replace it in all those places. You'd also end up with the old file still on your website and potentially indexed by search engines.

The alternative is to use the **Media Entity File Replace** module to **edit** the existing media asset, and replace the file. This overwrites the old file with the new one, ensuring that all links and references now point to the new file.

### How to use the file replace feature

1. Open the **Media Library** and find the media asset you want to update
2.  Select the **Edit** button on the corresponding row&#x20;

    <figure><img src="../.gitbook/assets/Screenshot 2026-06-09 at 2.23.28 pm.png" alt=""><figcaption></figcaption></figure>
3.  In the **Replace file** section, select the **Choose file** button

    <figure><img src="../.gitbook/assets/Screenshot 2026-06-09 at 2.23.16 pm.png" alt=""><figcaption></figcaption></figure>
4. Browse to the new file you want to upload (Note: It must be the same filetype as the original, e.g. you can't replace a PDF with a DOCX file)
5. Ensure that the **Overwrite original file** checkbox is checked
6. Scroll down and select **Save.**

The media asset will now have your new document uploaded.

{% hint style="warning" %}
Your old file may still be cached by the GovCMS caching system. As the cache time for documents is 30 days, users may not see the updated document right away. You should use the GovCMS Akamai Purge module to ensure your new document file is the one served to customers. If you don't know how to use the module, contact your developers.
{% endhint %}

### 🎥 Video

{% embed url="https://player.vimeo.com/video/501680070?h=750ab57092" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn how to delete assets and replace files.

We'll cover the following two topics: How to delete media assets and discuss deleting physical files and how to replace files in a media asset

We know how to upload files and create media assets. But let's look at how you can delete media assets. To demonstrate how to delete media assets, let's upload an image.

Make sure you're on the media page. Then click on add media, and then image and I'll upload a file called "delete dash file". I'll enter in "Delete file" as the name, the alternative text, and then click on save.

At this point we've uploaded a file and created a media asset... ...and if we go into the asset we can see the file. If we click on thefiles tab we can see the physical file here, delete-file.jpg and you can see it is used in two places by looking at the used in column. But this is just the number of revisions, because if we click on the link you will see that it's part of the delete file media asset.

To delete a media asset and its physical file is relatively straightforward. First, you want to make sure that your user role has access to delete files and media. And make sure that your GovCMS website has the "Media File Delete" module installed and configured. If you need any of this configured, contact your service provider.

To delete a media asset, click on the Media tab, then from the Operations column click on Delete. An asset can also be deleted by clicking into it... ...and clicking on the Delete tab above, or at the bottom of the page next to save.

If you click on Delete, make sure you check "Also delete the associated file" checkbox. This will delete the physical file attached to the media asset. If you can't see the checkbox it means you do not have permission to delete files or the "Media File Delete" module hasn't been installed. Then click on Delete.

Now if we go to Files, we shouldn't see the delete file image, as it's been deleted.

You now know how to manage assets, how to create and delete them. Now, let's look at how you can replace the uploaded file in a media asset. To demonstrate let's go ahead and create a media asset for a PDF document.

Click on add media, and then document. I'll enter "User document" into the name field and upload this user dash document version one... and then click on save.

Then, if I go into the document and click on the file, we can see that it's version one and the title is user documentation.

A quick side note, how the PDF gets displayed on your computer could be different. This video uses Chrome and it displays the PDF in a pop-up window, but it may look different on your computer.

Take note of the path up the top here; "Sites slash default slash files slash 2025 dash 09". This is standard GovCMS. When you upload a file it will save it into "sites slash default slash files". Then it will put the file in a folder with the year, then a dash then the month. This is the year and month when the file was uploaded. Next is the actual file name "user dash document dot PDF". You can copy this URL to access the file directly. But what if you want to replace this file with a new version?

Let's close the pop-up. Then click on remove, and then select version two and drag it across. Finally, click on save.

Let's now go back into the document. And then click on the file. Notice that the PDF is different because it is version two, but the file name has also changed.

Notice in the URL, there's an underscore zero in the name. The full URL to the file has changed. Drupal, which GovCMS is built on, will add a number to the file name and increment it, because a file with the same name "user dash document" already exists. It hasn't replaced or deleted the old file. This can cause problems if you've linked directly to the file, for example in an email newsletter, because you haven't technically replaced the old file.

There is a solution for this problem. If your media edit page looks like what's on screen, it means the functionality to replace files hasn't been set up. You need to create a GovCMS service desk ticket, and ask for "media entity file replace", and they'll be able to set it up on your website. Once the module is installed... ...you'll be able see the file replace functionality, and most importantly we have this option, "overwrite original file".

Click on add media, Then document. And I'll enter in "Website report" as the title. And select version one, of the website report. Then click on save.

And then if we go into the document And click on the file. we can see that it's version one.

Let's close this and replace this file. So let's go ahead and get version two and make sure overwrite original file is checked, and then click on save.

Let's go back into the document. And click on the file.

If you see the old version, that's because it has been cached locally...just do a hard refresh. Press control F5 if you're on Windows, or command R if you're on a Mac. Let's go ahead and do a hard refresh... ...and now we can see version two of the file. ...and most importantly the file name has stayed the same. So now we won't have broken links or out of date content.

This functionality may not be set up on your website. If you don't see this "replace file" field, then it's definitely not set up. You need to create a ticket on the GovCMS service desk and ask for media entity file replace, and they'll set it up for you.

Let's now recap what we covered in this video. First you learnt how to delete a media asset and physical files. Then we looked at how to replace existing files in a media asset.

</details>
