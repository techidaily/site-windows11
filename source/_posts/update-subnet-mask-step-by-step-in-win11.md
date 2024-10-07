---
title: "Update Subnet Mask: Step-by-Step in Win11"
date: 2024-10-06T06:52:16.165Z
updated: 2024-10-07T06:31:38.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Update Subnet Mask: Step-by-Step in Win11"
excerpt: "This Article Describes Update Subnet Mask: Step-by-Step in Win11"
keywords: Win11 Subnet Update Guide,Change Windows Subnet,Win11 Network Settings Edit,Subnet Mask Adjustment (Win11),Win11 IP Configuration Steps,Reset PC Subnet in Windows 11,Altering Subnet in Win11 OS
thumbnail: https://thmb.techidaily.com/e9c990e25117479e90a6a7012f47011623d3e85d5155cf7861b563822cc331cb.jpg
---

## Update Subnet Mask: Step-by-Step in Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-inverting-your-instagram-footage-a-detailed-guide/"><u>[New] In 2024, Inverting Your Instagram Footage A Detailed Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-turn-every-instagram-moment-into-a-shareable-mp4-file-for-2024/"><u>[Updated] Turn Every Instagram Moment Into a Shareable MP4 File for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-youtube-editing-101-incorporating-time-markers-for-2024/"><u>[Updated] YouTube Editing 101 Incorporating Time Markers for 2024</u></a></li>
<li><a href="https://discover-data.techidaily.com/download-your-favorite-itunes-tv-shows-as-high-quality-movies-with-ittf-converter/"><u>Download Your Favorite iTunes TV Shows as High-Quality Movies with ITTF Converter</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialized-disks-a-windows-guide/"><u>Fixing Non-Initialized Disks: A Windows Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/game-capture-software-analysis-obs-vs-shadowplay/"><u>Game Capture Software Analysis OBS vs ShadowPlay</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/going-cashless-with-ease-your-comprehensive-guide-to-using-apple-pay-on-an-apple-watch/"><u>Going Cashless with Ease: Your Comprehensive Guide to Using Apple Pay on an Apple Watch</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-frozen-taskbar-and-menu/"><u>How to Reactivate Frozen Taskbar & Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-refresh-the-group-policy-settings-on-windows/"><u>How to Refresh the Group Policy Settings on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-samsung-galaxy-s24-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Samsung Galaxy S24 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-oppo-a38-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Oppo A38? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unpredictable-printer-selections/"><u>Remedying Unpredictable Printer Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missed-game-content-with-steam-on-win11/"><u>Resolving Missed Game Content with Steam on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unlisted-bluetooth-on-pc/"><u>Resolving Unlisted Bluetooth on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-harmony-fixing-sticky-notebooks-in-w11/"><u>Restoring Harmony: Fixing Sticky Notebooks in W11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unraveling-the-world-of-hardware-insights-from-toms-perspective/"><u>Unraveling the World of Hardware - Insights From Tom's Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-windows-nettools/"><u>Unveiling the Power of Windows NetTools</u></a></li>
</ul></div>

