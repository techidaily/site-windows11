---
title: How to Dampen Explore Tabs in Windows 11 OS
date: 2024-06-25T12:31:18.301Z
updated: 2024-06-26T12:31:18.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Dampen Explore Tabs in Windows 11 OS
excerpt: This Article Describes How to Dampen Explore Tabs in Windows 11 OS
keywords: Windows 11 Tab Control,Silent Page Switching,Reducing Screen Refresh,Noise-Free Browser Navigation,Stealth Explore Tabs,Quiet OS Browsing,Hush Window Activity
thumbnail: https://thmb.techidaily.com/3fdaca488d74735acc0a94b8e5d7a94444c107a2d9f4a5ecb937f59cae54b660.jpg
---

## How to Dampen Explore Tabs in Windows 11 OS

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
<li><a href="https://windows11.techidaily.com/overcoming-resource-monitor-stalls-in-windows-11/"><u>Overcoming Resource Monitor Stalls in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/key-applications-that-bridge-the-mac-and-windows-divide/"><u>Key Applications that Bridge the Mac and Windows Divide</u></a></li>
<li><a href="https://windows11.techidaily.com/paramount-procedures-for-wiping-your-windows-installation/"><u>Paramount Procedures for Wiping Your Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-notetaking-for-windows-professionals-win11w10/"><u>Advanced Notetaking for Windows Professionals (Win11/W10)</u></a></li>
<li><a href="https://windows11.techidaily.com/win-error-restoring-lost-or-absent-mfc71udll/"><u>Win Error: Restoring Lost or Absent Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-melody-seeker-find-mp3-on-fb/"><u>In 2024, Melody Seeker  Find MP3 on FB</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-digital-deviants-titles-mirroring-gta-v-experience/"><u>[New] In 2024, Digital Deviants  Titles Mirroring GTA V Experience</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-infuse-your-instagram-with-funny-flair-a-complete-guide-to-gif-memes/"><u>2024 Approved  Infuse Your Instagram with Funny Flair – A Complete Guide to GIF Memes</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-vivo-x-fold-2-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Vivo X Fold 2 FRP Without Computer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-step-by-step-livestreaming-to-facebook-from-iphonestablets/"><u>[New] 2024 Approved  Step-by-Step  Livestreaming to Facebook From iPhones/Tablets</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-system-prerequisites-for-running-big-sur-on-macs/"><u>[Updated] System Prerequisites for Running Big Sur on Macs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-of-the-web-the-10-leading-sites-for-purchasing-mystery-boxes/"><u>2024 Approved  Best of the Web  The 10 Leading Sites for Purchasing Mystery Boxes</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-a1x-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo A1x 5G to Samsung Phone | Dr.fone</u></a></li>
</ul></div>
