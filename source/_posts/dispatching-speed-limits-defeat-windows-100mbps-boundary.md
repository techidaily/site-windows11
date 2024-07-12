---
title: "Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary"
date: 2024-07-11T22:25:28.448Z
updated: 2024-07-12T22:25:28.448Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary"
excerpt: "This Article Describes Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary"
keywords: Speed Limit Dispatch,WINSPEED BOUNDARY,DISPATCH SPEC,WINDETECT SETUP,Mbps Limits Dispatch,Windows Speed Control,Boundary Limit Defeat
thumbnail: https://thmb.techidaily.com/db6e8bb5b9330de241494205e28fd162607bcee64226c4e5f87f88fc35435d44.jpg
---

## Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary

 Is the speed of your Ethernet connection stuck at 100Mbps? If so, several factors could be limiting it. You may only have a 100Mbps connection, and the speed technically cannot go higher; router settings could be limiting the bandwidth, or there could be an issue with the router, Ethernet cable, or cable connectors.

 Likewise, misconfigured Ethernet adapter speed settings, incompatible or corrupted drivers, and technical difficulties with the ISP can also limit speed. If you want your Ethernet connection to surpass 100Mbps, here are a few checks and fixes you should try.

## 1\. Check Your Internet Plan

![wifi speed test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/wifi-speed-test.jpg)

 Make sure you have a high-speed connection capable of delivering speeds greater than 100Mbps before you blame other factors for limiting your internet speed. Check with your internet provider that you're subscribed to a plan that offers 100Mbps+ or more. Also, ensure the ISP has a good reputation and track record of consistently delivering high speeds.

 If your internet service provider is reliable and you are subscribed to a good plan, then it's likely that something on your side is keeping the speed from reaching its maximum.

## 2\. Perform Some Basic Checks

 Start troubleshooting the problem by performing these basic fixes, as they may resolve the issue right away:

* [Reboot your router](https://www.makeuseof.com/reboot-router-correct-way/) once to rule out temporary issues.
* Ensure the Ethernet cable isn't loosely connected to your device. Disconnect both ends of the cable and reconnect them.
* Run the built-in network troubleshooter to identify and resolve any network problems. If you're not familiar with the process, check out our guide on [how to run a troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).
* An outdated network driver can also slow down a connection. Check out our guide on [how to find and replace outdated network drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) to update your network drivers fully.

 If none of the above checks uncaps the internet speed, it's time to move on to the remaining fixes

## 3\. Ensure Your Network Card Supports Gigabit Speed

 The Ethernet Card, also known as the Network Interface Card, connects your computer to the internet via an Ethernet cable. If you have an old computer, the adapter installed may not be capable of delivering over 100Mbps. Therefore, ensuring that your card supports the gigabit connection is imperative.

 To check this, look at the name of the adapter. If it contains keywords such as gigabit, gbe, 10/100/1000M gigabit, you probably have a gigabit connection. In contrast, if you see Fast Ethernet, 10/100FE, your connection is 100Mbps. Alternatively, you can check if your network adapter supports gigabit speeds in Device Manager. Here's how:

1. Right-click the **Start** button and select **Device Manager**.
2. Expand the **Network adapters** category.
3. Right-click the network connection adapter and select **Properties**.
4. Then, go to the **Advanced** tab.
5. Select **Speed and Duplex** from the **Property** column, then expand the **Value** dropdown.  
![Speed and Duplex Settings in the Network Adapter Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/speed-and-duplex-settings-in-the-network-adapter-settings.jpg)

 If **1.0 Gbps Full Duplex** is listed, your card supports gigabit connectivity. Your card does not support gigabit connections if **100 Mbps Full Duplex** is the highest value listed. In any case, select **Auto Negotiation** from the **Value** dropdown in the network adapter settings if any other value is selected.

## 4\. Ensure Your Router Supports Gigabit Connection

![a close up shot of router ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/modern-wifi-router-ports.jpg)

 Like your network card, your router should also be capable of delivering 100Mbps+ speeds. You can check that by looking at the router's documentation or description on the manufacturer's website. If the router manufacturer claims this specific model is a gigabit router, it can likely deliver gigabit speeds.

 If you have a gigabit router, make sure the port where your Ethernet cable is connected is also a gigabit LAN port that can handle up to 1Gbps data rates. Switch to a gigabit port if it's connected to a "Fast Ethernet" port, which can only deliver 100Mbps. Hopefully, this will increase your internet connection's speed.

 If your router doesn't support a gigabit connection, you will have no choice but to switch to one that does.

## 5\. Get a High-Category Ethernet Cable

![CAT5, CAT5e, CAT6, CAT6A Ethernet cables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/02-picture-showing-cat5-cat5e-cat6-cat6a-ethernet-cables.jpg)

 The Ethernet cable itself should be capable of delivering 100Mbps+ speed, just like your router. Ethernet cables with low bandwidth, such as Cat5, can only deliver speeds up to 100Mbps. If you want higher speeds, you need at least Cat5e cable, which can provide speeds of up to 1000Mbps.

 Cat5e and Cat5 cables have identical physical appearances, but don't let that fool you. Instead, look at the cable's label to determine its category. If it's low bandwidth, replace it with Cat5e or higher.

## 6\. Remove Restrictions in the Router Settings

 Most routers allow users to limit the connection speed. Therefore, log into the router's admin interface to ensure speed isn't constrained there. Here's how you can do it:

1. Open the **Command Prompt** and type **"ipconfig."** Then, hit **Enter**.
2. Copy the **IP address** next to **Default Gateway**—that's your router's IP address.  
![Check the Default Gateway IP Address in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-the-default-gateway-ip-address-in-windows-command-prompt.jpg)
3. Paste this address into any internet browser to access your router's admin interface. Then, log in with your username and password.
4. Go to the **Ethernet** settings and check if there are any restrictions on your internet speed. Remove any constraints you find here.

 Some routers allow users to switch between gigabit and 100Mbps speeds. If your router offers this option, opt for the 1Gbps connection.

## 7\. Rule Out Any Hardware Issues

 If none of the above fixes resolve the issue, it's time to check for and rule out hardware problems thoroughly.

![image of ethernet cables connected to router](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/ethernet-router-connection.jpg)

 Start the hardware inspection by checking both ends of the Ethernet cable where cable connectors are installed. Ensure both connectors are in good condition and all internal wires/conductors are pushed to the end and aren't falling off.

 Once you have confirmed that, inspect the Ethernet cable from one end and go through the entire length. If the cable shows any physical damage, especially areas that remain bent all the time, you may need to replace it.

 If the cable is intact, examine the Ethernet ports on your router and laptop. If any of the ports appears damaged, you should switch to another one (if available).

## Get the Most Out of Your Ethernet Connection on Windows

 Getting 100Mbps when subscribed to a higher-speed plan can be pretty frustrating. By now, you should better understand why the connection speed could be capped at 100Mbps. If you carefully follow all the steps listed above, you will likely be able to identify the leading cause and remove any restrictions.

 If your internet speed remains capped at 100Mbps despite applying all the fixes above, you should contact your internet service provider.

 Likewise, misconfigured Ethernet adapter speed settings, incompatible or corrupted drivers, and technical difficulties with the ISP can also limit speed. If you want your Ethernet connection to surpass 100Mbps, here are a few checks and fixes you should try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directive-for-drives-partitioned-areas-in-windows/"><u>Deletion Directive for Drives' Partitioned Areas in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-convenience-with-windows-task-scheduler/"><u>Command Line Convenience with Windows Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/decades-of-taskbars-windows-journey-19852023/"><u>Decades of Taskbars: Windows' Journey (1985–2023)</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-perfect-playback-top-strategies-to-record-and-share-your-vr-experiences/"><u>[New] The Perfect Playback  Top Strategies to Record and Share Your VR Experiences</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-how-quicktime-screen-recording-with-audio/"><u>[New] 2024 Approved  [How] QuickTime Screen Recording with Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-5-top-link-minimizers-transforming-youtube-watchability-for-2024/"><u>[Updated] 5-Top Link Minimizers Transforming YouTube Watchability for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dazzling-holiday-windows-a-celebration-of-joy-and-light/"><u>Dazzling Holiday Windows: A Celebration of Joy & Light</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unpacking-the-wirecast-experience-and-its-rivals/"><u>[New] Unpacking the WireCast Experience & Its Rivals</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-win11s-cursor-blackout-quickly/"><u>Clearing Up Win11's Cursor Blackout Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-cream-of-the-crop-5-top-reaction-video-creators/"><u>2024 Approved The Cream of the Crop 5 Top Reaction Video Creators</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-audio-enhanced-video-screen-record/"><u>[New] In 2024, Audio-Enhanced Video Screen Record</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-immersive-image-editing-online-cropping-essentials/"><u>[New] Immersive Image Editing  Online Cropping Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-console-connection-joining-win-to-ps3-controller/"><u>Direct Console Connection: Joining Win to PS3 Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-direct-call-setup-using-whatsapp-browser-on-your-notebook/"><u>2024 Approved  Direct Call Setup  Using WhatsApp Browser on Your Notebook</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/full-page-capture-on-device/"><u>Full Page Capture on Device</u></a></li>
<li><a href="https://windows11.techidaily.com/differentiating-windows-terminal-from-powershell-a-compreayer-study/"><u>Differentiating Windows Terminal From PowerShell: A Compreayer Study</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-noticing-lack-of-friend-requests/"><u>In 2024, Noticing Lack of Friend Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>