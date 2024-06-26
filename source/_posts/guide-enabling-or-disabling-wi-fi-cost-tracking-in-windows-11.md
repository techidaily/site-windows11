---
title: "Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
date: 2024-06-25T12:34:57.987Z
updated: 2024-06-26T12:34:57.987Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
excerpt: "This Article Describes Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
keywords: Wi-Fi Cost Monitoring,Wifi Expense Control,Wi-Fi Usage Tracking,Windows 11 Wi-Fi Tracking,Enable/Disable Wi-Fi Costs,Windows Wi-Fi Expense Management,Tracking Wi-Fi Usage in Windows 11
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://windows11.techidaily.com/decrypt-the-mystery-of-win11-blue-screen-with-11-hacks/"><u>Decrypt the Mystery of Win11 Blue Screen with 11 Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-download-efficiency-boosting-steam-and-windows-speed/"><u>Improve Download Efficiency: Boosting Steam and Windows Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reworking-default-view-of-task-manager-in-win11/"><u>Reworking Default View of Task Manager in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-oddities-in-windows-11-visual-language/"><u>Uncovering the Oddities in Windows 11 Visual Language</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-stability-the-definitive-net-window-repair-guide-max-156/"><u>Regain Stability: The Definitive .NET Window Repair Guide (Max 156)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-debut-video-capture-review-for-2024/"><u>[Updated] Debut Video Capture Review for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/your-personal-playlist-on-the-go-for-2024/"><u>Your Personal Playlist On-the-Go for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevate-your-videos-start-with-top-youtube-intro-tips/"><u>[Updated] In 2024, Elevate Your Video's Start with Top YouTube Intro Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-copyright-clarity-for-instagram-tracks/"><u>[Updated] Copyright Clarity for Instagram Tracks</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-make-an-emoji-of-yourself-on-mobile-emoji-yourself-for-2024/"><u>New How to Make an Emoji of Yourself on Mobile ? Emoji Yourself for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-discovering-charismatic-faces-on-your-snaps/"><u>In 2024, Discovering Charismatic Faces on Your Snaps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-facebook-live-mastery-making-the-most-of-real-time-sharing/"><u>[Updated] In 2024, Facebook Live Mastery  Making the Most of Real-Time Sharing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-action-hunting-cameras-of-2023/"><u>2024 Approved  Best Action Hunting Cameras of 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-canons-lut-collection-maximize-image-impact-free-and-paid-choices/"><u>[Updated] Canon’s LUT Collection  Maximize Image Impact - FREE & Paid Choices</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-xiaomi-redmi-a2plus-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Xiaomi Redmi A2+? Heres A Full Solution | Dr.fone</u></a></li>
</ul></div>
