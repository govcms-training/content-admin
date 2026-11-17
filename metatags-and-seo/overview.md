# Overview

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

When you search for something in a search engine, the results displayed are a combination of page content as well as various metatags that are set up inside Drupal to serve content so that a search engine can easily read it.

For example, if you search for GovCMS on Google you'll see:

<figure><img src="../.gitbook/assets/Screenshot 2026-06-11 at 2.45.57 pm.png" alt=""><figcaption></figcaption></figure>

If we opened the page and viewed the source code, we'd see that most of that data is being pulled from specific locations:

```
<link rel="icon" href="/themes/custom/govcms_ct_theme/dist/assets/favicon.ico" type="image/vnd.microsoft.icon" />
<meta property="og:site_name" content="GovCMS" />
<meta property="og:url" content="https://www.govcms.gov.au/content-management-and-web-hosting-government" />
<meta property="og:title" content="Content management and web hosting for government" />
```

The text that appears under the link is being sourced from the page's content for Paragraph text.

These are called metatags, and they take specific content from your content types and put them in a specific section of the website theme code for search engines to read.

While defaults are set by your developers, as Content Authors, you have some control to override values on a case-by-case basis.

When you edit a page, you'll notice in the right-hand column an accordion for **Metatags**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-11 at 3.14.51 pm.png" alt="" width="375"><figcaption></figcaption></figure>

If you expand this you'll see an extremely long list of fields, most of which are usually empty, and others that use **tokens.** These are replacement patterns using square brackets. For example \[node:title] is replaced with the title of the page.

These are all the default **metatags** that have been set by your developers. However, you can override them on a case-by-case basis by simply editing one of the fields.

While some fields make sense:

* Page title
* Description
* Page URL

Others are more unique and may not relate to your content:

* Latitude
* Fax number
* Creator's fediverse account
* Gender

{% hint style="info" %}
Metatags need to account for all types of content across the internet. If a field doesn't feel relevant to you, then you don't need to fill it in.
{% endhint %}

Realistically, the only fields that should contain information are:

* Basic tags
  * Page title
  * Description
* OpenGraph
  * Title
  * Description
  * Image

{% hint style="info" %}
OpenGraph is the standard used for social sharing, such as embeds that show up in Facebook or LinkedIn, which is why an image is often required.
{% endhint %}

Your developers can set default values site-wide, and then provide customisations per content type.

For example, the image field could be a government crest by default, but then for a news content type, it would be overridden by the thumbnail image.

{% hint style="info" %}
If you updated the metatags and they don't show up in Google search results it can be because:

1. Google has decided there's other information on the page that's more valuable to the user than what you entered
2. Google has not re-indexed the website yet (give it about 2-3 weeks).
{% endhint %}

However, if you find that a specific page has incorrect metatags in search results, you can edit the page directly, edit the metatags and select the **Save** button.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/516059431?h=da131c1b49" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn to customise the meta tags in GovCMS.

We'll cover the following two topics: We'll discuss what are meta tags and you'll learn how to customize the meta tags in GovCMS.

What are meta tags? To answer this question, we'll need to view the HTML source of this page. To view the HTML source, right click, and click on View Page Source. Don't worry about all this HTML, what I want you to focus on is this section. Meta tags are used to add context, or describe a page to search engines. The text in the meta tags is not visible on the page. However, text in the "title" tag is displayed in the tab. Often the title and description will appear in the search engine results, so it's important to make sure the meta tags have the correct information for search engine optimisation.

To help with search engine optimization, GovCMS is configured out of the box to populate some meta tags. If we take a look at the HTML again... The title tag is configured to display the page title and the site name. You also have the canonical URL, which is also configured. And the summary of the body field is automatically added to the description meta tag. That's the default configuration for meta tags in GovCMS. But you can customize the meta tags on individual pages.

Let's go and edit the page, And you should see the "Meta tags" section on the right. If you can't see this "Meta tags" section it means the content type doesn't have the meta tag field. This field will need to be added by a site builder.

If we take a look at all of the meta tag options, you can see there are a lot of things we can configure. The default configuration has the page title, description, and also the canonical URL, pre populated. These defaults can be changed if you have the site administrator role or the correct permissions. If you go to configuration and then scroll down to meta tag...you can configure the default options for all the meta tags.

Let's customize the meta tags just for this page. Click on edit. And then click on meta tags. And all we need to do is modify the meta tags in these fields. Note, that this value with the square bracket is called a token. Think of it as a placeholder that's replaced with an actual value when Gov CMS, or technically Drupal, renders it. This is similar to short codes in WordPress. If you're familiar with WordPress, node colon summary will generate a summary version of the body field. In the page title meta tag, node colon title will be replaced with the value from the title field. Let's go ahead and customize the page title.

Now let's remove the tokens, and add in some custom text. Then scroll down and click on save, We can now see that the page title has changed just for this specific page. If we view the source, we can see that the value for title has also changed.

Let's now recap what we covered in this video. First, we discussed what meta tags are, then you learned how to customize the meta tags for specific pages.

</details>
