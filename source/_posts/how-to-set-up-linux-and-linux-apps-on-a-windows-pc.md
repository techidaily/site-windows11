---
title: How to Set Up Linux and Linux Apps on a Windows PC
date: 2024-08-15T16:07:17.083Z
updated: 2024-08-16T16:07:17.083Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Set Up Linux and Linux Apps on a Windows PC
excerpt: This Article Describes How to Set Up Linux and Linux Apps on a Windows PC
keywords: Installing Linux,Setting up Linux,Linux on Windows,Linux Apps Setup,Laptop with Dual OS,Linux Desktop Integration,Windows + Linux Compatibility
thumbnail: https://thmb.techidaily.com/a172e0efcea75add6ab8eef1d0430a010e6f31545b8fd2ecff1c5ec11c0e45ff.png
---

## How to Set Up Linux and Linux Apps on a Windows PC

 If you are a typical tech enthusiast like us, you must have already used one or another form of Linux on your PC so far. And why not; it’s open source, offers tons of customization options, and, these days, it also lets you run almost any Windows app on it. But did you know the reverse is true as well?

 With a few modifications, you can now install and use all your Linux apps on Windows with a breeze. If you're looking to install and run Linux apps on Windows, then you've come to the right place. So, let’s dive into all the methods one by one.

## 1\. Virtual Machines

 Virtual machines have been around for a while—since 1999, to be precise, when [VMware first introduced the concept of virtualization](https://www.vmware.com/timeline.html). They have evolved multiple times over the years, but the primary purpose is still the same: to help you run a specific operating system on top of a ‘host’ computer that works on a different OS.

 Windows has a few options to choose from when it comes to picking a virtual machine. VirtualBox, VMware, and Bootcamp are some of the free options you can try out. And then there’s Parallels, Bluestacks, etc., on the proprietary side, too.

 If this is your first time playing around with VMs, we suggest you use a free, open-source option like [VirtualBox](https://www.makeuseof.com/what-is-virtualbox-what-does-it-do/). After you have VirtualBox, you have to install the Linux ISO; from there, you can run your Linux (and your Linux apps) on VirtualBox.

 Confusing? Don’t panic; we’ll do this in steps.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Step 1: Install VirtualBox

 The first step is to install a VirtualBox on your Windows. Head to the [official VirtualBox website](https://www.virtualbox.org/wiki/Downloads), and download the official Windows app from the website. Launch the setup and finish the VirtualBox installation.

### Step 2: Download and Install the Linux ISO

 Now download the Linux ISO, which will be handy in installing the Linux operating system on top of VirtualBox. Head to the [official Linux website](https://www.linux.org/pages/download/) and grab the ISO file from there. In this case, we'll go with the Ubuntu distribution.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
### Step 3: Install Linux on VirtualBox

 Now it’s time to install Linux on VirtualBox. Here’s how:

1. Launch the VirtualBox, and select **New**.
2. Select a relevant name for your OS, and pick the Ubuntu ISO image you just downloaded from above. Then click on **Next**.
3. Set a username and password, and click on **Next**.
4. Allocate a relevant name to the virtual operating system.
5. In the next dialog box, select **Create a virtual hard disk** **now**, and choose **Next**. Finally, click on **Finish**.

![create virtual machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-virtual-machine.JPG)

 From here, VirtualBox will then power up the Ubuntu VM on its own, and in a few seconds you will see the Ubuntu interface as well. In a couple of minutes, it will also finish the Ubuntu installation on its own.

![ubuntu oracle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-oracle.JPG)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

**Note:** If the VirtualBox doesn’t pick up the Linux ISO automatically, you must try the manual method; click on the folder, choose the file manually, and click **Start**. Finally, the Linux setup will be launched. From here, choose the language and click on **Install Ubuntu** to get started with the first part of the installation.

 Again, follow the on-screen instructions from here; it’s pretty straightforward. When asked, set up an account, and click **Continue** to finish the installation. Ubuntu will be installed on your VirtualBox in a few seconds from here.

 Now that Ubuntu is installed, you can run all the Linux apps on your Windows straight through the VirtualBox.

## 2\. Windows Subsystem for Linux 2 (WSL2)

 Using a virtual machine to run Linux is fine, but it isn’t straightforward and takes a fair amount of tinkering to get running. This is where Windows Subsystem for Linux, or WSL, can help you. WSL is a Windows feature that will help you run the Linux environment on your Windows without the help of a virtual machine like VirtualBox.

 We have a detailed guide that covers [how you can download and set up WSL2](https://www.makeuseof.com/how-to-run-linux-gui-apps-with-wsl2/) on your PC. Follow the steps from the guide, and you will be using the WSL (and, along with it, Linux apps) in no time.

## 3\. Cygwin

[Cygwin](https://www.cygwin.com/) is an open-source tool that offers a UNIX/Linux-like shell to run your Linux tools on the Windows environment. To get started, you first have to download the Cygwin app. Follow the steps below to get started:

* Download the Cygwin installer from the [official website](https://www.cygwin.com/).
* When launching the Cygwin app, choose the **Install from Internet** option and select **Next**.
* Set the installation location and click on **Next**.
* Follow the on-screen instructions from here, and when you arrive at the download mirror selection, pick any mirror, and click on **Next**.
* The mirror will download several packages now. Choose the default option and click on **Next** to proceed ahead.

![cygwin setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cygwin-setup.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

 After you’re done with the installation, you can then launch the Cygwin terminal from your desktop. By default, the terminal is set to _C:\\Cygwin\\home\\<user>_ folder. So, first, we suggest you move it to the _/cygdrive/c_ directory, so that you can run various Linux commands.

 Before we move ahead to make Cygwin work on Windows, though, you have to add it to your Windows Environment Variable so that you will be able to launch Cygwin straight from your Windows command prompt. You should start by opening the system properties. Then press the **Win+Pause/Break** or right-click on the computer and select properties.

![advanced system settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-system-settings.jpg)

 From there, click on **Advanced system settings** to open the system properties window. Now, click on the **Environment Variables** button from the bottom. Locate the path and click on **Edit**.

 At the end of the variable value, add Cygwin to your bin location. Here’s how:

;C:\Cygwin\bin

 Copy the above address and paste it into the end of the **Path** variable, and click on **OK** after you’re done.

![cygwin setup-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cygwin-setup-1.jpg)

 That’s it. You can now run Linux apps straight from the Cygwin app. Launch Cygwin and start typing the Ubuntu commands from here on. For instance, we have below used the _pwd_ command, which basically prints the path of the working directory, from the root.

![cygwin](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cygwin.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 From here, you can do pretty much anything; only creativity is the limit. Here's a [list of top Linux tools or commands](https://www.makeuseof.com/top-command-linux/) to help you get started.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Running Linux Apps on Your Windows Computer

 You don’t have to switch to Linux every time you want to use a handy tool from its large repository. With the methods we’ve laid down above, you can pretty much run any Linux tool straight from your Windows computer.

 While running Linux apps on your Windows will undoubtedly involve going through a slew of complicated steps, using them becomes second nature after a while. In fact, this also holds for the reverse case; by that, we mean when you’re looking to run Windows apps on your Linux.


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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-harness-the-power-of-video-for-enhanced-facebook-traffic/"><u>[New] In 2024, Harness the Power of Video for Enhanced Facebook Traffic</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-journey-through-history-similar-themed-video-games-to-ghost-of-tsushima-for-2024/"><u>[New] Journey Through History  Similar Themed Video Games to Ghost of Tsushima for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-survival-in-mc-top-house-ideas-and-plans/"><u>[New] Survival in MC  Top House Ideas & Plans</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-amplify-your-storytelling-integrating-captions-in-a-triple-threat-on-ig/"><u>[Updated] 2024 Approved  Amplify Your Storytelling - Integrating Captions in a Triple Threat on IG</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-unlocking-the-door-to-joining-a-tiktok-gathering/"><u>[Updated] 2024 Approved  Unlocking the Door to Joining a TikTok Gathering</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-first-time-furnishings-minimalist-house-plans-in-mc/"><u>[Updated] First-Time Furnishings  Minimalist House Plans in MC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-often-can-creators-expect-to-be-paid-by-youtube-in-2024/"><u>[Updated] How Often Can Creators Expect to Be Paid by YouTube, In 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-must-know-aspect-ratio-for-tweeting-videos-for-2024/"><u>[Updated] The Must-Know Aspect Ratio for Tweeting Videos for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-obs-capture-directly-on-instagram/"><u>2024 Approved  OBS Capture Directly on Instagram</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-premier-tech-to-record-your-on-air-video-on-youtube/"><u>2024 Approved  Premier Tech to Record Your On-Air Video on YouTube</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-synthesizing-creativity-a-brainstormers-toolkit-for-names/"><u>2024 Approved  Synthesizing Creativity  A Brainstormer’s Toolkit for Names</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-steps-to-resolve-chrome-profile-errors/"><u>7 Essential Steps to Resolve Chrome Profile Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/activation-indicators-for-windows-11-systems/"><u>Activation Indicators for Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-speed-and-ban-lags-in-windows-11-installation/"><u>Boost Speed & Ban Lags in Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-convenient-windows-environment-portable-software-icons/"><u>Create a Convenient Windows Environment: Portable Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-camera-app-crash-microsofts-windows-error-0xa00f425d/"><u>Eliminating Camera App Crash: Microsoft's Windows Error 0xA00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-mistakes-to-dodge-on-windows-11-upgrade/"><u>Essential Mistakes to Dodge on Windows 11 Upgrade</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-safety-and-performance-the-complete-guide-to-anker-roav-dash-cam-c1/"><u>Evaluating Safety and Performance - The Complete Guide to Anker Roav Dash Cam C1</u></a></li>
<li><a href="https://games-able.techidaily.com/fix-computer-issues-embrace-new-nvidia-drivers-today/"><u>Fix Computer Issues: Embrace New Nvidia Drivers Today.</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inactive-windows-headsets-communication-line/"><u>Fixing Inactive Windows Headset's Communication Line</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-beginner-to-pro-transforming-windows-videos-with-minimal-tools-for-2024/"><u>From Beginner to Pro  Transforming Windows Videos with Minimal Tools for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/from-screen-to-disk-techniques-for-effortless-internet-show-recording-for-2024/"><u>From Screen To Disk  Techniques for Effortless Internet Show Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-non-working-display-driver-on-windows-11/"><u>Guide to Fixing Non-Working Display Driver on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-driver-verification-on-windows-11-pcs/"><u>How to Enable Driver Verification on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-signing-you-in-with-a-temporary-profile/"><u>How to Fix Windows Signing You In With a Temporary Profile</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-battlefield-brilliance-the-exclusive-selection-of-top-7-total-war-chronicles/"><u>In 2024, Battlefield Brilliance  The Exclusive Selection of Top 7 Total War Chronicles</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-vivo-v30-promirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Vivo V30 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-honor-magic-5-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Honor Magic 5 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-witness-the-blend-the-top-ten-funny-and-deep-ig-meme-accounts/"><u>In 2024, Witness the Blend  The Top Ten Funny & Deep IG Meme Accounts</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-search-techniques-that-dont-use-ls/"><u>Innovative Windows Search Techniques That Don't Use LS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/instant-download-brother-hl-3170cdw-printer-drivers-swift-setup/"><u>Instant Download: Brother HL-3170CDW Printer Drivers | Swift Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/masking-task-view-button-on-win-11-bar/"><u>Masking Task View Button on Win 11 Bar</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-bing-ai-chat-tips-for-seamless-integration-with-your-android-keyboard/"><u>Mastering Bing AI Chat: Tips for Seamless Integration with Your Android Keyboard</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-for-edges-webview2/"><u>Mastering Memory Management for Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-territory-altering-default-app-choices-in-windows-11/"><u>Navigating New Territory: Altering Default App Choices in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-itunes-freeze-problems/"><u>Overcoming Windows-Based iTunes Freeze Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-torrent-performance-post-transfer-to-a-new-machine/"><u>Preserving Torrent Performance Post-Transfer to a New Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-usb-connectivity-in-windows-os-amidst-issues/"><u>Regain USB Connectivity in Windows OS Amidst Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-fn-key-usage-within-windows-11-platform/"><u>Reimagining FN Key Usage Within Windows 11 Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-pc-connection-issues-with-bluetooth-input-devices/"><u>Step-by-Step Solution for PC Connection Issues with Bluetooth Input Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unraveling-failed-system-call-issues-in-win1011/"><u>Steps to Unraveling 'Failed System Call' Issues in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-deploying-themes-from-microsoft-store/"><u>Stepwise Guide to Deploying Themes From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-sleepy-slumber-of-hibernation-woes/"><u>Stop the Sleepy Slumber of Hibernation Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-erase-no-server-errors-in-pc-apex-legends-(156-chars/"><u>Strategies To Erase No-Server Errors in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-interruptexception-on-windows-11/"><u>Tackling the INTERRUPT_EXCEPTION on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-touch-to-the-world-of-win11-keybindings/"><u>Tailoring Your Touch to the World of Win11 Keybindings</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-honor-magic-v2-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Honor Magic V2</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-12-clicker-games-on-pc/"><u>Top 12 Clicker Games on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-command-prompt-gambits-for-a-laugh/"><u>Top 5 Command Prompt Gambits for a Laugh</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-for-pc-players-facing-silent-warzone-battles/"><u>Troubleshooting Steps for PC Players Facing Silent Warzone Battles</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-storage-type-ssd-vs-hdd/"><u>Unveiling Storage Type: SSD vs HDD</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-calendar-and-email-fixes/"><u>Unveiling Windows 11'S Hidden Calendar & Email Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-error-code-0xc1900101/"><u>Unveiling Windows 11'S Hidden Error Code #0xC1900101</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-instant-and-simple-connection-guide-for-scansnap-s510-scanner/"><u>Update: Instant and Simple Connection Guide for ScanSnap S510 Scanner</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Lava Blaze Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/which-browser-takes-up-less-memory-and-cpu-on-windows-macos/"><u>Which Browser Takes Up Less Memory and CPU On Windows, macOS?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
</ul></div>
