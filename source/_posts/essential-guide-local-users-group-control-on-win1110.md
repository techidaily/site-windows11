---
title: "Essential Guide: Local Users, Group Control on WIN11/10"
date: 2024-07-11T21:32:49.600Z
updated: 2024-07-12T21:32:49.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Essential Guide: Local Users, Group Control on WIN11/10"
excerpt: "This Article Describes Essential Guide: Local Users, Group Control on WIN11/10"
keywords: Win 10 User Guide,Win 11 User Control,Group Policy Windows,Local Account Management,System Admin Steps,WIN11 Settings Guide,Win10/Win11 Group Privileges
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## Essential Guide: Local Users, Group Control on WIN11/10

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-the-windows-odbc-system/"><u>Getting Acquainted with the Windows ODBC System</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-microsoft-store-programs-on-windows-1011-systems/"><u>Restoring Microsoft Store Programs on Windows 10/11 Systems</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-if-you-are-looking-for-a-free-video-trimmer-to-trim-video-for-free-without-watermark-check-this-article-you-can-definitely-find-the-on/"><u>Updated 2024 Approved If You Are Looking for a Free Video Trimmer to Trim Video for Free without Watermark, Check This Article. You Can Definitely Find the One for Your Need</u></a></li>
<li><a href="https://windows11.techidaily.com/insightful-tips-for-timely-ping-execution-on-windows-pcs/"><u>Insightful Tips for Timely Ping Execution on Windows PCs</u></a></li>
<li><a href="https://fox-info.techidaily.com/cloud-price-wars-best-value-allocation/"><u>Cloud Price Wars  Best Value Allocation</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-graphics-the-key-to-optimal-radeon-performance-in-windows-11/"><u>Streamlined Graphics: The Key to Optimal Radeon Performance in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-android-studio-for-peak-performance-in-windows/"><u>Turbocharge Android Studio for Peak Performance in Windows</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-rog-phone-7-ultimate-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-spark-20-pro-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Spark 20 Pro.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-alleviate-windows-1011s-devastating-discord-js-failure/"><u>How to Alleviate Windows 10/11'S Devastating Discord JS Failure</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-best-free-video-trimming-software-online-top-10-picks-for-2024/"><u>Updated Best Free Video Trimming Software Online Top 10 Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-windows-diagnostics-powerhouses/"><u>Top 10 Windows Diagnostics Powerhouses</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-lessons-learned-from-top-notch-ogg-converters-for-2024/"><u>New Lessons Learned From Top-Notch OGG Converters for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/how-to-download-part-of-a-youtube-videos/"><u>How to Download Part of a YouTube Videos?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/raspberry-router-image-maker/"><u>Raspberry Router  Image Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x8024a205-in-winupdate/"><u>Troubleshooting Error 0X8024a205 in WinUpdate</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-methods-for-verifying-windows-11-installation/"><u>The Essential Methods for Verifying Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-protect-enabling-powershell-script-policy/"><u>Optimize & Protect: Enabling PowerShell Script Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-using-wireless-and-cable-in-harmony-on-windows/"><u>The Ultimate Guide: Using Wireless and Cable in Harmony on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-your-apathetic-windows-start-button-click/"><u>Rejuvenating Your Apathetic Windows Start Button Click</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-giggles-galore-the-quintessential-comedic-stars-on-tiktok/"><u>[New] Giggles Galore  The Quintessential Comedic Stars on TikTok</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-youtube-short-video-insights/"><u>2024 Approved  The Ultimate Guide to YouTube Short Video Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/the-undetectable-file-hiding-technique-on-windows-systems/"><u>The Undetectable File Hiding Technique on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-x0001-in-nvidias-windows-11-app/"><u>Troubleshooting Error X0001 in Nvidia's Windows 11 App</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-key-windows-programs-for-taskmasters/"><u>Optimizing Workflow: Key Windows Programs for Taskmasters</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-computers-potential-a-wintoy-guidebook/"><u>Master Your Computer's Potential: A Wintoy Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-reset-of-windows-icon-positions/"><u>Swift Reset of Windows Icon Positions</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeo-mastery-in-motion-building-high-impact-gifs/"><u>In 2024, Vimeo Mastery in Motion  Building High-Impact GIFs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/silence-the-microphone-a-complete-blueprint-to-remove-vocals-from-tracks-in-adobe-audition/"><u>Silence the Microphone A Complete Blueprint to Remove Vocals From Tracks in Adobe Audition</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missing-msvcr110dll-in-windows-environment/"><u>Overcoming Missing msvcr110.dll in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-connectivity-unlocking-windows-remote-desktop/"><u>Leap Into Connectivity: Unlocking Windows Remote Desktop</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-mastering-the-art-of-sound-on-windows-top-8-daw-selections-with-a-balance-of-costs/"><u>Updated Mastering the Art of Sound on Windows Top 8 DAW Selections with a Balance of Costs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-step-by-step-adding-captions-to-youtube-clips/"><u>[Updated] Step-by-Step  Adding Captions to YouTube Clips</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-airborne-broadcasting-how-to-stream-with-dji-drones/"><u>[New] Airborne Broadcasting  How to Stream with DJI Drones</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-samsung-galaxy-f34-5g-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Samsung Galaxy F34 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-install-net-core-now-on-pc/"><u>How to Counteract Install .NET Core Now on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-compromised-windows-defender-in-windows-11/"><u>Resolve Compromised Windows Defender in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-artedit-master/"><u>[Updated] ArtEdit Master</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-windows-screensaver-status-intact-from-user-changes/"><u>Keeping Windows Screensaver Status Intact From User Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-pc-gamepad-adjustments-and-accuracy-checks/"><u>Mastering PC Gamepad Adjustments & Accuracy Checks</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unlock-gif-potential-creating-animated-summaries-of-vimeo-videos-for-2024/"><u>[Updated] Unlock GIF Potential  Creating Animated Summaries of Vimeo Videos for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/how-can-you-choose-the-best-sound-editor/"><u>How Can You Choose the Best Sound Editor?</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-wsl-error-code-4294967295-in-windows/"><u>Steps to Correct WSL Error Code 4294967295 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-in-use-issue-on-windows-11/"><u>Overcoming Printer In Use Issue on Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1715859573863-2024-approved-premium-12-video-capture-apps-no-time-limit/"><u>2024 Approved  Premium 12 Video Capture Apps, No Time Limit!</u></a></li>
<li><a href="https://windows11.techidaily.com/protect-your-passwords-in-windows-files-easily/"><u>Protect Your Passwords in Windows Files Easily</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-helpful-advice-mastering-the-use-of-voxal-sound-changer-for-improved-discord-interaction-for-2024/"><u>New Helpful Advice Mastering the Use of Voxal Sound Changer for Improved Discord Interaction for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-micro-video-service-meets-your-individual-needs-better-for-2024/"><u>Which Micro-Video Service Meets Your Individual Needs Better for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-non-active-thermal-management-on-pcs/"><u>Reviving Non-Active Thermal Management on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tapping-into-your-true-essence-guide-for-accessing-windows-silent-personal-analyzer/"><u>Tapping Into Your True Essence: Guide for Accessing Windows' Silent Personal Analyzer</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-photography-tools-that-will-dazzle-you/"><u>2024 Approved  Free Photography Tools That Will Dazzle You</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-text-to-art-obsidian-canvas-techniques/"><u>Transforming Text to Art: Obsidian Canvas Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-frozen-netflix-on-windows/"><u>Troubleshooting Frozen Netflix on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-microsoft-store-hiccup-0x80131500/"><u>Remedying Microsoft Store Hiccup 0X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-game-recommendations-on-w11/"><u>Guide to Silencing Game Recommendations on W11</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-elite-ddr5-memory-modules/"><u>2024'S Elite DDR5 Memory Modules</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-premier-livestream-networks/"><u>2024 Approved  Unveiling the Premier Livestream Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-wsl-2-for-efficient-docker-workflows/"><u>Optimizing WSL 2 for Efficient Docker Workflows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Realme Narzo N55? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-drive-enable-file-cleanup-in-win11-operating-system/"><u>Optimize Your Drive: Enable File Cleanup in Win11 Operating System</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/quick-guide-filming-with-macs-webcam-5-straightforward-techniques/"><u>Quick Guide  Filming with Mac's Webcam - 5 Straightforward Techniques</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-premier-list-of-the-most-reliable-song-recorders-on-the-market/"><u>Updated In 2024, Premier List of the Most Reliable Song Recorders on the Market</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-link-sounds-to-visual-elements-in-ppt/"><u>2024 Approved  Link Sounds to Visual Elements in PPT</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-chkdsk-vs-scan-disk-dissecting-windows-tools/"><u>Understanding Chkdsk Vs. Scan Disk: Dissecting Windows Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-stream-perfecting-tweets-with-correct-video-formats-for-2024/"><u>[New] Stream-Perfecting Tweets with Correct Video Formats for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-paving-digital-pathways-for-ig-and-tiktok/"><u>2024 Approved  Paving Digital Pathways for IG & TikTok</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-edit-videos-like-a-pro-on-mac-with-mkvtoolnix/"><u>2024 Approved Edit Videos Like a Pro on Mac with MKVtoolnix</u></a></li>
</ul></div>
