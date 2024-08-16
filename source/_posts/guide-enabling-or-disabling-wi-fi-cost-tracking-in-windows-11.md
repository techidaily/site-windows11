---
title: "Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
date: 2024-08-15T15:35:11.152Z
updated: 2024-08-16T15:35:11.152Z
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

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://instagram-video-files.techidaily.com/updated-engaging-essentials-leading-ig-filters/"><u>[Updated] Engaging Essentials  Leading IG Filters</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-oneplus-nord-n30-5g-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart OnePlus Nord N30 5G Without Power Button | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/all-about-srt-essential-information-made-easy/"><u>All About SRT  Essential Information Made Easy</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-oppo-find-x7-ultra-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Oppo Find X7 Ultra Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-overlapping-security-measures-stick-to-one-windows-antivirus/"><u>Avoid Overlapping Security Measures: Stick to One Windows Antivirus</u></a></li>
<li><a href="https://extra-hints.techidaily.com/blending-binaries-digital-photographic-techniques/"><u>Blending Binaries  Digital Photographic Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/crafted-alerts-full-charge-on-your-win-pclaptop/"><u>Crafted Alerts: Full Charge on Your WIN PC/Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-fix-error-code-0xc0000001-on-windows-pcs/"><u>Easy Steps To Fix Error Code 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-fix-for-0x80072af9-in-windows-os/"><u>Immediate Fix for 0X80072AF9 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-workflow-integration-adding-shortcuts-to-the-wordpad-menu-of-windows-11/"><u>Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-little-legends-top-gaming-adventures/"><u>In 2024, Little Legends  Top Gaming Adventures</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mastering-video-thumbnail-creation-for-maximum-clicks/"><u>Mastering Video Thumbnail Creation for Maximum Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-subsystem-best-practices-for-wsl-2-users/"><u>Optimizing Subsystem: Best Practices for WSL 2 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/photoshop-power-users-guide-to-windows-keys/"><u>Photoshop Power-Users Guide to Windows Keys</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prioritize-quality-and-ease-the-top-12-videophones-for-2024/"><u>Prioritize Quality and Ease  The Top 12 Videophones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-disable-win-11-mobility-hub/"><u>Quick Tips: Disable Win 11 Mobility Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-code-3-nvidia-opengl-on-windows-1011/"><u>Resolving Error Code 3: NVIDIA OpenGL on Windows 10/11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/simplified-screen-switching-utilizing-pip-mode-on-netflix-for-smooth-viewing-for-2024/"><u>Simplified Screen Switching  Utilizing PIP Mode on Netflix for Smooth Viewing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/start-stealth-mode-obscuring-win11s-power-button/"><u>Start Stealth Mode: Obscuring Win11's Power Button</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-practices-for-using-wsl-2-on-windows-10-and-11/"><u>The 5 Best Practices for Using WSL 2 on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-from-ios-to-a-pc-a-complete-guide-to-imessage/"><u>Transitioning From iOS to a PC: A Complete Guide to iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-from-iphones-calendar-to-windows-smoothly/"><u>Transitioning From iPhone's Calendar to Windows Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/ultraportables-with-prime-windows-software/"><u>Ultraportables with Prime Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/unified-app-closure-master-the-multiplex-task-management/"><u>Unified App Closure: Master the Multiplex Task Management</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-6s-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 6s</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-pcs-potential-onedrive-troubleshooting-tips/"><u>Unlocking Your PC's Potential: OneDrive Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/using-windows-system-restore-feature-efficiently/"><u>Using Windows' System Restore Feature Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-steering-classic-games-to-your-pics/"><u>Windows 11: Steering Classic Games to Your Pics</u></a></li>
</ul></div>
