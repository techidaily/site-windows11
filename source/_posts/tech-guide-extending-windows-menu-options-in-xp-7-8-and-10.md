---
title: "Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10"
date: 2024-08-15T16:20:09.533Z
updated: 2024-08-16T16:20:09.533Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10"
excerpt: "This Article Describes Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10"
keywords: WinXP Menu Extend,XP Menu Expand,Win7 Menu Extend,Win7 Menu Enhance,Win7 Menu Customize,Win8+ Menu Options,Menu Extension Guide
thumbnail: https://thmb.techidaily.com/4f7677089ce9d876fde36aa600317f042b44ee73a802e442be2008c2b3992f0d.jpg
---

## Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the[Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our[how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
2. Click inside the address bar at the top of Registry Editor, and erase the current key location there.
3. Then enter this**ContextMenuHandlers** key location and press**Return** :  
`HKEY_CLASSES_ROOT\AllFilesystemObjects\shellex\ContextMenuHandlers`
4. Next, right-click**ContextMenuHandlers** and select the**New** submenu.
5. Click**Key** on the submenu.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-key-option.jpg)

1. Enter**Move to folder** for the new key’s name.
2. Select the new**Move to folder** key in the Registry Editor’s sidebar.
3. Double-click the**(Default)** string for the selected key.
4. Input**{C2FBB631-2971-11D1-A18C-00C04FD75D13}** inside the**Value data** box.  
![The value data for the Move to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window.jpg)
5. Select**OK** to set the new value for the (Default) string.
6. Exit the Registry Editor.

 You can now try out the new**Move to folder** option on the context menu. Press the**Explorer** taskbar button to view the Windows file manager. Right-click a file and select the new**Move to folder** option. You’ll need to select**Show more options** \>**Move to folder i** n Windows 11.

![The Move to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-to-folder-context-menu-option.jpg)

 A small Move Items window will then appear from which you can select a destination folder. Choose a folder to move the file to in that window. Then click**Move** to place the file in the selected directory.

![The Move Items window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-items-window.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to[the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
![The Extract all option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/extract-all-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Move and Copy Files to Folders With Your New Context Menu Options

 The**"** Copy/Move to folder" context menu options undoubtedly provide more convenient ways to copy and move files into alternative directories. You won’t need to drag files about anymore for moving items in Windows 11 after adding a new**"** Move to Folder option" to the right-click menu. Nor will you need to paste copied files elsewhere in Windows 11 thanks to the "Copy to folder" menu option.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-bring-footage-together-ken-burns-technique-for-camtasa-users/"><u>[New] Bring Footage Together  Ken Burns Technique for Camtasa Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-cinematographic-cuisine-expert-tips-on-filming-edibles/"><u>[New] Cinematographic Cuisine  Expert Tips on Filming Edibles</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-dual-drive-approach-video-uploads-to-twitter-plus-tumblr/"><u>[New] The Dual-Drive Approach  Video Uploads to Twitter + Tumblr</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-mastering-professional-camera-techniques-for-superior-igtv-videos/"><u>[Updated] 2024 Approved  Mastering Professional Camera Techniques for Superior IGTV Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advanced-tips-for-organizing-your-youtube-clip-structure/"><u>[Updated] Advanced Tips for Organizing Your YouTube Clip Structure</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-choosing-between-two-titans-obs-and-bandicam/"><u>[Updated] Choosing Between Two Titans  OBS and Bandicam</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-discover-everything-in-stardews-hidden-gem-ginger-isle/"><u>[Updated] In 2024, Discover Everything in Stardew's Hidden Gem, Ginger Isle</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-swift-method-image-alchemy-into-engaging-youtube-thumbnail-pics/"><u>[Updated] In 2024, Swift Method  Image Alchemy Into Engaging YouTube Thumbnail Pics</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unleashing-your-gaming-potential-with-win10-recordings/"><u>[Updated] In 2024, Unleashing Your Gaming Potential with Win10 Recordings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-newbies-ultimate-youtube-gear-handbook/"><u>[Updated] Newbies' Ultimate YouTube Gear Handbook</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-effortless-photo-retouch-dive-into-background-removal/"><u>2024 Approved  Effortless Photo Retouch  Dive Into Background Removal</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-pro-tips-for-impressive-gopro-time-lapse-cinematography/"><u>2024 Approved  Pro Tips for Impressive GoPro Time-Lapse Cinematography</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/audio-alchemy-mixing-techniques-for-sound-fusion-with-davinci-resolve/"><u>Audio Alchemy  Mixing Techniques for Sound Fusion with DaVinci Resolve</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/budgeted-bark-box-pet-vids-compendium/"><u>Budgeted Bark-Box: Pet Vids Compendium</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-lockout-overcoming-windows-11-device-error-code-22/"><u>Bypassing Lockout: Overcoming Windows 11 Device Error Code 22</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-secrecy-in-images-with-photoshop/"><u>Crafting Secrecy in Images with Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pointer-design-in-microsoft-systems/"><u>Customize Pointer Design in Microsoft Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-winirq-conflicts-for-clear-audio/"><u>Decoding and Resolving WinIRQ Conflicts for Clear Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-dichotomy-microsoft-vs-native-user-account-on-windows-os/"><u>Dissecting the Dichotomy: Microsoft vs Native User Account on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/essentials-of-implementing-windows-law-filters-effectively/"><u>Essentials of Implementing Windows LAW Filters Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-copy-paste-efficiency-across-browsers/"><u>How to Enhance Copy-Paste Efficiency Across Browsers</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-motorola-moto-g24-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Motorola Moto G24.</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-cross-media-iptv-synchronization/"><u>In 2024, Cross-Media IPTV Synchronization</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-supreme-five-optimal-dvd-software-for-sierra-os/"><u>In 2024, Supreme Five  Optimal Dvd Software for Sierra OS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-top-20-hilarious-tiktok-skits-for-giggle-fests/"><u>In 2024, Top 20 Hilarious TikTok Skits for Giggle Fests</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/larger-than-life-boosting-taskbar-icons-in-w11/"><u>Larger-than-Life: Boosting Taskbar Icons in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-morning-routine-launching-windows-and-sticky-notes/"><u>Mastering Morning Routine: Launching Windows & Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-settings-for-effortless-administration/"><u>Mastering Windows 11 Settings for Effortless Administration</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-recalibrate-windows-energy-plan/"><u>Method to Recalibrate Window's Energy Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-solutions-faster-configuring-shortcuts-for-win-1011-tools/"><u>Navigate to Solutions Faster: Configuring Shortcuts for Win 10/11 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722184338031-no-subscriptions-for-gpt-4-however-select-plus-membership-retains-its-unique-6-features/"><u>No Subscriptions for GPT-4: However, Select Plus Membership Retains Its Unique 6 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-1011-zoom-fatal-error-1132/"><u>Resolving Win 10/11 Zoom Fatal Error 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-screen-position-changes/"><u>Simple Steps for Screen Position Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-chrome-the-ultimate-guide-for-self-launched-tab-control/"><u>Stop Chrome: The Ultimate Guide for Self-Launched Tab Control</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-powerhouse-performer-unveiling-the-arcshell-ar-5-outstanding-quality-at-an-exceptional-price/"><u>The Powerhouse Performer - Unveiling the Arcshell AR-5: Outstanding Quality at an Exceptional Price</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-and-fix-windows-autoshrink-issue/"><u>Troubleshoot & Fix Windows' Autoshrink Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-office-activation-woes/"><u>Unlocking Windows Office Activation Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
</ul></div>
