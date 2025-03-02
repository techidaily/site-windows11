---
title: "Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
date: 2025-02-27T18:13:50.859Z
updated: 2025-03-02T10:43:31.287Z
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

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

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

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

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
<li><a href="https://some-approaches.techidaily.com/new-unleashing-premium-soundtracks-in-your-mp4-files-the-2024-guide/"><u>[New] Unleashing Premium Soundtracks in Your MP4 Files – The 2024 Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-composing-the-unseen-background-sounds-for-movie-teasers/"><u>[Updated] Composing the Unseen Background Sounds for Movie Teasers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-guide-to-seamlessly-share-your-igtv-story/"><u>2024 Approved Guide to Seamlessly Share Your IGTV Story</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-video-editing-software-to-blur-faces-in-video/"><u>Best Video Editing Software to Blur Faces in Video</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/boost-your-internet-reach-on-a-budget-the-tp-link-re200-ac750-range-extender-reviewed-thoroughly/"><u>Boost Your Internet Reach on a Budget: The TP-Link RE200 AC750 Range Extender Reviewed Thoroughly</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-non-scrolling-issue-unlock-cells-in-excel-windows/"><u>Fix Non-Scrolling Issue: Unlock Cells in Excel (Windows)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/open-locked-windows-shared-files-now/"><u>Open Locked Windows Shared Files Now</u></a></li>
<li><a href="https://android-frp.techidaily.com/oppo-f23-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Oppo F23 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-unconnected-error-with-geforce-experience-on-pc/"><u>Rectifying Unconnected Error with GeForce Experience on PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915191288-revitalize-performance-in-windows-11-learn-to-update-device-drivers-effortlessly/"><u>Revitalize Performance in Windows 11 - Learn to Update Device Drivers Effortlessly</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-oppo-reno-8t-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Oppo Reno 8T FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-mastery-tips-for-multitasking-windows-11/"><u>Supercharge Your Workday: Mastery Tips for Multitasking Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-windows-11s-protected-mode-graphics/"><u>Supercharging Windows 11'S Protected Mode Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072efd-on-windows-devices/"><u>Troubleshooting Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-print-potential-strategies-to-fix-slide-show-problems-on-windows/"><u>Unlocking Your Print Potential: Strategies to Fix Slide Show Problems on Windows</u></a></li>
</ul></div>

