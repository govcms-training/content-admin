# Manual aliases

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

Despite your website automatically creating aliases for you, you can manually override these on a case-by-case basis if needed.

{% hint style="info" %}
The URL alias is the final home address of your piece of content. It should make sense logically and be as permanent as possible. If you just need a short URL alias for a marketing campaign, you should use a URL redirect, covered in the next topic.
{% endhint %}

Sometimes the automated system can't account for all possibilities and it creates a URL alias that isn't quite right.

For example if you have a news article that was called "The national plan to address the financial impact of the ongoing crisis" your automatic URL alias might end up correctly being generated as:

```
https://government.gov.au/news/national-plan-address-financial-impact-ongoing-crisis
```

However, you could easily override this to be something easier to distribute:

```
https://government.gov.au/news/the-national-plan
```

### How to set a manual URL alias

1. **Edit** a page
2. In the right-hand column, make sure **URL alias** is expanded
3. Uncheck **Generate automatic URL alias** (this will unlock the URL alias text field)
4. In the **URL alias** field, enter in your new URL alias, ensuring that you start with a backslash

<figure><img src="../.gitbook/assets/Screenshot 2026-06-09 at 3.22.30 pm.png" alt="" width="375"><figcaption></figcaption></figure>

5. Click the **Save** button.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/516059128?h=ca4514f413" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn about URL aliases in GovCMS.

We'll cover the following two topics: What is a URL alias? And how to customise them

The URL to a page plays an important part in any website, not just GovCMS. A good URL can help with search engine optimisation and information architecture. And it's a better user experience if you add specific keywords in the URL.

So let's take a look at this event page for example. And let's take a look at the full URL in the address bar: - The first part is the domain name and this would be something.gov.au. - And then after that we have what's called in GovCMS the URL alias. In WordPress it's called Permalink and in other CMSs it's called a slug. But in GovCMS and Drupal it's called a URL alias.

The creation of a URL alias is configured by the content type. When you create a page, an alias is automatically created. GovCMS comes with these patterns already configured.

Let's go back to the content management area. So for example, if we look at a standard page... ...the alias is based off the page title. It'll be just "/", then the title.

And if we take a look at an event. ...you can see that the alias starts with "events" slash, then the title of the event.

And if I go to configuration, then URL alias, and click on Patterns, then we can see what GovCMS comes with out-of-the-box. I should mention that to access this page you'll need to have the site administrator role and the patterns could look a little different on your site, as it's common to change the patterns depending on the site architecture.

We talked about what a URL alias is and how they're automatically generated. But now let's create a page and customise the alias.

Click on Add content, and let's create a News and media page. Enter in the title of "Latest agency changes", and add some test content into the body field. Scroll down and save it as "Needs Review"... ...and then publish it.

Up the top, you can see the URL is slash "news-and-media" slash and then the title of the news and media page is used in the URL alias, which is "latest dash agency dash changes".

But what if we want to customise the URL alias just for this page? We can do that by clicking Edit, and in the right-hand column, you should see URL ALIAS. If you can't see it, then you need to be given access to this section. You can see that the checkbox "Generate automatic URL alias" has already been checked — that's why the alias was automatically created.

But if we uncheck the checkbox... we can customise the alias. So let's remove the word "latest-" Scroll down and click on Save.

Now you can see the URL alias has just been changed on this page. It's no longer "latest dash agency dash changes", it's "agency dash changes"."

Let's now recap what we covered in this video. First, we learnt what a URL alias is, then we looked at how to customise them.

</details>
