---
title: Mastering App Packages with Winget on Win11 - Tips and Tricks
date: 2024-09-05T02:08:03.395Z
updated: 2024-09-06T02:08:03.395Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering App Packages with Winget on Win11 - Tips and Tricks
excerpt: This Article Describes Mastering App Packages with Winget on Win11 - Tips and Tricks
keywords: Winget Win11 Pro,Windows Package Tool,App Dependency Management,Winget Installation Guide,PowerShell Package Scripts,Win11 Software Configuration,Automate Package Updates
thumbnail: https://thmb.techidaily.com/f858bf5f9e0327b42a985f450fae85190a7aad26feb7ee5b800247a93a2f3bb0.png
---

## Mastering App Packages with Winget on Win11 - Tips and Tricks

 Winget is a command-line tool that can download and install app packages from MS Store and the apps available in its repository. Windows users yearned for a dedicated package manager built into the OS until Microsoft decided to give them one. It is better than using an additional package manager but not all users love the terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

## What Is WingetUI, and How Is It Different From Winget?

 WingetUI is a GUI implementation of the [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/)tool that makes it super easy to manage app packages. It also supports Scoop and Chocolatey and can act as GUI forefront for all these three tools. If you'd like to know more about those, check out our [comparison between Chocolatey and Windows Package Manager](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/), and [how to install Scoop on Windows](https://www.makeuseof.com/windows-install-scoop/).

 Currently, WingetUI offers more than 4700 packages for Winget. If you combine the package list for all three package managers (including Chocolatey and [Scoop](https://www.makeuseof.com/windows-install-scoop/)), the numbers stand at a staggering 14000\.

 So, you can directly access 14000 packages without leaving the app and will have to rarely search the web. WingetUI can help you to manage all the installed packages, discover and install new ones, [batch install multiple packages](https://www.makeuseof.com/export-import-apps-winget-in-windows-11/), export or import package list, search for packages inside the app, and more.

 The fun doesn’t stop there. You can switch to dark mode in the app, and it even notifies you about the app updates whenever you launch the app and can even auto-update them. Furthermore, you can even view the package details, and its commands, and can share the packages with your friends.

## How to Download and Install WingetUI on Windows11

 WingetUI is available on GitHub and also has a dedicated website to keep you updated about the new features. However, you will find the download links on [GitHub](https://github.com/marticliment/WingetUI/releases/latest), Softpedia, and Uptodown only. Download the installer file from any of these hosts and then install it on your PC. Make note that WingetUI only works with Windows 10 and Windows 11 (64-bit versions only).

 After the installation completes, the app will ask you to select the package managers you want to use. Select the **Enable Winget** option for now, and click on the **Apply and Start WingetUI** button.

![Install WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-wingetui.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Manage App Packages Using WingetUI on Windows 11

 WingetUI divides the whole app into three sections: Discover Packages, Software Updates, and Installed packages. You can view all the available packages in the app using the Discover Packages section, while the Software Updates section list all the app that have a new version available. Lastly, the Installed Packages section allows you to manage the app packages on your PC.

 Here are the following things you can do using WingetUI:

### 1\. Browse List

 To browse the app list, click on the **Discover Packages** button on the top. WingetUI will list all the available packages with the source Winget. You will also see a counter indicating the total number of apps listed in the repository.

 Click on the search bar and type the name of the app package that you want to install on your PC. It will list all the available versions of the app package along with its package ID and version.

![Browse List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/browse-list-in-wingetui.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896560/19272" target="_top" id="1896560">
  <img src="//a.impactradius-go.com/display-ad/19272-1896560" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896560/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Install a Package

 To install a package, you will have to use the Discover Package tab:

1. After searching and locating the package, click on it to select it.
2. Then, right-click on it to open the context menu. Before starting the installation, you must configure the installation.
3. Select the **Package details** option from the context menu.  
![Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui.jpg)
4. Check the **source** of the package. Also, check the **image gallery** to get an idea of the app’s UI.
5. Move down to the **Installation options**. Keep the **Skip hash check** and **Interactive installation** unchecked. If you enable the interactive installation, you will have to manually perform the installation which can take longer.

1. Some apps cannot install on your PC without administrator rights. So, select the **Run as admin** checkbox.  
![Install a Package in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-2.jpg)
2. You can also select a particular version of the app you are trying to install. Expand the **Version to install** dropdown list. You can select any version from here. Keep the **Ignore future updates for this package** option untouched.  
![Install a Package in WingetUI 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-3.jpg)
3. Next, you can pick the **package architecture**: x64, x86, or arm65, depending upon your OS and CPU architecture.
4. Lastly, pick the **Scope** of the package installation. If you want to do a machine-wide install, pick the **local machine** option. Or pick the **Current user** if you want to install the app only for one user profile.  
![Install a Package in WingetUI 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-4.jpg)
5. Click on the **Install** button. UAC will pop up. Click on the **Yes** button.  
![Install a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-5.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You will see the installation status at the button of the WingetUI window. Windows will produce a notification when the installation completes.

### 2\. Uninstall a Package

 Repeat the following steps to uninstall a package using WingetUI:

1. Switch to the **Installed Packages** tab. Right-click on the package you want to uninstall.
2. Select the **Uninstall as administrator** option.  
![unInstall a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-a-package-in-wingetui-5.jpg)
3. UAC will pop up. Click on the **Yes** button.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. WingetUI will remove the installed package.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030373/7443" target="_top" id="2030373">
  <img src="//a.impactradius-go.com/display-ad/7443-2030373" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030373/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Batch Install or Uninstall Packages

 Batch installation and uninstallation are a breeze with WingetUI. Here’s how to do it:

1. Individually select each package you want to install.
2. Then click on the **Install the selected packages** button on the top.  
![batch Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-install-a-package-in-wingetui.jpg)
3. WingetUI will install these apps one by one.

 To batch uninstall packages, repeat the following steps:

1. Switch to the **Installed Packages** tab. Then, click and select all the packages you want to remove from your PC.
2. Click on the **Uninstall selected packages** button to remove the selected packages one by one.  
![batch unInstall Packages in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-uninstall-packages-in-wingetui.jpg)

### 4\. Import Export Packages List

 You can create a custom package export list and store them in a JSON or Txt file. Here’s how:

1. Firstly, select all the packages you want to export either from the **Discover Packages** section or the **Installed Packages** section.
2. Then, click on the **Export selected packages to a file** option.  
![Export Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui.jpg)
3. Enter a **name** for the export file and save it to any location on your PC.  
![Export Packages List in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui-2.jpg)
4. You can later import this file to another PC or even your PC using Winget or Winget UI.
<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Repeat the following steps to import a Winget JSON file in WingetUI:

1. Switch to the **Discover Packages** section in the app.
2. Click on the **Import packages from a file** option.
3. **Browse** your PC for the Winget import file and select it. Click on the **Open** button.  
![import Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/import-packages-list-in-wingetui.jpg)
4. WingetUI will automatically start installing all the packages listed in the import file.
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Check Software Updates

 Switch to the **Software Updates** section. WingetUI will list all the packages which have an update available. To update a single app, right-click on it and select the **Update as administrator** option.

![Check Software Updates in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui.jpg)

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to update all packages at once, click on the **tick mark** icon to select all the packages. Then, click on the **Update selected packages** button.

![Check Software Updates in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## No More Terminal Woes

 WingetUi makes it easy for the average Joe to manage app packages on a Windows PC. There is a similar web-based GUI package manager called Winstall for batch-installing apps, but it only generates codes for it. You will have to manually run the commands in the Terminal. So, you can use WingetUI instead if you want zero interaction with Windows Terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-high-def-mastery-the-leading-blu-ray-devs/"><u>[Updated] 2024 Approved  High-Def Mastery  The Leading Blu-Ray Devs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-breaking-barriers-next-level-strategies-for-fb-video-success/"><u>[Updated] Breaking Barriers  Next-Level Strategies for FB Video Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-future-of-games-analyzing-htc-vive-vs-oculus-rift-and-ps-vr/"><u>[Updated] Future of Games  Analyzing HTC Vive vs Oculus Rift & PS VR</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-best-3ip-apps-to-record-clear-speech-on-ipads/"><u>[Updated] In 2024, Best 3iP Apps to Record Clear Speech on iPads</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-novice-to-vlogger-professional-video-making-on-mobile-devices/"><u>2024 Approved  From Novice to Vlogger  Professional Video Making on Mobile Devices</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-preventing-htc-vive-disorientation-and-nausea/"><u>2024 Approved  Preventing HTC Vive Disorientation and Nausea</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-unlocking-google-meets-whiteboard-capabilities-on-diverse-tech-ecosystems/"><u>2024 Approved  Unlocking Google Meet's Whiteboard Capabilities on Diverse Tech Ecosystems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbots-on-guard-protecting-privacy-against-3-main-risks/"><u>Chatbots on Guard: Protecting Privacy Against 3 Main Risks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevating-your-audacity-sound-capture-game/"><u>Elevating Your Audacity Sound Capture Game</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-power-settings-on-windows-desktops/"><u>Exploring Power Settings on Windows Desktops</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-excellence-in-rayman-legends-a-critics-perspective-on-2d-platforming/"><u>Exploring the Excellence in Rayman Legends: A Critic's Perspective on 2D Platforming</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oneplus-ace-2v-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset OnePlus Ace 2V If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-save-and-play-gifs-on-an-iphone/"><u>How to Save and Play GIFs on An iPhone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-methods-for-subtle-volume-reduction-in-fl-studio/"><u>In 2024, Methods for Subtle Volume Reduction in FL Studio</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tomorrows-evaluation-creative-pathways/"><u>In 2024, Tomorrow’s Evaluation  Creative Pathways</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-unbind-your-onedrive-and-microsoft-profile-on-windows/"><u>Learn to Unbind Your OneDrive & Microsoft Profile on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-antivirus-softwares-ram-consumption/"><u>Managing Antivirus Software’s RAM Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-migration-to-your-new-windows-11-laptop/"><u>Mastering App Migration to Your New Windows 11 Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-canary-vulnerability-alerts/"><u>Mastering Windows’ Canary Vulnerability Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blocked-app-warning-on-windows-os/"><u>Overcoming Blocked App Warning on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pink-screens-with-ease-and-speed/"><u>Overcoming Windows Pink Screens with Ease and Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-after-connection-failures-in-windows/"><u>Reconnecting to EA Servers After Connection Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-control-over-windows-11s-dropped-items/"><u>Regain Control Over Windows 11'S Dropped Items</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-empty-folder-message-on-windows-11/"><u>Remedying the Empty Folder Message on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitation-guide-bring-back-function-of-wsreset-on-pcs/"><u>Resuscitation Guide: Bring Back Function of WSReset on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-stalled-access-on-credential-store/"><u>Revive Stalled Access on Credential Store</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-tasks-with-your-default-windows-terminal/"><u>Simplify Tasks With Your Default Windows Terminal</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-steps-to-prevent-blender-from-crashing-on-windowsmac-os-expert-tips-included/"><u>Solution Steps to Prevent Blender From Crashing on Windows/Mac OS - Expert Tips Included</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-package-unregistered-photo-problems-in-windows-os/"><u>Solving 'Package Unregistered' Photo Problems in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-zerodxgierordevicelatencyerror-for-win11-users/"><u>Solving ZeroDXGIErorDeviceLatencyError for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-error-0x0000011b-on-windows-11/"><u>Steps to Resolve Error 0X0000011B on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-tap-into-disk-access-4-ways-to-engage-with-disk-editor-settings-on-win11/"><u>Swiftly Tap Into Disk Access: 4 Ways to Engage with Disk Editor Settings on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-system-wake-up-shortening-boot-menu-hesitation-period/"><u>Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-reactivating-explore-in-11os/"><u>The Ultimate Guide to Reactivating Explore in 11OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-walkthrough-for-changing-cpu-drivers-in-microsoft-windows/"><u>The Ultimate Walkthrough for Changing CPU Drivers in Microsoft Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-green-screen-apps-for-mac-a-comprehensive-guide/"><u>Top Green Screen Apps for Mac A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-functional-thx-audio/"><u>Troubleshooting Windows for Functional THX Audio</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722195589882-unleash-the-power-of-artificial-intelligence-in-your-presentation-game-meet-the-top-7-applications/"><u>Unleash the Power of Artificial Intelligence in Your Presentation Game - Meet the Top 7 Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-microsoft-store-error-code-0x80073cf3/"><u>Unwrapping the Mystery: Microsoft Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-restricted-interface-an-overview/"><u>Windows 11'S Restricted Interface: An Overview</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>