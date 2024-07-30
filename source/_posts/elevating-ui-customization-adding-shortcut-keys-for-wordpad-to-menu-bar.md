---
title: "Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar"
date: 2024-07-29T04:27:30.475Z
updated: 2024-07-30T04:27:30.475Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar"
excerpt: "This Article Describes Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar"
keywords: UI Customize Shortcuts,Wordpad Keybar Addition,UI Enhancement Tips,Elevate Text Editor UI,User Interface Quickkeys,Menu Bar Optimization,Widget Keyboard Custom
thumbnail: https://thmb.techidaily.com/50a0e21454dc02c593e958f3f8488f7e3d42941b95d888cc2e5f79586c9b13d4.jpg
---

## Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://extra-information.techidaily.com/updated-binocular-vision-the-leading-digital-photo-enhancements/"><u>[Updated] Binocular Vision  The Leading Digital Photo Enhancements</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-visual-prowess-meets-audio-excellence-top-5-hd-webcams/"><u>[Updated] Visual Prowess Meets Audio Excellence - Top 5 HD Webcams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-miniature-homes-6-top-oriental-designs-for-mcers/"><u>2024 Approved  Miniature Homes  6 Top Oriental Designs for MCers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pushing-imagery-boundaries-mastering-ps-distortion-methods/"><u>2024 Approved  Pushing Imagery Boundaries  Mastering PS Distortion Methods</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-pathway-to-stellar-visual-results-through-color-tuning/"><u>2024 Approved  The Pathway to Stellar Visual Results Through Color Tuning</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-excessive-cpu-load-by-dropbox-app-on-windows-devices/"><u>Addressing Excessive CPU Load by Dropbox App on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-xiaomi-14-ultra-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Xiaomi 14 Ultra Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-between-wi-fi-and-ethernet-in-windows/"><u>Bridging the Gap Between Wi-Fi and Ethernet in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-ways-to-revert-personalized-settings-on-windows-11s-search/"><u>Easy Ways to Revert Personalized Settings on Windows 11'S Search</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-manage-windows-deletion-prompt-actions/"><u>Efficiently Manage Windows' Deletion Prompt Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-system-stability-automatic-windows-and-amd-driver-shift/"><u>Elevate System Stability: Automatic Windows & AMD Driver Shift</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskmgr-with-command-line-interface-cli-feature/"><u>Enhance TaskMgr with Command Line Interface (CLI) Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-self-shutdowns-steps-for-windows-11-users/"><u>Fix Self-Shutdowns: Steps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-login-hiccup-zero-based-code-error-on-win11/"><u>Fixing OneDrive Login Hiccup: Zero-Based Code Error on Win11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/full-guide-to-unlock-iphone-6-plus-with-itunes-drfone-by-drfone-ios/"><u>Full Guide to Unlock iPhone 6 Plus with iTunes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-fixing-nvidias-unreachable-error/"><u>Guiding Users Through Fixing NVIDIA's 'Unreachable' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-11-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 11 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/how-to-record-gameplay-on-windows-10-for-2024/"><u>How to Record Gameplay on Windows 10 for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-xiaomi-13t-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Xiaomi 13T</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock Apple iPhone XS Max</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-windows-innovations-to-enrich-macos/"><u>Leveraging Windows Innovations to Enrich macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/master-windows-performance-with-extended-display-setup/"><u>Master Window's Performance With Extended Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-correct-windows-installation-glitch-xc004f050/"><u>Method to Correct Windows Installation Glitch Xc004f050</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-notepad-abrupt-closures/"><u>Overcoming Windows Notepad Abrupt Closures</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tip-unearthing-windows-apps-installed-locations-quickly/"><u>Pro Tip: Unearthing Windows Apps' Installed Locations Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329285690-resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-disconnected-windows-printer-linkup/"><u>Restoring Disconnected Windows Printer Linkup</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-account-lockout-count-after-multiple-login-failures-in-windows-11/"><u>Revising Account Lockout Count After Multiple Login Failures in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-icloud-download-issues-with-these-helpful-steps/"><u>Solve iCloud Download Issues with These Helpful Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-windows-taskbar-recovery/"><u>Strategies for Windows Taskbar Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tactile-hover-over-customizing-your-click-experience-in-win11/"><u>Tactile Hover Over: Customizing Your Click Experience in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-frozen-windows-handbraked-vaults/"><u>Unlock Frozen Windows-Handbraked Vaults</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-high-dynamic-range-mastered-for-the-modern-user/"><u>Windows 11'S High Dynamic Range Mastered for the Modern User</u></a></li>
</ul></div>
