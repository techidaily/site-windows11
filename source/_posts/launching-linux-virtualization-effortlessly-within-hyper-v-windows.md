---
title: Launching Linux Virtualization Effortlessly Within Hyper-V Windows
date: 2024-08-08T06:14:40.472Z
updated: 2024-08-09T06:14:40.472Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Launching Linux Virtualization Effortlessly Within Hyper-V Windows
excerpt: This Article Describes Launching Linux Virtualization Effortlessly Within Hyper-V Windows
keywords: Linux VM Hyper-V,Hyper-V Virtualize,Linux Hyper-VM,Easy Linux on Hyper-V,Hyper-VM Linux,VMware Linux Effort,Simplify Linux Virtualization
thumbnail: https://thmb.techidaily.com/bb9accbf9aa450f0fe34df3fa6aee3bab970d5d0da3d5945b94c06b1e59faa56.jpg
---

## Launching Linux Virtualization Effortlessly Within Hyper-V Windows

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
5. Click on the**OK** button to apply changes.

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the[Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

 Now that the virtual machine is ready, it's time to get Ubuntu up and running:

1. Select the newly created virtual machine in the list and click on the**Start** option to launch the virtual machine.
2. Ubuntu setup will launch. Select the**Install Ubuntu** option and proceed with the installation.
3. Click on**Minimal Installation** and uncheck the**Download updates while installing Ubuntu** option.
4. Then, pick the**Erase disk and install Ubuntu** option and click on the**Install Now** button.
5. Select your geographical location and enter your username and password. Then, click on the**Continue** button.
6. Wait for the installation to complete. It may take longer if you have a SATA HDD installed on your system.
7. The installer will prompt you to restart the system. Click on the**Restart Now** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Ubuntu Virtual Machine Running Using Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/ubuntu-virtual-machine-running-using-hyper-v.jpg)

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on[how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

## Use Virtual Machine Inside a Virtual Machine With Hyper-V

 VMware supports hardware virtualization and can extend the feature to its virtual machines. VirtualBox is yet to catch up in this aspect because Hyper-V doesn’t work in a VirtualBox virtual machine as of writing this post. Make sure that you turn off virtualization features for the Windows virtual machine when you no longer need it.


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
<li><a href="https://youtube-data.techidaily.com/024-approved-coordinating-a-course-through-combined-youtube-watches/"><u>[New] 2024 Approved  Coordinating a Course Through Combined YouTube Watches</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-content-top-reasons-and-solutions-for-gaining-video-views/"><u>[New] 2024 Approved  Elevate Your Content  Top Reasons and Solutions for Gaining Video Views</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-expert-techniques-for-acquiring-pristine-images/"><u>[Updated] In 2024, Expert Techniques for Acquiring Pristine Images</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-optimizing-your-project-b-roll-utilization-tips/"><u>[Updated] In 2024, Optimizing Your Project  B-Roll Utilization Tips</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-lolkit-design-memes-and-graphics-with-a-click/"><u>[Updated] LolKit  Design Memes & Graphics with a Click</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-set-best-8-macbook-themes-and-skins/"><u>2024 Approved  Ideal Set  Best 8 MacBook Themes & Skins</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-installer-glitches-on-latest-windows-versions/"><u>Combatting Installer Glitches on Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-retrieval-how-to-master-the-art-of-qr-scanning-with-windows/"><u>Effortless Data Retrieval: How to Master the Art of QR Scanning with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hidden-programs-on-windows-pc/"><u>Enabling Hidden Programs on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smart-color-settings-in-windows-11-apps/"><u>Enabling Smart Color Settings in Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-real-time-performance-for-smooth-vlc-viewing/"><u>Enhancing Real-Time Performance for Smooth VLC Viewing</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-apple-iphone-6s-plus-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass Apple iPhone 6s Plus Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-realme-v30-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Realme V30 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-freezes-and-crashes-in-virtual-worlds/"><u>How to Reset Freezes & Crashes in Virtual Worlds</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-windows-control-panel-running-smoothly/"><u>Keep Your Windows Control Panel Running Smoothly</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/make-facebook-videos-extend-the-wallpaper-for-2024/"><u>Make Facebook Videos Extend the Wallpaper for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-based-in-game-voice-sync-with-valorant/"><u>Mastering Windows-Based In-Game Voice Sync with Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-auto-lock-settings-in-windows/"><u>Navigate Auto-Lock Settings in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/navigating-the-essentials-of-attractive-profiles/"><u>Navigating the Essentials of Attractive Profiles</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-mac-video-editing-made-easy-a-beginners-guide-to-movie-creation-for-2024/"><u>New Mac Video Editing Made Easy A Beginners Guide to Movie Creation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-image-precision-with-windows-11s-blurring-feature-in-photos-app/"><u>Unlocking Image Precision with Windows 11'S Blurring Feature in Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
</ul></div>
