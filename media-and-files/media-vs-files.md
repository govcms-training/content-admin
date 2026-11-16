# Media vs files

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

### Files and media — what's the difference?

You'll notice that in the secondary navigation, Files and Media are separate items.

**Files** refers to the actual files stored on the file system of your website. These are similar to files stored on your computer and only contain basic information such as:

* Name of the file
* File type (e.g. jpeg, png, pdf)
* File size
* Upload date and time

**Media** assets are entries in the website's database that reference a file, but also contain additional metadata.&#x20;

Examples of some additional data that a Media entity can hold that a File can't are:

* A user-friendly name
* Name of the user who uploaded it
* Alternative text for images
* Captions for images
* Transcripts for video and audio
* Taxonomy tags
* Full revision log

With this in mind, we always use **Media** entities when embedding graphics or documents in GovCMS websites.

### Files management interface

To access the Files management interface, click on **Content** then **Files** in the Admin toolbar.

The Files management interface presents a list of all physical files uploaded to the website. It also shows you the number of places the file is used in the column **Used in**.

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note: The **Used in** column does **NOT** display an accurate number and should **NOT** be relied on. This is a long and complicated Drupal core bug that's still being worked on.
{% endhint %}

The File list page includes filters at the top so you can search for a file by Filename, MIME type (file extension) or Status. The default order when this page loads is in order of last updated. Ordering can be changed by clicking on the small icons next to any column in the list.

Each file listing includes:

* Name
* MIME type (file type)
* Size
* Status (Permanent or Temporary)
* Upload date (date and time)
* Changed date (date and time)
* Used in (not an accurate number, see warning above)

{% hint style="info" %}
The Files list page does not provide any configuration options for files. It's mainly used to find orphaned and unused files.
{% endhint %}

### Media management interface

The Media management interface can be accessed by clicking **Content** in the Admin menu then clicking the **Media** tab in the tab area (highlighted in the previous screenshot).

The Media management interface (also known as the **Media Library**) displays a listing of all media contained on the website. It includes the following details about each item:

* Thumbnail
* Media name
* Type
* Author
* Status (Published or Unpublished)
* Updated (Last updated date/time)

It also includes a filter section so you can search for a media asset by Media name, Type (audio, image, video, etc.), Published status and Media tags. Your developers can customise this search if your media entities have any additional fields.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

The default order when this page loads is in order of last updated date. Ordering can be changed by clicking on the small icons next to any column in the list.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/501678251?h=52664feeee" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn how to view and manage files and media assets in GovCMS.

We'll cover the following two topics: How to view and manage media assets And how to see all the physical files in your site

One important feature of any content management system is the ability to create and manage media assets such as images or files. GovCMS allows you to upload and manage reusable media assets such as document files and images, which can be used across all of your content.

To view files and media assets make sure you are in the content management area and you should see the following two tabs, files and media.

Let's start with Media. If you click on the Media tab from this page, you can upload and manage the reusable media assets on your site.

If you want to upload, you can do so by clicking "Add media", to upload individual files, or if you want to bulk upload, just click on the "Upload media in bulk" button and simply drag and drop files to upload.

If you can't see the Upload Media in Bulk button, it means you do not have the Media Bulk Upload Module installed. Please contact your development partner and get them to install and configure the "Media Bulk Upload" module.

Then you can filter the assets by media name, type, and publish status.

If you want to find all media assets with the keyword of "event" in the name, You can type in the word "event" into media name and then click on filter and now only those media assets with that keyword will be returned.

Then from the action drop down, you can batch delete, publish and unpublish media assets.

But before you run an action, make sure you select a few media assets by checking the checkbox... ...or you can select all of them on this page by checking this checkbox up the top.

And most importantly, from this table you can manage your media assets. You can see a thumbnail, media name, type (which is image), the author (this is the user who created the media asset, if you can't see an author it means your user account does not have permission to view usernames) and finally you can edit and delete from the Operations columns.

Let's now click on edit for this asset. From this page, you can change the media name and you can also see the uploaded file and change the alternative text. And you can also delete the asset from this page by clicking on one of these delete links. You have a delete link next to save and you also have a delete link next to edit.

What is the difference between media and files? A media asset references a physical file stored on the file system but it also stores a lot of metadata such as the name, the author and when it was updated.

If we click on files... ...this will show us all of the physical files which have been uploaded into Gov CMS using a file or image field on a media asset or any type of content. The files will mostly be documents such as PDFs or Word documents and images. On this page, you can filter by the file name and you can see when the file was uploaded using the upload date column.

And if we click on the value in the used in column, we can see where the file is used.

Now this page isn't that useful to be honest. You'll spend most of your time on the media page managing the media assets and eventually this page will be removed.

So to summarise, if you want to see all of the physical files stored in GovCMS, you can do so from this page... ...and to upload and manage reusable media assets, you can do that from the media page.

Let's now recap what we covered in this video. First, we looked at how to view and manage media assets. And then you learned how to see all the physical files on your site.

</details>
