---
title: Leveraging Hyper-V for Efficient Linux VM Creation in Windows
date: 2024-08-15T16:08:17.695Z
updated: 2024-08-16T16:08:17.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging Hyper-V for Efficient Linux VM Creation in Windows
excerpt: This Article Describes Leveraging Hyper-V for Efficient Linux VM Creation in Windows
keywords: Hyper-V Linux VMs,Efficient VM Creation,WinHybrid Virtualization,Linux VM Optimization,Hyper-V Pro Power,Streamlined VM Setup,Windows VM Management
thumbnail: https://thmb.techidaily.com/00d8a989d7a324ab139f90cea816e72b6f2451ab8e331cf2285ff4f2ecbceec0.jpg
---

## Leveraging Hyper-V for Efficient Linux VM Creation in Windows

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

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
2. Once you boot to the desktop, press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the [Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

 Now that the virtual machine is ready, it's time to get Ubuntu up and running:

1. Select the newly created virtual machine in the list and click on the**Start** option to launch the virtual machine.
2. Ubuntu setup will launch. Select the**Install Ubuntu** option and proceed with the installation.
3. Click on**Minimal Installation** and uncheck the**Download updates while installing Ubuntu** option.
4. Then, pick the**Erase disk and install Ubuntu** option and click on the**Install Now** button.
5. Select your geographical location and enter your username and password. Then, click on the**Continue** button.
6. Wait for the installation to complete. It may take longer if you have a SATA HDD installed on your system.
7. The installer will prompt you to restart the system. Click on the**Restart Now** button.  
![Ubuntu Virtual Machine Running Using Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/ubuntu-virtual-machine-running-using-hyper-v.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on [how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-complete-logs-of-facebook-messages-explained-for-2024/"><u>[New] Complete Logs of Facebook Messages Explained for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-going-against-the-grain-instagram-video-reversal/"><u>[New] Going Against the Grain  Instagram Video Reversal</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-laptop-video-edits-going-off-inshot-for-2024/"><u>[New] Laptop Video Edits  Going Off-Inshot for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-8-online-learning-paths-for-newcomers-to-video/"><u>[New] Top 8 Online Learning Paths for Newcomers to Video</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-unlocking-imovies-potential-youtube-video-edition-excellence/"><u>[New] Unlocking iMovie's Potential  YouTube Video Edition Excellence</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-bridging-gaps-online-effective-techniques-for-screenshare-on-fb/"><u>[Updated] In 2024, Bridging Gaps Online  Effective Techniques for Screenshare on FB</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-obs-studio-vs-fraps-top-screen-capture-software-showdown/"><u>[Updated] In 2024, OBS Studio Vs Fraps  Top Screen Capture Software Showdown</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-perfect-the-art-of-posting-on-snapchat-15-tips/"><u>[Updated] Perfect the Art of Posting on Snapchat (15 Tips)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-noctuas-game-changer-the-prototype-for-pumpless-eco-friendly-aio-liquid-cooling-system/"><u>Discover Noctua's Game-Changer: The Prototype for Pumpless, Eco-Friendly AIO Liquid Cooling System</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-reactivate-printing-services/"><u>Easily Reactivate Printing Services</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-switch-your-windows-11-logon-technique-ditch-pin-embrace-password/"><u>Easily Switch Your Windows 11 Logon Technique: Ditch PIN, Embrace Password</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-excessive-load-alert-for-gpt-window-use/"><u>Easing Excessive Load Alert for GPT Window Use</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-cleansing-steam-dns-cache/"><u>Effective Strategies for Cleansing Steam DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-playback-of-laggard-videos/"><u>Efficient Playback of Laggard Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-address-directdraw-errors-in-newer-windows-editions/"><u>Efficient Strategies to Address DirectDraw Errors in Newer Windows Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-altering-windows-account-pin-code/"><u>Efficiently Altering Windows Account Pin Code</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-workstation-toggling-with-advanced-rdp-windows/"><u>Effortless Workstation Toggling with Advanced RDP Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-performance-top-tools-to-tune-up-windows-pcs/"><u>Elevate Performance: Top Tools to Tune Up Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-to-the-top-with-these-key-windows-11-widgets/"><u>Elevate to the Top with These Key Windows 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-window-management-crafting-unique-snapping-patterns/"><u>Elevate Window Management: Crafting Unique Snapping Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-workflow-select-7-most-powerful-w11-widgets/"><u>Elevate Workflow: Select 7 Most Powerful W11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-application-display-enable-windows-11s-autocolor/"><u>Elevate Your Application Display - Enable Windows 11'S AutoColor</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-with-god-mode-add-on/"><u>Elevate Your Workflow with God Mode Add-On</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-workflow-on-windows-11-for-professionals/"><u>Elevating Workflow on Windows 11 for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-app-setup-game-with-winstall-on-windows-11/"><u>Elevating Your App Setup Game with Winstall on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-hyper-v-bsod-steps-to-restore-windows/"><u>Eliminate Hyper-V BSOD: Steps to Restore Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-error-unable-to-terminate-process-phenomenon/"><u>Eliminating the 'Error: Unable to Terminate Process' Phenomenon</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-11-taskbar-chat-implications-unveiled/"><u>Eliminating Window's 11 Taskbar Chat: Implications Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/embark-on-cross-platform-development-via-windows-subsystem/"><u>Embark on Cross-Platform Development via Windows Subsystem</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-the-best-of-both-worlds-windows-11-macos-in-parallels/"><u>Embrace the Best of Both Worlds: Windows 11, MacOS in Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-convenience-using-googles-nearby-share/"><u>Embracing Convenience: Using Google's Nearby Share</u></a></li>
<li><a href="https://windows11.techidaily.com/emulate-macos-style-5-methods-to-revamp-windows/"><u>Emulate macOS Style: 5 Methods to Revamp Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enable-sd-card-view-in-file-explorer-puzzle-solved/"><u>Enable SD Card View in File Explorer Puzzle Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-application-guard-printing-for-windows-11-users/"><u>Enabling Application Guard Printing for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smooth-remote-play-via-windows-steam/"><u>Enabling Smooth Remote Play via Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-gaming-with-streamlined-directx-maintenance/"><u>Enhance PC Gaming with Streamlined DirectX Maintenance</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-epic-launcher-performance-a-how-to/"><u>Enhancing Epic Launcher Performance: A How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-mouse-cursor-prominence-in-windows-os/"><u>Enhancing Mouse Cursor Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-win11-boot-routines/"><u>Enhancing Performance: Win11 Boot Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-photos-step-by-step-background-elimination/"><u>Enhancing Photos: Step-by-Step Background Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-folder-management-custom-move-and-copy-commands-in-windows/"><u>Enriching Folder Management: Custom Move and Copy Commands in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-single-user-printer-operation-on-windows-11/"><u>Ensuring Single-User Printer Operation on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/error-2e-prevention-ensure-windows-update-works/"><u>Error 2E Prevention, Ensure Windows Update Works</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-6-tools-gpu-load-check-in-windows-environment/"><u>Essential 6 Tools: GPU Load Check in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s23-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S23 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premier-handwear-for-immersive-vr-experiences/"><u>In 2024, Premier Handwear for Immersive VR Experiences</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-future-frontiers-in-metaverse-with-top-8-gear/"><u>In 2024, Unveiling Future Frontiers in Metaverse with Top 8 Gear</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-merge-mov-files-for-free-5-best-options/"><u>New Merge MOV Files for Free 5 Best Options</u></a></li>
<li><a href="https://extra-skills.techidaily.com/racing-hearts-22-short-track-triumph-for-2024/"><u>Racing Hearts  '22 Short-Track Triumph for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/restoring-soundscape-troubleshooting-eg2s-missing-audio/"><u>Restoring Soundscape: Troubleshooting EG2's Missing Audio</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-maintain-anonymity-face-blurring-features-in-leading-video-editors-for-2024/"><u>Updated Maintain Anonymity Face Blurring Features in Leading Video Editors for 2024</u></a></li>
</ul></div>
