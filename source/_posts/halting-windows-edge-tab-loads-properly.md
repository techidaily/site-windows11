---
title: Halting Windows Edge Tab Loads Properly
date: 2024-08-22T21:39:52.309Z
updated: 2024-08-23T21:39:52.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Halting Windows Edge Tab Loads Properly
excerpt: This Article Describes Halting Windows Edge Tab Loads Properly
keywords: Load Halting Windows Edge,Windows Edge Tab Control,Edge Tab Stop Issue,Resolve Edge Tab Errors,Fix Edge Tabs Popping Up,Stabilize Edge Tab Loading,Prevent Edge Tab Malfunction
thumbnail: https://thmb.techidaily.com/6cebc56dc292975b98a5a871193af627ed43dff4753b2894db168c37d5d2f38f.png
---

## Halting Windows Edge Tab Loads Properly

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-from-bland-to-blockbuster-framing-videos-in-a-square-perspective/"><u>[New] 2024 Approved  From Bland to Blockbuster  Framing Videos in a Square Perspective</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-create-captivating-videos-an-introduction-to-fb-reels-for-2024/"><u>[Updated] How to Create Captivating Videos  An Introduction to FB Reels for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-essential-apps-for-professional-video-editing-on-androidpc/"><u>[Updated] In 2024, Essential Apps for Professional Video Editing on Android/PC</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-tools-that-enhance-your-travel-videos/"><u>[Updated] Tools That Enhance Your Travel Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-grandest-directors-reveals/"><u>2024 Approved  Grandest Directors' Reveals</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-infusing-life-into-collage-a-photogenic-approach/"><u>2024 Approved  Infusing Life Into Collage  A Photogenic Approach</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-essentials-of-creating-memorable-fb-slideshows/"><u>2024 Approved  The Essentials of Creating Memorable FB Slideshows</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-note-30-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-resolving-printer-connections-in-windows/"><u>Essential Steps for Resolving Printer Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-captcha-missteps-in-windows-steam/"><u>Fixing CAPTCHA Missteps in Windows Steam</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-setting-up-to-broadcasting-a-discoguide/"><u>From Setting Up to Broadcasting  A DiscoGuide</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-the-windows-11-voice-chat/"><u>Getting Started with the Windows 11 Voice Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-halt-safe-screensaver-modifications/"><u>Guidelines to Halt Safe Screensaver Modifications</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-the-file-not-displayed-problem-in-outlook-on-windows/"><u>Handling the File Not Displayed Problem in Outlook on Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/hero-5-black-showdown-against-keymission-170-for-2024/"><u>Hero 5 Black Showdown Against Keymission 170 for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-your-os-with-psoft-menu-tools/"><u>How to Enhance Your OS with PSoft Menu Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-your-preferred-theme-and-font-in-the-windows-11-notepad/"><u>How to Set Your Preferred Theme and Font in the Windows 11 Notepad</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-your-drivers-in-windows-11107-by-drivereasy-guide/"><u>How to use Device Manager to update your drivers in Windows 11/10/7</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-non-essential-windows-11-functions-to-turn-off/"><u>Identifying Non-Essential Windows 11 Functions to Turn Off</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-realme-12-proplus-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Realme 12 Pro+ 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-poco-c55-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-your-photos-with-ease-comprehensive-guide-on-background-erasure-tool-usage/"><u>In 2024, Transform Your Photos with Ease  Comprehensive Guide on Background Erasure Tool Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-the-benefits-of-windows-11s-auto-hdr/"><u>Leveraging the Benefits of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speech-recognition-in-seconds-whisper-guide/"><u>Mastering Speech Recognition in Seconds - Whisper Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-parent-lock-configurations/"><u>Mastering Windows 11 Parent Lock Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-powershell-activating-script-policies/"><u>Mastering Windows PowerShell: Activating Script Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-it-admin-limited-warning/"><u>Methods to Resolve 'IT Admin Limited' Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-background-activity-windows/"><u>Minimizing Background Activity Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsoft-windows-update-setbacks-0xca00a009/"><u>Navigating Microsoft Windows Update Setbacks: 0XCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-cpu-performance-with-solutions-for-tiworkerexe-use/"><u>Optimize CPU Performance with Solutions for TiWorker.exe Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-dormant-windows-keys-for-functionality/"><u>Overhauling Dormant Windows Keys for Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-speech-conversion-using-whisper-desktop/"><u>Real-Time Speech Conversion: Using Whisper Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/reawakening-windows-hibernate-a-practical-guide/"><u>Reawakening Windows Hibernate: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-overwhelming-impact-of-ntoskrnlexe/"><u>Reducing the Overwhelming Impact of Ntoskrnl.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-hidden-pane-windows-6-procedures-in-win11/"><u>Reinstating Hidden Pane Windows: 6 Procedures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-filesystem-issues-with-ease-on-windows-11/"><u>Repairing Filesystem Issues with Ease on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-order-7-solutions-for-lost-windows-server-time/"><u>Restoring Order: 7 Solutions for Lost Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0x0001-issue-geforce-software-w11/"><u>Solving Code 0X0001 Issue: GeForce Software W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steer-clear-of-windows-http-error-reduce-excessive-requests/"><u>Steer Clear of Window's HTTP Error: Reduce Excessive Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-windows-complications-during-amd-setup/"><u>Steering Clear of Windows Complications During AMD Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/surge-speed-settings-preventing-unexpected-download-plunges/"><u>Surge Speed Settings: Preventing Unexpected Download Plunges</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disable-discord-auto-updates-at-bootup/"><u>Techniques to Disable Discord Auto-Updates at Bootup</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-comprerancial-insight-into-instagram-a-step-by-step-data-interpretation-toolkit/"><u>The Comprerancial Insight Into Instagram  A Step-by-Step Data Interpretation Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-out-windows-11s-silencing-methods/"><u>The Easy Way Out: Windows 11'S Silencing Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-for-windows-users-converting-your-mp3s-into-professional-audio-cds-using-imgburn/"><u>The Ultimate Guide for Windows Users: Converting Your MP3s Into Professional Audio Cds Using ImgBurn</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-methods-for-resolving-windows-interface-dispute/"><u>Top 5 Methods for Resolving Windows Interface Dispute</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-common-errors-in-microsoft-office-windows/"><u>Troubleshooting Common Errors in Microsoft Office Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-witchers-memory-issue-in-fortnite-pc-and-xbox-guide/"><u>Troubleshooting Witcher's Memory Issue in Fortnite [PC and Xbox Guide]</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-windows-11s-limited-functionality-beneficial/"><u>What Makes Windows 11’S Limited Functionality Beneficial?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastering-cross-device-sticky-note-functionality/"><u>Windows 11: Mastering Cross-Device Sticky Note Functionality</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>