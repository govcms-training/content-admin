# Viewing submissions

Using the **Results** tab in the **Webform** menu, you can access all the submissions saved into the database.

The **Results** section has its own submenu containing the following sections:

<figure><img src="../.gitbook/assets/Screenshot 2026-06-11 at 10.46.52 am.png" alt=""><figcaption></figcaption></figure>

### Submissions

The submissions page includes a table of all submissions for the webform. There's a basic filter at the top, and you also have the ability to edit or delete any submission.

{% hint style="info" %}
Editing a submission after it's submitted won't trigger any Emails / Handlers that may be attached to the form.
{% endhint %}

### Download

This page allows you to download all the submissions into a format that can be opened by Excel/Sheets.

Leave the **Export format** to Delimited text, and scroll down to the **Column options** accordion. Expanding this section will allow you to choose which fields you export.

By default, the export will include technical fields like:

* Submission URL
* Three date fields
* Language
* Locked status
* Metatags

It's advisable to uncheck these options and just export the captured field data.

You can also use the **Download options** section to limit the export to a set period of time.

Once you've configured your options, select the **Download** button.

### Upload

Upload allows you to upload submissions in bulk into the webform. This feature is experimental and not supported by GovCMS at this time.

### Clear

Clear will allow you to delete all submissions. As the warning states, this action can **NOT** be undone, and to retrieve the submissions would require a full website restoration from a backup.

The **Clear** feature is useful if you've been conducting testing for your form and you're now about to go live.
