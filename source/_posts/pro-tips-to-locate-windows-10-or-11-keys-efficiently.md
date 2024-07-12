---
title: Pro Tips to Locate Windows 10 or 11 Keys Efficiently
date: 2024-07-11T21:59:36.704Z
updated: 2024-07-12T21:59:36.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pro Tips to Locate Windows 10 or 11 Keys Efficiently
excerpt: This Article Describes Pro Tips to Locate Windows 10 or 11 Keys Efficiently
keywords: Win10 Key Search,Win11 Unlock Methods,Fast PC Access Codes,Activation Code Finder,Windows Key Locator,Easy OS Update Keys,Quick Windows Activation
thumbnail: https://thmb.techidaily.com/06e4228770e6068ed6a3887b57608ffc3ec670ddf3f56b58d3f796cd0fa916df.jpg
---

## Pro Tips to Locate Windows 10 or 11 Keys Efficiently

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
<li><a href="https://screen-recording.techidaily.com/unleash-productivity-learn-to-screen-record-on-mac-using-just-keys/"><u>Unleash Productivity  Learn to Screen Record on Mac Using Just Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-unbranded-tiktok-content-easy-online-downloads-for-2024/"><u>[Updated] Unbranded TikTok Content  Easy Online Downloads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-win11-startup-processes/"><u>Fine-Tuning Win11 Startup Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-stability-post-windows-update-with-wsl-in-focus/"><u>Enhancing System Stability Post-Windows Update with WSL in Focus</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-use-creative-commons-copyright-licenses-in-2024/"><u>[Updated] How to Use Creative Commons Copyright Licenses, In 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-itel-p40plus-frp-by-drfone-android/"><u>The Updated Method to Bypass Itel P40+ FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-1111/"><u>How to Restore Windows Photo Viewer in Windows 11/11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-leading-presentation-to-film-tools/"><u>[New] Leading Presentation-to-Film Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-poor-internet-access-in-windows-apps-now/"><u>Resolve Poor Internet Access in Windows Apps Now</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-improve-iphone-filmingphotography-premium-accessory-guide/"><u>2024 Approved  Improve iPhone Filming/Photography  Premium Accessory Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-and-mouse-failure-windows-11-sleep-troubleshoot/"><u>Keyboard & Mouse Failure: Windows 11 Sleep Troubleshoot</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-multitask-media-with-ease-expertly-using-netflixs-picture-in-picture-feature/"><u>[New] Master Multitask Media with Ease  Expertly Using Netflix’s Picture-In-Picture Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-login-trials-detecting-successfulfailed-windows-access/"><u>Monitoring Login Trials: Detecting Successful/Failed Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-windows-defenders-exclusive-software-lockdown/"><u>How to Bypass Windows Defender's Exclusive Software Lockdown</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-crafting-professional-gamers-content-with-obs-recordings/"><u>[Updated] Crafting Professional Gamers' Content with OBS Recordings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-13-pro-official-method-to-unlock-your-apple-iphone-13-pro-by-drfone-ios/"><u>How To Unlock Apple iPhone 13 Pro Official Method to Unlock Your Apple iPhone 13 Pro</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-select-the-superior-a-guide-to-8-outstanding-free-android-mp3-downloaders/"><u>[Updated] Select the Superior  A Guide to 8 Outstanding Free Android MP3 Downloaders</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unleash-potential-in-online-engagement-through-zoom-screenshares-for-2024/"><u>[Updated] Unleash Potential in Online Engagement Through Zoom Screenshares for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-sticky-note-usage/"><u>Navigating Windows 11 for Sticky Note Usage</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/timelapse-excellence-iphones-quick-guide/"><u>Timelapse Excellence  IPhone's Quick Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-windows-11-redefined-a-features-breakdown/"><u>[Updated] In 2024, Windows 11 Redefined  A Features Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-text-emphasis-in-windows-11/"><u>Enabling/Disabling Text Emphasis in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/mastering-music-a-curated-list-of-the-best-5-mp3-compatible-audio-combiners-for-mac-for-2024/"><u>Mastering Music A Curated List of the Best 5 MP3 Compatible Audio Combiners for Mac for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-edible-expeditions-popular-foods-from-every-country/"><u>[Updated] 2024 Approved  Edible Expeditions  Popular Foods From Every Country</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-utorrent-sync-failures-on-windows-devices/"><u>Guiding Through uTorrent Sync Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-methods-to-overcome-security-errors-in-windows-11/"><u>Masterful Methods to Overcome Security Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-upgrade-glitch-error-0xc1900101/"><u>Decoding Windows Upgrade Glitch: Error #0xC1900101</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-gamers-guide-to-high-quality-in-game-broadcasts-for-2024/"><u>[New] Gamers' Guide to High-Quality In-Game Broadcasts for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-vivo-y78t-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Vivo Y78t Activity | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-the-standout-wallpaper-icon-in-win11/"><u>Get Rid of the Standout Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-vanished-steam-game-icons-immediately/"><u>Revive Vanished Steam Game Icons Immediately</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-directory-for-acquiring-cat-sound-effects-in-audio-format-for-2024/"><u>Updated Directory for Acquiring Cat Sound Effects in Audio Format for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-transfer-of-textual-data-via-edges-guardspace-win11-version/"><u>Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-compact-icons-arrangement-in-system-interface/"><u>Fixing Compact Icons Arrangement in System Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visibility-of-missing-cameras-on-device-management-screen/"><u>Enhance Visibility of Missing Cameras on Device Management Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-solve-nvidiae-experience-scanner-woes-on-windows/"><u>Easily Solve Nvidia'e Experience Scanner Woes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-store-error-0x00000000-in-windows-os/"><u>Eliminating Microsoft Store Error 0X00000000 in Windows OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/masterful-video-cropping-elevate-your-content-game-on-instagram-for-2024/"><u>Masterful Video Cropping  Elevate Your Content Game on Instagram for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-androids-best-picks-for-dynamic-collage-designers/"><u>[New] Android's Best Picks for Dynamic Collage Designers</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-entry-techniques-for-your-windows-11-appshouse/"><u>Seamless Entry Techniques for Your Windows 11 AppsHouse</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-pc-issues-amidst-minimum-specifications-and-intel-graphic-errors/"><u>Rectifying PC Issues Amidst Minimum Specifications and Intel Graphic Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-win-credentials-success-from-failure-scenarios/"><u>Discerning Win Credentials Success From Failure Scenarios</u></a></li>
<li><a href="https://extra-skills.techidaily.com/master-multi-tasking-on-edge-with-picture-in-picture-for-2024/"><u>Master Multi-Tasking on Edge with Picture-in-Picture for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-get-noticed-on-instagram-the-perfect-video-dimensions-and-aspect-ratios/"><u>Updated Get Noticed on Instagram The Perfect Video Dimensions and Aspect Ratios</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-front-doors-windows-desktop-sites/"><u>Digital Front Doors: Windows Desktop Sites</u></a></li>
<li><a href="https://location-social.techidaily.com/does-motorola-moto-g24-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Motorola Moto G24 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ocial-media-live-showdown-facebook-vs-youtube-and-twitter-periscope-for-2024/"><u>[New] Social Media Live Showdown  Facebook Vs. YouTube & Twitter Periscope for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-stellar-cursors-in-windows-1011/"><u>Simple Steps for Stellar Cursors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/howtomakenotepadwindowssmoothatnight/"><u>HowToMakeNotepadWIndowsSmoothAtNight</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-display-in-boot-process/"><u>Remedying Absence of Display in Boot Process</u></a></li>
</ul></div>
