---
title: "Curbing the Noise: Quiet Explore Tab Behavior"
date: 2024-07-11T22:21:06.559Z
updated: 2024-07-12T22:21:06.559Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Curbing the Noise: Quiet Explore Tab Behavior"
excerpt: "This Article Describes Curbing the Noise: Quiet Explore Tab Behavior"
keywords: Silent Exploration Guide,Quiet App Interface,Peaceful Navigation Tips,Soft Touch Experience,Calm App Usage,Low-Volume Browse,Serene Search Strategy
thumbnail: https://thmb.techidaily.com/c92572eed4dd2bbe96a0af1968717f74dd3686117855d1fc2a4babce9d7f3f12.png
---

## Curbing the Noise: Quiet Explore Tab Behavior

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
<li><a href="https://extra-support.techidaily.com/updated-lens-based-enlightenment-guide-to-editing-brilliance/"><u>[Updated] Lens-Based Enlightenment  Guide to Editing Brilliance</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-black-windows-back-with-simple-steps/"><u>Turn Black Windows Back with Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-individual-user-settings-on-group-policy-level/"><u>Delving Into Individual User Settings on Group Policy Level</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-office-activation-woes/"><u>Unlocking Windows Office Activation Woes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-document-your-days-with-xiaomis-state-of-the-art-screenshot-tool/"><u>[Updated] Document Your Days with Xiaomi's State-of-the-Art Screenshot Tool</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fifa-video-highlights-top-youtube-data-infographics/"><u>[New] In 2024, FIFA Video Highlights  Top YouTube Data Infographics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-seamless-backdrop-switches-for-google-meet-users/"><u>In 2024, Seamless Backdrop Switches for Google Meet Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-15-youtube-openings-elevate-your-contents-impact-for-2024/"><u>Top 15 YouTube Openings  Elevate Your Content's Impact for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tips-for-individualized-pattern-security-on-windows/"><u>Cutting-Edge Tips for Individualized Pattern Security on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-captivating-comedy-crafted-step-by-step-meme-tutorial/"><u>In 2024, Captivating Comedy Crafted  Step-by-Step Meme Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-files-a-step-by-step-windows-process/"><u>Converting Files: A Step-by-Step Windows Process</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-disparities-microsoft-and-default-windows-login-types/"><u>Dissecting Disparities: Microsoft and Default Windows Login Types</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-paths-opening-system-information-at-your-fingertips/"><u>Direct Paths: Opening System Information at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-tecno-spark-10-4g-by-fonelab-android-recover-music/"><u>Undelete lost music from Tecno Spark 10 4G</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-lenovo-thinkphone-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Lenovo ThinkPhone Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-unknown-obs-record-error-on-windows-11-pc/"><u>Combat Unknown OBS Record Error on Windows 11 PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-breaking-barriers-in-advertising-animating-for-maximum-roi-on-fb/"><u>In 2024, Breaking Barriers in Advertising  Animating for Maximum ROI on FB</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-express-yourself-authentically-on-instagram-with-these-captions/"><u>2024 Approved  Express Yourself Authentically on Instagram with These Captions</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-boost-your-videos-popularity-on-youtube/"><u>[New] In 2024, Boost Your Video's Popularity on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-local-group-policy-editor-in-windows-11/"><u>10 Ways to Open the Local Group Policy Editor in Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-role-of-extras-in-creating-dynamic-storytelling/"><u>In 2024, The Role of Extras in Creating Dynamic Storytelling</u></a></li>
<li><a href="https://extra-tips.techidaily.com/bridging-gap-integrating-zoom-into-your-gmail-setup/"><u>Bridging Gap  Integrating Zoom Into Your Gmail Setup</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-resize-your-video-tips-and-tricks-for-perfect-dimensions-for-2024/"><u>New Resize Your Video Tips and Tricks for Perfect Dimensions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-kali-with-windows-os-seamlessly/"><u>Combining Kali with Windows OS Seamlessly</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-top-10-igtv-channels-you-should-start-following-for-2024/"><u>[New] Top 10 IGTV Channels You Should Start Following for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-around-scheduler-setbacks-with-ease/"><u>Turn Around Scheduler Setbacks with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
</ul></div>
