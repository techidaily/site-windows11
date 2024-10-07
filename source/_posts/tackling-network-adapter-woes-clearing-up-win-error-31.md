---
title: "Tackling Network Adapter Woes: Clearing Up WIN Error 31"
date: 2024-09-29T22:38:23.287Z
updated: 2024-10-06T22:21:32.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Network Adapter Woes: Clearing Up WIN Error 31"
excerpt: "This Article Describes Tackling Network Adapter Woes: Clearing Up WIN Error 31"
keywords: Fixing Win32 Errors,Resolve NIC Issues,Windows Network Troubleshoot,Remove Win32 Error 31,Clear WIN Errors,Disable Bad Adapter,Stop Win Network Fails
thumbnail: https://thmb.techidaily.com/5b7228f82dd55952004c9e54eccc979f0193c694cfbf96a3723eb54169ea5205.jpg
---

## Tackling Network Adapter Woes: Clearing Up WIN Error 31

 Are you encountering an error message on Windows that reads "network adapter error code 31: this device is not working properly"? This error often occurs due to a corrupted or incorrect version of the network adapter driver installed on your PC.

 As such, let's explore all the ways to fix the network adapter error code 31 on Windows.

## 1\. Check for Any Pending Network Driver Updates

 First off, check to see if your network driver has any pending updates. While you can update the drivers for the device connected to your computer using Device Manager, we don't recommend it, as Device Manager often fails to find the most recent updates for the driver.

 You will most likely find the latest network driver on your computer manufacturer's website, so check who made your PC and visit their website for details. If you use an external network adapter, visit the adapter manufacturer's website instead.

 Additionally, you can also find new drivers using your manufacturer's proprietary system management tool. For example, with Lenovo and HP computers, you can use the Lenovo Vantage and HP Support Assistant utility to find and install new drivers for your network adapter and other devices.

## 2\. Perform a Driver Roll Back

 If you believe a recent driver update is causing the error, you can use the**Roll Back Driver** option to perform a rollback and reinstall the previous version of the network adapter driver.

To perform a network driver rollback:

1. Press**Win + R** to open Run.
2. Type**devmgmt** .**msc** and click**OK** to open Device Manager.
3. In Device Manager, expand the**Network Adapters** section.  
![device manager network adapter properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-adapter-properties.jpg)
4. Right-click on your network device and select**Properties** .

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. In the**Properties** dialog, open the**Driver** tab.  
![device manager network driver roll back driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-driver-roll-back-driver-1.jpg)
6. Click the**Roll Back Driver** button. If the option is**greyed out** , your computer doesn't have an older driver to perform a rollback. Check your manufacturer's website to see if they have older drivers in an archive.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Next, in the confirmation dialog, give a reason and click**Yes** .
8. Once the driver rollback is complete, check if the problem is resolved. If not, check if you can perform another rollback for the network device driver to see if that helps.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Perform a Network Reset

 Windows 10 and 11 feature a "network reset" option. This will remove and reinstall the network drivers and other networking components to their factory defaults to help you fix network adapter issues on your computer.

To perform a network reset:

1. Press**Win + I** to open**Settings** .
2. Open the**Network & internet** tab in the left pane.
3. Click on**Advanced network settings** .
4. ![advanced network settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11.jpg)  
 Next, click on**Network reset** .
5. ![advanced network settings windows 11 network reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset.jpg)  
 Click on**Reset now** and click**Yes** to rest your network settings.  
![advanced network settings windows 11 network reset reset now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset-reset-now.jpg)
6. Your PC will restart during the process.

## 3\. Delete the Corrupted Network Config File on Older Machines

![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

 On an older Windows Vista or XP computer, you can resolve the issue by tweaking a registry entry. You need to delete a corrupt config key in Registry Editor and then uninstall the device from Device Manager to fix the error.

 The following steps only apply to a Windows computer running Vista or XP.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .
3. In Registry Editor, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Network\`
4. In the right pane, locate the**Config** value.
5. Next, right-click on the**Config** value and select**Delete** .
6. Click**Yes** to confirm the action.

 Once the key is deleted, you'll need to remove and reinstall the network driver. You can do it using Device Manager, as shown in the step below.

 Note that modifications to some registry entries may fail due to insufficient permission issues. If you get an error when deleting the Config value, take full ownership of the registry key and then try again. Our guide on[how to take full ownership of registry keys on Windows 10](https://www.makeuseof.com/windows-10-full-ownership-registry/) will work on older systems too.

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see[how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![uninstall network driver device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-driver-device-device-manager.jpg)
5. Click**Uninstall** to confirm the action.

 Once uninstalled, restart your PC. After the restart, Windows will automatically detect connected but unrecognized devices and install the necessary drivers.

 If Windows fails to install the driver, open**Device Manager** , right-click on your network adapter and select**Update driver** . You can also download the latest drivers from your computer manufacturer's website, as shown in step one.

## 6\. Perform a System Restore

 This error can occur if Windows modifies your network adapter settings during an update. You can use a restore point to undo the changes and restore the computer to its earlier state. Since Windows automatically creates a new restore point before installing an update, you should be able to find a recent restore point to undo the changes.

To perform a restore point:

1. Press the**Win** key and type**restore point.**
2. Click on**Create a restore point** from the search result.
3. In the**System Protection** dialog, click the**System Restore** button.  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
4. In the**System Restore** dialog, click**Next** to view all the available restore points. Additionally, check the**Show more restore points** option to view older restore points.
5. Select the most recent restore point and click**Next** .  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
6. Confirm your restore point and read the description to understand what apps and data on your PC are affected.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click**Finish** to initialize the system restore process. Your PC will restart and may take some time to finish. Your PC will restart and show a system restore success or failure message.

 If the restore process fails, try it again. At times, it may take more than one attempt to get it right. If the computer is restored, it should hopefully restore the old network driver configuration and fix the error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix the Network Adapter Code 31 Error on Windows

 Network adapter code 31 is one of the many errors that can cause your network adapter to malfunction. To fix the error, check if you have the latest network adapter driver installed. If necessary, perform a driver rollback, clean up corrupt registry value or perform a system restore.

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
<li><a href="https://article-posts.techidaily.com/2024-approved-ultimate-clearer-eliminate-backgrounds-effectively/"><u>2024 Approved Ultimate Clearer Eliminate Backgrounds Effectively</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/beginners-blueprint-for-crafting-your-psn-signup/"><u>Beginner's Blueprint for Crafting Your PSN Signup</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-newest-hp-deskjet-ink-advantage-3755-all-in-one-printer-drivers-for-windows-101187/"><u>Download the Newest HP DeskJet Ink Advantage 3755 All-in-One Printer Drivers for Windows 10/11/8/7</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oppo-find-x6-pro-by-drfone-android/"><u>How to Bypass FRP on Oppo Find X6 Pro?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-emotion-to-entertainment-the-artisans-approach-to-making-memes-gifs/"><u>In 2024, From Emotion to Entertainment The Artisan’s Approach to Making Memes (GIFs)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/invisible-audiences-viewing-instagram-stories-privately-from-pcandroidios-screens/"><u>Invisible Audiences Viewing Instagram Stories Privately From PC/Android/iOS Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-8-must-do-tasks-following-the-acquisition-of-a-new-windows-computer/"><u>Maximizing Performance: 8 Must-Do Tasks Following the Acquisition of a New Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-the-boring-windows-terminal-into-a-stylish-command-hub/"><u>Revamping the Boring Windows Terminal Into a Stylish Command Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-netflix-download-functionality-for-desktop-upcoming-changes-explained/"><u>Say Goodbye to Netflix Download Functionality for Desktop: Upcoming Changes Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-12-improvements-for-a-future-release-what-users-hope-for-from-windows-12/"><u>The Essential 12 Improvements for a Future Release: What Users Hope For From Windows 12</u></a></li>
<li><a href="https://windows11.techidaily.com/the-nearly-complete-windows-11-update-for-2amz-may-2024-innovations-and-features-ahead/"><u>The Nearly Complete Windows 11 Update for 2Amz, May 2024: Innovations and Features Ahead!</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-troubled-tunes-of-your-ride-understanding-why-car-speakers-fail/"><u>The Troubled Tunes of Your Ride: Understanding Why Car Speakers Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-techniques-for-resolving-memory-corruption-issues-in-windows-11/"><u>Top 5 Techniques for Resolving Memory Corruption Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-strategies-microsoft-should-implement-to-rescue-github-copilot-from-a-fate-similar-to-cortana/"><u>Top Strategies Microsoft Should Implement to Rescue GitHub Copilot From a Fate Similar to Cortana</u></a></li>
<li><a href="https://os-tips.techidaily.com/using-your-iphone-to-monitor-and-elevate-emotional-well-being/"><u>Using Your iPhone to Monitor & Elevate Emotional Well-Being</u></a></li>
</ul></div>

