---
title: "Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
date: 2024-09-09T12:12:20.146Z
updated: 2024-09-10T12:12:20.146Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
excerpt: "This Article Describes Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
keywords: WinUserRightsEnhance,UserAccessModifyWin,AdjustWinPermsGuide,PrivilegeCustomizeWin,ElevateWindowsUsers,AccessControlWinOS,StandardUserPrivilege
thumbnail: https://thmb.techidaily.com/5a6b81e19407a604be22bf69df443b0f8b7b5bc4d3841b542775d6677ac13b8e.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-macwebcam-tutorial-filming-basics-decoded/"><u>[New] MacWebCam Tutorial Filming Basics Decoded</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-syncing-socials-a-step-by-step-guide-to-linking-instagram-and-tiktok/"><u>[New] Syncing Socials A Step-by-Step Guide to Linking Instagram and TikTok</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nique-channels-generating-top-notch-video-naming/"><u>[New] Unique Channels Generating Top-Notch Video Naming</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-mastering-screencapture-essential-techniques-for-2024/"><u>[Updated] Mastering ScreenCapture Essential Techniques for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-social-media-excellence-a-practical-approach/"><u>2024 Approved Social Media Excellence A Practical Approach</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-powerful-video-titles-and-sizes-for-2024/"><u>Crafting Powerful Video Titles & Sizes for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-veiled-content-on-youtube-for-2024/"><u>Decoding Veiled Content on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-erase-dark-steam-display/"><u>Expert Advice to Erase Dark Steam Display</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-management-issues-5-approaches-with-windows-11-focus/"><u>Fixing Management Issues: 5 Approaches with Windows 11 Focus</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-location-on-facebook-dating-for-your-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-audio-error-0xc00d36b4-in-windows-11-and-11/"><u>How to Fix the Audio Error 0Xc00d36b4 in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-misaligned-stickies-on-windows-11/"><u>How to Rectify Misaligned Stickies on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-15-pro-max-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, iPhone 15 Pro Max Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-navigating-your-first-stride-into-snapseed-land/"><u>In 2024, Navigating Your First Stride Into Snapseed Land</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-vivo-y100t-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Vivo Y100t Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-desktops-analyzing-wsl-role/"><u>Linux Desktops: Analyzing WSL Role?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-lately-opened-files-in-windows-os/"><u>Master Lately Opened Files in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-alleviating-power-management-issues-on-windows-devices/"><u>Methods for Alleviating Power Management Issues on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-remove-access-error-in-windows-file-explorer/"><u>Methods to Remove Access Error in Windows File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-alerts-and-reminders/"><u>Muting Windows Update Alerts and Reminders</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-time-warp-your-videos-top-10-free-speed-adjustment-apps-for-mobile-for-2024/"><u>New Time Warp Your Videos Top 10 Free Speed Adjustment Apps for Mobile for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc00000f-on-pc-a-step-by-step-guide/"><u>Overcoming 0Xc00000f on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-updating-problem-error-x8019/"><u>Overcoming Updating Problem: Error X8019</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-taskbar-alignment-with-win-11-tips/"><u>Perfect Taskbar Alignment with Win 11 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-fixing-erroneous-game-status-in-discord-pc/"><u>Quick Guide: Fixing Erroneous Game Status in Discord (PC)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rectified-initialization-mishap-of-the-display-engine-with-latest-fixes-year-2pressure-on-rendering-engines-we-can-create-titles-that-communicate-a-successf111/"><u>Rectified Initialization Mishap of the Display Engine with Latest Fixes (Year 2Pressure on Rendering Engines, We Can Create Titles that Communicate a Successful Resolution to an Initial Problem While Still Hinting at Improvements or Fixes Made</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-organization-owned-chromeedge-issues-on-desktops/"><u>Resolving Organization-Owned Chrome/Edge Issues on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/retrace-to-original-directory-view-in-windows-11/"><u>Retrace to Original Directory View in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-dotnet-top-5-reparations-for-pcs-max-156/"><u>Reviving DotNet: Top 5 Reparations for PCs (Max 156)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-content-production-with-these-8-cutting-edge-ai-tools/"><u>Revolutionize Your Content Production with These 8 Cutting-Edge AI Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-your-windows-11-fix-system-call-failed/"><u>Saving Your Windows 11: Fix System Call Failed</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-save-big-keys-fans-black-friday-treat-for-windows-11/"><u>Secure Your System, Save Big - Keys Fan's Black Friday Treat for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips-40/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips (40)</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-onedrive-sync-fails-in-windows-os/"><u>Solutions for OneDrive Sync Fails in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-fixed-no-change-in-your-windows-wallpaper/"><u>Stay Fixed: No Change in Your Windows Wallpaper</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-cooling-computers-running-hot-w11/"><u>Steps for Cooling Computers Running Hot W11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-display-with-speed-meter-widget/"><u>Streamline Your Display with Speed Meter Widget</u></a></li>
<li><a href="https://screen-recording.techidaily.com/superior-emulator-lineup-for-playing-retro-ps1-classics/"><u>Superior Emulator Lineup for Playing Retro PS1 Classics</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-shimmering-window-title-bar-in-win11/"><u>Tips for A Shimmering Window Title Bar in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-your-windows-xbox-app-woes/"><u>Troubleshoot Your Windows Xbox App Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-a-non-operational-media-player-in-windows-11/"><u>Troubleshooting a Non-Operational Media Player in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-11-how-to-resolve-elevation-error-740/"><u>Unblocking Windows 11: How to Resolve Elevation Error #740</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-0x8007007e-windows-error/"><u>Understanding and Resolving 0X8007007E Windows Error</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-g2-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Vivo G2 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-music-library-tackling-w10w11-errors/"><u>Unlocking Your Music Library: Tackling W10/W11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/ways-to-deal-with-laptop-screen-tint-issue/"><u>Ways to Deal with Laptop Screen Tint Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-navigation-nuances-secrets-to-effectively-copying-files-locations-6-strategies/"><u>Windows Navigation Nuances: Secrets to Effectively Copying Files' Locations (6 Strategies)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>