# Moderation states

Content moderation is a GovCMS module that provides a default workflow process. In this model content has four "states":

* **Draft**: In this state the changes are not available to the public.
* **Needs Review**: The changes are still not available, ideally they are reviewed and approved by a second user.
* **Published**: The changes are made live for the public.
* **Archived**: The page is taken **off-line** and not visible to the public, but kept in the CMS for record-keeping.

Content _transitions_ as it moves from one state to another.

Different people with different roles have different permissions regarding what actions they can perform in the content workflow. For example, in the default setting, Content Authors cannot publish content. Only a Content Approver can approve content.

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

This default workflow can be extended by a developer or advanced content editor.

{% hint style="info" %}
In the GovCMS training environments you're given both Content Author and Content Approver roles.
{% endhint %}
