---
title: "Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
date: 2024-06-25T12:28:15.712Z
updated: 2024-06-26T12:28:15.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
excerpt: "This Article Describes Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11"
keywords: Wi-Fi Cost Meter Guide,Windows 11 Wi-Fi Control,Manage Wi-Fi Expenses,Disable Wi-Fi Monitoring,Enabling/Disabling Wi-Fi,Windows 11 Network Settings,Optimize Wi-Fi Costs in Win11
thumbnail: https://thmb.techidaily.com/c54c6148123e508341809a9f8c11fb6ca2958cb786ab2471b34202053c6a9248.jpg
---

## Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11

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
<li><a href="https://windows11.techidaily.com/taskbar-timeline-microsofts-ui-evolution/"><u>Taskbar Timeline: Microsoft's UI Evolution</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-enrollment-in-windows-11s-beta-testers-club/"><u>Mastering Enrollment in Windows 11'S Beta Testers Club</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-laptops-a-forward-looking-2024-review/"><u>Best Windows Laptops: A Forward-Looking 2024 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-updates-from-triggering-at-system-startup/"><u>Preventing Discord Updates From Triggering at System Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/facing-down-rounded-corners-in-windows-11/"><u>Facing Down Rounded Corners in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-effective-network-sharing-tools-tech-giants-face-off/"><u>Determining Effective Network Sharing Tools: Tech Giants Face-Off</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-approach-to-bypass-cant-add-your-folder-now-error-in-windows-onedrive-drive/"><u>Swift Approach to Bypass 'Can't Add Your Folder Now' Error in Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-restoring-windows-defender-threat-shield-functionality/"><u>Quick Fixes: Restoring Windows Defender Threat Shield Functionality</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-the-essential-guide-to-youtube-edits-with-premiere-pro/"><u>2024 Approved  The Essential Guide to YouTube Edits with Premiere Pro</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-are-you-looking-for-the-best-video-marketing-agency-to-help-your-business-grow-exponentially-with-engaging-video-content-here-is-how-to-find-a-high-qual/"><u>New Are You Looking for the Best Video Marketing Agency to Help Your Business Grow Exponentially with Engaging Video Content? Here Is How to Find a High-Quality Video Marketing Company that Takes Your Videos to the Next Level</u></a></li>
<li><a href="https://extra-tips.techidaily.com/optimal-activities-coexisting-with-listening-podcasts/"><u>Optimal Activities Coexisting with Listening Podcasts</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-the-photographers-companion-to-master-color-correction-top-11/"><u>[New] In 2024, The Photographer's Companion to Master Color Correction (Top 11)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/understanding-your-chances-for-regular-youtube-payments/"><u>Understanding Your Chances for Regular YouTube Payments</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/jujutsu-kaisen-in-action-making-memorable-tiktok-videos-for-2024/"><u>Jujutsu Kaisen in Action  Making Memorable TikTok Videos for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/balancing-consistency-and-quality-a-key-to-increasing-youtube-viewership-for-2024/"><u>Balancing Consistency & Quality  A Key to Increasing YouTube Viewership for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-handbook-for-youtube-video-creation/"><u>In 2024, The Ultimate Handbook for YouTube Video Creation</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-realme-c67-4g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Realme C67 4G Find My Friends No Location Found? | Dr.fone</u></a></li>
</ul></div>
