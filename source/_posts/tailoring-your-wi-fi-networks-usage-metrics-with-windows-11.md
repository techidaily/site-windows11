---
title: Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
date: 2024-12-05T19:13:03.235Z
updated: 2024-12-10T20:38:41.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
excerpt: This Article Describes Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
keywords: Wi-Fi Usage Monitoring,Win11 NetMetrics,Wifi Performance Track,Windows 11 Usage Insights,Network Metric Tailor,Wi-Fi Optimization Tools,Data Analysis Windows 11
thumbnail: https://thmb.techidaily.com/5961427253350c1b74e1650e9c2f8a99858d6dfe3a81786842ed520231401b1b.jpg
---

## Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-become-a-livestream-king-the-best-webcams-for-youtube-stars/"><u>[New] 2024 Approved Become a Livestream King The Best Webcams for YouTube Stars</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-audio-overhaul-methods-for-content-creators-online/"><u>[Updated] Audio Overhaul Methods for Content Creators Online</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-odins-legacy-destiny-of-ragnarok/"><u>[Updated] In 2024, Odin's Legacy Destiny of Ragnarök</u></a></li>
<li><a href="https://win-able.techidaily.com/essential-tips-for-resolving-gta-5-online-malfunctions/"><u>Essential Tips for Resolving GTA 5 Online Malfunctions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/keys-fail-randomly/"><u>Keys Fail Randomly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-smartscreen-settings-in-microsoft-win11/"><u>Mastering SmartScreen Settings in Microsoft Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-hypervisor-crashes-on-winxose-with-ease/"><u>Overcome HYPERVISOR Crashes on WINXOSE with Ease</u></a></li>
<li><a href="https://blog-min.techidaily.com/perfeziona-i-tuoi-video-con-winxvideo-ai-per-una-qualita-senza-pari/"><u>Perfeziona I Tuoi Video Con WinXvideo AI per Una Qualità Senza Pari</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-error-code-0x80004004-on-windows-defender-a-guide/"><u>Solving Error Code 0X80004004 on Windows Defender: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-lowering-cpu-usage-by-wmi-service/"><u>Tips for Lowering Cpu Usage by WMI Service</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-presentations-true-potential-mastering-prints-from-powerpoint-in-windows/"><u>Unlocking Your Presentation's True Potential: Mastering Prints From PowerPoint in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/voice-customization-leaders-beyond-echo-magic/"><u>Voice Customization Leaders Beyond Echo Magic</u></a></li>
</ul></div>

