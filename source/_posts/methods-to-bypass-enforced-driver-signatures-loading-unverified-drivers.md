---
title: Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers
date: 2024-07-11T22:01:36.313Z
updated: 2024-07-12T22:01:36.313Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers
excerpt: This Article Describes Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers
keywords: Bypass Driver Signature,Unlock Drivers Safely,Skip Verification Process,Load Risky Drivers,Safe Driver Bypass,Enforced Loading Techniques,Avoiding Signature Restrictions
thumbnail: https://thmb.techidaily.com/21dc09642e8b9d9182830cb6498f509afd60ef4fb9e6e678414f0bc441ff1b6a.jpg
---

## Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-the-only-guide-youll-ever-need-to-learn-gif-design-that-get-shared-like-crazy/"><u>2024 Approved The Only Guide Youll Ever Need to Learn GIF Design That Get Shared Like Crazy</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-eliminate-extra-software-in-windows-11/"><u>Fast Track: Eliminate Extra Software in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-showmore-screen-recorder-review-2023/"><u>[Updated] In 2024, ShowMore Screen Recorder Review 2023</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-fb-live-demystified-how-to-watch-2023-update/"><u>[New] 2024 Approved  FB Live Demystified  How to Watch, 2023 Update</u></a></li>
<li><a href="https://article-helps.techidaily.com/the-ultimate-guide-making-your-gifs-into-stickers-via-discordwhatsapp-for-2024/"><u>The Ultimate Guide  Making Your GIFs Into Stickers via Discord/WhatsApp for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-the-power-of-final-cut-pro-creating-engaging-video-slideshows-for-2024/"><u>New Unleash the Power of Final Cut Pro Creating Engaging Video Slideshows for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/rights-and-recourse-following-sudden-account-suspension-on-fb-for-2024/"><u>Rights and Recourse Following Sudden Account Suspension on FB for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/n-series-window-enigma-deciding-factors/"><u>N-Series Window Enigma: Deciding Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-management-in-windows-the-power-of-winget/"><u>Mastering App Management in Windows: The Power of Winget</u></a></li>
<li><a href="https://windows11.techidaily.com/leveling-web-speeds-for-seamless-experience/"><u>Leveling Web Speeds for Seamless Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-productivity-with-windows-11-calendar/"><u>Maximizing Productivity with Windows 11 Calendar</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premier-winpodcast-options-reviewed/"><u>In 2024, Premier WinPodcast Options Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits!</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-startup-mastery-in-windows-11-a-comprehensible-guide/"><u>Fast Startup Mastery in Windows 11 - A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-supported-devices-found-in-windows-11/"><u>Overcoming No Supported Devices Found in Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-top-picks-the-ultimate-selection-of-4k-monitors-for-macos/"><u>[Updated] Top Picks  The Ultimate Selection of 4K Monitors for MacOS</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unbeatable-gaming-intro-creations-the-best/"><u>Updated Unbeatable Gaming Intro Creations The Best</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-taskbars-date-and-time-presentation/"><u>Fine-Tuning Taskbar's Date & Time Presentation</u></a></li>
<li><a href="https://windows11.techidaily.com/liberating-windows-past-a-set-of-three-tactics/"><u>Liberating Windows Past - A Set of Three Tactics</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-poco-m6-pro-5g-frp-by-drfone-android/"><u>Full Guide to Bypass Poco M6 Pro 5G FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/perfecting-presentations-with-zoom-screenshares-for-2024/"><u>Perfecting Presentations with Zoom Screenshares for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-write-permissions-correction-on-win/"><u>Mastering File Write Permissions Correction on Win</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-mastering-tempo-adjustments-aligning-audio-and-visuals-in-fcpx-for-2024/"><u>Updated Mastering Tempo Adjustments Aligning Audio and Visuals in FCPX for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/free-video-credits-expertise-top-6-maker-guide-for-2024/"><u>Free Video Credits Expertise - Top 6 Maker Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-failed-login-lockout-timer-in-windows-1011/"><u>Modifying Failed Login Lockout Timer in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-artisans-code-a-complete-blueprint-for-flawless-windows-tv-recording/"><u>2024 Approved  The Artisan's Code  A Complete Blueprint for Flawless Windows TV Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-new-submenus-to-windows-11s-desktop-context-menu/"><u>How to Add New Submenus to Windows 11’S Desktop Context Menu</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-10-powerful-igtv-video-tips-for-amplified-brand-impact/"><u>In 2024, 10 Powerful IGTV Video Tips for Amplified Brand Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-linux-and-linux-apps-on-a-windows-pc/"><u>How to Set Up Linux and Linux Apps on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-altering-terminal-preference/"><u>Essential Steps for Altering Terminal Preference</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-by-step-mastery-comprehensive-analysis-and-tutorial-for-powerdirector-2024/"><u>Step-by-Step Mastery  Comprehensive Analysis and Tutorial for PowerDirector 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-simple-windows-11-techniques-for-video-editing/"><u>[New] Simple Windows 11 Techniques for Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-lost-bluetooth-listings-dmi/"><u>How to Reactivate Lost Bluetooth Listings DMI</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-exclusive-selection-of-top-7-noise-cancellers-for-easy-voice-reduction/"><u>Updated Exclusive Selection of Top 7 Noise Cancellers for Easy Voice Reduction</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-samsung-flow-connected-life-for-devices/"><u>Navigate Through Samsung Flow - Connected Life for Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/best-mac-screen-grabbers-compiled-here-for-2024/"><u>Best Mac Screen Grabbers Compiled Here for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-ridiculous-rhythms-satirical-song-stories/"><u>[Updated] Ridiculous Rhythms  Satirical Song Stories</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-capture-clarity-selecting-best-gimbals-for-your-camera/"><u>2024 Approved  Capture Clarity  Selecting Best Gimbals for Your Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-limit-fixing-gpt-windows-problems/"><u>Overcoming System Limit: Fixing GPT Windows Problems</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-professional-prowess-best-webcams-to-upgrade-your-podcasting/"><u>[New] Professional Prowess  Best Webcams to Upgrade Your Podcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-windows-space-adding-this-pc-iconography/"><u>Personalizing Windows Space: Adding 'This PC' Iconography</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-expert-techniques-for-superior-quality-in-zoom-meetings-for-2024/"><u>[Updated] Expert Techniques for Superior Quality in Zoom Meetings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
</ul></div>
