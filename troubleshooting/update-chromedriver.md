# How to update ChromeDriver

### How to Update ChromeDriver

If you encounter the following error message when running the WhatsApp Blaster, it indicates a version mismatch between your Chrome browser and the ChromeDriver used by VBA Selenium:

<div align="left"><figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure></div>

#### What Does This Mean?

This error occurs because your Chrome browser has been updated to a newer version (e.g., version 123), but the ChromeDriver installed with VBA Selenium is still on an older version (e.g., version 120). To fix this, you'll need to update your ChromeDriver to match your current browser version.

**Below is a step-by-step guide on how to update the ChromeDriver:**

{% embed url="https://iframe.mediadelivery.net/play/289332/9b490438-3e22-43da-96ab-12ca54d6c6b1" %}

#### Steps to Update ChromeDriver

1. **Identify the Issue**:
   * Check the error message to confirm the version numbers of your current Chrome browser and ChromeDriver.
2. **Download the Correct ChromeDriver**:
   * Go directly to the [ChromeDriver download page](https://googlechromelabs.github.io/chrome-for-testing/).
   * Download the ChromeDriver that corresponds to your browser's major version (e.g., version 123).
   * Choose the correct driver for your operating system (win32 or win64).
3. **Replace the Old ChromeDriver**:
   * Extract the downloaded ZIP file.
   * Copy the `chromedriver.exe` file.
   * Navigate to `C:\Users\<USERNAME>\AppData\Local\SeleniumBasic`.
   * Paste the new file into this folder, replacing the existing `chromedriver.exe`.
4. **Test the WhatsApp Blaster**:
   * Return to the WhatsApp Blaster Excel file and run the bot again to ensure everything is working correctly.
