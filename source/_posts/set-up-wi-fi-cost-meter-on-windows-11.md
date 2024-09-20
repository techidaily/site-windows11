---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2024-09-13T21:27:09.763Z
updated: 2024-09-20T17:04:47.627Z
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
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-valhallas-vanguard-fiery-rebirth/"><u>[Updated] 2024 Approved Valhalla's Vanguard Fiery Rebirth</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-minimizing-noise-subtle-audio-tweaks-for-pc-mac/"><u>2024 Approved Minimizing Noise Subtle Audio Tweaks for PC, Mac</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-samsung-image-maker-insights-and-overview-2023/"><u>2024 Approved Samsung Image Maker Insights & Overview 2023</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-samsung-galaxy-m14-4g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Samsung Galaxy M14 4G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/automated-marketing-solutions-empower-your-online-presence-with-cookiebot/"><u>Automated Marketing Solutions: Empower Your Online Presence with Cookiebot</u></a></li>
<li><a href="https://sound-issues.techidaily.com/common-problems-and-fixes-dealing-with-a-dead-runmus-headset-mic/"><u>Common Problems and Fixes: Dealing with a Dead Runmus Headset Mic</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-new-software-update-for-your-dymo-4xl/"><u>Download and Install New Software Update for Your DYMO 4XL</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-data-recovery-recover-lost-data-from-honor-90-gt-by-fonelab-android-recover-data/"><u>Honor Data Recovery – recover lost data from Honor 90 GT</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-windows-after-failed-sign-in/"><u>How to Unlock Windows After Failed Sign-In</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-11-disk-space-strategies-without-deleting-files-max-156-chars/"><u>Innovative Windows 11 Disk Space Strategies Without Deleting Files (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-operative-grammarly-on-your-computer/"><u>Overcoming Non-Operative Grammarly on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-excel-operations-restored-a-guide-for-windows-users/"><u>Speedy Excel Operations Restored: A Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decipher-group-policy-on-your-computer/"><u>Strategies to Decipher Group Policy on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-the-prime-viewing-experience-on-windows-11-devices/"><u>Streamline the Prime Viewing Experience on Windows 11 Devices</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-in-pc-components-with-toms-gear-guides/"><u>Unveiling the Latest in PC Components with Tom’s Gear Guides</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

