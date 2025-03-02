---
title: "Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles"
date: 2025-02-23T13:07:22.585Z
updated: 2025-03-02T04:09:36.170Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles"
excerpt: "This Article Describes Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles"
keywords: MSI Bundles Install,Windows MSI Package,Seamless Application Bundle,Running MSI Installer,MSI Bundle Setup Guide,AppxBundle Integration,AppXBundle Deployment Methods
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles

 The new Microsoft Store on Windows 11 works great for the most part. But, for the times it doesn’t, Windows lets you sideload Microsoft Store apps in appx, appxBundle, msixbundle app files on your computer.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 You can download the appx or msix package from the app developer’s website, GitHub, or directly from the Microsoft Store server using third-party utilities. Here we show how to download appx/appxbundle and msixbundle package files from Microsoft Store and install them on your Windows computer.

## 1\. How to Download Appx/AppxBundle Files Using Adguard

![adguard msixbundle download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adguard-msixbundle-download.jpg)

 Adguard is a third-party web service and an online link generator for Microsoft Store. It makes it easy to download appx and appxbundle files from the Microsoft Store for sideloading them on your Windows computer.

To download appx, appxbundle or msixbundle using Adguard:

1. Go to [Microsoft Store](https://apps.microsoft.com/store/apps) on your browser, search, and open the app you want to download.
2. Copy the app URL, including the product ID, from the address bar. For example, the app URL for the Xbox app on Microsoft Store will look like this:  
`https://apps.microsoft.com/store/detail/xbox/9MV0B5HZVK9Z`
3. Next, go to the [Adguard page](https://store.rg-adguard.net/) and paste the app URL.
4. On the right side, click the**RP** drop-down and select**Retail** .
5. Click the**Check mark** button to generate a direct download link. It will populate the page with msixbundle, appx or appxbundle, and other associated files.
6. You only need to download the full app package. The rest are app dependencies that you don’t need to download in most cases. For example, in this instance, we only need to download**msixbundle** , which is also the largest file in the list.
7. Make sure to check the architecture compatibility (**x64, x86, Arm**) for the files depending on your system architecture.
8. Next, click on the msixbudle link to download. Microsoft Edge may sometimes block the download as not secure. You can use alternative browsers like Google Chrome and Firefox to compelete the download.

## 2\. Generate Microsoft Store Apps Direct Download Links Using Fiddler

 Fiddler Classic is a network tracking and monitoring tool to log HTTP(s) traffic from web browsers and installed apps. You can use this app to track Microsoft Store network when downloading an app to your computer. Then use the URL as a direct download link to download appx, msixbundle, and appxbundle files using any web browser.

To generate a Microsoft Store app downloading link using Fiddler:

1. Download and install the [Fidler Classic app](https://www.telerik.com/download/fiddler) . You’ll need to enter your email and territory to download the app.
2. Open**Fiddler** , and click the**WinConfig** button in the top left corner. Click**Yes** if prompted by User Account Control.  
![Fiddler_WinConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler_winconfig.jpg)
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  
![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

1. Next, launch**Microsoft Store,** search for the app you want to download, and click**Install** . Wait for the app to download and install completely. Fiddler will start capturing the traffic as the necessary files for the app download and install.
2. Once the download is complete, open the**Fiddler** app and press**Ctrl + F** to open**Find** .
3. Type**appx** in the**Find** dialog. Leave the rest options as default and click**Find Sessions** . It will scan through the recently captured Microsoft Store traffic and highlight the matching entries in yellow.  
![fiddler find session](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-find-session.jpg)
4. If no entries are highlighted, open**Find (Ctrl+F)** and type**msixbundle, appx** or**appxbundle** in the**Find** field, and click on**Find Sessions** .  
![Fiddler copy just url](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-copy-just-url.jpg)
5. Right-click on any entry highlighted in yellow and select**Copy > Just URL.**
6. Open**Google Chrome** or**Firefox** and paste the copied URL in the address bar. Press**Enter** and click**Save** to download the file. On Microsoft Edge, you may face a connection is not secure error. If so, switch to a different browser to complete the download.

 To install the downloaded appx, appxbundle, or msixbundle file, you can use PowerShell or the App Installer.

## How to Install Appx, Appxbundle and Msixbundle Apps

 In an ideal situation, you can double-click on the app file package to install it on your Windows computer. However, if that does not work, you can sideload the apps using PowerShell and the official App Installer. Here are the three ways to install the appxbundle and msixbundle file packages on Windows 10 and 11.

### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File

![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)

 You can install some appx, appxbundle, and msixbundle files like you would do with any .exe file. Follow these steps to sideload and install Universal Windows Platform apps.

1. Locate the saved app package in the**Downloads** folder.
2. Next, double-click on the file to open the installation wizard and click on the**Install** button to install the software.

 Unfortunately, this installation method does not work always. You are likely to run into errors like [this app package is not support installation](https://www.makeuseof.com/app-package-not-supported-installation-app-installer/) . What you can do instead is try to install the app using the App Installer app or PowerShell. You can use PowerShell to install apps not signed by Microsoft Store.

### 2\. Install Appx, Appxbundle, and Msixbundle using App Installer

![microsoft app installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-app-installer.jpg)

 Microsoft offers an official App Installer to sideload Windows 10 apps. However, this app installer also works on Windows 11\. If you encounter an error when sideloading apps using the convention double-click method, the App Installer will do the trick.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before installing App Installer. Once installed, you may not be able to uninstall the app. And it can also fiddle with Windows PowerShell’s ability to sideload apps.

To install App Installer:

1. Launch**Microsoft Store** and search for the app installer.
2. Click on**App** **Installer** from the search results. The description reads the app lets you sideload Windows 10 apps.
3. Click on Install and wait for it to complete the process.
4. Once installed, click on the appx, appxbundle, or msixbundle file to open it in**App Installer.**
5. Click**Install** and wait for the app installation to finish.

### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)

 You can use Windows PowerShell to sideload Microsoft Store app on Windows. This is an efficient way to sideload apps on multiple computers or when you get an error while running the msixbundle or other package files.

To install appx, msixbudnle, and appxbundle apps using PowerShell:

1. Press the**Win** key and**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator.**
3. Next, type the following command and press**Enter** to install the app:  
`Add-AppxPackage -Path $AppFilePath`
4. In the above command, replace AppFilePath with the appx, msixbundle, or appxbundle file path. To get the file path, right-click on the file and select**Copy as path.**
5. For example, if you want to install msixbundle for Files Apps, the full command will be something like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
6. PowerShell will show a progress bar to indicate the installation. Once done, you can launch the app from the Start menu.

 In addition, if you want to install a non-Microsoft Store app file package, you may also need to enable Developer Mode to install UWP apps from third-party sources.

To enable Developer Mode on Windows 11

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the**Privacy & Security** tab in the left pane,
3. Click on**For Developers** and then toggle the switch for**Developer Mode.**

## Download and Install Appx, Appxbundle, and Msixbundle from Microsoft Store on Windows

 Thanks to the built-in sideload support on Windows, you can easily install Microsoft Store and non-store apps on your computer. Adguard and Fiddler handle the important aspect of allowing to download app package files for sideload.

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
<li><a href="https://youtube-data.techidaily.com/024-approved-digital-arcade-over-a-hundred-game-channels/"><u>[New] 2024 Approved Digital Arcade Over a Hundred Game Channels</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-breakdown-of-cloud-storage-pricing-expert-analysis-and-top-deals/"><u>[New] Breakdown of Cloud Storage Pricing Expert Analysis & Top Deals</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-deciphering-genuine-connections-in-social-networks-for-2024/"><u>[New] Deciphering Genuine Connections in Social Networks for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/kyrocket-viewer-count-efficient-templated-content-creation-in-youtube-descs/"><u>[New] Skyrocket Viewer Count Efficient Templated Content Creation in YouTube Descs</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-charting-the-course-for-youtube-music-uploads/"><u>[Updated] In 2024, Charting the Course for YouTube Music Uploads</u></a></li>
<li><a href="https://win-blog.techidaily.com/editeurs-de-gameplay-en-avant-garde-pour-les-joueurs-de-2024/"><u>Éditeurs De Gameplay en Avant-Garde Pour Les Joueurs De 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-accessdeactivate-bing-chat-in-windows-search-bar/"><u>How To Quickly Access/Deactivate Bing Chat in Windows Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-and-reinstate-blocked-windows-program/"><u>How to Reset and Reinstate Blocked Windows Program</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-xiaomi-redmi-note-13-pro-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Xiaomi Redmi Note 13 Pro 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-and-upgrade-the-best-6-android-apps-on-windows-11/"><u>Integrate and Upgrade: The Best 6 Android Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-win-11s-capabilities-for-seamless-application-switch/"><u>Leveraging Win 11'S Capabilities for Seamless Application Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-organization-notes-on-w11w10/"><u>Mastering Desktop Organization: Notes on W11/W10</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-essential-features-of-a-mac-compatible-sound-editing-software/"><u>New 2024 Approved Essential Features of a Mac-Compatible Sound Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-trust-how-to-rectify-windows-safety-setbacks/"><u>Rebooting Trust: How to Rectify Windows Safety Setbacks</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-permanently-deleted-or-erased-excel-2000-files-for-free-stellar-by-stellar-guide/"><u>Recover Permanently Deleted or Erased Excel 2000 Files for Free | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/rog-ally-and-the-new-competitor-from-asus/"><u>ROG Ally and the New Competitor From ASUS</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-image-access-via-file-explorer-in-windows-11/"><u>Streamline Image Access via File Explorer in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-password-cracking-tools-for-realme-gt-5-by-drfone-android/"><u>Top 10 Password Cracking Tools For Realme GT 5</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-startup-latency-adjust-boot-menu-delay-in-win11/"><u>Trimming Startup Latency: Adjust Boot Menu Delay in Win11</u></a></li>
</ul></div>

