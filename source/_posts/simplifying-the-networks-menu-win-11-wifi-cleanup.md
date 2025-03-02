---
title: "Simplifying the Networks Menu: Win 11 Wifi Cleanup"
date: 2025-02-23T13:40:29.544Z
updated: 2025-03-02T06:36:32.137Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplifying the Networks Menu: Win 11 Wifi Cleanup"
excerpt: "This Article Describes Simplifying the Networks Menu: Win 11 Wifi Cleanup"
keywords: Win 11 Wi-Fi Fix,Simplify Win 11 Wi-Fi,Wifi Cleaning Win 11,Network Menu Optimization,Easy Win 11 Wi-Fi Setup,Streamline Win 11 Networks,Tidy Up Windows Wi-Fi
thumbnail: https://thmb.techidaily.com/34898e0ebb1abca68099d2acba8fac3a4c33b87872f768fed60cc168fcf66601.jpg
---

## Simplifying the Networks Menu: Win 11 Wifi Cleanup

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-excursion-videography-tools-compilation/"><u>[New] In 2024, Excursion Videography Tools Compilation</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-from-apple-iphone-xr-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons From Apple iPhone XR? Find the Best Solution Here</u></a></li>
<li><a href="https://win-cheats.techidaily.com/expert-tips-for-diagnosing-and-fixing-windows-memory-errors-yl-software-solutions/"><u>Expert Tips for Diagnosing and Fixing Windows Memory Errors - YL Software Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-geforce-experience-settings-not-available-hurdle-windows-11/"><u>Fixing the 'GeForce Experience Settings Not Available' Hurdle, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-powershell-not-found-issue-on-windows-os/"><u>Fixing the PowerShell Not Found Issue on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-designs-and-advanced-tech-years-best-windows-laptops/"><u>Innovative Designs and Advanced Tech - Year's Best Windows Laptops</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-look-investing-in-automation-why-i-committed-to-the-premium-robomower-6000-for-my-yard/"><u>Inside Look: Investing in Automation – Why I Committed to the Premium RoboMower ($6,000) for My Yard</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/making-the-move-from-iphone-to-samsung-how-apple-must-simplify-transition-process/"><u>Making the Move From iPhone to Samsung: How Apple Must Simplify Transition Process</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-high-dynamic-range-hdr-in-windows-11-a-step-by-step-manual/"><u>Navigating High Dynamic Range (HDR) in Windows 11: A Step-by-Step Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-system32-in-windows-11/"><u>Navigating to System32 in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/offline-driver-setup-a-guide-to-installing-windows-drivers-without-internet-access/"><u>Offline Driver Setup: A Guide to Installing Windows Drivers Without Internet Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-requested-operation-unsuccessful-by-wrp-troubleshooting-guide/"><u>Overcome 'Requested Operation Unsuccessful by WRP': Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-audio-clarity-and-functionality-in-valorant-windows/"><u>Restoring Audio Clarity and Functionality in Valorant (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/retrieve-missing-5ghz-connection-now-easily-for-windows-11/"><u>Retrieve Missing 5GHz Connection, Now Easily for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-obsidian-way-to-uncluttered-vivid-note-taking/"><u>The Obsidian Way to Uncluttered, Vivid Note-Taking</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-vr-the-creation-gap-for-2024/"><u>Unveiling VR The Creation Gap for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-mastering-compression-in-fcpx-a-step-by-step-guide-for-2024/"><u>Updated Mastering Compression in FCPX A Step-by-Step Guide for 2024</u></a></li>
</ul></div>

