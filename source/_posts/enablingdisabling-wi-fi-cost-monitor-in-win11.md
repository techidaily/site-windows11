---
title: Enabling/Disabling Wi-Fi Cost Monitor in Win11
date: 2025-01-08T20:31:45.845Z
updated: 2025-01-10T22:33:40.016Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Wi-Fi Cost Monitor in Win11
excerpt: This Article Describes Enabling/Disabling Wi-Fi Cost Monitor in Win11
keywords: Win11 Wi-Fi Cost Tracking,Disable Wi-Fi Meter,Enable Wi-Fi Meter Off,Win11 Wi-Fi Usage Monitor,Turn On/Off Wi-Fi Meter,Windows 11 Wi-Fi Pricing,Wi-Fi Cost Indicator Win11
thumbnail: https://thmb.techidaily.com/34898e0ebb1abca68099d2acba8fac3a4c33b87872f768fed60cc168fcf66601.jpg
---

## Enabling/Disabling Wi-Fi Cost Monitor in Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-a-step-by-step-approach-for-effective-spotify-marketing/"><u>[New] 2024 Approved A Step-by-Step Approach for Effective Spotify Marketing</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-diy-filmmaking-for-youtube-personalities/"><u>[New] 2024 Approved DIY Filmmaking for YouTube Personalities</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-core-auditory-stimulation-channels/"><u>[New] In 2024, Core Auditory Stimulation Channels</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tactical-co-creation-youtube-and-brand-joint-efforts/"><u>[Updated] Tactical Co-Creation YouTube and Brand Joint Efforts</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-at-your-fingertips-uninstall-microsoft-edge-from-w11/"><u>Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-unlock-recovery-options-for-your-pc/"><u>Efficiently Unlock Recovery Options for Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-capabilities-a-comprehensible-wintoy-approach/"><u>Elevate PC Capabilities: A Comprehensible WinToy Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-expertise-with-vivetool-on-windows/"><u>Elevate Your PC Expertise with ViVeTool on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/ultimate-guide-to-remote-podcast-recording/"><u>Ultimate Guide to Remote Podcast Recording</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-and-utilizing-adobes-storage-plus-insights-into-alternate-vaulting-services-for-2024/"><u>Understanding and Utilizing Adobe's Storage, Plus Insights Into Alternate Vaulting Services for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-apple-iphone-xr-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and Apple iPhone XR</u></a></li>
</ul></div>

