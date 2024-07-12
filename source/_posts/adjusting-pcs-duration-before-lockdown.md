---
title: Adjusting PC's Duration Before Lockdown
date: 2024-07-11T21:35:48.852Z
updated: 2024-07-12T21:35:48.852Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting PC's Duration Before Lockdown
excerpt: This Article Describes Adjusting PC's Duration Before Lockdown
keywords: Pre-Lockdown PC Setup,Optimizing Computer Duration,Device Lockdown Prep Tips,Adjust PC Before Quarantine,Manage Screen Time Pre-Shutdown,Computer Usage Adjustment,Lockdown Tech Optimization
thumbnail: https://thmb.techidaily.com/475e778db07011aff476548fbdaa46272592bc242d2a4144096bc7b432d20837.jpg
---

## Adjusting PC's Duration Before Lockdown

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-samsung-galaxy-f14-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Samsung Galaxy F14 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/comparing-stream-quality-with-obs-studio-and-fraps/"><u>Comparing Stream Quality with OBS Studio and Fraps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-itel-p55-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Itel P55</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-linkedin-posts-can-be-made-engaging-by-using-the-emojis-this-article-will-tell-you-its-importance-and-different-ways-to-add-them/"><u>New Linkedin Posts Can Be Made Engaging by Using the Emojis. This Article Will Tell You Its Importance and Different Ways to Add Them</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-ultimate-list-10-vegas-pro-alternatives-for-mac-video-editing-enthusiasts/"><u>Updated The Ultimate List 10 Vegas Pro Alternatives for Mac Video Editing Enthusiasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-zte-blade-a73-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove ZTE Blade A73 5G Fingerprint Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-sound-experience-in-windows-11/"><u>Tailoring Your Sound Experience in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-peek-behind-the-curtain-of-hidden-youtube-videos/"><u>In 2024, How to Peek Behind the Curtain of Hidden YouTube Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transformative-srt-to-txt-guide-for-time-saving/"><u>[New] Transformative SRT to TXT Guide for Time-Saving</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unexpected-security-alerts/"><u>Troubleshooting Windows' Unexpected Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-to-lost-steam-contact-list-win11/"><u>Regaining Access to Lost Steam Contact List (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/solution-for-fixing-the-invalid-file-history-options-in-windows/"><u>Solution for Fixing the Invalid File History Options in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-iis-quick-windows-internet-pathway/"><u>Mastering IIS: Quick Windows Internet Pathway</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-capture-failures-overcoming-pc-spec-limitations/"><u>Resolving Capture Failures: Overcoming PC Spec Limitations</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-taskbar-notification-banners/"><u>Resurrecting Taskbar Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-nokia-c02-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Nokia C02 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-revive-slow-running-asana-on-windows/"><u>Solutions to Revive Slow-Running Asana on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-ultimate-guide-to-purchasing-asmr-microphones/"><u>[Updated] Ultimate Guide to Purchasing ASMR Microphones</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-samsung-galaxy-a14-5g-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Samsung Galaxy A14 5G Phone Now with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/snipemaster-offline-solutions-for-reconnecting-it/"><u>SnipeMaster Offline? Solutions for Reconnecting It</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-tiktok-aspect-ratio-is-a-crucial-element-to-succeeding-in-the-tiktok-algorithm-here-are-some-suggestions-to-improve-video-quality-and-land-on-the-fo/"><u>Updated Tiktok Aspect Ratio Is a Crucial Element to Succeeding in the Tiktok Algorithm. Here Are some Suggestions to Improve Video Quality and Land on the for You Page</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-no-light-gameplay-experience-on-windows/"><u>Remedies for No-Light Gameplay Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/program-specific-keys-on-a-microsoft-system/"><u>Program-Specific Keys on a Microsoft System</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unlock-windows-credentials-management/"><u>Steps to Unlock Windows Credentials Management</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-application-of-ping-for-optimal-pc-performance/"><u>Strategic Application of Ping for Optimal PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-outlooks-speed-for-better-windows-experience/"><u>Revamp Outlook's Speed for Better Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-quiet-hardware-reclaiming-sound-systems/"><u>Overcoming Quiet Hardware: Reclaiming Sound Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-the-silenced-wastebin-image-in-windows-11/"><u>Reviving the Silenced Wastebin Image in Windows 11</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-optimal-5-displays-for-immersive-ps5-gaming/"><u>2024 Approved  Optimal 5 Displays for Immersive PS5 Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-tracking-down-your-software-install-pathways-in-windows/"><u>Quick Guide: Tracking Down Your Software' Install Pathways in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-trash-for-permanent-deletion-on-windows-oses/"><u>Mastering Desktop Trash for Permanent Deletion on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-windows-update-roadblocks-effortlessly/"><u>Navigate Past Windows Update Roadblocks Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-restoring-light-from-dark-mode/"><u>Troubleshooting Steps: Restoring Light From Dark Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-for-files-mastering-windows-11s-history/"><u>Time Travel for Files: Mastering Windows 11'S History</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-prep-your-pc-with-win-11-via-these-3-usb-steps/"><u>Quickly Prep Your PC with Win 11 via These 3 USB Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-post-sleep-device-awareness-procedures/"><u>Mastering Post-Sleep Device Awareness Procedures</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-tiny-turbines-car-shindig/"><u>[New] In 2024, Tiny Turbines' Car Shindig</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-to-personalizing-windows-11-fax-cover-pages/"><u>The Pathway to Personalizing Windows 11 Fax Cover Pages</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-cheap-yet-quality-top-cam-lows/"><u>2024 Approved  Cheap Yet Quality  Top Cam Lows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-calculating-expenses-for-youtubers-success/"><u>[Updated] Calculating Expenses for YouTubers' Success</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-pc-with-the-proper-management-of-fn-key/"><u>Secure Your PC with the Proper Management of Fn Key</u></a></li>
</ul></div>
