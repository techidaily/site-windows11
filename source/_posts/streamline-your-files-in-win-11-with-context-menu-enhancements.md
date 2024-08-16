---
title: Streamline Your Files in Win 11 with Context Menu Enhancements
date: 2024-08-15T15:54:21.440Z
updated: 2024-08-16T15:54:21.440Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Your Files in Win 11 with Context Menu Enhancements
excerpt: This Article Describes Streamline Your Files in Win 11 with Context Menu Enhancements
keywords: File Streamlining Win 11,Enhanced Windows Files,Context Menu Update,Win 11 Optimization,Easy File Management,Context Menus in Win 11,Organize Windows Files
thumbnail: https://thmb.techidaily.com/da30e1ebb9eb5ab25a7effb66e03594a33963d6af1f63bbe87601ee182a33306.jpg
---

## Streamline Your Files in Win 11 with Context Menu Enhancements

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

## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
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
<li><a href="https://extra-lessons.techidaily.com/new-crafting-real-world-stories-an-insight-into-documentary-screenplay-writing/"><u>[New] Crafting Real World Stories  An Insight Into Documentary Screenplay Writing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-youtube-thumbnails-saving-guide-for-2024/"><u>[New] Free YouTube Thumbnails Saving Guide for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-harmonyhub-pro-downloads-and-reviews-for-2024/"><u>[New] HarmonyHub Pro Downloads & Reviews for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-easy-way-to-share-instagram-meets-facebook/"><u>[New] In 2024, The Easy Way to Share  Instagram Meets Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-endless-escapades-top-10-best-freeware-online-rpgs/"><u>[Updated] 2024 Approved  Endless Escapades  Top 10 Best Freeware Online RPGs</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-resolve-bluetooth-pairing-failures-on-windows-1011/"><u>Easily Resolve Bluetooth Pairing Failures on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-out-of-the-eclipse-ending-dark-mode-anomaly/"><u>Easing Out of the Eclipse: Ending Dark Mode Anomaly</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-way-installing-google-play-on-win11/"><u>Easy Way: Installing Google Play on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-rename-microsoft-account-on-win11-systems/"><u>Effective Methods to Rename Microsoft Account on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-boost-for-winwms-excessive-graphics-use/"><u>Efficiency Boost for WinWM's Excessive Graphics Use</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-method-to-engagedisengage-bings-taskbar-assist/"><u>Efficient Method to Engage/Disengage Bing's Taskbar Assist</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-ways-to-handle-lunar-client-not-starting-on-pc/"><u>Efficient Ways To Handle Lunar Client Not Starting on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-navigate-your-workflow-essential-command-tips-for-win11/"><u>Efficiently Navigate Your Workflow: Essential Command Tips for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-tailor-dns-settings-for-your-win11-system/"><u>Efficiently Tailor DNS Settings for Your Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-usb-prep-for-upgrading-to-windows-11-3-tried-and-true-methods/"><u>Effortless USB Prep for Upgrading to Windows 11: 3 Tried-and-True Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-productivity-the-best-tech-tools-for-success/"><u>Elevate Windows Productivity: The Best Tech Tools for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-visual-experience-increasing-vram-capacity/"><u>Elevate Your Visual Experience: Increasing VRAM Capacity</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-security-controlling-user-biometrics-in-windows-11/"><u>Elevating Security: Controlling User Biometrics in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-onedrive-icons-in-explorer-on-windows-11/"><u>Eliminate OneDrive Icons in Explorer on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-overscan-maximizing-screen-real-estate-in-windows/"><u>Eliminate Overscan: Maximizing Screen Real Estate in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blackout-phenomenon-in-windows-titles/"><u>Eliminating Blackout Phenomenon in Windows Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-common-windows-installer-problems/"><u>Eliminating Common Windows Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-genuineness-errors-in-adobe-windows/"><u>Eliminating Genuineness Errors in Adobe Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steams-content-server-unreachable-problem-in-windows/"><u>Eliminating Steam's Content Server Unreachable Problem in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-voice-typing-glitches-in-windows-11-error-code-0x80049dd3/"><u>Eliminating Voice Typing Glitches in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0xc00000f-in-minutes/"><u>Eliminating Windows Error 0Xc00000f in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0x80072f8f-0x20000/"><u>Eliminating Windows Error: 0X80072f8f-0x20000</u></a></li>
<li><a href="https://windows11.techidaily.com/eluding-eyes-the-art-of-concealing-buttons/"><u>Eluding Eyes: The Art of Concealing Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/embellishing-windows-tray-adding-number-lock-symbols/"><u>Embellishing Windows Tray: Adding Number Lock Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-linguistic-diversity-with-windows-fonts/"><u>Embracing Linguistic Diversity with Windows Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/empower-your-pc-with-the-most-innovative-powertoys-use-cases/"><u>Empower Your PC with the Most Innovative PowerToys Use Cases</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-watching-tips-for-prime-subtitles-glitches-in-windows-11/"><u>Enhance Watching: Tips for Prime Subtitles Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-subnet-configuration-in-win11/"><u>Enhance Your Subnet Configuration in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-win11-experience-with-rgb-customization/"><u>Enhance Your Win11 Experience with RGB Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-memory-capability-for-hogwarts-virtual-learning-experience/"><u>Enhancing Graphics Memory Capability for Hogwarts Virtual Learning Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-analysis-widgets-for-hardware-monitoring/"><u>Enhancing System Analysis: Widgets for Hardware Monitoring</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/enhancing-twitters-visual-capacity-to-fhd-level/"><u>Enhancing Twitter's Visual Capacity to FHD Level</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-in-windows-11/"><u>Enhancing User Experience in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visibility-notifications-for-win11-webcam-use/"><u>Enhancing Visibility: Notifications for Win11 WebCam Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windowed-discords-query-system/"><u>Enhancing Windowed Discord's Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-the-windows-1011-requires-privilege-issue-error-0x80070522/"><u>Eradicate the Windows 10/11 Requires Privilege Issue (Error 0X80070522)</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-screen-annoyances-in-sonic-frontiers-on-windows-11/"><u>Eradicating Screen Annoyances in Sonic Frontiers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-windows-update-problems-the-0x800736cc-way/"><u>Eradicating Windows Update Problems: The 0X800736CC Way</u></a></li>
<li><a href="https://windows11.techidaily.com/error-busters-for-windows-top-10-must-haves/"><u>Error Busters for Windows: Top 10 Must-Haves</u></a></li>
<li><a href="https://windows11.techidaily.com/error-e8024002e-fixes-for-updated-windows/"><u>Error E:8024002E Fixes for Updated Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-everything-to-know-about-apple-id-password-requirements-for-apple-iphone-se-by-drfone-ios/"><u>In 2024, Everything To Know About Apple ID Password Requirements For Apple iPhone SE</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-from-concept-to-creation-youtube-trailer-production-via-filmora/"><u>In 2024, From Concept to Creation  YouTube Trailer Production via Filmora</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/innovative-techniques-for-igtv-backgrounds-for-2024/"><u>Innovative Techniques for IGTV Backgrounds for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/override-playback-halt-on-cx0d36c4-error/"><u>Override Playback Halt on Cx0d36c4 Error</u></a></li>
</ul></div>
