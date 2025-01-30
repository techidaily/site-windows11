---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2025-01-25T17:12:19.324Z
updated: 2025-01-30T01:32:21.348Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-perfecting-the-art-of-hd-broadcasting-on-facebookshiftscreenresolution/"><u>[New] 2024 Approved Perfecting the Art of HD Broadcasting on Facebook'shift_screen_resolution</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/pin-the-web-advanced-tips-for-video-orientation-in-youtube-for-2024/"><u>[New] Spin the Web Advanced Tips for Video Orientation in YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-art-of-editing-crafting-your-youtube-story-with-precision/"><u>[New] The Art of Editing Crafting Your YouTube Story with Precision</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-the-ultimate-guide-to-crafting-breathtaking-time-lapses-with-gopro/"><u>[Updated] The Ultimate Guide to Crafting Breathtaking Time-Lapses with GoPro</u></a></li>
<li><a href="https://fox-links.techidaily.com/find-the-best-value-top-6-budget-friendly-camera-options/"><u>Find the Best Value Top 6 Budget-Friendly Camera Options</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oppo-k11x-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-wipeout-wsl-entirely-from-windows-11-system/"><u>How To Wipeout WSL Entirely From Windows 11 System</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-lava-storm-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Lava Storm 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hero4-black-vs-hero4-silver/"><u>In 2024, Hero4 Black Vs Hero4 Silver</u></a></li>
<li><a href="https://some-tips.techidaily.com/msix-vs-advanced-installer-evaluating-your-options-for-windows-software-packaging-tools/"><u>MSIX vs Advanced Installer: Evaluating Your Options for Windows Software Packaging Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/network-assurance-on-pc-ensuring-reliable-win-net-access/"><u>Network Assurance on PC: Ensuring Reliable Win Net Access</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-opengl-error-code-3-in-os-11/"><u>Overcoming the Challenge of OpenGL Error Code 3 in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/project-mastery-exclusive-key-maneuvers/"><u>Project Mastery: Exclusive Key Maneuvers</u></a></li>
<li><a href="https://windows11.techidaily.com/teleport-yourself-to-the-network-with-these-tips-for-win/"><u>Teleport Yourself to the Network with These Tips for Win</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-game-plan-for-first-time-diablo-gamers/"><u>The Ultimate Game Plan for First-Time Diablo Gamers</u></a></li>
<li><a href="https://win-hacks.techidaily.com/top-choice-instantaneous-file-copy-apps-for-seamless-change-integration/"><u>Top Choice Instantaneous File Copy Apps for Seamless Change Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-winning-edge-fps-tips-for-valorant-on-pc/"><u>Unlock Your Winning Edge: FPS Tips for Valorant on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-best-game-install-location-on-windows-xbox/"><u>Unlocking the Best Game Install Location on Windows Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-grit-in-valorant-tackling-lags-head-on/"><u>Winning Grit in Valorant: Tackling Lags Head-On</u></a></li>
</ul></div>

