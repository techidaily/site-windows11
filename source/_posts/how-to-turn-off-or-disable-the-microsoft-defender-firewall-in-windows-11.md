---
title: How to Turn Off or Disable the Microsoft Defender Firewall in Windows 11
date: 2024-07-11T21:49:51.461Z
updated: 2024-07-12T21:49:51.461Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Off or Disable the Microsoft Defender Firewall in Windows 11
excerpt: This Article Describes How to Turn Off or Disable the Microsoft Defender Firewall in Windows 11
keywords: Turn Off Firewall,Disable Windows Defender,Stop Firewall Service,Firewall Disable Process,Ending Microsoft Defender,Turn Off Windows Firewall,Bypass Defender Firewall
thumbnail: https://thmb.techidaily.com/59ebf54bbd2728b1cee67f80e126289c9f6737977aace37b8f0906719738cd6b.jpg
---

## How to Turn Off or Disable the Microsoft Defender Firewall in Windows 11

 While firewalls can protect you from malicious online threats, there may be times when it is necessary to disable them for certain tasks or applications. While it's usually not a good idea to disable the firewall for long periods of time, doing so for a few seconds while you troubleshoot a problem is usually safe.

 As such, let's explore how to turn off or disable the Microsoft Defender firewall safely and securely in Windows 11\.

## How Important Is the Microsoft Defender Firewall?

 A firewall acts as a shield against unwanted intrusions and prevents external connections from accessing your system without permission. When disabled, your computer becomes vulnerable, and you should take extra precautions while online.

 To ensure maximum security while disabling your firewall, always make sure that other protective measures such as antivirus programs are running in the background. Once these have been taken care of, you can disable the firewall on your Windows 11 PC. Here's how to do this:

## 1\. How to Disable the Firewall Using Windows Security

 The Windows Security program allows you to disable the firewall in Windows 11\. It is the most straightforward way to disable Microsoft Defender Firewall and you don’t need to have any additional tools or software installed. Here's how:

1. Click on **Start** and search for “Windows Security”.
2. Then select the result from the top of the list.
3. Once you are in Windows Security, click on the **Firewall & network protection** option.
4. Select the **Public network** or **Private network** profile and turn off the firewall for that selection.  
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
![Turn off the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-through-control-panel.jpeg)
4. Then select **Turn off Windows Defender Firewall (not recommended)** for each network setting.
5. Click **OK** to save your changes.

## 3\. How to Disable the Firewall Using Command Prompt

 If you are comfortable using the command line, then you can also disable your firewall through the Command Prompt. Here’s how:

 Press **Win + S** on your keyboard to open the Windows search tool. Now type "cmd" in the search field and press **Ctrl + Shift + Enter** on your keyboard. This will open Command Prompt with admin rights.

 Once you are in the Command Prompt, type in the following command and hit **Enter:**

netsh advfirewall set currentprofile state off

 Running the above command will turn off the firewall for the current network profile.

 If you wish to disable the firewall for the domain network profile, copy and paste the following command, and hit **Enter**:

netsh advfirewall set domainprofile state off

 Similarly, you can disable the firewall for the private network profile. To do this, copy and paste the following command and hit **Enter**:

netsh advfirewall set privateprofile state off

 For the public network profile, type the following command in the Command Prompt window and press **Enter**:

netsh advfirewall set publicprofile state off

 Alternatively, you can disable the Defender Firewall for all network profiles, such as domain, private, and public, with just one command. To do this, copy and paste the below command and hit **Enter**:

netsh advfirewall set allprofiles state off

 In this way, you can disable the firewall according to your selected network profiles.

## 4\. How to Turn Off the Firewall via PowerShell

 Windows PowerShell is an important tool that can be used to manage many aspects of the Windows operating system. You can also use it to disable the Microsoft Defender Firewall.

 To do this, open a PowerShell window as an administrator and run the following commands:

![Turn Off the Firewall Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-via-powershell.jpg)

Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False

 After running the above command, the firewall will be disabled for all network profiles simultaneously.

## 5\. How to Turn Off the Firewall Using Group Policy Editor

 The Group Policy Editor is a powerful system resource that can be used to manage different settings on all Windows computers. With this tool, you can disable your firewall, but it only works with Windows Professional and Enterprise. If you are using Windows Home Edition, you need to [activate the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) in order to access it.

 To disable firewall settings using the Local group policy editor, follow these steps:

1. Right-click on Start and select **Run** from the menu list.
2. Type **gpedit.msc** in the dialog box and click **OK** or press Enter on your keyboard.
3. Inside the Group Policy Editor window, navigate to the following:  
Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Standard Profile
4. On the right side of the window, double-click the policy called **Windows Defender Firewall: Protect all network connections**.  
![Turn Off the Firewall Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-group-policy-editor.jpg)
5. Next, choose **Disabled** from the dialog box that appears.
6. When you're done making your changes, click **Apply** \> **OK**.
7. For the changes to take effect, restart your computer after completing the above steps.

## 6\. How to Turn Off the Firewall Using Registry Editor

 Windows also has a method for disabling the firewall that involves editing the registry. It is an advanced feature that should only be used by experienced computer users, as incorrect usage can cause serious damage to your computer.

 When using the Registry Editor, it is important not to modify any other settings than those related directly to the firewall. Making unwanted changes could potentially lead to instability within your system, including a decrease in performance or even the complete failure of your operating system. If you're ready to use this method, make sure you [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) first.

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Once you're in, navigate to the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\WindowsFirewall\StandardProfile
3. Right-click StandardProfile and select **New > DWORD (32-bit) Value**.
4. Specify **EnableFirewall** as the key name.
5. Double-click it and enter **0** in the Value data field.  
![Turn Off the Firewall Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-registry-editor.jpg)
6. Once you have made the changes, click **OK**.

 When you have completed all the steps above, close the Registry Editor and restart your computer.

## Disable the Firewall With Ease on Windows

 You may want to disable the firewall for testing, developing applications, or playing online games. However, disabling the firewall can have risks, and you should always exercise caution. In case you need to do it, this guide explains multiple ways to do it, such as via Windows Security, Control Panel, Command Prompt, and more.


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
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-nova-y91-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Nova Y91</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-in-calendar-design-a-windows-outlook-method/"><u>Unleashing Creativity in Calendar Design - A Windows Outlook Method</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-remove-option-for-pin-access-control/"><u>Reviving Disabled 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://video-capture.techidaily.com/tailored-techniques-for-logging-high-quality-roblox-sessions-on-a-mac-for-2024/"><u>Tailored Techniques for Logging High-Quality Roblox Sessions on a Mac for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-pixels-for-every-window-11-display/"><u>Perfect Pixels for Every Window 11 Display</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-of-error-code-0x0000004e/"><u>Overcoming the Obstacle of Error Code 0X0000004E</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-techniques-to-master-telegram-web-interface/"><u>Comprehensive Techniques to Master Telegram Web Interface</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-smooth-screenshots-selecting-the-ultimate-handheld-stabilizer/"><u>In 2024, Smooth Screenshots  Selecting the Ultimate Handheld Stabilizer</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-searches-using-everythingapp/"><u>Streamline Windows Searches Using EverythingApp</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-a-quick-guide-to-firefoxs-innovative-pip-mode/"><u>2024 Approved  A Quick Guide to Firefox's Innovative PIP Mode</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-engaging-videos-with-the-ken-burns-effect-a-step-by-step-tutorial-for-2024/"><u>Create Engaging Videos with the Ken Burns Effect A Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/applications-and-their-unique-run-notations-explored/"><u>Applications & Their Unique Run Notations Explored</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-honor-play-8t-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-win-error-due-to-missing-mfc71udll/"><u>Troubleshooting Absence: Win Error Due to Missing Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-microsoft-teams-freeze-in-ws11ws10/"><u>Strategies to Prevent Microsoft Teams Freeze in WS11/WS10</u></a></li>
<li><a href="https://windows11.techidaily.com/purging-protection-logs-on-windows-1011-with-ease/"><u>Purging Protection Logs on Windows 10/11 with Ease</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-proficiency-through-practice-using-ez-grabber/"><u>In 2024, Proficiency Through Practice  Using EZ Grabber</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-print-service-stopped-issue-on-windows-pc/"><u>Addressing Print Service Stopped Issue on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-saving-paradox-modern-standbys-dilemni/"><u>Windows' Power-Saving Paradox: Modern Standby's Dilemni</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-optimize-your-view-amazon-prime-video-aspect-ratio-hacks/"><u>In 2024, Optimize Your View Amazon Prime Video Aspect Ratio Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-steam-offline-status-via-win-tricks/"><u>Re-Establish Steam Offline Status via Win Tricks</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-elevate-video-quality-mastering-fb-1080p-streams/"><u>[New] Elevate Video Quality  Mastering FB 1080P Streams</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-easy-to-use-tiktok-video-to-mp4-tool/"><u>2024 Approved  Easy-to-Use TikTok Video to MP4 Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-installer-package-fails-on-windows-11/"><u>Troubleshooting Installer Package Fails on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/charting-new-pathways-in-art-an-exclusive-look-at-the-top-10-low-cost-creator-platforms-on-youtube/"><u>Charting New Pathways in Art  An Exclusive Look at the Top 10 Low-Cost Creator Platforms on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-hidden-desktop-icons-on-the-latest-windows/"><u>Revive Hidden Desktop Icons on the Latest Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-content-discovery-with-powerful-title-and-tag-use/"><u>In 2024, Mastering Content Discovery with Powerful Title & Tag Use</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-unique-windows-11-search-interface/"><u>Crafting a Unique Windows 11 Search Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-connection-issues-dissolving-ea-errors/"><u>Winning Over Connection Issues: Dissolving EA Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-the-art-of-digital-expression/"><u>Windows 11 Makeover: The Art of Digital Expression</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-honor-magic5-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Honor Magic5 Ultimate to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-display-settings-install-hp-graphics-in-win11/"><u>Streamline Display Settings: Install HP Graphics in Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-samsung-galaxy-a23-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Samsung Galaxy A23 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-smooth-playback-on-instagram-videos/"><u>[New] Mastering Smooth Playback on Instagram Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/six-secrets-to-spinning-pictures-in-w11-os/"><u>Six Secrets to Spinning Pictures in W11 OS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-11-pro-max-learn-all-4-methods-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone 11 Pro Max? Learn All 4 Methods</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-bust-a-smile-well-up-in-tears-with-top-10-instagram-meme-groups/"><u>[Updated] In 2024, Bust a Smile, Well Up in Tears with Top 10 Instagram Meme Groups</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-non-responsive-function-keys-in-windows-11/"><u>Solve: Non-Responsive Function Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-cost-effective-windows-11-keys/"><u>Unveiling Cost-Effective Windows 11 Keys</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-apple-iphone-15-plus-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking Apple iPhone 15 Plus Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-art-of-memetic-mastery/"><u>In 2024, The Art of Memetic Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-superiority-persistent-high-privilege-terminal/"><u>Uncomplicated Superiority: Persistent High-Privilege Terminal</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/breaking-down-barriers-combining-obs-with-zoom/"><u>Breaking Down Barriers  Combining OBS with Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-optimal-functionality-of-add-ons-in-windows-os/"><u>Strategies to Ensure Optimal Functionality of Add-Ons in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-wi-fi-links-top-strategies-to-regain-internet-connection-on-windows-10/"><u>Reviving Lost Wi-Fi Links: Top Strategies to Regain Internet Connection on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
</ul></div>
