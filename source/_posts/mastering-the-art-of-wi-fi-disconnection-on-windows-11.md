---
title: Mastering the Art of Wi-Fi Disconnection on Windows 11
date: 2024-10-02T17:26:08.740Z
updated: 2024-10-06T19:19:05.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Wi-Fi Disconnection on Windows 11
excerpt: This Article Describes Mastering the Art of Wi-Fi Disconnection on Windows 11
keywords: WinWi-Fi Mastery,Wifi Disconnect Pro,Windows 11 Secure,Wi-Fi Control Guide,Disconnect Techniques,Connectivity Management,Wireless Security Tips
thumbnail: https://thmb.techidaily.com/46486d3cf08c5d74abeb420acca02a4bdb0158ce8590b04726071d43a2a2101d.jpg
---

## Mastering the Art of Wi-Fi Disconnection on Windows 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.

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
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-guide-to-efficiently-convert-vimeo-videos-to-audible-files/"><u>[Updated] 2024 Approved Guide to Efficiently Convert Vimeo Videos to Audible Files</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-error-free-excel-sheets-a-step-by-step-guide-to-automatic-spelling-correction/"><u>1. Mastering Error-Free Excel Sheets: A Step-by-Step Guide to Automatic Spelling Correction</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/1-unlocking-digital-content-how-to-liberate-your-ebooks-audiobooks-and-videos-from-drm-on-amazon/"><u>1. Unlocking Digital Content: How to Liberate Your eBooks, Audiobooks, and Videos From DRM on Amazon</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-ultimate-warrior-challenge-t5-vs-sjcam-s6/"><u>2024 Approved The Ultimate Warrior Challenge T5 vs SJCAM S6</u></a></li>
<li><a href="https://windows11.techidaily.com/beginning-your-journey-with-windows-live-mesh-2011-the-ultimate-guide-for-seamless-data-management/"><u>Beginning Your Journey with Windows Live Mesh 2011 – The Ultimate Guide for Seamless Data Management</u></a></li>
<li><a href="https://windows11.techidaily.com/check-out-the-most-recent-updates-to-microsoft-office-suite-whats-new/"><u>Check Out the Most Recent Updates to Microsoft Office Suite: What's New?</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-guide-securing-data-with-cell-locking-techniques-in-excel/"><u>Complete Guide: Securing Data with Cell Locking Techniques in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-to-compress-data-within-cells-using-microsoft-excel/"><u>Effective Techniques to Compress Data Within Cells Using Microsoft Excel</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensure-smooth-printing-download-hp-laserjet-5200-drivers-for-modern-operating-systems-windows-11108/"><u>Ensure Smooth Printing: Download HP LaserJet 5200 Drivers for Modern Operating Systems (Windows 11/10/8)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/introducing-the-cutting-edge-features-of-the-newest-ipad/"><u>Introducing the Cutting-Edge Features of the Newest iPad</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/keeping-track-saving-insta-visuals-on-iphone/"><u>Keeping Track Saving Insta Visuals on iPhone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguard-your-social-networks-exposing-the-rogue-chrome-plugin-mimicking-chatgpt-and-targeting-facebook-logins/"><u>Safeguard Your Social Networks: Exposing the Rogue Chrome Plugin Mimicking ChatGPT & Targeting Facebook Logins</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-fixes-to-your-realtek-alc887-hd-audio-woes-on-a-windows-computer/"><u>Step-by-Step Fixes to Your Realtek ALC887 HD Audio Woes on a Windows Computer.</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-latest-update-excels-enhanced-task-automation-on-windows/"><u>Unveiling the Latest Update: Excel's Enhanced Task Automation on Windows</u></a></li>
</ul></div>

