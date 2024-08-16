---
title: Redirecting to File Explorer From OneDrive Menu
date: 2024-08-15T15:45:48.546Z
updated: 2024-08-16T15:45:48.546Z
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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
<li><a href="https://some-knowledge.techidaily.com/new-four-basic-techniques-for-adjusting-photo-hues/"><u>[New] Four Basic Techniques for Adjusting Photo Hues</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-secrets-of-the-top-social-media-videos-for-2024/"><u>[New] Secrets of the Top Social Media Videos for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-future-is-here-free-innovative-fb-story-enhancers/"><u>[Updated] 2024 Approved  The Future Is Here  Free, Innovative FB Story Enhancers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-the-instagram-sequence-steps-to-reach-1k-monthly-followers/"><u>[Updated] In 2024, The Instagram Sequence  Steps to Reach 1K Monthly Followers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-6-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 6 for Free</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-oppo-reno-11f-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Oppo Reno 11F 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-dxgierrordeviceremoved-in-modern-win-oses/"><u>Combatting DXGI_ERROR_DEVICE_REMOVED in Modern Win OSes</u></a></li>
<li><a href="https://fox-helps.techidaily.com/creative-composition-ideal-apps-for-ios-and-android/"><u>Creative Composition  Ideal Apps for iOS and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-windows-security-incorporating-firewalls-into-context-menu/"><u>Enhance Your Windows Security: Incorporating Firewalls Into Context Menu</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-fix-a-corrupted-iphone-backup-with-two-reliable-techniques/"><u>How to Fix a Corrupted iPhone Backup with Two Reliable Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-snapshot-superiority-choosing-the-best-10-cameras/"><u>In 2024, Snapshot Superiority  Choosing the Best 10 Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://review-topics.techidaily.com/lenovo-thinkphone-messages-recovery-recover-deleted-messages-from-lenovo-thinkphone-by-fonelab-android-recover-messages/"><u>Lenovo ThinkPhone Messages Recovery - Recover Deleted Messages from Lenovo ThinkPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/multiply-your-efforts-mastering-multiple-directory-creation-in-win11plus11/"><u>Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-directdraw-woes-a-users-survival-manual-for-win11/"><u>Navigating DirectDraw Woes: A User's Survival Manual for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failure-to-launch-on-windows-speech-recognition/"><u>Overcoming Failure to Launch on Windows Speech Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-safety-with-windows-canary-channel-feature/"><u>Step Into Safety with Windows' Canary Channel Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-windows-backup-configuration-recollection/"><u>Steps for Windows Backup Configuration Recollection</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-steams-online-potential-on-pc/"><u>Unlocking Steam's Online Potential on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-hello-biometrics-endangered-by-recent-cyberattacks/"><u>Windows Hello Biometrics Endangered by Recent Cyberattacks</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-windows-missing-files-issue/"><u>Winning Over Windows' Missing Files Issue</u></a></li>
</ul></div>
