---
title: 4 Ways to Fix the Windows PowerShell Cannot Be Loaded Because Running Scripts Is Disabled Error
date: 2024-07-11T22:13:43.674Z
updated: 2024-07-12T22:13:43.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Fix the Windows PowerShell Cannot Be Loaded Because Running Scripts Is Disabled Error
excerpt: This Article Describes 4 Ways to Fix the Windows PowerShell Cannot Be Loaded Because Running Scripts Is Disabled Error
keywords: PowerShellErrorFix,RunScriptLoadFailure,DisablePSLaunchFailure,FixPowerShellError,EnablePSExecution,ScriptRunWindowsError,PSLoaderRestartTips
thumbnail: https://thmb.techidaily.com/19c73d13dc30898f49d32d8c5d0e6badbf2d50aea1c634709fd828dcee42d79c.jpg
---

## 4 Ways to Fix the Windows PowerShell Cannot Be Loaded Because Running Scripts Is Disabled Error

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

## 2\. Change the Execution Policy in PowerShell

 In some instances, changing the execution policy could help. But before we explore the solutions, let’s first take you through what the execution policy is and how it works.

### What Is the Execution Policy, and How Does It Work?

 The execution policy is a security feature that controls the way you run PowerShell scripts on your device. It simply determines which types of scripts can be run and which ones should be avoided. The best part is that you can configure this policy to your liking.

 Here are the options you can pick from when configuring the execution policy:

* **Restricted**: This policy prohibits you from running any PowerShell script.
* **Unrestricted**: Allows you to run any script but shows you a warning message when you run suspicious scripts.
* **RemoteSigned**: This policy requires a digital signature when you run the scripts that you downloaded online. However, it doesn’t require a signature for local scripts.
* **ByPass**: This allows you to run any script without any restrictions. Unlike the "Unrestricted" policy, the "ByPass" policy won’t show you any warning messages when you run suspicious scripts. So, always apply this policy only when running legit scripts.
* **AllSigned**: This policy only runs scripts that are signed by a trusted publisher.

 Now, if you use PowerShell regularly, then you might want to change the execution policy from time to time. However, some execution policies might display error messages when you run your PowerShell scripts.

 For example, enabling the “Restricted,” “AllSigned,” or “RemoteSigned” policies might lead to error messages like the "running scripts is disabled" error.

 To resolve the problem, you'd simply have to change the execution policy to “Unrestricted” or “ByPass.” But that’s not all; you'd also need to decide how the policy should be implemented. For example, do you want to apply the policy for all users or just for your current PowerShell session?

 Let's explore all the additional [PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) you’ll have to add when changing the execution policy:

* **CurrentUser**: This policy will only be applied to all the PowerShell sessions of the person who has currently logged in on the device.
* **LocalMachine**: Applies to all the users that have an account on the device. This policy can only be configured by local users that have administrative privileges.
* **Process**: Only applies on the current PowerShell session. This means you’ll have to execute the policy again if you start a new session.
* **MachinePolicy**: This policy applies to all the users who have an account on your device. However, it can only be configured by network administrators who have appropriate permissions. But it's often possible for local administrators to configure this execution policy using the Local Group Policy Editor.
* **UserPolicy**: Applies to all PowerShell sessions and the scripts executed by a particular user.

 Now that everything is clear, let’s explore how you can execute the relevant policies to tackle the "PowerShell cannot load" issue.

### How to Change the Execution Policy to "Unrestricted"

 The best way to tackle the issue at hand is to change the execution policy to "unrestricted." But before that, you need to check how each execution policy is configured.

 Here are the steps for checking how the execution policies are configured:

1. Press **Win + X** to open the Quick Access Menu.
2. Select **Windows PowerShell (Admin)** from the options.
3. Type the following command and press **Enter**:

`Get-ExecutionPolicy -List`

![Displaying the list of execution policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/displaying-the-list-of-execution-policies.jpg)

 This should show you how the execution policies are configured for different users and systems.

 To can change the execution policy to “Unrestricted” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

![Setting the execution policy on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/setting-the-execution-policy-on-powershell.jpg)

 To change the execution policy to “Unrestricted” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope LocalMachine`

 When you finish running the command, close PowerShell and restart your PC to save these changes.

### How to Change the Execution Policy to "ByPass"

 The "ByPass" execution policy will allow you to run any PowerShell script without a hassle. But remember that it might also allow you to run buggy files. So, always configure this execution policy only when running trustworthy PowerShell files.

 To change the execution policy to “ByPass” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope CurrentUser`

 And to change the execution policy to “ByPass” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope LocalMachine`

 When you finish, close PowerShell and then restart your device.

## 3\. Change the Execution Policy Via the Local Group Policy Editor

![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)

 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)

 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.

## 4\. Change the Execution Policy Using the Registry Editor

![A lady using her Windows PC while sitting on bed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-her-Windows-PC-while-sitting-on-bed.jpg)

 If the other methods didn’t help, then try changing the execution policy using the Registry Editor. However, you need to be careful when editing Registry keys. If you tweak the wrong keys, then you might end up damaging your PC.

 Now, here’s how to change the execution policy via the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell`

 Locate the **ExecutionPolicy** value on the right-hand side.

![Selecting the ExecutionPolicy value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-executionpolicy-value.jpg)

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Nokia G42 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-expert-techniques-for-removing-audio-disturbances-for-2024/"><u>[New] Expert Techniques for Removing Audio Disturbances for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beats-for-beginnings-10-premium-songs-to-launch-your-podcasts/"><u>Beats for Beginnings  10 Premium Songs to Launch Your Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstating-original-size-for-win-11-icons/"><u>Guide to Reinstating Original Size for Win 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-launch-snapchat-seamlessly-on-mac-systems-for-2024/"><u>[Updated] How to Launch Snapchat Seamlessly on Mac Systems for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-xiaomi-redmi-a2-by-drfone-android/"><u>How to Show Wi-Fi Password on Xiaomi Redmi A2</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-foremost-sites-for-digital-type-creation/"><u>In 2024, Foremost Sites for Digital Type Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-favorite-apps-on-new-windows-11-devices/"><u>Guide to Reinstalling Favorite Apps on New Windows 11 Devices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-free2x-cam-recorders/"><u>[New] 2024 Approved  The Ultimate Guide to Free2X Cam Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-update-notifications-on-windows/"><u>How to Disable Update Notifications on Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-power-up-your-gym-sessions-with-these-top-20-songs/"><u>[New] Power Up Your Gym Sessions with These Top 20 Songs</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-error-x-on-windows-a-guide-to-email-repair/"><u>Decoding Error X on Windows: A Guide to Email Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-on-iphone-14ipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock on iPhone 14/iPad/iPod</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-print-service-stopped-issue-on-windows-pc/"><u>Addressing Print Service Stopped Issue on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/from-edge-to-frontline-quick-fixes-for-lost-off-screen-windows/"><u>From Edge to Frontline: Quick Fixes for Lost Off-Screen Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-perfecting-images-slideshow-and-fix-in-windows-11-photos-app/"><u>Guide to Perfecting Images: Slideshow & Fix in Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-unique-windows-11-search-interface/"><u>Crafting a Unique Windows 11 Search Interface</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-choosing-youtube-downloader-apps-on-your-android-device-for-2024/"><u>[New] Choosing YouTube Downloader Apps on Your Android Device for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-get-ready-to-lol-the-funniest-face-swap-apps-for-ios-and-android/"><u>Updated 2024 Approved Get Ready to LOL The Funniest Face Swap Apps for iOS and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-enable-a-search-bar-on-win11s-taskbar/"><u>Elevate Your Productivity: Enable a Search Bar on Win11's Taskbar</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/advanced-techniques-for-smartphone-screenshots-for-2024/"><u>Advanced Techniques for Smartphone Screenshots for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-stepwise-quietening-routine-for-mixes/"><u>In 2024, Stepwise Quietening Routine for Mixes</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-cutting-edge-content-creation-mastering-how-to-trim-videos-in-real-time-on-vimeo/"><u>[Updated] 2024 Approved  Cutting-Edge Content Creation  Mastering How to Trim Videos in Real Time on Vimeo</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-analyzing-the-significance-of-instagrams-selfie-verification/"><u>[New] Analyzing the Significance of Instagram's Selfie Verification</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-notable-20-free-non-exclusive-pubg-screenshots/"><u>2024 Approved  Notable 20 Free, Non-Exclusive PUBG Screenshots</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-purpose-behind-windows-11-s-mode-feature/"><u>Deciphering the Purpose Behind Windows 11 S Mode Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/applications-and-their-unique-run-notations-explored/"><u>Applications & Their Unique Run Notations Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-troubleshooters-not-working-in-windows-10-and-11/"><u>How to Fix the Troubleshooters Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-copyright-concern-unscheduled-video-displacement-for-2024/"><u>[New] Copyright Concern  Unscheduled Video Displacement for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-streamline-your-snapchat-chat-and-calls-with-3-key-steps/"><u>2024 Approved  Streamline Your Snapchat Chat and Calls with 3 Key Steps</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/brief-vignettes-facebooks-fast-lane-for-2024/"><u>Brief Vignettes  Facebook’s Fast Lane for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-realme-c53-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Realme C53 Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-elevate-your-iphone-photography-dive-into-hdr/"><u>[New] How to Elevate Your iPhone Photography  Dive Into HDR</u></a></li>
</ul></div>
