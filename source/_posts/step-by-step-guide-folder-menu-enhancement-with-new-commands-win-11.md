---
title: "Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)"
date: 2024-08-15T15:50:11.428Z
updated: 2024-08-16T15:50:11.428Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)"
excerpt: "This Article Describes Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)"
keywords: Win 11 Folder Commands Guide,Enhancing Windows Folder View,Menu Command Updates Win 11,Win 11 File Management Tips,Improve Win 11 Navigation Menus,Customizing Win 11 Menu Options,New Commands for Win 11 Folders
thumbnail: https://thmb.techidaily.com/c889a547e421f550d3854604da4881f54e6123831fe3b245b44881a2b3d8e123.jpg
---

## Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
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
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-adapting-your-favorite-songs-from-spotify-to-youtube-music-service-for-2024/"><u>[New] Adapting Your Favorite Songs From Spotify to YouTube Music Service for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-enhance-videos-effortlessly-with-story-remix-and-windows-10-photos/"><u>[New] Enhance Videos Effortlessly with Story Remix and Windows 10 Photos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-tricks-to-enhance-your-ppt-impact-on-google-meet-any-device/"><u>[Updated] 2024 Approved  Tricks to Enhance Your PPT Impact on Google Meet, Any Device</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-screensnapper-revisited-apowersofts-latest-pc-tool/"><u>[Updated] ScreenSnapper Revisited  Apowersoft's Latest PC Tool</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-the-art-of-captivation-rally-more-likes-for-your-tiktok-unpacks/"><u>[Updated] The Art of Captivation  Rally More Likes for Your TikTok Unpacks</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-from-silence-to-soundscape-embedding-mp3s-in-presentations/"><u>2024 Approved  From Silence to Soundscape  Embedding MP3s in Presentations</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-t2-pro-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo T2 Pro 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-t2-5g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo T2 5G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-step-by-step-approach-to-discard-youtube-watch-later-items-for-2024/"><u>A Step-by-Step Approach to Discard YouTube Watch Later Items for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-discord-speed-a-step-by-step-guide/"><u>Boosting Windows Discord Speed: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/brush-up-your-youtube-videos-with-color-correction-for-2024/"><u>Brush Up Your Youtube Videos with Color Correction for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-samsung-galaxy-s23-ultra-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Samsung Galaxy S23 Ultra is off? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-steam-performance-preventing-zero-speed-slowdowns/"><u>Elevate Windows Steam Performance: Preventing Zero-Speed Slowdowns</u></a></li>
<li><a href="https://program-issues.techidaily.com/elevate-your-game-battlefield-2042s-fps-issues-and-stutters-corrected-for-a-seamless-pc-adventure/"><u>Elevate Your Game - Battlefield ˈ2042's FPS Issues & Stutters Corrected for a Seamless PC Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/freedom-from-filmage-tiktok-videos-without-stickers/"><u>Freedom From Filmage  TikTok Videos Without Stickers</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-samsung-galaxy-s23-fe-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-samsung-galaxy-f54-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Samsung Galaxy F54 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-master-the-use-of-winservicesexe-on-windows/"><u>How to Master the Use of Winservices.exe on Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-repair-an-iphone-mobile-hotspot-that-wont-connect/"><u>How to Repair an iPhone Mobile Hotspot That Won't Connect</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-y200-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo Y200</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-a05-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy A05 Lock Screen Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-samsung-galaxy-xcover-6-pro-tactical-edition-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Samsung Galaxy XCover 6 Pro Tactical Edition Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-second-screen-harmony-windows-plus-android-tablets/"><u>Mastering Second Screen Harmony: Windows + Android Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/navigating-url-integration-in-ig-stories-and-posts/"><u>Navigating URL Integration in IG Stories and Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-multi-display-setup/"><u>Navigating Windows 11 Multi-Display Setup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-free-ai-powered-face-makers-no-download-required-for-2024/"><u>New Free AI-Powered Face Makers No Download Required for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-isarcextract-error-a-window-11-solution/"><u>Overcoming ISArcExtract Error: A Window 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-dual-device-names-on-your-windows-network/"><u>Preventing Dual Device Names on Your Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-troubleshooters-in-windows-11-with-custom-keys/"><u>Quick Access to Troubleshooters in Windows 11 with Custom Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tricks-to-pinpoint-your-graphic-card-on-windows-11/"><u>Quick Tricks to Pinpoint Your Graphic Card on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-windows-search-top-11-remedies-explored/"><u>Reinvigorate Windows Search: Top 11 Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/security-enhancement-manual-add-a-self-designed-lock-pattern/"><u>Security Enhancement Manual: Add a Self-Designed Lock Pattern</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-absence-of-windows-1011-search-outcomes/"><u>Solving Absence of Windows 10/11 Search Outcomes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-up-to-greater-ai-efficiency-with-these-top-browser-plugins/"><u>Step Up to Greater AI Efficiency with These Top Browser Plugins</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-onedrive-errors-on-w11-systems/"><u>Strategies to Overcome OneDrive Errors on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-approach-to-bypass-cant-add-your-folder-now-error-in-windows-onedrive-drive/"><u>Swift Approach to Bypass 'Can't Add Your Folder Now' Error in Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-group-policies-focusing-on-one-user-at-a-time/"><u>Tailoring Group Policies: Focusing on One User at a Time</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-windows-11-navshortcuts/"><u>The Ultimate List of Windows 11 NavShortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-fixes-for-rename-restrictions-on-files-and-directories-of-windows-11/"><u>Top 7 Fixes for Rename Restrictions on Files and Directories of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-win-11-desk-aids-boosting-workflow/"><u>Top 7 Win 11 Desk Aids Boosting Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/trends-in-firmware-enhancement-what-every-surface-user-needs-to-know/"><u>Trends in Firmware Enhancement: What Every Surface User Needs to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-zoom-error-1132-on-windows-11/"><u>Troubleshooting Zoom Error 1132 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-widget-toolbar-functionality-in-win11/"><u>Understanding the Widget Toolbar Functionality in Win11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/unseen-snaps-and-hushed-user-signal-to-check-for-blocks-for-2024/"><u>Unseen Snaps and Hushed User  Signal to Check for Blocks for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/your-beginners-guide-to-making-money-on-youtubers-for-2024/"><u>Your Beginner's Guide to Making Money on YouTubers for 2024</u></a></li>
</ul></div>
