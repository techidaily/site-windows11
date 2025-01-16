---
title: Customize Your PC's Idle Lock Time
date: 2025-01-15T05:18:04.639Z
updated: 2025-01-15T16:56:11.456Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Your PC's Idle Lock Time
excerpt: This Article Describes Customize Your PC's Idle Lock Time
keywords: PC Idle Time Customization,PC Sleep Lock Adjust,Set PC Standby Delay,Customizable PC Idle,Tailor PC Downtime,Modify PC Sleep Timer,Personalize Pc Rest State
thumbnail: https://thmb.techidaily.com/eb0b88fc8ea01a6f57ac593062a230bcd4f411a04c405e68f58f5857acd450ec.jpg
---

## Customize Your PC's Idle Lock Time

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/ut-the-clutter-convert-videos-discover-the-best-alternatives-for-flv-to-yt/"><u>[New] Cut the Clutter, Convert Videos Discover the Best Alternatives for Flv to YT</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-ideal-choices-our-exclusive-top-10-gopro-case-picks-for-2024/"><u>[Updated] Ideal Choices Our Exclusive Top 10 GoPro Case Picks for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-perfecting-highlight-covers-an-in-depth-insta-photography-guide/"><u>2024 Approved Perfecting Highlight Covers An In-Depth Insta Photography Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-path-to-correctness-resolving-server-stumbled-issues-in-win-store/"><u>Clear Path to Correctness: Resolving Server Stumbled Issues in Win Store</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-adjusting-low-power-modes-in-windows/"><u>Essential Tips: Adjusting Low-Power Modes in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win-reviews.techidaily.com/guide-urgent-fixer-un-hdd-externe-detecte-sans-acces-immediat/"><u>Guide Urgent : Fixer Un HDD Externe Détecté Sans Accès Immédiat !</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-typing-hiccups-top-7-solutions-for-win-11s-key-lag/"><u>Navigate Typing Hiccups: Top 7 Solutions for Win 11'S Key Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-webp-images-in-chrome-for-windows-users/"><u>Reverse WebP Images in Chrome for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-deadlocked-files-on-windows-11-a-guide-1/"><u>Reviving Deadlocked Files on Windows 11: A Guide (1)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-device-lockout-windows-11-error-code-22-resolution/"><u>Tackling Device Lockout: Windows 11 Error Code 22 Resolution</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-apps-and-online-tools-to-track-nokia-c12-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Nokia C12 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlock-fluent-interaction-italys-top-10-conversation-starters/"><u>Unlock Fluent Interaction: Italy's Top 10 Conversation Starters</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1723808287239-unlock-savings-and-safer-trips-secure-a-huge-20-discount-on-driver-easy-app-use-coupon-code-now/"><u>Unlock Savings and Safer Trips: Secure a Huge 20% Discount on Driver Easy App - Use Coupon Code Now</u></a></li>
<li><a href="https://windows11.techidaily.com/update-mail-and-calendars-style-them-with-fav-photos/"><u>Update Mail & Calendars: Style Them with Fav Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/your-route-to-a-maps-integrated-windows-experience/"><u>Your Route to a Maps-Integrated Windows Experience</u></a></li>
</ul></div>

