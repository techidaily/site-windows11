---
title: "Altering Windows 11 Identity: New UserName Guide"
date: 2024-07-11T22:17:42.908Z
updated: 2024-07-12T22:17:42.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Windows 11 Identity: New UserName Guide"
excerpt: "This Article Describes Altering Windows 11 Identity: New UserName Guide"
keywords: Win11 Username Change,NewUserWin11,AlterIdentityWin11,SetUpWin11Account,Windows11UserName,CreateWin11ID,UpdateWin11Username
thumbnail: https://thmb.techidaily.com/477a0b3e8eaad5a77258f27b87d4827ff92a53251f6cf584b61b0ab39b309f07.jpg
---

## Altering Windows 11 Identity: New UserName Guide

 Have you got tired of using the same username for a long time? Were you assigned a random username when you created your account, but now you want to add a personal touch? If you want to change your username for any reason, Windows lets you do it easily. In fact, there are numerous ways to go about this. We have listed some of the simplest ones below.

## Before We Get Started…

 Keep in mind that the first four methods discussed below can only be used to change the username of a local user account. If you use them to change the username of a Microsoft account, the change will be reversed the next time you restart your device.

 So, if you want to change your Microsoft account username, we recommend directly using the last method—changing your username from Microsoft's website. However, if you want to change the username of a local user account, you can use one of the first four methods mentioned below.

## 1\. How to Change Your Username Using the Control Panel

 The Control Panel serves as the central hub in the Windows operating system. From changing the operating system's appearance to configuring the connected hardware, the Control Panel allows users to tailor the entire OS. Among other customizations, users can change their usernames and manage their user accounts effectively.

To change your username using the Control Panel, follow these steps:

1. Type**"Control Panel"** in Windows Search and open the**Control Panel** app. (Check out [other ways to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) )
2. Select**Large icons** from the**View by** dropdown menu if it isn't already selected.
3. Go to**User Accounts** .  
![Go to User Accounts in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-go-to-user-accounts-in-windows-control-panel.jpg)
4. Click on**Change your account name** .  
![Click on Change Your Account Name in User Account Settings in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-click-on-change-your-account-name-in-user-account-settings-in-windows-control-panel.jpg)
5. Click**Yes** in the**User Account Control (UAC)** window.
6. In the**New account name** field, type your new username.
7. After that, click on**Change Name** .  
![Click on Change Name After Entering the New Username](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-click-on-change-username-after-entering-the-new-username.jpg)
8. For this change to take effect, you need to sign out of your account and sign back in.

## 2\. How to Change Your Username Using the Run Command

 Using the Run command, Windows users can access any location on a computer whose path is known. It eliminates the need to navigate through numerous folders to reach our destination.

 Using this utility, we can access the User Accounts settings via a simple command, "netplwiz," which allows us to access the dedicated account management panel. From there, you can easily change your username.

To change your username using the Run command, follow these steps:

1. Press**Win + R** to launch the**Run command** .
2. Enter**"netplwiz"** in the**Run command** field and press**Enter** .  
![Run Netplwiz Command in the Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-run-netplwiz-command-in-the-windows-run-command.jpg)
3. Click**Yes** in the**User Account Control (UAC)** window.
4. In the**User Accounts** window, select the user account for which the username needs to be changed.
5. Click on**Properties** .  
![Go to Properties in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-go-to-properties-in-the-user-accounts-window.jpg)
6. In the**General** tab, you'll see your existing username. Rename it to your liking after removing it.
7. Once the new username has been added, click the**Apply** button and**OK** .  
![Click OK After Adding the New Name in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-click-ok-after-adding-the-new-name-in-the-user-accounts-window.jpg)
8. Then, log out of your account, and you'll be greeted with your new username on the sign-in screen when you sign in.

## 3\. How to Change Your Username From Local User and Group Management Tool

 If the "netplwiz" command does not work or gives an error when accessing the user account manager, you can use the local user and group management tool to change the username. This is the easiest way to modify your Windows username, as it allows you to simply rename your username directly—like you rename any folder.

 Here's how to change the username through the local user and group management tool:

1. Press**Win + R** to open the Run command.
2. Type**"lusrmgr.msc"** and press**Enter** .  
![Run lusrmgr.msc Command in Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-run-lusrmgr-msc-command-in-windows-run-command.jpg)
3. Click**"Yes"** in the**User Account Control (UAC)** window.
4. Select the**Users** tab in the left sidebar.
5. Find your account in the right pane.
6. Right-click the username and click**Rename** .  
![Click Rename by Right-clicking on the Account Name in the Local User and Group Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/8-click-rename-by-right-clicking-on-the-account-name-in-the-local-user-and-group-management-tool.jpg)
7. Enter the new username you want to use.

 Afterward, close the local user and group management tool, sign out of your account once, and you'll see your new username on the sign-in screen.

## 4\. How to Change Your Username Using Windows PowerShell

[Windows Powershell](https://www.makeuseof.com/what-is-windows-powershell/) , an object-oriented automation engine, was designed primarily for IT administrators to automate tasks. Still, its simplicity and ease of use make it worthwhile for laypeople without programming experience.

 Using its built-in cmdlets or writing custom scripts, you can make any changes to your Windows device that you usually make via GUI-based applications and settings. You can also change your username using it.

 To change your username using the Windows PowerShell, follow these steps:

1. Type**"Windows PowerShell"** in Windows Search and open the Windows PowerShell app.
2. Type the following command and press Enter to find your current username:  
Get-LocalUser
3. Add the following command after entering your current username and the one you want to switch to:  
Rename-LocalUser -Name "Enter your current username" -NewName "Enter the new username"
4. Hit**Enter** after adding the above command.  
![Changing Username in Windows Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/changing-username-in-windows-powershell.jpg)
5. Then, log back into your account after logging out.

## 5\. How to Change Your Profile Username From the Microsoft Website

 If you use a Microsoft account on your computer, change your username on the Microsoft website. To update your profile username on the Microsoft website, follow these steps:

1. Go to your account page on the [Microsoft website](https://account.microsoft.com/account/Account) .
2. Log in to your account if you haven't already.
3. Navigate to the**Your info** menu after logging in.
4. Click the**Edit name** button.  
![Click on Your info and Edit name to Change Username of a Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-your-info-and-edit-name-to-change-username-of-a-microsoft-account.jpg)
5. Remove your current username and add the one you wish to switch to.
6. After that, click**Save** .  
![Click on Save to Change the Username of Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-save-to-change-the-username-of-microsoft-account.jpg)

 Changing the username associated with your Microsoft account may not take effect immediately. Sometimes, you may not see the new username after signing out from your account once, as we do in the other methods. To prevent that from happening, we recommend [restarting your device](https://www.makeuseof.com/windows-restart-methods/) instead of just signing out.

## Change Your Username With Ease

 Your username doesn't have to remain the same for the rest of your life. If you decide to change it, you can use the first four methods listed above to change the current username (of your local user account) to the one you prefer. Regardless of which way you opt, ensure you sign out of your account once. Only then will this change take effect.

 You will need to change the username associated with your Microsoft account from the Microsoft website. Also, remember that changing your username does not automatically change the user profile folder name. Therefore, you'll have to change it separately.


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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-convert-facebook-to-mp4-hack-for-quick-access/"><u>[Updated] In 2024, Convert Facebook to MP4 – Hack for Quick Access</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-legendary-lens-showdown-sj6-vs-the-four-k-visionaries-of-xiaomi/"><u>[New] Legendary Lens Showdown  SJ6 Vs. The Four-K Visionaries of Xiaomi</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-failures-fixing-vagrant-boot-problems-win11/"><u>Bypassing Failures: Fixing Vagrant Boot Problems Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-not-working-errors-for-your-pcs-win-based-software/"><u>Bypassing 'Not Working' Errors for Your PC’s Win-Based Software</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-assessing-hdr-standards-luminances-role/"><u>2024 Approved  Assessing HDR Standards  Luminance's Role</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-the-surface-innocent-looking-apps-steal-speed-from-pcs/"><u>Beneath the Surface, Innocent-Looking Apps Steal Speed From PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-metric-monitoring-of-wifi-networks-via-win11-settings/"><u>Adjusting Metric Monitoring of Wifi Networks via Win11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-life-to-windows-11-desktops-with-interactive-wallpapers/"><u>Bring Life to Windows 11 Desktops with Interactive Wallpapers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-add-music-to-a-video-on-iphone-3-free-ways/"><u>[New] How to Add Music to a Video on iPhone [3 FREE WAYS]</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-11-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-control-panel-with-ease-on-pcs/"><u>Accessing Control Panel with Ease on PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581605473-learn-bulgarian-in-dashes-10-minute-sessions/"><u>Learn Bulgarian in Dashes - 10-Minute Sessions!</u></a></li>
<li><a href="https://windows11.techidaily.com/7-curious-design-choices-that-differ-from-w10/"><u>7 Curious Design Choices That Differ From W10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enlightened-exercits-discovering-the-most-inspiring-yogis-online/"><u>In 2024, Enlightened Exercits - Discovering the Most Inspiring Yogis Online</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-1011s-xc0f1103f-with-geforce-error/"><u>Addressing Win 10/11'S XC0F1103F with GeForce Error</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-4-best-websites-for-downloading-skype-ringtone/"><u>[New] 4 Best Websites For Downloading Skype Ringtone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-speak-with-style-mastering-the-art-of-altering-vocal-effects-on-snapchat/"><u>[Updated] Speak with Style  Mastering the Art of Altering Vocal Effects on Snapchat</u></a></li>
<li><a href="https://extra-tips.techidaily.com/your-step-by-step-guide-to-selecting-the-best-vr-headset-is-mobility-more-important-than-connections/"><u>Your Step-by-Step Guide to Selecting the Best VR Headset  Is Mobility More Important than Connections?</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-how-to-make-a-flv-photo-slideshow-with-music/"><u>Updated How to Make a FLV Photo Slideshow with Music</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-progopro-series-camera-comparison/"><u>[New] ProGoPro Series Camera Comparison</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-12-video-grabber-online-to-download-any-video-you-like/"><u>In 2024, Top 12 Video Grabber Online to Download Any Video You Like</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-enhancing-meeting-productivity-zooms-audio-and-video-recording-tips/"><u>2024 Approved  Enhancing Meeting Productivity  Zoom's Audio & Video Recording Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-best-keys-for-auto-clicking/"><u>Boost Efficiency: Best Keys for Auto Clicking</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-streamlined-approaches-to-documenting-whatsapp-discussions/"><u>[Updated] Streamlined Approaches to Documenting WhatsApp Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/backup-your-cortana-data-for-future-reference-windows/"><u>Backup Your Cortana Data for Future Reference (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-prints-with-microsofts-edge-shield-windows-11/"><u>Activating Prints with Microsoft's Edge Shield (Windows 11)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-civi-3-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Civi 3</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-pc-life-hacks-for-older-systems/"><u>Bypass Windows 11: PC Life Hacks for Older Systems</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-channel-finale-101-insider-tricks-for-successful-outros/"><u>[New] 2024 Approved  Channel Finale 101  Insider Tricks for Successful Outros</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-revealing-hidden-group-sharing-in-chat-space/"><u>2024 Approved  Revealing Hidden Group Sharing in Chat Space</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-linguistic-separator-on-win11-status-bar/"><u>Camouflage Linguistic Separator on Win11 Status Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/bigger-is-not-better-limited-minipc-zest/"><u>Bigger Is Not Better - Limited MiniPC Zest</u></a></li>
</ul></div>
