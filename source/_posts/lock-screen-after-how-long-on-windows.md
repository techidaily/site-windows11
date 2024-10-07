---
title: Lock Screen After How Long on Windows?
date: 2024-10-02T22:18:07.340Z
updated: 2024-10-07T05:05:43.534Z
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
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .

6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-unlock-the-power-of-visual-storytelling-with-screen-capture-skills/"><u>[New] In 2024, Unlock the Power of Visual Storytelling with Screen Capture Skills</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-effortless-editing-in-obs-studio-with-top-5-hacks/"><u>[Updated] In 2024, Effortless Editing in OBS Studio with Top 5 Hacks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unleashing-the-full-potential-of-your-channel-in-studio/"><u>2024 Approved Unleashing the Full Potential of Your Channel in Studio</u></a></li>
<li><a href="https://data-recovery.techidaily.com/bug-free-gaming-how-from-the-ashes-of-remnant-now-stays-steady-on-launch/"><u>Bug-Free Gaming: How 'From the Ashes of Remnant' Now Stays Steady on Launch</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-depth-review-of-ivona-text-to-speech-converter/"><u>In-Depth Review of Ivona Text to Speech Converter</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-smooth-video-transitions-taming-vlc-lags/"><u>Mastering Smooth Video Transitions: Taming VLC Lags</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-pitfalls-a-windows-11-overview/"><u>Navigating the Pitfalls: A Windows 11 Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-os-not-found-a-comprehensive-guide/"><u>Overcoming OS Not Found: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-constant-display-of-edge-buttons/"><u>Preventing Constant Display of Edge Buttons</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ining-the-greatest-movies-2023-edition/"><u>Redefining The Greatest Movies 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-windows-error-8-ways-to-overcome-sign-in-denial/"><u>Sidestep Windows Error: 8 Ways to Overcome Sign-In Denial</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-strategy-for-bio-linking-on-tiktok-for-2024/"><u>Ultimate Strategy for Bio Linking on TikTok for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-efficiency-ditch-the-excess-in-win11/"><u>Unleash Efficiency: Ditch the Excess in Win11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-entertainment-features-on-chatgpt-here-are-the-best-games-to-play/"><u>Unlock Entertainment Features on ChatGPT – Here Are the Best Games to Play</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-wi-fi-errors-addressing-missing-actions-in-prompts/"><u>Winning Over Wi-Fi Errors: Addressing Missing Actions in Prompts</u></a></li>
</ul></div>

