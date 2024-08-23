---
title: Unshackle Administrative Access on PCs
date: 2024-08-22T21:40:46.290Z
updated: 2024-08-23T21:40:46.290Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unshackle Administrative Access on PCs
excerpt: This Article Describes Unshackle Administrative Access on PCs
keywords: Unlock PC Admin,PC Admin Access,Enhance PC Control,Elevate PC Permissions,Simplify PC Management,Improve PC Accessibility,Boost PC Security
thumbnail: https://thmb.techidaily.com/769d83492280fd0660acd0112190d1d990d0e4305860168c39e79719f29b2ea7.jpg
---

## Unshackle Administrative Access on PCs

 Administrator accounts offer extensive control over the system, granting the ability to manage settings, install software, and access critical system files. However, occasionally, users may encounter issues when attempting to switch from their standard user account to an admin account.

 Below, we explore various effective fixes to resolve this problem permanently.

## 1\. Modify the User Account Control (UAC) Settings

 User Account Control (UAC) is a security feature that prevents users from making unauthorized changes to the computer. It typically appears as a dialog box, prompting you to confirm the action by clicking the "Yes" or "No" option.

 In the case of this specific error, you might be facing the issue because of misconfigured or incorrect UAC settings. Here is how you can ensure UAC is enabled and set to a suitable level:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "control" in the text field and click **Enter**.
3. In the following window, navigate to **System and Security** \> **Security and Maintenance**.
4. Choose **Change User Account Control settings**.
5. In the dialog that appears, move the slider to the desired level (recommended: notify only when apps try to make changes to your computer) and click **OK** to save the changes.  
![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

 Once done, close the Command Prompt and check if the issue is resolved.

## 2\. Activate the Built-In Administrator Account

![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-built-in-admin-account.jpg)

 Windows comes with a hidden administrator account that can allow you to have full control over the system. This account is typically disabled by default for security reasons but if you are having trouble switching to an administrator account, enabling the built-in Administrator account can be beneficial.

 Here's how to activate the built-in Administrator account:

1. Press the **Win** \+ **R** keys to open Run.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the following dialog.
4. Once you are in the Command Prompt, type the command below and hit **Enter** to execute it:  
net user administrator /active:yes
5. After the command executes successfully, you should see a message in Command Prompt confirming it. If you want to set a password for this administrator account, execute the following command:  
​​​​​​​net user administrator *
6. Follow the prompts to set a new password.

 Alternatively, you can also use the Local Users and Groups management console to make these changes. Here is how you can do that:

1. Open Run by pressing **Win** \+ **R** keys together.
2. Type "lusrmgr.msc" in Run and click **Enter**.
3. In the left pane, expand **Users** and right-click on **Administrator**.
4. Choose **Properties** from the context menu.
5. Uncheck the **Account is disabled** option and click **OK**.  
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-admin-account.jpg)

 This should successfully activate the built-in administrator account. You can now access the Settings app again and check if you can switch the account type easily now.

## 3\. Make the Changes in Safe Mode

 It's possible that a background process or application is causing interference with system processes, which could be preventing you from switching to an administrator account.

 To determine if this is the cause of the issue, you can [boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). Safe Mode launches the system with minimal drivers and programs, disabling any background processes that may be contributing to the problem. In this diagnostic state, you should be able to switch to the administrator account if such processes were previously causing the obstruction.

 Once you have booted into Safe Mode, try performing the action that was initially causing the problem. If it does not occur in Safe Mode, you can try eliminating the culprit by either uninstalling it manually or [using the System Restore utility](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) to revert to a stable, error-free state.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Your Antivirus Program

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 If you are using a third-party security program on your computer, it might be preventing you from switching to an admin account because of security reasons.

 In this case, you can try to temporarily disable your security program and see if that helps you switch to an administrator account. You can do this by right-clicking on your antivirus icon in the taskbar and choosing the **Shields Control** \> **Disable until the computer is restarted** option.

 If this works, you can consider [switching to a better security program for your Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to prevent issues like this from occurring in the future.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 5\. Create a New Administrator Account

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## Finally, if none of the methods above have helped you, you can try creating a new administrator account in Windows

 This will help with any corruption issues in the current account, as well as help you determine if the permission-related problems were user-specific. It is, however, important to note that you will require admin access to the system to proceed with the steps in this method, so you must enable the built-in administrator account beforehand.

 Once that is done, here is how you can proceed:

1. Open the Settings app by pressing the **Win** \+ **I** keys together.
2. Choose **Accounts** from the left pane and click on **Other users**.
3. Hit the **Add account** button for **Add other users** in the following window.  
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)
4. Select **I don’t have this person’s sign-in information** \> **Add a user without a Microsoft account**.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
5. In the next dialog, enter details like the username and password for the new account.
6. Click **Next**.
7. Once the account is created, click on the **Change account type** button associated with the newly created account.  
![The Change account type button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-change-account-type-option.jpg)
8. Expand the Account type dropdown and choose **Administrator** from the menu.
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Click **OK** to save the changes.

 You can now log into the new administrator account and begin using it.

## Enjoy Administrative Access to Your Windows System

 The inability to change an account type to Administrator in Windows can be caused by a number of reasons, such as misconfigured User Account Control (UAC) settings or underlying system issues. However, with the right troubleshooting methods, you can overcome the account type change challenge and enjoy administrative access to the system.

 Below, we explore various effective fixes to resolve this problem permanently.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-the-goofy-adventure-a-critical-appraisal-videotape-edition/"><u>[New] 'The Goofy Adventure' - A Critical Appraisal Videotape Edition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-innovative-video-sharing-best-practices-for-live-monitor-display/"><u>[New] 2024 Approved  Innovative Video Sharing  Best Practices for Live Monitor Display</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-transform-your-visuals-with-these-11-expert-strategies/"><u>[New] 2024 Approved  Transform Your Visuals with These 11 Expert Strategies</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-achieve-smooth-aquatic-vids-with-these-seven-steps/"><u>[New] Achieve Smooth Aquatic Vids with These Seven Steps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-expert-ai-visualization-toolset/"><u>[New] Expert AI Visualization Toolset</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-standout-methods-for-fb-ad-visualization/"><u>[New] In 2024, Standout Methods for FB Ad Visualization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-recordingratings-analyzer-for-2024/"><u>[New] RecordingRatings Analyzer for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-ultimate-guide-to-engagement-mastering-instagram-stories/"><u>[Updated] 2024 Approved  The Ultimate Guide to Engagement  Mastering Instagram Stories</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-breaking-down-barriers-to-inaccessible-youtube-content/"><u>[Updated] In 2024, Breaking Down Barriers to Inaccessible YouTube Content</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-maximizing-your-android-game-adventure-with-kinemaster-review/"><u>[Updated] Maximizing Your Android Game Adventure with KineMaster Review</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-superb-cyber-shops-for-handcrafted-gift-enclosures/"><u>2024 Approved  Superb Cyber Shops for Handcrafted Gift Enclosures</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-vs-google-bard-showdown-an-in-depth-comparison-of-the-top-language-models/"><u>ChatGPT Vs. Google Bard Showdown: An In-Depth Comparison of the Top Language Models</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-stunning-visual-stories-best-online-collage-software-for-2024/"><u>Create Stunning Visual Stories Best Online Collage Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-always-show-task-manager-on-top-of-other-open-windows/"><u>How to Always Show Task Manager on Top of Other Open Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-redmi-note-13-pro-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-calculator-in-windows-11/"><u>How to Open the Calculator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-wi-fi-and-ethernet-at-the-same-time-on-windows/"><u>How to Use Wi-Fi and Ethernet at the Same Time on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-extended-firewall-protection-for-windows-11/"><u>Implementing Extended Firewall Protection for Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-boost-your-youtube-earnings-with-effective-adsense-use/"><u>In 2024, Boost Your YouTube Earnings with Effective AdSense Use</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-design-your-closure-the-best-free-youtube-tutorials/"><u>In 2024, Design Your Closure  The Best Free YouTube Tutorials</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-quick-gain-techniques-to-expand-your-channels-audience/"><u>In 2024, Quick-Gain Techniques to Expand Your Channel's Audience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-the-top-10-to-11-screen-capturing-tools-for-every-mac-user/"><u>In 2024, The Top 10 to 11 Screen Capturing Tools for Every Mac User</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-11-proplus-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme 11 Pro+</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-tinyflicker-log-capture-and-competing-tools/"><u>In 2024, TinyFlicker Log Capture & Competing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-cooling-on-microsoft-pcs/"><u>Mastering Hardware Cooling on Microsoft PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-require-privilege-woes-winerror-740-breakthroughs/"><u>Navigating 'Require Privilege' Woes: WinError 740 Breakthroughs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-family-safety-in-windows-11-for-guardians/"><u>Navigating Family Safety in Windows 11 for Guardians</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-win11-settings-for-defaults/"><u>Navigating Win11 Settings for Defaults</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unbiased-comparison-final-cut-pro-and-lumafusion-for-video-editors/"><u>New Unbiased Comparison Final Cut Pro and LumaFusion for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-freeze-frames-in-windows-league-of-legends/"><u>Overcoming Freeze Frames in Windows League of Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-fatal-exception-error-0x8007045d-on-pc/"><u>Overhauling Fatal Exception Error 0X8007045D on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-not-for-snip-stop-windows-11s-snipping-tool-by-default/"><u>PrtScn Not for Snip: Stop Windows 11'S Snipping Tool by Default</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-methods-to-enable-fingertip-writing-on-windows-pcs/"><u>Quick Methods to Enable Fingertip Writing on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-zoom-functionality-in-windows-11-error-1132/"><u>Reinstating Zoom Functionality in Windows 11 Error 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-display-issue-with-error-x0001-geforce/"><u>Resolving Display Issue with Error X0001, GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/searching-for-ideal-windows-hello-friendly-camera/"><u>Searching for Ideal Windows Hello-Friendly Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-counteract-windows-11-error-x80049dd3/"><u>Step-by-Step Guide to Counteract Windows 11 Error X80049DD3</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-data-management-in-windows-with-custom-commands/"><u>Streamlining Data Management in Windows with Custom Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-of-eradicating-linguistic-line-from-win11-taskbar/"><u>The Secret of Eradicating Linguistic Line From Win11 Taskbar</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-vivo-y27s-by-drfone-android/"><u>Three Ways to Sim Unlock Vivo Y27s</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-stopping-self-opening-search-bar-in-win11/"><u>Tips for Stopping Self-Opening Search Bar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secret-tips-for-accessing-win11s-credential-vault-in-under-a-minute/"><u>Top Secret Tips for Accessing Win11's Credential Vault in Under a Minute</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-ranked-independent-offline-mobile-gaming-android/"><u>Top-Ranked Independent Offline Mobile Gaming (Android)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-unresponsive-win11-media-player/"><u>Troubleshooting for Unresponsive Win11 Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-power-of-your-digital-brush-on-windows-11-with-paint-cocreator-for-ai-artistry/"><u>Unleash the Power of Your Digital Brush on Windows 11 with Paint Cocreator for AI Artistry</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-creativity-free-animation-techniques-for-2024/"><u>Unlocking Creativity  Free Animation Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-not-found-in-windows-os-fixes/"><u>Unraveling 'Not Found' In Windows OS Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-widget-personalization-in-microsofts-latest-os/"><u>Unveiling Widget Personalization in Microsoft's Latest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/what-lies-behind-the-numbers-in-windows-updates/"><u>What Lies Behind the Numbers in Windows Updates?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Where Is the Best Place to Catch Dratini On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windowing-ways-to-keep-notes-above-the-rest/"><u>Windowing Ways to Keep Notes Above the Rest</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-integrating-custom-directories-into-menus/"><u>Windows 11 Mastery: Integrating Custom Directories Into Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>