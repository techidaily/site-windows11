---
title: Streamline and Simplify Game Setup in Xbox App
date: 2024-08-15T15:56:22.960Z
updated: 2024-08-16T15:56:22.960Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline and Simplify Game Setup in Xbox App
excerpt: This Article Describes Streamline and Simplify Game Setup in Xbox App
keywords: Xbox Quick Setup,Streamlined Gaming,Easy Xbox Access,Xbox App Simplicity,Speed Up Game Start,Xbox Configurations,Faster Xbox Play
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Streamline and Simplify Game Setup in Xbox App

 The Xbox app lets you purchase and install games on any of your system drives. Usually, this process works well, but sometimes, the Xbox app won't let you install games in any location other than the default directory. This can be problematic, especially when you want to install a big-size game, but the default directory doesn't have enough space.

 Such situations usually arise due to corruption in the Xbox app or misconfigured registry settings. Fortunately, it's very easy to troubleshoot this problem. Here are some fixes to try when you can't choose a drive to install games on the Xbox app.

## 1\. Restart the Computer

![Restart option in Power menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart.jpg)

 You might fail to change the installation drive in the Xbox app due to a temporary system glitch or bug. Luckily, you can quickly eliminate such bugs and glitches by restarting your computer.

 To restart, press the**Alt + F4** hotkeys to open the Shut Down Windows prompt, click the drop-down icon, choose**Restart** from the context menu, and then click**OK.** After restart, launch the Xbox app and check if you can choose a different drive to install games. If not, then it's time to dive into the advanced troubleshooting methods.

## 2\. Change the Installation Directory in the Xbox App Settings

 There are two places from where you can change the installation drive on the Xbox app. One is while installing the game, whereas the other is the Xbox settings menu.

 If the first method is not working, you can use the second method to change the installation drive in the Xbox app. So, here's how to edit the Xbox app settings to change its default download location.

1. Launch the Xbox app, click on your profile in the top left corner, and choose**Settings** from the context menu.
2. Choose**General** from the left sidebar.
3. Click the**Change folder** option under**Change where this app installs games by default** .  
![Change Folder in Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
4. Choose the location where you want to install the game and then click the**Select Folder** option.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Customize the System Settings

 If editing the Xbox app settings wasn't helpful, you can edit the system settings and check if it makes a difference. Here's what you need to do:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Choose**System** from the left sidebar and then click on the**Storage** option in the right pane.
3. Click the drop-down icon next to**Advanced storage settings** and choose**Where new content** **is saved** option from the context menu.  
![Where new content is saved option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/where-new-content-is-saved.png)
4. Click the drop-down icon under the**New** **apps** **will save to** section, choose the drive where you want to install the game, and then click**Apply.**  
![New apps will save to section in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-apps-will-save-to-section.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->

 That's it! Restart your computer and check if the problem continues.

## 4\. Restart Important Xbox Services

![Restart Service option in Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-service.jpg)

 There are certain Xbox services that must be running for you to use the Xbox app properly. If any of these services fail to start properly, you might face the problem at hand.

 To fix that, restart each service manually. Here's how to do that:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. Type**services.msc** in the search bar and click OK.
3. In the Services window, locate and right-click on the following services and choose**Restart** from the context menu.  
`Xbox Accessory Management  
Xbox Live Game Save  
Xbox Live Auth Manager  
Xbox Live Networking Service`

## 5\. Reinstall the Gaming Services App

 The Gaming Services app allows you to seamlessly download apps and games from the Microsoft Store and the Xbox app. But if the app gets corrupt, you might face various issues, including the one in question.

 The solution, in this case, is to reinstall the Gaming Services app on your computer. You can do that by following the below instructions:

 Editing the registry can be dangerous, as one wrong edit can make your system unstable. To ensure that your data is secure even if something goes wrong,[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

1. Open the Run dialog box, type**regedit,** and click OK.
2. In the Registry Editor, navigate to the below location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
3. Right-click on the**GamingServices** folder in the left sidebar and choose**Delete** from the context menu.  
![Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-option.jpg)
4. Click**Yes** to confirm your selection.
5. Next, delete the**GamingServicesNet** folder as well in the left sidebar.

 Now, open the elevated PowerShell window (see how to [open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/) ), type the following command, and press**Enter** .

`Get-AppxPackage *gamingservices* -allusers | remove-appxpackage -allusers`

![Remove Gaming Services command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-gaming-services.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->

 After uninstalling the Gaming Services app, restart your computer. Then, open the Microsoft Store, search for and [download the Gaming Services](https://apps.microsoft.com/store/detail/gaming-services/9MWPM2CQNLHN?hl=en-us&gl=us) app again.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Repair the Xbox App

 It's very common for the Xbox app to get corrupt and throw various issues. The best way to remove corruption from the UWP apps like the Xbox app is to use the Windows repair feature.

 Check out [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) for information on how to do this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 7\. Update the Xbox App

 If repairing the Xbox app doesn't remove the corruption, consider updating the app. Downloading the latest update of the Xbox app will not only remove the corruption but also introduce new features.

To update the Xbox app, follow the below steps:

1. Open the Microsoft Store and click the**Library** option in the left sidebar.
2. Click the**Get updates** button to allow the Microsoft Store to search for available updates of the installed apps.

 The Microsoft Store will now automatically download updates for installed apps, including the Xbox app.

 While you're at installing updates, we'd also recommend [downloading any available Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . To do so, launch the Settings app, choose**Windows Update** from the left sidebar, and then click the**Check for Updates** button to install any available update on your computer. Following this, you will be able to choose a drive to install games on the Xbox app.

## Change the Download Location of the Xbox App

 The Xbox app is a great place to download your favorite games. However, the app might fail to change the installation location of games. Fortunately, you can quickly eliminate this issue by following the above fixes.

 Meanwhile, you might be interested to know how to increase downloading speed of the Xbox app.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-enhancing-ps3-playthroughs-a-guide-to-effective-capture/"><u>[New] Enhancing PS3 Playthroughs  A Guide to Effective Capture</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-advanced-mobile-mounting-accurate-camera-positioning/"><u>[New] In 2024, Advanced Mobile Mounting  Accurate Camera Positioning</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-renaming-your-podcast-leading-ai-generators-explored-for-2024/"><u>[New] Renaming Your Podcast  Leading AI Generators Explored for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-step-by-step-guide-embellishing-images-with-borders-on-instagram/"><u>[New] Step-by-Step Guide  Embellishing Images with Borders on Instagram</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-gateways-to-googles-advertising-on-youtube-platforms/"><u>[Updated] In 2024, Gateways to Google's Advertising on YouTube Platforms</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-stay-ahead-of-the-curve-with-iphone-and-androids-best-photo-sticker-apps/"><u>[Updated] Stay Ahead of the Curve with iPhone and Android's Best Photo Sticker Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-your-roadmap-to-acquiring-facebooks-esteemed-verification/"><u>[Updated] Your Roadmap to Acquiring Facebook’s Esteemed Verification</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-metaphorical-realities-30plus-inspirational-vr-expressions/"><u>2024 Approved  Metaphorical Realities  30+ Inspirational VR Expressions</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-driver-checks-in-windows-no-signatures-any-installation/"><u>Circumventing Driver Checks in Windows: No Signatures, Any Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-detox-revelations-from-a-no-snap-break/"><u>Digital Detox: Revelations From a No-Snap Break</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-instantly-generate-multiple-directories-in-modern-windows-environments/"><u>How to Instantly Generate Multiple Directories in Modern Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-11-tray-and-secret-icons/"><u>Illuminating Windows 11 Tray & Secret Icons</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-apple-iphone-13-without-itunes-drfone-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked Apple iPhone 13 Without iTunes | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-trouble-with-apple-iphone-6-swipe-up-try-these-11-solutions-by-drfone-ios/"><u>In 2024, Trouble with Apple iPhone 6 Swipe-Up? Try These 11 Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-execution-descriptor-labels-in-software/"><u>Leveraging Execution Descriptor Labels in Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-jdk-installation-for-windows-11-users/"><u>Mastering JDK Installation for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-avoid-and-fix-0x0-error-instantly/"><u>Mastering Win11: Avoid and Fix 0X0 Error Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-on-the-horizon-learning-classic-diablo/"><u>Mastery on the Horizon: Learning Classic Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/method-rectifying-disks-not-available-on-windows-pcs/"><u>Method: Rectifying Disks Not Available on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-pivoting-to-windows-11-in-place-strategies/"><u>Perfectly Pivoting to Windows 11: In-Place Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-disregard-the-your-license-will-end-alert/"><u>Procedures to Disregard the Your License Will End Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-troubleshooting-guide-no-audio-output-error/"><u>Quick Troubleshooting Guide: No Audio Output Error</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-cannot-open-error-on-closed-folders-in-microsoft-mail-for-pc/"><u>Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-game-locks-in-windows-environment/"><u>Resolving Steam Game Locks in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/reworking-default-view-of-task-manager-in-win11/"><u>Reworking Default View of Task Manager in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-pc-controlling-high-cpu-load-with-windows-resource-tool/"><u>Steady Your PC: Controlling High CPU Load With Window's Resource Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-discords-auto-activation-at-pc-boot-sequence/"><u>Stop Discord's Auto-Activation at PC Boot Sequence</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-for-dotnet-health-in-pcs-max-156/"><u>Swift Solutions for DotNet Health in PCs (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-fine-tuning-windows-11-alerts/"><u>The Art of Fine-Tuning Windows 11 Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-to-bluescreenview-execution/"><u>The Insider’s Guide to BlueScreenView Execution</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-fixes-for-errgfxstate-error-in-red-dead-redemption-2-step-by-step-guide/"><u>Ultimate Fixes for ERR_GFX_STATE Error in Red Dead Redemption 2 - Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-best-encoding-methods-on-pc/"><u>Understanding the Best Encoding Methods on PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleashing-the-magic-searching-for-photos-on-pexels-for-2024/"><u>Unleashing the Magic  Searching for Photos on Pexels for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-angle-game-rotate-images-in-6-steps-w11/"><u>Winning the Angle Game: Rotate Images in 6 Steps W11</u></a></li>
</ul></div>
