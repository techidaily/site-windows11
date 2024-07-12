---
title: Interpreting Launch Identifiers for Applications
date: 2024-07-11T21:14:04.613Z
updated: 2024-07-12T21:14:04.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Interpreting Launch Identifiers for Applications
excerpt: This Article Describes Interpreting Launch Identifiers for Applications
keywords: Launch ID Explained,App Identifier Meaning,Launch Significance,Understanding Launch Codes,Launch Keyword Guide,Decoding Launch Symbols,App Launch Reference
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Interpreting Launch Identifiers for Applications

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-12-pro-passcode-screen-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 Pro Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-the-ultimate-list-of-free-android-video-editing-software/"><u>Updated 2024 Approved The Ultimate List of Free Android Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-the-top-5-personal-information-harvesters/"><u>Win11: The Top 5 Personal Information Harvesters</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-seize-endless-photographic-content-from-elite-4-video-clips/"><u>[Updated] Seize Endless Photographic Content From Elite 4 Video Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-taskbar-notification-banners/"><u>Resurrecting Taskbar Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-secret-windows-11-themes-with-the-registry/"><u>How to Unlock Secret Windows 11 Themes With the Registry</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-to-personalizing-windows-11-fax-cover-pages/"><u>The Pathway to Personalizing Windows 11 Fax Cover Pages</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-tracking-down-your-software-install-pathways-in-windows/"><u>Quick Guide: Tracking Down Your Software' Install Pathways in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-long-does-it-take-to-edit-a-video/"><u>How Long Does It Take To Edit A Video</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-to-lost-steam-contact-list-win11/"><u>Regaining Access to Lost Steam Contact List (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-restoring-light-from-dark-mode/"><u>Troubleshooting Steps: Restoring Light From Dark Mode</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-organize-photo-album-on-iphone-and-icloud/"><u>2024 Approved  How To Organize Photo Album On iPhone And iCloud</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-revive-slow-running-asana-on-windows/"><u>Solutions to Revive Slow-Running Asana on Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-sculpting-your-audio-experience-in-videos-with-ease-and-precision-for-2024/"><u>Updated Sculpting Your Audio Experience in Videos with Ease and Precision for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-iis-quick-windows-internet-pathway/"><u>Mastering IIS: Quick Windows Internet Pathway</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-post-sleep-device-awareness-procedures/"><u>Mastering Post-Sleep Device Awareness Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unlock-windows-credentials-management/"><u>Steps to Unlock Windows Credentials Management</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-application-of-ping-for-optimal-pc-performance/"><u>Strategic Application of Ping for Optimal PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-windows-update-roadblocks-effortlessly/"><u>Navigate Past Windows Update Roadblocks Effortlessly</u></a></li>
<li><a href="https://extra-tips.techidaily.com/user-interface-and-functionality-app-checkup/"><u>User Interface & Functionality App Checkup</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-outlooks-speed-for-better-windows-experience/"><u>Revamp Outlook's Speed for Better Windows Experience</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-tips-and-tricks-for-efficient-twitch-stream-recordings/"><u>[Updated] Tips and Tricks for Efficient Twitch Stream Recordings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/fusiontv-services-international-and-home-viewing-unite/"><u>FusionTV Services  International & Home Viewing Unite</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-get-noticed-10-exceptional-music-video-makers-for-emerging-artists/"><u>Updated 2024 Approved Get Noticed 10 Exceptional Music Video Makers for Emerging Artists</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-knowledge-on-folder-tagsging-in-windows-explorer/"><u>Insider Knowledge on Folder Tagsging in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-trash-for-permanent-deletion-on-windows-oses/"><u>Mastering Desktop Trash for Permanent Deletion on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-sound-experience-in-windows-11/"><u>Tailoring Your Sound Experience in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/snipemaster-offline-solutions-for-reconnecting-it/"><u>SnipeMaster Offline? Solutions for Reconnecting It</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/elevate-note-taking-to-new-heights-with-mematic/"><u>Elevate Note-Taking to New Heights with Mematic</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-capture-failures-overcoming-pc-spec-limitations/"><u>Resolving Capture Failures: Overcoming PC Spec Limitations</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-demystifying-youtube-seo-terminology-and-tactics/"><u>[New] 2024 Approved  Demystifying YouTube SEO Terminology and Tactics</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-unveiling-tiktok-mastery-camera-settings-and-editing-secrets-revealed/"><u>[New] Unveiling TikTok Mastery  Camera Settings and Editing Secrets Revealed</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-full-potential-of-canon-cams-with-gratuitous-and-fee-based-luts/"><u>[New] Unlock Full Potential of Canon Cams with Gratuitous & Fee-Based LUTs</u></a></li>
<li><a href="https://windows11.techidaily.com/program-specific-keys-on-a-microsoft-system/"><u>Program-Specific Keys on a Microsoft System</u></a></li>
<li><a href="https://windows11.techidaily.com/solution-for-fixing-the-invalid-file-history-options-in-windows/"><u>Solution for Fixing the Invalid File History Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-pc-with-the-proper-management-of-fn-key/"><u>Secure Your PC with the Proper Management of Fn Key</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unexpected-security-alerts/"><u>Troubleshooting Windows' Unexpected Security Alerts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/mastering-audio-editing-a-step-by-step-approach-for-isolating-vocals-with-audacity/"><u>Mastering Audio Editing A Step-by-Step Approach for Isolating Vocals with Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-no-light-gameplay-experience-on-windows/"><u>Remedies for No-Light Gameplay Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-for-files-mastering-windows-11s-history/"><u>Time Travel for Files: Mastering Windows 11'S History</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-prep-your-pc-with-win-11-via-these-3-usb-steps/"><u>Quickly Prep Your PC with Win 11 via These 3 USB Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-the-silenced-wastebin-image-in-windows-11/"><u>Reviving the Silenced Wastebin Image in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-quiet-hardware-reclaiming-sound-systems/"><u>Overcoming Quiet Hardware: Reclaiming Sound Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-understanding-and-fixing-blue-screen/"><u>Win11 BSOD: Understanding & Fixing Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-onedrive-and-microsoft-accounts-a-walkthrough/"><u>Integrating OneDrive & Microsoft Accounts: A Walkthrough</u></a></li>
</ul></div>
