---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2025-02-24T03:57:55.730Z
updated: 2025-03-01T21:54:33.590Z
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

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  

![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-echoes-of-entertainment-adding-sound-to-snapchat-vids/"><u>[New] 2024 Approved Echoes of Entertainment Adding Sound to Snapchat Vids</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-modify-where-mac-photos-stash-location-for-2024/"><u>[New] Modify Where Mac Photos Stash Location for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-quirky-quotables-tailoring-hilarious-content-for-brief-videography/"><u>[Updated] 2024 Approved Quirky Quotables Tailoring Hilarious Content for Brief Videography</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-the-eternal-gallery-of-commons-artworks-online/"><u>[Updated] 2024 Approved The Eternal Gallery of Commons Artworks Online</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-becoming-a-confident-content-creator-youtubes-top-tips/"><u>[Updated] In 2024, Becoming a Confident Content Creator YouTube's Top Tips</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-get-the-latest-canon-tr1620-driver-update-for-your-printer-windows-friendly/"><u>How to Get the Latest Canon TR1620 Driver Update for Your Printer (Windows Friendly)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-methods-to-turn-off-life-360-on-vivo-x90s-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Methods to Turn off Life 360 On Vivo X90S without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-nokia-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Nokia Phone Hassle-Free</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-to-launch-outlook-preview/"><u>Navigating Through Windows 11 to Launch Outlook Preview</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-nvidia-connect-attempts-on-windows-11-pcs/"><u>Overcoming Failed Nvidia Connect Attempts on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-empty-folder-puzzle-in-win-11/"><u>Overcoming the Empty Folder Puzzle in Win 11</u></a></li>
<li><a href="https://facebook.techidaily.com/preserving-page-harmony-the-art-of-excluding-profiles/"><u>Preserving Page Harmony: The Art of Excluding Profiles</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-retrieve-content-from-a-shared-windows-space/"><u>Seamlessly Retrieve Content From a Shared Windows Space</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-reactivate-windows-11s-silent-wireless-hotspot/"><u>Strategies to Reactivate Windows 11'S Silent Wireless Hotspot</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-concealment-start-menu-command-hideout/"><u>The Art of Concealment: Start Menu Command Hideout</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essentials-for-selecting-a-win-pc-a-must-know-guide/"><u>Top Essentials for Selecting a Win PC: A Must-Know Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-solutions-for-unzipped-files-woes/"><u>Win 11: Solutions for Unzipped Files Woes</u></a></li>
</ul></div>

