---
title: Transforming User Access Control on Common Windows Systems
date: 2024-09-05T02:08:04.332Z
updated: 2024-09-06T02:08:04.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transforming User Access Control on Common Windows Systems
excerpt: This Article Describes Transforming User Access Control on Common Windows Systems
keywords: Windows Access Control Transformation,UAC Enhancement Windows,Secure Windows Security Update,Improving Windows Permissions,User Access Control Upgrade,Windows Authentication Advancement,Elevated Privilege Management Windows
thumbnail: https://thmb.techidaily.com/b1dd0483f32a09412f335f94508f9f7301d5aa196fe907bac96fdd29e9d8162d.png
---

## Transforming User Access Control on Common Windows Systems

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-advanced-guide-to-using-luts-for-professional-image-editors/"><u>[New] Advanced Guide to Using LUTs for Professional Image Editors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-tweetvidtowebm-easy-streaming-tools/"><u>[New] In 2024, TweetVidToWebM  Easy Streaming Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-process-of-android-video-u-turns/"><u>[New] The Process of Android Video U-Turns</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweet-town-ranking-the-trending-threads-for-2024/"><u>[New] Tweet Town  Ranking the Trending Threads for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-command-your-tech-not-money-needed/"><u>[Updated] Command Your Tech, Not Money Needed</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-ultimate-video-streaming-channel-lists-films-and-series/"><u>[Updated] In 2024, Ultimate Video Streaming Channel Lists  Films & Series</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-podcast-dissemination-instagram-stories-vs-feed/"><u>[Updated] Podcast Dissemination  Instagram Stories Vs. Feed</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-selecting-audio-for-your-movie-trailer/"><u>[Updated] Selecting Audio for Your Movie Trailer</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-ultimate-list-of-trending-instagram-hashtags-for-success/"><u>2024 Approved  The Ultimate List of Trending Instagram Hashtags for Success</u></a></li>
<li><a href="https://extra-tips.techidaily.com/astonishingly-fast-finders-of-forlorn-reddit-content-for-2024/"><u>Astonishingly Fast Finders of Forlorn Reddit Content for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-installation-issues-resolved-a-comprehensive-guide/"><u>BattlEye Installation Issues Resolved - A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/convert-avi-videos-to-mpeg-for-free-using-your-mac/"><u>Convert AVI Videos to MPEG for Free Using Your Mac</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-facebooks-feed-how-to-make-it-yours/"><u>Decoding Facebook's Feed: How to Make It Yours</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dialogue-dynamics-and-emotional-depth-via-gpts-novel-writing-tips/"><u>Dialogue Dynamics and Emotional Depth via GPT’s Novel-Writing Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-restful-nights-with-the-ihome-zenergy-bedside-sleep-enhancer-comprehensive-review/"><u>Discover Restful Nights with the IHome Zenergy Bedside Sleep Enhancer – Comprehensive Review</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/eliminate-unexpected-shutdowns-in-depth-strategies-for-fixing-windows-seven/"><u>Eliminate Unexpected Shutdowns: In-Depth Strategies for Fixing Windows ˈseven</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-set-up-your-windows-11-home/"><u>Explore and Set Up Your Windows 11 Home</u></a></li>
<li><a href="https://os-tips.techidaily.com/find-your-missing-iphone-easily-with-these-android-tricks/"><u>Find Your Missing iPhone Easily with These Android Tricks!</u></a></li>
<li><a href="https://windows11.techidaily.com/gift-ideas-for-a-christmasy-windows-11-experience/"><u>Gift Ideas for a Christmasy Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-revealing-your-pcs-background-image-storage/"><u>Guide to Revealing Your PC’s Background Image Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-windows-error-0x0000004e-woes/"><u>Guiding Users Through Windows' Error 0X0000004E Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-missing-router-control-center/"><u>How to Remedy Missing Router Control Center</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-iphone-xs-max-without-backup-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Restore iPhone XS Max without Backup | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-photo-errors-in-windows-devices/"><u>How to Tackle Photo Errors in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-your-powertoys-settings-to-a-new-pc/"><u>How to Transfer Your PowerToys Settings to a New PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-will-eliminating-taskbar-chat-from-windows-11-change-your-user-experience/"><u>How Will Eliminating Taskbar Chat From Windows 11 Change Your User Experience?</u></a></li>
<li><a href="https://windows11.techidaily.com/ignore-non-essential-feedback-alerts-suggestions-on-windows/"><u>Ignore Non-Essential Feedback Alerts, Suggestions on Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfersync-notes-from-apple-iphone-x-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer/Sync Notes from Apple iPhone X to iPad | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-meditative-tunes-compilation-top-10-legal-streams/"><u>In 2024, Meditative Tunes Compilation - Top 10 Legal Streams</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-oppo-a78-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Oppo A78 5G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-xiaomi-redmi-a2-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Xiaomi Redmi A2 Location | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Samsung Galaxy S23 Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-magic-6-profrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor Magic 6 ProFRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/make-the-most-of-older-os-a-guide-beyond-windows-11/"><u>Make the Most of Older OS: A Guide Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-webcam-fixes-error-a00f4289/"><u>Mastering Windows 11 Webcam Fixes - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-taskbar-icon-separation-in-win-11/"><u>Mastery Over Taskbar Icon Separation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11s-application-management-capabilities-with-winget/"><u>Maximizing Windows 11'S Application Management Capabilities with Winget</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-sign-in-woes-heres-how-to-fix-it/"><u>Microsoft Store Sign-In Woes? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/modernize-windows-shift-to-enhanced-tiled-workspace/"><u>Modernize Windows: Shift to Enhanced Tiled Workspace</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-steps-to-overcome-0x8004def5-onedrive-error-in-win11/"><u>Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-snip-tool-text-expertly-on-windows-11/"><u>Perfect Your Snip Tool Text Expertly on Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/quick-fixes-for-the-troublesome-bsod-error-code-0x00000116/"><u>Quick Fixes for the Troublesome BSOD Error Code 0X00000116</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-addressing-need-to-quit-in-roblox-on-pc/"><u>Quick Guide: Addressing Need To Quit in Roblox on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/race-the-rating-effective-techniques-for-measuring-network-adapter-speed-on-windows/"><u>Race the Rating: Effective Techniques for Measuring Network Adapter Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-after-connection-failures-in-windows/"><u>Reconnecting to EA Servers After Connection Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-cpu-peaks-with-the-help-of-windows-rm-insights/"><u>Reduce CPU Peaks with the Help of Windows RM Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-internet-connectivity-issues-in-windows-11/"><u>Resolving Internet Connectivity Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidia-control-panel-save-issue/"><u>Resolving Nvidia Control Panel Save Issue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safe-and-effective-fitness-plans-from-gpt/"><u>Safe and Effective Fitness Plans From GPT</u></a></li>
<li><a href="https://windows11.techidaily.com/shielding-windows-key-tactics-for-uac-protection/"><u>Shielding Windows: Key Tactics for UAC Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-with-easy-steps-surface-pcs-version-enhancement-guide/"><u>Smooth Transition with Easy Steps: Surface PCs' Version Enhancement Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solution-guide-why-are-my-headphones-not-working-with-windows-10/"><u>Solution Guide: Why Are My Headphones Not Working with Windows 10?</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-xboxs-dead-end-road-error-on-modern-os/"><u>Steering Clear of Xbox's Dead-End Road Error on Modern OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-revive-non-launching-obs-on-windows/"><u>Steps to Revive Non-Launching OBS on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correctly-handle-windows-update-failure-error-0x80070003/"><u>Strategies to Correctly Handle Windows Update Failure (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-memory-monster-edge-webview2-troubleshooting/"><u>Taming the Memory Monster: Edge WebView2 Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-choosing-top-fps-counter-software-for-windows-11/"><u>The Essential Guide to Choosing Top FPS Counter Software for Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-list-8-crypto-trading-bots-with-chatgpt-integration/"><u>The Ultimate List: 8 Crypto Trading Bots with ChatGPT Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-notification-blockade-from-phone-link/"><u>Unblocking Windows Notification Blockade From Phone Link</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/visuals-that-convert-mastering-the-art-of-video-marketing-on-insta/"><u>Visuals That Convert  Mastering the Art of Video Marketing on Insta</u></a></li>
<li><a href="https://windows11.techidaily.com/win-over-frozen-exe-files-on-your-computer/"><u>Win Over Frozen Exe Files on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-restricted-interface-an-overview/"><u>Windows 11'S Restricted Interface: An Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-startup-guide-navigating-accessibility-features/"><u>Windows Startup Guide: Navigating Accessibility Features</u></a></li>
<li><a href="https://technical-tips.techidaily.com/your-micromobility-companion-important-dates-fresh-updates-and-hidden-trends/"><u>Your Micromobility Companion: Important Dates, Fresh Updates & Hidden Trends</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>