---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2025-01-15T12:45:03.293Z
updated: 2025-01-16T12:04:11.279Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-exploring-hidden-gems-secrets-on-locating-superb-insta-ringtunes-and-creating-noteworthy-chimes/"><u>[New] In 2024, Exploring Hidden Gems Secrets on Locating Superb Insta-Ringtunes & Creating Noteworthy Chimes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-the-essentials-of-logging-live-performances-online/"><u>[New] In 2024, The Essentials of Logging Live Performances Online</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-harnessing-the-power-of-personal-success-stories-in-videos/"><u>[Updated] Harnessing the Power of Personal Success Stories in Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-installer-glitches-on-latest-windows-versions/"><u>Combatting Installer Glitches on Latest Windows Versions</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-boot-from-a-usb-drive-dvd-or-cd/"><u>How to Boot From a USB Drive, DVD or CD</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-samsung-galaxy-a14-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Samsung Galaxy A14 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Asus ROG Phone 7? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-windows-control-panel-running-smoothly/"><u>Keep Your Windows Control Panel Running Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-auto-lock-settings-in-windows/"><u>Navigate Auto-Lock Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://tech-revival.techidaily.com/pursue-excellence-in-play-and-artistry-via-gpt-my-bots-techniques/"><u>Pursue Excellence in Play and Artistry via GPT-My Bots Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-audio-in-microsoft-teams-for-windows-11-and-10-users-common-fixes-exposed/"><u>Reviving Audio in Microsoft Teams for Windows 11 & 10 Users - Common Fixes Exposed</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-rated-free-tools-for-high-res-youtube-cover-extraction-for-2024/"><u>Top-Rated Free Tools for High-Res YouTube Cover Extraction for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/turning-off-the-text-overlays-for-movies-and-shows-on-amazons-prime-video-platform/"><u>Turning Off The Text Overlays for Movies and Shows on Amazon's Prime Video Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
</ul></div>

