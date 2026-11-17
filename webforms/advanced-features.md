# Advanced features

{% hint style="info" %}
Webforms is a powerful tool with advanced features that can be difficult to use. If you're considering building a complicated form, we suggest you contact a developer or service provider for help.

Additionally, there are some form features outside the ability of Webforms, and you may be better to use a third-party form provider and embed that in your website instead.
{% endhint %}

### Conditionals

The most common advanced feature of a webform is the ability to show and hide fields conditionally, based on user inputs.

In the webform example below, there's a checkbox called **Show name field**, and then a text field called **Name**. If you viewed the form right now, both fields would be visible.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 4.57.41 pm.png" alt=""><figcaption></figcaption></figure>

However, if you select the **Edit** button for **Name** and select **Conditions** in the tabs at the top of the sidebar, you'll see the **Conditional logic** generator.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 4.58.35 pm.png" alt="" width="375"><figcaption></figcaption></figure>

Using the select lists, you can choose what state the field will be in, depending on the conditions  set. It's easiest to think about it as a sentence:

This field will be **Visible** if **All the following is met**, **Show name field** is **Checked**.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 5.01.27 pm.png" alt="" width="563"><figcaption></figcaption></figure>

Now if you scroll down and select the **Save** button and then **view** the webform, the **Name** field only appears once the **Show name field** checkbox is checked (see below).

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 5.02.35 pm.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 5.02.45 pm.png" alt="" width="375"><figcaption></figcaption></figure>



{% hint style="info" %}
When setting up conditionals, you can only affect fields that are positioned **AFTER** it in the order. In this example, we couldn't set up the **Text field** to affect the visibility of the **Checkbox**, because of the order they appear in.
{% endhint %}

### Advanced and Access tabs for fields

Each field also has an **Advanced** tab and an **Access** tab.

**Advanced** allows you to set a default value for the field as well as define the HTML wrapper and CSS classes and markup. This is for developers to style the fields.

**Access** allows you to define which roles can access this field, however since webforms should only ever be used by the public, this is not required.

### Form settings

Each form also has settings that are applied across the entire form, not just each field. This can be accessed by selecting the **Settings** tab in the webform navigation.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-11 at 9.26.09 am.png" alt=""><figcaption></figcaption></figure>

This will display a secondary navigation with the sections shown in the above screenshot.&#x20;

{% hint style="info" %}
These sections each have numerous configuration options that you can adjust. Below we cover the important ones.

Each field has a question mark icon beside it that, if you hover over, will display some useful context about what that setting does.
{% endhint %}

#### General

**Disable saving of submissions**. By default all webform submissions are saved in the database, however with this option enabled they are NOT saved, and instead are only available when the form is submitted and sent via the **Email / Handlers** option (covered below). This can be useful to prevent retaining too much public data, or while testing the form during development.

#### Form

**Form status**: Determine if your form is open or closed to submissions. Useful for limited time application forms.

**Form wizard settings**: This allows you to configure how the form will display if you're using a multi-page layout.

#### Submissions

**Submission behaviours**: This section allows you to disable logging of IP data for submissions, which may be required by your legal or cyber security team.

#### Confirmation

In this section you can define what happens when the user finishes the form. For example, they could be sent to a dedicated **Thank you page** on your website, they could see a simple **Thank you message** or the form could reload ready for another submission.

#### Emails / Handlers

This section allows you to configure if an email or remote post action should be taken on submission.&#x20;

Emails can be configured to:

* Send an email to a static address each time
* Send an email to a different address, depending on what options were selected in the form
* Send a simple confirmation email back to the user's email address if entered in the form.

Handlers allow you to submit the data to a third-party system such as Mailchimp or Salesforce.

#### Access

Similar to the Access section available for each field, this allows you to configure the access per role. However, since webforms should only be used for public submissions, this section is not really used.
