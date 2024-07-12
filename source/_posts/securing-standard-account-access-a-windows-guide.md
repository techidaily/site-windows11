---
title: "Securing Standard Account Access: A Windows Guide"
date: 2024-07-11T22:05:59.624Z
updated: 2024-07-12T22:05:59.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Securing Standard Account Access: A Windows Guide"
excerpt: "This Article Describes Securing Standard Account Access: A Windows Guide"
keywords: WinAccessGuide,SecureWinAccount,PCWindowsSecurity,WindowsLoginTips,AccessProtectionWin,SafeWinCredentials,AccountsSecureWindows
thumbnail: https://thmb.techidaily.com/03b9d4f25f53b702691684fe2aacadda124f8e51ce8909742113d79362ddfedd.jpg
---

## Securing Standard Account Access: A Windows Guide

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

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-proven-strategies-for-professional-green-screen-filming/"><u>In 2024, Proven Strategies for Professional Green Screen Filming</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-enable-or-disable-windows-build-service/"><u>Procedures to Enable or Disable Windows Build Service</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-interactive-web-glitch-sounds-pack-free-legal-download-2023-edition-for-2024/"><u>Updated Interactive Web Glitch Sounds Pack – Free, Legal Download 2023 Edition for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-perfecting-highlight-covers-an-in-depth-insta-photography-guide/"><u>[New] 2024 Approved  Perfecting Highlight Covers  An In-Depth Insta Photography Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-to-mend-post-windows-update-issues/"><u>Immediate Actions to Mend Post-Windows Update Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-original-screen-aspect-ratio/"><u>Restore Original Screen Aspect Ratio</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-boosting-engagement-uploading-and-sharing-on-instagram-desktop/"><u>[New] Boosting Engagement  Uploading and Sharing on Instagram Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-driver-verifier-in-win11-os/"><u>Launching the Driver Verifier in Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-reverse-a-video-on-snapchat-complete-guide/"><u>How to Reverse a Video on Snapchat? [Complete Guide]</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-munching-memes-10-food-trends-galore-on-tiktok-for-2024/"><u>[New] Munching Memes  10 Food Trends Galore on TikTok for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-new-era-for-mobile-photography-iphone-x-explored/"><u>[Updated] New Era for Mobile Photography  IPhone X Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-step-by-step-techniques-for-sharing-videos-on-instagram-for-2024/"><u>[Updated] Step-by-Step Techniques for Sharing Videos on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-how-to-download-videoleap-on-macbook/"><u>New In 2024, How to Download Videoleap on MacBook</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-ultimate-selection-of-top-5-android-audio-editing-software-worth-your-time-for-2024/"><u>New The Ultimate Selection of Top 5 Android Audio Editing Software Worth Your Time for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://driver-install.techidaily.com/wireless-proxy-installer-w7-edition/"><u>Wireless Proxy Installer, W7 Edition</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitters-number-one-video-trends/"><u>[New] Twitter's Number One Video Trends</u></a></li>
<li><a href="https://article-files.techidaily.com/new-shaking-no-more-evaluating-photoshops-anti-shake-feature/"><u>[New] Shaking No More  Evaluating Photoshop's Anti-Shake Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-honor-x50iplus-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Honor X50i+ FRP</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/audible-savings-the-essential-guide-to-using-these-24-no-cost-splitters-on-youtube-for-2024/"><u>Audible Savings  The Essential Guide to Using These 24 No-Cost Splitters on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-sound-quality-top-5-free-windows-tools/"><u>Improve Sound Quality: Top 5 Free Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-unreal-device-issue-in-win-11/"><u>How to Resolve Unreal Device Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reveal-hidden-sd-card-in-file-explorer/"><u>How to Reveal Hidden SD Card in File Explorer?</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-apple-iphone-12-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to Apple iPhone 12 Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579709641-which-are-the-most-studied-foreign-languages-in-america/"><u>Which Are The Most Studied Foreign Languages In America?</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhancing-your-aesthetic-vision/"><u>Enhancing Your Aesthetic Vision</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ensuring-precision-the-art-of-skype-call-documentation/"><u>In 2024, Ensuring Precision  The Art of Skype Call Documentation</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-launch-identifiers-for-applications/"><u>Interpreting Launch Identifiers for Applications</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ost-smart-and-cheap-your-guide-to-youtube-seminars-for-2024/"><u>[New] Host Smart and Cheap  Your Guide to Youtube Seminars for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-go-global-with-music-transform-your-spotify-lists-into-youtube-videos/"><u>In 2024, Go Global with Music  Transform Your Spotify Lists Into YouTube Videos</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-unleash-your-creativity-the-best-time-lapse-video-editing-software/"><u>New In 2024, Unleash Your Creativity The Best Time-Lapse Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/unlocking-talkshoplive-pros-and-tips-for-live-shopping-success-for-2024/"><u>Unlocking TalkShopLive Pros and Tips for Live Shopping Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-samsung-galaxy-m34-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Samsung Galaxy M34 for Free? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/twice-as-nice-sequential-video-playback-via-television-setup/"><u>Twice as Nice  Sequential Video Playback via Television Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-mastering-mac-from-live-classroom-to-recorded-session-for-2024/"><u>[New] Mastering Mac  From Live Classroom to Recorded Session for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/freeze-yourself-no-more-9-techniques-for-easing-windows-install-locks/"><u>Freeze Yourself No More: 9 Techniques for Easing Windows Install Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-best-free-video-to-audio-converter-for-2024/"><u>New Best Free Video to Audio Converter for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/auditory-aesthetics-weaving-melodies-into-your-feed/"><u>Auditory Aesthetics  Weaving Melodies Into Your Feed</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-credentials-error-loop/"><u>Overcoming Windows Credentials Error Loop</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-free-sound-effects-for-fcp-a-beginners-guide-to-elevating-your-video-editing-game/"><u>New In 2024, Free Sound Effects for FCP A Beginners Guide to Elevating Your Video Editing Game</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-uncovering-budget-friendly-video-communication-apps-pcmac-for-2024/"><u>[New] Uncovering Budget-Friendly Video Communication Apps  PC/MAC for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-guide-to-brightening-gopro-footage/"><u>2024 Approved  Step-by-Step Guide to Brightening GoPro Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-samsung-galaxy-m34-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Samsung Galaxy M34 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-exceptional-list-superior-tiktok-downloaders-watermark-free/"><u>[Updated] In 2024, Exceptional List  Superior TikTok Downloaders (Watermark-Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failures-qt-platform-support-error-at-launch/"><u>Correcting Failures: 'Qt Platform Support' Error at Launch</u></a></li>
</ul></div>
