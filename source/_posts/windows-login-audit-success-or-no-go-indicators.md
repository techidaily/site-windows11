---
title: "Windows Login Audit: Success or No-Go Indicators"
date: 2024-07-11T22:01:01.665Z
updated: 2024-07-12T22:01:01.665Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Login Audit: Success or No-Go Indicators"
excerpt: "This Article Describes Windows Login Audit: Success or No-Go Indicators"
keywords: Windows Audit Login,Success Login Metrics,Failed Login Alerts,Security Login Review,Audit Login Failures,Login System Analysis,Indicator Check Login
thumbnail: https://thmb.techidaily.com/6190a0016cd0db6cebefe5acaadd207d01333c2584c8d35c887e62fae8bb62c7.jpg
---

## Windows Login Audit: Success or No-Go Indicators

 Windows lets you create multiple user accounts to let multiple users use a single computer. But what if you suspect someone to have accessed your PC or user account without your knowledge?

 While physically monitoring your computer all the time is not feasible for most people, the built-in Windows log utility, Event Viewer, can reveal the recent activities on your computer, including login attempts. Here we show you how to audit failed and successful login attempts in Windows using Event Viewer and other methods.

## How to Enable Logon Auditing via Group Policy Editor

 You need to enable logon auditing in Group Policy Editor to be able to view login audit in Event Viewer. While this feature may be enabled by default on some computers, you can also enable logon auditing manually by following these steps.

 Note that Group Policy Editor is only available on the Pro, Edu, and Enterprise edition of the Windows OS. If you are on the Home edition, follow our guide to [enable gpedit in the Windows home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Note that if you don't configure your Group Policy for Logon Auditing, you can only view the successful login attempts in Event Viewer.

 Once you have the Group Policy Editor enabled, follow these steps to enable logon auditing:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open the**Group Policy Editor.**
3. Next, navigate to the following location:  
`Computer Configuration > Windows Settings > Security Settings > Local Policies > Audit Policy`
4. In the right pane, right-click on**Audit logon events** and select**Properties** .  
![group policy editor audit logon events properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties.jpg)
5. In the**Properties** dialog, select**Success** and**Failure** options under the**Audit these attempts** section.  
![group policy editor audit logon events properties enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties-enable.jpg)
6. Click**Apply** and**OK** to save the changes.

 Close Group Policy Editor and move to the next set of steps to view login attempts in Event Viewer.

## How to View Failed and Successful Login Attempts in Event Viewer

 The [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

 Follow these steps to view failed and successful login attempts in Windows:

1. Press the**Win key** and type**event viewer.** Alternatively, click on**Search** in the taskbar and type**event viewer.**
2. Click on**Event Viewer** from the search result to open it.
3. In the left pane, expand the**Windows Logs** section.  
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

 Similarly, for failed login attempts, review**Event ID 4625** . In the**Properties** dialog, you can find reasons for the failed login attempt and the affected user account. If you find multiple instances of unsuccessful attempts, consider learning [how to limit the number of failed login attempts to protect your Windows PC](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) .

 Below is the list of all nine**Logon Types** for logon events that you may encounter reviewing login events in Event Viewer:

| **Logon Type** | **Description**                                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Logon Type 2   | A local user logged on to this computer.                                                                                                          |
| Logon Type 3   | A user logged on to this computer from the network.                                                                                               |
| Logon Type 4   | Batch logon type without user intervention – Scheduled Tasks, etc.                                                                                |
| Logon Type 5   | Logon by system service started by Service Control Manager – Most common type                                                                     |
| Logon Type 7   | System unlocked by a local account user                                                                                                           |
| Logon Type 8   | NetworkClearText - Logon attempted over the network where the password was sent as clear text.                                                    |
| Logon Type 9   | NewCredentials – triggered when a user uses the RunAs command with the /netonly option to start a program.                                        |
| Logon Type 10  | RemoteInteractive – Generated when a computer is accessed via a remote access tool such as Remote Desktop Connection.                             |
| Logon Type 11  | CachedInteractive – When the user logged on to the computer via console using the cached credentials when the domain controller is not available. |

## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

## Viewing Failed and Successful Login Attempts in Windows

 If you suspect someone to have logged in to your PC, the Event Viewer will likely catch and record the attempt. For this to work, you must enable the Logon Auditing policy in Group Policy Editor. You can also use Command Prompt to view a specific user's login history.

 That said, anyone who knows their way around Event Viewer can easily clear the logs. So, if anything, beefing up your Windows computer security is the best way to prevent unauthorized access. You can begin by limiting the number of failed login attempts on your Windows PC.

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
<li><a href="https://windows11.techidaily.com/beneath-radar-outstanding-windows-11-customization/"><u>Beneath Radar: Outstanding Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-yuletide-atmosphere-in-window-artistry/"><u>Captivating Yuletide Atmosphere in Window Artistry</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-win-11-games-with-these-best-fps-tools/"><u>Ace Your Win 11 Games with These Best FPS Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-processing-excellence-using-task-scheduler/"><u>Batch Processing Excellence Using Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-tray-ui-add-scrolllock-and-number-keys-iconos/"><u>Amplify Tray UI: Add ScrollLock and Number Keys Iconos</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-memory-limitations-strategies-for-windows/"><u>Avoidance of Memory Limitations: Strategies for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/apexs-windows-woes-strategies-to-clear-no-server-error-(156-chars/"><u>Apex's Windows Woes: Strategies to Clear No-Server Error (<156 Chars)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-essential-open-video-players-across-operating-systems/"><u>2024 Approved  Essential Open Video Players Across Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-your-win-software-downloader-choco-versus-wslm/"><u>Choosing Your Win Software Downloader: Choco Versus WSLM</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-boost-interaction-on-your-tiktok-with-these-5-innovative-caption-methods/"><u>[Updated] 2024 Approved  Boost Interaction on Your TikTok with These 5 Innovative Caption Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-iphone-se-2020-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled iPhone SE (2020) Without iTunes in 5 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/applying-luts-for-cinematic-color-grades-for-2024/"><u>Applying Luts for Cinematic Color Grades for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-best-ispoofer-alternative-to-try-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-fps-supercharge-yuzu-for-windows/"><u>Boosting FPS: Supercharge Yuzu for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/blending-digital-worlds-androidpc-connections-made-simple/"><u>Blending Digital Worlds: Android/PC Connections Made Simple</u></a></li>
<li><a href="https://youtube-help.techidaily.com/expert-endorsed-asmr-microphones-unveiled-for-2024/"><u>Expert-Endorsed ASMR Microphones Unveiled for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-adjustments-for-a-mac-look-in-windows-environment/"><u>5 Key Adjustments for a Mac Look in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/1719351366052-breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips!</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-free-and-easy-techniques-to-cut-out-loud-elements-from-windows-10-videos-for-2024/"><u>New Free and Easy Techniques to Cut Out Loud Elements From Windows 10 Videos for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-resolving-disabled-state-of-obs-fullscreen-for-2024/"><u>[Updated] Resolving Disabled State of OBS Fullscreen for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/best-budget-single-board-windows-systems/"><u>Best Budget Single-Board Windows Systems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-viral-vibrancy-trending-audio-amplifying-your-yt-shorts/"><u>2024 Approved  Viral Vibrancy  Trending Audio Amplifying Your YT Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-prowess-on-windows-a-comprehensible-drivers-upgrade-blueprint/"><u>Audio Prowess on Windows: A Comprehensible Drivers' Upgrade Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/a-history-of-the-windows-taskbar-from-1985-to-2023/"><u>A History of the Windows Taskbar From 1985 to 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/1719366391353-keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-comprehensive-checklist-for-launching-engaging-online-events/"><u>In 2024, The Comprehensive Checklist for Launching Engaging Online Events</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-system-call-failures-quickly/"><u>Addressing Windows 11 System Call Failures Quickly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-isolate-frames-as-photos-in-windows-11/"><u>[New] How to Isolate Frames as Photos in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-strategies-to-enhance-testimonial-credibility-and-impact/"><u>[New] Strategies to Enhance Testimonial Credibility and Impact</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-start-your-vlog-and-make-money-from-it-for-2024/"><u>How to Start Your Vlog and Make Money From It for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-beyond-the-dance-understanding-copyright-pre-upload/"><u>[New] Beyond the Dance  Understanding Copyright Pre-Upload</u></a></li>
<li><a href="https://howto.techidaily.com/reliable-user-guide-to-fix-realme-11-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Realme 11 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-essentials-of-sharing-music-compilations-online-for-2024/"><u>The Essentials of Sharing Music Compilations Online for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-sluggishness-of-windows-discord-features/"><u>Addressing the Sluggishness of Windows Discord Features</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-crafting-connections-posting-vids-between-tweets-and-tumbles/"><u>In 2024, Crafting Connections  Posting Vids Between Tweets & Tumbles</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-folder-permission-snags-swiftly/"><u>Bypass Windows Folder Permission Snags Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unbeatable-bargain-video-content-websites/"><u>2024 Approved  Unbeatable Bargain Video Content Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limited-it-admin-power-in-security-warning/"><u>Bypassing 'Limited IT Admin Power' In Security Warning</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-art-of-documenting-xbox-playtime-online/"><u>[Updated] In 2024, The Art of Documenting Xbox Playtime Online</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-oppo-a38-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-default-user-directory-labels-windows-11/"><u>Changing Default User Directory Labels (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-of-docker-in-wsl-2-on-windows-devices/"><u>Boosting Performance of Docker in WSL 2 on Windows Devices</u></a></li>
</ul></div>
