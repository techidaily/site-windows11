---
title: Lock Screen After How Long on Windows?
date: 2024-12-18T17:20:38.574Z
updated: 2024-12-25T18:32:20.242Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .

6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-unleashing-potential-profile-video-elevation/"><u>[New] In 2024, Unleashing Potential Profile Video Elevation</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-a-beginners-path-to-compiling-a-youtube-playlist-for-2024/"><u>[Updated] A Beginner's Path to Compiling a YouTube Playlist for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-cinematic-composer-software-for-2024/"><u>[Updated] Cinematic Composer Software for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-lenovos-screen-recording-an-in-depth-user-manual/"><u>[Updated] In 2024, Lenovo’s Screen Recording – An In-Depth User Manual</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-unleash-creative-potential-for-video-editing-in-windows-photos-for-2024/"><u>[Updated] Unleash Creative Potential for Video Editing in Windows Photos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-benefits-of-arm-based-copilotplus-computers-why-theyre-perfect-for-me/"><u>Exploring the Benefits of ARM-Based Copilot+ Computers: Why They're Perfect for Me</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-evolution-a-compelling-overview-of-windows-wallpaper-developments/"><u>Exploring the Evolution: A Compelling Overview of Windows Wallpaper Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/future-of-windows-11s-copilot-feature-understanding-the-phasing-out-process/"><u>Future of Windows 11'S Copilot Feature: Understanding the Phasing Out Process</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-safely-procure-pure-photography-collections/"><u>How to Safely Procure Pure Photography Collections</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-7-best-zero-cost-web-based-film-makers/"><u>In 2024, 7 Best Zero-Cost Web-Based Film Makers</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-successfully-addresses-persistent-problems-with-latest-windows-update-releases/"><u>Microsoft Successfully Addresses Persistent Problems with Latest Windows Update Releases</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/sharing-knowledge-via-instagrams-hyperlink-haven-for-2024/"><u>Sharing Knowledge via Instagram's Hyperlink Haven for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microsoft-edge-by-disabling-redundant-features-techniques-and-tips/"><u>Streamlining Microsoft Edge by Disabling Redundant Features - Techniques and Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-fundamental-windows-terminal-commands-every-new-user-should-know/"><u>Top 10 Fundamental Windows Terminal Commands Every New User Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-linux-qualities-deserving-a-spot-in-the-next-windows-update/"><u>Top 7 Linux Qualities Deserving a Spot in the Next Windows Update</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-oppo-find-x7-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Oppo Find X7 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-lifespan-extension-continuity-and-microsoft/"><u>Windows 11, Lifespan Extension, Continuity, and Microsoft.</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-gaming-on-windows-11-a-step-by-step-performance-optimization-tutorial/"><u>Winning at Gaming on Windows 11: A Step-by-Step Performance Optimization Tutorial</u></a></li>
</ul></div>

