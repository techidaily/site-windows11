---
title: "Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11"
date: 2025-01-28T06:41:10.907Z
updated: 2025-01-29T21:29:49.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11"
excerpt: "This Article Describes Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11"
keywords: Win10PhotopackageTroubleshooting,FixPhotoErrorWindowsOS,ResolveWin11ImagePack,PhotoCorrectionTipsWin10,WindowsPhotoFixGuide,OptimizeWin10Pics,EliminateWinErrorsPhotos
thumbnail: https://thmb.techidaily.com/f75585e4daf78953dd0ce1cfd0b26209fab1e9c588003fe7de564148a8e3e23c.jpg
---

## Avoiding Disruption: Correcting Photo Package Issues on Windows 10/11

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-the-definitive-guide-for-choosing-best-youtube-visual-elements/"><u>[Updated] 2024 Approved The Definitive Guide for Choosing Best YouTube Visual Elements</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-optimal-tools-for-high-quality-zoom-recordings/"><u>[Updated] In 2024, Optimal Tools for High-Quality Zoom Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/1-crafting-personalized-borders-in-excel-a-step-by-step-guide/"><u>1. Crafting Personalized Borders in Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/avoiding-and-fixing-cities-skylines-stability-issues-expert-advice/"><u>Avoiding and Fixing Cities: Skylines Stability Issues - Expert Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-microsoft-excels-innovative-integration-of-chatgpt-technology-for-enhanced-productivity/"><u>Discover Microsoft Excel's Innovative Integration of ChatGPT Technology for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-changing-sheet-names-in-microsoft-excel/"><u>Easy Steps for Changing Sheet Names in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-methods-to-modify-text-casing-in-microsoft-excel-2013-with-built-in-formulae/"><u>Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-razer-naga-software-updates-for-your-computer-running-windows/"><u>Get the Newest Razer Naga Software Updates for Your Computer Running Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-x-flip-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo X Flip phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-creating-and-personalizing-your-own-signature-block-in-excel/"><u>Step-by-Step Guide: Creating & Personalizing Your Own Signature Block in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-generating-word-mailing-labels-using-your-excel-spreadsheet/"><u>Step-by-Step Guide: Generating Word Mailing Labels Using Your Excel Spreadsheet</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-overcoming-airpod-connection-errors-on-windows-11-latest-techniques/"><u>Step-by-Step Guide: Overcoming AirPod Connection Errors on Windows 11 - Latest Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-on-leveraging-sumif-in-excel-techniques-and-strategies-for-effective-data-analysis/"><u>The Ultimate Tutorial on Leveraging SUMIF in Excel: Techniques and Strategies for Effective Data Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-productivity-microsoft-office-suite-available-in-immersive-quest-vr-experience/"><u>Transform Your Productivity: Microsoft Office Suite Available in Immersive Quest VR Experience!</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/troubleshooting-origin-failure-to-start-in-windows-11-environment/"><u>Troubleshooting 'Origin' Failure to Start in Windows 11 Environment</u></a></li>
<li><a href="https://win-online.techidaily.com/youtube-movavi/"><u>YouTube 동영상에 대한 효과적인 조정: Movavi의 도전</u></a></li>
</ul></div>

