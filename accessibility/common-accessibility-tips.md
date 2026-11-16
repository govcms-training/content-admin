# Common accessibility tips

### Headings

A common tool used by screen-reading software is the ability to list out all the headings on a page, in order. Pay attention to the structure of your headings.&#x20;

As a rule, your page should only ever have one Heading 1, which is the page title.

All content that you edit should start with Heading 2s with nested Heading 3s.

Sometimes, it may be more visually appealing if a certain heading is smaller or larger, and this should be done using the WYSIWYG editor styles, NOT with illogical heading orders.

**Note:** Properly structured headings also improve search engine and AI index optimisation.

### Links

Another common tool is to read out all the hyperlinks on a page. This can be useful for vision-impaired users to know what content the site is linking to.

If all the links are the words "read more" or "click here", this provides zero context to the user in terms of where the link will take them.

Use contextual links, linking on words like 'Download the annual report'.

### Images

Luckily when uploading media assets in Drupal you're forced to provide alternative text. Unfortunately there's nothing in the code that requires you to provide accurate alt text.&#x20;

You should provide concise alternative text that describes an image’s purpose. Acceptable alternative text would be:

* Two people standing at a desk looking at a laptop
* The Sydney Opera House
* Children riding in a school bus

Purely decorative images that provide no purpose and add no context should be given a single space (" ") as their alternative text.

{% hint style="info" %}
The implementation of a blank alt text can differ between themes. You should contact your developers for help in how to best provide alt text for images.
{% endhint %}

Images should **NEVER** be used to simply provide text in a unique colour or font.

### Tables

Tables should only be used for tabular data, and you should apply correct header cells and columns where appropriate.

Tables are **NOT** to be used for layout purposes.

If you're thinking about adding content in a table, and it's **not** numerical data, stop and think about if that same information can be added in **any other way** first.

You should also consider that even numerical data displayed in a table can be difficult to view on any mobile device with a limited screen width.

### Documents

Documents should be uploaded ideally as a matched pair in two formats, this reduces the risk of a user not being able to access the information due to not having the correct software.

However, most users can open PDF files, as this is now widely supported in web browsers.

{% hint style="info" %}
Just because a file is a PDF doesn't mean it meets the requirements, as some PDFs simply contain a photo of text, which will also be unreadable by screen-reading software.

Please make every attempt to create accessible PDF files before uploading them to your website.
{% endhint %}

### Understandability and readability

Two often overlooked accessibility requirements are understandability and readability.

#### Understandability

Pages should have logical layouts and information should follow the standard flow of left to right, top to bottom.

You should ensure text is broken up into paragraphs of average length, and forms should be divided into pages rather than overloading the user with hundreds of fields at once.

A good self-test for this is: How would you feel if you were asked to understand a page after 9 hours of in-person meetings at 6pm on a Friday? If you're overwhelmed by the content and find it difficult to understand, so will others.

#### Readability

You should aim for your content to be understood by those of a high school reading level. Pages that require a university- or doctorate-level education to understand them isolate a huge portion of our audiences.

The Flesch-Kincaid Grade Level is a common tool used to assess the readability of content, and there are many tools online that assess your content.

Readability also covers acronyms and technical definitions, two concepts used a lot in government. Ensure that acronyms and definitions are explained to users the first time they are presented, and consider adding a glossary to your website if your subject matter contains lots of acronyms and/or definitions.&#x20;

### Useful resources

* [W3 WCAG 2.2](https://www.w3.org/WAI/WCAG21/Understanding/)
* [Digital Service Standard](https://www.digital.gov.au/policy/digital-experience/digital-service-standard) for Australian Government
