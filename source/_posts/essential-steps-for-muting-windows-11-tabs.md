---
title: Essential Steps for Muting Windows 11 Tabs
date: 2024-06-25T12:03:48.558Z
updated: 2024-06-26T12:03:48.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Muting Windows 11 Tabs
excerpt: This Article Describes Essential Steps for Muting Windows 11 Tabs
keywords: Mute Win11 Tabs,Silence Windows XTABs,Tab Muting in Win11,Windows Tabs Quieten,Stop Tab Noise Win11,Hush Windows Tabding,Shutdown Windows Tabs
thumbnail: https://thmb.techidaily.com/65300c988d41879c46efcdc0b8a7f4ebdd53e06feae865a9a356c9f8b695aec3.jpg
---

## Essential Steps for Muting Windows 11 Tabs

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://windows11.techidaily.com/navigate-past-share-permission-hurdles-in-win-os/"><u>Navigate Past Share Permission Hurdles in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-programs-by-their-launch-shorthand-labels/"><u>Identifying Programs by Their Launch Shorthand Labels</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-removing-device-from-apple-id-for-your-iphone-12-mini-by-drfone-ios/"><u>In 2024, Removing Device From Apple ID For your iPhone 12 mini</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-editing-gopro-videos-on-pc-quik-alternatives-and-more/"><u>2024 Approved Editing GoPro Videos on PC Quik, Alternatives, and More</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-smaller-is-better-top-drone-brands-reviewed/"><u>2024 Approved  Smaller Is Better  Top Drone Brands Reviewed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-streamlining-screen-capture-minecraft-edition-tips-and-tricks-for-macs/"><u>In 2024, Streamlining Screen Capture  Minecraft Edition - Tips & Tricks for Macs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discovering-where-youtube-video-management-happens-for-2024/"><u>[Updated] Discovering Where YouTube Video Management Happens for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-on-apple-iphone-15-pro-max-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock On Apple iPhone 15 Pro Max? How to Fix it?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-bright-future-for-your-android-videos-a-comprehensive-plan/"><u>[Updated] In 2024, Bright Future for Your Android Videos - A Comprehensive Plan</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-expert-tips-for-avoiding-instagram-video-troubles/"><u>[Updated] In 2024, Expert Tips for Avoiding Instagram Video Troubles</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-building-a-powerful-brand-on-tiktok-maximizing-views-and-likes-for-2024/"><u>[Updated] Building a Powerful Brand on TikTok  Maximizing Views & Likes for 2024</u></a></li>
</ul></div>
