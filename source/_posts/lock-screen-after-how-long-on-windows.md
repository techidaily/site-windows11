---
title: Lock Screen After How Long on Windows?
date: 2025-02-08T03:42:07.101Z
updated: 2025-02-10T17:16:05.586Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .

7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://discover-bits.techidaily.com/comprendre-les-differences-recuperation-dimages-systeme-et-restauration-du-systeme-expliquees/"><u>« Comprendre Les Différences : Récupération D’images Système Et Restauration Du Système Expliquées »</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-best-9-screen-free-adventures-in-mobile-gaming-android-edition/"><u>[Updated] Best 9 Screen-Free Adventures in Mobile Gaming (Android Edition)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-unwavering-visual-captures-for-2024/"><u>A Guide to Unwavering Visual Captures for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/explore-the-features-introducing-googles-latest-innovation-a-multi-functional-smart-hub-and-streaming-device/"><u>Explore the Features: Introducing Google's Latest Innovation - A Multi-Functional Smart Hub and Streaming Device</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/fresh-perspectives-on-an-iconic-platformer-revitalized-ratchet-and-clank-examination/"><u>Fresh Perspectives on an Iconic Platformer: Revitalized Ratchet & Clank Examination</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-control-of-costs-windows-11-pro-key-advantages/"><u>Gain Control of Costs: Windows 11 Pro Key Advantages</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-the-required-apple-store-verification-for-iphone-11-pro-by-drfone-ios/"><u>How To Bypass the Required Apple Store Verification For iPhone 11 Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-vivo-x90s-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Vivo X90S</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-windows-obs-studio-crashes/"><u>How to Troubleshoot Windows OBS Studio Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-notepad-on-win11-via-ingenious-sage/"><u>Improve Notepad on Win11 via Ingenious Sage</u></a></li>
<li><a href="https://windows11.techidaily.com/master-9-techniques-to-modify-windows-audio-interface/"><u>Master 9 Techniques to Modify Windows Audio Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-onedrive-errors-efficient-steps-for-instant-folder-addition/"><u>Overcoming Windows OneDrive Errors - Efficient Steps for Instant Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixed-top-10-windows-glitch-solvers/"><u>Quick Fixed: Top 10 Windows Glitch Solvers</u></a></li>
<li><a href="https://windows11.techidaily.com/secret-menu-additions-a-step-by-step-guide-in-win-10/"><u>Secret Menu Additions: A Step-by-Step Guide in Win 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-to-converting-dvd-media-files-into-mp4m4v-format-on-mac/"><u>Step-by-Step Guide to Converting DVD Media Files Into MP4/M4V Format on Mac</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-filmmakers-blueprint-to-panoramic-perfection-9-key-techniques/"><u>The Filmmaker's Blueprint to Panoramic Perfection 9 Key Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-windows-portable-executable-file-format/"><u>What Is the Windows Portable Executable File Format?</u></a></li>
</ul></div>

