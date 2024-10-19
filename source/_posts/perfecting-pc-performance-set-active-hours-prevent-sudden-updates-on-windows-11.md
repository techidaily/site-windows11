---
title: "Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
date: 2024-10-11T21:23:33.939Z
updated: 2024-10-18T18:14:53.439Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
excerpt: "This Article Describes Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11"
keywords: Win11 Boost Performance,Optimize PC Windows,Schedule PC Updates,Avoid Windows Disruptions,Active Hours Setting,Windows 11 Stability,Update Pause Benefits
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885928/19272" target="_top" id="1885928">
  <img src="//a.impactradius-go.com/display-ad/19272-1885928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/updated-streamline-your-storage-download-vimeo-videos-in-mp4-formats-for-2024/"><u>[Updated] Streamline Your Storage Download Vimeo Videos in MP4 Formats for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-devhome-enhancing-windows-11-performance/"><u>A Closer Look at DevHome: Enhancing Windows 11 Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-mcuicnt-file-execution-failure-on-windows/"><u>Addressing McUICnt File Execution Failure on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-decades-old-password-request-on-modern-windows/"><u>Bypassing Decades-Old Password Request on Modern Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-generative-ai-explained-an-essential-guide-for-parents/"><u>ChatGPT and Generative AI Explained: An Essential Guide for Parents</u></a></li>
<li><a href="https://windows11.techidaily.com/cooling-down-your-windows-11-computer/"><u>Cooling Down Your Windows 11 Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directive-for-drives-partitioned-areas-in-windows/"><u>Deletion Directive for Drives' Partitioned Areas in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/free-easy-to-use-screen-recording-tools-for-windows-10/"><u>Free, Easy-To-Use Screen Recording Tools For Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-poco-x6-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Poco X6 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-5-filters-for-deep-blue-cinematography/"><u>In 2024, Optimal 5 Filters for Deep Blue Cinematography</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-bring-your-vision-to-life-10-best-music-video-production-companies/"><u>New In 2024, Bring Your Vision to Life 10 Best Music Video Production Companies</u></a></li>
<li><a href="https://driver-install.techidaily.com/power-systems-up-intell-drivers/"><u>Power Systems Up: Intell Drivers</u></a></li>
</ul></div>

