---
title: "Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall"
date: 2024-08-08T06:10:38.752Z
updated: 2024-08-09T06:10:38.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall"
excerpt: "This Article Describes Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall"
keywords: Win11 Mastery,Winstall Guide,Group Update Tips,Software Installation,Windows Ease-Up,Tech Upgrade Path,System Optimization
thumbnail: https://thmb.techidaily.com/9fc617880b7f763c252c5a9e983583a15e0501d81b43be135b81d00ad4f84b19.png
---

## Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall

 The latest builds of Windows 10 and 11 now get the Windows Package Manager (Winget) from Microsoft. Before Microsoft included it in the latest versions of its operating systems, Winget was just an experimental project only enthusiasts used. Or you had to use third-party apps, like Chocolatey, to install apps automatically on your PC.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

## What Is Winstall?

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Winstall home page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/winstall-home-page.jpg)

 Winstall is a website that outputs the exact Winget commands you need to run in the Terminal app to install various apps. What's groundbreaking about this service is that it provides the exact package name, ID, and commands for everything you need—you no longer have to scrounge up what you need from all over the internet.

 With that, you can easily use Winget [from Windows Terminal or PowerShell](https://www.makeuseof.com/windows-terminal-vs-powershell/) by copying and pasting the commands.

 The exact purpose of Winstall is to help you install not one but multiple apps at once. So, you don't have to wait for one installation to finish and then execute the next command. In addition, using a Graphic User Interface (GUI—[what is a GUI?](https://www.makeuseof.com/what-is-gui/)) to find apps and create packages is easy for the average Joe. You can find the available packages of popular apps you need or create your own packages.

 Currently, the Winstall app library has over 4,600+ app listings, all thanks to the efforts of Mehdi Hassan and other contributors who continue to find, list, and update package details of apps. It isn't as big as the Microsoft Store or Winget repository but still tries to include all the popular and requested apps on the portal.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Batch Install Apps in Windows 11 with Winstall

 Before batch-installing apps on your Windows 11 PC, remember that Winstall is a web portal that provides the complete Winget command to install one or many apps. It cannot directly install apps on your PC. For that, you need to run the generated commands in Command Prompt, PowerShell, as a batch file, or import as a .json file.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. How to Install Multiple Apps Using a Winstall App Pack

 Winstall app packs are pre-curated collections of apps you need on Windows 11\. There are essential packs, entertainment packs, browser packs, and more. Here's how to install a Winstall pack on your system:

1. Visit the [official Winstall website](https://winstall.app/) and scroll down to the **Featured Packs** section. You don't have to sign up to use the site.
2. Click on the app pack label. Alternatively, you can click on the **View Pack** option.  
![Install Multiple Apps Using a Winstall App Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack.jpg)
3. Now, click on the **Get Pack** button. This will scroll the page to the **Get the Pack** section at the bottom.  
![Install Multiple Apps Using a Winstall App Pack 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-2.jpg)

 Now, you can install the app pack in three ways: Batch, PowerShell, and Winget Import. You can [download and run the batch file](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) with administrator privileges on your system. Or, you can copy the batch file commands and run them in an elevated Command Prompt window.

 Similarly, you can run the PowerShell commands in an elevated PowerShell window. The command prompt code uses the "**&&**" operator to sequentially install multiple apps in one attempt, while the PowerShell code uses the "**;**" operator to achieve the same thing. Lastly, you can download the .json file containing the commands and import it using Winget to download all the packages on your PC.

 Here's how to use the Winstall commands to install multiple apps on your PC using the Command Prompt:

1. Select the **Batch** option and click on the **Advanced** options. Keep the **installation scope** unchecked.
2. Then select the **Silent installation** checkbox. It will hold back all the installer popups and automatically complete the installation with default options.
3. Click on the **Copy to clipboard** button to copy the generated code.  
![Install Multiple Apps Using a Winstall App Pack 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-3.jpg)
4. Now, press **Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** and press **Ctrl + Shift + Enter** keys to open the tool with administrator privileges.
5. Paste the copied code into the Command Prompt window and press the enter key to execute the code.  
![Install Multiple Apps Using a Winstall App Pack 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-4.jpg)
6. The commands will execute linearly and download and install the respective apps on your system. You won't have to click a button or interact with an installer window. After all the apps finish installation, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
### 2\. How to Install Multiple Apps Using a Custom App List in Winstall

 If you don't like the packs available on the Winstall packs section, you can create your custom collection or pack and then download and batch-install those apps. But you must pick at least five apps to create a pack and have to log in. Or you can use the Generate Script option to view the code to batch install the selected apps. Repeat the following steps:

1. Click on the **search bar** on the Winstall home page and type the app's name. Then click on the **+** icon to add the app to a pack.
2. Similarly, search and add more apps to the pack. There's no upper limit, but we will suggest batch-installing five apps in one session. If you encounter any error, finding and reattempting failed app installs will be easy.
3. Click on the **Generate Script** button. Like before, you will be redirected to a page with multiple options to install the app packages on your system.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
![Install Multiple Apps Using a Custom App List in Winstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall.jpg)
4. You can use the **Advanced options** section to enable the **silent installation** command while adding the selected packages. Then, click on the **Copy to Clipboard** button.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install Multiple Apps Using a Custom App List in Winstall 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-2.jpg)
5. [Open Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your system. Paste the copied code into it and press Enter to execute the code.  
![Install Multiple Apps Using a Custom App List in Winstall 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-3.jpg)
6. Wait for Winget to download and install each app and then close the Command Prompt window.

## Things to Remember While Using Winstall

 Using Winstall is pretty straightforward: you don't need to figure out the commands because it does that for you. It is also free, but you can donate to support the developers. However, the installation doesn't go smoothly as always, and it can be difficult to troubleshoot and reattempt the installation for an average user.

 However, you can avoid most of these issues by ensuring a few things:

* Ensure an uninterrupted internet connection while installing the apps using Winget.
* Update the Winget source if the utility fails to find the source file. Just run the Winget source update command, and it will update both the msstore and Winget source in one go.
* Always run the Command Prompt, PowerShell, or batch file with administrator privileges, or you could face issues while installing certain apps. Moreover, use the silent installation option (-h) with all Winget batch installs. It will save you the effort of interacting with the installer window.

 If you want to know more about Winget, you should check out [our Widows Package Manager guide](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Batch Installing Apps Is a Piece of Cake

 Opening Microsoft Store or your browser and manually searching for each app or program is exhausting. You can use Winstall to generate code to download and install multiple apps using Winget. Moreover, you can even sign in and create a pack on the website, so other users don't have to search for a specific collection of useful Windows 11 apps.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-audio-ambiance-for-visionaries-incorporating-youtube-music-wisely/"><u>[New] Audio Ambiance for Visionaries  Incorporating YouTube Music Wisely</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-vocal-lens-capture-microphone-inputs-for-2024/"><u>[New] Vocal Lens Capture  Microphone Inputs for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/outube-editing-tutorial-mastering-video-cuts/"><u>[New] YouTube Editing Tutorial  Mastering Video Cuts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-10-quick-diy-moviemaking-secrets-unveiled/"><u>[Updated] 10 Quick DIY Moviemaking Secrets Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-enhancing-visual-appeal-youtube-images-in-presentations/"><u>[Updated] In 2024, Enhancing Visual Appeal  YouTube Images in Presentations</u></a></li>
<li><a href="https://windows11.techidaily.com/13-ways-to-open-the-windows-system-settings/"><u>13 Ways to Open the Windows System Settings</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-laugh-loom-image-stitcher/"><u>2024 Approved  Laugh Loom  Image Stitcher</u></a></li>
<li><a href="https://windows11.techidaily.com/7-compelling-reasons-to-maintain-your-love-for-win10/"><u>7 Compelling Reasons to Maintain Your Love for Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/a-novel-approach-to-combining-data-units-on-windows-11/"><u>A Novel Approach to Combining Data Units on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adaptive-keystroke-configurations-for-windows-11-users/"><u>Adaptive Keystroke Configurations for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-data-loss-with-unresponsive-usb-drives-on-pc/"><u>Addressing Data Loss with Unresponsive USB Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccuracy-of-power-usage-predictor-on-win-11-devices/"><u>Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-no-connection-error-with-malwarebytes-in-win-1011/"><u>Addressing the “No Connection” Error with Malwarebytes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-disk-errors-with-ease-and-expertise/"><u>Addressing Windows Disk Errors with Ease and Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-windows-techniques-for-diverse-partition-merging/"><u>Advanced Windows Techniques for Diverse Partition Merging</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-pc-utorrent-transfer-rate-windows-edition-guide/"><u>Amplify PC uTorrent Transfer Rate - Windows Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-macos-capabilities-via-windows-applications/"><u>Augmenting macOS Capabilities via Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-heic-to-jpeg-images-in-windows-environment/"><u>Batch Heic to Jpeg Images in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-nvidias-windows-scanner-errors-today/"><u>Beat Nvidia's Windows Scanner Errors Today</u></a></li>
<li><a href="https://windows11.techidaily.com/beginner-friendly-steps-to-install-chrome-on-windows-11/"><u>Beginner-Friendly Steps to Install Chrome on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-elderly-friendly-window-pc-usability/"><u>Boosting Elderly-Friendly Window PC Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-linux-with-windows-technologies-and-features/"><u>Boosting Linux With Windows Technologies and Features</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-security-the-art-of-updating-gpo-in-windows/"><u>Boosting Security: The Art of Updating GPO in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-your-dormant-windows-mouse/"><u>Breathing Life Into Your Dormant Windows Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-user-not-valid-issues-in-windows-11-and-11/"><u>Bypassing 'User Not Valid' Issues in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/check-if-your-computer-meets-new-win11-criteria/"><u>Check if Your Computer Meets New Win11 Criteria</u></a></li>
<li><a href="https://windows11.techidaily.com/1719314513697-combat-snip-and-sketch-failures-a-guide-to-capturing-entire-display/"><u>Combat Snip & Sketch Failures: A Guide to Capturing Entire Display.</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-minimum-requirement-misfires-in-intel-hd-errors/"><u>Correcting Minimum Requirement Misfires in Intel HD Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-microsofts-store-0x800704cf-issue/"><u>Counteracting Microsoft's Store 0X800704CF Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-shortcuts-a-guide-for-winos-users/"><u>Crafting Shortcuts: A Guide for WinOS Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cryptographic-concealment-stashing-zip-files-undetected-on-windows-pcs/"><u>Cryptographic Concealment: Stashing Zip Files Undetected on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shifted-key-changes-from-windows-10-to-11/"><u>Desktop Dynamics Shifted: Key Changes From Windows 10 to 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-and-resolving-0x80072af9-hitches/"><u>Dissecting and Resolving 0X80072AF9 Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-digital-canvases-the-best-7-apps-for-win10-artists/"><u>Dive Into Digital Canvases: The Best 7 Apps for Win10 Artists</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-sony-vaio-system-drivers-seamless-compatibility-with-windows/"><u>Download & Install Sony VAIO System Drivers – Seamless Compatibility with Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Oppo Reno 10 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-tecno-spark-10-pro-frp-bypass-by-drfone-android/"><u>In 2024, About Tecno Spark 10 Pro FRP Bypass</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-irecorder-unleashed-a-review-revealed/"><u>In 2024, IRecorder Unleashed  A Review Revealed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jest-engineer-online/"><u>In 2024, Jest Engineer Online</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leading-cloud-services-for-android/"><u>In 2024, Leading Cloud Services for Android</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-livestream-quality-decision-opt-for-streamlabs-or-obs/"><u>In 2024, Livestream Quality Decision  Opt for Streamlabs or OBS?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-paper-jam-hp-print-fix-on-os-x/"><u>Overcoming Paper Jam: HP Print Fix on OS X</u></a></li>
<li><a href="https://technical-tips.techidaily.com/perfect-viewing-order-of-harry-potter-saga-a-comprehensive-list/"><u>Perfect Viewing Order of Harry Potter Saga - A Comprehensive List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premium-camcorder-brands-for-clear-footage-for-2024/"><u>Premium Camcorder Brands for Clear Footage for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719303910728-regain-shift-key-functionality-in-windows/"><u>Regain Shift Key Functionality in Windows.</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722773801949-stay-motivated-with-fitbit-versa-3s-inbuilt-gps-and-comprehensive-health-apps/"><u>Stay Motivated with Fitbit Versa 3'S Inbuilt GPS & Comprehensive Health Apps</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-vivo-x-fold-2-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Vivo X Fold 2? Here is How | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>