# Getting Started

### Follow these simple steps to get started with WhatsApp Blaster:

{% embed url="https://iframe.mediadelivery.net/play/289332/8a609935-f0ab-47aa-912d-9bc1327f79f9" %}
WhatsAppBlaster - Getting Started Video
{% endembed %}

### Detailed Steps: Getting Started with the WhatsAppBlaster

**Unblock the WhatsAppBlaster and enable macros**

* After downloading the Excel file, right-click it and select _Properties_. In the _General_ tab, check the _Unblock_ box if it’s available, then click _Apply_ and _OK_.
* Open the Excel file, and when prompted, click _Enable Content_ to allow macros to run properly.

**Download the files**

You'll need three files to set up WhatsApp Blaster. Click the links below to download them:

1. [Download VBA Selenium (exe)](https://github.com/florentbr/SeleniumBasic/releases/download/v2.0.9.0/SeleniumBasic-2.0.9.0.exe)\
   (_The tool that connects Excel to your browser_)
2. Download **ChromeDriver** & **Chrome Testing Browse**r ⤵️:

{% tabs %}
{% tab title="For 64-bit Windows (recommended)" %}
* [Download ChromeDriver (win64)](https://storage.googleapis.com/chrome-for-testing-public/136.0.7103.92/win64/chromedriver-win64.zip)
* [Download Chrome Testing Browser (win64)](https://storage.googleapis.com/chrome-for-testing-public/136.0.7103.92/win64/chrome-win64.zip)

_Version: 136.0.7103.92, Last updated: May 07, 2025_
{% endtab %}

{% tab title="For 32-bit Windows" %}
* [Download ChromeDriver (win32)](https://storage.googleapis.com/chrome-for-testing-public/136.0.7103.92/win32/chromedriver-win32.zip)
* [Download Chrome Testing Browser (win32)](https://storage.googleapis.com/chrome-for-testing-public/136.0.7103.92/win32/chrome-win32.zip)

_Version: 136.0.7103.92, Last updated: May 07, 2025_
{% endtab %}
{% endtabs %}

#### Extract the files

1. Extract the **ChromeDriver zip file** (`chromedriver-win64.zip`):
   * Inside the extracted folder, you’ll find `chromedriver.exe`.
2. Extract the **Chrome Testing Browser zip file** (`chrome-win64.zip`):
   * You’ll get a folder called `chrome-win64`.

**Install VBA Selenium**

{% embed url="https://iframe.mediadelivery.net/play/289332/374aefc5-e980-4638-b770-a7b4f6c63723" %}

**Move the Files to Selenium Basic Folder**

1.  Open the default Selenium Basic folder:

    ```makefile
    C:\Users\<YourUsername>\AppData\Local\SeleniumBasic
    ```
2. Replace the existing `chromedriver.exe` in this folder with the new one from the `chromedriver-win64` folder.
3. Copy the **entire `chrome-win64` folder** into the Selenium Basic folder.\
   Your folder should now look like this:

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Add the Chrome Path to WhatsAppBlaster**

1.  Find the path to `chrome.exe` inside the `chrome-win64` folder.\
    Example path:

    ```makefile
    C:\Users\<YourUsername>\AppData\Local\SeleniumBasic\chrome-win64\chrome.exe
    ```
2. Open WhatsAppBlaster and paste this path into the input field for the Chrome binary path.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Change WhatsApp Language to EN**

Set your WhatsApp language to English by following the instructions [here](https://faq.whatsapp.com/779773243128935/?cms_platform=android).

***

### Getting Started Troubleshooting

<details>

<summary>Error 7: "No Such Element Found" in the Status Column</summary>

If you see this error in the **Status** column after sending messages, it usually means your WhatsApp interface is not set to **English**.

**How to Fix It**:

* Open WhatsApp on your phone.
* Follow [these instructions](https://faq.whatsapp.com/779773243128935/?cms_platform=android) to change the app language to **English**.

Once your WhatsApp is in English, retry sending your messages.

</details>

<details>

<summary>Error: Buttons Not Working ("Cannot Run the Macro")</summary>

If you get an error like the one below when clicking any buttons:

<img src="../.gitbook/assets/image (27).png" alt="" data-size="original">

This happens when macros are not enabled in Excel. To fix this, [follow the instructions here](../troubleshooting/unable-to-click-on-buttons-in-the-whatsapp-blaster.md).

</details>
