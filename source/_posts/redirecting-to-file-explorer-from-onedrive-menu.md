---
title: Redirecting to File Explorer From OneDrive Menu
date: 2024-06-25T12:26:03.532Z
updated: 2024-06-26T12:26:03.532Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redirecting to File Explorer From OneDrive Menu
excerpt: This Article Describes Redirecting to File Explorer From OneDrive Menu
keywords: Redirect OneDrive FS,File Explorer Share,ONEDRIVE Open Files,Direct OneDrive Explorer,Access Files OneDrive,Navigate OneDrive FS,OneDrive to Explorer
thumbnail: https://thmb.techidaily.com/74722f9cb9d89019ce2bd2f1c80c266bfc2adc6c2152da5539a4a5d5cb3e57e3.jpg
---

## Redirecting to File Explorer From OneDrive Menu

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/cease-windows-tally-of-new-software-activities/"><u>Cease Windows' Tally of New Software Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-hello-fingerprint-setup-on-11/"><u>Mastering Windows Hello Fingerprint Setup on 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/snipemaster-offline-solutions-for-reconnecting-it/"><u>SnipeMaster Offline? Solutions for Reconnecting It</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-mp3s-into-listenable-audio-cds-using-windows-and-imgburn-techniques/"><u>Optimizing MP3s Into Listenable Audio Cds Using Windows and ImgBurn Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-your-battlenet-downloads-on-windows-pcs/"><u>Turbocharging Your Battle.net Downloads on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-stopping-auto-recommended-game-suggestion/"><u>Steps for Stopping Auto-Recommended Game Suggestion</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-digital-notepad-a-guide-to-windows-11-customization/"><u>Personalize Your Digital Notepad: A Guide to Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-best-free-desktop-pass-gen-software/"><u>The Ultimate Guide to Best Free Desktop Pass Gen Software</u></a></li>
<li><a href="https://windows11.techidaily.com/prove-your-prowess-top-7-zero-cost-pc-password-apps/"><u>Prove Your Prowess: Top 7 Zero-Cost PC Password Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-make-moments-last-longer-using-phantoms-slow-mo-magic-for-2024/"><u>How to Make Moments Last Longer  Using Phantom's Slow Mo Magic for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-top-10-cost-free-video-chat-apps-on-ios-and-android-for-2024/"><u>[New] Top 10 Cost-Free Video Chat Apps on iOS & Android for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-from-beginner-to-pro-5-final-cut-pro-editing-tips-to-up-your-game/"><u>New In 2024, From Beginner to Pro 5 Final Cut Pro Editing Tips to Up Your Game</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-premier-applications-for-audio-file-isolation-from-visual-content-for-2024/"><u>Updated Premier Applications for Audio File Isolation From Visual Content for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-rookie-to-veteran-10-must-have-cinema-cameras/"><u>[Updated] From Rookie to Veteran  10 Must-Have Cinema Cameras</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-financial-outcomes-dailymotion-versus-youtube-earning-potential/"><u>[New] 2024 Approved  Financial Outcomes  Dailymotion versus YouTube Earning Potential</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-overcoming-frame-loss-in-high-pace-broadcasts-with-obs/"><u>[New] 2024 Approved  Overcoming Frame Loss in High-Pace Broadcasts with OBS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-harmonizing-posts-with-instagram-music/"><u>[New] In 2024, Harmonizing Posts with Instagram Music</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-often-can-creators-expect-to-be-paid-by-youtube-in-2024/"><u>How Often Can Creators Expect to Be Paid by YouTube, In 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>