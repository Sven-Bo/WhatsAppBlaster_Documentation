---
description: >-
  If WhatsApp Web loads slowly or you notice unexpected behavior, updating the
  testing browser and driver can often help.
---

# How to update the Chrome Testing Browser & Driver

### Watch the tutorial below ⤵️

{% embed url="https://iframe.mediadelivery.net/play/289332/a337169b-097a-4c94-a726-f1fa288038bb" %}
Update ChromeTesting Browser - Tutorial
{% endembed %}

{% stepper %}
{% step %}
#### Download the latest Chrome Testing Browser & ChromeDriver

You need both files to update properly:

{% tabs %}
{% tab title="For 64-bit Windows (recommended)" %}
* [Download ChromeDriver (win64)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/win64/chromedriver-win64.zip)
* [Download Chrome Testing Browser (win64)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/win64/chrome-win64.zip)

_Version: 138.0.7204.92, Last updated: July 07, 2025_
{% endtab %}

{% tab title="For 32-bit Windows" %}
* [Download ChromeDriver (win32)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/win32/chromedriver-win32.zip)
* [Download Chrome Testing Browser (win32)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.92/win32/chrome-win32.zip)

_Version: 138.0.7204.92, Last updated: July 07, 2025_
{% endtab %}
{% endtabs %}

Extract both zip files.
{% endstep %}

{% step %}
#### Delete the old Chrome Testing Browser

1. Go to this folder:\
   `C:\Users\<YourUsername>\AppData\Local\SeleniumBasic`
2. Delete the folder named **chrome-win64**\
   \&#xNAN;_(This folder contains the old version of the testing browser)_

<figure><img src=".gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Move the files to the SeleniumBasic Folder

1. Copy the extracted `chrome-win64` folder into:\
   `C:\Users\<YourUsername>\AppData\Local\SeleniumBasic`
2. Replace the existing `chromedriver.exe` in the same folder with the new one from the `chromedriver-win64` zip.

Your `SeleniumBasic` folder should now contain:

* A new `chrome-win64` folder
* The updated `chromedriver.exe` file
{% endstep %}

{% step %}
#### Delete the ChromeUserData Folder

1. Go to the folder where your `WhatsApp_BOT_PRO.xlsm` file is located
2. Delete the folder named `ChromeUserData`\
   This clears any cached settings or login sessions.

<div align="left"><figure><img src=".gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}
