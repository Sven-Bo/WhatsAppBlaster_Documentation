---
description: >-
  This guide will help you resolve the "Error 429: Class Not Registered" issue
  in WhatsApp Blaster. Please follow the steps below carefully:
---

# Resolving Error 429: Class Not Registered

### Error Message:

<div align="left"><figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure></div>

### Solution 1: Ensure SeleniumBasic is Installed

1. **Download SeleniumBasic**:
   * Visit the official SeleniumBasic release page: [https://github.com/florentbr/SeleniumBasic/releases/tag/v2.0.9.0](https://github.com/florentbr/SeleniumBasic/releases/tag/v2.0.9.0).
2. **Install SeleniumBasic**:
   * Install SeleniumBasic to the following path:\
     `C:\Users\%username%\AppData\Local\SeleniumBasic`
   *

       <figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
3. **Reinstall if Necessary**:
   * If SeleniumBasic is already installed, try reinstalling it to ensure the installation is correct.

***

### Solution 2: Add Selenium Type Library in VBA

1. **Open VBA Editor**:
   * Open the WhatsApp Blaster file in Excel.
   * Press `Alt + F11` to open the VBA Editor.
2. **Access References**:
   * In the VBA Editor, click on `Tools` in the top menu.
   * Select `References` from the dropdown menu.
3. **Select Selenium Type Library**:
   * In the References dialog box, scroll down and look for `Selenium Type Library`.
   * Check the box next to it and click `OK` to confirm.
   *

       <figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>
4. **Save and Close**:
   * Save the changes in the VBA Editor and close it.
