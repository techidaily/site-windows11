---
title: Breaking Down Operation Elevation Woes on Windows 11 & 11
date: 2024-07-11T21:47:29.257Z
updated: 2024-07-12T21:47:29.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down Operation Elevation Woes on Windows 11 & 11
excerpt: This Article Describes Breaking Down Operation Elevation Woes on Windows 11 & 11
keywords: WinElevationIssues,ElecWinUpdates,UpgradeWoesWindows,Win11Operational,WindowsUpdateTips,ElevateWinFix,FixWin11Issue
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Breaking Down Operation Elevation Woes on Windows 11 & 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-expert-tips-for-creating-dynamic-youtube-splits-for-2024/"><u>[Updated] Expert Tips for Creating Dynamic YouTube Splits for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-notepad-malfunctions/"><u>Taming Windows Notepad Malfunctions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamlined-steps-for-ios-voice-recordings/"><u>Streamlined Steps for iOS Voice Recordings</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/bold-pfp-strategies-for-a-memorable-tiktok-persona/"><u>Bold PFP Strategies for a Memorable TikTok Persona</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-hotkey-tricks-to-reconfigure-windows/"><u>Enhance Productivity: Hotkey Tricks to Reconfigure Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-computer-recovery-top-10-tactics/"><u>Conquering Computer Recovery: Top 10 Tactics</u></a></li>
<li><a href="https://youtube-web.techidaily.com/our-first-steps-for-youtube-earning-8-methods/"><u>[New] Your First Steps for YouTube Earning - 8 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-correcting-windows-update-problems-0x30017/"><u>Expert Tips for Correcting Windows Update Problems (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-ms-store-app-selection-2023-edition/"><u>Dive Into MS Store App Selection: 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/breath-of-fresh-air-for-windows-13-revival-techniques/"><u>Breath of Fresh Air for Windows: 13 Revival Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-behind-the-screen-discovering-samsung-galaxy-s8s-4k-edge/"><u>In 2024, Behind the Screen  Discovering Samsung Galaxy S8's 4K Edge</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/8-popular-streaming-audio-recorder-that-you-cant-miss-for-2024/"><u>8 Popular Streaming Audio Recorder That You Cant Miss for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-gaming-to-goals-celebrating-the-top-10-ladies-on-youtube/"><u>[Updated] In 2024, From Gaming to Goals  Celebrating the Top 10 Ladies on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/5-strategies-for-resolving-the-no-support-windows-error/"><u>5 Strategies for Resolving the No-Support Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-laying-down-the-law-vegas-pro-21-edition-reviewed/"><u>[New] Laying Down the Law  VEGAS Pro '21 Edition Reviewed</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-high-definition-recording-mastering-live-footage-using-logitech-cam/"><u>[Updated] In 2024, High Definition Recording  Mastering Live Footage Using Logitech Cam</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-search-failure-a-fixers-manual/"><u>Confronting Windows Search Failure: A Fixer's Manual</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unveiling-websites-your-source-for-youtube-branding-collabs/"><u>Unveiling Websites  Your Source for YouTube Branding Collabs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-shared-printer-issues-on-windows-11/"><u>Addressing Shared Printer Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-image-precision-with-windows-11s-blurring-feature-in-photos-app/"><u>Unlocking Image Precision with Windows 11'S Blurring Feature in Photos App</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/did-your-iphone-15-plus-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>Did Your iPhone 15 Plus Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-reading-mode-on-ms-word-for-win-users/"><u>Troubleshooting Silent Reading Mode on MS Word for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-samsung-galaxy-a05-lock-screen-password-by-drfone-android/"><u>How to Reset your Samsung Galaxy A05 Lock Screen Password</u></a></li>
<li><a href="https://extra-support.techidaily.com/premium-vr-headset-picks-for-uavs-for-2024/"><u>Premium VR Headset Picks for UAVs for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163462577-interactive-storytelling-at-your-fingertips/"><u>Interactive Storytelling at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-error-e1-in-windows-10-11-editions/"><u>Eradicate Error E1 in Windows 10, 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-professional-print-perfection-nine-key-techniques-for-powerpoint-on-pcs/"><u>The Path to Professional Print Perfection: Nine Key Techniques for PowerPoint on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-performance-gauges-for-pcs/"><u>Efficient Performance Gauges for PCs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-noisy-to-neat-cutting-out-clutter-on-photos/"><u>2024 Approved  From Noisy to Neat  Cutting Out Clutter on Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-conversion-technique-windows-11-heic-to-jpeg/"><u>Effortless Conversion Technique: Windows 11 HEIC to JPEG</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-code-0x800700e1-problems-in-windows-11/"><u>Fixing Code 0X800700E1 Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/triggering-the-verification-toolset-for-win11-systems/"><u>Triggering the Verification Toolset for Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-understanding-its-role-in-windows-memory-controls/"><u>Decoding ftdibus.sys: Understanding Its Role in Windows Memory Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-task-monitor-in-win-11-accelerating-real-time-updates/"><u>Boosting Task Monitor in Win 11: Accelerating Real-Time Updates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-free-auditory-gamespace-vaults-copyright-free/"><u>[Updated] Free Auditory Gamespace Vaults (Copyright-Free)</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-laptops-a-forward-looking-2024-review/"><u>Best Windows Laptops: A Forward-Looking 2024 Review</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-video-venues-clash-youtube-shorts-vs-tiktoks-rapid-rise-for-2024/"><u>Viral Video Venues Clash  YouTube Shorts Vs. TikTok's Rapid Rise for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-boost-printer-functionality/"><u>Briskly Boost Printer Functionality</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-smartest-video-editing-tools-with-auto-refraiming-capabilities/"><u>Updated Smartest Video Editing Tools with Auto-Refraiming Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/forming-mobile-content-into-profitable-youtube-experiences/"><u>Transforming Mobile Content Into Profitable YouTube Experiences</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-mac-operations-with-windows-tech/"><u>Augmenting Mac Operations with Windows Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-step-into-the-future-of-video-creation-with-animated-subscribe-buttons-in-filmora/"><u>2024 Approved  Step Into the Future of Video Creation with Animated Subscribe Buttons in Filmora</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/crafting-memorable-tiktok-personal-frames-for-attention-for-2024/"><u>Crafting Memorable TikTok Personal Frames for Attention for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-motorola-edge-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-missing-sign-in-screens-in-windows-11/"><u>Bypassing Missing Sign-In Screens in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-the-ultimate-method-to-seamless-integration-of-linktree-into-tiktok-profiles/"><u>[New] In 2024, The Ultimate Method to Seamless Integration of Linktree Into TikTok Profiles</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-spotify-connection-errors-in-win11/"><u>Tackling Spotify Connection Errors in Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/convincing-consumers-one-testimonial-at-a-time-for-2024/"><u>Convincing Consumers, One Testimonial at a Time for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/master-sound-capture-on-your-macos-device-via-audacity/"><u>Master Sound Capture on Your MacOS Device via Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-images-top-4-viewer-tools-on-windows-os/"><u>Elevate WebP Images: Top 4 Viewer Tools on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-control-center-hidepower-command-of-windows-11/"><u>Clandestine Control Center: Hidepower Command of Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-secrets-for-transcribing-twitter-videos-into-mp3-format/"><u>[New] Secrets for Transcribing Twitter Videos Into MP3 Format</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-digital-contents-full-value-winning-at-powerpoint-prints-in-windows/"><u>Unlocking Your Digital Content's Full Value: Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-explore-popular-youtube-comment-sections/"><u>In 2024, Explore Popular YouTube Comment Sections</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-blocked-windows-guard-functions/"><u>Bypassing Blocked Windows Guard Functions</u></a></li>
</ul></div>
