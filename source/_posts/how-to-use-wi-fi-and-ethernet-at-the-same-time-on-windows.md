---
title: How to Use Wi-Fi and Ethernet at the Same Time on Windows
date: 2024-12-04T17:57:43.893Z
updated: 2024-12-10T20:56:17.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use Wi-Fi and Ethernet at the Same Time on Windows
excerpt: This Article Describes How to Use Wi-Fi and Ethernet at the Same Time on Windows
keywords: Wi-Fi+Ethernet Use,Dual Network Connect,Simultaneous Wi-Fi/Ethernet,Multi-Network Setup Windows,Ethernet and Wi-Fi Combo,Seamless Dual-Network Windows,Concurrent Wi-Fi/Ethernet PC
thumbnail: https://thmb.techidaily.com/289e1b59f873ec0dc8305b0281292ab73fb1d9fdd29063def94d2427e3383ad3.jpg
---

## How to Use Wi-Fi and Ethernet at the Same Time on Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-unveiling-top-8-collaborative-video-collage-android-apps-freepremium/"><u>[New] 2024 Approved Unveiling Top 8 Collaborative Video Collage Android Apps (Free/Premium)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-gamers-guide-to-seamless-screen-recording/"><u>[Updated] 2024 Approved Gamers' Guide to Seamless Screen Recording</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1-step-by-step-guide-effortless-setup-of-the-kingdom-add-on-in-your-kodi-media-center/"><u>1. Step-by-Step Guide: Effortless Setup of the Kingdom Add-On in Your Kodi Media Center</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-creativity-in-3-bot-systems/"><u>Comparing Creativity in 3 Bot Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-locate-missing-gateway-ubisofts-launcher/"><u>How To Locate Missing Gateway: Ubisoft's Launcher</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-from-voice-to-phrase-transcribing-with-whisper-for-windows/"><u>Leap From Voice to Phrase: Transcribing with Whisper for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-window-experience-essential-product-key-insights/"><u>Optimize Your Window Experience: Essential Product Key Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-setup-your-external-drives-in-newest-os-win11/"><u>Perfectly Setup Your External Drives in Newest OS, Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-toolkit-best-free-resources-for-win11-power/"><u>Priority Toolkit: Best Free Resources for Win11 Power</u></a></li>
<li><a href="https://windows11.techidaily.com/sneak-peek-into-windows-11s-undercover-menus/"><u>Sneak Peek Into Windows 11'S Undercover Menus</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-next-big-step-in-ai-googles-unveiling-of-palm-2-model/"><u>The Next Big Step in AI: Google's Unveiling of PaLM 2 Model</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-realme-v30t-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Realme V30T Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win-webster.techidaily.com/1728470306209-windows-10/"><u>Windows 10 新装開始用保管ファイル作成方法</u></a></li>
</ul></div>

