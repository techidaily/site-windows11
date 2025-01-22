---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2025-01-17T16:50:38.959Z
updated: 2025-01-22T19:14:56.239Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-in-2024-teleport-into-virtuality-top-10-mobile-vr-headsets-reviewed/"><u>[New] In 2024, Teleport Into Virtuality Top 10 Mobile VR Headsets Reviewed</u></a></li>
<li><a href="https://article-files.techidaily.com/new-the-ultimate-journey-in-sky-high-4k-clarity-for-2024/"><u>[New] The Ultimate Journey in Sky High 4K Clarity for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-realme-12-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Realme 12 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-on-win-xpvista7-backup-reset-procedure/"><u>Guide on Win XP/Vista/7 Backup Reset Procedure</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-samsung-galaxy-m34-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Samsung Galaxy M34 ?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-11-pro-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone 11 Pro Data From iOS iTunes? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-oneplus-11r-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from OnePlus 11R</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-look-at-the-oneplus-8t-speed-vs-photography-is-it-a-tradeoff/"><u>In-Depth Look at the OnePlus 8T: Speed Vs. Photography - Is It a Tradeoff?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-freeze-frames-in-leading-lol-game/"><u>Navigating Freeze Frames in Leading LOL Game</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-11-overheating-issues/"><u>Preventing Windows 11 Overheating Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tame-the-tech-tyranny-restoring-sound-on-your-pc/"><u>Tame the Tech Tyranny: Restoring Sound on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-halt-automatic-startup-of-spotify/"><u>Techniques to Halt Automatic Startup of Spotify</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-editing-efforts-10-text-innovations/"><u>Top Editing Efforts 10 Text Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-hyper-v-on-windows-11-homes-with-simple-instructions/"><u>Unlock Hyper-V on Windows 11 Homes with Simple Instructions</u></a></li>
</ul></div>

