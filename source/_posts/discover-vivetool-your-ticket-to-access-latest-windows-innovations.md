---
title: "Discover ViVeTool: Your Ticket to Access Latest Windows Innovations"
date: 2024-07-11T21:30:38.200Z
updated: 2024-07-12T21:30:38.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Discover ViVeTool: Your Ticket to Access Latest Windows Innovations"
excerpt: "This Article Describes Discover ViVeTool: Your Ticket to Access Latest Windows Innovations"
keywords: ViVeTool Insights,Windows Innovation Guide,ViVeTool Updates,New Windows Features,ViVeTech Latest News,Windows Tech Access,Discover Windows Edge
thumbnail: https://thmb.techidaily.com/57dbc57b52c40c100c33b010fd03c7c914f04eea27a15b8c369fc3e51785f1d6.jpg
---

## Discover ViVeTool: Your Ticket to Access Latest Windows Innovations

 ViVeTool is an open-source command-line tool to enable experimental but hidden features on your Windows computer. It is also available in a GUI version, which makes it much easier to enable or disable certain features on Windows.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

## What Is ViVeTool, and How Does It Work?

 ViVeTool is a third-party open-source C# library and console app to enable unreleased features on your Windows computer. You can also use it to restore or disable certain features.

 ViVeTool uses feature IDs, part of Windows Feature Management, a software-development practice, to identify the available features. You can then use the feature IDs to enable or disable certain features on your Windows computer by using the ViVeTool command-line or GUI utility.

 For example, if you want to remove the new search box and replace it with the classic search icon, you’ll need to run the **ViVetool /disable /id:39263329** command using the ViVeTool command-line utility.

 The **feature ID id:39263329** in the above command tells the ViVeTool and the subsequent API request which feature to toggle on your Windows computer.

 You can source the feature ID from the internet or by using the ViVeTool GUI version. That said, the feature ID description in the GUI version is mostly cryptic, so tread carefully. Once you have the feature ID, you can use the ViVeTool command-line or GUI version to enable or disable features on your Windows computer.

## Is ViVeTool Safe to Use?

 ViVeTool doesn’t add new features on its own. It simply toggles the existing features to enable or disable them for your Windows system. However, since these features are experimental by nature, activating them may sometimes cause some issues.

 If you want to use ViVeTool on your daily driver, go through the [Windows data backup and recovery options](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) and proceed with the steps below. Ideally, use a virtual machine to test new features, and if found to be stable, apply them to your daily driver.

## How to Download and Install the ViVeTool GUI Version

 ViVeTool GUI is the forked version of the ViVeTool command-line utility. It is less complicated to use and removes the hassle of executing commands or remembering them in the first place. The GUI version is available as an executable installer or portable version. Here’s how to install and use ViVeTool GUI on Windows.

 To download the ViVeTool GUI version:

1. Go to the [ViVeTool GUI page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub.  
![download vivetool gui zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-gui-zip.jpg)
2. Download the latest version of the **Setup.exe file** available. You can also download a portable version if you prefer.
3. Run the setup file and keep the default settings. Follow the on-screen instructions to install the app.

## How to Install Unreleased Features Using ViVeTool on Windows

 Now that the app is installed, you can use it to find and install unreleased features on your Windows computer. Here’s how to do it:

1. Launch the ViVeTool using a desktop shortcut or from the **Start** menu.  
![vivetool gui select build](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-gui-select-build.jpg)
2. Click the **Select Build** drop-down in the top-left corner and select your **Windows build.** You can [check Windows 11 build and version](https://www.makeuseof.com/check-build-and-version-windows-11/) using the **Settings app**. ViVeTool GUI will now start looking for all the available features for the selected build. This may take a few minutes, so wait till the list is populated.
3. ViVeTool GUI categorizes the available features into different categories, including **Always Disabled**, **Always Enabled**, **Disabled by Default**, **Enabled by Default**, and **Modifiable**. You can expand the category and select the feature to install.
4. Next, select the feature you want to enable or disable. Alternatively, type the feature name in the search bar to find a specific feature.  
![activate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/activate-feature-vivetool-gui.jpg)
5. Click the **Perform Action** drop-down select **Activate** to enable the feature. Wait for the success message and click **Close**.  
![revert to default values feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/revert-to-default-values-feature-vivetool-gui.jpg)
6. If the changes are not immediately visible, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) to apply the changes. In some instances, you may need to restart your PC to make the changes.

 To revert the changes or disable a feature, you can use the Deactivate Feature option available in ViVeTool. Here's how to disable a feature using ViVeTool:

![deactivate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/deactivate-feature-vivetool-gui.jpg)

1. Launch **ViVeTool GUI.**
2. Search and select the feature you want to disable.
3. Click the **Perform Action** drop-down in the top-right corner.
4. Select **Deactivate Feature** and click **OK**.

 Alternatively, you can also revert the feature to its default state. To do this, select the modified feature, click on **Perform Action,** and select **Revert Feature to Default Values.** The changes will take effect when you restart your computer next time.

 Here are a few new and lesser-known Windows features that you can enable using ViVeTool before anyone else:

* [Enable Windows Copilot Using ViVeTool](https://www.makeuseof.com/enable-windows-copilot-vivetool/)
* [Enable the Home Section in the Settings App in Windows 11](https://www.makeuseof.com/enable-home-section-settings-app-windows-11/)
* [Enable Instant Search Results in File Explorer in Windows 11](https://www.makeuseof.com/instant-search-results-file-explorer-windows-11/)
* [Enable the Enhanced Taskbar in Windows 11](https://www.makeuseof.com/enhanced-taskbar-settings-windows-11/)
* [Enable the Volume Mixer in the Action Center in Windows 11](https://www.makeuseof.com/volume-mixer-action-center-windows/)

## How to Use the ViVeTool Command-Line Version

 The original version of ViVeTool is a command-line utility. While it offers similar functionality as the GUI version, it is an efficient way to enable and disable Windows features quickly. Here’s how to do it:

1. Go to the [ViVeTool page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub. This lists all the releases of ViVeTools since its inception.  
![download vivetool command line zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-command-line-zip.jpg)
2. Locate the latest version of ViVeTools. As of writing this, **Version 1.6.2** is the latest stable release available, and version 1.7 is available as a pre-release.
3. Click on **Assets** to view the download options.
4. Next, click the **ViVeTool.GUI.1.6.2.0.Portable.zip** file (version may change with the new releases) to download the latest version to your local drive.  
![vivetool zip extract folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-zip-extract-folder.jpg)
5. Right-click on the **Zip** file and select **Extract** **all**. Select a destination and click **Extract**. Take note of the extraction folder.

1. Next, press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![command prompt vivetool change directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-change-directory.jpg)
3. In the Command Prompt, change the directory to ViVeTool extracted folder. So, type the following command and press **Enter** to change the directory:  
`cd /d [ViVeToolFolderPath]`
4. For example, if I have the ViVeTool folder saved in C:\\Users\\username\\Downloads\\ViVeTool-v0.3.2, then the full command will look this:  
`cd /d C:\Users\username\Downloads\ViVeTool-v0.3.2`
5. Next, to enable a feature, use the following command and press Enter:  
`ViVeTool.exe /enable /id:featureID`

1. In the above command, replace featureID with the feature ID you want to enable.  
![command prompt vivetool enable feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-enable-feature.jpg)
2. For example, to enable the tab feature in File Explorer, the feature ID is id:37634385\. So, the full command will look like this:  
`ViVeTool.exe /enable /id:37634385`
3. If you want to disable a feature, then the command will look something like this:  
`ViVeTool.exe /disable /id:featureID`
4. Once the command is executed, type exit and press Enter to close the Command Prompt.
5. Restart your PC to apply the changes. After the PC restarts, the changes should be visible.

## Why Does Enabling a Feature in ViVeTool Not Do Anything?

 You may not be able to enable all the features present in ViVeTool. Almost all the hidden features are OS build-dependent. This means if you enable a feature using ViVeTool, but the changes don’t take effect, it is likely because the feature is not supported by the Windows OS build version you are running.

 In other instances, it may be due to the feature state being set to **Always Disabled** or **Enabled** during compilation. In this instance, even if ViVeTool successfully processes your request, you are unlikely to see any real changes, as the feature is hard-coded to remain on or off.

## ViVeTool's Supported Commands

 Apart from the /enable and /disable command, ViVeTools support a bunch of other commands to reset the custom configuration for specific or all features, update ViVeTool, and export and import custom feature configuration.

| ViVeTool Command | Action                                                       |
| ---------------- | ------------------------------------------------------------ |
| /enable          | Enable a feature                                             |
| /disable         | Disable a feature                                            |
| /query           | Find a list of all the existing features configuration       |
| /reset           | To reset a custom configuration for a specific feature       |
| /resetall        | To reset a custom configuration for all the features         |
| /addsubs         | To add a feature usage subscription                          |
| /delsub          | To remove a feature usage subscription                       |
| /export          | To export custom feature configuration                       |
| /import          | To import custom feature configuration                       |
| /fixlkg          | Fix the current ‘Last Known Good’ rollback system corruption |
| /appupdate       | Look for new ViVeTool updates                                |
| /notifyusage     | Shows a feature notification                                 |

## ViVeTool Brings Hidden Windows Experimental Features to Everyone

 ViVeTool makes it easy to find and test new experimental features before they are released to the public. Whether you use the GUI or command-line version, it lets you easily enable and disable some exciting and annoying features.

 That said, many of these hidden features may be buggy and cause system malfunction. So, keep your system backup handy before you tinker with ViVeTool.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-what-every-youtuber-should-know-about-live-thumbnails/"><u>[New] 2024 Approved  What Every YouTuber Should Know About Live Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-perfect-your-mac-how-to-record-desktop-activity/"><u>[Updated] 2024 Approved  Perfect Your Mac  How to Record Desktop Activity</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-elite-hd-video-preservation-devices/"><u>In 2024, Elite HD Video Preservation Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-the-art-of-digital-expression/"><u>Windows 11 Makeover: The Art of Digital Expression</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-in-calendar-design-a-windows-outlook-method/"><u>Unleashing Creativity in Calendar Design - A Windows Outlook Method</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-hidden-desktop-icons-on-the-latest-windows/"><u>Revive Hidden Desktop Icons on the Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-connection-issues-dissolving-ea-errors/"><u>Winning Over Connection Issues: Dissolving EA Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-superiority-persistent-high-privilege-terminal/"><u>Uncomplicated Superiority: Persistent High-Privilege Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-installer-package-fails-on-windows-11/"><u>Troubleshooting Installer Package Fails on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/six-secrets-to-spinning-pictures-in-w11-os/"><u>Six Secrets to Spinning Pictures in W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-streamlining-your-watch-time-on-instagram-mobiledesktop/"><u>[New] In 2024, Streamlining Your Watch Time on Instagram (Mobile/Desktop)</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-steam-offline-status-via-win-tricks/"><u>Re-Establish Steam Offline Status via Win Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-non-responsive-function-keys-in-windows-11/"><u>Solve: Non-Responsive Function Keys in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-futuristic-feature-unveiling-mac-via-applewatch/"><u>2024 Approved  Futuristic Feature  Unveiling Mac via AppleWatch</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-searches-using-everythingapp/"><u>Streamline Windows Searches Using EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-microsoft-teams-freeze-in-ws11ws10/"><u>Strategies to Prevent Microsoft Teams Freeze in WS11/WS10</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-video-editing-mastery-35-essential-tools-for-all-devices-and-operating-systems/"><u>2024 Approved Video Editing Mastery 35 Essential Tools for All Devices and Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/applications-and-their-unique-run-notations-explored/"><u>Applications & Their Unique Run Notations Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-cost-effective-windows-11-keys/"><u>Unveiling Cost-Effective Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-win-error-due-to-missing-mfc71udll/"><u>Troubleshooting Absence: Win Error Due to Missing Mfc71u.dll</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-remove-option-for-pin-access-control/"><u>Reviving Disabled 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-saving-paradox-modern-standbys-dilemni/"><u>Windows' Power-Saving Paradox: Modern Standby's Dilemni</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-youtube-buffering-busted-stream-uninterrupted-new-techniques/"><u>[New] 2024 Approved  YouTube Buffering Busted - Stream Uninterrupted (New Techniques)</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-how-to-install-and-uninstall-audacity-on-ubuntu/"><u>2024 Approved How to Install and Uninstall Audacity on Ubuntu</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-optimal-functionality-of-add-ons-in-windows-os/"><u>Strategies to Ensure Optimal Functionality of Add-Ons in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-pixels-for-every-window-11-display/"><u>Perfect Pixels for Every Window 11 Display</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-print-service-stopped-issue-on-windows-pc/"><u>Addressing Print Service Stopped Issue on Windows PC</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-audacity-users-guide-to-immediate-sound-suppression/"><u>Updated In 2024, Audacity Users Guide to Immediate Sound Suppression</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/purging-protection-logs-on-windows-1011-with-ease/"><u>Purging Protection Logs on Windows 10/11 with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-wi-fi-links-top-strategies-to-regain-internet-connection-on-windows-10/"><u>Reviving Lost Wi-Fi Links: Top Strategies to Regain Internet Connection on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-motorola-defy-2-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Motorola Defy 2 | Dr.fone</u></a></li>
</ul></div>
