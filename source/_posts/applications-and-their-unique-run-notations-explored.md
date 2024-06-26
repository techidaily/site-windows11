---
title: Applications & Their Unique Run Notations Explored
date: 2024-06-25T12:10:01.591Z
updated: 2024-06-26T12:10:01.591Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Applications & Their Unique Run Notations Explored
excerpt: This Article Describes Applications & Their Unique Run Notations Explored
keywords: App Usage Metrics,Run Notation Analysis,Application Performance,Unique Notation Methods,Running Logs Insight,Notation Efficiency,App Functionality Study
thumbnail: https://thmb.techidaily.com/02ef47e4fa1bec9703102ec97417713d4516fad507615fc36a561cee9ad50600.png
---

## Applications & Their Unique Run Notations Explored

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://windows11.techidaily.com/tips-to-turn-on-or-off-windows-installation-service/"><u>Tips to Turn On or Off Windows Installation Service</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-tweaking-your-web-privacy-via-proxies-in-win-11/"><u>Expert Advice: Tweaking Your Web Privacy via Proxies in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-an-incorrect-cpu-usage-in-the-windows-task-manager/"><u>How to Fix an Incorrect CPU Usage in the Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/tcpip-port-safety-a-windows-perspective/"><u>TCP/IP Port Safety: A Windows Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-network-drives-on-win11/"><u>Automating Network Drives on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-distinctive-decor-for-each-monitor-in-windows-11/"><u>Discovering Distinctive Decor for Each Monitor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-best-of-the-app-store-top-iphone-apps-reviewed-and-rated/"><u>New In 2024, The Best of the App Store Top iPhone Apps , Reviewed and Rated</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-essential-10-dynamic-tiktok-filters-for-fresh-looks/"><u>In 2024, Essential 10 Dynamic TikTok Filters For Fresh Looks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-tecno-spark-20c-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Tecno Spark 20C to Apple TV | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevate-your-youtube-traffic-best-hash-tactics-explained/"><u>[Updated] In 2024, Elevate Your YouTube Traffic  Best Hash Tactics Explained</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-seamless-video-editing-on-arm-devices-filmora-x-makes-it-happen/"><u>Updated In 2024, Seamless Video Editing on ARM Devices Filmora X Makes It Happen</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-art-of-sharing-on-social-making-instagram-stories-explode/"><u>[New] The Art of Sharing on Social  Making Instagram Stories Explode</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/digital-dazzle-fine-tuning-video-chrominance-for-beauty/"><u>Digital Dazzle  Fine-Tuning Video Chrominance for Beauty</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-full-breakdown-razers-hd-webcam-experience/"><u>2024 Approved  Full Breakdown  Razer's HD Webcam Experience</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-pandemonium-playlist-10-wildest-tiktok-gaming-adventures-for-2024/"><u>[Updated] Pandemonium Playlist  10 Wildest TikTok Gaming Adventures for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-oneplus-ace-2v-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock OnePlus Ace 2V Phone When You Forget the Password</u></a></li>
</ul></div>
