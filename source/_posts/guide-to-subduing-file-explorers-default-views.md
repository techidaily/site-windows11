---
title: Guide to Subduing File Explorer's Default Views
date: 2024-08-15T15:43:29.874Z
updated: 2024-08-16T15:43:29.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Subduing File Explorer's Default Views
excerpt: This Article Describes Guide to Subduing File Explorer's Default Views
keywords: Subdue Explore Views Guide,Taming File Viewer Display,Mastery in File Explorer Normals,Halt Default File Explorer View,Conquering Default Options,Suppress Explorer Window Views,Override Explorers Initial Screens
thumbnail: https://thmb.techidaily.com/6c8487e0b404251fb12aeaebde28154ddd618ecb4b5d51b0cd4522eee48c4e1f.jpg
---

## Guide to Subduing File Explorer's Default Views

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-the-right-way-to-increase-your-tiktok-followers-safely/"><u>[New] 2024 Approved  The Right Way to Increase Your TikTok Followers Safely</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-best-of-the-best-20-hilarious-incarceration-posts-to-brighten-your-digital-world-for-2024/"><u>[New] Best of the Best - 20 Hilarious Incarceration Posts to Brighten Your Digital World for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-effortless-extraction-of-twitter-jokes-3-ways/"><u>[Updated] 2024 Approved  Effortless Extraction of Twitter Jokes  3 Ways</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-snatching-twitter-laughter-3-pc-techniques/"><u>[Updated] 2024 Approved  Snatching Twitter Laughter  3 PC Techniques</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-firecapture-extensions-for-ff-users/"><u>[Updated] FireCapture Extensions for FF Users</u></a></li>
<li><a href="https://windows11.techidaily.com/10-must-have-microsoft-store-apps-for-a-new-windows-pc/"><u>10 Must-Have Microsoft Store Apps for a New Windows PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-how-to-record-a-video-presentation-using-adobe-captivate/"><u>2024 Approved  How to Record a Video Presentation Using Adobe Captivate</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-asmr-equipment-for-thoughtful-shoppers-seeking-performance/"><u>2024 Approved  Top ASMR Equipment for Thoughtful Shoppers Seeking Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-tools-to-clipboard-access-for-easier-compatibility-fixes/"><u>Adding Tools to Clipboard Access for Easier Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-one-side-output-in-windows-10-headphones/"><u>Addressing One Side Output in Windows 10 Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-settings-for-visible-sticky-notes/"><u>Adjusting Windows Settings for Visible Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-locating-ip-and-mac-in-windows-ps/"><u>Advanced Techniques: Locating IP & MAC in Windows PS</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-text-recall-on-windows-11-through-enhanced-clipping/"><u>Advancing Text Recall on Windows 11 Through Enhanced Clipping</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-turning-off-your-pc-safely/"><u>Best Practices for Turning Off Your PC Safely</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/character-inspector-easy-steps-for-windows-11/"><u>Character Inspector: Easy Steps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/chkdsk-sfc-and-dism-windows-tools-unveiled-and-explained/"><u>CHKDSK, SFC & DISM: Windows Tools Unveiled and Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-security-filters-in-context-menu/"><u>Configuring Windows 11 Security Filters in Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-device-disabled-issue-with-error-code-22-on-windows-11/"><u>Correcting Device Disabled Issue with Error Code 22 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-install-access-denied-windows-setup-issue/"><u>Correcting Install Access Denied Windows Setup Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-the-spiritual-command-center-of-windows-11/"><u>Delving Into the Spiritual Command Center of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shift-unveiling-the-latest-os-features/"><u>Desktop Dynamics Shift: Unveiling the Latest OS Features</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-admin-settings-causing-windows-security-failsafe/"><u>Disabling Admin Settings Causing Windows Security Failsafe</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374504396-dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-the-world-of-dxvk-essential-knowledge-for-windows-gamers/"><u>Dive Into the World of DXVK: Essential Knowledge for Windows Gamers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-samsung-galaxy-s24-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Samsung Galaxy S24 in Minutes | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-best-20-non-copyrighted-pubg-image-gems/"><u>In 2024, Best 20 Non-Copyrighted PUBG Image Gems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-a24-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy A24 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719369938575-run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All.</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://extra-information.techidaily.com/speak-with-ease-simple-pubg-sound-tweaks/"><u>Speak with Ease  Simple PUBG Sound Tweaks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlocking-the-potential-of-instagrams-filters-a-modern-guide-2e23-for-2024/"><u>Unlocking the Potential of Instagram's Filters - A Modern Guide (2E23) for 2024</u></a></li>
</ul></div>