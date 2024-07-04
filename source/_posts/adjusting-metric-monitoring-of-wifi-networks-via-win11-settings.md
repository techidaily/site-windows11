---
title: Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
date: 2024-07-03T11:15:19.788Z
updated: 2024-07-04T11:15:19.788Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
excerpt: This Article Describes Adjusting Metric Monitoring of Wifi Networks via Win11 Settings
keywords: WiFi Monitoring in Windows,Win11 Wireless Settings,Wifi Performance Tracking,Network Latency Checker,Signal Strength Analysis,Optimize Win11 Wi-Fi,Metric Management Tool
thumbnail: https://thmb.techidaily.com/c35bb55569306b5428a10bd1ab44596d5c722993db7a19d5db6d527a1da8e1b4.png
---

## Adjusting Metric Monitoring of Wifi Networks via Win11 Settings

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
<li><a href="https://windows11.techidaily.com/averting-self-triggered-openings-on-msdnstoreapp/"><u>Averting Self-Triggered Openings on MSDN/StoreApp</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-slow-windows-apps-ensure-robust-web-linkage/"><u>Revive Slow Windows Apps: Ensure Robust Web Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-dormant-windows-11-control-panel-options/"><u>Bring Forth Dormant Windows 11 Control Panel Options</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-control-center-hidepower-command-of-windows-11/"><u>Clandestine Control Center: Hidepower Command of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-12-mini-without-passcode-or-face-id-by-drfone-ios/"><u>How to Unlock iPhone 12 mini without Passcode or Face ID</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-10-tiktok-edits-android-and-ios-leaders/"><u>[New] Top 10 TikTok Edits  Android & iOS Leaders</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-formulating-imaginative-tiktok-credit-graphics/"><u>[Updated] Formulating Imaginative TikTok Credit Graphics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-motorola-moto-e13-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Motorola Moto E13 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-tailoring-talent-to-treasure-the-proactive-pursuit-of-video-profitability/"><u>[Updated] Tailoring Talent to Treasure  The Proactive Pursuit of Video Profitability</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-designing-direct-access-to-your-channels-subscribe-page/"><u>[New] 2024 Approved  Designing Direct Access to Your Channel's Subscribe Page</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-exploring-top-ios-psp-emulation-tools-for-gamers/"><u>[New] In 2024, Exploring Top iOS PSP Emulation Tools for Gamers</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-how-to-translate-youtube-videos-to-english-subtitles-for-2024/"><u>Updated How to Translate YouTube Videos to English Subtitles for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-the-audio-you-produce-will-inevitably-be-flawed-throughout-the-production-process-so-learn-how-adobe-audition-removes-echo-to-sound-better-instead-of-th/"><u>New The Audio You Produce Will Inevitably Be Flawed Throughout the Production Process. So, Learn How Adobe Audition Removes Echo to Sound Better Instead of Throwing It Away</u></a></li>
</ul></div>
