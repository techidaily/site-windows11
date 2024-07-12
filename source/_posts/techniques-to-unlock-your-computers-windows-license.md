---
title: Techniques to Unlock Your Computer's Windows License
date: 2024-07-11T22:00:55.866Z
updated: 2024-07-12T22:00:55.866Z
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
<li><a href="https://windows11.techidaily.com/best-slate-companions-selecting-top-7-windows-tabs/"><u>Best Slate Companions: Selecting Top 7 Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-tactics-against-flaky-saving-mechanism-in-nvidia-gui/"><u>Avoidance Tactics Against Flaky Saving Mechanism in Nvidia GUI</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-based-office-glitches-effectively/"><u>Addressing Win-Based Office Glitches Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/6-different-ways-to-open-programs-on-windows/"><u>6 Different Ways to Open Programs on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-professional-tips-to-perfect-igtv-thumbnails/"><u>[Updated] 2024 Approved  Professional Tips to Perfect IGTV Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-no-network-access-on-winethernet/"><u>Bridging No Network Access on WinEthernet</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-disappearing-desktop-elements-on-windows/"><u>Bring Back Disappearing Desktop Elements on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-assault-win-against-mouse-lags-on-sw/"><u>Ace Your Assault: Win Against Mouse Lags on SW</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-system-refreshment-navigating-the-windows-driver-update-process/"><u>Audio System Refreshment: Navigating the Windows Driver Update Process</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-capturing-quality-video-on-macbook/"><u>[New] Capturing Quality Video on MacBook</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-simplify-satire-funniest-memes-made-simple/"><u>In 2024, Simplify Satire  Funniest Memes Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-windows-11s-digital-storyteller/"><u>Awakening Windows 11'S Digital Storyteller</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-apple-melodies-enhancing-visual-storytelling/"><u>[Updated] Apple Melodies Enhancing Visual Storytelling</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-endless-credential-entry-alerts-in-windows/"><u>Circumventing Endless Credential Entry Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bouncing-back-deleted-folders-on-your-pc/"><u>Bouncing Back Deleted Folders on Your PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-any-samsung-galaxy-f54-5g-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Samsung Galaxy F54 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-choose-a-drive-to-install-games-on-the-xbox-app-for-windows-try-these-fixes/"><u>Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-dialer-in-microsoft-windows-11/"><u>Activate Dialer in Microsoft Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719354556221-eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues.</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-blue-screens-a-windows-fixers-manual/"><u>Banishing Blue Screens: A Windows Fixer’s Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-tweaking-firewall-security/"><u>A Comprehensive Guide to Tweaking Firewall Security</u></a></li>
<li><a href="https://windows11.techidaily.com/become-a-windows-wizard-learn-essential-shortcut-commands/"><u>Become a Windows Wizard: Learn Essential Shortcut Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-termbackground-pic/"><u>Choosing a Fresh TermBackground Pic</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-time-display-in-the-taskbar-of-window-11/"><u>Adjusting Time Display in the Taskbar of Window 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-guide-to-initiating-and-archiving-webinars-economically/"><u>In 2024, Guide to Initiating and Archiving Webinars Economically</u></a></li>
<li><a href="https://extra-resources.techidaily.com/shh-9-secrets-of-simple-stock-editing/"><u>Shh! 9 Secrets of Simple Stock Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-license-validity-time-out-alerts-on-win10w11/"><u>Bypassing License Validity Time-Out Alerts on Win10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-11-notepad-using-ai-mentor/"><u>Boost Windows 11 Notepad Using AI Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://windows11.techidaily.com/boosted-windows-11-app-launch-strategies/"><u>Boosted Windows 11 App Launch Strategies</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exclusive-list-of-e-commerce-sites-for-one-of-a-kind-boxed-gifts/"><u>[New] Exclusive List of E-Commerce Sites for One-of-a-Kind Boxed Gifts</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-a-clean-desktop-with-automatic-trash-emptying-in-windows/"><u>Achieve a Clean Desktop with Automatic Trash Emptying in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-xiaomi-redmi-12-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Xiaomi Redmi 12? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-obstacles-downloading-icloud-on-windows/"><u>Bypassing Obstacles: Downloading iCloud on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-system-maintenance-locating-and-resolving-win-os-error-codes-via-command-prompt-expertise/"><u>Advanced System Maintenance: Locating and Resolving Win-OS Error Codes via Command Prompt Expertise</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-mastering-ps4-game-capture-via-obs-studio/"><u>[New] In 2024, Mastering PS4 Game Capture via OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/5-great-free-podcast-editing-programs-for-windows/"><u>5 Great Free Podcast Editing Programs for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-blackouts-unveiled-7-fixes-to-restore-access-on-your-os/"><u>Browser Blackouts Unveiled: 7 Fixes to Restore Access on Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-error-code-0x800736cc-in-windows-update/"><u>Circumventing Error Code 0X800736CC in Windows Update</u></a></li>
</ul></div>
