---
title: Saving Screen Time by Hushing File Explorer Tabs
date: 2024-06-25T12:31:36.825Z
updated: 2024-06-26T12:31:36.825Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Saving Screen Time by Hushing File Explorer Tabs
excerpt: This Article Describes Saving Screen Time by Hushing File Explorer Tabs
keywords: Save Screen Time,Limit Tab Usage,Reduce File Explore,Minimize Browser Distractions,Control Tab Frequency,Decrease Digital Noise,Optimize Browsing Habits
thumbnail: https://thmb.techidaily.com/de7c313fd07e2524cf8d55d82a6066b369ed71aad2bc2f894ad55f60508b5e77.jpg
---

## Saving Screen Time by Hushing File Explorer Tabs

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
<li><a href="https://windows11.techidaily.com/how-to-activate-and-control-fast-boot-in-your-windows-11-pc/"><u>How to Activate and Control Fast Boot in Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-wxpxo11-dilemnas-fixes-for-non-openable-folders-after-double-clicks/"><u>Unfolding WXP/XO11 Dilemnas: Fixes for Non-Openable Folders After Double-Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-effective-network-sharing-tools-tech-giants-face-off/"><u>Determining Effective Network Sharing Tools: Tech Giants Face-Off</u></a></li>
<li><a href="https://windows11.techidaily.com/zap-zaps-revitalizing-a-sluggish-windows-11-experience/"><u>Zap Zaps: Revitalizing a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-reliable-remote-access-across-windows-networks/"><u>Ensuring Reliable Remote Access Across Windows Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://windows11.techidaily.com/quicker-quests-9-strategies-to-prevent-wwe-2k23-crashes/"><u>Quicker Quests: 9 Strategies to Prevent WWE 2K23 Crashes</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-living-virtually-tips-for-an-active-facebook-presence/"><u>In 2024, Living Virtually  Tips for an Active Facebook Presence</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advanced-tiktok-edit-tricks-to-boost-creativity/"><u>[Updated] Advanced TikTok Edit Tricks to Boost Creativity</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-xiaomi-13t-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Xiaomi 13T Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-files-after-iphone-15-pro-max-factory-reset-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Files after iPhone 15 Pro Max Factory Reset? | Stellar</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-snappers-playbook-advanced-tactics-for-filter-fun/"><u>The Snapper's Playbook  Advanced Tactics for Filter Fun</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-stabilizing-aerial-vision-a-comprehensive-guide-to-choosing-a-gimbal/"><u>[New] Stabilizing Aerial Vision  A Comprehensive Guide to Choosing a Gimbal</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-lava-yuva-2-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Lava Yuva 2 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-undead-humor-engine/"><u>2024 Approved  Undead Humor Engine</u></a></li>
</ul></div>
