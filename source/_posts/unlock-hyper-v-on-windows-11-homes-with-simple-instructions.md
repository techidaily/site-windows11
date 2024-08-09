---
title: Unlock Hyper-V on Windows 11 Homes with Simple Instructions
date: 2024-08-08T06:15:34.870Z
updated: 2024-08-09T06:15:34.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Hyper-V on Windows 11 Homes with Simple Instructions
excerpt: This Article Describes Unlock Hyper-V on Windows 11 Homes with Simple Instructions
keywords: Windows 11 Hyper-V Guide,Enable Hyper-V Easy Steps,Hyper-V Activation Procedure,Unlocking Hyper-V Homes,Instructional Hyper-V Setup,Simplify Hyper-V on WS11,Hyper-V Installation Windows 11
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Unlock Hyper-V on Windows 11 Homes with Simple Instructions

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Disable Hyper-V on Windows 11 Home

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-explore-the-8-premier-zero-cost-video-editors-for-social-media-pros/"><u>[New] 2024 Approved  Explore the 8 Premier Zero-Cost Video Editors for Social Media Pros</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-get-going-on-youtube-video-upload-tutorial-in-premiere/"><u>[New] 2024 Approved  Get Going on YouTube  Video Upload Tutorial in Premiere</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-5-rapid-setup-techniques-for-home-cinematography/"><u>[New] Best 5 Rapid Setup Techniques for Home Cinematography</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-best-yt-storytellers-for-enthralling-viewing-experience/"><u>[New] Best YT Storytellers for Enthralling Viewing Experience</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-power-of-words-in-marketing-top-20-essentials/"><u>[New] The Power of Words in Marketing - Top 20 Essentials</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-achieve-cinematic-brilliance-the-11-ultimate-tutorials-on-color-grading/"><u>[Updated] 2024 Approved  Achieve Cinematic Brilliance  The 11 Ultimate Tutorials on Color Grading</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-leading-edits-the-10-best-video-apps/"><u>[Updated] Leading Edits  The 10 Best Video Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-mastering-your-influence-amidst-changing-social-media-ecosystem/"><u>[Updated] Mastering Your Influence Amidst Changing Social Media Ecosystem</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-mastering-easy-hdr-a-step-by-step-guide/"><u>2024 Approved  Mastering Easy HDR  A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-using-w11s-auto-hdr/"><u>A Comprehensive Guide to Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/activatingdeactivating-windows-setup-service-on-pcs/"><u>Activating/Deactivating Windows Setup Service on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-hardware-utilization-four-ways-to-open-the-disk-manager-in-windows-11/"><u>Boost Hardware Utilization: Four Ways to Open the Disk Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-lock-screen-swiftly/"><u>Bypass Windows 11 Lock Screen Swiftly</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-meizu-21-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Meizu 21 Pro</u></a></li>
<li><a href="https://fox-direct.techidaily.com/comprehensive-guide-to-addressing-red-dead-redemption-2s-pc-crashes-and-bugs/"><u>Comprehensive Guide to Addressing Red Dead Redemption 2'S PC Crashes and Bugs</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-failed-office-activation-on-pcs-and-laptops/"><u>Conquering Failed Office Activation on PCs and Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-batched-taskbar-visual-elements/"><u>Correcting Batched Taskbar Visual Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-photo-management-software/"><u>Cutting-Edge Windows Photo Management Software</u></a></li>
<li><a href="https://windows11.techidaily.com/decorating-windows-11-with-a-christmas-twist/"><u>Decorating Windows 11 with a Christmas Twist</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/directing-youtube-and-twitter-videos-via-whatsapp-messages/"><u>Directing YouTube & Twitter Videos via WhatsApp Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/dont-relininas-chatbots-for-secure-authenticated-win-11-keys/"><u>Don't Relininas Chatbots for Secure, Authenticated Win 11 Keys</u></a></li>
<li><a href="https://driver-install.techidaily.com/elevate-performance-essential-win10-drivers-for-yoga-900s/"><u>Elevate Performance: Essential Win10 Drivers for Yoga 900S</u></a></li>
<li><a href="https://fox-helps.techidaily.com/emblem-of-success-create-and-tailor-professional-logos-with-free-models-for-2024/"><u>Emblem of Success  Create & Tailor Professional Logos with Free Models for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-microsoft-store-app-on-win11-pcs/"><u>Enabling Microsoft Store App on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-innovation-best-windows-devices-for-24/"><u>Exploring Innovation - Best Windows Devices for '24</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-address-missing-windows-1011-search-data/"><u>Guidelines to Address Missing Windows 10/11 Search Data</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-honor-90-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Honor 90 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-the-home-section-in-the-settings-app-in-windows-11/"><u>How to Enable the Home Section in the Settings App in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-of-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-iphone-xs-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your iPhone XS without Security Questions?</u></a></li>
<li><a href="https://apple-account.techidaily.com/icloud-separation-how-to-disconnect-apple-iphone-se-and-ipad-by-drfone-ios/"><u>iCloud Separation How To Disconnect Apple iPhone SE and iPad</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-repairs-how-to-tackle-post-windows-update-glitches/"><u>Immediate Repairs: How to Tackle Post-Windows Update Glitches</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-xiaomi-redmi-note-13-proplus-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Xiaomi Redmi Note 13 Pro+ 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-apple-iphone-xs-max-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to Apple iPhone XS Max iCloud Bypass</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leveraging-viewership-the-mechanics-of-product-sponsored-youtube-videos/"><u>In 2024, Leveraging Viewership  The Mechanics of Product-Sponsored YouTube Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-evolution-of-drone-remote-control-systems-syma-x8c/"><u>In 2024, The Evolution of Drone Remote Control Systems – Syma X8C</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/learn-how-to-share-your-winning-forex-trades-with-friends-and-family-on-local-trade-copier-tm-together-by-mt4copier-guide/"><u>Learn how to Share Your Winning Forex Trades With Friends and Family on Local Trade Copier™ Together</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leveraging-chatgpt-to-establish-and-reach-your-personal-health-goals-efficiently/"><u>Leveraging ChatGPT to Establish and Reach Your Personal Health Goals Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-fixing-disk-read-errors/"><u>Master the Art of Fixing Disk Read Errors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-metaai-integration-on-instagram-step-by-step-guide/"><u>Mastering MetaAI Integration on Instagram: Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-fix-strategies-for-handling-missing-coredll-files/"><u>Mastering the Fix: Strategies for Handling Missing core.dll Files</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-fingertip-writing-options-in-windows-system/"><u>Navigate Through Fingertip Writing Options in Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-package-control-with-winget-on-win11/"><u>Navigating Package Control with Winget on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-snipeater-glitches-fix-strategies-here/"><u>Navigating SnipEater Glitches: Fix Strategies Here</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unbiased-review-vn-video-editor-pros-features-and-performance-for-2024/"><u>New Unbiased Review VN Video Editor Pros Features and Performance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/paramount-procedures-for-wiping-your-windows-installation/"><u>Paramount Procedures for Wiping Your Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-proliferate-elevating-notifications-in-windows-11/"><u>Prioritize and Proliferate: Elevating Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-spooler/"><u>Reinitializing Windows' Spooler</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-a-non-functional-windows-taskbar/"><u>Reinvigorating a Non-Functional Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-your-screen-quickly-when-black-hits/"><u>Reset Your Screen Quickly When Black Hits</u></a></li>
<li><a href="https://windows11.techidaily.com/set-your-desktops-mood-with-spotlight-controls/"><u>Set Your Desktop's Mood with Spotlight Controls</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/silent-blades-and-righteous-honor-your-next-game-adventure-awaits-in-2024/"><u>Silent Blades & Righteous Honor  Your Next Game Adventure Awaits, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-pcs-protection-the-firewall-guide/"><u>Tailoring Your PC's Protection: The Firewall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-guide-to-getting-most-out-of-windows-11s-startup-screen/"><u>The Comprehensive Guide to Getting Most Out of Windows 11'S Startup Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-in-vintage-gear-installation-of-22h2-win11/"><u>Unleash Potential in Vintage Gear: Installation of 22H2 Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mystery-of-yourphoneexe-in-w10/"><u>Unveiling the Mystery of YourPhoneExe in W10</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-overcome-directdraw-challenges-in-11-series-windows/"><u>Unveiling the Secrets to Overcome DirectDraw Challenges in 11-Series Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/what-makes-users-grumble-in-windows-11/"><u>What Makes Users Grumble in Windows 11?</u></a></li>
<li><a href="https://windows11.techidaily.com/window-brightness-prodigies-a-list-of-premier-tools-for-multiscreeners/"><u>Window Brightness Prodigies: A List of Premier Tools for Multiscreeners</u></a></li>
<li><a href="https://windows11.techidaily.com/1719268966849-windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure!</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-workplace-presentations-fixing-powerpoints-print-problems-in-windows/"><u>Winning at Workplace Presentations: Fixing PowerPoint's Print Problems in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>