---
title: "Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
date: 2024-12-04T16:47:23.435Z
updated: 2024-12-10T17:54:29.427Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
excerpt: "This Article Describes Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed"
keywords: Ethernet Speed Test,Wi-Fi Speed Comparison,Ping Time Analysis,Network Latency Check,Data Throughput Rate,Bandwidth Measurement,Fiber Optic Speed
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed

 The network adapter is a critical piece of hardware that connects your Windows computer to the internet via a wired or wireless connection. In order to achieve the maximum speeds offered by your Internet Service Provider, it is important to know what network speed your card is capable of.

 Whether you want to upgrade your internet plan or diagnose your network for performance issues, there are several ways to determine the network adapter speed on Windows. Let’s go over all of them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Check the Network Adapter Connection Speed Using the Settings App

 The quickest way to check the connection speed for a Wi-Fi or Ethernet adapter is through the Windows Settings app. Aside from network speed, the Settings app also provides important information like network band, local IP address, MAC address, and more.

To check the network adapter speed via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Select**Network & internet** from the left sidebar.
3. Click on**Properties** at the top.
4. Scroll down to the**Link speed (Receive/Transmit)** field to check the connection speed.  
![Check Network Adapter Speed Using the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-the-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Seeing too many network adapter entries on your Windows computer? Learn[how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide on[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

## Checking Network Adapter Connection Speed on Windows

 As we just learned, determining the network adapter connection speed on Windows is relatively simple. Do you know what else is easy? Speeding up the internet connection speed on your Windows computer.

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
<li><a href="https://vimeo-videos.techidaily.com/new-optimized-vimeo-video-exporting-apps-for-2024/"><u>[New] Optimized Vimeo Video Exporting Apps for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-infinite-gaming-space-10-ssds-hdds-for-ps5/"><u>[Updated] In 2024, Infinite Gaming Space #10 SSDs, HDDs for PS5</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-audio-capture-in-windows-11/"><u>2024 Approved Streamlining Audio Capture in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/best-video-production-software-top-14-tools-for-outstanding-content-creation/"><u>Best Video Production Software: Top 14 Tools for Outstanding Content Creation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-motorola-edge-40-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Motorola Edge 40 Pictures An Easy Method Explained.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-poco-by-fonelab-android-recover-pictures/"><u>How To Restore Missing Pictures Files from Poco .</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oppo-a79-5g-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Oppo A79 5G Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-2024-top-10-ai-talking-avatars-revolutionizing-communication/"><u>In 2024, Top 10 AI-Talking Avatars Revolutionizing Communication</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-copying-custom-powertoys-configurations/"><u>Mastering the Art of Copying Custom PowerToys Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-index-settings-on-windows/"><u>Navigate to Index Settings on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-0x80860010-application-overload/"><u>Navigating Through the Maze of 0X80860010 Application Overload</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-screens-that-tick-in-windows-11/"><u>Quick Remedy for Screens that Tick in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-non-functional-google-nearby-share-window/"><u>Steps to Resolve Non-Functional Google Nearby Share Window</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-erasing-windows-11s-task-view/"><u>The Art of Erasing Windows 11'S Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-on-preventing-windows-notepad-hangouts/"><u>Tips on Preventing Windows Notepad Hangouts</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0xa00f4289-in-windows-webcam-errors/"><u>Troubleshooting Code 0xA00F4289 in Windows Webcam Errors</u></a></li>
</ul></div>

