---
title: "How to Reduce Clutter: Disabling Explorer Tabs"
date: 2024-12-04T18:24:57.328Z
updated: 2024-12-10T21:44:48.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Reduce Clutter: Disabling Explorer Tabs"
excerpt: "This Article Describes How to Reduce Clutter: Disabling Explorer Tabs"
keywords: Reduce Clutter Guide,Explore Tab Control,Declutter Browsers,Limit Web Pages,Eliminate Browser Chaos,Tabs Disabling Techniques,Streamline Internet Use
thumbnail: https://thmb.techidaily.com/4cbebb13391bd3ac3f3b9ef43b45b771ba69f0146a8bbd42e4f0e8dd5abd0510.jpg
---

## How to Reduce Clutter: Disabling Explorer Tabs

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-decoding-youtubes-user-comment-selection-criteria-for-2024/"><u>[New] Decoding YouTube's User-Comment Selection Criteria for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-depth-look-at-sonys-x1000v-hd-recorder/"><u>[New] In-Depth Look at Sony's X1000V HD Recorder</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-live-feed-capture-via-obs-for-instagram/"><u>[New] Live Feed Capture via OBS for Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-guidelines-for-perfect-nightscape-photography-for-2024/"><u>[Updated] Guidelines for Perfect Nightscape Photography for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-live-stream-to-facebook-with-wirecast/"><u>[Updated] How to Live Stream to Facebook with Wirecast</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-beginners-bane-the-top-8-youtube-errors-you-shouldnt-commit/"><u>[Updated] In 2024, Beginner's Bane The Top 8 Youtube Errors You Shouldn't Commit</u></a></li>
<li><a href="https://hardware-help.techidaily.com/amd-radeon-rx-480-seamless-driver-installation-and-enhanced-visual-experience/"><u>AMD Radeon RX 480 - Seamless Driver Installation and Enhanced Visual Experience</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/comment-transferer-des-fichiers-dune-cle-usb-a-un-ordinateur-windows-11/"><u>Comment Transférer Des Fichiers D'Une Clé USB À Un Ordinateur Windows 11?</u></a></li>
<li><a href="https://solve-helper.techidaily.com/grabacion-y-conversion-de-mp3-a-flac-por-internet-sin-coste-alguno-utiliza-movavi/"><u>Grabación Y Conversión De MP3 a FLAC Por Internet Sin Coste Alguno - Utiliza Movavi</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-and-use-the-dialer-on-win-11/"><u>How to Open and Use the Dialer on Win 11</u></a></li>
<li><a href="https://games-able.techidaily.com/in-depth-look-at-pimax-crystals-visual-mastery-and-misfires/"><u>In-Depth Look at Pimax Crystal’s Visual Mastery and Misfires</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-your-backup-journey-with-windows-11s-restore-capabilities/"><u>Initiating Your Backup Journey with Windows 11'S Restore Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-opengl-error-code-3-in-os-11/"><u>Overcoming the Challenge of OpenGL Error Code 3 in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/project-mastery-exclusive-key-maneuvers/"><u>Project Mastery: Exclusive Key Maneuvers</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-startup-procedures-in-the-latest-windows-os/"><u>Streamlining Startup Procedures in the Latest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-laptop-studio-2-review-artists-companion-for-the-future/"><u>Surface Laptop Studio 2 Review: Artists' Companion for the Future</u></a></li>
<li><a href="https://windows11.techidaily.com/teleport-yourself-to-the-network-with-these-tips-for-win/"><u>Teleport Yourself to the Network with These Tips for Win</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-winning-edge-fps-tips-for-valorant-on-pc/"><u>Unlock Your Winning Edge: FPS Tips for Valorant on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-best-game-install-location-on-windows-xbox/"><u>Unlocking the Best Game Install Location on Windows Xbox</u></a></li>
</ul></div>

