---
title: "Windows Health Check-Up: Top 13 Restoration Techniques"
date: 2024-07-11T21:32:32.092Z
updated: 2024-07-12T21:32:32.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Health Check-Up: Top 13 Restoration Techniques"
excerpt: "This Article Describes Windows Health Check-Up: Top 13 Restoration Techniques"
keywords: Windows Health Checkup,Window Maintenance Tips,System Recovery Methods,PC Repair Strategies,Optimize System Performance,Windows Restore Procedures,Digital Wellness Audit
thumbnail: https://thmb.techidaily.com/f84b2c3b2f643243e9c367a28e725ddd1d16800a678efc068af4239160ee06bb.jpg
---

## Windows Health Check-Up: Top 13 Restoration Techniques

 System Restore is one of the most useful Windows features, as it allows you to revert your computer to an earlier state, in case something goes wrong. This can be a lifesaver as long as it works.

 There’s a chance you will figure out that System Restore stopped working only when you need it, which can add an extra layer of frustration to your existing issues. Many different factors can affect its performance, but these pointers should help you get to the root of the problem.

## 1\. Create a System Restore Point Manually

 Your first port of call during System Restore irregularities should be to manually create a System Restore point. While this is unlikely to solve the problem outright, you may well be presented with an error message that makes it easier to diagnose what's wrong.

![Create restore point manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-restore-point-manually-1.jpg)

 To get started, type **Restore Point** into your search bar and click on the result titled **Create a restore point**. Click the button labelled **Create** and choose a name, then wait for the process to complete and see if an error message pops up.

## 2\. Check System Restore is Active on All Volumes

 System Restore may simply not be activated on your computer. This is particularly relevant if you're using more than one drive, or have recently swapped your system storage from one volume to another, as drives can have their protection turned on and off individually.

![Check system restore status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-restore-status-1.jpg)

 Type **Restore Point** into the search bar and click on **Create a Restore Point**. You'll see the Available Drives listed under the Protection Settings subheading, alongside a column telling you whether or not they're protected.

 To change this setting, click on the desired drive to highlight it and then click on **Configure**. A radio toggle will allow you to turn System Restore protection on or off.

 As with almost any other technical issue, turning System Restore off and on again is well worth a try.

## 3\. Disable Antivirus Software

 Using a [reliable piece of antivirus software](https://www.makeuseof.com/windows-11-antivirus-apps/) is a great way to keep your system protected against malware and other undesirable installs, but sometimes this kind of utility can cause problems for other tasks.

 If you're facing difficulties with System Restore, briefly disable your antivirus software early on during your troubleshooting — it may well fix things.

## 4\. Check Your Disk Space Allocation

 Your Restore Points will fail if there isn't enough space allocated for their storage. To see how much space you have assigned to this task, enter **Restore Point** into the search bar and open the entry titled **Create a restore point**.

![Check System Restore disk allocation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restore-disk-allocation-1.jpg)

 Click the Configure button and you'll be able to tweak your **Disk Space Usage**. Try using the slider to increase your allocated space, then create a new Restore Point to see whether it has had the desired effect.

## 5\. Manually Delete Restore Points

 As we’ve mentioned, System Restore will fail to create a new restore point if there’s no available storage space on your computer. However, you can [manually delete older restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) that you no longer need to free up some space for System Restore to work.

## 6\. Confirm Essential Services are Running

 System Restore relies on a few different services to do its job; without them, it can't function. Fortunately, it's very easy to check whether or not they are active by typing **Services** into the search bar and opening the app.

 You'll be presented with a long list of all the services that are loaded onto your computer, but you're just looking for three:

* Microsoft Software Shadow Copy Provider Service
* Task Scheduler
* Volume Shadow Copy

 Make sure the **Name** column is sorted alphabetically, then skim through the list to find these three services. You need to confirm that all of them are **Running** and are set to **Automatic** in the **Startup Type** column.

![Check System Restore services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-restore-services-1.jpg)

## 7\. Run Check Disk via Command Prompt

 Check Disk is a system tool built into Windows that can verify the integrity of a file system, and fix logical errors. To access the utility, in the Start menu search bar, search for **command prompt** and select **Run as administrator**.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1.jpg)

 To run Check Disk, input the following command:

chkdsk /f /r

 You might also want to try the similar System File Checker tool with this command:

sfc /scannow

## 8\. Boot Into Safe Mode

 Problems affecting System Restore can often be traced back to services and drivers from a source other than Microsoft. Safe Mode strips your computer's abilities back to the bare essentials, meaning that those processes won't interfere with your procedure.

 You'll still have to find the culprit if you want to fix the issue permanently, but dropping into Safe Mode can be a useful stopgap if you're in a bind.

![Boot your computer in Safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/safe-mode-1.jpg)

 To boot into Safe Mode, type **msconfig** into the search bar and open **System Configuration**. Head to the **Boot** tab and tick the checkbox marked **Safe boot**, with the radio toggle set to **Minimal**. Then try running System Restore from Safe Mode.

 If this didn't work for you, there are [other methods to boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

## 9\. Try Selective Startup

 Selective Startup is a similar tool to Safe Mode, in that it reduces the amount of processes running on your computer to make it easier to diagnose problems. Type **System Configuration** into the search box and open the top result to get started.

![Use selective startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/selective-startup-1.jpg)

 You can check and uncheck the **Load system services** and **Load startup items** boxes to customize how your computer behaves at startup. For more information on using Selective Startup to troubleshoot, refer to Microsoft's guide to the process.

## 10\. Consult the Event Viewer

 You might be able to find some clues about errors pertaining to System Restore processes by delving into the Event Viewer. Search for the utility and open it up to get started — you'll need to expand the **Windows Logs** folder, then click on **Applications**.

![Check Windows event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/event-viewer-1.jpg)

 Scroll through the results to find anything with **Error** in the **Level** column. Click on an individual event to display its description, and see if that offers up any reason that it might be connected to System Restore. You can do a Google search for any related errors that you find to see what the best course of action is.

## 11\. Check Your Timing

 As simple as it might sound, your System Restore strife might be caused by something as straightforward as your computer being asleep when it's scheduled to create a new image. Your PC won't be able to wake itself up to do the job, unless you have a handy tool called [Restore Point Creator](http://www.downloadcrew.com/article/31634-restore%5Fpoint%5Fcreator).

![Restore Point Creator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restore-point-creator-1.jpg)

 Among a host of other advantages, Restore Point Creator offers users the opportunity to schedule the task for the future, and instruct their system to wake up at that specified time. This option is available by navigating to **System Restore Point Utilities** \> **Schedule creation of System Restore Points** and then checking the box labelled **Wake computer if the system is sleeping**.

 One point to remember is that Restore Point Creator uses Task Scheduler to implement this feature. As such, you'll have to check that your computer is compatible with the tool.

## 12\. Employ a Third-Party Alternative

 If you really can't fix System Restore, you could always try a different solution. This won't help anyone in the midst of a crisis right now, but for those readers that are just setting up their defenses, a backup plan could pay dividends down the line.

 You might also check out these [rescue and restore disks for your Windows System Restore](https://www.makeuseof.com/tag/5-best-rescue-disks-windows-system-restore/).

## 13\. Factory Reset Your Computer

 If none of the above solutions fixed System Restore, and you’re stuck with a system full of bugs and glitches, you should factory reset your computer. This is a bold move, as it will return your PC to the state it was when you bought it.

 Before doing so, make sure to [back up any personal data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) you might need, so long as you’re able to.

## Fixing Windows System Restore

 There are plenty of reasons why System Restore might stop working, so it might be challenging to pin down the exact cause. However, with a bit of patience, the above tips will help you fix the issue so you can load a restore point any time you need it.

 If you want to create restore points faster, you can add the option to the Windows context menu.


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
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-leverage-slug-lines-in-articles/"><u>In 2024, How to Leverage Slug Lines in Articles</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://games-able.techidaily.com/a-compreayer-look-at-top-rated-elgato-decks/"><u>A Compreayer Look at Top-Rated Elgato Decks</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Honor Play 40C? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-ae-excellence-select-best-templates-for-free-access/"><u>2024 Approved  AE Excellence  Select Best Templates for Free Access</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-step-by-step-adding-a-flurry-of-images-and-videos-to-your-ig-story-for-2024/"><u>[New] Step-by-Step  Adding a Flurry of Images & Videos to Your IG Story for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-insufficient-spec-on-game-captures/"><u>Troubleshooting Insufficient Spec on Game Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-discover-the-best-anime-vids-on-youtube-list/"><u>2024 Approved  Discover the Best Anime Vids on YouTube (List)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-new-frontier-of-video-conversations-a-2023-guide-to-non-omegle-chat-websites/"><u>Updated 2024 Approved The New Frontier of Video Conversations A 2023 Guide to Non-Omegle Chat Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-full-breakdown-razers-hd-webcam-experience-for-2024/"><u>[New] Full Breakdown  Razer's HD Webcam Experience for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-get-your-vhs-fix-on-the-go-top-mobile-apps-for-retro-video-enthusiasts-for-2024/"><u>Updated Get Your VHS Fix on the Go Top Mobile Apps for Retro Video Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0xa00f4243-overlapping-camera-usage-in-apps/"><u>Troubleshooting 0xA00F4243: Overlapping Camera Usage in Apps</u></a></li>
<li><a href="https://some-tips.techidaily.com/unifying-online-collaboration-tools-skype-and-zoom-for-2024/"><u>Unifying Online Collaboration Tools  Skype & Zoom for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-above-and-beyond-selecting-premium-software-for-drone-filmmaking/"><u>2024 Approved  Above & Beyond  Selecting Premium Software for Drone Filmmaking</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/unleashing-creativity-the-ultimate-guide-to-crafting-compelling-tiktok-captions/"><u>Unleashing Creativity  The Ultimate Guide to Crafting Compelling TikTok Captions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/premier-collection-top-10-audio-capturers-on-spotify/"><u>Premier Collection  Top 10 Audio Capturers on Spotify</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harmonizing-hues-audio-fade-techniques-in-logic-pro/"><u>[Updated] Harmonizing Hues  Audio Fade Techniques in Logic Pro</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-huawei-nova-y71-by-drfone-android/"><u>In 2024, How to Bypass FRP from Huawei Nova Y71?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-the-best-free-video-editors-for-chromebook-users/"><u>In 2024, The Best Free Video Editors for Chromebook Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/fy-your-content-best-practices-in-collaborative-youtube-outros/"><u>Amplify Your Content  Best Practices in Collaborative YouTube Outros</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/best-budget-friendly-android-chat-services-for-2024/"><u>Best Budget-Friendly Android Chat Services for 2024</u></a></li>
</ul></div>
