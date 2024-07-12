---
title: Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC
date: 2024-07-11T21:48:05.884Z
updated: 2024-07-12T21:48:05.884Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC
excerpt: This Article Describes Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC
keywords: Fixing Mail Folder Errors,Resolving Closed Mail Issues,Troubleshooting MS Mail,Microsoft Outlook Folder Access,Overcoming Email Open Failures,Outlook Error,Closed Folder Problems in Office 365
thumbnail: https://thmb.techidaily.com/99ddeff4dd981a34b1bf66d98e84fae1038add51e63fa5e698f7136621990952.jpg
---

## Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC

 Do you encounter the error "the set of folders cannot be opened" when launching Outlook? The leading cause behind this error is the interference from Outlook add-ins. Other possible causes include issues with your email profile, corruption of your Outlook profile, or corrupted OST and data files.

 Likewise, using an incompatible version of Outlook or the same email address in multiple mail apps may also result in an error. Here are some fixes you should apply to resolve the issue.

## 1\. Perform Some Preliminary Checks

 Before moving on to any serious troubleshooting, perform the following preliminary checks first, as they may resolve the error right away:

* Close other open email clients, especially the Mail app that comes built into Windows.
* Run Outlook as administrator. Right-click on the Outlook client and hit **Run as administrator**.  
![Run Outlook as an Administrator in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-run-outlook-as-an-administrator-in-windows.jpg)
* Ensure you have the compatible version of Outlook (**x32** or **x64**) installed on your device.
* Update or repair Outlook to ensure a corrupt or outdated installation has not caused the error.

 If the basic checks and fixes do not resolve the error, it's time to move on to serious troubleshooting.

## 2\. Check for Add-In Interference

 The add-in interference is the leading cause of Outlook not launching and presenting the "the set of folders cannot be opened" error, as reported by numerous users on various online forums. Running Outlook in Safe mode is the best way to confirm that since it launches the app without add-ins and other elements.

 Press **Win + R,** type **"Outlook.exe /safe"** and hit **Enter** to launch Outlook in safe mode.

![Run Outlook in Safe Mode by Running a Command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-run-outlook-in-safe-mode-by-running-a-command-in-windows.jpg)

 If the app launches without an error, the add-in interference must have been the culprit. Therefore, stay in safe mode and turn off any interfering add-ins. Here's how:

1. Go to the **File** tab and select **Options**.  
![Select Options in the File Tab of Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-options-in-the-file-tab-of-outlook.jpg)
2. Go to the **Add-ins** tab in the left menu.
3. Select **"COM Add-ins"** from the **Manage** menu, then click **Go**.  
![Click on the Go Button After Selecting the COM Add-ins Option From the Manage Dropdown Menu in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-click-on-the-go-button-after-selecting-the-com-add-ins-option-from-the-manage-dropdown-menu-in-outlook.jpg)
4. Uncheck the boxes behind any add-ins you don't need and disable them.

## 3\. Check for Issues With the OST File

 The mislocated OST file or its corruption can also lead to the error. Therefore, ensure the file is at its original location and recreate it to eliminate the possibility of file corruption. Here's how:

1. Open the Control Panel.
2. Click on the **View by** dropdown menu and select **Large icons**.
3. Go to **Mail (Microsoft Outlook)**.  
![Go to Mail Option in the Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-go-to-mail-option-in-the-windows-control-panel.jpg)
4. Click the **Data Files...** button.
5. Select the OST file location and click **Open File Location...**  
![Click the Open File Location Button After Selecting the OST File in the Data Files Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-click-the-open-file-location-button-after-selecting-the-ost-file-in-the-data-files-tab.jpg)
6. Right-click the file in the **File Explorer** and select **Properties**. If the file type is **OST**, the file is in the right place, and no action is needed.  
![Ensure the File Type Is OST by Going to Properties in the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-ensure-the-file-type-is-ost-by-going-to-properties-in-the-windows-file-explorer.jpg)

 To ensure that the OST file is not corrupt, copy it to a safe location outside the Outlook installation folder. Then, right-click and delete the main OST file.

 After that, restart Outlook, and it will automatically recreate the OST file and download the data from the Exchange Server. If you decide to go this route, remain connected to the internet.

## 4\. Check for Issues With Your Outlook Profile

 Outlook uses the Outlook profile to store information about your email accounts, data files, and other client settings. Profile corruption can prevent Outlook from loading the necessary data at launch and can present the "set of folders cannot be opened" error. To rule out profile corruption as the cause of the problem, follow these steps:

1. Open the Control Panel.
2. Click on the **View by** dropdown menu and select **Large icons**.
3. Go to **Mail (Microsoft Outlook)**.
4. Click the **Show Profiles** button.
5. Click on the **Add** button.  
![Click on the Add Button in the Show Profiles Menu in Mail Microsoft Outlook Settings in the Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-click-on-the-add-button-in-the-show-profiles-menu-in-mail-microsoft-outlook-settings-in-the-windows-control-panel.jpg)
6. Follow the instructions on the screen to create your new profile.
7. Launch a new Outlook profile.

 If Outlook launches successfully, a corrupt profile could be to blame. So, continue to use the new profile after adding your account. If switching profiles does not help, go to the next step.

## 5\. Look for Issues With the Navigation Pane

 Misconfigured navigation pane settings or corrupted XML files, which store the navigation pane settings, can also prevent Outlook from opening and presenting the error. To eliminate this possibility, you should reset the navigation pane in Outlook that will reset the configuration to its default settings. Press **Win + R**, type **"outlook.exe /resetnavpane"** and hit **Enter**.

![Run a Command to Reset the Navigation Pane in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-run-a-command-to-reset-the-navigation-pane-in-outlook.jpg)

 After that, relaunch Outlook. If resetting the navigation pane doesn't work, you should delete the XML file manually. To do this, press **Win + R**, type **"%localappdata%\\Microsoft\\Outlook"** and hit **Enter**. After that, delete any XML files you find in this folder.

 Then, restart Outlook from scratch, and it will recreate the XML file with default settings. There's a good chance that it will resolve the issue.

## 6\. Repair the Outlook PST Files

 PST files store data about contacts, calendars, events, and messages. If the error window indicates that Outlook could not open the PST file, then the file could be corrupt, which could be why Outlook presents the error. Therefore, you can fix it by repairing the files. To repair the corrupted data files, follow the below steps:

1. Navigate to the Outlook installation folder, which is located here by default:  
`C:\Program Files\Microsoft Office\root\Office16`
2. Locate the **ScanPST.exe** file and run it.
3. Click **Browse**, paste the path from the error window into the **Inbox Repair** tool, and click Start.  
![Click Start After Pasting the Path From the Error Window into the Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/10-click-start-after-pasting-the-path-from-the-error-window-into-the-inbox-repair-tool.jpg)
4. Then, click the **Repair** button to complete the repair.

 If you can't locate the Outlook folder in the path mentioned above, see our [guide on repairing the PST file](https://www.makeuseof.com/repair-pst-without-scanpst/) for the exact path.

## 7\. Run the Microsoft Support and Recovery Assistant

 If none of the above fixes resolves the error, run the Microsoft Support and Recovery Assistant, Microsoft's recommended tool for fixing issues with Microsoft Office products.

 Here's how to download and use the tool:

1. Download **Microsoft Support and Recovery Assistant** from the [Microsoft website](https://www.microsoft.com/en-US/download/details.aspx?id=100607).
2. Unzip the file you just downloaded.
3. Run the **SaraSetup** file to install the software.
4. Upon installation, launch the tool and click the **"I agree"** button.
5. Select **Outlook** from the list of applications and click **Next**.  
![Click Next After Selecting Outlook From the List of Apps in the Microsoft Support and Recovery Assistant Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/11-click-next-after-selecting-outlook-from-the-list-of-apps-in-the-microsoft-support-and-recovery-assistant-window.jpg)
6. Then, follow the on-screen instructions to carry out the repair.

 If any underlying problem with the Outlook client contributed to this issue, running this tool will most likely resolve the issue.

## Run Outlook on Windows Without a Hitch

 Running into irritating errors when launching the Outlook client can hinder our productivity. Hopefully, you now better understand what causes the "the set of folders cannot be opened" error. In addition, by carefully applying the fixes listed above, you should be able to fix the error and launch Outlook successfully.

 Likewise, using an incompatible version of Outlook or the same email address in multiple mail apps may also result in an error. Here are some fixes you should apply to resolve the issue.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-social-media-strategy-broadcasting-twitch-to-facebook/"><u>[Updated] 2024 Approved  Social Media Strategy  Broadcasting Twitch to Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-extracting-device-ids-on-windows-pcs/"><u>Detailed Guide: Extracting Device IDs on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-art-of-attraction-mastering-youtubes-glamour-trove-for-2024/"><u>The Art of Attraction  Mastering Youtube's Glamour Trove for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-the-impact-of-high-cpu-tiworkerexe-applications/"><u>Decreasing the Impact of High-CPU TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://driver-install.techidaily.com/instantly-setup-windows-supported-ssd-drivers/"><u>Instantly Setup Windows-Supported SSD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-restarting-windows-update-process/"><u>Essential Tips for Restarting Windows Update Process</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-breakdown-using-toolbar-in-mspcm-on-windows-11/"><u>Comprehensive Breakdown: Using Toolbar in MSPCM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-versatility-top-10-innovative-ways-to-use-powertoys-tools/"><u>Discover Versatility: Top 10 Innovative Ways to Use PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-m6-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Poco M6 5G Phone without PIN</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-unforgettable-videos-top-10-iphone-and-ipad-collage-apps-2023-for-2024/"><u>New Make Unforgettable Videos Top 10 iPhone and iPad Collage Apps 2023 for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-next-gen-gpus-for-crystal-clear-4k/"><u>In 2024, Next-Gen GPUs for Crystal Clear 4K</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-network-how-to-conceal-on-windows-pc/"><u>Elusive Network: How to Conceal on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Sony Xperia 10 V? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-expert-guide-to-using-toolbar-on-w11-winpcm/"><u>Elevate Your Productivity: Expert Guide to Using Toolbar on W11 WinPCM</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-visuals-perfect-windows-desktop-backdrops/"><u>Elevating Visuals: Perfect Windows Desktop Backdrops</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-change-the-pace-best-gif-speed-changer-tools-reviewed/"><u>New 2024 Approved Change the Pace Best GIF Speed Changer Tools Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-realme-note-50-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Realme Note 50 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-in-discord-for-windows-os/"><u>Fix 'Installation Failed' In Discord for Windows OS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ideal-choice-best-free-reliable-mac-screenshot-tools/"><u>[New] Ideal Choice  Best Free, Reliable Mac Screenshot Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-retro-revival-simple-steps-to-achieve-a-vhs-look-in-fcp/"><u>Updated Retro Revival Simple Steps to Achieve a VHS Look in FCP</u></a></li>
</ul></div>
