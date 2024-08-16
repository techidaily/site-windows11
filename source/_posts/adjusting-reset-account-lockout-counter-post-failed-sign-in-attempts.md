---
title: Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
date: 2024-08-15T15:49:28.252Z
updated: 2024-08-16T15:49:28.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
excerpt: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
keywords: Sign-In Limits Adjustment,Account Lockout Reduce,Failed Login Policy Changes,Reset Counter Post-Sign In,Managing User Lockouts,Password Attempt Limit Update,Preventing Account Blocks
thumbnail: https://thmb.techidaily.com/90e284fb29c37a4c0c2a2e6970ee3fa6b56745fa434982e234c62e6bb83237e0.jpg
---

## Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-craft-a-memorable-youtube-channel-brand-for-more-viewers/"><u>[New] 2024 Approved  Craft a Memorable YouTube Channel Brand for More Viewers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/isabling-youtube-ads-across-chrome-firefox-android-and-ios-browsers/"><u>[New] Disabling YouTube Ads Across Chrome, Firefox, Android & iOS Browsers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unlocking-creative-potential-with-top-rated-gif-makers/"><u>[New] Unlocking Creative Potential with Top-Rated GIF Makers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-experts-choice-aspertronics-for-phones/"><u>[Updated] In 2024, Expert's Choice  Aspertronics For Phones</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-direct-platform-comparison-choosing-between-obs-and-twitch-studio/"><u>2024 Approved  Direct Platform Comparison  Choosing Between OBS & Twitch Studio</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-how-to-become-an-instagram-influencer-a-complete-guide/"><u>2024 Approved  How to Become an Instagram Influencer  A Complete Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimize-sound-speed-with-these-essential-apps/"><u>2024 Approved  Optimize Sound Speed with These Essential Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-top-2-ios-video-editors-compared-cameo-versus-filmorago/"><u>2024 Approved  Top 2 iOS Video Editors Compared  Cameo Versus FilmoraGo</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-vivo-y78t-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-win11-taskbar-icon-dimensions/"><u>Adjusting Win11 Taskbar Icon Dimensions</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-finding-out-charge-status-win-1011/"><u>Advanced Techniques: Finding Out Charge Status (Win 10/11)</u></a></li>
<li><a href="https://windows11.techidaily.com/battle-of-the-packagers-chocolatey-or-wm-on-windows-pcs/"><u>Battle of the Packagers: Chocolatey or WM on Windows PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/capturing-chats-storing-gh-live-sessions-for-2024/"><u>Capturing Chats  Storing GH Live Sessions for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/freeloading-futures-with-ae-creative-tools/"><u>Freeloading Futures with AE Creative Tools</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-latest-updates-for-your-razer-devices-across-multiple-windows-versions/"><u>Get Latest Updates for Your Razer Devices Across Multiple Windows Versions</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-counter-facebooks-instantaneous-deletion-of-videos/"><u>How to Counter Facebook's Instantaneous Deletion of Videos</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-realme-11-proplus-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Realme 11 Pro+ in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-wordpad-in-windows/"><u>How to Open WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-mb-service-connections-problem-on-win11-pc/"><u>How to Overcome MB Service Connections Problem on Win11 PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How to Simulate GPS Movement in AR games On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-no-cost-audio-treasure-trove-for-video-endings/"><u>In 2024, No-Cost Audio Treasure Trove for Video Endings</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-xiaomi-redmi-a2-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Xiaomi Redmi A2? Look No Further | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-storage-with-onedrive-rearrange-for-win-11/"><u>Managing Storage with OneDrive – Rearrange for Win 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-installation-of-enhanced-ai-features-in-chatgpt/"><u>Mastering the Installation of Enhanced AI Features in ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-solo-sound-output-in-windows-audio-device/"><u>Mending Solo Sound Output in Windows Audio Device</u></a></li>
<li><a href="https://extra-support.techidaily.com/musical-notes-on-call-creating-and-cutting-tamil-alert-songs-for-2024/"><u>Musical Notes on Call  Creating & Cutting Tamil Alert Songs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-notifications/"><u>Muting Windows Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-computer-no-need-for-windows-11-upgrades/"><u>Optimize Your Computer: No Need for Windows 11 Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-chromes-file-uploading-frustrations-on-a-pc/"><u>Overcome Chrome's File Uploading Frustrations on a PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/precision-in-digital-imaging-a-professionals-approach/"><u>Precision in Digital Imaging  A Professional's Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-lost-steam-games-symbols/"><u>Preventing and Fixing Lost Steam Games Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-connection-issues-with-googles-nearby-sharing/"><u>Resolving Connection Issues with Google's Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-microsofts-phone-tethering-for-windows-11-users/"><u>Revisiting Microsoft's Phone Tethering for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-disabling-windows-wi-fi-broadcast/"><u>Stealth Mode: Disabling Windows Wi-Fi Broadcast</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-absent-app-in-windows-filesystem/"><u>Strategies to Fix Absent App in Windows Filesystem</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-and-fix-windows-error-code-0xc00000f/"><u>Strategies to Prevent & Fix Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-symphony-of-silence-starting-with-a-soft-fade-in/"><u>The Symphony of Silence  Starting with a Soft Fade In</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-4-must-try-artificial-intelligence-story-creation-tools/"><u>Top 4 Must-Try Artificial Intelligence Story Creation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-for-optimal-clipchamp-functionality/"><u>Unlocking Windows 11 for Optimal ClipChamp Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
</ul></div>
