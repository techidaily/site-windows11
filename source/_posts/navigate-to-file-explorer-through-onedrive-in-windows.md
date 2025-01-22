---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2025-01-20T20:20:41.064Z
updated: 2025-01-22T19:44:58.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to File Explorer Through OneDrive in Windows
excerpt: This Article Describes Navigate to File Explorer Through OneDrive in Windows
keywords: Navigate to DFexplorer,OneDrive Explore Files,File Explorer Access,Windows OneDrive View,Direct Explorer Opening,Quick OneDrive Explorer,OneDrive Navigate Explorer
thumbnail: https://thmb.techidaily.com/9ad9147e4fbb8c24ccda197a0486be5c1d9c044a46c11534bd2a1352ab33e591.png
---

## Navigate to File Explorer Through OneDrive in Windows

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  

![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-the-six-secrets-to-holding-your-viewers-attention/"><u>[New] 2024 Approved The Six Secrets to Holding Your Viewers' Attention</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/log-verily-tips-and-taboos-in-the-daily-digital-sphere-for-2024/"><u>[New] Vlog Verily Tips and Taboos in the Daily Digital Sphere for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-clearing-process-for-youtubes-pending-video-list/"><u>[Updated] 2024 Approved Clearing Process for YouTube's Pending Video List</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-art-of-selective-engagement-on-ig/"><u>[Updated] 2024 Approved The Art of Selective Engagement on IG</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722978060906-ace-your-gaming-session-secure-acer-predator-xb271h-ultimate-drivers-without-delay/"><u>Ace Your Gaming Session: Secure Acer Predator XB271H Ultimate Drivers Without Delay</u></a></li>
<li><a href="https://win-advanced.techidaily.com/facile-duplication-de-commentaires-pour-windows-server-2019-guide-ultime/"><u>Facile Duplication De Commentaires Pour Windows Server 2019: Guide Ultime</u></a></li>
<li><a href="https://windows11.techidaily.com/fortifying-win-connections-for-uninterrupted-surfing/"><u>Fortifying Win Connections for Uninterrupted Surfing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-elevating-engagement-the-pillars-of-youtube-rankings/"><u>In 2024, Elevating Engagement The Pillars of YouTube Rankings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-huawei-nova-y71-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Huawei Nova Y71 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/old-habits-die-hard-reasons-for-sticking-with-windows-10/"><u>Old Habits Die Hard – Reasons for Sticking with Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-seamless-connectivity-with-fall-guys-windows-edition/"><u>Restoring Seamless Connectivity with Fall Guys (Windows Edition)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-unplugging-epic-from-win-11-pcs/"><u>Step-By Step Guide: Unplugging Epic From Win 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-deactivating-hyper-v-win11/"><u>Techniques for Deactivating Hyper-V Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-a-missing-graphics-driver/"><u>Unraveling the Mystery of a Missing Graphics Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-truth-behind-windows-activation-error-0x8007251d/"><u>Unveiling the Hidden Truth Behind Windows Activation Error 0X8007251D</u></a></li>
</ul></div>

