---
title: "Mastering Batch Installs: Windows 11 with Winstall"
date: 2024-07-29T04:20:46.155Z
updated: 2024-07-30T04:20:46.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Batch Installs: Windows 11 with Winstall"
excerpt: "This Article Describes Mastering Batch Installs: Windows 11 with Winstall"
keywords: Win11 Winstall Mastery,Batch Install Windows Pro,Efficient Winstall Guide,Simplified Winstall Process,Advanced Windows Setup,Quick Windows Installs,Winstall Techniques for 11
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## Mastering Batch Installs: Windows 11 with Winstall

 The latest builds of Windows 10 and 11 now get the Windows Package Manager (Winget) from Microsoft. Before Microsoft included it in the latest versions of its operating systems, Winget was just an experimental project only enthusiasts used. Or you had to use third-party apps, like Chocolatey, to install apps automatically on your PC.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

## What Is Winstall?

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Winstall home page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/winstall-home-page.jpg)

 Winstall is a website that outputs the exact Winget commands you need to run in the Terminal app to install various apps. What's groundbreaking about this service is that it provides the exact package name, ID, and commands for everything you need—you no longer have to scrounge up what you need from all over the internet.

 With that, you can easily use Winget [from Windows Terminal or PowerShell](https://www.makeuseof.com/windows-terminal-vs-powershell/) by copying and pasting the commands.

 The exact purpose of Winstall is to help you install not one but multiple apps at once. So, you don't have to wait for one installation to finish and then execute the next command. In addition, using a Graphic User Interface (GUI—[what is a GUI?](https://www.makeuseof.com/what-is-gui/)) to find apps and create packages is easy for the average Joe. You can find the available packages of popular apps you need or create your own packages.

 Currently, the Winstall app library has over 4,600+ app listings, all thanks to the efforts of Mehdi Hassan and other contributors who continue to find, list, and update package details of apps. It isn't as big as the Microsoft Store or Winget repository but still tries to include all the popular and requested apps on the portal.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## How to Batch Install Apps in Windows 11 with Winstall

 Before batch-installing apps on your Windows 11 PC, remember that Winstall is a web portal that provides the complete Winget command to install one or many apps. It cannot directly install apps on your PC. For that, you need to run the generated commands in Command Prompt, PowerShell, as a batch file, or import as a .json file.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. How to Install Multiple Apps Using a Winstall App Pack

 Winstall app packs are pre-curated collections of apps you need on Windows 11\. There are essential packs, entertainment packs, browser packs, and more. Here's how to install a Winstall pack on your system:

1. Visit the [official Winstall website](https://winstall.app/) and scroll down to the **Featured Packs** section. You don't have to sign up to use the site.
2. Click on the app pack label. Alternatively, you can click on the **View Pack** option.  
![Install Multiple Apps Using a Winstall App Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack.jpg)
3. Now, click on the **Get Pack** button. This will scroll the page to the **Get the Pack** section at the bottom.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![Install Multiple Apps Using a Winstall App Pack 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-4.jpg)
6. The commands will execute linearly and download and install the respective apps on your system. You won't have to click a button or interact with an installer window. After all the apps finish installation, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. How to Install Multiple Apps Using a Custom App List in Winstall

 If you don't like the packs available on the Winstall packs section, you can create your custom collection or pack and then download and batch-install those apps. But you must pick at least five apps to create a pack and have to log in. Or you can use the Generate Script option to view the code to batch install the selected apps. Repeat the following steps:

1. Click on the **search bar** on the Winstall home page and type the app's name. Then click on the **+** icon to add the app to a pack.
2. Similarly, search and add more apps to the pack. There's no upper limit, but we will suggest batch-installing five apps in one session. If you encounter any error, finding and reattempting failed app installs will be easy.
3. Click on the **Generate Script** button. Like before, you will be redirected to a page with multiple options to install the app packages on your system.  
![Install Multiple Apps Using a Custom App List in Winstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall.jpg)
4. You can use the **Advanced options** section to enable the **silent installation** command while adding the selected packages. Then, click on the **Copy to Clipboard** button.  
![Install Multiple Apps Using a Custom App List in Winstall 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-2.jpg)
5. [Open Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your system. Paste the copied code into it and press Enter to execute the code.  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install Multiple Apps Using a Custom App List in Winstall 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-3.jpg)
6. Wait for Winget to download and install each app and then close the Command Prompt window.

## Things to Remember While Using Winstall

 Using Winstall is pretty straightforward: you don't need to figure out the commands because it does that for you. It is also free, but you can donate to support the developers. However, the installation doesn't go smoothly as always, and it can be difficult to troubleshoot and reattempt the installation for an average user.

 However, you can avoid most of these issues by ensuring a few things:

* Ensure an uninterrupted internet connection while installing the apps using Winget.
* Update the Winget source if the utility fails to find the source file. Just run the Winget source update command, and it will update both the msstore and Winget source in one go.
* Always run the Command Prompt, PowerShell, or batch file with administrator privileges, or you could face issues while installing certain apps. Moreover, use the silent installation option (-h) with all Winget batch installs. It will save you the effort of interacting with the installer window.

 If you want to know more about Winget, you should check out [our Widows Package Manager guide](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/).

## Batch Installing Apps Is a Piece of Cake

 Opening Microsoft Store or your browser and manually searching for each app or program is exhausting. You can use Winstall to generate code to download and install multiple apps using Winget. Moreover, you can even sign in and create a pack on the website, so other users don't have to search for a specific collection of useful Windows 11 apps.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-incorporating-live-streaming-your-ultimate-website-guide/"><u>[New] 2024 Approved  Incorporating Live Streaming  Your Ultimate Website Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-ultimate-guide-to-iphoneipad-recording/"><u>[New] 2024 Approved  The Ultimate Guide to iPhone/iPad Recording</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-win10s-best-practices-for-gaming-video-capture/"><u>[New] 2024 Approved  Win10's Best Practices for Gaming Video Capture</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-addressing-missing-thumbnails-in-youtube-shorts-for-2024/"><u>[New] Addressing Missing Thumbnails in YouTube Shorts for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-detailed-protocols-for-filming-films-across-multiplatform-systems/"><u>[New] In 2024, Detailed Protocols for Filming Films Across Multiplatform Systems</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-ultimate-windows-and-cross-platform-videography-tools-guide/"><u>[Updated] In 2024, Ultimate Windows & Cross-Platform Videography Tools Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-clean-up-your-firewall-rules/"><u>10 Ways to Clean Up Your Firewall Rules</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-professional-acid-pro-analysis-and-substitutes/"><u>2024 Approved  Professional ACID Pro Analysis and Substitutes</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-samsung-galaxy-f15-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/7-compelling-reasons-to-maintain-your-love-for-win10/"><u>7 Compelling Reasons to Maintain Your Love for Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/a-novel-approach-to-combining-data-units-on-windows-11/"><u>A Novel Approach to Combining Data Units on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-to-new-gear-your-powertoys-configuration-guide/"><u>Adapting To New Gear: Your PowerToys Configuration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/adaptive-keystroke-configurations-for-windows-11-users/"><u>Adaptive Keystroke Configurations for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-steam-vac-denial-for-gaming-sessions/"><u>Addressing Steam VAC Denial for Gaming Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-photos-problem-package-not-registered/"><u>Addressing Windows Photos Problem - Package Not Registered</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-windows-techniques-for-diverse-partition-merging/"><u>Advanced Windows Techniques for Diverse Partition Merging</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-pc-utorrent-transfer-rate-windows-edition-guide/"><u>Amplify PC uTorrent Transfer Rate - Windows Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-macos-capabilities-via-windows-applications/"><u>Augmenting macOS Capabilities via Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unable-to-start-application-error-xc000003e-in-windows-11/"><u>Avoiding Unable to Start Application Error Xc000003e in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-vscode-shutdown-troubles-in-new-os/"><u>Avoiding VSCode Shutdown Troubles in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/become-a-windows-wizard-learn-essential-shortcut-commands/"><u>Become a Windows Wizard: Learn Essential Shortcut Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-elderly-friendly-window-pc-usability/"><u>Boosting Elderly-Friendly Window PC Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-security-the-art-of-updating-gpo-in-windows/"><u>Boosting Security: The Art of Updating GPO in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/brighten-and-sharpen-expert-tips-for-v22-video-enhancement/"><u>Brighten and Sharpen  Expert Tips for V2.2 Video Enhancement</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/broadcasting-with-gopro-tips-for-facebookperiscope-integration-for-2024/"><u>Broadcasting with GoPro  Tips for Facebook/Periscope Integration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-office-activation-barriers-on-desktops/"><u>Circumventing Office Activation Barriers on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-advanced-windows-index-features/"><u>Configuring Advanced Windows Index Features</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-immediate-failure-effective-strategies-to-tackle-onedrive-folder-issues-on-pc/"><u>Conquering Immediate Failure: Effective Strategies to Tackle OneDrive Folder Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/critiquing-7-perplexing-windows-11-aesthetics/"><u>Critiquing 7 Perplexing Windows 11 Aesthetics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/decoding-photopeas-art-of-backdrop-elimination/"><u>Decoding Photopea's Art of Backdrop Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shifted-key-changes-from-windows-10-to-11/"><u>Desktop Dynamics Shifted: Key Changes From Windows 10 to 11</u></a></li>
<li><a href="https://windows11.techidaily.com/differences-between-cloud-based-windows-installations/"><u>Differences Between Cloud-Based Windows Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/1719299682478-enhancing-productivity-with-cloud-services-dropboxgoogle-on-c/"><u>Enhancing Productivity with Cloud Services: Dropbox/Google on C</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/essential-tips-for-game-recording-on-windows-10-for-2024/"><u>Essential Tips for Game Recording on Windows 10 for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/expert-insights-for-effective-clips-blending-for-2024/"><u>Expert Insights for Effective Clips Blending for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-to-completely-erase-data-on-iphone-11-pro-max-to-avoid-privacy-leak-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Guide to Completely Erase Data on iPhone 11 Pro Max to Avoid Privacy Leak | Stellar</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-asus-rog-phone-8-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Asus ROG Phone 8 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-poco-f5-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Poco F5 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-samsung-galaxy-f34-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Samsung Galaxy F34 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/live-viewing-archive/"><u>Live Viewing Archive</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-5-best-video-editors-for-avchd-files/"><u>New 2024 Approved The 5 Best Video Editors for AVCHD Files</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-tips-efficiently-post-videos-on-igtv-for-2024/"><u>Quick Tips  Efficiently Post Videos on IGTV for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719303910728-regain-shift-key-functionality-in-windows/"><u>Regain Shift Key Functionality in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293537225-resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-and-score-top-techniques-for-great-youtube-cinematography/"><u>Shoot and Score  Top Techniques for Great YouTube Cinematography</u></a></li>
</ul></div>