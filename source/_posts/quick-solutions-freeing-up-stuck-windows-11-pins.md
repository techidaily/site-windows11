---
title: "Quick Solutions: Freeing Up Stuck Windows 11 PINs"
date: 2024-07-11T21:16:19.436Z
updated: 2024-07-12T21:16:19.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Solutions: Freeing Up Stuck Windows 11 PINs"
excerpt: "This Article Describes Quick Solutions: Freeing Up Stuck Windows 11 PINs"
keywords: Fix Stuck W11 Pin,Unlock W11 PIN,Release W11 Lock,Clear W11 Password,Free W11 Access,Bypass W11 PIN,Reset Windows 11 Code
thumbnail: https://thmb.techidaily.com/45a1f9697d2bdeb16116c56d8bb656d37d6c88757987caf5e6bad0d2243c55f0.jpg
---

## Quick Solutions: Freeing Up Stuck Windows 11 PINs

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
<li><a href="https://windows11.techidaily.com/disabling-accidental-windows-11-search-menu-trigger/"><u>Disabling Accidental Windows 11 Search Menu Trigger</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-find-a-programs-install-location-on-windows/"><u>4 Ways to Find a Program's Install Location on Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-best-choices-8-leading-audio-production-tools-transforming-todays-hip-hop-genre/"><u>In 2024, Best Choices 8 Leading Audio Production Tools Transforming Todays Hip-Hop Genre</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-data-power-discover-four-routes-to-opening-disk-management-in-win11/"><u>Unleash Data Power: Discover Four Routes to Opening Disk Management in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-display-more-pinned-items-on-the-windows-11-start-menu/"><u>How to Display More Pinned Items on the Windows 11 Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-apps-better-internet-fixes-for-windows-devices/"><u>Faster Apps, Better Internet: Fixes for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-data-consumption-by-windows-programs/"><u>Decoding Data Consumption by Windows Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-discord-app-lag-on-windows/"><u>How to Fix Discord App Lag on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-tecno-spark-go-2023-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Tecno Spark Go (2023) Quickly | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-program-initiation-with-optimal-win11-settings/"><u>Enhance Program Initiation with Optimal Win11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-inactive-snapshots-on-pcs/"><u>Fixes for Inactive Snapshots on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-effective-policies-for-external-drive-use-in-windows/"><u>Implementing Effective Policies for External Drive Use in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-windows-11s-compatibility-diagnostic/"><u>Unveiling the Secrets of Windows 11’S Compatibility Diagnostic</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-evolution-a-portable-offline-approach/"><u>Windows Evolution: A Portable Offline Approach</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-crafting-visual-stories-for-successful-fb-covers-for-2024/"><u>[Updated] Crafting Visual Stories for Successful FB Covers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-your-pc-reduce-memorycpu-waste-from-apps/"><u>Tweak Your PC: Reduce Memory/CPU Waste From Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-video-quality-using-madvr-on-windows/"><u>Boosting Video Quality: Using MadVR on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-mouse-efficiency-altering-double-click-speed-in-windows/"><u>Maximize Mouse Efficiency: Altering Double-Click Speed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/claim-your-potential-in-windows-11-regain-missing-system-upgrades/"><u>Claim Your Potential in Windows 11: Regain Missing System Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-windows-11-taskbar-placement-hacks/"><u>Custom Windows 11 Taskbar Placement Hacks</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-iphone-x-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your iPhone X without Security Questions?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-instantaneous-sharability-tweeting-videos-on-snapchat-network/"><u>[New] In 2024, Instantaneous Sharability  Tweeting Videos on Snapchat Network</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-sony-xperia-1-v-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Sony Xperia 1 V Activity | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-symphony-space-recordings-downloads-for-study-for-2024/"><u>[Updated] Symphony Space  Recordings, Downloads for Study for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-iphone-13-mini-passcode-easily-video-inside-by-drfone-ios/"><u>How to Bypass iPhone 13 mini Passcode Easily Video Inside</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveil-the-true-image-learn-background-removal-on-photopea/"><u>Unveil the True Image  Learn Background Removal on Photopea</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-malfunctioning-outlook-mail-signals-on-pc/"><u>Mending Malfunctioning Outlook Mail Signals on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-ai-with-microsoft-copilot-writes-and-debugging/"><u>Embracing AI with Microsoft Copilot' Writes and Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ping-wisdom-utilizing-tools-for-maximum-efficiency/"><u>Windows Ping Wisdom: Utilizing Tools for Maximum Efficiency</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-change-quicktime-player-speed-on-mac/"><u>Updated In 2024, How to Change Quicktime Player Speed on Mac?</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-your-battlenet-downloads-on-windows-pcs/"><u>Turbocharging Your Battle.net Downloads on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/climate-control-experts-the-finest-windows-11-apps/"><u>Climate Control Experts: The Finest Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-common-fails-on-your-first-day-with-windows-11/"><u>Avoiding Common Fails on Your First Day with Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-dissecting-sharex-opinions-and-picks/"><u>In 2024, Dissecting ShareX  Opinions & Picks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-how-to-create-a-google-meet-account/"><u>In 2024, How to Create a Google Meet Account</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-top-10-coolest-plugins-for-final-cut-pro-x-freeandpaid/"><u>Updated Top 10 Coolest Plugins for Final Cut Pro X Free&Paid</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-mac-video-editing-101-how-to-choose-the-right-movie-maker-software/"><u>In 2024, Mac Video Editing 101 How to Choose the Right Movie Maker Software</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-battlenet-game-updates-in-windows/"><u>Accelerating Battle.net Game Updates in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-cortana-in-windows-11-os/"><u>How to Mute Cortana in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reach-windows-11s-account-control-interface/"><u>How to Reach Windows 11'S Account Control Interface</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-original-visual-storytelling-appraisal-and-substitutions/"><u>[New] In 2024, Original Visual Storytelling Appraisal & Substitutions</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-elevation-problem-with-error-code-740-on-windows-11/"><u>Fixing Elevation Problem with Error Code 740 on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-top-rated-free-video-storage-sites-for-online-sharing/"><u>New 2024 Approved Top-Rated Free Video Storage Sites for Online Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-domain-user-biometric-control-in-windows-11/"><u>Mastering Domain User Biometric Control in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-projector-disconnected-error-on-your-pc/"><u>Fixing Projector Disconnected Error on Your PC</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-ai-to-enhance-shopping-on-the-ms-store/"><u>Leveraging AI to Enhance Shopping on the MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-windows-error-0x800704b3/"><u>Understanding and Fixing the Windows Error: 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-correcting-roblox-error-262/"><u>Mastering the Art of Correcting Roblox Error 262</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-zte-nubia-flip-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with ZTE Nubia Flip 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-the-load-streamlining-windows-11-mails-email-display/"><u>Easing the Load: Streamlining Windows 11 Mail's Email Display</u></a></li>
</ul></div>
