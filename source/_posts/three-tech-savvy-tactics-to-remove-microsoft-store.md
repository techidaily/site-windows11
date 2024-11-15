---
title: Three Tech-Savvy Tactics to Remove Microsoft Store
date: 2024-11-11T17:23:20.608Z
updated: 2024-11-15T17:14:00.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Tech-Savvy Tactics to Remove Microsoft Store
excerpt: This Article Describes Three Tech-Savvy Tactics to Remove Microsoft Store
keywords: Microsoft Store Removal,Tech Tips,MSIStore Deletion Guide,Quick Fixes for MS Store Exit,Get Rid of Microsoft Store,Tactics to Uninstall MS Apps,Eliminate MS From PC
thumbnail: https://thmb.techidaily.com/87eef5cf587ac33a0581d68baadab4d33ca4c311a823a65d146f4fbbcbf04745.jpg
---

## Three Tech-Savvy Tactics to Remove Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://extra-information.techidaily.com/new-basics-of-engaging-narratives/"><u>[New] Basics of Engaging Narratives</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-tailoring-content-advanced-pc-video-editing-methods-for-youtube/"><u>[Updated] 2024 Approved Tailoring Content Advanced PC Video Editing Methods for YouTube</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-8-drfone-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Poco C55? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-iphone-14-plus-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 14 Plus Without a Home Button</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-kinemasters-journey-through-seamless-segmentation/"><u>In 2024, Kinemaster's Journey Through Seamless Segmentation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
</ul></div>

