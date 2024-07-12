---
title: Altering Failed Logon Wait Duration Settings in Windows
date: 2024-07-11T22:08:32.655Z
updated: 2024-07-12T22:08:32.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Failed Logon Wait Duration Settings in Windows
excerpt: This Article Describes Altering Failed Logon Wait Duration Settings in Windows
keywords: Login Delay Adjustment Windows,Increase Failure Wait Time PC,Modify Unsuccessful Logon Time,Extend Logon Wait Duration,Reduce Failed Login Retry Count,Boost Unauthorized Access Window,Raise Logon Error Delay Value
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## Altering Failed Logon Wait Duration Settings in Windows

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-recovering-copilot-in-ws11/"><u>Solving the Mystery: Recovering Copilot In WS11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-infinix-smart-8-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Infinix Smart 8 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-lost-wi-fi-link-windows-edition/"><u>Resurrecting Lost Wi-Fi Link: Windows Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unusual-video-orientation-what-causes-sideway-images-on-instagram/"><u>2024 Approved  Unusual Video Orientation  What Causes Sideway Images on Instagram</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-an-mp4-on-xiaomi-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How to play an MP4 on Xiaomi Redmi Note 13 Pro+ 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-null-audio-output-on-windows-pcs/"><u>Resolve Null Audio Output on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/staying-current-the-impact-of-additional-yearly-patches-on-your-pc/"><u>Staying Current: The Impact of Additional Yearly Patches on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-saving-your-personalized-powertoys-profile/"><u>Steps for Saving Your Personalized PowerToys Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/tcpip-port-safety-a-windows-perspective/"><u>TCP/IP Port Safety: A Windows Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-onedrive-authentication-xyz-error-on-windows-11/"><u>Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/androids-top-digital-realms-15-must-play-virtual-games-for-2024/"><u>Android's Top Digital Realms  15 Must-Play Virtual Games for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-infinix-smart-8mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Infinix Smart 8Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-and-secure-file-saving-ultimate-remedies-in-windows-11/"><u>Swift and Secure File Saving: Ultimate Remedies in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sweep-away-unrecognized-interfaces-with-these-tips/"><u>Sweep Away Unrecognized Interfaces with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-rectify-opengl-error-3-in-win11-pcs/"><u>Swift Solutions to Rectify OpenGL Error #3 in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-onedrive-of-microsoft-id-integration-in-windows/"><u>Strip OneDrive of Microsoft ID Integration in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-for-removing-steams-dns-information/"><u>Stepwise Approach for Removing Steam's DNS Information</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/adding-media-instagrams-guide-for-2024/"><u>Adding Media  Instagram's Guide for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-efficient-path-to-time-stamped-image-documentation-for-2024/"><u>The Efficient Path to Time-Stamped Image Documentation for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-the-best-of-the-best-top-10-online-waveform-generators-for-audio-enthusiasts/"><u>Updated 2024 Approved The Best of the Best Top 10 Online Waveform Generators for Audio Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-pcs-absent-controllers/"><u>Resurrect Your PC's Absent Controllers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-worlds-premier-content-creators-ranked-by-subscriber-count/"><u>In 2024, World's Premier Content Creators Ranked By Subscriber Count</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-convert-audio-files-with-ease-top-5-software-solutions/"><u>New In 2024, Convert Audio Files with Ease Top 5 Software Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-windows-backup-to-original-settings/"><u>Restoring Windows Backup to Original Settings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-converting-imovie-edits-for-online-exhibition-youtube-edition/"><u>[New] 2024 Approved  Converting iMovie Edits for Online Exhibition - YouTube Edition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-finding-prominent-comment-spotlights-for-2024/"><u>[Updated] Finding Prominent Comment Spotlights for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-moto-g84-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Moto G84 5GFRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-browsing-security-with-win-11-ms-defender-guard/"><u>Optimize Browsing Security with Win 11 MS Defender Guard</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glances-to-your-favorites-windows-shortcuts-uwp-apps/"><u>Quick Glances to Your Favorites: Windows Shortcuts (UWP Apps)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-unique-audio-selections-for-video-conclusions/"><u>2024 Approved  Free, Unique Audio Selections for Video Conclusions</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eradicate-0x80072af9-on-windows/"><u>Steps to Eradicate 0X80072AF9 on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-youtube-tagging-for-content-visibility/"><u>[New] Mastering YouTube Tagging for Content Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-to-enhance-wireless-and-cable-networks-on-windows/"><u>Proven Strategies to Enhance Wireless and Cable Networks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-beam-me-up-optimal-webcam-choices-for-podcasts/"><u>[Updated] 2024 Approved  Beam Me Up  Optimal Webcam Choices for Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-playback-from-black-screen/"><u>Steps to Restore Playback From Black Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/rewiring-success-restoring-troubleshooters-in-windows-11/"><u>Rewiring Success: Restoring Troubleshooters in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-profit-mechanisms-in-windows-11/"><u>Microsoft's Profit Mechanisms in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-global-gastronomy-hits-on-tiktok/"><u>2024 Approved  Global Gastronomy Hits on TikTok</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-designing-professional-youtube-editors-workflow/"><u>[Updated] 2024 Approved  Designing Professional YouTube Editors' Workflow</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-poco-x5-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Poco X5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-microsoft-store-issues-error-code-0x80072f17-fix/"><u>Resolving Microsoft Store Issues: Error Code 0X80072f17 Fix</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-essential-guide-to-low-cost-cloud-storage-plans/"><u>[New] 2024 Approved  The Essential Guide to Low-Cost Cloud Storage Plans</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-list-of-funny-youtube-sources-for-downtime/"><u>In 2024, The Ultimate List of Funny YouTube Sources for Downtime</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/seamless-techniques-easy-steps-to-preserve-your-google-gatherings/"><u>Seamless Techniques  Easy Steps to Preserve Your Google Gatherings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-normalcy-windows-11-permissions-reversal/"><u>Reboot to Normalcy: Windows 11 Permissions Reversal</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc0000142-problems-on-win11win7/"><u>Overcoming 0XC0000142 Problems on Win11/Win7</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-windows-audio-glitches/"><u>Steps to Recover Windows Audio Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-unlocking-diskusage-insights-for-storage-management/"><u>Maximizing Windows: Unlocking DiskUsage Insights for Storage Management</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-starting-a-channel-with-confidence-your-essential-kit/"><u>2024 Approved  Starting a Channel with Confidence – Your Essential Kit</u></a></li>
<li><a href="https://windows11.techidaily.com/revival-rituals-for-lost-windows-unlocking-off-screen-restoration-in-win-1011-6-essentials/"><u>Revival Rituals for Lost Windows: Unlocking Off-Screen Restoration in Win 10/11 (6 Essentials)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-common-errors-during-windows-11-system-rollout/"><u>Tackling Common Errors During Windows 11 System Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-onedrive-sign-in-snags-with-windows-steps/"><u>Navigate Past OneDrive Sign-In Snags with Windows Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11s-0x8007045d-bluescreen-troubleshooting/"><u>Navigating Through Windows 11'S 0X8007045D Bluescreen Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unravel-exception-reached-on-windows-pcs/"><u>Steps to Unravel 'Exception Reached' On Windows PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-realme-12-pro-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Realme 12 Pro 5G</u></a></li>
</ul></div>
