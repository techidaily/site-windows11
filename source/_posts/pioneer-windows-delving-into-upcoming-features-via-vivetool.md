---
title: "Pioneer Windows: Delving Into Upcoming Features via ViVeTool"
date: 2024-09-14T19:32:56.360Z
updated: 2024-09-15T17:24:59.808Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pioneer Windows: Delving Into Upcoming Features via ViVeTool"
excerpt: "This Article Describes Pioneer Windows: Delving Into Upcoming Features via ViVeTool"
keywords: Pioneer Windows New,Windows Feature Update,ViVeTool Insight,Window's Future Tech,Upcoming Windows Traits,ViVeAnalysis Tools,Innovating Windows Design
thumbnail: https://thmb.techidaily.com/6c8487e0b404251fb12aeaebde28154ddd618ecb4b5d51b0cd4522eee48c4e1f.jpg
---

## Pioneer Windows: Delving Into Upcoming Features via ViVeTool

 ViVeTool is an open-source command-line tool to enable experimental but hidden features on your Windows computer. It is also available in a GUI version, which makes it much easier to enable or disable certain features on Windows.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## ViVeTool Brings Hidden Windows Experimental Features to Everyone

 ViVeTool makes it easy to find and test new experimental features before they are released to the public. Whether you use the GUI or command-line version, it lets you easily enable and disable some exciting and annoying features.

 That said, many of these hidden features may be buggy and cause system malfunction. So, keep your system backup handy before you tinker with ViVeTool.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-seamless-visuals-on-screen-zooming-into-clarity/"><u>[New] 2024 Approved Seamless Visuals on Screen Zooming Into Clarity</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Samsung Galaxy XCover 6 Pro Tactical Edition to iPhone | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/fcpx-visual-effects-freeze-frames-slow-motion-and-advanced-editing/"><u>FCPX Visual Effects Freeze Frames, Slow Motion, and Advanced Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-device-error-0xa00f425d-in-camera-app/"><u>Fixing Windows Device Error 0xA00F425D in Camera App</u></a></li>
<li><a href="https://driver-error.techidaily.com/geforce-experience-game-cannot-be-optimized-solved/"><u>GeForce Experience Game Cannot Be Optimized [Solved]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-infinix-note-30-pro-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Infinix Note 30 Pro to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-steam-disconnection-challenges-on-windows/"><u>Navigating Steam Disconnection Challenges on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/optimal-phone-replacement-frequency/"><u>Optimal Phone Replacement Frequency</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-and-restore-your-windows-display-preferences/"><u>Revive and Restore Your Windows Display Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-homes-enabling-efficient-user-handling/"><u>Windows 11/10 Homes: Enabling Efficient User Handling</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    