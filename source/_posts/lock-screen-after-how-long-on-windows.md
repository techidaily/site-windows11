---
title: Lock Screen After How Long on Windows?
date: 2024-10-12T02:12:40.258Z
updated: 2024-10-19T01:24:36.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Lock Screen After How Long on Windows?
excerpt: This Article Describes Lock Screen After How Long on Windows?
keywords: LockWinScreenDelay,WindowsLockDuration,ScreenLockTimeWindows,DelayedLockWindows,TimerForWindowsLock,AutoLockOnWindows,WindowsLockTimerSetting
thumbnail: https://thmb.techidaily.com/7180d1f46214638b981f44d739909bb52ccedea125713b9abadc25eed94ff8d6.jpg
---

## Lock Screen After How Long on Windows?

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .

7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://digital-screen-recording.techidaily.com/new-essential-guide-mac-screen-recording-techniques/"><u>[New] Essential Guide Mac Screen Recording Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-instant-impression-audiovisual-capture/"><u>[New] In 2024, Instant Impression Audiovisual Capture</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-5-high-res-screens-for-playstation-5/"><u>[New] Top 5 High-Res Screens for PlayStation 5</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-earnings-update-navigating-youtube-monetization/"><u>[Updated] Earnings Update Navigating YouTube Monetization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-warrior-spirits-rising-comparable-game-suggestions/"><u>[Updated] In 2024, Warrior Spirits Rising Comparable Game Suggestions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-ultimate-list-of-windows-10-webcam-recorders/"><u>[Updated] The Ultimate List of Windows 10 Webcam Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-improve-network-stability-in-windows-11-systems/"><u>How to Improve Network Stability in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-resolve-windows-11-error-0x800f0922/"><u>How To Quickly Resolve Windows 11 Error 0X800F0922</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-12-pro-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 12 Pro Without iTunes in 5 Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-apps-fixed-in-task-manager-on-pc/"><u>Keeping Apps Fixed in Task Manager on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-installation-of-windows-11-arm-from-iso/"><u>Mastering the Installation of Windows 11 ARM From ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-a-detailed-guide-to-its-auto-hdr-function/"><u>Navigating Windows 11: A Detailed Guide to Its Auto HDR Function</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-self-lock-in-windows-os/"><u>Preventing Self-Lock in Windows OS</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/resolving-samsung-television-issues-troubleshooting-mp4-file-playback/"><u>Resolving Samsung Television Issues: Troubleshooting MP4 File Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-progress-solving-qbittorrent-pauses-on-windows/"><u>Restarting Progress: Solving qBittorrent Pauses on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ath-to-mastering-the-art-of-asmr-filmmaking-for-2024/"><u>The Path to Mastering the Art of ASMR Filmmaking for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-oppo-reno-8t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-if-the-mail-and-calendar-app-wont-open-in-windows-11/"><u>What to Do if the Mail and Calendar App Won’t Open in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-productivity-push-crafting-uwp-shortcuts/"><u>Windows 11 Productivity Push: Crafting UWP Shortcuts</u></a></li>
</ul></div>

