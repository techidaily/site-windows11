---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2024-10-29T16:54:51.990Z
updated: 2024-10-30T16:42:05.520Z
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
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/2024-approved-advanced-tactics-to-modify-playback-speed-in-spotify/"><u>2024 Approved Advanced Tactics to Modify Playback Speed in Spotify</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209650601-9780757318856-connecting-with-coincidence/"><u>Connecting with Coincidence | Free Book</u></a></li>
<li><a href="https://win-forum.techidaily.com/diagnosis-and-remediation-of-maximum-disk-usage-problems-in-windows/"><u>Diagnosis and Remediation of Maximum Disk Usage Problems in Windows 지급 택시</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-puzzling-problem-of-error-code-c0000005-in-win-os/"><u>Fixing the Puzzling Problem of Error Code C0000005 in Win-OS</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-the-solutions-for-seamless-start-up-of-the-elder-scrolls-online/"><u>Mastering the Solutions for Seamless Start-Up of The Elder Scrolls Online</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-room-acoustics-with-windows-11/"><u>Maximizing Room Acoustics with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/migrate-onedrive-to-a-desired-folder-on-win-11/"><u>Migrate OneDrive to a Desired Folder on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-windows-11s-isdonedll-file-failure/"><u>Repairing Windows 11'S ISDone.dll File Failure</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-samsung-galaxy-a24-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-remedies-for-fixing-microsoft-store-crash-code-0x80072efd/"><u>Swift Remedies for Fixing Microsoft Store Crash Code 0X80072EFD</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restricting-removable-storage-via-windows-settings/"><u>Tips for Restricting Removable Storage via Windows Settings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/your-pathway-to-perfect-igtv-footage-from-phone-to-dslr/"><u>Your Pathway to Perfect IGTV Footage From Phone to DSLR</u></a></li>
</ul></div>

