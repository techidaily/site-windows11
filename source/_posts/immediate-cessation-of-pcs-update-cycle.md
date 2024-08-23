---
title: Immediate Cessation of PC's Update Cycle
date: 2024-08-22T21:43:01.393Z
updated: 2024-08-23T21:43:01.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Immediate Cessation of PC's Update Cycle
excerpt: This Article Describes Immediate Cessation of PC's Update Cycle
keywords: Stop PC Updates,Halt System Update,Cease Patching Process,Terminate OS Upgrades,Quit Automatic Updates,Disable Software Updates,Halting System Patches
thumbnail: https://thmb.techidaily.com/589975317cd54578e2464cf37ff9c3436a24bffda2b797c9a9ae1ed0b5abaff9.jpg
---

## Immediate Cessation of PC's Update Cycle

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to[download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


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
<li><a href="https://fox-helps.techidaily.com/new-quieten-system-sounds-on-pc-and-mac-devices-for-2024/"><u>[New] Quieten System Sounds on PC and Mac Devices for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-best-ten-spotify-equipment-for-high-quality-recording-for-2024/"><u>[New] The Best Ten Spotify Equipment for High-Quality Recording for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-sprinkle-of-life-in-your-text-animations/"><u>[New] The Sprinkle of Life in Your Text Animations</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-discovering-those-who-left-my-instagram-circle/"><u>[Updated] 2024 Approved  Discovering Those Who Left My Instagram Circle</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-mastering-metaverse-laughter-how-to-make-unforgettable-meme-art/"><u>[Updated] 2024 Approved  Mastering Metaverse Laughter  How to Make Unforgettable Meme Art</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-fine-tuning-your-linkedin-headline-for-2024/"><u>[Updated] Fine-Tuning Your LinkedIn Headline for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-15plus-best-iphoneipad-video-editing-tools-in-free-market/"><u>[Updated] In 2024, 15+ Best iPhone/iPad Video Editing Tools in Free Market</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-mastering-the-art-of-incorporating-youtube-in-slate-presentations/"><u>[Updated] In 2024, Mastering the Art of Incorporating YouTube in Slate Presentations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expertly-selected-10-best-gimbals-for-smartphone-and-dslr-cameras/"><u>2024 Approved  Expertly Selected 10 Best Gimbals for Smartphone & DSLR Cameras</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-hidden-gems-6-secret-voice-recorder-apps-for-android-and-ios/"><u>2024 Approved  Hidden Gems! 6 Secret Voice Recorder Apps for Android & iOS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-art-of-recording-your-online-fb-conversations/"><u>2024 Approved  The Art of Recording Your Online FB Conversations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/action-cameras-clash-gopro-hero5-black-against-yi-4k-update-for-2024/"><u>Action Cameras Clash  GoPro Hero5 Black Against Yi 4K Update for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ffect-filmmaking-youtubes-guide-to-green-magic/"><u>Eco-Effect Filmmaking  YouTube's Guide to Green Magic</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exiting-the-chatgpt-realm-top-alternatives/"><u>Exiting the ChatGPT Realm: Top Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-external-devices-in-explorers-side/"><u>Expanding External Devices in Explorer's Side</u></a></li>
<li><a href="https://games-able.techidaily.com/from-console-joy-to-computer-control-the-process-explained-156-chars/"><u>From Console Joy to Computer Control: The Process Explained (156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/from-cr2-to-jpg-on-windows-a-comprehensive-conversion-guide/"><u>From CR2 to JPG on Windows: A Comprehensive Conversion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-showhide-directories-on-modern-windows-11-pcs/"><u>Guide to Show/Hide Directories on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-error-code-0xc00000f-with-ease-on-pcs/"><u>Handling Error Code 0xC00000F with Ease on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-or-disable-in-hand-typing-windows-10/"><u>How to Enable or Disable In-Hand Typing Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-quake-mode-in-windows-terminal/"><u>How to Enable Quake Mode in Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-plain-out-windows-edges/"><u>How to Plain Out Windows Edges</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-oppo-a18-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Oppo A18</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-y78-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo Y78 5G Is Unlocked</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-motorola-moto-g23-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Motorola Moto G23 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-spark-10-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Spark 10 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-from-your-apple-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status From Your Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-samsung-galaxy-a14-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Samsung Galaxy A14 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instantly-strip-outdated-graphic-cards-windows-style/"><u>Instantly Strip Outdated Graphic Cards, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-your-smartphone-as-a-windows-microphone/"><u>IPhone/Android: Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-image-spin-6-tactics-for-windows-11/"><u>Mastering Image Spin: 6 Tactics for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-quick-start-for-rdc-on-windows-11/"><u>Mastering the Art of Quick Start for RDC on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-file-history-setting-glitch-in-windows-os/"><u>Mending File History Setting Glitch in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-local-gpo-on-windows-with-ease/"><u>Navigating Local GPO on Windows with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-projection-failure-issue/"><u>Overcoming Windows Projection Failure Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-diagnosis-navigating-through-windows-error-messages-with-command-line-skills/"><u>Precision in Diagnosis: Navigating Through Windows Error Messages with Command Line Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-error-x8019-on-windows-xp/"><u>Preventing Error X8019 on Windows XP</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-lost-5ghz-lan-link-in-windows-11-heres-how/"><u>Reclaim Your Lost 5GHz LAN Link in Windows 11 Here's How</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-power-a-windows-guide-to-net-repair-max-156/"><u>Regaining Power: A Windows Guide to .NET Repair (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-discords-loading-failures-in-windows/"><u>Resolving Discord's Loading Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-functional-activation-in-os-11/"><u>Resolving Non-Functional Activation in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-and-restore-key-applications-for-changing-createdmodified-dates/"><u>Rewind and Restore: Key Applications for Changing Created/Modified Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-for-converting-bat-files-into-exes/"><u>Simplified Guide for Converting .bat Files Into EXEs</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-compatibility-issues-between-usb-and-serial-on-win/"><u>Solve Compatibility Issues Between USB & Serial on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-swiftly-eradicating-windows-steams-e84-error/"><u>Strategies for Swiftly Eradicating Windows Steam's E84 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notepad-with-astute-mentor/"><u>Supercharge Win11's Notepad with Astute Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-made-window-ordering-powertoy-guide-to-win-os-snaps/"><u>Tailor-Made Window Ordering: PowerToy Guide to Win OS Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-shortcut-compendium-windows-narrators-command-guide/"><u>The Ultimate Shortcut Compendium: Windows Narrator's Command Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-personalization-hacks-for-windows-1011-via-bubbleui/"><u>Top 8 Personalization Hacks for Windows 10/11 via BubbleUI</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/total-review-demystifying-googles-podcast-app/"><u>Total Review  Demystifying Google's Podcast App</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-proper-thx-surround-sound/"><u>Troubleshooting Windows for Proper THX Surround Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-winservicesexe-insights-for-windows-users/"><u>What Is WinServices.exe? Insights for Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-relying-on-ai-bots-for-your-windows-11-license-isnt-a-smart-move/"><u>Why Relying on AI Bots for Your Windows 11 License Isn't a Smart Move</u></a></li>
<li><a href="https://windows11.techidaily.com/wingetui-masterclass-enhancing-windows-11s-application-handling/"><u>WingetUI Masterclass: Enhancing Windows 11'S Application Handling</u></a></li>
</ul></div>
