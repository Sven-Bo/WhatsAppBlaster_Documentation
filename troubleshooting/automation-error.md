# Resolving Run-Time Error '-2146232576 (80131700)': Automation Error

If you encounter a Run-time error ‘-2146232576 (80131700)’: Automation error in Excel while running the WhatsApp Blaster VBA script, it is typically due to a missing or inactive .NET Framework on your system. Follow the steps below to resolve this issue:

#### Steps to Fix the Automation Error

1.  **Open Windows Features**:

    * Search for **"Turn Windows features on or off"** in the Start Menu and select it.

    <figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
2.  **Activate .NET Framework**:

    * For Windows 7: Look for **MICROSOFT .NET FRAMEWORK 3.5.1**.
    * For Windows 10: Look for **.NET FRAMEWORK 3.5 (includes .NET 2.0 and 3.0)**.
    * Check the box next to the .NET Framework and click **OK**.

    <figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
3.  **Download the Update**:

    * Windows will prompt you to download the required files for the .NET Framework. Allow the download to proceed.

    <figure><img src="../.gitbook/assets/image (13).png" alt="" width="563"><figcaption></figcaption></figure>
4. **Restart Your Computer**:
   * Once the download and installation are complete, restart your computer. This should resolve the Run-time error ‘-2146232576 (80131700)’.

#### Optional: Manual Installation

If the issue persists or if you prefer a manual installation, you can download the **Microsoft .NET Framework 3.5 Service Pack 1 (Full Package)** directly from the link below:

[Download .NET Framework 3.5 SP1](https://www.microsoft.com/en-in/download/details.aspx?id=25150\&irgwc=1\&OCID=AID2000142_aff_7806_1246483\&tduid=\(ir__h6mcgpzz6gkftz01kk0sohzz0e2xlforq1r6k1yg00\)\(7806\)\(1246483\)\(%2826af5e78cf215246c1fbf000121fbac0%29%2881561%29%28686431%29%28at106140_a107739_m12_p12460_c%29%28%29\)\(26af5e78cf215246c1fbf000121fbac0\)\&irclickid=_h6mcgpzz6gkftz01kk0sohzz0e2xlforq1r6k1yg00)

After following these steps, the Run-time error should be resolved, allowing you to continue using the WhatsApp Blaster without issues.
