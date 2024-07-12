---
title: "Windows 11 User Mastery: Group & Admin Essentials Guide"
date: 2024-07-11T21:53:42.230Z
updated: 2024-07-12T21:53:42.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 User Mastery: Group & Admin Essentials Guide"
excerpt: "This Article Describes Windows 11 User Mastery: Group & Admin Essentials Guide"
keywords: Windows 11 Pro Guide,Admin Controls W11,User Privilege Basics,System Access Management,Mastering W11 Security,W11 Group Policy Tips,Advanced W11 Admin Tools
thumbnail: https://thmb.techidaily.com/37c258031093435d71dd94d5151455426579049284afd82c0786b6e3dd815a4b.jpg
---

## Windows 11 User Mastery: Group & Admin Essentials Guide

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
<li><a href="https://youtube-sure.techidaily.com/sive-list-best-online-video-to-mp3-tools/"><u>Exclusive List  Best Online Video to Mp3 Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-a-guide-to-top-screen-capture-for-zoom/"><u>[Updated] 2024 Approved  A Guide to Top Screen Capture for Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/1719265109241-master-google-chromes-filesync-on-your-windows-device-now/"><u>Master Google Chrome's Filesync on Your Windows Device Now</u></a></li>
<li><a href="https://windows11.techidaily.com/12-top-changes-to-expect-with-windows-11s-latest-release/"><u>12 Top Changes to Expect with Windows 11'S Latest Release</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-optimizing-social-media-for-vimeo-sharing-for-2024/"><u>[Updated] Optimizing Social Media for Vimeo Sharing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719208597283-unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand</u></a></li>
<li><a href="https://windows11.techidaily.com/15-paths-to-recover-missing-windows-system-time-functionality/"><u>15 Paths to Recover Missing Windows System Time Functionality</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/1716089176641-2024-approved-how-to-watch-facebook-live-on-roku/"><u>2024 Approved  How to Watch Facebook Live on Roku</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-the-ins-and-outs-of-converting-mp3-files-to-mp4-a-beginners-guide/"><u>Updated 2024 Approved The Ins and Outs of Converting MP3 Files to MP4 A Beginners Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/hot-40i-messages-recovery-recover-deleted-messages-from-hot-40i-by-fonelab-android-recover-messages/"><u>Hot 40i Messages Recovery - Recover Deleted Messages from Hot 40i</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-silent-screens-to-life-tricks-for-win1011-users/"><u>Bringing Silent Screens to Life: Tricks for Win10/11 Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-ace-the-game-download-every-tiktok-video-with-ease/"><u>In 2024, Ace the Game  Download Every TikTok Video with Ease</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-stabilize-your-videos-for-free-top-software-for-windows-and-mac/"><u>Updated 2024 Approved Stabilize Your Videos for Free Top Software for Windows and Mac</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-xiaomi-redmi-13c-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Xiaomi Redmi 13C to iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-display-settings-via-nonfunctional-fn-button-in-windows-11/"><u>Addressing Faulty Display Settings via Nonfunctional Fn Button in Windows 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-progopro-enhancing-footage-and-stability-for-2024/"><u>[New] ProGoPro  Enhancing Footage & Stability for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719241276591-team-chat-freezing-heres-a-fix/"><u>Team Chat Freezing? Here’s a Fix!</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-workflow-of-windows-11s-recovery-features/"><u>Breaking Down the Workflow of Windows 11'S Recovery Features</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/instantly-display-pics-on-platforms-with-this-guide-for-2024/"><u>Instantly Display Pics on Platforms with This Guide for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-idea-to-hit-solo-podcast-production-tactics/"><u>[Updated] From Idea to Hit  Solo Podcast Production Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-file-download-blockades-on-windows-11/"><u>Breaking Through File Download Blockades on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/10-overlooked-windows-11-aesthetic-themes/"><u>10 Overlooked Windows 11 Aesthetic Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/your-guide-to-iconic-fonts-boosting-video-engagement-for-2024/"><u>Your Guide to Iconic Fonts Boosting Video Engagement for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-fix-the-windows-search-bar-not-showing-or-working-on-windows-11/"><u>11 Ways to Fix the Windows Search Bar Not Showing or Working on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-top-picks-review-best-4k-capture-gadgets-and-apps-for-2024/"><u>[Updated] Top Picks Review  Best 4K Capture Gadgets and Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266282483-combatting-common-windows-11-mail-errors-get-your-email-back-now/"><u>Combatting Common Windows 11 Mail Errors - Get Your Email Back Now</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://windows11.techidaily.com/1719207064707-ifas-hottest-laptops-unveiled/"><u>IFA's Hottest Laptops Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/1719271997711-enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility.</u></a></li>
<li><a href="https://windows11.techidaily.com/1719256266387-repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise</u></a></li>
<li><a href="https://windows11.techidaily.com/10-easy-steps-for-a-working-windows-mouse/"><u>10 Easy Steps for a Working Windows Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/1719356403176-cross-language-build-system-setup/"><u>Cross-Language Build System Setup:</u></a></li>
<li><a href="https://windows11.techidaily.com/1719235299454-overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-10-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 10 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266225421-eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/best-video-splitters-and-editors-on-windows-systems/"><u>Best Video Splitters & Editors on Windows Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-12-pro-max-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 12 Pro Max? How to Fix it?</u></a></li>
<li><a href="https://windows11.techidaily.com/1719252317464-understanding-and-fixing-the-common-problem-of-wwinplusp-not-working/"><u>Understanding and Fixing the Common Problem of WWin+P Not Working</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-se-2022-to-ipad-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone SE (2022) to iPad? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-transitioning-vids-from-twitter-to-fb-engagement-zone/"><u>[Updated] In 2024, Transitioning Vids From Twitter to FB Engagement Zone</u></a></li>
<li><a href="https://windows11.techidaily.com/10-must-have-microsoft-store-apps-for-a-new-windows-pc/"><u>10 Must-Have Microsoft Store Apps for a New Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/1719297453407-mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-poco-x5-pro-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Poco X5 Pro Through Google Earth?</u></a></li>
<li><a href="https://windows11.techidaily.com/add-emulators-to-playnite-a-windows-guide/"><u>Add Emulators to Playnite: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/1719267835321-reactivating-silenced-pc-speakers-easy-fixes-ahead/"><u>Reactivating Silenced PC Speakers – Easy Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-expiring-software-license-caution-in-windows-1011/"><u>Avoiding Expiring Software License Caution in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719211883980-tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-11-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 11 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://windows11.techidaily.com/10-essential-windows-methods-for-controller-recognition/"><u>10 Essential Windows Methods for Controller Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293537225-resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/boost-your-tiktok-video-speed-easy-methods-explored/"><u>Boost Your TikTok Video Speed  Easy Methods Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-fix-onedrive-sync-issues-on-windows-11/"><u>10 Ways to Fix OneDrive Sync Issues on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-minecraft-branding-tools-download/"><u>[Updated] 2024 Approved  Free Minecraft Branding Tools Download</u></a></li>
<li><a href="https://windows11.techidaily.com/big-byte-in-mini-pcs-but-barely-booming/"><u>Big Byte in Mini PCs, But Barely Booming</u></a></li>
<li><a href="https://windows11.techidaily.com/13-ways-to-open-the-windows-system-settings/"><u>13 Ways to Open the Windows System Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-clean-up-your-firewall-rules/"><u>10 Ways to Clean Up Your Firewall Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-1110-malwarebytes-functional-flaws/"><u>Addressing Windows 11/10 Malwarebytes Functional Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-store-failure-code-0x800704cf/"><u>Addressing Windows Store Failure Code 0X800704CF</u></a></li>
</ul></div>
