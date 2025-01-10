---
title: Customizing Quick Access to Start From OneDrive
date: 2025-01-05T17:02:20.158Z
updated: 2025-01-10T21:24:50.767Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Quick Access to Start From OneDrive
excerpt: This Article Describes Customizing Quick Access to Start From OneDrive
keywords: Dashboard QuickAccess Customize,QuickStart OneDrive Personalization,OneDrive Custom Quick Access Setup,Streamline OneDrive Navigation,Personalized OneDrive Start Point,Efficient OneDrive Initial View,Tailored OneDrive Accessibility
thumbnail: https://thmb.techidaily.com/71f657792ad13f84286b1544671aaf8455260b87c02f1f22e6d755ac15543040.jpg
---

## Customizing Quick Access to Start From OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-essential-screen-recording-tools-a-comprehensive-educators-guide-for-2024/"><u>[New] Essential Screen Recording Tools A Comprehensive Educator's Guide for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-discover-10-premium-video-players-for-ultimate-hd-vids-android/"><u>[Updated] In 2024, Discover 10 Premium Video Players for Ultimate HD Vids, Android</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-prime-pickups-for-novice-gopro-owners-for-2024/"><u>[Updated] Prime Pickups for Novice GoPro Owners for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-smooth-operation-installing-missing-hardware-drivers-on-your-new-windows-11-computer/"><u>Ensure Smooth Operation: Installing Missing Hardware Drivers on Your New Windows 11 Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-xbox-game-pass-0x800700e9-error-in-windows-11-os/"><u>Fixing Xbox Game Pass 0X800700E9 Error in Windows 11 OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-samsung-galaxy-a15-5g-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Samsung Galaxy A15 5G Face Lock?</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1424577-9781780284651-heal-your-spirit-heal-yourself/"><u>Heal Your Spirit, Heal Yourself | Free Book</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Infinix Hot 40? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-slideshow-and-spot-fix-in-the-windows-11-photos-app/"><u>How to Use Slideshow and Spot Fix in the Windows 11 Photos App</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-open-library-legal-gaming-tracks-downloadable/"><u>In 2024, Open Library Legal Gaming Tracks Downloadable</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-system-how-to-reinitialize-windows-11-programs/"><u>Resetting the System: How to Reinitialize Windows 11 Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-android-studio-tasks-on-windows-os/"><u>Speeding Up Android Studio Tasks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-windows-media-player-launch/"><u>Step-by-Step Guide to Windows Media Player Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-interface-not-recognized-a-win-to-success-guide/"><u>Troubleshoot 'Interface Not Recognized': A Win to Success Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-blocked-functionality-of-ccleaner-on-win11/"><u>Unblocking Blocked Functionality of CCleaner on Win11</u></a></li>
</ul></div>

