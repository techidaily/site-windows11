---
title: Set Up Wi-Fi Cost Meter on Windows 11
date: 2024-10-23T16:11:58.448Z
updated: 2024-10-24T20:53:57.525Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-building-a-sustainable-income-via-youtube-and-adsense/"><u>[New] In 2024, Building a Sustainable Income via YouTube and AdSense</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-incorporating-music-into-canva-projects/"><u>[New] Step-by-Step Incorporating Music Into Canva Projects</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-virtual-diary-dos-and-donts-for-consistent-content/"><u>[Updated] 2024 Approved Virtual Diary Dos & Don'ts for Consistent Content</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-photoshop-shake-control-necessary-tool-or-unnecessary/"><u>2024 Approved Photoshop Shake Control Necessary Tool or Unnecessary?</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-issue-the-0x800736cc-method/"><u>Bypassing Windows Update Issue: The 0X800736CC Method</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-appearance-with-custom-pointer-design/"><u>Enhancing System Appearance with Custom Pointer Design</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-zte-nubia-flip-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock ZTE Nubia Flip 5G Pattern Lock Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-power-using-lav-filters-on-microsoft-windows/"><u>Harnessing Power: Using LAV Filters on Microsoft Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-from-apple-iphone-12-pro-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked From Apple iPhone 12 Pro?</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-mastery-original-diablo-basics-explained/"><u>Journey to Mastery: Original Diablo Basics Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-installation-of-intel-wi-fi-drivers/"><u>Navigating the Installation of Intel Wi-Fi Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011s-auto-restart-settings/"><u>Navigating Windows 10/11'S Auto-Restart Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-accessing-power-user-terminal/"><u>Securely Accessing Power-User Terminal</u></a></li>
<li><a href="https://fox-making.techidaily.com/superior-video-editing-and-conversion-tools-top-notch-reviews/"><u>Superior Video Editing & Conversion Tools - Top-Notch Reviews</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://facebook.techidaily.com/the-dark-side-social-networks-popularity-controversy/"><u>The Dark Side: Social Networks' Popularity Controversy</u></a></li>
<li><a href="https://win-amazing.techidaily.com/transformer-des-fichiers-au-format-mp3-sans-frais-sur-movavi-guerilla-seo-pour-les-amateurs-de-musique/"><u>Transformer Des Fichiers Au Format MP3 Sans Frais Sur Movavi : Guérilla SEO Pour Les Amateurs De Musique</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/vibrant-voices-energizing-conversations-with-subscribers/"><u>Vibrant Voices Energizing Conversations With Subscribers</u></a></li>
</ul></div>

