---
title: Install and Manage Packages with Windows Package Manager (WPM)
date: 2024-10-17T21:01:31.252Z
updated: 2024-10-24T17:16:35.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Install and Manage Packages with Windows Package Manager (WPM)
excerpt: This Article Describes Install and Manage Packages with Windows Package Manager (WPM)
keywords: Windows Package Management,WPM Installation Guide,Packages Management on Win,WPM Dependency Resolution,Windows WPM Command Line,Efficient Software Updates,Package Manager Automation
thumbnail: https://thmb.techidaily.com/e9c990e25117479e90a6a7012f47011623d3e85d5155cf7861b563822cc331cb.jpg
---

## Install and Manage Packages with Windows Package Manager (WPM)

 As Windows has developed over the years, we’ve seen Microsoft introduce some of Linux’s functionality into the Windows ecosystem. In addition to Windows 10 and 11 supporting a Linux subsystem through WSL 2, they also feature a package manager called the Windows Package Manager (or winget for short).

 So what exactly is the Windows Package Manager, and how do you use it? Read on as we answer all of your burning questions below.

## What Is a Package Manager?

 All modern apps and any projects that you build will utilize existing frameworks, libraries, and tools. If you’re building a simple React app, you’re going to require Node.js, ReactJS, and other libraries or tools for your project to function correctly. The underlying third-party software that essentially helps your project function is called dependencies.

 As you can imagine, managing the installation and updation of multiple dependencies within a project can become quite frustrating. You also need to make sure that your system is compatible with third-party software. If you were to integrate and update each third-party software manually, you’d be wasting a good chunk of your valuable time managing the software dependencies.

 To solve this problem (among others), developers came up with the ingenious idea of a package manager—a single tool that can manage all your project dependencies. Package managers typically perform several essential features such as:

* Finding the correct source files for your platform.
* Ensuring source files are free of malware and other security vulnerabilities.
* Integrating dependencies into your project.
* Allowing seamless installation, updation, and removal of software dependencies.

 Package managers also have a vast catalog of tools you can choose from and install with just a single command on the terminal.

Some examples of popular package managers include:

* Homebrew.
* Node Package Manager (NPM).
* Yarn.
* Advanced Packaging Tool (APT).

## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105883/7443" target="_top" id="2105883">
  <img src="//a.impactradius-go.com/display-ad/7443-2105883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to[log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087253/19272" target="_top" id="2087253">
  <img src="//a.impactradius-go.com/display-ad/19272-2087253" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087253/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a[third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

### 4\. How to View Application Details

![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)

 To look into the installation details and software version of a specific app, you can use the following command:

`winget show <APP_NAME>`

## Are Package Managers Worth the Hassle on Windows?

 Winget is incredible at installing applications on your Windows 11 PC. You no longer need to hunt for malware-free download links on the internet; simply open up a terminal and download the application you need via winget.

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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-sharpen-the-scene-expert-insights-for-cropping-videos-with-insta-flair/"><u>[Updated] 2024 Approved Sharpen the Scene Expert Insights for Cropping Videos with Insta Flair</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-optimize-your-iphones-camera-for-perfection/"><u>[Updated] In 2024, Optimize Your iPhone's Camera for Perfection</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-soundscape-scrutiny-listening-insights-for-2024/"><u>[Updated] Soundscape Scrutiny Listening Insights for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/building-fantasy-universes-with-chatgpt-step-by-step-tips-and-tricks/"><u>Building Fantasy Universes with ChatGPT: Step-by-Step Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-adjust-lockout-frequency-after-incorrect-user-credentials-for-windows-11/"><u>How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-vivo-y200-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Vivo Y200 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-unsolicited-openings-of-search-bar-win11/"><u>How to Prevent Unsolicited Openings of Search Bar, Win11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-plus-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 15 Plus With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-convergence-the-best-6-compatible-android-apps-on-windows-11/"><u>Master the Convergence: The Best 6 Compatible Android Apps on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/optus-and-ciscos-30-year-legacy-of-innovation-in-australia-revolutionizing-customer-collaboration/"><u>Optus and Cisco's 30-Year Legacy of Innovation in Australia, Revolutionizing Customer Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-win-1011-menu-options/"><u>Reviving Your Win 10/11 Menu Options</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamlining-your-meetings-using-zoom-with-win11-for-2024/"><u>Streamlining Your Meetings Using Zoom with Win11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-correcting-failed-java-setup-in-windows/"><u>Techniques for Correcting Failed Java Setup in Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-simple-process-of-uploading-videos-to-twitter/"><u>The Simple Process of Uploading Videos to Twitter</u></a></li>
</ul></div>

