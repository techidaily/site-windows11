---
title: Validating or Rejecting Window Login Attempts with Precision
date: 2024-08-27T16:08:03.211Z
updated: 2024-08-28T16:08:03.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Validating or Rejecting Window Login Attempts with Precision
excerpt: This Article Describes Validating or Rejecting Window Login Attempts with Precision
keywords: Validate Login Windows,Reject Invalid Logins,Precise Authentication,Check User Credentials,Secure Login Verification,Authenticate Window Entry,Accurate Access Control
thumbnail: https://thmb.techidaily.com/5c0c9eb8f56df5fe4db5872765fea7c0cdfb1d4cf1ab34421179afeae4f509e7.png
---

## Validating or Rejecting Window Login Attempts with Precision

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

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
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
<li><a href="https://youtube-web.techidaily.com/024-approved-democratize-music-distribution-via-social-media/"><u>[New] 2024 Approved  Democratize Music Distribution via Social Media</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-closing-an-outdated-linkedin-profile-a-step-by-step-guide-for-2024/"><u>[New] Closing an Outdated LinkedIn Profile  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ffective-team-videos-boosting-channelnode-growth-rate/"><u>[New] Effective Team Videos  Boosting Channelnode Growth Rate</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-essential-youtube-to-mp3-conversion-apps-reviewed-for-2024/"><u>[New] Essential YouTube to Mp3 Conversion Apps Reviewed for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-live-youtube-streaming-unlocked-beginners-obs-tutorial/"><u>[New] Live Youtube Streaming Unlocked  Beginner's OBS Tutorial</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-effortlessly-journey-to-your-custom-designed-music-library-on-youtube/"><u>[Updated] 2024 Approved  Effortlessly Journey to Your Custom-Designed Music Library on Youtube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-intellect-in-your-hand-the-moto-z2-breakdown/"><u>[Updated] 2024 Approved  Intellect in Your Hand  The Moto Z2 Breakdown</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capturing-the-clouds-advanced-drone-video-techniques/"><u>[Updated] Capturing the Clouds  Advanced Drone Video Techniques</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-green-walls-in-grey-buildings-a-step-towards-eco-cities-for-2024/"><u>[Updated] Green Walls in Grey Buildings  A Step Towards Eco-Cities for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-heimdalls-vigil-gods-clash-in-ragnarok-for-2024/"><u>[Updated] Heimdall's Vigil  Gods Clash in Ragnarok for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-the-dark-and-light-iphone-silhouette-tips/"><u>[Updated] Master the Dark & Light  IPhone Silhouette Tips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-instagram-etiquette-ceasing-connections/"><u>2024 Approved  Instagram Etiquette  Ceasing Connections</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ai-name-magic-selecting-the-best-tools-for-your-podcast-titles/"><u>AI Name Magic  Selecting the Best Tools for Your Podcast Titles</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cinematic-craftsman-corner-qanda-hub-for-2024/"><u>Cinematic Craftsman Corner  Q&A Hub for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-overcoming-outlook-crashing-issues/"><u>Essential Guide: Overcoming Outlook Crashing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-variance-in-offline-versus-online-windows-installation-methods/"><u>Exploring Variance in Offline Versus Online Windows Installation Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-winerror-0x8007043c-on-media-creator/"><u>Guide to Resolving WinError 0X8007043C on Media Creator</u></a></li>
<li><a href="https://windows11.techidaily.com/halting-windows-edge-tab-loads-properly/"><u>Halting Windows Edge Tab Loads Properly</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-window-11-customization-marvels/"><u>Hidden Window 11 Customization Marvels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-evaluate-processor-load-using-task-manager/"><u>How to Correctly Evaluate Processor Load Using Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-device-driver-loading-in-win11/"><u>How to Enable Device Driver Loading in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-sign-in-option-is-disabled-because-of-failed-sign-in-attempts-on-windows/"><u>How to Fix This Sign-In Option Is Disabled Because of Failed Sign-In Attempts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-past-a-non-starting-battlenet-interface/"><u>How to Get Past a Non-Starting Battle.net Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-the-incorrect-token-call-error-on-win11/"><u>How to Rectify the “Incorrect Token Call” Error on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-switch-off-mobility-features-on-win-11/"><u>How To Switch Off Mobility Features on Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-realme-c67-4g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Realme C67 4G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-samsung-galaxy-a25-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Samsung Galaxy A25 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-11-by-drfone-ios/"><u>In 2024, Protecting Your Privacy How To Remove Apple ID From Apple iPhone 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlock-the-secrets-essential-tiktok-video-editing-techniques/"><u>In 2024, Unlock the Secrets  Essential TikTok Video Editing Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-color-secrets-master-the-craft-with-our-tutorial-series/"><u>In 2024, Unveiling Color Secrets - Master the Craft with Our Tutorial Series</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-prodigy-tips-for-windows-photoshop/"><u>Keyboard Prodigy Tips for Windows Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-regaining-win-folder-entry/"><u>Master the Art of Regaining Win Folder Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-cursor-adjustments-on-windows-11-systems/"><u>Masterful Cursor Adjustments on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-heic-jpeg-conversions-on-windows/"><u>Mastering HEIC-JPEG Conversions on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/navigating-through-best-liquid-physics-experiences/"><u>Navigating Through Best Liquid Physics Experiences</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-typing-troubles-addressing-zerox-code-0x80049dd3/"><u>Navigating Through Windows 11 Typing Troubles: Addressing Zerox (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-already-active-issue-on-windows-11/"><u>Overcoming Resource Already Active Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11s-uptime-failure-error-code-0x80246007/"><u>Overcoming Windows 11’S Uptime Failure: Error Code 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-directory-design-mass-folder-formation-strategies-for-windows-1011-users/"><u>Proactive Directory Design: Mass Folder Formation Strategies for Windows 10/11 Users</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-editing-incorporating-jump-cuts-in-video-content-for-2024/"><u>Quick Editing  Incorporating Jump Cuts in Video Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-defenders-a-step-by-step-guide-for-five-common-issues/"><u>Reactivating Defenders: A Step-by-Step Guide for Five Common Issues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/redesigned-look-at-s3700-sony-entertainment-for-2024/"><u>Redesigned Look at S3700 Sony Entertainment for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-audio-preferences-winvolume-issue-resolution/"><u>Reinstate Audio Preferences: WinVolume Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidias-geforce-error-x0001-on-windows-1011/"><u>Resolving Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-rpc-issues-on-windows-key-strategies/"><u>Resolving RPC Issues on Windows: Key Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-lost-rendering-device-error-in-overwatch-2/"><u>Reverse Lost Rendering Device Error in Overwatch 2</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-realign-file-history-configurations-in-windows/"><u>Steps to Realign File History Configurations in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/strategies-for-overcoming-frozen-fb-notifications/"><u>Strategies for Overcoming Frozen FB Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-errortoomanyretries-in-wsl-subsystem/"><u>Strategies to Tackle ERROR_TOO_MANY_RETRIES in WSL Subsystem</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workflow-with-the-ultimate-win-11-guide/"><u>Streamline Your Workflow with the Ultimate Win 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-write-operations-error/"><u>Tackling Windows Write Operations Error</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-competition-unveiled-twitchs-clash-with-youtube-for-2024/"><u>The Competition Unveiled  Twitch's Clash with YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-11-widget-bar-activation/"><u>The Essential Guide to Windows 11 Widget Bar Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-for-restoring-win11s-5g-link/"><u>Tips and Tricks for Restoring Win11’s 5G Link</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-windows-11-help-app-restoration/"><u>Tips for Windows 11 Help App Restoration</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-5-homemade-shot-strategies-the-fastest-hacks-you-need-for-2024/"><u>Top 5 Homemade Shot Strategies – The Fastest Hacks You Need for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-resolving-wings-of-ruin-game-crash-in-monster-hunter-stories-nro-2/"><u>Troubleshooting Guide: Resolving 'Wings of Ruin' Game Crash in Monster Hunter Stories Nro 2</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-programming-file-formats/"><u>Understanding Windows' Programming File Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-windows-1011-8-innovative-personalization-techniques/"><u>Unlock Windows 10/11: 8 Innovative Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-control-panel-access-methods/"><u>Unveiling Control Panel Access Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tech-tip-validate-audiovideo-before-participating/"><u>Windows Tech Tip: Validate Audio/Video Before Participating</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/x1000-video-world-comprehensive-sony-examination-for-2024/"><u>X1000 Video World  Comprehensive Sony Examination for 2024</u></a></li>
</ul></div>
