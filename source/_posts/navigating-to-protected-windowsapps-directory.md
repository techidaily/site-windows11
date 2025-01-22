---
title: Navigating to Protected WindowsApps Directory
date: 2025-01-15T19:24:36.028Z
updated: 2025-01-22T17:29:39.578Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Protected WindowsApps Directory
excerpt: This Article Describes Navigating to Protected WindowsApps Directory
keywords: Windows Apps Directory Guide,Accessing WindowsApps,WindowsApps Security Path,Navigate Windows Application,Safe Windows Apps Access,Windows Apps Directory Location,Protected Windows Apps Finder
thumbnail: https://thmb.techidaily.com/28b4424e01d4cc277a30d2dc85adec4230b241c9e861b58d7c8b2fd02e294cb8.jpg
---

## Navigating to Protected WindowsApps Directory

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the WindowsApps Folder?

 You can find the WindowsApps folder under the **C:\\Program Files** directory in Windows 10 and 11\. This folder has all the files related to UWP packages or Windows apps that you get from the Microsoft Store or that come preinstalled on Windows OS.

 The problem is that a basic Windows user or even a system administrator user account can't access or change the files in the folder. This is because it is owned by a Microsoft account named "TrustedInstaller." We've already covered [everything about TrustedInstaller](https://www.makeuseof.com/tag/what-is-trustedinstaller-and-why-does-it-keep-me-from-renaming-files/) and how to disable it in detail.

![WindowsApps Hidden Folder In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Hidden-Folder.jpg)

 Even if you uninstall or debloat some of the apps on Windows, the core application files are not removed from the WindowsApps folder. So, there are chances that such apps will reappear after a new Windows update.

 This is why we recommend using one of the [popular software uninstallers for Windows](http://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/). Because these tools not only uninstall an app completely but also clean up any leftovers and traces from all the secured folders.

 If you don't know what you're doing—modifying or deleting the files in the WindowsApps folder could cause system errors or even cause the Windows operating system to crash.

 There are many ways to access the WindowsApps folder and bypass the protection to gain access to the necessary files.

## Method 1\. How to Access WindowsApps via File Explorer

 You can easily find the WindowsApps folder in the Windows File Explorer by unhiding the respective folder first. However, to access the folder and make changes to the files—you need to gain some extra rights by changing the ownership.

 Follow these steps to view the WindowsApps folder first:

1. Open the Windows File Explorer (**Win + E**) and go to the **C:\\Program Files** directory.  
![Program Files Directory In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Program-Files-Directory-In-Explorer.jpg)
2. Now, click the **View** options button at the top of the File Explorer.

3. Click or hover over the **Show** button and select the **Hidden items** option to enable it.  
![File Explorer View Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/file-explorer-view-options.jpg)

 That's it. Now, you can see theWindowsApps folder in the same directory.

 If you try to open it, you'll see an information popup saying, "You have been denied permission." So, to actually access that folder and gain exclusive read and write rights—you've got to do a bit more.

### Change Ownership Properties to Get Access

 For the next steps, you need a user account with administrative rights. If you're a beginner, you must know [everything about the Administrator account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) to understand the steps better.

 Follow the steps mentioned below to change the ownership rights and access the required folder:

1. Select the **WindowsApps** folder and right-click on it.
2. Once the context menu appears, select **Properties** from the list. You can also use a quick shortcut to open the folder properties, i.e., **Alt + Enter**.  
![WindowsApps Properties Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Properties-Option.jpg)
3. Now, under the **Properties** window. Click the **Security** tab and then the **Advanced** option locatedright at the bottom.  

![WindowsApps Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Security-Properties.jpg)
4. Once you've opened the Advanced Security Settings window, click the **Change** text next to Owner.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Now, click **Advanced > Find Now > Administrator on the following screen**.  
![Advanced Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-properties.jpg)
6. Finally, click **OK** to select the Administrator as the owner and again **OK** to save the changes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![User Group Selection Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/User-Group-Selection-Window.jpg)
7. Then, tick the checkbox before the **Replace owner on sub containers and objects** text.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Now, click the **Apply** button, followed by the **OK** button, to initiate the process of transferring ownership.  
![WindowsApps Advanced Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Advanced-Security-Settings.jpg)
9. Once done, click the **OK** button on the next pop-up.

 If you followed the steps above to take ownership of the WindowsApps folder, you can now move or delete files from that folder.

 When you don't pause automatic software installations from the Microsoft store, the WindowsApps folder occupies a considerable bit of disc space. So, it becomes essential for you to access this folder once and check for the files that you no longer need.

 Moreover, you can also check out some [free tools for taking control of files and folders](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) on Windows. Such tools allow you to take full ownership of all your files and folders with a single click.

## Method 2\. How to Access WindowsApps via a PowerShell Command

 The File Explorer-based method is pretty complicated for a newbie. Use PowerShell to complete your job if you're looking for an easy-to-go method. Using Windows PowerShell is a pretty straightforward and automated way of doing the same thing.

 Follow these steps to access the WindowsApps folder using PowerShell:

 1\. Launch the Windows start menu or Windows search by pressing **Win + Q**.

 2\. Type in **PowerShell** and click the **Run as Administrator** option to run PowerShell with administrator rights. Besides, you must also know some other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) for future usage.

![PowerShell In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-In-Windows-Search.jpg)

 4\. In Powershell, run the following command and press the Enter key:

`takeown /f &ldquo;C:\Program Files\WindowsApps&rdquo; /r`

![Change Ownership Command In Shell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Change-Ownership-Command-In-Shell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The above command will restore all the files or folder ownership to the system administrator. It will take some time for your administrator user account to become the owner of the WindowsApps folder and everything in it.

 The access you gain by executing the above process is similar to that of the Windows File Explorer-based method. You have just automated the process and eliminated the unhiding of system files. Now, you can back up, clear some space, or make changes to the Windows apps' back-end files.

 If you're facing crashes while executing the file, make sure to check out some [effective ways to fix PowerShell crash errors](http://www.makeuseof.com/windows-powershell-has-stopped-working-error-fix/).

## 3\. How to Access WindowsApps via a Registry Hack

 There's another quick way to do the same thing with just a few steps. If you cannot use the PowerShell method stated above, you can use a simple registry hack to access the files in one go.

 Here's how you can take full ownership of the context menu for your files and folders and get to the WindowsApps folder:

1. Download the [Take Ownership registry](https://www.majorgeeks.com/files/details/take%5Ffull%5Fownership%5Fof%5Ffiles%5Ffolders%5Fregistry%5Fhack.html) file.
2. Extract the zip and open the **Add Take Ownership to Context menu** registry file.  
![Take Ownership Registry File In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Registry-File.jpg)
3. On the next screen, click **Yes** to add it to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, exit the popup by clicking **OK** and navigate to the **C:\\Program Files** directory.
5. Select the **WindowsApps** folder and right-click on it.
6. From the context menu, click the **Take Ownership** option.  
![Take Ownership Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Context-Menu.jpg)
7. In the Command Prompt, you must [give User Account Control Administrator rights](https://www.makeuseof.com/tag/user-account-control-windows-10/) for the registry hack to work. After that, please wait a few minutes for the window to close. Soon, it will display success messages constantly in the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once finished, you'll no longer face the "You've been denied permission" error on clicking the WindowsApps folder.

## Enjoy Unrestricted Access to the WindowsApps Folder

 Using one of the provided methods, you should now be able to view the hidden files and folders inside the WindowsApps folder. Now that you know everything about it, you can easily make changes to the UWP packages that are safe.

 Moreover, in the WindowsApps folder—you can remove Windows app remnants, open any software directly from the .EXE file, and inspect all removed packages, among other things.

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-cosmetics-confidentials-building-a-beauty-channel-on-youtube-for-2024/"><u>[New] Cosmetics Confidentials Building a Beauty Channel on YouTube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-fidelity-transformation-choosing-the-best-video-converters/"><u>[New] High Fidelity Transformation Choosing the Best Video Converters</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-home-film-expertise-in-a-flash-top-5-diy-tips-for-speed/"><u>[Updated] Home Film Expertise in a Flash Top 5 DIY Tips for Speed</u></a></li>
<li><a href="https://article-posts.techidaily.com/a-step-by-step-approach-to-incorporating-luts-in-obs-studio-projects-for-2024/"><u>A Step-by-Step Approach to Incorporating LUTs in OBS Studio Projects for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-blue-screens-resulting-from-unhandled-exceptions/"><u>How to Resolve Blue Screens Resulting From Unhandled Exceptions</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone 12 Pro Max?</u></a></li>
<li><a href="https://win-dash.techidaily.com/mastering-driver-upgrades-for-razer-blade-17-a-cross-platform-guide-for-windows-operating-systems/"><u>Mastering Driver Upgrades for Razer Blade 17 - A Cross-Platform Guide for Windows Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-internet-router-settings-on-windows-pc/"><u>Recovering Internet Router Settings on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/refining-malfunctional-fixes-within-windows-1011-diagnostics/"><u>Refining Malfunctional Fixes Within Windows 10/11 Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-is-here-windows-11-changes-to-file-explorer/"><u>The Future Is Here: Windows 11 Changes to File Explorer</u></a></li>
<li><a href="https://win-tricks.techidaily.com/top-ranked-reciprocal-sync-software-seamless-file-sharing-between-windows-11-8-and-7/"><u>Top-Ranked Reciprocal Sync Software: Seamless File Sharing Between Windows 11, 8 & 7</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbeatable-deal-for-gamers-discover-the-elite-speaker-system-with-30-off-at-amazon-featured-by-zdnet/"><u>Unbeatable Deal for Gamers: Discover the Elite Speaker System with 30% Off at Amazon, Featured by ZDNET</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-altering-win-11-proxy-settings/"><u>Understanding and Altering Win 11 Proxy Settings</u></a></li>
</ul></div>

