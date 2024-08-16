---
title: "Augmented Folder Actions: Power Up Your File Management"
date: 2024-08-15T15:56:45.221Z
updated: 2024-08-16T15:56:45.221Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Augmented Folder Actions: Power Up Your File Management"
excerpt: "This Article Describes Augmented Folder Actions: Power Up Your File Management"
keywords: AugFolderActionsBoost,EnhancedFileManagement,FolderActionUpgrade,OptimizedFileHandling,BoostedFileSystem,AdvancedFoldersystem,FileManagementEnhancement
thumbnail: https://thmb.techidaily.com/7231e7cfa11b8c48bc0e8ca6efb14ca7e0a26276b7faf838f32af6539b7e71cf.jpg
---

## Augmented Folder Actions: Power Up Your File Management

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
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-gaming-recorded-the-complete-breakdown/"><u>[New] 2024 Approved  Gaming Recorded  The Complete Breakdown</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-overcoming-the-invisible-barrier-in-tiktok-world/"><u>[New] 2024 Approved  Overcoming the Invisible Barrier in TikTok World</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-easy-to-use-free-youtube-downloader-with-mp3-support-for-2024/"><u>[New] Easy-to-Use Free YouTube Downloader with MP3 Support for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-exploring-the-essence-of-vimeo-a-leader-in-video-platforms/"><u>[New] Exploring the Essence of Vimeo  A Leader in Video Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-exploring-youtubes-payment-mechanisms-for-content-makers/"><u>[New] In 2024, Exploring YouTube's Payment Mechanisms for Content Makers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-quick-guide-capturing-vimeo-videos/"><u>[New] In 2024, Quick Guide  Capturing Vimeo Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-filmopedia-answer-to-inquiries/"><u>[Updated] FilmoPedia  Answer to Inquiries</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-novice-to-master-photographer-with-lunapic/"><u>[Updated] From Novice to Master Photographer with LunaPic</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unveiling-how-t-series-earnings-growth-on-youtube-works/"><u>[Updated] Unveiling How T-Series Earnings Growth on YouTube Works</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-webcams-that-win-top-picks-for-youtube-stream-success/"><u>2024 Approved  Webcams that Win  Top Picks for YouTube Stream Success</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-vivo-y27-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-digital-experience-process-control-and-thematic-aesthetics-in-w11/"><u>Elevate Your Digital Experience: Process Control & Thematic Aesthetics in W11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/enabling-autoplay-youtube-videos-in-social-media-network/"><u>Enabling Autoplay Youtube Videos in Social Media Network</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-office-applications-open-email-attachments-as-text-only-by-design/"><u>Ensure Office Applications Open Email Attachments as Text Only by Design</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-backup-bin-to-picture-panel-guiding-games-on-pcs-with-w11/"><u>From Backup Bin to Picture Panel: Guiding Games on PCs with W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-remedy-disconnected-windows-11-printers/"><u>Guide to Remedy Disconnected Windows 11 Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-x-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone X Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-samsung-galaxy-a23-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Samsung Galaxy A23 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-non-sport-spectacles-in-the-top-ten-front-rows/"><u>In 2024, Non-Sport Spectacles in the Top Ten Front Rows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfecting-the-art-of-gif-to-sticker-transition-on-various-messaging-platforms/"><u>In 2024, Perfecting the Art of GIF to Sticker Transition on Various Messaging Platforms</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-on-iphone-13-mini-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number On iPhone 13 mini</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-knots-unraveling-win10-functional-issues/"><u>Keyboard Knots: Unraveling WIN10 Functional Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-lan-world-play-in-windows-mc-game/"><u>Mastering LAN World Play in Windows MC Game</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-program-use-in-windows-via-right-click-options/"><u>Optimizing Program Use in Windows via Right-Click Options</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-shrink-or-enlarge-apps-using-shortcut-on-win11/"><u>Perfecting the Art: Shrink or Enlarge Apps Using Shortcut on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-photos-from-infinix-hot-40-by-fonelab-android-recover-photos/"><u>Possible solutions to restore deleted photos from Infinix Hot 40.</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-reviving-with-modern-os-alternatives/"><u>Redefine Reviving with Modern OS Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule!</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-windows-activation-flaw-error-0x803f700f/"><u>Remedying Windows Activation Flaw: Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-back-to-legacy-window-explorer/"><u>Reverting Back to Legacy Window Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-ui-adding-cli-functionality-to-taskmgr-in-win11/"><u>Revolutionizing UI: Adding CLI Functionality to TaskMgr in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-game-wont-launch-issues-by-validating-your-game-installation/"><u>Solving 'Game Won't Launch' Issues by Validating Your Game Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-timeline-microsofts-ui-evolution/"><u>Taskbar Timeline: Microsoft's UI Evolution</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disconnect-untrusted-users-from-windows-11/"><u>Techniques to Disconnect Untrusted Users From Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-iphone-x-drfone-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of iPhone X | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-tecno-spark-10-5g-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Tecno Spark 10 5G.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-apple-iphone-14-pro-and-android-phones-by-drfone-ios/"><u>Top IMEI Unlokers for Apple iPhone 14 Pro and Android Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-busy-errors-on-pcs/"><u>Troubleshooting Printer Busy Errors on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-wxpxo11-dilemnas-fixes-for-non-openable-folders-after-double-clicks/"><u>Unfolding WXP/XO11 Dilemnas: Fixes for Non-Openable Folders After Double-Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-registry-a-guide-to-its-components/"><u>Unveiling Windows 11'S Registry: A Guide to Its Components</u></a></li>
<li><a href="https://windows11.techidaily.com/verify-the-validity-three-ways-to-check-windows-11/"><u>Verify the Validity: Three Ways to Check Windows 11</u></a></li>
</ul></div>
