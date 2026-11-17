# User management

User management is accessed via the **People** menu item. It's generally handled by a website's Site Administrator(s).&#x20;

Content Authors and Content Approvers have limited access over **user administration**, so you may not be able to see all the items in the **People** menu. Below is more information for those who do have user administration access.&#x20;

Select the **People** tab from the main menu to see all the people/users for your website.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption><p>The People administration section</p></figcaption></figure>

There are a number of distinct functions:

1. The **Add user** button allows you to create new users
2. The **User table** is a full list of all users on the website, as well as if they're active and when they last logged in
3. The **Bulk actions** select list at the bottom allows you to perform certain actions on multiple users at once.

{% hint style="info" %}
All GovCMS SaaS websites will have a **super user** at the bottom of the **People** table. The username will appear random and have no role, and will often appear as Blocked. This is an administrative user that the Service Desk uses when required. The super user is not editable.&#x20;
{% endhint %}

### Adding a user

Select the **Add user** button to add a new user to your website.

You'll then be asked for some mandatory information:

* **Email address**: This can be any valid email address.
* **Username**: This is usually the person's name. This can be used when the user is logging in, instead of the email address. It's not usually ever shown to the public.
* **Password**: The password must be at least 15 characters, have uppercase and lowercase letters, and include a number and special character.
* **Status**: Whether the user account is **Active** or **Blocked**.

Additionally you can check a box to have the CMS send the user a welcome email. &#x20;

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption><p>Adding a user, filling in all the required fields</p></figcaption></figure>

Finally, scroll down and select **Create new account**.

The form will reload with the following message:

<figure><img src="../.gitbook/assets/Screenshot 2026-06-03 at 2.26.10 pm.png" alt=""><figcaption></figcaption></figure>

The new user can now login with the defined username and password. However, they don't have any roles assigned to them yet.

Select the **People** tab to return to the People page, and you'll see the new user account in the table.

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption><p>New user has been added, but the Roles section is empty</p></figcaption></figure>

### Modifying role assignments

To grant or revoke a Role from a user, check the box beside the user's name, then scroll down to the select list at the bottom and choose the action you'd like to take.

In the screenshot below, the new **Sample user** is checked and **Add the Content Author role to the selected user(s)** has been selected from the dropdown list at the bottom.&#x20;

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption><p>Adding the Content Author role to the Sample user account</p></figcaption></figure>

Next, select **Apply to selected items** and the Sample user is updated with the new role.

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

A success message is displayed and I can see the Sample user's Role has been updated.

The same process can be used to add or remove any role that the **current user** has.

{% hint style="info" %}
Drupal uses an additive role system, meaning that any user can have any combination of roles, and their permissions are additive. So if you have a specific role that only has permission to create pages, and another role that only has permission to create events, assigning both roles to a user  gives them permission to add both pages **and** events.
{% endhint %}

### Editing a user account

By selecting the **Edit** button on the far right of any user row, you'll be taken to the **Edit user screen**.

This allows you to edit the user's email address or username, reset their password, or block/activate them.

If **your** user role has permission to administer TFA for users, you'll also be able to do that when editing a user.

