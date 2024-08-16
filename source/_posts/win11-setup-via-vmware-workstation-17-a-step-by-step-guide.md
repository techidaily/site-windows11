---
title: "Win11 Setup via VMware Workstation 17: A Step-by-Step Guide"
date: 2024-08-15T16:17:15.613Z
updated: 2024-08-16T16:17:15.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Setup via VMware Workstation 17: A Step-by-Step Guide"
excerpt: "This Article Describes Win11 Setup via VMware Workstation 17: A Step-by-Step Guide"
keywords: Win11 Installation VMWare,Windows 11 Virtual Setup,Win11 VMSetup Guide,Workstation 17 Win11 Prep,Steps to Install Win11 VM,Setting Up Win11 VMware,VirtualWin11 Configuration
thumbnail: https://thmb.techidaily.com/9648422bd4a60544ea009a8215c8d33f0ea36e37be4db7347e6bdc7775fbd6e2.jpg
---

## Win11 Setup via VMware Workstation 17: A Step-by-Step Guide

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.

## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on[how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
2. A Windows 10 or above operating system with TPM 2.0 and virtualization support.
3. The latest version of VMware Workstation 17 Player must be pre-installed on the host system.
4. Adequate computing resources to run Windows 11 as a virtual machine. The list includes 64 GB disk space, 4 GB RAM, and a dual-core x64 processor.

 Once you have the necessary ISO file and the latest copy of VMware on your system, you can proceed to the virtual machine creation and Windows 11 installation.

## How to Install Windows 11 in VMware Workstation 17 Player

 Firstly, we will create a virtual machine in VMware for Windows 11\. Then, we will install Windows 11 on the virtual machine. Lastly, we will install VMware tools to finish setting up the virtual machine.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Create a Windows 11 Virtual Machine

 Here’s how to create a virtual machine for Windows 11 in VMware:

1. Launch VMware Player on your system. On the home page, click on**Create a new virtual machine** option.
2. Select the**I will install the operating system later** radio button and click on the**Next** button.  
![Creating a Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/creating-a-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

1. Click on the**Customize Hardware** button. Under the memory tab, increase the**RAM** allocation to**6 GB** or more to avoid a sluggish Windows 11 experience.
2. Switch to the**Processors** tab and allocate**4 or more cores** to the Windows virtual machine.
3. Next, move to the**New CD/DVD (SATA)** tab, and click on the**Use ISO image file** option located under the**Connection** section.
4. Click on the**Browse** button and select the Windows 11 ISO image file you previously downloaded. Click on the**Open** button.
5. Now, close the Hardware window and click on the**Finish** button to create the new virtual machine.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Install Windows 11 on the Virtual Machine

 Repeat the following steps to install Windows 11 on the newly created virtual machine:

1. Navigate to the left-hand side menu and select the Windows 11 virtual machine. Click on the**Play virtual machine** option.
2. Press any keyboard key to boot from the ISO file. Pick the appropriate language and region and click on the**Next** button. Then, click on the**Install now** button.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. In the Windows setup window, click on the**I don’t have a product key** option.
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## Run Windows 11 on VMware Without Any Registry Hacks

 With TMP emulation, there is no need for registry tweaking to disable secure boot and TPM requirements on Windows 11\. All the features work fine, and you don’t need to switch to another hypervisor program. However, Oracle VirtualBox offers the same TPM virtualization and secure boot features.


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
<li><a href="https://youtube-lab.techidaily.com/024-approved-exploring-differences-between-igtv-and-youtube-for-effective-posts/"><u>[New] 2024 Approved  Exploring Differences Between IGTV and YouTube for Effective Posts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-make-collage-for-facebook-instantly/"><u>[Updated] How to Make Collage for Facebook Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-capturing-excellence-the-premium-seven-selection/"><u>2024 Approved  Capturing Excellence  The Premium Seven Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-virtual-fraud-tips-for-discerning-true-windows-apps/"><u>Avoid Virtual Fraud: Tips for Discerning True Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-dialogue-and-direction-in-film-scripts-for-2024/"><u>Crafting Dialogue and Direction in Film Scripts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-differences-how-exe-files-function-compared-to-msi/"><u>Dissecting Differences: How Exe Files Function Compared to Msi</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-absence-of-drive-letters-in-windows-environments/"><u>Dissecting the Absence of Drive Letters in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-seamless-fullscreen-launch-on-windows-pcs/"><u>Ensure Seamless Fullscreen Launch on Windows PCs</u></a></li>
<li><a href="https://driver-install.techidaily.com/essential-guide-new-nvidia-drivers-in-windows/"><u>Essential Guide: New NVIDIA Drivers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-12-pro-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 12 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-11-when-it-cant-connect-to-5ghz-wi-fi/"><u>How to Fix Windows 11 When It Can’t Connect to 5GHz Wi-Fi</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-breaking-news-working-obs-cam/"><u>In 2024, Breaking News  Working OBS Cam</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabling-iphone-6-parental-restrictions-withwithout-password-drfone-by-drfone-ios/"><u>In 2024, Disabling iPhone 6 Parental Restrictions With/Without Password | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inside-out-top-tips-for-windows-11-pros-for-2024/"><u>Inside Out  Top Tips for Windows 11 Pros for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-guide-for-end-task-enabling-on-windows-11/"><u>Instructional Guide for End Task Enabling on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-unveiled-navigating-disks-in-w10-and-w11-systems/"><u>Key Steps Unveiled: Navigating Disks in W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-surface-software-enhancement-techniques-for-maximum-performance/"><u>Mastering Surface Software Enhancement Techniques for Maximum Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://windows11.techidaily.com/mindfulness-meets-the-mind-cognitive-and-emotional-responses-to-meditation/"><u>Mindfulness Meets the Mind: Cognitive & Emotional Responses to Meditation</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-search-with-custom-settings/"><u>Optimizing Windows 11 Search with Custom Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-vms-in-windows-using-these-top-6-enhancers/"><u>Power Up Your VMs in Windows Using These Top 6 Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-nvidia-experience-connectivity-issues-on-pcs/"><u>Remedying Nvidia Experience Connectivity Issues on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-lag-how-to-fix-warhammer-40k-delays-on-your-pc/"><u>Say Goodbye to Lag: How to Fix Warhammer 40K Delays on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-typing-swift-input-strategies-for-win-1011-users/"><u>Skyrocket Your Typing: Swift Input Strategies for WIN 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-taskbar-transparency-in-maxed-browser-screens/"><u>Solutions for Taskbar Transparency in Maxed Browser Screens</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Motorola Moto G 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-selectable-text-in-windows-based-pdf-documents-easily/"><u>Tackle Non-Selectable Text in Windows-Based PDF Documents Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-guide-to-image-spin-on-your-windows-11-pc/"><u>The Complete Guide to Image Spin on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-tutorial-to-launch-w11s-administrator-powershell/"><u>The Complete Tutorial to Launch W11's Administrator PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-edge-building-snaps-with-powertoys/"><u>The Insider's Edge: Building Snaps with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-selection-of-cost-free-storage-solutions-for-windows-users/"><u>The Ultimate Selection of Cost-Free Storage Solutions for Windows Users</u></a></li>
<li><a href="https://fox-links.techidaily.com/unboxing-mastery-the-soundtrack-selection-guidebook-for-2024/"><u>Unboxing Mastery  The Soundtrack Selection Guidebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
</ul></div>
