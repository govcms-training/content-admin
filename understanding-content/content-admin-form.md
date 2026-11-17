# Content admin form

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

In this example we will create a **page** by hovering over **Content**, **Add Content** and then selecting **Page**. This will present us with the Page add form.

{% hint style="info" %}
The fields here are specific to the training environment, and will differ from your agency's website. However it provides a good snapshot of common fields you'll come across.
{% endhint %}

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption><p>Creating a page in the GovCMS training website</p></figcaption></figure>

Starting at the very top we have a tabbed layout where the content author can choose to edit the **Content** or the **Banner** section.

Staying in **Content** for now, the first field is the **Title**. The title is the only mandatory field for every content type. Every piece of content in a Drupal website must have a title. This is a standard text input field, which accepts text but no styling.

Below that is the **Summary** field, which is a long text field. Similar to the title, this field accepts text with no formatting/styling.

Underneath that we have an accordion display used to group together similar fields. In this instance, **Metadata** about the page itself.

First is a **Taxonomy** autocomplete field for the page's **Topics**. By typing in the name of a taxonomy term, you can select any existing term in this field. You can also select the **Add another item** button to add additional terms. [Taxonomy](https://app.gitbook.com/s/zAp101XNX82HnyCe3C9U/taxonomy) itself is a topic covered later in training.

Next is the **Site section**. This is also a taxonomy field, however the widget only allows you to select a single, pre-existing item.

{% hint style="info" %}
Taxonomy is one of the field types where there are a number of different interfaces (known as widgets) for using it. Here we have seen an autocomplete, and now a select list.
{% endhint %}

Outside of the metadata accordion is the **Show Table of Contents** checkbox. This is a Boolean (on/off) value that the developers have set up to automatically include a dynamic table of contents at the top of the page when this option is checked.

After that is the **Components** section. Components are also sometimes called **Paragraphs.** Components provide content authors with rich and interesting content templates to use, rather than a single massive text field.

If you select the dropdown arrow beside **Add Content** you can see a list of available components that can be added to the website.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-03 at 4.56.06 pm.png" alt="" width="287"><figcaption><p>The various components available in CivicTheme</p></figcaption></figure>

{% hint style="info" %}
These are the out-of-the-box components available in CivicTheme. Your component library may vary, or your website may not even use the Paragraphs module.
{% endhint %}

Each of these **components** is built with its own custom fields and settings. You can think of these as smaller content types that are used inside your content.

{% hint style="info" %}
Developing new components is not covered in this training, however feel free to add and play around with any of the existing options.
{% endhint %}

Below the Components section is another organisational accordion, this time relating to the **appearance** of the page.

The **Thumbnail** field is a media upload field. [Media](https://app.gitbook.com/s/zAp101XNX82HnyCe3C9U/media-and-files) itself is a large topic covered later in the training.

Underneath that is a select list that will define the padding of the page element.

And finally, two more checkboxes that set different layout options.

At the bottom we have **Save as**, which is part of the [publishing workflow](https://app.gitbook.com/s/zAp101XNX82HnyCe3C9U/workflows) (which is covered in a later topic).

Below that are the **Save** and **Preview** buttons.

The right-hand menu contains a **Revision log message** text area, which will be covered in the [Revision](../creating-editing-and-archiving-content/revisions.md) topic later on. Below that is [Menu settings](https://app.gitbook.com/s/zAp101XNX82HnyCe3C9U/menus-and-navigation) (covered in a later topic), [Metatags](https://app.gitbook.com/s/zAp101XNX82HnyCe3C9U/metatags-and-seo) (covered in a later topic), Last updated date (which is automatically incremented whenever the page is edited), and [URL alias](../url-aliases-and-redirects/url-aliases.md) (covered in a later topic).

All of these **fields** together create the **content type** of **Page**.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/488350047?h=c1c437ff59" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series. In this video, you'll learn about the content form in GovCMS.

We'll cover the following two topics. You'll be given an overview of the content form, and you'll learn about how fields are reused across content types.

In the previous video, we talked about the default content types that come with GovCMS and what they're used for.

Now let's look at the content create and edit form in more detail. This is where you'll spend most of your time creating and editing content.

Go ahead and click on Add Content, then Standard Page, and let's take a look at this form in more detail.

First you have Title. This is used as the page title. Then there's Thumbnail where you can select an image as the page thumbnail.

Then we have the Body field. This is where all the important content goes. You can format the text and add links.

Then below the Body is the Attachments field. Any attached files will be displayed at the bottom of the page.

Then the Featured Image field should be used when you want to display an image above the body text on the page.

Then at the bottom, we have Save As, which allows you to set the moderation state of the page. Then finally, we have the Save and Preview buttons.

The items on the right will be discussed in other videos, so we'll cover it later. Most of these fields here, like Thumbnail, Body, Attachments, and

Featured Image, are reused on other content types. If we go back to the Add Content page and click on News and Media, you can

see most of the same fields as on the standard page. We have Title, Thumbnail, Body, Attachments, and Featured Image.

</details>
