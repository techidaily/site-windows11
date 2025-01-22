---
title: Accessing the Internet Without a Browser Post-Setup
date: 2025-01-15T20:46:41.892Z
updated: 2025-01-22T19:13:44.304Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing the Internet Without a Browser Post-Setup
excerpt: This Article Describes Accessing the Internet Without a Browser Post-Setup
keywords: NoBrowserInternetAccess,PostSetupWebNavSkip,BrowseFreePostInstall,AccessNetNoBrowser,NonBrowserWebEntry,DirectNetPostSetup,InternetBypassBrowser
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
---

## Accessing the Internet Without a Browser Post-Setup

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and [Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose [Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once the process is complete, you can start using the new browser.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by [launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

## Start Browsing on Your Fave Browser From Day One

 Hopefully, you were able to download a browser and install it using one of these methods. Windows offers a ton of options to get things done. Take your pick when installing a browser without a browser. What matters is installing a browser you think best suits your needs.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-exclusive-video-editing-software-just-for-vimeo-pros/"><u>[New] 2024 Approved Exclusive Video Editing Software Just For Vimeo Pros</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlocking-the-secrets-of-youtubes-shorts-revenue-sharing/"><u>[New] Unlocking the Secrets of YouTube’s Shorts Revenue Sharing</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-free-meme-templates/"><u>[Updated] Best Free Meme Templates</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-discover-the-power-of-kinemaster-and-learn-about-its-10-online-rivals/"><u>[Updated] In 2024, Discover the Power of KineMaster & Learn About Its 10 Online Rivals</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compre-written-in-the-stars-mastering-your-laptops-touchscreen-precision/"><u>A Compre Written in the Stars: Mastering Your Laptop’s Touchscreen Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-proficient-with-windows-odbc-control-panel/"><u>Becoming Proficient with Windows' ODBC Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-software-generations-windows-7-key-for-11-boot/"><u>Bridging Software Generations: Windows 7 Key for 11 Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-reroute-mac-screenshot-file-destination/"><u>In 2024, Reroute Mac Screenshot File Destination</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96393659-9781591433392-opening-the-akashic-records/"><u>Opening the Akashic Records | Free Book</u></a></li>
<li><a href="https://win-answers.techidaily.com/sharpen-your-gameplay-tips-and-tricks-to-correct-unclear-graphics-in-cod-warzone-on-windows/"><u>Sharpen Your Gameplay: Tips & Tricks to Correct Unclear Graphics in COD: Warzone on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/king-success-optimizing-gaming-videos-via-smart-use-of-hashtags/"><u>Unlocking Success Optimizing Gaming Videos via Smart Use of Hashtags</u></a></li>
</ul></div>

