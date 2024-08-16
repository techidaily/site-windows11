---
title: "Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files"
date: 2024-08-15T15:46:43.691Z
updated: 2024-08-16T15:46:43.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files"
excerpt: "This Article Describes Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files"
keywords: CAB File Extraction,Windows CAB Usage,Compressing Archives,Cabfile Handling,Unpacking CAB Format,Implementing Archive Files,Windows Data Packaging
thumbnail: https://thmb.techidaily.com/8358f47af5ec8aff78eb055a676b098baa58d37b0eb3993597fb253da585f204.jpg
---

## Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

## What Is a Windows CAB File?

 A CAB file or Cabinet file is a common archive file format used by Microsoft. It contains the compressed version of different files, folders, and even other cabinet files. Microsoft uses these files to distribute Windows, drivers, and UWP app updates. However, you can also use it to store other forms of data, such as images, videos, and documents.

 A CAB file is compressed using the Microsoft Cabinets Compression Format (MCF), which ensures that you can easily decompress it without losing the data stored in it. It can also be signed with digital certificates, allowing to maintain the authenticity and integrity of the file.

 CAB files are recognized by their first four bytes, which are the [ASCII characters](https://www.makeuseof.com/what-is-ascii-text/) MSCF. You can store up to 65,535 folders in a CAB file, with each folder having a storage capacity of 65,535 files.

 Now that you have a brief understanding of CAB files, let's check out how you can install it on Windows 11\.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## How to Install a CAB File on Windows 11

 You can easily install a CAB file on Windows 11 using Command Prompt and Windows PowerShell. In the Command Prompt method, you'll have to use the [DISM command](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/). Whereas, in the PowerShell method, you'll use the Add-WindowsPackage command.

 Here's how to install a CAB file using Command Prompt.

1. Navigate to the CAB file location on your computer.
2. Right-click the CAB file, and choose **Copy as path**.  
![Copy as path option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/copy-as-path-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
3. Press **Win** key to open the **Start Menu**, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
4. In the elevated Command Prompt window, type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`dism /Online /Add-Package /PackagePath:"CAB location"`  
![CMD window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cmd-window.jpg)

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->

 That's it. PowerShell will install the content of the CAB file on your computer.

## How to Install Driver Updates From a CAB File

 If you have downloaded a driver update, which is a CAB file, you can install it using the following instructions:

1. Double-click the CAB file to view its contents.
2. Press **Ctrl + A** to select all the files, right-click, and choose **Extract**.  
![Extract option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/extract-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Choose the location where you want to extract the contents of the CAB file and click **Extract**.
4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **Browse my computer for drivers**.  
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Device Manager will now install the driver update on your computer.

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-decoding-macbook-airs-screen-capture-a-detailed-walkthrough-guide/"><u>[New] 2024 Approved  Decoding MacBook Air's Screen Capture  A Detailed Walkthrough Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-dive-into-makers-earnings-exploring-youtube-shorts-revenue-structure/"><u>[New] 2024 Approved  Dive Into Maker's Earnings  Exploring YouTube Shorts Revenue Structure</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-bypass-issue-twitter-video-on-chrome-freeze-for-2024/"><u>[New] Bypass Issue  Twitter Video on Chrome Freeze for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-essential-tips-for-youtube-thumbnail-design-for-2024/"><u>[New] Essential Tips for YouTube Thumbnail Design for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-erase-unwanted-black-fringes-on-youtube-tracks/"><u>[New] In 2024, Erase Unwanted Black Fringes on YouTube Tracks</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-crafting-a-symphony-of-sights-and-sounds-in-video/"><u>[Updated] Crafting a Symphony of Sights & Sounds in Video</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-guide-on-downloading-processing-and-saving-twitter-vids-as-mp3s/"><u>[Updated] In 2024, Guide on Downloading, Processing, and Saving Twitter Vids as MP3s</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-simplicity-to-spectacle-the-rise-of-hdr-in-video-editing/"><u>2024 Approved  From Simplicity to Spectacle  The Rise of HDR in Video Editing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-lens-tricks-editing-secrets-to-photo-wonders/"><u>2024 Approved  Lens Tricks  Editing Secrets to Photo Wonders</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-livestream-quality-decision-opt-for-streamlabs-or-obs/"><u>2024 Approved  Livestream Quality Decision  Opt for Streamlabs or OBS?</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://win-dash.techidaily.com/acer-predator-xb2nhu-driver-download-made-easy-enhanced-display-performance-guaranteed/"><u>Acer Predator XB2nHU Driver Download Made Easy – Enhanced Display Performance Guaranteed</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-installed-windows-11-on-mac-through-parallels/"><u>Breaking the Barrier: Installed Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-unable-to-retrieve-settings-issue-with-geforce-experience-on-windows-11/"><u>Curing Unable to Retrieve Settings Issue with GeForce Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-steam-performance-preventing-zero-speed-slowdowns/"><u>Elevate Windows Steam Performance: Preventing Zero-Speed Slowdowns</u></a></li>
<li><a href="https://article-helps.techidaily.com/entry-level-lenses-reviewed-the-newcomers-choice-2024/"><u>Entry-Level Lenses Reviewed  The Newcomer's Choice 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722989088797-fix-your-wos-crashes-fast-efficient-hacks-and-tips-for-windowspc-players/"><u>Fix Your WOS Crashes Fast: Efficient Hacks & Tips for Windows/PC Players</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-safety-six-steps-to-entering-safe-mode-in-windows-11/"><u>Get to Safety: Six Steps to Entering Safe Mode in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-create-a-digital-signature-online-for-jpg-document-by-ldigisigner-sign-a-jpg-sign-a-jpg/"><u>How to Create a Digital Signature Online for JPG document</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y100a-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y100A in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-show-more-options-entry-from-the-context-menu-on-windows-11/"><u>How to Remove the Show More Options Entry From the Context Menu on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-oppo-find-x6-pro-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Oppo Find X6 Pro FRP Bypass Instantly</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-online-bunches-of-premium-quality-vector-icons/"><u>In 2024, Best Online Bunches of Premium-Quality Vector Icons</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-samsung-galaxy-s24-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Samsung Galaxy S24 for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-the-internal-error-on-windows-1111-pro/"><u>Methods to Correct the Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-words-silent-mode-fix-for-pc-users/"><u>Microsoft Word's Silent Mode Fix for PC Users</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-audio-fade-infade-out-secrets-unleash-the-power-of-final-cut-pro-for-2024/"><u>New Audio Fade-In/Fade-Out Secrets Unleash the Power of Final Cut Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tricks-to-pinpoint-your-graphic-card-on-windows-11/"><u>Quick Tricks to Pinpoint Your Graphic Card on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-powerful-usage-in-modern-host-computers/"><u>Reducing Powerful Usage in Modern Host Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-windows-search-top-11-remedies-explored/"><u>Reinvigorate Windows Search: Top 11 Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/security-enhancement-manual-add-a-self-designed-lock-pattern/"><u>Security Enhancement Manual: Add a Self-Designed Lock Pattern</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-software-removal-context-menu-optimization-for-win-1011/"><u>Simplifying Software Removal: Context Menu Optimization for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-approach-to-bypass-cant-add-your-folder-now-error-in-windows-onedrive-drive/"><u>Swift Approach to Bypass 'Can't Add Your Folder Now' Error in Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-group-policies-focusing-on-one-user-at-a-time/"><u>Tailoring Group Policies: Focusing on One User at a Time</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-harmony-wirelessly-connect-dualshock-to-pc/"><u>Tech Harmony: Wirelessly Connect DualShock to PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-insiders-secrets-of-screencastify-recording-for-2024/"><u>The Insider’s Secrets of Screencastify Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-windows-11-navshortcuts/"><u>The Ultimate List of Windows 11 NavShortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-overcoming-black-screen-on-store-app/"><u>Tips for Overcoming Black Screen on Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-win-11-desk-aids-boosting-workflow/"><u>Top 7 Win 11 Desk Aids Boosting Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-widget-toolbar-functionality-in-win11/"><u>Understanding the Widget Toolbar Functionality in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-variances-between-exe-and-msi-software-packages/"><u>Unveiling the Variances Between EXE & MSI Software Packages</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-video-resumes-can-be-quite-effective-if-used-in-the-right-context-and-that-is-the-reason-why-weve-decided-to-take-you-through-some-of-the-best-video/"><u>Updated Video Resumes Can Be Quite Effective if Used in the Right Context, and that Is the Reason Why Weve Decided to Take You Through some of the Best Video Resume Makers You Can Use to Get the Job Youve A for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1011-auto-cleanup-a-step-by-step-guide/"><u>Windows 10/11 Auto-Cleanup: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unearthing-absent-settings-in-control-panel/"><u>Windows 11: Unearthing Absent Settings in Control Panel</u></a></li>
</ul></div>
