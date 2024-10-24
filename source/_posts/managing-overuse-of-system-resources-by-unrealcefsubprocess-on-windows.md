---
title: Managing Overuse of System Resources by UnrealCEFSubprocess on Windows
date: 2024-10-22T16:24:18.385Z
updated: 2024-10-24T20:35:23.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Overuse of System Resources by UnrealCEFSubprocess on Windows
excerpt: This Article Describes Managing Overuse of System Resources by UnrealCEFSubprocess on Windows
keywords: Resource Management in URCS,Windows Subsystem Usage,CPU & Memory Limits,Efficient Computing,System Resource Control,UnrealCEFSubprocess Impact,Performance Optimization
thumbnail: https://thmb.techidaily.com/0177669a9f7e47198243a9fecb2a2f8d7897c9576df374da55c9c20dfb4332d6.jpg
---

## Managing Overuse of System Resources by UnrealCEFSubprocess on Windows

 Is the UnrealCEFSubprocess process consuming hefty CPU and RAM resources in the Task Manager, causing your games to crash? Does it keep straining your hardware even after you close all the active programs and apps? You may also have seen it multiply in the Task Manager, which might have made you believe it's a virus.

 There's no need to worry; it's not a virus but a legitimate process belonging to Valorant. Below, we'll discuss why this process consumes many system resources and how you can reduce its resource usage to relieve the strain on your hardware.

## Why Does the UnrealCEFSubprocess Process Consume High CPU and RAM Resources?

 UnrealCEFSubprocess is a legitimate Valorant process, so it shouldn't overload your system resources. If this process starts to strain your hardware and cause CPU, RAM, or GPU usage to spike in the Task Manager, it's either not functioning correctly, or other processes are interfering with it.

 As many users pointed out in a[Reddit thread](https://www.reddit.com/r/ValorantTechSupport/comments/z66n1b/unrealcefsubprocessexe%5Fmultiplying%5Fand%5Fputting/) , one of the major causes of high resource consumption by this process is the interference from Windows' built-in security suite, Windows Defender, and third-party antivirus software, primarily AVG antivirus and Avast antivirus. If you are using security software, then it might be causing the issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144288/7443" target="_top" id="2144288">
  <img src="//a.impactradius-go.com/display-ad/7443-2144288" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144288/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Can You Disable the UnrealCEFSubprocess Process via the Task Manager?

 Disabling the UnrealCEFSubprocess process could adversely affect your active gaming session in Valorant. The gaming elements this process controls or handles will crash and behave abnormally. Because of this, we do not advocate closing it down.

 Furthermore, Valorant or the Riot client will automatically relaunch this process the next time you open them, so disabling only the process won't solve the issue. Therefore, we recommend that you fix the underlying problem rather than only disabling this process.

## How to Stop the UnrealCEFSubprocess Process From Taking Up Too Much RAM and CPU

 The easiest way to reduce UnrealCEFSubprocess's CPU and RAM consumption is to[permanently disable Windows Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/) , the built-in security software in Windows, and uninstall any third-party antivirus software you currently use. Even though doing this is easy and quick, we don't recommend it. Why is that?

 The Windows Defender and third-party antivirus software installed on your laptop are a solid defense against viruses and malware. They prevent any potentially harmful agents from wreaking havoc on your device. If you delete or disable them, you will remove your frontline fighters and allow enemies to attack your territory with no fear.

 These security suites would likely have already quarantined many threats and blocked potentially harmful files from affecting your computer. Disabling or deleting them can release these threats and remove restrictions on malicious files. Consequently, this could negatively affect your computer in the long run.

 Considering the risks associated with it, it would be wise not to disable security software right away. Instead of that, you can whitelist the UnrealCEFSubprocess process in them. Whitelisting any file instructs security software not to interfere with it. Therefore, whitelisting the file associated with this process will prevent antivirus programs from interfering with it.

 Consequently, you will be successful in reducing resource consumption without compromising your security.

### How to Whitelist UnrealCEFSubprocess From Windows Defender

 Follow these steps to whitelist UnrealCEFSubprocess from Windows Defender:

1. Type**"Windows Security"** in Windows Search and open the**Windows Security** app.  
![Open Windows Security from Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-windows-security-from-windows-search.jpg)
2. Go to the**Firewall and network protection** tab on the left.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Click on the**Allow an app through the firewall** link on the right side of the screen.  
![Click on the Allow an App Through the Firewall Link in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-the-allow-an-app-through-the-firewall-link-in-windows-security-app.jpg)
4. Click on**Change settings** .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click on**Allow another app** .  
![Click on Allow Another App in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-allow-another-app-in-the-windows-defender-firewall-settings.jpg)

1. In the**Add an app** window, click on the**Browse** button.  
![Click on the Browse Button in the Add an App Window in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-the-browse-button-in-the-add-an-app-window-in-the-windows-defender-firewall-settings.jpg)
2. Then, go to the following path:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
3. Here, select**UnrealCEFSubProcess** from the list.  
![Select UnrealCEFSubprocess to Create an Exclusion for It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-select-unrealcefsubprocess-to-create-an-exclusion-for-it.jpg)
4. Then, click on**Add** .  
![Click on the Add Button After Selecting the Relevant Process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-click-on-the-add-button-after-selecting-the-relevant-process.jpg)
5. After that, check the**Public** and**Private** boxes next to the**UnrealCEFSubProcess** process and click**OK** .  
![Click OK After Checking the Public and Private Boxes Next to the UnrealCEFSubprocess in the Windows Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-ok-after-checking-the-public-and-private-boxes-next-to-the-unrealcefsubprocess-in-the-windows-firewall-settings.jpg)
6. Restart your computer after whitelisting this process.

**I** f you have installed Valorant in a different folder or your operating system resides on a different drive, change the path above to reflect the proper location.

### How to Whitelist UnrealCEFSubprocess From Avast Antivirus

 Follow these steps to whitelist UnrealCEFSubprocess from Avast Antivirus:

1. Launch Avast Antivirus.
2. Click the**Menu** button (represented by three horizontal lines stacked over each other) in the top-right of the screen.
3. Go to**Settings** .  
![Go to Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/8-go-to-settings-in-avast-antivirus-app.jpg)
4. Go to the**Exceptions** tab in the**General** settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click on**Add Exception** .  
![Click on Add Exception in the General Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/9-click-on-add-exception-in-the-general-settings-in-avast-antivirus-app.jpg)
6. Click**Browse** in the**Add exception** window.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Click Browse in the Add Exception Window in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/10-click-browse-in-the-add-exception-window-in-avast-antivirus-app.jpg)
7. Navigate to the following path if you haven't changed the default installation path when installing Valorant:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
8. Check the box beside**UnrealCEFSubprocess** and click**OK** .  
![Click OK After Checking the Box Beside UnrealCEFSubprocess in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/11-click-ok-after-checking-the-box-beside-unrealcefsubprocess-in-avast-antivirus-app.jpg)
9. After that, restart your computer once, and hopefully, the process won't overtax your computer's resources anymore.

### How to Whitelist UnrealCEFSubprocess From AVG Antivirus

 The interface of AVG antivirus is almost identical to Avast antivirus. So, you can whitelist UnrealCEFSubprocess from it by following the steps outlined above. Once you have whitelisted the file,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) once, and hopefully, the resource consumption by this process will decrease significantly.

 According to some users, whitelisting the UnrealCEFSubprocess file from AVG antivirus doesn't always reduce its resource consumption. Due to this, users had to delete AVG antivirus from their computers. So, if whitelisting the file doesn't reduce the load on your hardware, you can delete the AVG antivirus.

 Before doing that,[turn on Windows Defender](https://www.makeuseof.com/turn-on-microsoft-defender/) if it's off, or install alternative antivirus software to replace AVG and keep your computer safe from incoming threats.

 If you use an antivirus software other than the two listed above and the UnrealCEFSubprocess process consumes more than half of your system resources, you need to whitelist the UnrealCEFSubprocess file there as well. If you are not familiar with the whitelisting process, visit the antivirus software's official website.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Don't Let the UnrealCEFSubprocess Process Overburden Your Hardware

 The UnrealCEFSubprocess process consumes a lot of resources, which leaves barely any resources for other processes. Consequently, your games and apps will take a long time to load and crash frequently—enough to ruin your gaming experience.

 You should now better understand why this process consumes a lot of resources and what you can do to fix it. Therefore, whitelist the UnrealCEFSubprocess process in your security program, and if that does not solve the issue, disable or uninstall your antivirus.

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
<li><a href="https://fox-helps.techidaily.com/updated-seamless-image-superimposition-for-desktop-for-2024/"><u>[Updated] Seamless Image Superimposition for Desktop for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/facing-problems-with-the-chatgpt-app-on-your-iphone-try-these-9-fixes/"><u>Facing Problems with the ChatGPT App on Your iPhone? Try These 9 Fixes!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-online-video-converter-mp4-to-mpg-by-movavi-edit-and-convert-videos-effortlessly/"><u>Free Online Video Converter: MP4 to MPG by Movavi - Edit and Convert Videos Effortlessly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y56-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo Y56 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-big-waters-better-views-top-5-fishing-cams/"><u>In 2024, Big Waters, Better Views - Top 5 Fishing Cams</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-strategies-for-an-engaging-zoom-youtube-live-session/"><u>In 2024, Expert Strategies for an Engaging Zoom YouTube Live Session</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80072af9-error-in-windows-os/"><u>Overcoming 0X80072AF9 Error in Windows OS</u></a></li>
<li><a href="https://discover-data.techidaily.com/retrieve-your-accidentally-deleted-files-on-windows/"><u>Retrieve Your Accidentally Deleted Files on Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revive-vanished-files-on-your-apple-device-with-the-help-of-stellar-app/"><u>Revive Vanished Files on Your Apple Device with the Help of Stellar App</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-from-unrealcefsubprocess-on-pcs/"><u>Strategies to Reduce CPU and RAM Overuse From UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-fixes-for-eliminating-windows-error-code-0xc00000f/"><u>Swift Fixes for Eliminating Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-malfunction-code-0x80246007-on-w10w11/"><u>Tackling Windows Update Malfunction: Code 0X80246007 on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-windows-11s-system-restore-features/"><u>Unlocking the Power of Windows 11'S System Restore Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-edges-additional-taskers/"><u>Unraveling the Mystery of Edge's Additional Taskers</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-10-and-11s-isdonedll-dilemmrances/"><u>Unraveling Windows 10 & 11'S ISDone.dll Dilemmrances</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-evolution-a-look-at-the-taskbar/"><u>Windows' Icon Evolution - A Look at the Taskbar</u></a></li>
</ul></div>

