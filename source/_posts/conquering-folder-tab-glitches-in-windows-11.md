---
title: Conquering Folder Tab Glitches in Windows 11
date: 2025-01-09T08:50:24.565Z
updated: 2025-01-15T23:32:47.426Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conquering Folder Tab Glitches in Windows 11
excerpt: This Article Describes Conquering Folder Tab Glitches in Windows 11
keywords: Fix Folder Glitch Win11,Solve File Errors Win11,Unlock Folder Issues Windows11,Address Tab Bug in Win11,Overcome Folders Malfunction Windows,Tackle Directory Freeze 11,Eliminate Glitches Win11 Filesystem
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
---

## Conquering Folder Tab Glitches in Windows 11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-help.techidaily.com/new-from-raw-footage-to-final-cut-youtube-edition/"><u>[New] From Raw Footage to Final Cut YouTube Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-secrets-to-proficient-mobile-and-desktop-film-recording-for-2024/"><u>[New] Secrets to Proficient Mobile and Desktop Film Recording for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-guide-to-secure-and-cost-free-youtube-music-extraction/"><u>2024 Approved Guide to Secure and Cost-Free YouTube Music Extraction</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://win-lab.techidaily.com/auf-nvme-ssds-hochladen-klonierung-von-sata-festplatten-sicher-und-effizient-gestalten-lernstrategien-fur-zuverlassige-datentransfersysteme/"><u>Auf NVMe SSDs Hochladen: Klonierung Von SATA-Festplatten Sicher Und Effizient Gestalten – Lernstrategien Für Zuverlässige Datentransfersysteme</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-reinstate-windows-print-spooler/"><u>Guides to Reinstate Windows Print Spooler</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-realme-c67-4g-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Realme C67 4G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-a14-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy A14 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-unveiling-the-magic-behind-film-plots/"><u>In 2024, Unveiling the Magic Behind Film Plots</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-rated-quicktime-editors-free-and-easy-to-use/"><u>New Top-Rated QuickTime Editors Free and Easy to Use</u></a></li>
<li><a href="https://windows11.techidaily.com/restoration-of-microsoft-store-applications-in-1011-systems/"><u>Restoration of Microsoft Store Applications in 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-workflow-integration-to-do-plus-ifttt/"><u>Seamless Workflow Integration: To-Do + IFTTT</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-workflow-integrating-a-functional-taskbar-on-slate-devices-windows-11/"><u>Streamlining Workflow: Integrating a Functional Taskbar on Slate Devices (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0xc00d36b4-on-windows-11-pcs/"><u>Tackling Error 0XC00D36B4 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-pc-audio-with-a-fresh-windows-driver-installation/"><u>Transform Your PC Audio With a Fresh Windows Driver Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategies-for-ms-teams-error-80080300/"><u>Win11 Strategies for MS Teams Error 80080300</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-modern-standby-demystified-with-pros-and-cons/"><u>Windows Modern Standby Demystified with Pros & Cons</u></a></li>
</ul></div>

