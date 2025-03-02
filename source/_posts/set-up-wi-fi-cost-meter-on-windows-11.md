---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2025-02-24T05:28:27.628Z
updated: 2025-03-02T05:38:58.102Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Set Up Wi-Fi Cost Meter on Windows 11
excerpt: This Article Describes Set Up Wi-Fi Cost Meter on Windows 11
keywords: Wifi Cost Monitoring,Wi-Fi Usage Tracking,Wi-Fi Expense Meter,Network Bill Tracker,Windows 11 Wi-Fi Meter,Data Usage Analysis,ISP Billing Tool
thumbnail: https://thmb.techidaily.com/e849b3433ae861a98a41e422ed19bb8502406c23628dc5175ac052fdfbe1c181.jpg
---

## Set Up Wi-Fi Cost Meter on Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-captivating-clips-transforming-footage-vertically-in-final-cut-x/"><u>[New] 2024 Approved Captivating Clips Transforming Footage Vertically in Final Cut X</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-hitting-the-high-score-in-ps4-game-capture-mastery/"><u>[New] 2024 Approved Hitting the High Score in PS4 Game Capture Mastery</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-ranking-the-best-cameras-that-dont-feature-a-gopro-brand/"><u>[New] 2024 Approved Ranking the Best Cameras That Don't Feature a GoPro Brand</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-complete-guide-to-selecting-high-performance-fpv-drone-propellers/"><u>[Updated] The Complete Guide to Selecting High-Performance FPV Drone Propellers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-unlock-your-earning-potential-maximizing-youtube-revenue-on-mobile/"><u>2024 Approved Unlock Your Earning Potential Maximizing YouTube Revenue on Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-fixes-for-the-common-spotify-errors-on-win11/"><u>Easy Fixes for the Common Spotify Errors on Win11</u></a></li>
<li><a href="https://article-helps.techidaily.com/elevate-video-quality-converters-triad-of-tactics/"><u>Elevate Video Quality Converter's Triad of Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-inspiring-window-decorations/"><u>Festive Glamour: Inspiring Window Decorations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-re-position-your-qbittorrent-on-different-windows-devices/"><u>How to Re-Position Your qBittorrent on Different Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-life-easier-deploying-multiple-apps-on-windows-11-via-winstall/"><u>Making Your Life Easier: Deploying Multiple Apps on Windows 11 via Winstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-task-manager-advanced-filters-personalized-theme-setting-guide-windows-11/"><u>Master Task Manager: Advanced Filters, Personalized Theme Setting Guide (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-wi-fi-mouse-simple-steps-for-windows-users/"><u>Reignite Your Wi-Fi Mouse - Simple Steps for Windows Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-your-google-hangouts-audio-issue-mic-troubleshooting-guide/"><u>Resolving Your Google Hangouts Audio Issue - Mic Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-and-restore-absent-cameras-to-system-list/"><u>Reveal and Restore Absent Cameras to System List</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-the-day-unraveling-steam-storage-errors/"><u>Saving the Day: Unraveling Steam Storage Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-scaling-problems-in-windows-high-dpi-environments/"><u>Solutions for Scaling Problems in Windows High DPI Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-windows-admin-managed-security-issues/"><u>Solutions to Windows Admin-Managed Security Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workflow-with-enabled-wsl-support/"><u>Streamline Your Workflow with Enabled WSL Support</u></a></li>
<li><a href="https://techtrends.techidaily.com/taylor-swift-in-cinema-how-to-enjoy-her-movies-chronologically/"><u>Taylor Swift in Cinema: How to Enjoy Her Movies Chronologically</u></a></li>
</ul></div>

