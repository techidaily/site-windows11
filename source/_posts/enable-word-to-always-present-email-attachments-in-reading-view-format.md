---
title: Enable Word to Always Present Email Attachments in Reading View Format
date: 2024-07-11T21:21:14.249Z
updated: 2024-07-12T21:21:14.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Word to Always Present Email Attachments in Reading View Format
excerpt: This Article Describes Enable Word to Always Present Email Attachments in Reading View Format
keywords: ReadEmailAttachments,WordReadAttachFormat,EnableEmailView,AttachByWord,ReadingEmailFormat,EmailAttachmentInWord,ViewEmailAttachments
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
---

## Enable Word to Always Present Email Attachments in Reading View Format

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.


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
<li><a href="https://windows11.techidaily.com/how-to-mend-screen-driver-problems-in-windows-11/"><u>How to Mend Screen Driver Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-tracking-down-your-software-install-pathways-in-windows/"><u>Quick Guide: Tracking Down Your Software' Install Pathways in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-onedrive-and-microsoft-accounts-a-walkthrough/"><u>Integrating OneDrive & Microsoft Accounts: A Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-secret-windows-11-themes-with-the-registry/"><u>How to Unlock Secret Windows 11 Themes With the Registry</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-xiaomi-redmi-note-12-4g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Xiaomi Redmi Note 12 4G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-10-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-iis-quick-windows-internet-pathway/"><u>Mastering IIS: Quick Windows Internet Pathway</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-taskbar-notification-banners/"><u>Resurrecting Taskbar Notification Banners</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-path-to-professionalism-morphvox-transformation-guide/"><u>2024 Approved  Path to Professionalism  MorphVOX Transformation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-record-audio-on-windows-11/"><u>How to Record Audio on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-and-control-fast-boot-in-your-windows-11-pc/"><u>How to Activate and Control Fast Boot in Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-windows-update-roadblocks-effortlessly/"><u>Navigate Past Windows Update Roadblocks Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-sound-experience-in-windows-11/"><u>Tailoring Your Sound Experience in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/top-10-effortless-yet-striking-tikfilters-for-all/"><u>Top 10 Effortless Yet Striking TikFilters for All</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-master-the-art-of-console-game-recording-with-computer-assistance/"><u>[Updated] 2024 Approved  Master the Art of Console Game Recording with Computer Assistance</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-to-lost-steam-contact-list-win11/"><u>Regaining Access to Lost Steam Contact List (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-top-5-text-to-speech-websites/"><u>New In 2024, Top 5 Text to Speech Websites</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exclusive-spotlight-on-tone-treasures-websites/"><u>[New] Exclusive Spotlight on Tone Treasures Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/snipemaster-offline-solutions-for-reconnecting-it/"><u>SnipeMaster Offline? Solutions for Reconnecting It</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-from-still-to-stunning-8-best-animated-photo-makers/"><u>In 2024, From Still to Stunning 8 Best Animated Photo Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-nokia-c32-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Nokia C32? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-capture-failures-overcoming-pc-spec-limitations/"><u>Resolving Capture Failures: Overcoming PC Spec Limitations</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-for-files-mastering-windows-11s-history/"><u>Time Travel for Files: Mastering Windows 11'S History</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-pc-with-the-proper-management-of-fn-key/"><u>Secure Your PC with the Proper Management of Fn Key</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-navigating-the-best-the-ultimate-7-android-adblockers-guide/"><u>In 2024, Navigating the Best  The Ultimate 7 Android AdBlockers Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unwind-youtube-videos-advanced-retrospectives/"><u>[Updated] Unwind YouTube Videos  Advanced Retrospectives</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-resource-monitor-app-when-its-not-working-on-windows-11/"><u>How to Fix the Resource Monitor App When It's Not Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-post-sleep-device-awareness-procedures/"><u>Mastering Post-Sleep Device Awareness Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-knowledge-on-folder-tagsging-in-windows-explorer/"><u>Insider Knowledge on Folder Tagsging in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/program-specific-keys-on-a-microsoft-system/"><u>Program-Specific Keys on a Microsoft System</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/keep-your-tweets-compliant-with-aspect-ratio-requirements/"><u>Keep Your Tweets Compliant with Aspect Ratio Requirements</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-navigating-the-world-of-tiktok-marketing-hits-and-insights/"><u>[Updated] Navigating the World of TikTok Marketing  Hits & Insights</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-best-fcpx-tutorial-collection-channels-and-websites-for-2024/"><u>New Best FCPX Tutorial Collection Channels and Websites for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solution-for-fixing-the-invalid-file-history-options-in-windows/"><u>Solution for Fixing the Invalid File History Options in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-lava-blaze-pro-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Lava Blaze Pro 5G PC | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-realme-gt-5-240w-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Realme GT 5 (240W)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-the-silenced-wastebin-image-in-windows-11/"><u>Reviving the Silenced Wastebin Image in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-poco-x6-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Poco X6</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-application-of-ping-for-optimal-pc-performance/"><u>Strategic Application of Ping for Optimal PC Performance</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-choruscheck-live-audio-critique/"><u>[New] ChorusCheck  Live Audio Critique</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-trash-for-permanent-deletion-on-windows-oses/"><u>Mastering Desktop Trash for Permanent Deletion on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unlock-windows-credentials-management/"><u>Steps to Unlock Windows Credentials Management</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-revive-slow-running-asana-on-windows/"><u>Solutions to Revive Slow-Running Asana on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-quiet-hardware-reclaiming-sound-systems/"><u>Overcoming Quiet Hardware: Reclaiming Sound Systems</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-rise-to-the-top-the-essentials-of-starting-a-youtube-gaming-sensation/"><u>[Updated] In 2024, Rise to the Top  The Essentials of Starting a YouTube Gaming Sensation</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-breaking-down-the-footage-how-to-split-videos-into-smaller-clips-in-windows-live-movie-maker-for-2024/"><u>Updated Breaking Down the Footage How to Split Videos Into Smaller Clips in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-no-light-gameplay-experience-on-windows/"><u>Remedies for No-Light Gameplay Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-prep-your-pc-with-win-11-via-these-3-usb-steps/"><u>Quickly Prep Your PC with Win 11 via These 3 USB Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-outlooks-speed-for-better-windows-experience/"><u>Revamp Outlook's Speed for Better Windows Experience</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-mac-users-download-vllo-and-find-alternative-solutions/"><u>In 2024, Mac Users Download VLLO and Find Alternative Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-to-personalizing-windows-11-fax-cover-pages/"><u>The Pathway to Personalizing Windows 11 Fax Cover Pages</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-nokia-c12-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Nokia C12 Android SIM Unlock APK</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-guide-on-google-podcast-upload/"><u>[Updated] Guide on Google Podcast Upload</u></a></li>
</ul></div>
