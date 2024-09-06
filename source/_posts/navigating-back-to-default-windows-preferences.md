---
title: Navigating Back to Default Windows Preferences
date: 2024-09-05T02:14:56.696Z
updated: 2024-09-06T02:14:56.696Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Back to Default Windows Preferences
excerpt: This Article Describes Navigating Back to Default Windows Preferences
keywords: Default Window Settings,Win Preference Restore,Default Appearance Fix,Default System Lookup,Windows Standard Mode,Reset Window UI,Config Back to Defaults
thumbnail: https://thmb.techidaily.com/db339cfb71ad17e704275f446976657b74bdf593b2c3464a856c74dd3bbe549b.jpg
---

## Navigating Back to Default Windows Preferences

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to[create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


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
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-crafting-content-that-captivates-a-guide-to-facebook-reels/"><u>[Updated] 2024 Approved  Crafting Content that Captivates  A Guide to Facebook Reels</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-the-comprehensive-manual-for-effective-morphvox-voice-changes/"><u>[Updated] 2024 Approved  The Comprehensive Manual for Effective MorphVOX Voice Changes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-list-10-budget-friendly-passport-photographers-online/"><u>[Updated] Exclusive List  10 Budget-Friendly Passport Photographers Online</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-essential-knowledge-how-io-screen-recorder-works/"><u>[Updated] In 2024, Essential Knowledge  How Io Screen Recorder Works</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-redefining-the-greatest-movies-2023-edition-for-2024/"><u>[Updated] Redefining The Greatest Movies  2023 Edition for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-the-best-10-vector-stock-pools/"><u>2024 Approved  Navigating the Best 10 Vector Stock Pools</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-honor-magic-6-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/cinema-quest-the-definitive-order-for-enjoying-indiana-jones-movies/"><u>Cinema Quest: The Definitive Order for Enjoying Indiana Jones Movies</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-7-innovative-fixes-for-rename-issue-in-win-11/"><u>Expert Advice: 7 Innovative Fixes for Rename Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-6-incongruent-features-in-windows-11/"><u>Exposing 6 Incongruent Features in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-permissions-hurdle-become-an-admin-instantly/"><u>Fix Permissions Hurdle - Become an Admin Instantly</u></a></li>
<li><a href="https://techidaily.com/hard-reset-xiaomi-civi-3-disney-100th-anniversary-edition-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Xiaomi Civi 3 Disney 100th Anniversary Edition in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-get-arcadegeddon-running-smoothly-on-your-pc-again/"><u>How To Get Arcadegeddon Running Smoothly on Your PC Again</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-itel-a60s-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Itel A60s to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-infinix-note-30-vip-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Infinix Note 30 VIP to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-11-best-location-changers-for-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-from-iphone-6-plus-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working From iPhone 6 Plus</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-animators-toolkit-a-detailed-list-of-the-best-cartoon-sounds-available-online/"><u>In 2024, The Animators Toolkit A Detailed List of the Best Cartoon Sounds Available Online</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-secure-file-management-using-powertoys/"><u>Mastery of Secure File Management Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-prioritizing-terminal-over-others/"><u>Maximizing Efficiency: Prioritizing Terminal Over Others</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-imessage-on-non-ios-devices-tips-and-tricks/"><u>Navigating iMessage on Non-iOS Devices: Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-fn-button-a-comprehensive-guidebook/"><u>Navigating the Fn Button: A Comprehensive Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/no-expense-spared-try-these-5-top-tier-driver-upgrades/"><u>No Expense Spared? Try These 5 Top-Tier Driver Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-web-access-a-comparative-study-of-browser-ram-use/"><u>Optimal Web Access: A Comparative Study of Browser RAM Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-audacity-audio-error-in-windows-1111/"><u>Overcoming Audacity Audio Error in Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-defense-7-steps-to-thwart-windows-hackers/"><u>Proactive Defense: 7 Steps to Thwart Windows Hackers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-erroneous-0x80246007-in-win11-uptime/"><u>Quick Fix for Erroneous 0X80246007 in Win11 Uptime</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-windows-clock-stop-time-discrepancy-woes/"><u>Realign Windows Clock: Stop Time Discrepancy Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-credible-power-consumption-forecasts-on-windows-11/"><u>Reinstating Credible Power Consumption Forecasts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missing-update-files-issue-error-code-0x80070003-in-windows/"><u>Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-operative-bin-icon-on-windows-11/"><u>Restoring Operative Bin Icon on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-incorporate-gallery-view-into-file-explorer/"><u>Seamlessly Incorporate Gallery View Into File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/show-more-pins-strategies-for-start-screen/"><u>Show More Pins: Strategies for Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-w11s-onedrive-error-code-def5/"><u>Sidestep W11's OneDrive Error Code DEF5</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-strategies-for-merging-content-on-win-11/"><u>Smart Strategies for Merging Content on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-qbittorrent-transfer-from-one-windows-to-another/"><u>Steps for qBittorrent Transfer From One Windows to Another</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approaches-to-shutting-down-your-computer/"><u>Strategic Approaches to Shutting Down Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-game-hub-connectivity-issues/"><u>Strategies to Overcome Game Hub Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-win-based-software-overcome-too-many-requests/"><u>Streamlining Your Win-Based Software: Overcome Too Many Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-application-launch-in-windows-11/"><u>Swift Application Launch in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-glitches-the-ultimate-guide-for-eradicating-error-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>Triumph Over Glitches: The Ultimate Guide for Eradicating Error 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solving-windows-10s-missing-fix-service-registration-problems/"><u>Troubleshooting and Solving Windows 10'S Missing Fix Service Registration Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-itunes-performance-issues-on-windows-pcs/"><u>Unlocking iTunes Performance Issues on Windows PCs</u></a></li>
<li><a href="https://article-posts.techidaily.com/updating-your-skills-regularly/"><u>Updating Your Skills Regularly</u></a></li>
</ul></div>
