---
title: Techniques to Unlock Your Computer's Windows License
date: 2025-02-27T10:45:04.817Z
updated: 2025-03-01T21:31:19.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Unlock Your Computer's Windows License
excerpt: This Article Describes Techniques to Unlock Your Computer's Windows License
keywords: Unlocking Windows,Resetting Password,Bypassing Lockout,Activate OS,Keyboard Shortcuts,Safe Mode Access,Registry Tricks
thumbnail: https://thmb.techidaily.com/5961427253350c1b74e1650e9c2f8a99858d6dfe3a81786842ed520231401b1b.jpg
---

## Techniques to Unlock Your Computer's Windows License

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell

![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  
![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-snapchats-secret-storytelling-a-step-by-step-guide/"><u>[New] 2024 Approved Snapchat’s Secret Storytelling A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-autoplay-youtube-on-phones-without-interruption/"><u>[New] Autoplay YouTube on Phones without Interruption</u></a></li>
<li><a href="https://fox-blue.techidaily.com/beyond-reality-the-top-10-sci-fi-movies-with-metaverse-travels-for-2024/"><u>Beyond Reality The Top 10 Sci-Fi Movies with Metaverse Travels for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/eliminate-chrome-delays-effective-and-easy-remedies-to-enhance-speed/"><u>Eliminate Chrome Delays: Effective and Easy Remedies to Enhance Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-printouts-with-easy-windows-troubleshooting/"><u>Faster Printouts with Easy WIndows Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-stalled-windows-outlook-conditional-rules/"><u>Fixing Stalled Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-a-device-which-does-not-exist-was-specified-error-in-windows-10-and-11/"><u>How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-lava-blaze-curve-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Lava Blaze Curve 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reduce-clutter-disabling-explorer-tabs/"><u>How to Reduce Clutter: Disabling Explorer Tabs</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-realme-note-50-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-look-at-the-samsung-qn55q3u-a-premier-4k-hdr-smart-tv-experience/"><u>In-Depth Look at the Samsung QN55Q3U: A Premier 4K HDR Smart TV Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-circumvent-windows-11-lock-without-fuss/"><u>Learn to Circumvent Windows 11 Lock Without Fuss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-matters-quick-ways-to-check-your-pcs-ram-on-windows/"><u>Memory Matters: Quick Ways to Check Your PC's RAM on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/new-era-of-productivity-microsofts-ai-integration-in-windows-11-taskbar/"><u>New Era of Productivity: Microsoft's AI Integration in Windows 11 Taskbar</u></a></li>
<li><a href="https://app-tips.techidaily.com/overcoming-obstacles-to-utilize-generative-ai-effectively-reveals-new-study-by-deloitte-featured-on-zdnet/"><u>Overcoming Obstacles to Utilize Generative AI Effectively, Reveals New Study by Deloitte Featured on ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-a-smooth-setup-for-microsoft-works-in-w11/"><u>Securing a Smooth Setup for Microsoft Works in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-windows-cryptography-tools-under-156-chars/"><u>Top 7 Windows Cryptography Tools (Under 156 Chars)</u></a></li>
</ul></div>

