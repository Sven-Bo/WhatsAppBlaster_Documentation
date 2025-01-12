# How to configure the backend settings sheet

When the WhatsApp Blaster bot automates tasks, it uses something called **XPaths** to find and interact with elements like buttons and text fields in WhatsApp Web. Sometimes WhatsApp updates their page structure, which means these XPaths need to be updated too. Don't worry—I handle most of this automatically in the background for you.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

#### Retrieve Latest XPaths

This setting tells the bot whether it should grab the latest XPaths from my server:

* **True** (Recommended): Keeps everything running smoothly by automatically updating to the latest XPaths when you start the bot.
* **False**: Stops the bot from getting updates from my server. This is mainly for debugging or testing purposes, and in general, you won't need to change it.

{% hint style="info" %}
**Note:** It's best to keep this set to **True** so that the bot stays updated and works reliably.
{% endhint %}



**XPaths Version**

The **XPaths Version** setting lets you choose between two different sets of XPaths: **Version A** or **Version B**.

* **Version A** and **Version B** are generally the same.
* In rare cases, WhatsApp might gradually roll out changes to some users. Having two versions helps ensure that the bot can adapt to these changes.

{% hint style="info" %}
**Tip:** You can leave this set to **Version A** by default. No need to worry about this unless instructed otherwise.
{% endhint %}
