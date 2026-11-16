# Scheduled publishing

Scheduled transitions allows GovCMS users to set a date and time for a moderation state to transition from one to another.

This usually takes the form of **Needs Review** transitioning to **Published**.

### ⚠️ Important disclaimer ⚠️

While you can set a scheduled transition to take place at a set date and time, that's not the specific **TIME** that your change will be actioned.

This is due to a system called Cron that manages the scheduled tasks on the GovCMS hosting platform.

On a normal, standalone website, Cron may be configured to run every 5 minutes, meaning that anything that the website wants to schedule for the future will be actioned at some point every 5 minutes.

However, due to the scale of GovCMS, our Cron schedule is every **one hour**.

And again, due to the scale of GovCMS, we can't have all 400+ websites running a task at the exact same time as each other, as this would overload the platform.

So instead, each website is given its own unknown minute each hour when it runs its Cron tasks to even out the load on the platform.

What this means, is that if you schedule your transition to **Published** at 2:30pm, and your website's  minute happens to be set to 31, then your content will be published at 2:31pm.

However, if your website's minute is set to 29, then your content won't be published until 3:29pm.

All we can guarantee is that your scheduled transition will take place **at some point within 1 minute, and 1 hour from the time you set**.

{% hint style="danger" %}
Do not use scheduled transitions for time-sensitive information such as Budget-related content.
{% endhint %}

### How to schedule a transition

To schedule a transition for a page, browse to it and then select the **Scheduled transitions** tab in the page edit menu.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 12.21.51 pm.png" alt=""><figcaption></figcaption></figure>

This will show a summary of the current transitions that are scheduled for this page.

Select the blue **Add Scheduled transition** button.

You'll be presented with the the list of revisions, as well as a dropdown list for which transition you want to schedule and what date and time.

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

Select the options that you want and select the blue **Schedule transition** button.

You'll be returned to the list of transitions with your new schedule listed.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-10 at 2.52.05 pm.png" alt=""><figcaption></figcaption></figure>

You can use the options in the **Operations** dropdown menu to reschedule or delete the transition. This doesn't delete the revision itself, just the schedule.
