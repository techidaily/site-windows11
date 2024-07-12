---
title: Comprehensive Solution for Inaccessible Administrative Mode
date: 2024-07-11T21:44:17.831Z
updated: 2024-07-12T21:44:17.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Solution for Inaccessible Administrative Mode
excerpt: This Article Describes Comprehensive Solution for Inaccessible Administrative Mode
keywords: Admin Access Fix,Unlock Admin Mode,Inclusive Admin Solutions,Admin Security Resolution,Gateway to Admin Control,Eliminate Adminscape Obstacles,Secure Admin Entrance
thumbnail: https://thmb.techidaily.com/5f1dd72a960c69600ce9688063aeb5e7a932b178d483ab7dbc13cbf4ab650189.jpg
---

## Comprehensive Solution for Inaccessible Administrative Mode

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/breaking-through-disabled-script-barrier-4-key-techniques-to-load-ps-successfully/"><u>Breaking Through Disabled Script Barrier: 4 Key Techniques to Load PS Successfully</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Infinix Zero 5G 2023 Turbo? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-windows-functionality-with-these-top-6-android-apps/"><u>Augmenting Windows Functionality with These Top 6 Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-power-hungry-unrealcefsubprocess-a-windows-guide/"><u>Addressing Power-Hungry UnrealCEFSubprocess: A Windows Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-ultimate-no-fuss-techniques-for-valorant-sessions/"><u>2024 Approved  Ultimate No-Fuss Techniques for Valorant Sessions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revitalize-computing-power-refreshing-intels-graphics-drivers/"><u>Revitalize Computing Power: Refreshing Intel's Graphics Drivers</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-mastering-free-video-text-dynamics-for-2024/"><u>[New] Mastering FREE Video Text Dynamics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-why-files-cant-sync-in-steam-library/"><u>Addressing Why Files Can't Sync in Steam Library</u></a></li>
<li><a href="https://windows11.techidaily.com/9-insights-on-how-pc-outperforms-a-mac-in-essential-areas/"><u>9 Insights on How PC Outperforms a Mac in Essential Areas</u></a></li>
<li><a href="https://windows11.techidaily.com/a-fresh-window-on-computers-after-windows-11/"><u>A Fresh Window on Computers: After Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/illuminating-soundscapes-with-imagery-techniques-for-photographic-audio-amalgamation-2023-art-and-technology-insights-for-2024/"><u>Illuminating Soundscapes with Imagery Techniques for Photographic Audio Amalgamation 2023 Art & Technology Insights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-soon-to-end-windows-license-issues/"><u>Avoidance of Soon-to-End Windows License Issues</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/top-iphones-and-androids-ultimate-tiktok-marker-erasers-for-2024/"><u>Top iPhones & Androids  Ultimate TikTok Marker Erasers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-primer-to-installation-of-the-java-sdkjdk-on-windows-11/"><u>A Primer to Installation of the Java SDK/JDK on Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-audio-techniques-capturing-clear-sound/"><u>[Updated] 2024 Approved  Essential Audio Techniques  Capturing Clear Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-spontaneous-windows-11-lockups-and-shuts/"><u>Avoid Spontaneous Windows 11 Lockups & Shuts</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-vivo-v29-pro-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Vivo V29 Pro Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-overdrive-best-5-programs-for-higher-than-100-pc-audio/"><u>Audible Overdrive: Best 5 Programs for Higher-Than-100%% PC Audio</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-top-tier-tools-transforming-remote-discussions/"><u>2024 Approved  Top-Tier Tools Transforming Remote Discussions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-directly-connect-youtube-tunes-to-imovie-seamlessly/"><u>[Updated] In 2024, Directly Connect YouTube Tunes to iMovie Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-file-explorer-errors-essential-fixes-for-win11-users/"><u>Banish File Explorer Errors: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-user-not-valid-issues-in-windows-11-and-11/"><u>Bypassing 'User Not Valid' Issues in Windows 11 & 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-best-of-fcp-top-10-movies-mastered-with-final-cut-pro/"><u>Updated In 2024, The Best of FCP Top 10 Movies Mastered with Final Cut Pro</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leading-edge-wireless-cameras-the-hottest-18-on-the-market/"><u>[New] Leading-Edge Wireless Cameras  The Hottest 18 On The Market</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-navigating-file-explorer-tabs-windows-11-style/"><u>A User's Guide to Navigating File Explorer Tabs, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-with-multi-task-proficiency-on-windows-11-pcs/"><u>Achieve Peak Performance with Multi-Task Proficiency on Windows 11 PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-rapidly-rise-with-smart-instagram-reel-techniques/"><u>In 2024, Rapidly Rise with Smart Instagram Reel Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-top-10-twitter-viewers-2023-edition/"><u>[New] In 2024, The Top 10 Twitter Viewers - 2023 Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-black-background-on-windows-calculator/"><u>Adopting a Black Background on Windows Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-need-old-password-error-in-microsoft-windows/"><u>Bypassing 'Need Old Password' Error in Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-steam-downloads-enhancing-windows-performance/"><u>Boosting Steam Downloads: Enhancing Windows Performance</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-booktoks-15-essential-titles-for-avid-readers-for-2024/"><u>[New] BookTok's 15 Essential Titles for Avid Readers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-gpsvc-wait-issue-on-pcs/"><u>Bypassing the GPSVC Wait Issue on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-performance-with-windows-11-power-options/"><u>Boost Performance with Windows 11 Power Options</u></a></li>
<li><a href="https://windows11.techidaily.com/academic-excellence-with-these-top-8-study-tips-for-windows-users/"><u>Academic Excellence with These Top 8 Study Tips for Windows Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-masters-picks-highest-rated-cards-for-streaming-on-youtube/"><u>In 2024, Master's Picks  Highest Rated Cards for Streaming on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/5-secure-operating-system-tactics-when-bitlocker-is-offline/"><u>5 Secure Operating System Tactics When BitLocker Is Offline</u></a></li>
<li><a href="https://win11.techidaily.com/clipit-woes-uncover-top-fixes-for-swift-recovery/"><u>ClipIt Woes? Uncover Top Fixes for Swift Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/1719359377017-unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vivobook-s-15-the-ultimate-blend-of-style-and-functionality/"><u>ASUS Vivobook S 15: The Ultimate Blend of Style & Functionality</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-boosting-views-with-analytics-in-youtube-strategy/"><u>[Updated] Boosting Views with Analytics in YouTube Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-reconnecting-legrl-after-drops/"><u>Bridging the Gap: Reconnecting LeGRL After Drops</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capturing-dark-scenes-with-iphone-pros/"><u>Capturing Dark Scenes with iPhone Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-firewall-restriction-chrome-connectivity-solution/"><u>Circumventing Firewall Restriction: Chrome Connectivity Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-windows-auditory-restart-post-boot-issue/"><u>Automating Windows Auditory Restart Post-Boot Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-your-window-11-with-these-6-pioneering-android-apps/"><u>Augmenting Your Window 11 with These 6 Pioneering Android Apps</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-top-10-ai-avatar-video-generators/"><u>Updated Top 10 AI Avatar Video Generators</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-vivo-s17-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Vivo S17 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-poco-x5-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Poco X5 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-profit-with-windows-11-pro-capture-best-offers/"><u>Accelerate Profit with Windows 11 Pro: Capture Best Offers</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ultimate-freeze-frame-collection-for-mac-max-156-chars/"><u>[New] Ultimate Freeze Frame Collection for Mac (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-problem-solving-in-windows-10-and-11-via-shortcuts/"><u>Accelerating Problem-Solving in Windows 10 & 11 via Shortcuts</u></a></li>
<li><a href="https://games-able.techidaily.com/adapting-to-change-how-steams-ai-rules-transform-gaming/"><u>Adapting to Change: How Steam's AI Rules Transform Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-tweaks-for-your-windows-11-search-settings/"><u>5 Essential Tweaks for Your Windows 11 Search Settings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-essential-video-concepts-fueling-creativity-in-youtube-channels-for-2024/"><u>[New] Essential Video Concepts  Fueling Creativity in YouTube Channels for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-login-blockers-with-these-8-steps/"><u>Bypassing Windows Login Blockers with These 8 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/androidios-to-windows-pc-microphone-conversion-guide/"><u>Android/iOS to Windows PC Microphone Conversion Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pacing-presentations-with-ease-speedy-slides/"><u>[Updated] Pacing Presentations with Ease  Speedy Slides</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-mac-to-apple-iphone-15-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share Mac to Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-report-dji-inspire-1-reviewed/"><u>[Updated] Comprehensive Report  DJI Inspire 1 Reviewed</u></a></li>
</ul></div>
