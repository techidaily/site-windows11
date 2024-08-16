---
title: "Windows 11 Folder Shuffle: Show/Hide System Directories"
date: 2024-08-15T15:53:27.579Z
updated: 2024-08-16T15:53:27.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Folder Shuffle: Show/Hide System Directories"
excerpt: "This Article Describes Windows 11 Folder Shuffle: Show/Hide System Directories"
keywords: Windows 11 Hidden Folders,System Files Explorer,11 Shuffle Directories,Show System Folders,Hide OS Folder View,Windows Explorer Options,11 File Display Settings
thumbnail: https://thmb.techidaily.com/7e37922976a0cd02bd45d34c10fef6f069d63ae07942af07cd489ff374cb4abd.png
---

## Windows 11 Folder Shuffle: Show/Hide System Directories

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-6-superior-android-screen-capture-apps/"><u>[New] 2024 Approved  6 Superior Android Screen Capture Apps</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-leading-video-chatting-software-for-teams/"><u>[New] In 2024, Leading Video Chatting Software for Teams</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-rapid-visual-recorder-w-preloaded-auditory-narrations/"><u>[New] In 2024, Rapid Visual Recorder W/ Preloaded Auditory Narrations</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-art-of-adding-emojis-to-youtube-comments/"><u>[New] In 2024, The Art of Adding Emojis to YouTube Comments</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-the-hidden-truths-behind-vrs-advantages-and-limitations/"><u>[New] Unveiling the Hidden Truths Behind VR's Advantages and Limitations</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-visual-filmmaking-resources-environmentally-conscious-for-2024/"><u>[New] Visual Filmmaking Resources - Environmentally Conscious for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-visual-vibes-top-story-filter-rankings-for-2024/"><u>[New] Visual Vibes  Top Story Filter Rankings for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-perfectly-blend-audiotracks-in-slideshows/"><u>[Updated] How to Perfectly Blend Audiotracks in Slideshows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-dark-heroity-meets-radiant-righteousness/"><u>[Updated] In 2024, Dark Heroity Meets Radiant Righteousness</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-live-action-lensing-cutting-edge-methods-in-sports-video-for-2024/"><u>[Updated] Live Action Lensing  Cutting-Edge Methods in Sports Video for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-step-by-step-guide-adding-subs-to-igtv-for-2024/"><u>[Updated] Step-by-Step Guide  Adding Subs to IGTV for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-journey-beyond-the-frantic-crafting-epic-slow-motion-content-for-instragram/"><u>2024 Approved  Journey Beyond the Frantic  Crafting Epic Slow Motion Content for Instragram</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-mastering-audio-integration-in-adobe-premiere-pro/"><u>2024 Approved  Mastering Audio Integration in Adobe Premiere Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/7-ways-to-lock-apps-on-iphone-15-pro-max-and-ipad-securely-by-drfone-ios/"><u>7 Ways to Lock Apps on iPhone 15 Pro Max and iPad Securely</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-guide-to-excellent-live-cricket-online-watch/"><u>A Guide to Excellent Live Cricket Online Watch</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/advanced-audio-alliance-for-podcasters-for-2024/"><u>Advanced Audio Alliance for Podcasters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-agendas-integrating-ifttt-with-to-do/"><u>Automating Agendas: Integrating IFTTT with To-Do</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-0xfffffff-confusion-quick-fixes/"><u>Clearing Windows' 0XFFFFFFF Confusion: Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-c0000005-crashes-on-windows-systems/"><u>Combatting C0000005 Crashes on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-ical-data-for-smooth-windows-11-use/"><u>Converting iCal Data for Smooth Windows 11 Use</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cost-free-win-10-screencast-solutions-top-5-picks/"><u>Cost-Free Win 10 Screencast Solutions  Top 5 Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-disk-space-auto-deletion-settings-for-windows-11/"><u>Declutter Your Disk Space: Auto-Deletion Settings for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-dated-wallpapers-triple-technique-trick/"><u>Ditch the Dated Wallpapers: Triple Technique Trick</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-setup-of-microsofts-powertoys-win11/"><u>Effortless Setup of Microsoft's PowerToys (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-productivity-essential-win11-and-command-tips-for-efficiency/"><u>Elevate Productivity: Essential Win11 and Command Tips for Efficiency</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-diagnosing-and-repairing-lack-of-light-in-your-razer-keyboard/"><u>Expert Advice: Diagnosing and Repairing Lack of Light in Your Razer Keyboard</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-solutions-for-error-0x80042306-during-system-restore/"><u>Expert Solutions for Error 0X80042306 During System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/experts-selection-7-best-windows-photos-apps-reviewed/"><u>Expert's Selection: 7 Best Windows Photos Apps Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/from-raw-esd-to-refined-iso-windows-conversion-techniques/"><u>From Raw ESD to Refined ISO: Windows Conversion Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/from-vocal-inputs-to-text-output-a-comprehensible-guide-for-windows-users/"><u>From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users</u></a></li>
<li><a href="https://techidaily.com/hard-reset-oneplus-nord-3-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset OnePlus Nord 3 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-an-attempt-was-made-to-reference-a-token-error-in-windows-1110/"><u>How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restart-and-streamline-windows-update-processes/"><u>How to Restart and Streamline Windows Update Processes</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-15-pro-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 15 Pro without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-s17e-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo S17e</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-top-5-high-quality-android-screen-recording-solutions/"><u>In 2024, Top 5 High-Quality Android Screen Recording Solutions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-visual-voice-choir-discovering-video-driven-music/"><u>In 2024, Visual Voice Choir  Discovering Video-Driven Music</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-webcam-master-ultimate-live-recording-guide/"><u>In 2024, WebCam Master  Ultimate Live Recording Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-14-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>iPhone 14 Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://change-location.techidaily.com/list-of-pokemon-go-joysticks-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-your-agenda-using-4-exceptional-complimentary-online-calendars/"><u>Master Your Agenda Using 4 Exceptional Complimentary Online Calendars</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-gaming-journey-optimizing-ps1-experience-in-win-using-duckstations-guide/"><u>Master Your Gaming Journey: Optimizing PS1 Experience in WIN Using Duckstation's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-ease-of-access-in-5-steps/"><u>Navigating to Windows Ease of Access in 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-barriers-in-superuser-command-activation/"><u>Overcoming Barriers in Superuser Command Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373513910-reawaken-chrome-on-win11-essential-troubleshooting-steps/"><u>Reawaken Chrome on Win11 – Essential Troubleshooting Steps.</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-windows-11-search-top-11-fixes-here/"><u>Reignite Your Windows 11 Search: Top 11 Fixes Here</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-frustrations-of-code-1132-on-win-1011/"><u>Resolving the Frustrations of Code 1132 on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functional-link-to-mb-services-on-win11-devices/"><u>Restoring Functional Link to MB Services on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374357320-seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid!</u></a></li>
<li><a href="https://windows11.techidaily.com/sky-high-internet-beyond-100mbps-overcoming-windows-speed-ceiling/"><u>Sky-High Internet Beyond 100Mbps: Overcoming Windows' Speed Ceiling</u></a></li>
<li><a href="https://fox-access.techidaily.com/streamlining-post-processing-with-effective-use-of-luts-in-pscc-for-2024/"><u>Streamlining Post-Processing with Effective Use of LUTs in PSCC for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-updating-windows-cards-a-comprehensive-guide/"><u>Swiftly Updating Windows Cards: A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tailoring-snaps-the-science-behind-compelling-advertising/"><u>Tailoring Snaps  The Science Behind Compelling Advertising</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-curiosity-non-edge-process-puzzles/"><u>Tasker's Curiosity: Non-Edge Process Puzzles</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-overhaul-pretend-its-windows-98-edition/"><u>Windows Overhaul: Pretend It's Windows 98 Edition</u></a></li>
</ul></div>
