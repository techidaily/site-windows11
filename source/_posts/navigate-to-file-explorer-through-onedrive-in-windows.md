---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2024-10-18T16:25:46.551Z
updated: 2024-10-24T18:45:27.609Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-core-elements-of-virtual-tale-transmission/"><u>[New] Core Elements of Virtual Tale Transmission</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-seamless-background-extraction-in-picsart-editing/"><u>[New] In 2024, Seamless Background Extraction in Picsart Editing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-optimal-downloaders-your-guide-to-superior-4k-content/"><u>[New] Optimal Downloaders Your Guide to Superior 4K Content</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-blank-screen-top-techniques-to-recover-vanished-panes-in-windows-11/"><u>Avoid the Blank Screen: Top Techniques to Recover Vanished Panes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-windows-updates-interruptions/"><u>Avoidance of Windows Updates Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-windows-photo-viewer-a-1111-edition-guide/"><u>Bring Back Windows Photo Viewer: A 11/11 Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-bandsaw-methods-for-fixing-lost-windows-time/"><u>Bring Back Your Bandsaw: Methods for Fixing Lost Windows Time</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-interface-cli-addition-to-task-manager-in-windows-11/"><u>Command Line Interface (CLI) Addition to Task Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-huawei-nova-y71-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Huawei Nova Y71?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-oppo-k11x-by-fonelab-android-recover-messages/"><u>How To Restore Missing Messages Files from Oppo K11x</u></a></li>
<li><a href="https://windows11.techidaily.com/1719297453407-mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality</u></a></li>
<li><a href="https://facebook.techidaily.com/profiles-that-pop-visual-tactics-for-more-interaction/"><u>Profiles That Pop: Visual Tactics for More Interaction</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/rated-recs-top-pages-for-obtaining-snapalert-tunes-for-2024/"><u>Rated Recs Top Pages for Obtaining SnapAlert Tunes for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-bokeh-effects-unleashed-top-ios-and-android-apps-for-photography/"><u>Updated 2024 Approved Bokeh Effects Unleashed Top iOS and Android Apps for Photography</u></a></li>
</ul></div>

