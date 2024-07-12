---
title: Revising Account Lockout Count After Multiple Login Failures in Windows 11
date: 2024-07-11T21:13:16.876Z
updated: 2024-07-12T21:13:16.876Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
excerpt: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
keywords: Windows 11 Login Issues,Account Lockout Remedies,Manage Failed Logins,Reduce Lockout Count,Win11 Security Settings,Prevent User Lockouts,Optimize Login Attempts
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Revising Account Lockout Count After Multiple Login Failures in Windows 11

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

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

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
<li><a href="https://windows11.techidaily.com/unfreezing-windows-updates-top-6-strategies-to-resolve-sticking-issues/"><u>Unfreezing Windows Updates: Top 6 Strategies to Resolve Sticking Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/snap-opera-download-into-action-windows-style/"><u>Snap Opera Download Into Action, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-tech-windows-7-product-key-for-11-activation/"><u>Time-Travel Tech: Windows 7 Product Key for 11 Activation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-2023s-top-tweets-the-highest-traffic-watchlist/"><u>[New] 2024 Approved  2023'S Top Tweets  The Highest Traffic Watchlist</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-music-syncing-for-iphones-and-androids-in-fb/"><u>2024 Approved  Music Syncing for iPhones & Androids in FB</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-file-system-woes-on-windows-11/"><u>Navigating File System Woes on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-small-drone-models-today/"><u>2024 Approved  Best Small Drone Models Today</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-googles-augmented-reality-stickers-in-spotlight-a-comparative-analysis/"><u>[New] Google’s Augmented Reality Stickers in Spotlight - A Comparative Analysis</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-35-hilarious-image-editing-software-for-smartphones-and-pcs/"><u>2024 Approved  35 Hilarious Image Editing Software for Smartphones & PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-how-you-use-the-mouse-worldwide-through-powertoys/"><u>Revolutionize How You Use the Mouse Worldwide Through PowerToys</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/flaskful-formula-freaks/"><u>FLASKFUL FORMULA FREAKS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-removing-onedrive-linkage-on-windows-os/"><u>Steps for Removing OneDrive Linkage on Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-charting-the-course-to-prodigy-status-for-ajey-carryminati-for-2024/"><u>[New] Charting the Course to Prodigy Status for Ajey (CarryMinati) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/phase-out-announcement-end-for-windows-781-on-microsoft-platforms/"><u>Phase-Out Announcement: End for Windows 7/8.1 on Microsoft Platforms</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-vivo-x100-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Vivo X100</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-best-matches-ultimate-websites-for-acquiring-snapchat-ringtones/"><u>[New] 2024 Approved  Best Matches  Ultimate Websites for Acquiring Snapchat Ringtones</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-pc-boosters-for-speed-and-efficiency/"><u>Top 5 Windows PC Boosters for Speed and Efficiency</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-alluring-world-of-high-quality-sound-editing-software-advantages-disadvantages-and-competitive-insights/"><u>Updated In 2024, The Alluring World of High-Quality Sound Editing Software Advantages, Disadvantages, and Competitive Insights</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-iphone-shutterbug-secrets-perfecting-reflections-in-water/"><u>In 2024, IPhone Shutterbug Secrets  Perfecting Reflections in Water</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-fraps-for-gamers-a-screen-record-review/"><u>2024 Approved  Fraps for Gamers  A Screen Record Review</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-oppo-a56s-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Oppo A56s 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-s17t-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to S17t Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-battlenet-access-issues-in-windows-1011/"><u>Overcoming Battle.net Access Issues in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/rehabbing-windows-1011s-recycle-bin-crisis-a-step-by-step-guide/"><u>Rehabbing Windows 10/11'S Recycle Bin Crisis: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-network-unreachable-issue/"><u>Overcoming WIN Network Unreachable Issue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-path-to-perfect-presence-on-zoom-platforms/"><u>[New] In 2024, The Path to Perfect Presence on Zoom Platforms</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mandarin-manners-essential-chinese-gratitude-words/"><u>Mandarin Manners: Essential Chinese Gratitude Words</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-breaking-content-buzz-2024/"><u>[New] Breaking Content Buzz 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-wbk-file-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .wbk file free</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-content-restricted-on-pc-a-step-by-step-guide/"><u>Solving Steam Content Restricted on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-detected-network-proxy-settings-in-windows/"><u>Overcoming Non-Detected Network Proxy Settings in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-crack-open-your-marketing-potential-with-these-nine-tactics/"><u>[Updated] Crack Open Your Marketing Potential with These Nine Tactics</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-who-are-tiktoks-gaming-visionaries-for-2024/"><u>[Updated] Who Are TikTok’s Gaming Visionaries for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-top-trends-in-instagram-hashtags-for-enhanced-reach/"><u>In 2024, Top Trends in #Instagram Hashtags for Enhanced Reach</u></a></li>
<li><a href="https://windows11.techidaily.com/the-9-best-features-in-the-windows-11-february-2023-update/"><u>The 9 Best Features in the Windows 11 February 2023 Update</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/perfecting-yt-aesthetics-in-depth-guide-to-banner-and-art-sizing-for-2024/"><u>Perfecting YT Aesthetics  In-Depth Guide to Banner & Art Sizing for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-the-genius-of-face-editing-apps-for-smartphones/"><u>[Updated] Explore the Genius of Face-Editing Apps for Smartphones</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-fbm-issues-on-your-pc-screen/"><u>Unblocking FBM Issues on Your PC Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-4-ways-to-stop-pc-update-notifications/"><u>Quick Fixes: 4 Ways to Stop PC Update Notifications</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-clearing-up-opaque-video-views-on-youtube/"><u>[New] In 2024, Clearing Up Opaque Video Views on YouTube</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-dynamic-duo-shots-perfecting-youtube-video-splitting/"><u>[New] Dynamic Duo Shots  Perfecting YouTube Video Splitting</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-apple-iphone-7-plus-imei-checker-by-drfone-ios/"><u>In 2024, Best Free Apple iPhone 7 Plus IMEI Checker</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-the-art-of-effective-spotify-promotion/"><u>[Updated] Mastering the Art of Effective Spotify Promotion</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/3-ways-add-captions-to-instagram-videos-for-2024/"><u>[3 Ways] Add Captions to Instagram Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-for-ditching-microsofts-store/"><u>Three Steps for Ditching Microsoft's Store</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-labyrinth-of-updater-0x800f080a-on-windows/"><u>Navigating Through the Labyrinth of Updater 0X800F080A on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-gpu-potential-in-windows-10-and-11-via-vram/"><u>Unleashing Full GPU Potential in Windows 10 & 11 via VRAM</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-software-management-with-new-context-menu-addition/"><u>Simplify Software Management with New Context Menu Addition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-stream-google-meet-directly-on-youtube-with-these-tips/"><u>[Updated] Stream Google Meet Directly on YouTube with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony!</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-10-shutdown-keep-programs-open/"><u>Slowing Down Windows 10 Shutdown: Keep Programs Open</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-window-management-feature-in-windows-11-end-task/"><u>How to Engage Window Management Feature in Windows 11 (End Task)</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-mac-video-editing-made-easy-with-mkvtoolnix-2023-update-for-2024/"><u>New Mac Video Editing Made Easy with MKVtoolnix 2023 Update for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-desktop-spaces-preset-program-dimensions-on-win11/"><u>Optimizing Desktop Spaces: Preset Program Dimensions on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-directx-setup-failures-on-pc/"><u>Mending DirectX Setup Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-law-filter-mechanics-and-output/"><u>Unraveling the Mystery of Window's LAW Filter Mechanics and Output</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unseen-wi-fi-in-windows/"><u>The Art of Unseen Wi-Fi in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-a-disconnected-printer-issue/"><u>Navigating a Disconnected Printer Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-instructions-for-software-icons-on-desktop-menu/"><u>Tailored Instructions for Software Icons on Desktop Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-organization-made-simple/"><u>Windows Icon Organization Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-the-hover-over-sensitivity-and-visibility-in-windows-11/"><u>Tailoring the Hover Over Sensitivity and Visibility in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-student-laptop-asus-s15-oled-in-focus/"><u>The Ultimate Student Laptop: ASUS S15 OLED in Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/win-1011-printer-uninstallation-a-quick-and-direct-guide/"><u>Win 10/11 Printer Uninstallation: A Quick & Direct Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-permission-problems-during-windows-1011-installer-errors/"><u>Remedying Permission Problems During Windows 10/11 Installer Errors</u></a></li>
</ul></div>
