# Resolving 1000 SeleniumError

If you encounter the error **1000: SeleniumError - disconnected: Unable to receive message from renderer**, it is usually caused by an outdated **Chrome test browser** or **ChromeDriver**.

<div align="left"><figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure></div>

### Step 1: Update Chrome Test Browser and ChromeDriver

* **Download the latest versions ⤵️:**

{% tabs %}
{% tab title="For 64-bit Windows (recommended)" %}
* [Download ChromeDriver (win64)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.94/win64/chromedriver-win64.zip)
* [Download Chrome Testing Browser (win64)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.94/win64/chrome-win64.zip)

_Version: 138.0.7204.94, Last updated: July 11, 2025_
{% endtab %}

{% tab title="For 32-bit Windows" %}
* [Download ChromeDriver (win32)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.94/win32/chromedriver-win32.zip)
* [Download Chrome Testing Browser (win32)](https://storage.googleapis.com/chrome-for-testing-public/138.0.7204.94/win32/chrome-win32.zip)

_Version: 138.0.7204.94, Last updated: July 11, 2025_
{% endtab %}
{% endtabs %}

* **Extract the downloaded ZIP files.**

### Step 2: Replace Outdated Files in SeleniumBasic Folder

1.  Open **File Explorer** and go to:

    ```
    C:\Users\<YourUserName>\AppData\Local\SeleniumBasic
    ```
2. **Delete** the existing `chrome-win64` folder if it exists.
3. Copy the newly downloaded **`chrome-win64`** folder and paste it inside `SeleniumBasic`.
4. Copy the new **`chromedriver.exe`** file and paste it into `SeleniumBasic`. When prompted, **replace** the existing file.

### Step 3: Update Chrome Path in WhatsApp Blaster

1. Open **WhatsApp Blaster**.
2. Find the setting **"Use Default Chrome Installation"** and set it to **No**.
3.  Paste the path to your custom Chrome installation. It should look like one of the following:

    ```
    C:\Users\<YourUserName>\AppData\Local\SeleniumBasic\chrome-win64\chrome-win64\chrome.exe
    ```

    or

    ```
    C:\Users\<YourUserName>\AppData\Local\SeleniumBasic\chrome-win64\chrome.exe
    ```

    _(This depends on how you extracted the folder.)_

### Video Guide

{% embed url="https://iframe.mediadelivery.net/play/289332/f89ee1c6-8ddc-4ca8-bdaf-7171a799ab49" %}
Resolving 1000 Selenium Error - Video Guide
{% endembed %}
