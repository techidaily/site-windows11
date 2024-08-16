---
title: "Mastering Windows 11 Menu: Erase Show More Options"
date: 2024-08-15T15:43:34.153Z
updated: 2024-08-16T15:43:34.153Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11 Menu: Erase Show More Options"
excerpt: "This Article Describes Mastering Windows 11 Menu: Erase Show More Options"
keywords: Win11 Menu Guide,Menu Expansion Tips,Navigate Win11,Hide Win11 Extras,Optimize Win11 UI,Master Win11 Layout,Windows Options Insight
thumbnail: https://thmb.techidaily.com/06b7f9bb308a2f230442ff554dbb6dddbc8b32cf4318fa7b79eedb41360cb388.jpg
---

## Mastering Windows 11 Menu: Erase Show More Options

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-explore-our-12-tycoon-classics-for-engrossing-experiences/"><u>[New] 2024 Approved  Explore Our #12 Tycoon Classics for Engrossing Experiences</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-public-domain-art-what-is-it-and-website-recommendations/"><u>[New] Exploring Public Domain Art  What Is It and Website Recommendations</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-whats-in-your-wallet-from-one-million-youtube-sights/"><u>[New] In 2024, What's In Your Wallet From One Million YouTube Sights?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-seamless-speed-control-the-editors-essential-handbook/"><u>[New] Seamless Speed Control  The Editor's Essential Handbook</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-the-blueprint-of-an-engaging-podcast-blurb-for-2024/"><u>[New] The Blueprint of an Engaging Podcast Blurb for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-perfect-your-pitch-with-android-the-ultimate-list-of-voice-alteration-apps/"><u>[Updated] 2024 Approved  Perfect Your Pitch with Android  The Ultimate List of Voice Alteration Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-perfect-guide-to-making-your-video-memories-last-with-gifs/"><u>[Updated] In 2024, The Perfect Guide to Making Your Video Memories Last with GIFs</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-optimal-5-filters-for-deep-blue-cinematography/"><u>[Updated] Optimal 5 Filters for Deep Blue Cinematography</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-plotline-path-to-youtube-prosperity/"><u>[Updated] Plotline Path to YouTube Prosperity</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-10-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 10 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-the-hardware-ids-of-your-devices-on-windows/"><u>4 Ways to Check the Hardware IDs of Your Devices on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-reasons-to-choose-windows-10-over-windows-11/"><u>7 Reasons to Choose Windows 10 Over Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-telnet-on-windows-3-key-methods/"><u>Activating Telnet on Windows: 3 Key Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-operational-state-of-ccleaner-on-win1011-systems/"><u>Addressing Non-Operational State of CCleaner on Win10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-unavailable-display-settings-in-nvidia-software/"><u>Addressing Unavailable Display Settings in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-space-efficiency-of-windows-software/"><u>Analyzing Space Efficiency of Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-decreased-size-of-your-windows-11-icons/"><u>Avoid Decreased Size of Your Windows 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-the-surface-innocent-looking-apps-steal-speed-from-pcs/"><u>Beneath the Surface, Innocent-Looking Apps Steal Speed From PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/breached-byte-bastion-maintain-reflect-then-switch/"><u>Breached Byte Bastion: Maintain, Reflect, Then Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-workflow-of-windows-11s-recovery-features/"><u>Breaking Down the Workflow of Windows 11'S Recovery Features</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-sound-on-systems-running-low-volume-errors/"><u>Bring Back Sound on Systems Running Low Volume Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-steam-cloud-errors/"><u>Clearing Up Steam Cloud Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-11s-taskbar-search-function/"><u>Concealing Windows 11'S Taskbar Search Function</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-shortcut-personalization-techniques/"><u>Cutting-Edge Windows 11 Shortcut Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/free-logo-blueprint-tailor-and-share-your-brand-identity/"><u>Free Logo Blueprint  Tailor and Share Your Brand Identity</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17t-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17t to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-art-of-creating-spherical-shots-with-fisheye-lenses/"><u>In 2024, The Art of Creating Spherical Shots with Fisheye Lenses</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-visual-symphony-iosandroid-instagram-collage-app/"><u>In 2024, Visual Symphony  IOS/Android Instagram Collage App</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-photoscape-analysis-top-features-of-this-complimentary-graphic-design-tool/"><u>In-Depth Photoscape Analysis: Top Features of This Complimentary Graphic Design Tool</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovating-job-quests-6-chatgpt-techniques-explored/"><u>Innovating Job Quests: 6 ChatGPT Techniques Explored</u></a></li>
<li><a href="https://extra-resources.techidaily.com/learn-how-to-distort-pic-using-different-tools/"><u>Learn How to Distort Pic Using Different Tools</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/mastering-photo-management-with-the-nixplay-iris-system/"><u>Mastering Photo Management with the Nixplay Iris System</u></a></li>
<li><a href="https://windows11.techidaily.com/1719270325227-seeking-help-navigate-through-windows-troubles-easily/"><u>Seeking Help? Navigate Through Windows Troubles Easily</u></a></li>
<li><a href="https://data-wizards.techidaily.com/vivid-verification-real-users-on-screen/"><u>Vivid Verification: Real Users on Screen</u></a></li>
</ul></div>
