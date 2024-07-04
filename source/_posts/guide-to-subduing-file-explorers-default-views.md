---
title: Guide to Subduing File Explorer's Default Views
date: 2024-07-03T11:10:03.235Z
updated: 2024-07-04T11:10:03.235Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Subduing File Explorer's Default Views
excerpt: This Article Describes Guide to Subduing File Explorer's Default Views
keywords: Subdue Explore Views Guide,Taming File Viewer Display,Mastery in File Explorer Normals,Halt Default File Explorer View,Conquering Default Options,Suppress Explorer Window Views,Override Explorers Initial Screens
thumbnail: https://thmb.techidaily.com/6c8487e0b404251fb12aeaebde28154ddd618ecb4b5d51b0cd4522eee48c4e1f.jpg
---

## Guide to Subduing File Explorer's Default Views

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

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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
<li><a href="https://windows11.techidaily.com/revisiting-microsofts-phone-tethering-for-windows-11-users/"><u>Revisiting Microsoft's Phone Tethering for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/1719346558796-why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-error-code-31-a-troubleshooting-manual/"><u>Navigating Through Windows Error Code 31: A Troubleshooting Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-tackle-office-errors-a-winos-approach/"><u>Efficient Strategies to Tackle Office Errors: A WinOS Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unresponsive-f-keys-troubleshooting-in-windows-11-os/"><u>Fix: Unresponsive F Keys - Troubleshooting in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/audio-recording-made-easy-free-x-recorder-for-pc-for-2024/"><u>Audio Recording Made Easy  Free X-Recorder for PC for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-resolve-instagrams-video-problems-swiftly-for-2024/"><u>[New] Resolve Instagram's Video Problems Swiftly for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-how-to-create-benime-whiteboard-animation-on-android/"><u>2024 Approved How to Create Benime Whiteboard Animation on Android</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/4-ways-to-unlock-iphone-12-pro-max-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>4 Ways to Unlock iPhone 12 Pro Max to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-theyoucamguidetoeffectivewebcapture/"><u>[Updated] 2024 Approved  TheYouCamGuideToEffectiveWebCapture</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-quick-tutorial-get-snapchat-running-on-macos/"><u>[New] In 2024, Quick Tutorial  Get Snapchat Running on macOS</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-microsoft-excel-2013-error-code-0x800a03ec-by-stellar-guide/"><u>How to Fix Microsoft Excel 2013 Error Code 0x800A03EC?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-ultimate-pc-workaround-for-console-gaming-recordings-for-2024/"><u>[New] The Ultimate PC Workaround for Console Gaming Recordings for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-easy-guide-to-crafting-fun-snapchat-lenses/"><u>[New] 2024 Approved  Easy Guide to Crafting Fun Snapchat Lenses</u></a></li>
</ul></div>
