---
title: Reactivating Dormant CPU Temp Control Measures
date: 2024-08-08T06:03:42.090Z
updated: 2024-08-09T06:03:42.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Dormant CPU Temp Control Measures
excerpt: This Article Describes Reactivating Dormant CPU Temp Control Measures
keywords: CPU Temp Management,Reactivate Temp Controls,Dormant Temp Fixes,CPU Cooling Strategies,Enhance CPU Temp Regulation,Restore CPU Thermal Limits,Resume CPU Temperature Control
thumbnail: https://thmb.techidaily.com/20c1b79c602928e68eb827f2805a2d6c02102230fc6f02657f8a03a2a51b45e9.jpg
---

## Reactivating Dormant CPU Temp Control Measures

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://youtube-tips.techidaily.com/024-approved-engaging-everyone-quickly-which-platform-triumphs-for-shorter-videos/"><u>[New] 2024 Approved  Engaging Everyone Quickly  Which Platform Triumphs for Shorter Videos?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-essential-guide-to-enhancing-youtube-content-post-upload/"><u>[New] 2024 Approved  Essential Guide to Enhancing YouTube Content Post-Upload</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-fb-quick-views-snap-and-share/"><u>[New] 2024 Approved  FB Quick Views  Snap & Share</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-the-art-of-optimizing-your-yt-channel-description/"><u>[New] 2024 Approved  The Art of Optimizing Your YT Channel Description</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-bite-sized-tips-for-aspiring-video-editors-for-2024/"><u>[New] Bite-Sized Tips for Aspiring Video Editors for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-top-3-ipad-voice-recorder/"><u>[New] In 2024, Top 3 iPad Voice Recorder</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-turning-tiktok-hits-into-personal-cellphone-chimes/"><u>[New] Turning TikTok Hits Into Personal Cellphone Chimes</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-best-in-class-chromebook-recording-app/"><u>[Updated] 2024 Approved  Best in Class  Chromebook Recording App</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harness-the-power-of-color-grading-a-guide-to-luts-in-photoshop-cs6/"><u>[Updated] Harness the Power of Color Grading  A Guide to LUTs in Photoshop CS6</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-post-extended-clip-on-youtube-per-your-request/"><u>[Updated] Post Extended Clip on YouTube Per Your Request</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-precision-control-for-incredible-android-time-lapses/"><u>[Updated] Precision Control for Incredible Android Time-Lapses</u></a></li>
<li><a href="https://windows11.techidaily.com/1720600438278-windowsstellar-data-recovery/"><u>「Windowsで失われたファイルを取り戻せる無料ソフトStellar Data Recovery」</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-razer-device-absence-in-win-1011-via-synapse/"><u>Addressing Razer Device Absence in Win 10/11 via Synapse</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unwanted-hibernation-usb-tweaks-for-windows-11/"><u>Avoid Unwanted Hibernation - USB Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updating-obstacles-a-compreeher-guide-to-fixes/"><u>Clearing Updating Obstacles: A Compreeher Guide to Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-11-shutdown-managing-ongoing-processes/"><u>Delaying Windows 11 Shutdown: Managing Ongoing Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-the-windows-11-afc-error-camera-app-solution/"><u>Disarming the Windows 11 AFC Error: Camera App Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-path-into-windows-11-insider-group/"><u>Discovering the Path Into Windows 11 Insider Group</u></a></li>
<li><a href="https://video-capture.techidaily.com/easy-steps-how-to-record-on-vimeo-for-2024/"><u>Easy Steps  How to Record on Vimeo for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-play-fixing-fall-guys-errors-in-windows-os/"><u>Ensuring Continuous Play: Fixing Fall Guys Errors in Windows OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-tecno-phantom-v-fold-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Tecno Phantom V Fold</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-six-impactful-ways-to-harness-chatgpts-language-parsing-abilities/"><u>Exploring Six Impactful Ways to Harness ChatGPT's Language Parsing Abilities</u></a></li>
<li><a href="https://windows11.techidaily.com/file-finder-simplicity-windowed-explorer-reduction-technique/"><u>File Finder Simplicity: Windowed Explorer Reduction Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-xc0000142-with-windows-oses/"><u>Fixing Error XC0000142 with Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-and-windows-exploring-the-memory-integrity-dilemshift/"><u>Ftdibus.sys and Windows: Exploring the Memory Integrity Dilemshift</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-logitech-webcams-up-and-running-free-windows-compatible-drivers/"><u>Get Logitech Webcams Up and Running: Free Windows-Compatible Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-widgets-to-the-windows-11-desktop/"><u>How to Add Widgets to the Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-an-incorrect-cpu-usage-in-the-windows-task-manager/"><u>How to Fix an Incorrect CPU Usage in the Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-asana-not-working-on-windows/"><u>How to Fix Asana Not Working on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-apple-iphone-7-plus-have-find-my-friends-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Apple iPhone 7 Plus Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-lava-yuva-2-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Lava Yuva 2 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-iphone-transfer-transfer-contact-from-apple-iphone-14-plus-to-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>In 2024, iPhone Transfer Transfer Contact from Apple iPhone 14 Plus to iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-samsung-galaxy-m54-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Samsung Galaxy M54 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://data-wizards.techidaily.com/inspiring-stories-video-customer-narratives/"><u>Inspiring Stories: Video Customer Narratives</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-windows-drivers-for-hps-elitebook-folio-1020-g7-laptop-a-step-by-step-guide/"><u>Installing Windows Drivers for HP's EliteBook Folio 1020 G7 Laptop: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-and-resolving-outlooks-error-0x80040610/"><u>Navigating Through and Resolving Outlook's Error 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://driver-install.techidaily.com/nvidia-graphics-card-software-revamp-gtx-1060/"><u>Nvidia Graphics Card Software Revamp - GTX 1060</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-multitask-with-windows-11-expertise/"><u>Optimizing Workflow: Multitask with Windows 11 Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-capture-issue-in-win11-photoapp/"><u>Overcoming 'Failed Capture' Issue in Win11 PhotoApp</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-0x8007045d-error-on-windows-11/"><u>Overcoming the Challenge of 0X8007045d Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-folder-menu-enhancement-with-new-commands-win-11/"><u>Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-notebook-interface-with-themes-and-fonts/"><u>Streamline Your Notebook Interface with Themes & Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-your-windows-security-pin-quickly/"><u>Switching Your Windows Security Pin Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-connoisseurs-guide-top-tips-for-perfecting-pc-displays/"><u>The Clarity Connoisseur's Guide: Top Tips for Perfecting PC Displays</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/transcribing-chats-efficient-techniques-for-fb-live-recordings/"><u>Transcribing Chats  Efficient Techniques for FB Live Recordings</u></a></li>
<li><a href="https://fox-blue.techidaily.com/1721459979470-troubleshoot-and-repair-an-unresponsive-iphone-home-button-in-minutes/"><u>Troubleshoot and Repair an Unresponsive iPhone Home Button in Minutes!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/uncover-the-secret-correcting-mobile-video-sharing-on-fb-messenger/"><u>Uncover the Secret  Correcting Mobile Video Sharing on FB Messenger</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-screen-without-pin-in-windows-11/"><u>Unlock Your Screen Without PIN in Window's 11</u></a></li>
</ul></div>
