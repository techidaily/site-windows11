---
title: "Zeroing in on Win11's ONEDRIVE Sign In Fault: Error XYZ Unraveled"
date: 2024-10-02T17:33:39.300Z
updated: 2024-10-07T05:10:15.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Zeroing in on Win11's ONEDRIVE Sign In Fault: Error XYZ Unraveled"
excerpt: "This Article Describes Zeroing in on Win11's ONEDRIVE Sign In Fault: Error XYZ Unraveled"
keywords: Win11 ONEDrive Error,ONEDRIVE Sign-In FAIL,Zeroing Win11 ONEDrive,ONEDRIVE XYZ Error,Fix Win11 ONEDrive Issue,Unravel Win11 Error,ONEDrive Sign In Trouble
thumbnail: https://thmb.techidaily.com/2ce87a986250d8398be45eae1ecaf9f012f12535b14ea9611940de411cb7abe5.jpg
---

## Zeroing in on Win11's ONEDRIVE Sign In Fault: Error XYZ Unraveled

 Microsoft's cloud storage service OneDrive simplifies file management on Windows. However, you might experience issues when signing in to OneDrive, like the 0x8004dec5 error. This article will guide you on how to resolve OneDrive sign-in error 0x8004dec5 specifically on Windows 11\.

## 1\. Check Your Internet Connection

 If you’re having trouble signing in to OneDrive, first [check your internet connection](http://www.makeuseof.com/windows-check-wifi-network-strength/). Slow or spotty internet causes sign-in problems. So, check your connection speed and make sure it’s strong enough for OneDrive. If necessary, reset your router or modem to restore the connection.

 If your internet connection is working, restart your computer and sign in to OneDrive again. This simple step fixes minor errors in the operating system that may cause the sign-in issue.

## 2\. Run the Network Troubleshooter

 If your internet connection is stable, but you’re still having OneDrive sign-in problems, you can run the Internet Connections Troubleshooter. This diagnosis tool scans for network problems and repairs any issues it finds.

 To run the Internet Connection Troubleshooter, follow these steps:

1. Right-click on Start and select **Run** from the menu list.  
![Open Internet Connections](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/open-internet-connections.jpg)
2. In the dialog box, type the following command and click **OK**.  
`msdt.exe -id NetworkDiagnosticsWeb`
3. Click **Advanced** and check **Apply repairs automatically**.  
![Run the Internet Connections troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-the-internet-connections-troubleshooter.jpg)
4. Now click **Next** and follow the on-screen instructions to finish the troubleshooting process.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1883998/19272" target="_top" id="1883998">
  <img src="//a.impactradius-go.com/display-ad/19272-1883998" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1883998/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once it’s done, sign into OneDrive and see if the error is fixed. If not, try the next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Tweak the Registry Editor

 If the problem persists, remove cached Office account identities from the registry. This requires changing a few settings in the Windows registry which is a database of your operating system, so proceed with caution.

 If you’re not sure what you’re doing, have an experienced technician make the changes for you. To avoid damaging your system, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making these changes.

1. Press **Win + R** on your keyboard to open the Run dialog.
2. Type **regedit** in the search box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to proceed.
4. In the Registry Editor window, navigate to the path as follows:  
`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity`
5. Right-click on the **Identity** folder and select **Delete** from the menu.  
![Delete Identity Folder From Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-identity-folder-from-registry.jpg)
6. Click **Yes** when asked to confirm your action.
7. Close Registry Editor and restart your computer.

 Now try signing in to OneDrive again. The sign-in error should now be resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove Cached Credentials Folders

 If you're not comfortable tweaking the registry editor, remove cached Office account identities using Windows Explorer. Here's how to do it.

1. Press **Win + E** to open File Explorer.
2. In the File Explorer window, navigate to the following location:  
`C:\Users\Username\AppData\Local\Microsoft\IdentityCache`
3. Press **Ctrl + A** to select all files and delete them.  
![Clear Identity Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/clear-identity-folder.jpg)
4. Now navigate to this location, and replace **Username** with your own Windows username.:  
`C:\Users\Username\AppData\Local\Microsoft\OneAuth  
`
5. Select all the files here and hit the **Delete** button.

 Once you've removed all cached Office account identities, restart your computer and try signing in to OneDrive again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Unlink and Re-Link Your OneDrive Account

 If you have a valid OneDrive account, but still can’t sign in due to the 0x8004dec5 error code, unlink and relink your account. This will reset the connection and fix the problem.

 To unlink OneDrive, follow these steps.

1. Go to the right side of the taskbar and click on the **OneDrive** icon.
2. Click **Help & Settings** (the gear icon) and select **Settings** from the menu list.
3. In the Settings window, go to the **Account** tab.
4. Under your OneDrive account, click **Unlink this PC**.  
![Unlink OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive.jpg)
5. Click **Unlink account** to confirm your action.  
![Unlink OneDrive Account on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive-account-on-windows.jpg)

 After unlinking the account, you now need to relink it. To do that, open the OneDrive Settings window again and click **Add an Account**. Enter your OneDrive credentials and sign in to the account.

 When it’s done, close the Settings window. Now open OneDrive and sign in with your new account credentials. The sign-in error should now be resolved.

## 6\. Reset the OneDrive App

 In some cases, resetting the OneDrive application solves the sign-in errors. This restores the app to its default settings and removes any corrupted system files.

 To reset the OneDrive app, follow these steps.

1. Press **Win + X** on your keyboard and select **Installed apps** from the list.
2. In the list of installed apps, scroll down to **OneDrive**.
3. Click the three dots and select the **Advanced options**.
4. Scroll down to the **Reset** section and click on the **Reset** button.  
![Reset OneDrive app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-onedrive-app.jpg)
5. Click **Reset** again to confirm your action.

 After the reset, try signing in to OneDrive and seeing if error 0x8004dec5 is fixed.

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Get the Latest Windows Updates

 Microsoft releases new patches that improve Windows performance. If your computer didn't receive the latest updates, it may cause OneDrive sign-in errors. To fix this problem, install the pending Windows updates and try signing in to OneDrive again.

 To download and install the latest Windows updates, use these steps.

1. Press **Win + I** on your keyboard to open the Settings window (see our guide on [how to open the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/)).
2. From the left sidebar, click on the **Windows Update** tab.
3. Now click **Check for updates** and wait while Windows checks for available updates.  
![Check for updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-updates.jpg)
4. If you find new updates, download and install them.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After performing the above action, restart your computer. Now try signing in to OneDrive and seeing if the error is fixed.

## 8\. Uninstall and Reinstall OneDrive

 If the error persists even after trying the above solutions, it's likely that the OneDrive app is malfunctioning. In that case, reinstall the application. It fixes corrupted files and solves sign-in issues. Here's how to do it.

1. [Open Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/).
2. Set the View by option to **Category**, then click **Programs** \> **Uninstall a program**.
3. Find **OneDrive** in the list of installed programs and click **Uninstall**.  
![Uninstall OneDrive-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-onedrive-2.jpg)
4. If you get a confirmation prompt, click **Yes**.

 Now follow the instructions to complete the process. After that, [visit Microsoft's official website](https://www.microsoft.com/en-us/microsoft-365/onedrive/download?) to download and install OneDrive.

## Fixing OneDrive's 0x8004dec5 Sign In Error

 Following the steps mentioned above should resolve the 0x8004dec5 OneDrive sign-in error. Corrupt files, outdated Windows versions, or compatibility issues usually cause it. A basic troubleshooting step would be to restart your computer and reset the OneDrive app. If that doesn't fix it, unlink and relink your account, or reinstall OneDrive.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-smooth-transition-optimal-8-sub-to-srt-modules/"><u>[New] 2024 Approved Smooth Transition Optimal 8 Sub to SRT Modules</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-effortless-and-easy-video-snapshots-of-win11/"><u>[New] Effortless & Easy Video Snapshots of Win11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-science-of-captivating-youtube-thumbnails/"><u>[New] The Science of Captivating YouTube Thumbnails</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-rankings-secrets-enhancing-video-visibility/"><u>[New] YouTube Rankings Secrets Enhancing Video Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-system-performance-by-curbing-browser-activity/"><u>Improving System Performance by Curbing Browser Activity</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-12-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On iPhone 12</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-tecno-spark-10c-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Tecno Spark 10C For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/installing-social-media-adding-snapchat-to-your-mac-for-2024/"><u>Installing Social Media Adding Snapchat to Your Mac for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-15-free-raw-image-editing-tools-the-ultimate-guide-by-movavi/"><u>Top 15 Free RAW Image Editing Tools: The Ultimate Guide by Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-fix-sound-issues-in-windows-7/"><u>Troubleshooting Steps: How to Fix Sound Issues in Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-type-tips-quick-key-input-enhancements-for-win-1011/"><u>Turbo-Type Tips: Quick Key Input Enhancements for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-5ghz-wi-fi-connection-woes-how-to-solve-them/"><u>Win11 5GHz Wi-Fi Connection Woes: How to Solve Them</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-widgets-configuration-the-triad-approach/"><u>Windows 11 Widgets Configuration: The Triad Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
</ul></div>

