# How to set up Chrome for WhatsAppBlaster

### Why Set Up a Dedicated Chrome for WhatsAppBlaster?

WhatsAppBlaster works by automating your Chrome browser. It opens the browser, navigates to WhatsApp Web, and sends messages for you—all automatically.

To make this possible, two things are needed:

1. A **Chrome browser** to perform the tasks.
2. A **ChromeDriver** to control the browser.

The problem? Google updates both Chrome and ChromeDriver frequently. If your browser updates, you also have to update the ChromeDriver to match, which can quickly become a hassle.

The solution? Use a dedicated "testing" Chrome browser. This is a special version of Chrome that’s only used for automation tasks like WhatsApp messaging. Paired with its matching ChromeDriver, this setup eliminates the need for constant updates, making the process much easier.

Follow the steps below to set up your dedicated Chrome browser and ChromeDriver.

### Watch the Video: How to Set Up Chrome

{% embed url="https://iframe.mediadelivery.net/play/289332/79448a7d-ab54-4688-b807-b4afea73cf08" %}
Step-by-Step Guide
{% endembed %}



### Detailed Steps: Setting Up Chrome for WhatsAppBlaster

{% stepper %}
{% step %}
### Download the files

1. **Download ChromeDriver**:\
   [Download ChromeDriver (zip)](https://storage.googleapis.com/chrome-for-testing-public/131.0.6778.264/win64/chromedriver-win64.zip)
2. **Download Chrome Testing Browser**:\
   [Download Chrome Testing Browser (zip)](https://storage.googleapis.com/chrome-for-testing-public/131.0.6778.264/win64/chrome-win64.zip)
{% endstep %}

{% step %}
### Extract the files

1. Extract the **ChromeDriver zip file** (`chromedriver-win64.zip`):
   * Inside the extracted folder, you’ll find `chromedriver.exe`.
2. Extract the **Chrome Testing Browser zip file** (`chrome-win64.zip`):
   * You’ll get a folder called `chrome-win64`.
{% endstep %}

{% step %}
### Move the Files to Selnium Basic Folder

1.  Open the default Selenium Basic folder:

    ```makefile
    C:\Users\<YourUsername>\AppData\Local\SeleniumBasic
    ```
2. Replace the existing `chromedriver.exe` in this folder with the new one from the `chromedriver-win64` folder.
3. Copy the **entire `chrome-win64` folder** into the Selenium Basic folder.\
   Your folder should now look like this:

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Add the Chrome Path to WhatsAppBlaster

1.  Find the path to `chrome.exe` inside the `chrome-win64` folder.\
    Example path:

    ```makefile
    C:\Users\<YourUsername>\AppData\Local\SeleniumBasic\chrome-win64\chrome.exe
    ```
2. Open WhatsAppBlaster and paste this path into the input field for the Chrome binary path.

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

