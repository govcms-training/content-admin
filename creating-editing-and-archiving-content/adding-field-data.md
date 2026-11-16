# Adding field data

As previously mentioned on the [Fields](../understanding-content/fields.md) page, GovCMS supports a number of different field types. Each field can have its own requirements and this can differ between instances.

Additionally, GovCMS comes with the Paragraphs module, sometimes called Components. This allows developers or advanced content editors to create repeatable packages of fields that Content Authors can use to create rich and engaging content.

### Fields

Each field type has its own **configuration** and **settings**.

For example, below is a standard **Textarea field.** The following items have been set in the field configuration:

* Its label, 'Body'
* A separate, unformatted Summary that can be provided by selecting **Edit summary**
* The field is not mandatory&#x20;
* A text format of Rich text has been provided.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.36.10 pm.png" alt=""><figcaption></figcaption></figure>

Whereas the example below is also a **Textarea field**, however it has a different label, it is mandatory field, it doesn't allow a separate summary and no text format is enabled.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.39.32 pm.png" alt=""><figcaption></figcaption></figure>

This shows how even technically similar fields can be quite different depending on how your developer has configured them.

Another prime example of this is [Taxonomy](../taxonomy/what-is-taxonomy.md) fields. Taxonomy will be covered later, but it's a great example of a single field type that can have **different configuration options** that change how the field is authored and displayed.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.44.01 pm.png" alt="" width="375"><figcaption><p>Comma separated list, without the ability to dynamically add new terms</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.45.04 pm.png" alt="" width="222"><figcaption><p>Radio list where only one item can be selected</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.45.47 pm.png" alt="" width="219"><figcaption><p>Checkboxes allowing for multiple options to be selected</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.46.40 pm.png" alt="" width="563"><figcaption><p>Autocomplete, with the ability to add new items that are not already present in the list</p></figcaption></figure>

As there are 16 different field types, with different interfaces depending on configuration options, it would be too exhaustive to document them fully here.&#x20;

{% hint style="info" icon="dumbbell" %}
If you're currently doing the GovCMS training, you can add as much test content on your training environment as you like, and by testing out the various content types and paragraphs, you'll be able to experience most of the available field types.
{% endhint %}

### Paragraphs / Components

**Paragraphs** (cometimes called **Components**) are sets or groups of fields that your developers have created so you can add rich content to your website in a repeatable and consistent manner.

You can think of them as small self-contained [content types](../understanding-content/what-are-content-types.md) that are used inside an actual content type.

Some examples of Paragraphs on the training environment are:

#### Callout

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

Above is a Paragraph called **Callout**, that contains multiple text fields, a link field and options to configure theme and spacing.

This Paragraph allows Content Authors to easily create a Callout and have it display consistently across the website, without having to remember things like what size font the heading text should be, or what styles should be applied to the buttons.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 1.58.42 pm.png" alt=""><figcaption></figcaption></figure>

#### Accordion

Accordions on the Training website are unique in that they are a **Paragraph with embedded Paragraphs**.

In the screenshot below there is a Paragraph called **Accordion**, which includes fields for Expand all, Theme, Vertical spacing and Background. But then it also has a field called Panels, which is a reference to another Paragraph called **Accordion panel**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-30 at 2.00.40 pm.png" alt=""><figcaption></figcaption></figure>

This allows Content Authors to create the accordion container and then have as many individual accordion panels as they need.

While the creation of new Paragraphs is only covered in the Advanced Content Management training, it's important to notice that even though Paragraphs can be complicated and have additional elements embedded in them, they're all built from the same simple fields.

Once you're comfortable with how a text field behaves and how a Rich text editor works, you'll be able to edit any content on your website with ease.
