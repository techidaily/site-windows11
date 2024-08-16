---
title: Setting New Reset Limit on Account Lockouts in Windows 10/11
date: 2024-08-15T15:25:11.695Z
updated: 2024-08-16T15:25:11.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
excerpt: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
keywords: WinLockResetLimit,ResetWindowsLock,PCAccountLockNew,UpdateWindowsLocks,ChangeLockTimeWin,SetLockTimeoutWin,AdjustPCLockPeriod
thumbnail: https://thmb.techidaily.com/971a75711e8320cab50ce3d6d3f20ecd50a3ca9874f23293eacb87d6417f00bb.jpg
---

## Setting New Reset Limit on Account Lockouts in Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-complete-digest-exploring-google-podcast-apps-essence/"><u>[New] 2024 Approved  Complete Digest  Exploring Google Podcast App's Essence</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-frolic-in-fun-the-best-comedy-centric-concepts-for-shorter-videos/"><u>[New] 2024 Approved  Frolic in Fun  The Best Comedy-Centric Concepts for Shorter Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fine-tune-your-virtual-interaction-with-close-up-google-meet-tips/"><u>[New] Fine-Tune Your Virtual Interaction with Close-Up Google Meet Tips</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-taking-twitter-videos-from-regular-to-high-definition/"><u>[New] In 2024, Taking Twitter Videos From Regular to High-Definition</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-vibrant-video-vibes-merging-melodies-with-media/"><u>[New] Vibrant Video Vibes  Merging Melodies with Media</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-authenticity-on-display-video-reviews-role/"><u>[Updated] 2024 Approved  Authenticity on Display  Video Reviews' Role</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-capture-your-gameplay-essential-webcams-for-twitch-enthusiasts/"><u>[Updated] 2024 Approved  Capture Your Gameplay  Essential Webcams For Twitch Enthusiasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-use-of-telegram-in-a-step-by-step-approach/"><u>[Updated] Mastering the Use of Telegram in a Step-by-Step Approach</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-navigate-through-group-sharing-options-on-messenger/"><u>[Updated] Navigate Through Group Sharing Options on Messenger</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unlocking-tiktoks-photoshop-magic-effortlessly/"><u>[Updated] Unlocking TikTok's Photoshop Magic Effortlessly</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-visual-excellence-roundup-top-6-high-definition-dslrs-for-2024/"><u>[Updated] Visual Excellence Roundup  Top 6 High-Definition DSLRs for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-screenmaster-review-the-latest-in-tech-capture/"><u>2024 Approved  ScreenMaster Review  The Latest in Tech Capture</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-fundamentals-of-human-interface-recognition/"><u>2024 Approved  The Fundamentals of Human Interface Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-adjust-the-mouse-double-click-speed-on-windows/"><u>3 Ways to Adjust the Mouse Double-Click Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/activatedeactivate-smartscreen-filter-on-windows-11/"><u>Activate/Deactivate SmartScreen Filter on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-correcting-windows-security-faults-in-windows-11/"><u>Avoiding and Correcting Windows Security Faults in Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-video-chatting-tools-for-remote-team-interactions/"><u>Best Video Chatting Tools for Remote Team Interactions</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-to-maximize-windows-ram/"><u>Breaking Down Barriers to Maximize Windows' RAM</u></a></li>
<li><a href="https://screen-capture.techidaily.com/budding-builders-simple-stylish-mc-habitats/"><u>Budding Builders  Simple, Stylish MC Habitats</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cutting-edge-software-transform-and-tweet-videos/"><u>Cutting-Edge Software  Transform and Tweet Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-error-messages-post-installed-application-failure/"><u>Deciphering Error Messages Post Installed Application Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-editing-skills-mastering-jumps-and-pastes/"><u>Elevate Editing Skills: Mastering Jumps & Pastes</u></a></li>
<li><a href="https://article-helps.techidaily.com/expert-analysis-vita-video-editor-full-insight-for-2024/"><u>Expert Analysis  Vita Video Editor - Full Insight for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/film-enhancements-15-best-luts-to-boost-gopro-cinematography/"><u>Film Enhancements  15 Best LUTs to Boost GoPro Cinematography</u></a></li>
<li><a href="https://driver-download.techidaily.com/find-and-install-the-best-hp-deskjet-2755e-drivers-for-optimal-windows-performance/"><u>Find and Install the Best HP Deskjet 2755E Drivers for Optimal Windows Performance</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-v29e-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Vivo V29e Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-wordpad-in-windows/"><u>How to Open WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-mb-service-connections-problem-on-win11-pc/"><u>How to Overcome MB Service Connections Problem on Win11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-cannot-link-with-nvidia-in-windows-11/"><u>How to Rectify Cannot Link with NVIDIA in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-mount-and-blade-2-bannerlord-performance-issues-and-crashes/"><u>How to Resolve Mount & Blade 2: Bannerlord Performance Issues and Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-resolving-directdraw-failures-on-windows-1011/"><u>Immediate Actions for Resolving DirectDraw Failures on Windows 10/11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-adding-panoramic-movement-a-camtasa-guide-to-ken-burns/"><u>In 2024, Adding Panoramic Movement  A Camtasa Guide to Ken Burns</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-icloud-unlocker-download-unlock-icloud-lock-for-your-iphone-se-2022-by-drfone-ios/"><u>In 2024, iCloud Unlocker Download Unlock iCloud Lock for your iPhone SE (2022)</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-uniting-upskill-utopia/"><u>In 2024, Ultimate Uniting Upskill Utopia</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-how-to-reach-windowsstore-folder/"><u>Inside Look: How To Reach WindowsStore Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/lowering-gameplay-stress-reducing-cpu-load-while-playing/"><u>Lowering Gameplay Stress: Reducing CPU Load While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-efficiency-the-5-uptime-test-routines/"><u>Maximizing Windows 11 Efficiency: The 5 Uptime Test Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-icon-position-restoration-in-windows/"><u>Method for Icon Position Restoration in WIndows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-landscape-of-android-and-windows-file-sharing/"><u>Navigating the Landscape of Android & Windows File Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-frustration-quick-fixes-for-windows-11-woes/"><u>No More Frustration! Quick Fixes for Windows 11 Woes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/no-phone-number-necessary-step-by-step-guide-to-signing-up-on-chatgpt-telegram-and-more/"><u>No-Phone-Number Necessary: Step-by-Step Guide to Signing Up on ChatGPT, Telegram & More</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-screen-disruptions-secure-smooth-play-on-w11-with-sonic-frontiers/"><u>Overcoming Screen Disruptions: Secure Smooth Play on W11 with Sonic Frontiers</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-management-windows-folders-restricted-mode-setup/"><u>Secure File Management: Windows Folders Restricted Mode Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-reclaiming-standard-windows-11-search-preferences/"><u>Step-by-Step: Reclaiming Standard Windows 11 Search Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-fixing-steam-file-connections-issue/"><u>Strategies for Fixing Steam File Connections Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-windows-welcome-cant-read-fingers/"><u>Tackling Error: Windows Welcome Can't Read Fingers</u></a></li>
<li><a href="https://windows11.techidaily.com/taking-flight-with-windows-accessibility-novice-style/"><u>Taking Flight with Windows Accessibility, Novice Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-best-way-to-setup-games-on-the-windows-xbox-app/"><u>The Best Way to Setup Games on the Windows Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-9-truths-about-why-pc-computers-win-over-macos-9/"><u>The Top 9 Truths About Why PC Computers Win over MacOS (#9)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-ranked-4k-screen-recorders-summarized-for-2024/"><u>Top-Ranked 4K Screen Recorders Summarized for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-inadequate-system-resources-complete-guide-to-repair-services/"><u>Troubleshooting Inadequate System Resources - Complete Guide to Repair Services</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-impact-of-ntfs-compression-on-data-saving/"><u>Understanding the Impact of NTFS Compression on Data Saving</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-powertoys-worldwide-mouse-capabilities/"><u>Unlock PowerToy's Worldwide Mouse Capabilities</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlock-the-potential-of-siri-solutions-for-when-suggestions-fail-to-appear/"><u>Unlock the Potential of Siri: Solutions for When Suggestions Fail to Appear</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-internet-options/"><u>Unlocking Windows 11 Internet Options</u></a></li>
<li><a href="https://win-solutions.techidaily.com/virtual-fixes-overcoming-common-challenges-in-getting-vrchat-up-and-running-smoothly/"><u>Virtual Fixes: Overcoming Common Challenges in Getting VRChat Up and Running Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-your-ideas-type-them-out-with-openais-whisper/"><u>Voice Your Ideas, Type Them Out With OpenAI’s Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tackle-icons-not-aligned/"><u>Win 11: Tackle Icons Not Aligned</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
</ul></div>
