---
title: Techniques to Disconnect Untrusted Users From Windows 11
date: 2024-08-15T15:34:35.552Z
updated: 2024-08-16T15:34:35.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Disconnect Untrusted Users From Windows 11
excerpt: This Article Describes Techniques to Disconnect Untrusted Users From Windows 11
keywords: Win11 Security Block,Halt Rogue Access,Disconnect Unregistered Users,Prevent Unknown Login,Secure User Exits,Wipe Offshore Logins,Windows 11 UX Lockout
thumbnail: https://thmb.techidaily.com/7fc466e5e2b7732daf41c9b5f420c5c5add88815dae1954866b21ab967027c21.jpg
---

## Techniques to Disconnect Untrusted Users From Windows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-narrative-nooks-the-leading-10-rogues/"><u>[New] 2024 Approved  Narrative Nooks  The Leading 10 Rogues</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-standout-thumbnails-start-here-20-top-font-picks/"><u>[New] 2024 Approved  Standout Thumbnails Start Here  20 Top Font Picks</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/heap-yet-good-quality-cameras-reviewed-here/"><u>[New] Cheap Yet Good Quality Cameras Reviewed Here</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-magix-vpxs-innovative-editing-capabilities/"><u>[New] Exploring Magix VPX's Innovative Editing Capabilities</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-expert-techniques-for-high-quality-android-recordings/"><u>[New] In 2024, Expert Techniques for High-Quality Android Recordings</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tech-insight-pulling-and-keeping-twitters-vids-in-phone/"><u>[New] Tech Insight  Pulling and Keeping Twitters Vids in Phone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-captivatescreen-scrutiny-platform/"><u>[Updated] CaptivateScreen Scrutiny Platform</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-crafting-visual-magic-the-essentials-of-snapchat-photo-editing/"><u>[Updated] Crafting Visual Magic  The Essentials of Snapchat Photo Editing</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-finalized-choices-best-10-video-editing-tools-for-reels/"><u>[Updated] Finalized Choices  Best 10 Video Editing Tools for Reels</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-capturing-moments-like-never-before-toolwiz-apps-2023-review/"><u>[Updated] In 2024, Capturing Moments Like Never Before  Toolwiz App's 2023 Review</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-unlocking-the-secrets-of-irecorder-for-2024/"><u>[Updated] Unlocking the Secrets of iRecorder for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/access-all-instagram-video-content-with-free-online-and-os-compatible-exporters/"><u>Access All Instagram Video Content with Free Online and OS-Compatible Exporters</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-google-pixel-8-pro-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Google Pixel 8 Pro Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-of-windows-11s-enhancements-february-update-speaks/"><u>Breakdown of Windows 11'S Enhancements – February Update Speaks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/capturezone-win-10s-best-recorder-for-2024/"><u>CaptureZone  Win 10'S Best Recorder for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/enabledarkinterfacefornotepad/"><u>EnableDarkInterfaceForNotepad</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-activating-windows-11s-system-restore-feature/"><u>Essential Steps for Activating Windows 11'S System Restore Feature</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-advice-on-acquiring-the-latest-360-cameras/"><u>Expert Advice on Acquiring the Latest 360 Cameras</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-samsung-nvme960-evo-driver-a-comprehensive-guide-for-windows-users/"><u>Find and Install Samsung Nvme960 EVO Driver - A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fine-tuning-the-art-of-recording-in-audacity/"><u>Fine-Tuning the Art of Recording in Audacity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-lgs-27uhd68-enhances-gaming-experience-for-2024/"><u>How LG's 27UHD68 Enhances Gaming Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-windows-software-initiation-failures/"><u>How to Overcome Windows Software Initiation Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-unreal-device-issue-in-win-11/"><u>How to Resolve Unreal Device Issue in Win 11</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-samsung-galaxy-a15-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Samsung Galaxy A15 5G phone? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-12-proipad-without-computer-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone 12 Pro/iPad Without Computer</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Realme C53? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-lava-yuva-2-pro-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Lava Yuva 2 Pro to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-on-apple-iphone-12-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud on Apple iPhone 12 Safe and Legal</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-efficient-edits-encapsulating-powerpoint-talks/"><u>In 2024, Efficient Edits  Encapsulating PowerPoint Talks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-how-to-insert-youtube-links-for-an-engaging-ppt-experience/"><u>In 2024, How to Insert YouTube Links for an Engaging PPT Experience</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-transformation-tips-applying-japans-favorite-on-screen-effects/"><u>In 2024, Transformation Tips  Applying Japan's Favorite On-Screen Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-shutdown-on-windows-11-for-idleness/"><u>Mastering Auto-Shutdown on Windows 11 for Idleness</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-connection-stability-fixed-windows-lol-issues/"><u>Mastering Connection Stability: Fixed Windows LoL Issues</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-art-of-crafting-compelling-video-testimonials-for-2024/"><u>Mastering the Art of Crafting Compelling Video Testimonials for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-directx-setup-failures-on-pc/"><u>Mending DirectX Setup Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-labyrinth-of-updater-0x800f080a-on-windows/"><u>Navigating Through the Labyrinth of Updater 0X800F080A on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-credentials-error-loop/"><u>Overcoming Windows Credentials Error Loop</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-4-ways-to-stop-pc-update-notifications/"><u>Quick Fixes: 4 Ways to Stop PC Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-thx-not-working-in-windows-setup/"><u>Rectifying THX Not Working in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-directx-download-problems-in-os/"><u>Remedying DirectX Download Problems in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-how-you-use-the-mouse-worldwide-through-powertoys/"><u>Revolutionize How You Use the Mouse Worldwide Through PowerToys</u></a></li>
<li><a href="https://fox-that.techidaily.com/simplify-your-digital-album-merging-duplicate-images-across-all-your-apple-devices/"><u>Simplify Your Digital Album: Merging Duplicate Images Across All Your Apple Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/snap-opera-download-into-action-windows-style/"><u>Snap Opera Download Into Action, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-docx-to-pdf-migration-for-windows-users/"><u>Step-by-Step DOCX to PDF Migration for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-github-desktop-on-windows-11-os/"><u>The Ultimate Guide to GitHub Desktop on Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-word-docs-seamlessly-into-pdfs-using-windows-11/"><u>Transform Your Word Docs Seamlessly Into PDFs Using Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-your-windowed-discord-interface-in-windows/"><u>Unblocking Your Windowed Discord Interface in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-auto-start-understanding-your-windows-10-pcs-self-booting-issue/"><u>Unexpected Auto-Start: Understanding Your Windows 10 PC's Self-Booting Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-history-for-lately-used-pages/"><u>Unlocking Windows History for Lately Used Pages</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/wi-fi-expectations-trashed-nikon-coolpix-b500-flop/"><u>Wi-Fi Expectations Trashed: Nikon COOLPIX B500 Flop</u></a></li>
<li><a href="https://windows11.techidaily.com/win-1011-printer-uninstallation-a-quick-and-direct-guide/"><u>Win 10/11 Printer Uninstallation: A Quick & Direct Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-overview-understanding-arp-caches/"><u>Windows Network Overview: Understanding ARP Caches</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-reimagined-analyzing-the-core-upgrades-of-windows-11/"><u>Windows Reimagined: Analyzing the Core Upgrades of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-efficiently-eliminate-partitioned-areas-on-your-pc/"><u>Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC</u></a></li>
</ul></div>
