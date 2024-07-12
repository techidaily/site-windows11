---
title: "Windows 11: Clear PIN Lockouts with Ease"
date: 2024-07-11T21:18:50.386Z
updated: 2024-07-12T21:18:50.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Clear PIN Lockouts with Ease"
excerpt: "This Article Describes Windows 11: Clear PIN Lockouts with Ease"
keywords: Windows 11 PIN Lockout,Clear Windows PIN,Easy Windows Lock,Windows 11 Security Fix,PIN Recovery in W11,Resolve Windows Lockout,Ease Windows Lock Issue
thumbnail: https://thmb.techidaily.com/5cce1c00c454a1f4ada87360e66f8d07572afee6c8228611ca9a5690c1d2c490.jpg
---

## Windows 11: Clear PIN Lockouts with Ease

 Is your Windows Hello PIN not being accepted by Windows? In most cases, it occurs when you enter the wrong PIN. Other factors that could contribute to this issue include corruption of the Ngc folder, a problem with your Microsoft or local accounts, or misconfigured PIN settings in the Group Policy Editor.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.

## 1\. Ensure You Aren't Entering the Incorrect PIN

 You could simply be entering the wrong PIN, which is the first possible cause of your PIN not working. To eliminate this possibility, reset your PIN once.

 Your computer must be connected to an active internet connection to reset your PIN. Therefore, turn on your computer and ensure that the internet is connected. To reset your PIN, go to the profile's login page and click on **I forgot my PIN**.

![Clicking on I Forgot My PIN in Windows Home Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Clicking-on-I-Forgot-My-PIN-in-Windows-Home-Screen.jpg)

 You can either reset the PIN by verifying your identity with your Microsoft account password or choose an alternative sign-in option by clicking **Send code**, which sends a code to your email address.

![Windows Notifying About Receiving the Code to Reset Pin on the Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Windows-Notifying-About-Receiving-the-Code-to-Reset-Pin-on-the-Windows-Login-Screen-Censor-1.jpg)

 If you select the latter option, enter the code you received by email and click **Continue**. Windows will direct you to enter a new PIN here, so enter it, confirm it once, and click **OK**.

![Adding a New Pin to Change the Old One in Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Adding-a-New-Pin-to-Change-the-Old-One-in-Windows-Login-Screen.jpg)

 Restart your computer once more, add your new PIN on the login screen, and try logging in again to make sure it was the wrong PIN that wasn't letting you enter the computer previously. You are good to go if you can log in this time - just don't forget your new PIN.

 If the PIN again does not work after resetting and you are sure that the PIN you are entering is correct, the problem may reside elsewhere. Therefore, use an alternate way to log in to your account and then rule out other possibilities.

## 2\. Sign-In Using Alternative Methods

 If resetting the PIN from the login screen does not resolve the issue, you can use your account password instead. To do that, follow the below steps:

1. Click **Sign-in options** to view other options for logging in.
2. Click the **key icon**, which is usually located on the left.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
3. Type the password associated with your account here.

 Once logged in, you can start applying the remaining fixes.

 If you don't remember your account password, you can reset it just like you can your PIN. Unlike resetting the PIN, resetting the password mostly goes smoothly and lets you sign in.

## 3\. Delete the Ngc Folder in Windows

 Windows stores all your PIN-related settings in this folder, so if the OS isn't accepting your PIN, which is correct, you should delete this folder. This process will wipe out all PIN-related data from the OS. You can then set up a new PIN, which should work fine.

 You can delete the Ngc folder by following these steps:

1. Log in to your administrator account.
2. Navigate to **C: drive > Windows> ServiceProfiles > LocalService > AppData > Local> Microsoft**.
3. Locate the Ngc folder, right-click on it, and hit **Delete**.  
![Deleting Ngc Folder in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Deleting-Ngc-Folder-in-Windows-10-Edit.jpg)

 Navigate to **Settings > Accounts > Sign-in options** to set up a new PIN after deleting the old one. Afterward, click on **Windows Hello PIN**, add a new PIN, and hopefully, the PIN will start working on your operating system.

![Windows Hello PIN In Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/3-Windows-Hello-PIN-In-Windows-Settings-App.jpg)

 If this fix also doesn't resolve the issue, it lies somewhere else that needs to be investigated further.

## 4\. Rule Out User Account Specific Issues

 When troubleshooting PIN issues, it's essential to rule out account-specific problems first. To begin with, check that the problem does not persist on a single Microsoft account. The best way to confirm this is to switch to a local account. To do that, follow the below steps:

1. Open the Windows Settings app.
2. Go to **Accounts**.
3. Navigate to **Your info** in the left-sidebar.
4. Click on **Sign in with a local account instead**.  
![changing accounts settings in windows 10 settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/changing-accounts-settings-in-windows-10-settings-app-edit.jpg)
5. Click on **Next**.
6. Enter your PIN.
7. Set up your local account by adding your username and password.
8. Once done, hit **Next**.  
![Setting Up Local Account in Windows 10 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/2-Setting-Up-Local-Account-in-Windows-10-Settings-App.jpg)
9. Click on **Sign out and finish**.

 By following the above steps, you will return to the login screen. Type in your PIN again to confirm it works. If it does, it's your Microsoft account that is to blame. Creating another user account and checking if the PIN works there could help confirm that.

 Therefore, if the issue originates from your Microsoft user account, you should copy your files to the new account and start using the new account permanently.

 If the PIN does not work on any account, move on to the next fix.

## 5\. Tweak PIN Sign-In Settings in Group Policy Editor

 When the convenience PIN sign-in setting in the Group Policy Editor is disabled, the PIN will not work. Therefore, it's essential to ensure it's not causing the problem during sign-in.

 Some Windows versions, however, might not have this feature. If this applies to you as well, skip this step.

 Follow the below steps to adjust the settings in the Group Policy Editor:

1. Search for the **Run** app in the Windows search bar.
2. Type **gpedit.msc** and click on **OK**.
3. Navigate to **Administrative Templates > System > Logon**.
4. In the right-hand pane, locate and double-click on **Turn on convenience PIN sign-in setting**.
5. Check the **Enabled** checkbox, click **Apply**, and hit **OK**.

 If the setting is already enabled, continue to apply the remaining fixes.

 Group Policy Editor isn't available in the Windows Home edition by default. You can skip this fix if you're using the Home edition or try [alternative ways to get the Group Policy Editor](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

## 6\. Update or Downgrade Your OS

 According to [Microsoft support helpers](https://answers.microsoft.com/en-us/windows/forum/all/pin-not-working-on-windows-10/d444ebfb-d643-40b5-be62-1569454118d1), one of the possible causes of PIN not working on Windows may be recent updates. If you remember doing an update recently, you need to [roll the update back](https://www.makeuseof.com/tag/regret-update-windows-10-revert-version/).

 Conversely, if you haven't updated your computer for quite some time, maybe the problem stems from an outdated Windows OS. In that case, follow the below steps to update your computer:

1. Open the Windows Settings app.
2. Go to **Update & Security**.
3. Navigate to **Windows Update** in the left sidebar.
4. Click on **Check for updates** box.  
![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

 Windows will automatically check for the latest updates and update itself if necessary. After your OS has been updated, try logging in again with your PIN if it works this time.

 If you're experiencing this issue on Windows 11, see our guide on [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) to update your system. If you've started experiencing this issue after installing an update, follow our guide on [how to uninstall updates in Windows 11](https://www.makeuseof.com/windows-11-uninstall-updates/) and uninstall the most recent updates you installed.

 If the issue persists, run a malware scan to rule out the possibility of malware interference.

## 7\. Turn Off Your Antivirus and Run a Malware Scan

 Possible interference from antivirus may also result in your PIN being rejected. To prevent this from happening, temporarily turn off any third-party antivirus you're using. If turning off the third-party security suite fixes the problem, turn it off permanently.

 In addition, you can [temporarily disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) (now known as Microsoft Defender), the built-in security suite, to ensure that it's not the culprit. Remember to re-enable the security suite, as turning it off for too long can expose your device to malware.

 Aside from that, malware infections can also impair many system functions. Thus, it is imperative to rule out this possibility. You can easily do this by [running a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/). By scanning the system, you can ensure that no hidden malware is affecting its performance.

## 8\. Run an SFC Scan

 When you remove malware from your computer, make sure it hasn't corrupted any Windows files that might have caused the issue at hand.

 The easiest way to do this is to run an SFC scan. The scan automatically searches for corrupted files and replaces them with a cached copy. You can check out how to use the SFC tool in our guide on [how to repair corrupt Windows files with its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 If running the SFC scan does not fix the problem, you can [revert your system to an earlier restore point](https://www.makeuseof.com/use-system-restore-windows/) where the PIN was working. You can only do this if you've already created a restore point. Otherwise, it's impossible.

## PIN Still Isn’t Working on Windows?

 After you have tried all fixes listed above and the issue persists, consider restoring your computer to a previous point where the PIN was working fine. If that doesn't solve the problem either, it's best to factory reset your computer as a last resort.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/best-options-to-windows-snipper-top-5-alternative-capture-apps/"><u>Best Options to Windows Snipper: Top 5 Alternative Capture Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-9-affordable-and-straightforward-video-editors-for-2024/"><u>Top 9 Affordable & Straightforward Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winsplit-a-guide-to-overcome-display-split/"><u>WinSplit: A Guide to Overcome Display Split</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-itel-p55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Itel P55 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-honor-v-purse-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Honor V Purse Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-chuckle-filled-creativity-crafting-7-side-splitting-youtube-sets/"><u>[New] Chuckle-Filled Creativity  Crafting 7 Side-Splitting YouTube Sets</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-tips-for-immaculate-nighttime-photography/"><u>[New] Tips for Immaculate Nighttime Photography</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-video-to-live-photo-expert-recommended-apps-and-guides/"><u>Updated From Video to Live Photo Expert-Recommended Apps and Guides</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-enhance-your-video-watching-with-top-fire-browser-extensions-for-facebook-videos-2023-edition/"><u>[New] In 2024, Enhance Your Video Watching with Top Fire-Browser Extensions for Facebook Videos, 2023 Edition</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-harmonizing-soundscape-and-aesthetics-showcasing-audio-signals-in-visual-forms-and-animating-them-for-cinematic-vision-in-adobe-audition-pro/"><u>Updated In 2024, Harmonizing Soundscape and Aesthetics Showcasing Audio Signals in Visual Forms & Animating Them for Cinematic Vision in Adobe Audition Pro Master.</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-acquiring-lifelike-vampire-sonic-traces-for-2024/"><u>New Acquiring Lifelike Vampire Sonic Traces for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premium-portfolio-cutting-edge-cardboard-vr-game-listings/"><u>[New] Premium Portfolio  Cutting-Edge Cardboard VR Game Listings</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-infinix-note-30-vip-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Infinix Note 30 VIP to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-tecno-spark-20-proplus-by-drfone-android/"><u>How to Bypass FRP from Tecno Spark 20 Pro+?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-effortless-video-capturing-on-win11-os/"><u>[Updated] Effortless Video Capturing on Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleash-your-devices-potential-how-to-download-and-customize-whatsapp-ringtones-for-2024/"><u>Unleash Your Device's Potential  How to Download and Customize WhatsApp Ringtones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-how-to-resolve-unison-issues-on-win11/"><u>Winning Strategies: How To Resolve Unison Issues on Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-identifying-high-impact-keywords-for-effective-youtube-marketing/"><u>2024 Approved  Identifying High-Impact Keywords for Effective YouTube Marketing</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/apk-quickstart-guide-for-widely-adopted-windows-11/"><u>APK Quickstart Guide for Widely-Adopted Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/video-editing-face-off-sony-vegas-pro-vs-adobe-premiere-pro-features-pricing-and-more/"><u>Video Editing Face-Off Sony Vegas Pro vs Adobe Premiere Pro - Features, Pricing, and More</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-video-expertise-elevated-streamline-your-edits-with-these-vimeo-shortening-techniques-for-2024/"><u>[Updated] Video Expertise Elevated  Streamline Your Edits with These Vimeo Shortening Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-becoming-a-pro-in-tiktok-live-shopping-your-complete-guide-for-2024/"><u>Updated Becoming a Pro in TikTok Live Shopping Your Complete Guide for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-ultimate-8-enhancement-packs-for-live-video-feeds/"><u>In 2024, Ultimate 8 Enhancement Packs for Live Video Feeds</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-configuring-picture-in-picture-for-apple-browsers/"><u>2024 Approved  Configuring Picture-in-Picture for Apple Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/harmonize-video-quality-with-instagrams-visual-theme/"><u>Harmonize Video Quality with Instagram's Visual Theme</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-sony-xperia-1-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-pinnacle-of-live-tweeting-on-social-media/"><u>[New] In 2024, The Pinnacle of Live Tweeting on Social Media</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-audio-issue-methods-to-enable-automatic-system-startup/"><u>Windows Audio Issue: Methods to Enable Automatic System Startup</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-make-well-done-animated-gif-for-2024/"><u>New Make Well Done Animated GIF for 2024</u></a></li>
</ul></div>
