---
title: "Mastering App Management in Windows: The Power of Winget"
date: 2024-06-25T12:06:41.289Z
updated: 2024-06-26T12:06:41.289Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering App Management in Windows: The Power of Winget"
excerpt: "This Article Describes Mastering App Management in Windows: The Power of Winget"
keywords: WinAppManagementSkills,WingetPowerWindows,AppInstallationWinget,EfficientAppSetup,WindowSDKUtility,PowerfulAppIntegration,WingetOptimizationTips
thumbnail: https://thmb.techidaily.com/66f3cf36e141a02ee3ef4f8fc90997bfb9adc390279a16b539b7e76e0dc798e2.jpg
---

## Mastering App Management in Windows: The Power of Winget

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

## How to Manage App Packages Using WingetUI on Windows 11

 WingetUI divides the whole app into three sections: Discover Packages, Software Updates, and Installed packages. You can view all the available packages in the app using the Discover Packages section, while the Software Updates section list all the app that have a new version available. Lastly, the Installed Packages section allows you to manage the app packages on your PC.

 Here are the following things you can do using WingetUI:

### 1\. Browse List

 To browse the app list, click on the **Discover Packages** button on the top. WingetUI will list all the available packages with the source Winget. You will also see a counter indicating the total number of apps listed in the repository.

 Click on the search bar and type the name of the app package that you want to install on your PC. It will list all the available versions of the app package along with its package ID and version.

![Browse List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/browse-list-in-wingetui.jpg)

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

 You will see the installation status at the button of the WingetUI window. Windows will produce a notification when the installation completes.

### 2\. Uninstall a Package

 Repeat the following steps to uninstall a package using WingetUI:

1. Switch to the **Installed Packages** tab. Right-click on the package you want to uninstall.
2. Select the **Uninstall as administrator** option.  
![unInstall a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-a-package-in-wingetui-5.jpg)
3. UAC will pop up. Click on the **Yes** button.
4. WingetUI will remove the installed package.

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

 Repeat the following steps to import a Winget JSON file in WingetUI:

1. Switch to the **Discover Packages** section in the app.
2. Click on the **Import packages from a file** option.
3. **Browse** your PC for the Winget import file and select it. Click on the **Open** button.  
![import Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/import-packages-list-in-wingetui.jpg)
4. WingetUI will automatically start installing all the packages listed in the import file.

### 5\. Check Software Updates

 Switch to the **Software Updates** section. WingetUI will list all the packages which have an update available. To update a single app, right-click on it and select the **Update as administrator** option.

![Check Software Updates in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui.jpg)

 If you want to update all packages at once, click on the **tick mark** icon to select all the packages. Then, click on the **Update selected packages** button.

![Check Software Updates in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui-2.jpg)

## No More Terminal Woes

 WingetUi makes it easy for the average Joe to manage app packages on a Windows PC. There is a similar web-based GUI package manager called Winstall for batch-installing apps, but it only generates codes for it. You will have to manually run the commands in the Terminal. So, you can use WingetUI instead if you want zero interaction with Windows Terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-fn-key-brighness-in-windows-11/"><u>Steps to Restore Fn Key Brighness in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-malwarebytes-service-connections-in-win-oses/"><u>Re-Establishing Malwarebytes' Service Connections in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-run-as-command-issues/"><u>Strategies to Overcome 'Run As' Command Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-your-search-for-the-best-gif-creator-tools-ends-here/"><u>New In 2024, Your Search for the Best GIF Creator Tools Ends Here</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-screen-capture-connoisseurs-your-guide-to-preserving-twitvid-media/"><u>[New] 2024 Approved  Screen Capture Connoisseurs  Your Guide to Preserving TwitVid Media</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-top-10-ai-talking-avatars-revolutionizing-communication-for-2024/"><u>New Top 10 AI-Talking Avatars Revolutionizing Communication for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-capturing-contentment-top-streaming-techniques/"><u>[Updated] In 2024, Capturing Contentment  Top Streaming Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-ultimate-screen-recording-hack-for-instagram-stories/"><u>[New] The Ultimate Screen Recording Hack for Instagram Stories</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-ways-to-lock-apps-on-apple-iphone-6s-and-ipad-securely-drfone-by-drfone-ios/"><u>7 Ways to Lock Apps on Apple iPhone 6s and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-beginning-your-first-fb-giveaway-announcement/"><u>[Updated] Beginning Your First FB Giveaway Announcement</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-fbm-transcripts-how-to-get-and-use-complete-records/"><u>[Updated] In 2024, FBM Transcripts  How to Get and Use Complete Records</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-want-to-take-your-editing-creativity-to-the-next-level-by-designing-top-class-professional-quality-slideshows-in-aquasoft-rest-assured-you/"><u>New 2024 Approved Want to Take Your Editing Creativity to the Next Level by Designing Top-Class, Professional-Quality Slideshows in Aquasoft? Rest Assured, You Have Landed at the Right Place</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>