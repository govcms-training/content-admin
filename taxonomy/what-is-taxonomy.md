# What is taxonomy

{% hint style="info" %}
The page has a video that explains the information located at the bottom of the page.
{% endhint %}

Taxonomy is the science of classification. In Drupal we use taxonomy **vocabularies** and taxonomy **terms** to classify and categorise our content.

A taxonomy **vocabulary** in Drupal is a container used to group and organise a collection of related categorisation terms (known as taxonomy **terms**).

Correctly categorised content can provide better discoverability and search, as well as allow for cross-referenced content.

{% hint style="info" %}
You might also know this concept as **tags** or **topics** from other CMSs.
{% endhint %}

### What are taxonomies used for?

Taxonomies are used to help categorise your content for a number of reasons.

#### Better content discoverability

Tagging content with taxonomy terms allows you to group similar content, which makes searching for content a lot easier. For example on the [GovCMS Site Gallery](https://www.govcms.gov.au/gallery) page, each of the websites in the gallery is a node of a content type called **Website**. And each piece of content contains various taxonomy tags such as the Drupal version, jurisdiction, website type, etc.

This allows website visitors to quickly filter out irrelevant results and find exactly what they're looking for.

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption><p>Filtered based on the Taxonomy Terms of SaaS and State</p></figcaption></figure>

#### Show related content

When content is tagged correctly, you can show content that's related to what the user is currently viewing.

For example if they're viewing a news story about a certain government policy, you could automatically have a list of other content on your website that relates to that same policy, without having to constantly curate a list manually.

### 🎥 Video

{% embed url="https://player.vimeo.com/video/516059762?h=43d9583834" %}

<details>

<summary>Video transcript</summary>

Welcome to the GovCMS Introduction to Content Management series.

In this video, you'll learn how content is categorised in GovCMS using the taxonomy system.

We'll cover the following two topics: how to create and manage taxonomy terms, and then we'll look at how to categorize pages from the content edit form.

The taxonomy system in GovCMS is used to categorise content. To see all the category types, or as they're called in GovCMS "vocabularies", go to Structure, and then click on taxonomy. You'll need to have the content author or the content approver role to access this page. GovCMS comes out-of-the-box with four vocabularies. But your site may have extra vocabularies, because it's not uncommon to create custom ones.

If we click on "List terms" on "blog article categories", we can see all the category items, or as they're called in GovCMS, taxonomy terms. From this page, you can see all the available terms, and we can create new ones.

Let's go ahead and create a new term. Click on "Add term", and enter Drupal into the name, and then scroll down and click on Save. Here you can see the new term that we just created. You can also edit and change the name of existing taxonomy terms.

Click on Edit, change the name, and then click on Save. This is the great thing about the taxonomy system. None of the names are hard coded. If you need to change any of them, come to this page and edit them.

To categorize a page, we'll need to do it from the Content Edit form. The Blog Article Categories Vocabulary is only used on the Blog Article Content type. Event categories only on the Event Content type. Media tags are used on media entities, and the News Categories Vocabulary is used on the News and Media Content type. Let's go ahead now and categorize a Blog Article with the new Drupal term, which we just created.

Go to Content, and edit a Blog Article. Scroll down to the Categories Auto Complete field, and we can now select one of the terms in the vocabulary.

Let's go ahead and search for Drupal, select it, and scroll down and click on Save. And if we go to the Blog Article, we should see the new category right here.

Let's now recap what we covered in this video. First, we looked at how to create and manage taxonomy terms. And finally, you learned how to categorize a page using the Content Edit form.

</details>
