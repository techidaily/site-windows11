---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2024-10-14T22:31:20.200Z
updated: 2024-10-18T21:28:53.737Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-get-unlimited-echoes-for-online-content-makers/"><u>[New] Get Unlimited Echoes for Online Content Makers!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-securesave-specialists-judgment/"><u>[Updated] 2024 Approved SecureSave Specialists Judgment</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-game-on-and-store-more-top-5-ssd-reviews-for-xbox/"><u>[Updated] Game On & Store More Top 5 SSD Reviews for Xbox</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expertly-edited-entries-anywhere-at-the-tap-of-a-finger-in-2e23/"><u>2024 Approved Expertly Edited Entries, Anywhere at the Tap of a Finger in 2E23</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/experiencing-the-speed-with-asus-zenbook-s16-and-its-integrated-amd-ryzen-ai9-hx-370-processor-reviewed-here/"><u>Experiencing the Speed with ASUS Zenbook S16 and Its Integrated AMD Ryzen AI9 HX-370 Processor Reviewed Here</u></a></li>
<li><a href="https://windows11.techidaily.com/note-taking-evolution-embracing-obsidian-canvas/"><u>Note-Taking Evolution: Embracing Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-unfreezing-stuck-spotify-app-in-win11-pcs/"><u>Quick Guide: Unfreezing Stuck Spotify App in Win11 PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/screen-recording-pros-bandicam-or-camtasia-for-2024/"><u>Screen Recording Pros Bandicam or Camtasia for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adjusting-your-fax-covers-on-w11/"><u>Step-by-Step Guide: Adjusting Your Fax Covers on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-boost-utorrent-downloads-in-windows/"><u>Strategies to Boost uTorrent Downloads in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-ps5-game-library-management/"><u>Streamlining PS5 Game Library Management</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-nostalgia-unleashed-windows-11-to-the-past/"><u>Tech Nostalgia Unleashed: Windows 11 to the Past</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-fixes-for-hiberatus-computers/"><u>The 5 Best Fixes for Hiberatus Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/top-writing-helpers-to-transform-your-windows-experience/"><u>Top Writing Helpers to Transform Your Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-windows-lockscreensaver-timer/"><u>Tweaking Windows Lock/Screensaver Timer</u></a></li>
<li><a href="https://techidaily.com/vivo-data-recovery-recover-lost-data-from-vivo-v29-by-fonelab-android-recover-data/"><u>Vivo Data Recovery – recover lost data from Vivo V29</u></a></li>
</ul></div>

