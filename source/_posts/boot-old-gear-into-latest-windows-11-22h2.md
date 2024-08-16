---
title: Boot Old Gear Into Latest Windows 11 22H2
date: 2024-08-15T15:14:42.412Z
updated: 2024-08-16T15:14:42.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boot Old Gear Into Latest Windows 11 22H2
excerpt: This Article Describes Boot Old Gear Into Latest Windows 11 22H2
keywords: Upgrade to Windows 11,Modernize PCs with Windows 11,Transition From Old OS,Embrace Windows 11 Features,Update to Latest Windows Version,Install Windows 11 22H2,Windows 11 Upgrade Tips
thumbnail: https://thmb.techidaily.com/95f65ec843e39dc81b80b6ffcbfef45d788958cee2b82fb5803fb90b93482a66.jpg
---

## Boot Old Gear Into Latest Windows 11 22H2

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 1\. Download the Windows 11 22H2 ISO

![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

## 2\. Download a Windows 10 ISO

![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 4\. Go Back to the Previous Version

![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-art-of-effortless-video-size-transformation-on-macos/"><u>[New] 2024 Approved  The Art of Effortless Video Size Transformation on MacOS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-audio-clarity-10-pro-tips-for-high-quality-recordings-for-2024/"><u>[New] Audio Clarity  10 Pro Tips for High-Quality Recordings for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-comprehensible-guide-to-capturing-instagram-media-via-computer-systems/"><u>[New] In 2024, The Comprehensible Guide to Capturing Instagram Media via Computer Systems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-professional-tips-for-high-quality-video-disc-production-on-mac/"><u>[New] Professional Tips for High-Quality Video Disc Production on Mac</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/cutting-edge-accessories-reviewing-the-best-in-vr/"><u>Cutting-Edge Accessories  Reviewing the Best in VR</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-internal-audio-problems-in-audacity-for-windows-1111/"><u>Fixing Internal Audio Problems in Audacity for Windows 11/11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-realme-gt-5-240w-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Realme GT 5 (240W) Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-update-issues-when-the-system-cant-find-them/"><u>How To Fix Windows Update Issues When The System Can't Find Them</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-search-bar-from-the-taskbar-on-windows-11/"><u>How to Hide the Search Bar From the Taskbar on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-lock-apps-on-oneplus-11-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on OnePlus 11 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-time-travelled-command-history/"><u>How to Revert Time-Travelled Command History</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-update-asking-to-update-and-restart/"><u>How to Stop Windows Update Asking to Update and Restart</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-how-to-convert-youtube-to-mp3-without-compromising-security-3-tips/"><u>In 2024, How to Convert YouTube to MP3 Without Compromising Security - 3 Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-integrate-youtube-playlists-into-your-site/"><u>In 2024, How to Integrate YouTube Playlists Into Your Site</u></a></li>
<li><a href="https://windows11.techidaily.com/instantly-access-dark-mode-in-notepad-windows-11-edition/"><u>Instantly Access Dark Mode in Notepad, Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-component-services-accessibility-in-w11/"><u>Mastering Component Services Accessibility in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-error-0x80070570-restoring-broken-files-on-windows-11/"><u>Mastering Error 0X80070570: Restoring Broken Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-uninstall-glitches-on-windows-11/"><u>Mastering the Art of Fixing Uninstall Glitches on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-group-policies-a-threefold-pathway-guide/"><u>Mastering Windows Group Policies: A Threefold Pathway Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-managing-windows-11-tpm-issues/"><u>Mastery in Managing Windows 11 TPM Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-correcting-a-dysfunctional-delete-key/"><u>Methods for Correcting a Dysfunctional Delete Key</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-device-dialogue-syncing-android-and-windows/"><u>Navigating Device Dialogue: Syncing Android & Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-through-new-releases-at-toms-hardware-hub/"><u>Navigating Through New Releases at Tom's Hardware Hub</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-instant-cartoon-effects-for-your-photos-for-2024/"><u>New Instant Cartoon Effects for Your Photos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-content-access-difficulty-on-windows-systems/"><u>Overcoming Steam Content Access Difficulty on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-microsofts-updating-mechanics-for-os/"><u>Peering Into Microsoft's Updating Mechanics for OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/precise-aural-link-the-casters-toolkit/"><u>Precise Aural Link  The Caster's Toolkit</u></a></li>
<li><a href="https://media-tips.techidaily.com/quick-and-simple-mp3-maker-transform-videos-and-audios-into-portable-music-format/"><u>Quick & Simple MP3 Maker: Transform Videos and Audios Into Portable Music Format</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-a-mute-windows-start-button-issue/"><u>Recovering a Mute Windows Start Button Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-device-errors-in-windows-11/"><u>Remedying Device Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rethinking-taskbar-design-top-strategies-to-elevate-windows-11-experience/"><u>Rethinking Taskbar Design: Top Strategies to Elevate Windows 11 Experience</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/seconds-in-a-snapshot-20mb-videography/"><u>Seconds in a Snapshot  20MB Videography</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-windows-11-access-with-pin-solutions/"><u>Smooth Windows 11 Access with PIN Solutions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-connection-issues-repairing-your-vizio-tvs-wi-fi-capabilities/"><u>Solving Connection Issues: Repairing Your Vizio TV's Wi-Fi Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-spotify-links-on-windows-11-pcs/"><u>Streamlining Spotify Links on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-windows-11-keys/"><u>Tackling Non-Functional Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-leaderboard-game-lol/"><u>Unlocking Windows Leaderboard Game (LOL)</u></a></li>
<li><a href="https://windows11.techidaily.com/weekend-wins-lifetime-win10-starting-at-612/"><u>Weekend Wins: Lifetime Win10, Starting at $6.12</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-update-how-to-use-the-widget-toolbar/"><u>Windows 11 Update: How to Use the Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-cost-hardware-recreation-in-windows/"><u>Zero-Cost Hardware Recreation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-to-win-efficiently-handling-app-issues-in-windows-11/"><u>Zero-to-Win: Efficiently Handling App Issues in Windows 11</u></a></li>
</ul></div>
