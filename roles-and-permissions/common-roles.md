---
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
metaLinks:
  alternates:
    - /broken/spaces/yE16Xb3IemPxJWydtPOj/pages/i73g4LZQanoLj7XtSO18
---

# Common roles

Drupal websites use role‑based permissions to ensure publishing quality and to protect website stability.

GovCMS comes with the following roles out-of-the-box:

* **Content Author:** A Content Author can typically create new content, make content revisions and mark them for review by a Content Approver.
* **Content Approver:** A Content Approver can publish, archive and delete content created by Content Editors.
* **Site Administrator:** A Site Administrator can delete content, revert content revisions, place content blocks and perform other content management tasks that require special caution and experience.

However, your developers can customise these roles and permissions as needed.

### Why multiple roles?

GovCMS’ different roles are set up to restrict permissions around who can edit and approve content and who can make administrative changes to the website.

However, you can apply multiple roles to a single user.

By assigning a user both the **Content Author** and **Content Approver** role, they will be able to edit and approve content to be published.

### Customising roles

While only the above roles are provided out-of-the-box, your developers can create custom roles specifically for your website, and restrict permissions to create more granular control.

For example:

* You could create a Legal Review role with an additional permission to moderate content through the Legal Review state.
* You could create a role that only has access to create and edit content of a certain type, for example an event content type. This would give them full control over all events on the website without the permission to accidentally alter any publications or page content.
