---
title: "Simplifying the Networks Menu: Win 11 Wifi Cleanup"
date: 2025-01-09T17:12:42.846Z
updated: 2025-01-10T21:09:17.246Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/n-2024-check-your-youtube-channels-for-accurate-monetization-practices/"><u>[New] In 2024, Check Your YouTube Channels for Accurate Monetization Practices</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-visualize-your-story-with-top-snapchat-augments/"><u>[New] In 2024, Visualize Your Story with Top Snapchat Augments</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-dynamics-behind-tseries-youtube-earning-patterns-for-2024/"><u>[New] The Dynamics Behind TSeries' YouTube Earning Patterns for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/8-proven-solutions-for-stable-multiversus-gameplay-no-more-crashes/"><u>8 Proven Solutions for Stable MultiVersus Gameplay - No More Crashes</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-deadline-popular-apps-gone-offline/"><u>Digital Deadline: Popular Apps Gone Offline</u></a></li>
<li><a href="https://screen-capture.techidaily.com/elite-screen-recording-apps-of-2023-expert-picks/"><u>Elite Screen Recording Apps of 2023 - Expert Picks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-google-pixel-7a-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Google Pixel 7a Pattern Lock Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-downloading-pictures-from-icloud-onto-various-devices-comprehensive-instructions/"><u>Seamlessly Downloading Pictures From iCloud Onto Various Devices: Comprehensive Instructions</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-accessing-windows-1/"><u>Step-by-Step Guide: Accessing Windows 1</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-on-integrating-your-pc-with-a-tv-display/"><u>Step-by-Step Tutorial on Integrating Your PC with a TV Display</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-activating-and-deactivating-secure-login-in-windows-11/"><u>Step-by-Step Tutorial: Activating and Deactivating Secure Login in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-access-how-windows-subsystem-for-linux-is-becoming-more-user-friendly/"><u>Streamlining Access: How Windows Subsystem for Linux Is Becoming More User-Friendly</u></a></li>
<li><a href="https://win-reviews.techidaily.com/stunning-dark-meta-knight-designs-and-decor-high-quality-wallpaper-selection-by-yl-computing/"><u>Stunning Dark Meta Knight Designs & Decor: High-Quality Wallpaper Selection by YL Computing</u></a></li>
<li><a href="https://windows11.techidaily.com/top-4-cost-free-applications-for-monitoring-and-optimizing-your-windows-pcs-storage/"><u>Top 4 Cost-Free Applications for Monitoring and Optimizing Your Windows PC's Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-windows-applications-the-must-have-software-tools-and-their-importance/"><u>Top Essential Windows Applications: The Must-Have Software Tools & Their Importance</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-10-built-in-apps-crashing-issues/"><u>Troubleshooting Windows 10 Built-In Apps Crashing Issues</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-cutting-edge-video-editing-on-mac-the-top-software-of/"><u>Updated Cutting-Edge Video Editing on Mac The Top Software Of</u></a></li>
</ul></div>

