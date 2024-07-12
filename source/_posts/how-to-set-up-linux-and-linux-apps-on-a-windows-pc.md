---
title: How to Set Up Linux and Linux Apps on a Windows PC
date: 2024-07-11T21:24:33.199Z
updated: 2024-07-12T21:24:33.199Z
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

### Step 1: Install VirtualBox

 The first step is to install a VirtualBox on your Windows. Head to the [official VirtualBox website](https://www.virtualbox.org/wiki/Downloads), and download the official Windows app from the website. Launch the setup and finish the VirtualBox installation.

### Step 2: Download and Install the Linux ISO

 Now download the Linux ISO, which will be handy in installing the Linux operating system on top of VirtualBox. Head to the [official Linux website](https://www.linux.org/pages/download/) and grab the ISO file from there. In this case, we'll go with the Ubuntu distribution.

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

 From here, you can do pretty much anything; only creativity is the limit. Here's a [list of top Linux tools or commands](https://www.makeuseof.com/top-command-linux/) to help you get started.

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
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-usb-connectivity-in-windows-os-amidst-issues/"><u>Regain USB Connectivity in Windows OS Amidst Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-visual-comfort-notebook-themes-and-fonts-in-windows-11/"><u>Tailoring Visual Comfort: Notebook Themes and Fonts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/which-browser-takes-up-less-memory-and-cpu-on-windows-macos/"><u>Which Browser Takes Up Less Memory and CPU On Windows, macOS?</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-speed-and-ban-lags-in-windows-11-installation/"><u>Boost Speed & Ban Lags in Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-fn-key-usage-within-windows-11-platform/"><u>Reimagining FN Key Usage Within Windows 11 Platform</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-google-pixel-fold-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Google Pixel Fold? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-erase-no-server-errors-in-pc-apex-legends-(156-chars/"><u>Strategies To Erase No-Server Errors in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/assessment-of-differences-onsite-vs-cloud-based-windows-downloads/"><u>Assessment of Differences: Onsite vs Cloud-Based Windows Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rejuvenating-your-systems-visual-experience-through-driver-update-win7/"><u>Rejuvenating Your System's Visual Experience Through Driver Update (Win7)</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-package-not-registered-image-glitches-in-win11/"><u>Unraveling 'Package Not Registered' Image Glitches in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-storage-type-ssd-vs-hdd/"><u>Unveiling Storage Type: SSD vs HDD</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-oppo-find-n3-flip-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Oppo Find N3 Flip? </u></a></li>
<li><a href="https://windows11.techidaily.com/top-methods-to-enhance-utorrent-download-speed-win-edition/"><u>Top Methods to Enhance uTorrent Download Speed, WIN Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fix-windows-non-functional-start/"><u>A Step-by-Step Guide to Fix Window's Non-Functional Start</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-mouse-functionality-through-clicklock-mechanism/"><u>Advancing Mouse Functionality Through ClickLock Mechanism</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-complex-windows-partition-unification/"><u>The Ultimate Guide to Complex Windows Partition Unification</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-note-30-vipfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Note 30 VIPFRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-calendar-and-email-fixes/"><u>Unveiling Windows 11'S Hidden Calendar & Email Fixes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/list-of-pokemon-go-joysticks-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/a-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>A Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Samsung Galaxy S23 Tactical Edition?</u></a></li>
<li><a href="https://windows11.techidaily.com/three-strategies-to-redo-windows-11-user-preferences/"><u>Three Strategies to Redo Windows 11 User Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-clashes-in-windows-desktop-ordering/"><u>Avoid Clashes in Windows Desktop Ordering</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-touch-to-the-world-of-win11-keybindings/"><u>Tailoring Your Touch to the World of Win11 Keybindings</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-systemsettings-errors-in-windows-11/"><u>Steps to Address SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-edge-background-runs-how-to-control/"><u>Win11 and Edge Background Runs - How to Control</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-from-iphone-13-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock From iPhone 13 You Should Try Out</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719291887266-eliminating-obstacles-in-capturing-whole-screen-with-windows-snipping-tool/"><u>Eliminating Obstacles in Capturing Whole-Screen with Windows Snipping Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-firewall-settings-integration-into-windows-11s-ui/"><u>Advanced Firewall Settings Integration Into Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/activation-indicators-for-windows-11-systems/"><u>Activation Indicators for Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-deploying-themes-from-microsoft-store/"><u>Stepwise Guide to Deploying Themes From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unraveling-failed-system-call-issues-in-win1011/"><u>Steps to Unraveling 'Failed System Call' Issues in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktok-mastery-a-2023-elements-compendium-for-2024/"><u>TikTok Mastery  A 2023 Elements Compendium for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-classics-seamless-integration-of-achievements-using-retroarch-software/"><u>Boosting Classics: Seamless Integration of Achievements Using Retroarch Software</u></a></li>
</ul></div>
