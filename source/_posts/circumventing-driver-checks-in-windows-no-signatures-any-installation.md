---
title: "Circumventing Driver Checks in Windows: No Signatures, Any Installation"
date: 2024-07-11T21:47:31.306Z
updated: 2024-07-12T21:47:31.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Circumventing Driver Checks in Windows: No Signatures, Any Installation"
excerpt: "This Article Describes Circumventing Driver Checks in Windows: No Signatures, Any Installation"
keywords: Bypassing Windows Driver Signature,Unsigned Driver Installs,Driver Installation Without Signature,Avoiding Driver Auth Checks,No-Signature Windows Drivers,Easy Driver Install, No Signature,Bypassing Windows Auth for Drivers
thumbnail: https://thmb.techidaily.com/6816402dd23c56a105ec64bc0a33bec17942a9ec34c261fc2115b1bb0464ace8.jpg
---

## Circumventing Driver Checks in Windows: No Signatures, Any Installation

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
<li><a href="https://windows11.techidaily.com/crafting-a-unique-windows-11-search-interface/"><u>Crafting a Unique Windows 11 Search Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-print-service-stopped-issue-on-windows-pc/"><u>Addressing Print Service Stopped Issue on Windows PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-simple-steps-to-curve-an-image-in-photoshop/"><u>[New] Simple Steps to Curve an Image in Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-ultimate-guide-to-documenting-your-ps4-journey-for-2024/"><u>[New] Ultimate Guide to Documenting Your PS4 Journey for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-cost-effective-windows-11-keys/"><u>Unveiling Cost-Effective Windows 11 Keys</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-retrieve-your-voice-on-youtube-comments/"><u>[New] 2024 Approved  How To Retrieve Your Voice on YouTube (Comments)</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-the-art-of-digital-expression/"><u>Windows 11 Makeover: The Art of Digital Expression</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-purpose-behind-windows-11-s-mode-feature/"><u>Deciphering the Purpose Behind Windows 11 S Mode Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/applications-and-their-unique-run-notations-explored/"><u>Applications & Their Unique Run Notations Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-joke-journey-uncovering-top-talents-on-tiktok/"><u>[New] In 2024, Joke Journey  Uncovering Top Talents on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-error-x-on-windows-a-guide-to-email-repair/"><u>Decoding Error X on Windows: A Guide to Email Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-superiority-persistent-high-privilege-terminal/"><u>Uncomplicated Superiority: Persistent High-Privilege Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-enable-a-search-bar-on-win11s-taskbar/"><u>Elevate Your Productivity: Enable a Search Bar on Win11's Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-win-error-due-to-missing-mfc71udll/"><u>Troubleshooting Absence: Win Error Due to Missing Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-connection-issues-dissolving-ea-errors/"><u>Winning Over Connection Issues: Dissolving EA Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-crafting-charismatic-videos-with-diy-camera-setups/"><u>In 2024, Crafting Charismatic Videos with DIY Camera Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-how-to-convert-youtube-and-vimeo-videos-into-mp3-files/"><u>[New] In 2024, How to Convert YouTube and Vimeo Videos Into MP3 Files</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-platform-predicament-choosing-the-right-space/"><u>In 2024, Platform Predicament  Choosing the Right Space</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-saving-paradox-modern-standbys-dilemni/"><u>Windows' Power-Saving Paradox: Modern Standby's Dilemni</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-installer-package-fails-on-windows-11/"><u>Troubleshooting Installer Package Fails on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-updating-your-meet-name-easy-steps-for-pc-and-mobile/"><u>[New] In 2024, Updating Your Meet Name  Easy Steps for PC & Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-transform-your-streams-adopting-these-four-recording-approaches/"><u>[Updated] In 2024, Transform Your Streams  Adopting These Four Recording Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unlock-cinematic-storytelling-how-to-apply-the-ken-burns-effect-in-final-cut-pro/"><u>Updated Unlock Cinematic Storytelling How to Apply the Ken Burns Effect in Final Cut Pro</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-chromebook-visual-recorder-for-2024/"><u>[New] Top Chromebook Visual Recorder for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-in-calendar-design-a-windows-outlook-method/"><u>Unleashing Creativity in Calendar Design - A Windows Outlook Method</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-huawei-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Huawei FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
</ul></div>
