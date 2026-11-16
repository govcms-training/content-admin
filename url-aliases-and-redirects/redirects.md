# Redirects

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

Sometimes an alternative URL is required for a web address or piece of content. This may be due to an incorrect URL being published in print, old content being deleted but the link is already widely known, or in cases where a shorter URL is preferable (for example, for a radio marketing campaign).

In these instances, a **URL redirect** is the most useful answer.

Redirects are also created automatically by GovCMS to make sure only one **URL alias** is functional and to ensure previously created URL aliases do not return “404 not found” response.

The screenshot below illustrates how redirects forward all traffic to the latest alias for a given URL.

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

URL redirects can be created automatically or manually.

### Automatic URL redirects

In the example in the previous **Manual aliases section**, we changed an automatic URL alias from **/news/national-plan-address-financial-impact-ongoing-crisis** to **/news/the-national-plan**.&#x20;

At that point, the new shorter URL alias became the sole URL alias of that page. But what would happen if someone had bookmarked the old **/news/national-plan-address-financial-impact-ongoing-crisis** address?

Thanks to the automatic setting in GovCMS, a new URL redirect was created that _redirects_ any requests from the old alias to the new one.

You can see this by editing a page that has had a manual URL alias change, and expanding the URL redirects section in the right-hand column.

<figure><img src="../.gitbook/assets/Screenshot 2026-07-07 at 2.33.13 pm.png" alt=""><figcaption><p>The old Alias has become a new Redirect</p></figcaption></figure>

You may also want to manually add another redirect for this page, for a marketing campaign for example.&#x20;

Select the **Add URL redirect** button and you'll be taken to the **Add URL redirect** page.

### Manually adding a URL redirect

You can also access the page by navigating to **Configuration**, **Search and metadata**, **URL redirects**, **Add redirect**:

<figure><img src="../.gitbook/assets/Screenshot 2026-06-09 at 3.32.53 pm.png" alt=""><figcaption></figcaption></figure>

Once on this page, enter in the new URL redirect you want to add in the **Path field**.

{% hint style="info" %}
The **Path** that you enter should be a _unique address not used elsewhere on your website_. For example, if you have an existing page with the URL alias of **/new-page**, and you try to set up a redirect for **/new-page** to **/awesome-page**, then Drupal will get confused as to where requests for **/new-page** should be sent. Should it be the redirect or the alias?

If you **need** to redirect from an existing URL alias (for example a page gets archived) there is a slightly different process that's outlined at the bottom of this page.
{% endhint %}

If you've come from the button in the sidebar while editing a node, the **To** field will already be filled in. If not, simply start typing in the name of the page you want to redirect to and use the autocomplete field to select the correct page.

<figure><img src="../.gitbook/assets/Screenshot 2026-07-07 at 2.34.49 pm.png" alt=""><figcaption></figcaption></figure>

**Redirect status** can usually be left as **301 Moved Permanently** if the path you've entered is for old content, or **307 Temporary Redirect** if this is a short-term redirect (6 months or less).

Finally, select the **Save** button.

Now, when you edit the content, you can see the new redirect in place:

<figure><img src="../.gitbook/assets/Screenshot 2026-07-07 at 2.36.10 pm.png" alt=""><figcaption></figcaption></figure>

### What's happening behind the scenes

Our test content now has four different ways to access it:

* **/news/national-plan-address-financial-impact-ongoing-crisis** (The original URL alias that is now a redirect)
* **/newest-plan** (The new URL redirect that was manually added)
* **/node/8** (The internal Drupal URL)
* **/news/the-national-plan** (The current URL alias)

However, while the user can enter any of these URLs into their browsers, they will always be redirected to the **current** URL alias, which at this point is **/news/the-national-plan**.

### Redirecting an old URL alias

Occasionally you'll have a page on your website that you archive, and you want any visitor who tries to go to that page sent somewhere else.

In this example we want to archive **/test-page** and have our visitors sent to **/why-govcms** instead.

If you try to create a URL redirect for **/test-page** to **/why-govcms**, Drupal won't know what to do, because there's an existing URL alias for **/test-page**.

Instead, you first need to archive the page and change its URL alias, freeing that address up to become a redirect.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-24 at 11.21.56 am.png" alt=""><figcaption></figcaption></figure>

In the above image you can see the workflow state is changed to Archived, and the URL alias is overridden to add **-archived** after it.

{% hint style="info" %}
You only **NEED** to change the URL alias if you plan on re-using it. If you're just archiving a page you don't need to change this.
{% endhint %}

When we save that page, the active URL alias is **/test-page-archived**, however as mentioned above in the **Automatic URL redirects** section, when we change a URL alias manually, a redirect automatically gets created.

If you edit the page again, you can see a new URL redirect has been added, redirecting **/test-page** to **/test-page-archived**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-24 at 11.49.06 am.png" alt="" width="375"><figcaption></figcaption></figure>

So all we need to do is change the destination. Select the **Edit** button to change the redirect.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-24 at 11.50.04 am.png" alt=""><figcaption></figcaption></figure>

Here we can see that the old URL alias has been converted into a URL redirect, pointing **/test-page** to our node.

Now, update the destination to the 'Why GovCMS?' page and select **Save**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-24 at 11.50.53 am.png" alt=""><figcaption></figcaption></figure>

You'll be returned to the archived node, it will show no redirects for this node, and the page is only accessible via **/test-page-archived**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-24 at 11.52.24 am.png" alt="" width="269"><figcaption></figcaption></figure>

However, if you then try to access **/test-page** you'll be taken to the **Why GovCMS?** page.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/516059309?h=afd8211eaf" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn about URL redirects in GovCMS.

We'll cover the following two topics: How URL redirects work And how to create your own URL redirect.

In the previous video, we talked about managing and creating a URL alias. Now I want to show you how to manage URL alias redirects. Managing old URLs (and making sure they still work) helps with search engine optimisation and it helps users navigate your site. The last thing a user wants to see is a "404, page not found" error. The ability to create and manage redirects is only available for site administrators, so make sure you have the correct role.

So what is a redirect? Let's start by going to the contact us page. The URL alias is "slash contact-us", but what if you just migrated over to GovCMS and the old contact us page was at "slash pages slash contact-us"? We want to keep this old URL working, so if a user goes to slash "pages slash contact-us" instead of getting a page not found or 404 error, they'll be redirected to "slash contact-us". To handle this situation we'll simply create a redirect in GovCMS.

Let's now go ahead, and create a redirect for the Contact us page so if a user goes to slash "pages slash contact-us" they'll be redirected to the current slash "contact-us" page. To create and manage redirects you must have the site administrator role or the required permissions.

Click configuration in the admin toolbar, scroll down to URL redirects, and click on "Add redirect". In "Path" add the old URL, which is "pages slash contact-us", and in the To field, add the new URL. This field is an autocomplete, so just search for the "Contact us" page and select it. Leave the redirect status to 301 (you can change it, but this will tell the search engines that the move is permanent). Then click on Save.

Now let's test this out. I'll open up another tab and go to slash "pages slash contact-us". And this now redirects us to "slash contact-us".

To keep tabs on all the incoming redirects for a page, just click on Edit. Then click on URL redirects and this will show you all the redirects pointing to this page. You can create another redirect by clicking on "add URL redirect", which will take you directly to the "add redirect" page.

Let's now recap what we covered in this video. First, we learnt how URL redirects work, then we looked at how to create a URL redirect.

</details>
