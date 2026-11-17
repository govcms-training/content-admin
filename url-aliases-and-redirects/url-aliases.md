# URL aliases

A URL (**Uniform Resource Locator**) is a web address. While some can be long and difficult to remember, others can be simple and descriptive.

For example, the URL below does **not** provide a good description of the content it will provide to a site visitor:

* https://government.gov.au/protection/safety/category13/93891

This URL, on the other hand, provides clear information about the content:

* https://government.gov.au/support/contact-us

Drupal creates and maintains its own internal URL for each piece of content.

These URLs contain the pattern **node/** plus the content's ID number, for example:

* https://government.gov.au/node/15

However, while this URL is short, it's not very descriptive. This is why Drupal uses **URL aliases**.

### URL aliases

A URL alias is a (usually) automatically created, unique, specific, descriptive URL for a page on a website. There are three main benefits of using a URL alias:

* URL aliases create more descriptive and meaningful URLs for users
* URL aliases are read by search engines, and form an important component of search engine optimisation (SEO)
* URL aliases make websites, their links and results in search engines look more professional.

URL aliases are generally the best type of URL for site visitors.

URL aliases are automatically generated when a piece of content is created or updated based on a set pattern. This pattern is configured by your developers, and can differ between content types.

For example, a common pattern for basic pages could be:

```
[node:menu-link:parents:join-path]/[node:title]
```

This will generate the URL alias based on the menu structure of the page and the page's title. &#x20;

Whereas a pattern for an event could simply be:

```
events/[node:title]
```

{% hint style="info" %}
In Drupal, if you see square brackets it's likely a **token**. This is a placeholder for information that will be sourced later. For example the pattern **events/\[node:title]** will become **events/my-new-event** if the **title** of content was **My new event**.
{% endhint %}

There are some additional settings that it are important to know (although your developers will set these):

* Spaces are replaced with dashes
* All URL aliases will be lowercase (URLs should never be case sensitive)
* Certain words will be removed such as: a, an, as, the, than, with, etc.
* Punctuation will either be removed or replaced with dashes.

{% hint style="info" %}
Content Authors are **not** required to set up the URL patterns or learn tokens. In the next section you'll learn how to manually override these patterns and tokens, but it's important to learn how they're generated in the first place.
{% endhint %}
