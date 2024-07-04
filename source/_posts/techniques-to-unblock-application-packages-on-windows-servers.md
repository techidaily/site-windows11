---
title: Techniques to Unblock Application Packages on Windows Servers
date: 2024-06-25T12:07:59.819Z
updated: 2024-06-26T12:07:59.819Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Unblock Application Packages on Windows Servers
excerpt: This Article Describes Techniques to Unblock Application Packages on Windows Servers
keywords: Unlock Apps,Server Fix,Windows Package Unblock,App Deployment,Server Restore,Windows Unblock Guide,Blocked Apps Fix
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

## Techniques to Unblock Application Packages on Windows Servers

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

 You can use[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.


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
<li><a href="https://windows11.techidaily.com/quick-guide-to-tackling-error-1053-unresponsive-windows-services/"><u>Quick Guide to Tackling Error 1053: Unresponsive Windows Services</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/climate-control-experts-the-finest-windows-11-apps/"><u>Climate Control Experts: The Finest Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-tweaking-your-web-privacy-via-proxies-in-win-11/"><u>Expert Advice: Tweaking Your Web Privacy via Proxies in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-agendas-integrating-ifttt-with-to-do/"><u>Automating Agendas: Integrating IFTTT with To-Do</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premier-gopro-hero5-black-batteries-with-certified-chargers/"><u>[New] Premier GoPro Hero5 Black Batteries with Certified Chargers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-samsung-galaxy-m54-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Samsung Galaxy M54 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-asus-rog-phone-7-ultimate-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Asus ROG Phone 7 Ultimate Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-oppo-reno-8t-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Oppo Reno 8T 5G Location | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-discovering-keepsake-bell-ringtone-implementations/"><u>In 2024, Discovering Keepsake Bell Ringtone Implementations</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-uncovering-places-known-for-thunderous-tribute-sounds/"><u>2024 Approved Uncovering Places Known for Thunderous Tribute Sounds</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-realme-narzo-60x-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Realme Narzo 60x 5G PC | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-slumber-solutions-through-asmr-advisors-choice/"><u>[New] Slumber Solutions Through ASMR  Advisors' Choice</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comprehensive-movement-study-2023/"><u>2024 Approved  Comprehensive Movement Study 2023</u></a></li>
</ul></div>
