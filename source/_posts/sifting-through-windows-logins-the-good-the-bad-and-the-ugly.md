---
title: "Sifting Through Windows Logins: The Good, The Bad & The Ugly"
date: 2024-08-31T22:11:53.539Z
updated: 2024-09-01T22:11:53.539Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sifting Through Windows Logins: The Good, The Bad & The Ugly"
excerpt: "This Article Describes Sifting Through Windows Logins: The Good, The Bad & The Ugly"
keywords: Login Troubleshooting Tips,Analyzing User Account Activity,Windows Security Checklist,Access Logs Insight,Safe Login Practices,Detecting Unauthorized Windows Users,Ugly Login Patterns Identification
thumbnail: https://thmb.techidaily.com/43a1f72d8140b4852b3ec1b168bf1a5fdf9e93b16a9fa8da6c72d7e20d694e32.jpg
---

## Sifting Through Windows Logins: The Good, The Bad & The Ugly

 Windows lets you create multiple user accounts to let multiple users use a single computer. But what if you suspect someone to have accessed your PC or user account without your knowledge?

 While physically monitoring your computer all the time is not feasible for most people, the built-in Windows log utility, Event Viewer, can reveal the recent activities on your computer, including login attempts. Here we show you how to audit failed and successful login attempts in Windows using Event Viewer and other methods.

## How to Enable Logon Auditing via Group Policy Editor

 You need to enable logon auditing in Group Policy Editor to be able to view login audit in Event Viewer. While this feature may be enabled by default on some computers, you can also enable logon auditing manually by following these steps.

 Note that Group Policy Editor is only available on the Pro, Edu, and Enterprise edition of the Windows OS. If you are on the Home edition, follow our guide to[enable gpedit in the Windows home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Note that if you don't configure your Group Policy for Logon Auditing, you can only view the successful login attempts in Event Viewer.

 Once you have the Group Policy Editor enabled, follow these steps to enable logon auditing:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open the**Group Policy Editor.**
3. Next, navigate to the following location:  
`Computer Configuration > Windows Settings > Security Settings > Local Policies > Audit Policy`
4. In the right pane, right-click on**Audit logon events** and select**Properties** .  
![group policy editor audit logon events properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties.jpg)
5. In the**Properties** dialog, select**Success** and**Failure** options under the**Audit these attempts** section.  
![group policy editor audit logon events properties enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties-enable.jpg)
6. Click**Apply** and**OK** to save the changes.

 Close Group Policy Editor and move to the next set of steps to view login attempts in Event Viewer.

## How to View Failed and Successful Login Attempts in Event Viewer

 The[Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

 Follow these steps to view failed and successful login attempts in Windows:

1. Press the**Win key** and type**event viewer.** Alternatively, click on**Search** in the taskbar and type**event viewer.**
2. Click on**Event Viewer** from the search result to open it.
3. In the left pane, expand the**Windows Logs** section.  
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 Similarly, for failed login attempts, review**Event ID 4625** . In the**Properties** dialog, you can find reasons for the failed login attempt and the affected user account. If you find multiple instances of unsuccessful attempts, consider learning[how to limit the number of failed login attempts to protect your Windows PC](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) .

 Below is the list of all nine**Logon Types** for logon events that you may encounter reviewing login events in Event Viewer:

| **Logon Type** | **Description**                                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Logon Type 2   | A local user logged on to this computer.                                                                                                          |
| Logon Type 3   | A user logged on to this computer from the network.                                                                                               |
| Logon Type 4   | Batch logon type without user intervention – Scheduled Tasks, etc.                                                                                |
| Logon Type 5   | Logon by system service started by Service Control Manager – Most common type                                                                     |
| Logon Type 7   | System unlocked by a local account user                                                                                                           |
| Logon Type 8   | NetworkClearText - Logon attempted over the network where the password was sent as clear text.                                                    |
| Logon Type 9   | NewCredentials – triggered when a user uses the RunAs command with the /netonly option to start a program.                                        |
| Logon Type 10  | RemoteInteractive – Generated when a computer is accessed via a remote access tool such as Remote Desktop Connection.                             |
| Logon Type 11  | CachedInteractive – When the user logged on to the computer via console using the cached credentials when the domain controller is not available. |

## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## Viewing Failed and Successful Login Attempts in Windows

 If you suspect someone to have logged in to your PC, the Event Viewer will likely catch and record the attempt. For this to work, you must enable the Logon Auditing policy in Group Policy Editor. You can also use Command Prompt to view a specific user's login history.

 That said, anyone who knows their way around Event Viewer can easily clear the logs. So, if anything, beefing up your Windows computer security is the best way to prevent unauthorized access. You can begin by limiting the number of failed login attempts on your Windows PC.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-non-retweeted-video-tweet-guide-for-iphone-and-android-users/"><u>[New] 2024 Approved  Non-Retweeted Video Tweet Guide for iPhone & Android Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-rage-quarters-and-swords-nintendo-switch-fighting-classics/"><u>[New] 2024 Approved  Rage Quarters & Swords  Nintendo Switch Fighting Classics</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-sharing-twitter-video-feeds-via-facebook-platform/"><u>[New] 2024 Approved  Sharing Twitter Video Feeds via Facebook Platform</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-boost-youtube-videos-appeal-3-ways-to-incorporate-neon-borders/"><u>[New] In 2024, Boost YouTube Videos' Appeal - 3 Ways to Incorporate Neon Borders</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-jumping-into-the-virtual-discussions-via-google/"><u>[New] Jumping Into the Virtual Discussions via Google</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-metaverses-funny-bone-generating-hitsome-online-jokes/"><u>[New] The Metaverse's Funny Bone  Generating Hitsome Online Jokes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-vidharvest-instagram-live-fb-for-2024/"><u>[New] VidHarvest  Instagram Live (FB) for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-movavi-pro-video-review-the-new-standard/"><u>[Updated] 2024 Approved  Movavi Pro Video Review – The New Standard</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pinnacle-of-pc-clicker-fun-top-12-must-try-games/"><u>[Updated] In 2024, Pinnacle of PC Clicker Fun  Top 12 Must-Try Games</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-streamline-cinematography-processes-using-obss-versatile-lut-tools-and-downloads-for-2024/"><u>[Updated] Streamline Cinematography Processes Using OBS's Versatile LUT Tools and Downloads for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-pioneering-color-grading-with-3d-luts/"><u>2024 Approved  Pioneering Color Grading with 3D LUTs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/auditory-storytelling-in-cinematic-openings/"><u>Auditory Storytelling in Cinematic Openings</u></a></li>
<li><a href="https://solve-hot.techidaily.com/cookiebot-enhanced-enrich-your-website-with-smart-seo-solutions/"><u>Cookiebot-Enhanced: Enrich Your Website with Smart SEO Solutions</u></a></li>
<li><a href="https://blog-min.techidaily.com/discover-how-windows-11s-enhanced-notepad-utilizes-ai-technology-for-code-explanation-insights/"><u>Discover How Windows 11'S Enhanced Notepad Utilizes AI Technology for Code Explanation Insights</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earnings-insights-for-video-content-surpassing-1-million-views/"><u>Earnings Insights for Video Content Surpassing 1 Million Views</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-vivo-v29-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Vivo V29 Pattern Lock Screen</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-apple-iphone-xs-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From Apple iPhone XS? Heres the Best Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-lol-launch-lag/"><u>Guide to Overcoming LOL Launch Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-postpone-windows-10-shutdown-during-active-processes/"><u>Guide to Postpone Windows 10 Shutdown During Active Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-sign-off-strangers-on-windows-11/"><u>Guide to Sign Off Strangers on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/has-ai-surpassed-the-old-standards-discovering-five-cutting-edge-alternatives-to-the-turing-test/"><u>Has AI Surpassed The Old Standards?: Discovering Five Cutting-Edge Alternatives to the Turing Test</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-10-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 10 & 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-xs-max-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone XS Max With 7 Methods</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-master-the-art-of-seamless-video-compatibility/"><u>In 2024, Master the Art of Seamless Video Compatibility</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/including-d-drive-paths-in-file-explorer-list/"><u>Including D: Drive Paths in File Explorer List</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/lost-on-snapchat-discover-how-you-can-bring-back-your-dormant-profile-to-life/"><u>Lost on Snapchat? Discover How You Can Bring Back Your Dormant Profile to Life</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vboxs-security-settings-secure-boot-and-tpm-management/"><u>Mastering VBox's Security Settings: Secure Boot & TPM Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-default-task-manager-viewport-in-win11/"><u>Modify Default Task Manager Viewport in Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-keyword-optimization-in-podcast-seo/"><u>Navigating Keyword Optimization in Podcast SEO</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-pc-delays-in-warhammer-boltguns-quest-for-precision/"><u>Overcome PC Delays in Warhammer: Boltgun's Quest for Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-update-issue-windows-11-error-code-0x800f0922/"><u>Overcome Update Issue: Windows 11 Error Code 0X800F0922</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-the-challenge-of-a-missing-ntldr-file-in-windows/"><u>Overcoming the Challenge of a Missing NTLDR File in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-usb-device-errors-on-windows-pcs/"><u>Overcoming USB Device Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-overheat-avoidance-bios-tutorial-for-win-users/"><u>Personalized Overheat Avoidance: BIOS Tutorial for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-common-winx-update-error-0x80246007/"><u>Quick Fixes for Common WinX Update Error: 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-composure-post-high-living-days-for-windows-users/"><u>Regaining Composure Post-High Living Days, for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-operations-at-low-cost-leverage-w11-pro-key/"><u>Smooth Operations at Low Cost: Leverage W11 Pro Key</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-securing-computer-against-unauthorized-usb-clip-attacks/"><u>Steps for Securing Computer Against Unauthorized USB Clip Attacks</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-spontaneous-scrolls-a-winworlders-guide/"><u>Stop Spontaneous Scrolls: A Winworlder's Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/stop-unwanted-airpod-connection-switches-among-various-apple-devices-a-step-by-step-guide/"><u>Stop Unwanted AirPod Connection Switches Among Various Apple Devices - A Step-By-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-iphone-photographic-transfer-issues-on-w11-systems/"><u>Strategies to Overcome iPhone Photographic Transfer Issues on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-zero-x-error-in-the-microsoft-email-on-windows-11/"><u>Strategies to Overcome Zero X Error in the Microsoft Email on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-pc-toggle-folders-visibility-windows-11/"><u>Streamline Your PC: Toggle Folders Visibility (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthen-your-safe-space-top-5-corrections-in-windows-features/"><u>Strengthen Your Safe Space: Top 5 Corrections in Windows Features</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-failures-error-x712/"><u>Tackling Windows Update Failures: Error X712</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-spark-10-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Spark 10 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win1011-audio-error-xc00d36b4/"><u>Troubleshooting Win10/11 Audio Error XC00D36B4</u></a></li>
<li><a href="https://windows11.techidaily.com/unique-apps-for-a-stylish-windows-clock-display/"><u>Unique Apps for a Stylish Windows Clock Display</u></a></li>
<li><a href="https://windows11.techidaily.com/unjamming-windows-tackling-access-issues-head-on/"><u>Unjamming Windows: Tackling Access Issues Head-On</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-boundaries-personal-growth-under-microphone-and-camera-censorship/"><u>Unseen Boundaries: Personal Growth Under Microphone & Camera Censorship</u></a></li>
<li><a href="https://network-issues.techidaily.com/video-streaming-problems-on-windows-11-after-upgrade-solved/"><u>Video Streaming Problems on Windows 11 After Upgrade [Solved]</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-vanishing-icons-restoration-strategies/"><u>Win 11'S Vanishing Icons - Restoration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-hacks-swift-recovery-of-synapse-functions/"><u>Windows 11/10 Hacks: Swift Recovery of Synapse Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-both-wi-fi-and-ethernet-connections-on-your-computer/"><u>Winning with Both Wi-Fi & Ethernet Connections on Your Computer</u></a></li>
</ul></div>
