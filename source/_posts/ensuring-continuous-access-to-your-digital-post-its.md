---
title: Ensuring Continuous Access to Your Digital Post-Its
date: 2024-07-29T04:24:42.901Z
updated: 2024-07-30T04:24:42.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Continuous Access to Your Digital Post-Its
excerpt: This Article Describes Ensuring Continuous Access to Your Digital Post-Its
keywords: Post-It Accessibility,Digital Note Retention,Uninterrupted Notes,Persistent Sticky Memos,Continuous Digital Reminders,Eternal Digital Boards,Endless Sticky Note Access
thumbnail: https://thmb.techidaily.com/8a64098fc8c00724b390ed4672a78681ea9b2ccc0c75a67c21e60baebffadabf.jpg
---

## Ensuring Continuous Access to Your Digital Post-Its

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-top-farm-games-for-social-play-with-peers/"><u>[New] 2024 Approved  Top Farm Games for Social Play with Peers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-achieve-high-quality-recordings-with-these-5-windows-11-tips/"><u>[New] Achieve High-Quality Recordings with These 5 Windows 11 Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-ultimate-guide-to-posting-vids-on-facebook/"><u>[New] In 2024, The Ultimate Guide to Posting Vids on Facebook</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-up-in-the-metaverse-game-with-these-critical-devices-top-7/"><u>[New] Step Up in the Metaverse Game with These Critical Devices (Top 7)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-streamline-your-youtube-experience-creating-custom-subscription-bar-with-filmora/"><u>[Updated] 2024 Approved  Streamline Your YouTube Experience  Creating Custom Subscription Bar with Filmora</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-unplugged-entertainment-essential-free-apps-for-offline-playing/"><u>[Updated] Unplugged Entertainment  Essential Free Apps for Offline Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/15-paths-to-recover-missing-windows-system-time-functionality/"><u>15 Paths to Recover Missing Windows System Time Functionality</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-background-excision-tool-affinity-photo/"><u>2024 Approved  Background Excision Tool Affinity Photo</u></a></li>
<li><a href="https://extra-information.techidaily.com/9-premier-drone-editing-suites-for-varied-expertise/"><u>9 Premier Drone Editing Suites for Varied Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deeper-dive-into-user-experience-revamping-windows-11-widgets/"><u>A Deeper Dive Into User Experience: Revamping Windows 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/access-androids-gaming-joy-on-pc-from-phone-to-window-11-via-google-linkup/"><u>Access Android's Gaming Joy on PC: From Phone to Window 11 via Google Linkup</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-soul-a-guide-to-registry-files-exploration/"><u>Accessing Windows 11’S Soul: A Guide to Registry Files Exploration</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-with-multi-task-proficiency-on-windows-11-pcs/"><u>Achieve Peak Performance with Multi-Task Proficiency on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-dialer-in-microsoft-windows-11/"><u>Activate Dialer in Microsoft Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-game-session-rejection-by-steams-vac/"><u>Avoiding Game Session Rejection by Steam's VAC</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-taskbar-efficiency-win11-guide/"><u>Boosting Taskbar Efficiency: Win11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-file-download-blockades-on-windows-11/"><u>Breaking Through File Download Blockades on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-occupied-files-a-guide-for-windows-11-users/"><u>Clearing Occupied Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-sound-malfunction-fixing-error-code-xc00d36b4/"><u>Combatting Sound Malfunction: Fixing Error Code Xc00d36b4</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-enhancement-for-taskmanager-windows-11/"><u>Command Line Enhancement for TaskManager (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-past-mastering-file-history-navigation/"><u>Command the Past: Mastering File History Navigation</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/comprehensive-guide-to-embedding-youtube-playlists-online/"><u>Comprehensive Guide to Embedding YouTube Playlists Online</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-setting-up-outlook-preview-for-w10w11/"><u>Comprehensive Guide: Setting up Outlook Preview for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-c0000005-on-windows-operating-systems/"><u>Conquering C0000005 on Windows Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-chrome-time-lag-on-windows-devices/"><u>Correcting Chrome Time Lag on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-internal-audio-issues-with-audacity-windows-11/"><u>Correcting Internal Audio Issues with Audacity (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-differences-windows-10-meets-windows-11/"><u>Deciphering the Differences: Windows 10 Meets Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-file-damage-enigma-winning-over-error-0x80070570-on-windows-11/"><u>Deciphering the File Damage Enigma - Winning Over Error 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-ram-allocation-strategies/"><u>Deciphering Windows' RAM Allocation Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-disk-defenders-sync-soundcard-irq-in-windows/"><u>Defeating Disk Defenders: Sync Soundcard IRQ in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-flask-and-socketio-for-windows-file-transfers-via-server/"><u>Deploying Flask and SocketIO for Windows File Transfers via Server</u></a></li>
<li><a href="https://windows11.techidaily.com/differentiating-windows-terminal-from-powershell-a-compreayer-study/"><u>Differentiating Windows Terminal From PowerShell: A Compreayer Study</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dominance-your-must-have-msistore-picks/"><u>Digital Dominance: Your Must-Have MSIStore Picks</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-tips-for-online-photo-cropting/"><u>Essential Tips for Online Photo Cropting</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-reimagine-reality-techniques-for-astonishing-image-distortions/"><u>In 2024, Reimagine Reality  Techniques for Astonishing Image Distortions</u></a></li>
<li><a href="https://windows11.techidaily.com/1719235299454-overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/reimagining-the-role-of-titles-in-after-effects-media-for-2024/"><u>Reimagining the Role of Titles in After Effects Media for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-y200e-5g-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Vivo Y200e 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293003975-winning-over-window-devices-no-more-naming-clashes/"><u>Winning Over Window Devices: No More Naming Clashes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>