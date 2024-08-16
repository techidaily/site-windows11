---
title: "Secure Your System: Mastering the Art of Expanded Pins in Win10/11"
date: 2024-08-15T16:22:03.858Z
updated: 2024-08-16T16:22:03.858Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Your System: Mastering the Art of Expanded Pins in Win10/11"
excerpt: "This Article Describes Secure Your System: Mastering the Art of Expanded Pins in Win10/11"
keywords: Windows Security,Expanded Pin Tips,Secure Access Control,Win10/11 Pins Best Practices,Advanced Pin Safety,Enhanced System Security,Mastering Expanded Pins,Windows Security Practices,Expanded Pin Strategies,Secure Access Methods,Win 10/11 Pins Guide,Advanced Lock Techniques,System Safeguard Tips,Expert Expanded Pin Usage
thumbnail: https://thmb.techidaily.com/facaba7a5fd4b37097e51780f00827156432b8b7f6935409750ab63148a1187d.jpg
---

## Secure Your System: Mastering the Art of Expanded Pins in Win10/11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-favorites-list-top-mac-software-for-video-recording-for-2024/"><u>[New] Favorites List  Top Mac Software for Video Recording for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-shade-portraits-with-orbital-illumination-technique-cs/"><u>[New] Shade Portraits with Orbital Illumination Technique CS</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-gigglygraphics-mememakers-haven/"><u>[Updated] 2024 Approved  GigglyGraphics  MemeMaker's Haven</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-advanced-photo-editing-how-to-clean-up-unwanted-space/"><u>[Updated] Advanced Photo Editing  How to Clean Up Unwanted Space</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-complete-guide-twitter-reaction-videos/"><u>[Updated] Complete Guide | Twitter Reaction Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-efficiently-downloading-youtube-sections-in-minutes-for-2024/"><u>[Updated] Efficiently Downloading YouTube Sections in Minutes for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-editors-edge-advanced-tactics-for-youtube-video-spins-guide/"><u>[Updated] The Editor's Edge  Advanced Tactics for YouTube Video Spins (Guide)</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-lava-agni-2-5g-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-tweaks-for-your-windows-11-search-settings/"><u>5 Essential Tweaks for Your Windows 11 Search Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/6-common-windows-screen-resolution-issues-and-fixes/"><u>6 Common Windows Screen Resolution Issues and Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-walkthrough-for-clean-booting-windows-11/"><u>A Comprehensive Walkthrough for Clean Booting Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-different-view-unique-changes-to-windows-11s-file-explorer/"><u>A Different View: Unique Changes to Windows 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-journey-to-windows-11s-god-like-settings-mastery/"><u>A Journey to Windows 11'S God-Like Settings Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-profit-with-windows-11-pro-capture-best-offers/"><u>Accelerate Profit with Windows 11 Pro: Capture Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-and-running-verifier-manager-in-windows-11/"><u>Accessing and Running Verifier Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-rgb-customization-in-win11/"><u>Activating RGB Customization in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-cpu-utilization-checkers/"><u>Advanced CPU Utilization Checkers</u></a></li>
<li><a href="https://driver-error.techidaily.com/amd-radeon-r7-250-graphics-driver-problems-on-windows-11-solved/"><u>AMD Radeon R7 250 Graphics Driver Problems on Windows 11 [Solved]</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722963229744-arc-blow-can-lead-to-weld-defects-like-lack-of-fusion-porosity-or-undercutting/"><u>Arc Blow Can Lead to Weld Defects Like Lack of Fusion, Porosity, or Undercutting.</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vivobook-s-15-the-ultimate-blend-of-style-and-functionality/"><u>ASUS Vivobook S 15: The Ultimate Blend of Style & Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-overdrive-best-5-programs-for-higher-than-100-pc-audio/"><u>Audible Overdrive: Best 5 Programs for Higher-Than-100%% PC Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-disruption-correcting-photo-package-issues-on-windows-1011/"><u>Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-tutorial-on-windows-canary-usage/"><u>Beginner’s Tutorial on Windows Canary Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/best-budget-single-board-windows-systems/"><u>Best Budget Single-Board Windows Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-tecno-spark-20-proplus-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Tecno Spark 20 Pro+ Fingerprint Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-reconnecting-legrl-after-drops/"><u>Bridging the Gap: Reconnecting LeGRL After Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-add-folder-now-obstacle-in-windows-onedrive-for-a-smooth-experience/"><u>Bypassing the 'Add Folder Now' Obstacle in Windows OneDrive for a Smooth Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-1011-bluetooth-connect-failure/"><u>Bypassing Windows 10/11 Bluetooth Connect Failure</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-iphone-6s-plus-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock iPhone 6s Plus After Forgetting the Passcode?</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-error-code-0x800736cc-in-windows-update/"><u>Circumventing Error Code 0X800736CC in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-revival-atlasos-for-outdated-pcs/"><u>Classic Revival: AtlasOS for Outdated PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-samsung-galaxy-a24-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Samsung Galaxy A24</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-error-code-0x8007045d-a-guide-for-windows-11-users/"><u>Confronting Error Code 0X8007045d: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-language-build-system-setup/"><u>Cross-Language Build System Setup</u></a></li>
<li><a href="https://vp-tips.techidaily.com/cut-the-clutter-not-quality-explore-top-37-apps-for-mobile-videos-downsize-for-2024/"><u>Cut the Clutter, Not Quality  Explore Top 37 Apps for Mobile Videos Downsize for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-dism-a-practical-guide-to-fixing-win11-os/"><u>Decoding Dism: A Practical Guide to Fixing Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-ten-step-window-repair-journey/"><u>Decoding the Ten-Step Window Repair Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-blue-screen-errors-through-microsofts-tools-in-w11/"><u>Demystifying Blue Screen Errors Through Microsoft's Tools in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-7-critical-windows-steps-for-cyber-threats/"><u>Detecting 7 Critical Windows Steps for Cyber Threats</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266225421-eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-vivo-y100i-is-unlocked-by-drfone-android/"><u>How To Check if Your Vivo Y100i Is Unlocked</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-pause-life360-location-sharing-for-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-samsung-galaxy-z-flip-5-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Samsung Galaxy Z Flip 5 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-xcover-6-pro-tactical-edition-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy XCover 6 Pro Tactical Edition by Phone Number | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/mastering-the-melody-of-text-vocal-styling-for-ppt/"><u>Mastering the Melody of Text  Vocal Styling for PPT</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premier-casts-for-google-listeners-for-2024/"><u>Premier Casts for Google Listeners for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-xiaomi-civi-3-disney-100th-anniversary-edition-by-drfone-android/"><u>Top 10 Password Cracking Tools For Xiaomi Civi 3 Disney 100th Anniversary Edition</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/transform-your-snaps-the-complete-guide-to-snapchat-editing-for-2024/"><u>Transform Your Snaps  The Complete Guide to Snapchat Editing for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-on-iphone-xr-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide on iPhone XR iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/1719208597283-unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>