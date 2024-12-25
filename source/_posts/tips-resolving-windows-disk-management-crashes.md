---
title: "Tips: Resolving Windows Disk Management Crashes"
date: 2024-12-24T18:52:12.108Z
updated: 2024-12-25T16:06:31.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tips: Resolving Windows Disk Management Crashes"
excerpt: "This Article Describes Tips: Resolving Windows Disk Management Crashes"
keywords: Fix Windows Disk Errors,Solve DiskMan Crashes,Unlock PC Storage Issue,Windows Storage Failure Fix,Stop Disk Manager Crash,Resolve Drive Management,Repair Windows Disk Problems
thumbnail: https://thmb.techidaily.com/2a29084ef28c5d6ebf693615660d627bf6405cc5a8ac614e41f7b335143de3df.jpg
---

## Tips: Resolving Windows Disk Management Crashes

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-ignite-audience-interest-with-effective-strategies-in-video-outros/"><u>[New] 2024 Approved Ignite Audience Interest with Effective Strategies in Video Outros</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/treaming-smarts-engaging-viewers-on-multiple-networks-for-2024/"><u>[New] Streaming Smarts Engaging Viewers on Multiple Networks for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-leading-edge-screen-snapshot-software/"><u>[Updated] 2024 Approved Leading Edge Screen Snapshot Software</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-asmr-video-knowledge-for-beginners/"><u>[Updated] In 2024, ASMR Video Knowledge for Beginners</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-ultimate-list-of-highest-rated-free-video-editing-apps-for-idevices/"><u>[Updated] Ultimate List of Highest-Rated Free Video Editing Apps for iDevices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-your-content-strategies-to-skyrocket-video-popularity/"><u>Ace Your Content Strategies to Skyrocket Video Popularity</u></a></li>
<li><a href="https://win-solutions.techidaily.com/comprehensive-strategies-to-address-dev-error-5573-on-xbox-and-pc-warzone-edition/"><u>Comprehensive Strategies to Address Dev Error 5573 on Xbox and PC: Warzone Edition</u></a></li>
<li><a href="https://facebook.techidaily.com/easy-ways-to-detect-unauthorized-pc-access/"><u>Easy Ways to Detect Unauthorized PC Access</u></a></li>
<li><a href="https://windows11.techidaily.com/free-up-local-space-in-win11-file-saving-techniques-max-156-chars/"><u>Free Up Local Space in Win11: File-Saving Techniques (Max 156 Chars)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-honor-v-purse-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Honor V Purse Black and White | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-cure-windows-dism-failure-error-0x800f082f/"><u>Steps to Cure Windows' DISM Failure Error 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/successful-recovery-of-non-functioning-ccleaner-win1011/"><u>Successful Recovery of Non-Functioning CCleaner Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0x800700e9-issue-with-xbox-game-pass-and-windows-11/"><u>Troubleshooting 0X800700E9 Issue with Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-how-windows-maintains-its-efficiency/"><u>Understanding How Windows Maintains Its Efficiency</u></a></li>
</ul></div>

