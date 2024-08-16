---
title: Step-by-Step Guide to Extending Windows 10/11 Contextual Commands
date: 2024-08-15T15:51:11.791Z
updated: 2024-08-16T15:51:11.791Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Extending Windows 10/11 Contextual Commands
excerpt: This Article Describes Step-by-Step Guide to Extending Windows 10/11 Contextual Commands
keywords: Windows 10/11 Command Prompt,Contextual Command Enhancement,PC Customization Tips,Extending System Functionality,Advanced Windows Usage,Efficient PC Management,Command Line Optimization
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
---

## Step-by-Step Guide to Extending Windows 10/11 Contextual Commands

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the [Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our [how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to [the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
![The Extract all option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/extract-all-option.jpg)
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-top-10-sci-fi-metaverse-movies-take-you-to-a-brand-new-world/"><u>[New] 2024 Approved  Top 10 Sci-Fi Metaverse Movies Take You to a Brand New World</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-review-mastering-facetunes-complete-features/"><u>[New] In-Depth Review  Mastering Facetune's Complete Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-small-companys-guide-to-the-safest-online-chat-services/"><u>[New] Small Company's Guide to the Safest Online Chat Services</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-speedy-shot-techniques-to-boost-home-filmmaking/"><u>[New] Speedy Shot Techniques to Boost Home Filmmaking</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-the-duel-of-durability-hero-5-black-versus-keymission-for-2024/"><u>[New] The Duel of Durability  HERO 5 Black Versus Keymission for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-get-rid-of-youtube-shorts-a-comprehensible-guide-for-2024/"><u>[Updated] Get Rid of YouTube Shorts  A Comprehensible Guide for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-ps1-classics-on-your-desktop-the-best-emulators-reviewed/"><u>[Updated] In 2024, PS1 Classics on Your Desktop  The Best Emulators Reviewed</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-instagram-ringtone-making-manual/"><u>[Updated] The Ultimate Instagram Ringtone Making Manual</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-a-comprehensive-look-at-djis-quadcopter-standard-flight/"><u>2024 Approved  A Comprehensive Look at DJI's Quadcopter Standard Flight</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-compelling-youtube-profile-definitions-for-2024/"><u>Crafting Compelling YouTube Profile Definitions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-activate-hyper-v-on-w11-home-pcs/"><u>Easy Steps to Activate Hyper-V on W11 Home PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-dns-clearing-on-the-newest-windows-os/"><u>Effective DNS Clearing on the Newest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-energy-use-with-windows-pcs/"><u>Efficient Energy Use with Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-adding-google-play-to-windows-11/"><u>Efficiently Adding Google Play to Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-drag-fixes-for-your-win11-desktop/"><u>Effortless Drag Fixes for Your Win11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-tech-integration-flow-app-connects-pc-galaxy/"><u>Effortless Tech Integration – Flow App Connects PC, Galaxy</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-theme-changes-for-a-stylish-windows-11-desktop/"><u>Effortless Theme Changes for a Stylish Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-updates-switching-to-new-amd-drivers/"><u>Effortless Windows Updates: Switching to New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-switching-files-between-formats-in-windows/"><u>Effortlessly Switching Files Between Formats in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elderly-tech-making-older-computers-senior-friendly/"><u>Elderly Tech: Making Older Computers Senior Friendly</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-development-workflow-navigating-windows-11s-dev-drive/"><u>Elevate Development Workflow: Navigating Windows 11'S Dev Drive</u></a></li>
<li><a href="https://techtrends.techidaily.com/elevate-your-facebook-game-discover-5-productivity-hacks-for-social-media-success/"><u>Elevate Your Facebook Game: Discover 5 Productivity Hacks for Social Media Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-vm-experience-implement-these-six-strategies-for-windows/"><u>Elevate Your VM Experience: Implement These Six Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-device-protection-prolonging-windows-11-pin-code/"><u>Elevating Device Protection: Prolonging Windows 11 Pin Code</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-driver-enforcement-loading-unsigned-on-windows-108/"><u>Eliminating Driver Enforcement: Loading Unsigned On Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-faulty-devices-from-system-logs-windows-1011/"><u>Eliminating Faulty Devices From System Logs: Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-read-only-files-a-guide-for-windows-11-users/"><u>Eliminating Read-Only Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-world-typography-on-windows-font-guide/"><u>Embrace World Typography on Windows - Font Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-failed-driver-loading-in-windows-11/"><u>Enabling Failed Driver Loading in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-browsing-with-windows-10s-safeguard/"><u>Enabling Secure Browsing with Windows 10’S SafeGuard</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-saga-how-to-smoothly-sync-chromebook-files-in-windows/"><u>End the Saga: How to Smoothly Sync Chromebook Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/energy-efficiency-windows-rest-states-analysis/"><u>Energy Efficiency: Windows' Rest States Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-interface-with-an-efficient-auto-check-function-for-win11/"><u>Enhance Windows Interface with an Efficient Auto-Check Function for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-onedrive-performance-a-comprehensive-guide-for-pc-users/"><u>Enhancing OneDrive Performance: A Comprehensive Guide for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-ram-performance-bypass-windows-limitations/"><u>Enhancing RAM Performance: Bypass Windows Limitations</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-touchscreen-accuracy-windows-11-tutorial/"><u>Enhancing Touchscreen Accuracy: Windows 11 Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-installer-security-for-user-privileges/"><u>Enhancing Windows Installer Security for User Privileges</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wsl-2s-docker-capabilities-key-insights/"><u>Enhancing WSL 2'S Docker Capabilities: Key Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-digital-security-best-windows-cryptography-picks-148-chars/"><u>Ensuring Digital Security: Best Window's Cryptography Picks (148 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-full-visibility-for-system-startups/"><u>Ensuring Full Visibility for System Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-system-misses-message-on-windows-os/"><u>Erase System Misses Message on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/error-code-x80246007-fixing-windows-update-issues/"><u>Error Code X80246007: Fixing WIndows Update Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-app-list-for-seamless-os-transition-from-apple-to-windows/"><u>Essential App List for Seamless OS Transition From Apple to Windows</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-15-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone 15 Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-iphone-13-mini-drfone-by-drfone-ios/"><u>How Do You Remove Restricted Mode on iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-12-proplus-5g-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Realme 12 Pro+ 5G Bootloader Easily</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-oppo-a78-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Oppo A78 5G FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-connecting-to-dropbox-and-google-drive-directly/"><u>Mastering Windows: Connecting to Dropbox & Google Drive Directly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-resolving-steam-setup-errors-with-win11/"><u>Navigating and Resolving Steam Setup Errors with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-systems-uncovering-5-prime-performance-strategies/"><u>Swift Systems: Uncovering 5 Prime Performance Strategies</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-vivo-v30-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Vivo V30</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unending-education-odyssey-the-1500th-of-no-cost-sessions-celebration/"><u>Unending Education Odyssey: The 1500Th of No-Cost Sessions Celebration</u></a></li>
</ul></div>
