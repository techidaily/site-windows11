---
title: How to Change Your Username in Windows 11
date: 2024-07-11T21:54:09.179Z
updated: 2024-07-12T21:54:09.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change Your Username in Windows 11
excerpt: This Article Describes How to Change Your Username in Windows 11
keywords: Changing Windows Username,Win11 New Username,Update Windows ID,Altering PC Login Name,Customize Windows Account,Edit Windows User,Modify Windows Username
thumbnail: https://thmb.techidaily.com/5b0ce9c020094ad31bdc87530c31e032109184ed98794f1ba27d0b681ad3c785.jpg
---

## How to Change Your Username in Windows 11

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
<li><a href="https://windows11.techidaily.com/avoiding-data-disaster-save-and-recover-snippets/"><u>Avoiding Data Disaster: Save & Recover Snippets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/step-by-step-techniques-for-google-meet-coordination-for-2024/"><u>Step-by-Step Techniques for Google Meet Coordination for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-easy-to-use-online-editors-for-quick-postings/"><u>[Updated] In 2024, Free, Easy-to-Use Online Editors for Quick Postings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-muted-system-sound-output-quickly/"><u>How to Reactivate Muted System Sound Output Quickly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-the-latest-100plus-best-tiktok-captions-to-improve-your-next-post/"><u>New 2024 Approved The Latest 100+ Best TikTok Captions to Improve Your Next Post</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-interlace-snaps-a-guide-to-crafting-picture-panoramas/"><u>[Updated] Interlace Snaps  A Guide to Crafting Picture Panoramas</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-windows-innovations-to-enrich-macos/"><u>Leveraging Windows Innovations to Enrich macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-boosting-speed-of-steam-on-windows/"><u>Overcoming Sluggishness: Boosting Speed of Steam on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-optimizing-nintendo-switch-controller-for-steam-games/"><u>[Updated] Optimizing Nintendo Switch Controller for Steam Games</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-between-wi-fi-and-ethernet-in-windows/"><u>Bridging the Gap Between Wi-Fi and Ethernet in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tip-unearthing-windows-apps-installed-locations-quickly/"><u>Pro Tip: Unearthing Windows Apps' Installed Locations Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-account-lockout-count-after-multiple-login-failures-in-windows-11/"><u>Revising Account Lockout Count After Multiple Login Failures in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-windows-performance-with-extended-display-setup/"><u>Master Window's Performance With Extended Display Setup</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-9-premier-apps-for-extracting-and-saving-youtube-videos-on-android/"><u>[Updated] 2024 Approved  9 Premier Apps for Extracting and Saving YouTube Videos on Android</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-revamp-photos-essential-color-correction-steps/"><u>In 2024, Revamp Photos  Essential Color Correction Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-windows-interface-crashing/"><u>Immediate Actions for Windows Interface Crashing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-11-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-iphone-photographic-file-import-failures-on-windows-pcs/"><u>Handling iPhone Photographic File Import Failures on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-manage-windows-deletion-prompt-actions/"><u>Efficiently Manage Windows' Deletion Prompt Actions</u></a></li>
<li><a href="https://driver-install.techidaily.com/boosting-performance-revamping-msi-drivers-on-legacy-oss/"><u>Boosting Performance: Revamping MSI Drivers on Legacy OSs</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-windows-file-explorer-directly-via-onedrive/"><u>Launching Windows File Explorer Directly via OneDrive</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-essential-3-step-copywriting-blueprint-for-effective-fb-campaigns-for-2024/"><u>[New] Essential 3-Step Copywriting Blueprint for Effective FB Campaigns for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-system-stability-automatic-windows-and-amd-driver-shift/"><u>Elevate System Stability: Automatic Windows & AMD Driver Shift</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/navigating-youtubes-landscape-a-beginners-primer/"><u>Navigating YouTube's Landscape  A Beginner's Primer</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskmgr-with-command-line-interface-cli-feature/"><u>Enhance TaskMgr with Command Line Interface (CLI) Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-perfect-every-post-automated-mac-methods-for-instagram-video-sizing/"><u>[New] 2024 Approved  Perfect Every Post  Automated Mac Methods for Instagram Video Sizing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-maximize-your-fb-videos-full-screen-mode-guide-2023/"><u>[Updated] Maximize Your FB Videos  Full-Screen Mode Guide 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-programs-making-movies-from-picture-files/"><u>[New] Optimal Programs  Making Movies From Picture Files</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-excessive-cpu-load-by-dropbox-app-on-windows-devices/"><u>Addressing Excessive CPU Load by Dropbox App on Windows Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-complete-2024-video-show-analysis-and-tips/"><u>[Updated] Complete 2024 Video Show Analysis & Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-installs-windows-11-with-winstall/"><u>Mastering Batch Installs: Windows 11 with Winstall</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963298888-new-have-you-tried-a-discord-boost-before-what-does-a-discord-server-boost-entail-and-is-it-worthwhile-what-are-the-advantages-heres-a-quick-guide-to-assist/"><u>New Have You Tried a Discord Boost Before? What Does a Discord Server Boost Entail, and Is It Worthwhile? What Are the Advantages? Heres a Quick Guide to Assist You in Making Your Decision for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-thermal-management-directive-for-pcs/"><u>Restoring Lost Thermal Management Directive for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-fixing-nvidias-unreachable-error/"><u>Guiding Users Through Fixing NVIDIA's 'Unreachable' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/flushing-dns-on-windows-best-practices/"><u>Flushing DNS on Windows: Best Practices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-through-the-complexities-of-canon-time-lapse/"><u>Navigating Through the Complexities of Canon Time-Lapse</u></a></li>
<li><a href="https://windows11.techidaily.com/amp-up-your-vehicles-performance-with-these-top-windows-upgraders/"><u>Amp up Your Vehicle's Performance with These Top Windows Upgraders</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-correct-windows-installation-glitch-xc004f050/"><u>Method to Correct Windows Installation Glitch Xc004f050</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/purify-your-setup-tiny11s-no-fuss-features/"><u>Purify Your Setup: Tiny11's No-Fuss Features</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-system-resource-usage-details-to-the-windows-system-tray/"><u>How to Add System Resource Usage Details to the Windows System Tray</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-the-narrator-in-windows-11/"><u>How to Start the Narrator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-login-hiccup-zero-based-code-error-on-win11/"><u>Fixing OneDrive Login Hiccup: Zero-Based Code Error on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-notepad-abrupt-closures/"><u>Overcoming Windows Notepad Abrupt Closures</u></a></li>
</ul></div>
