---
title: "Overcoming Obstacles: Fixing Outlook Issues in Windows"
date: 2024-09-05T02:09:16.399Z
updated: 2024-09-06T02:09:16.399Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Obstacles: Fixing Outlook Issues in Windows"
excerpt: "This Article Describes Overcoming Obstacles: Fixing Outlook Issues in Windows"
keywords: Outlook Troubleshooting Guide,Overcome Microsoft Outlook Errors,Resolve Windows Mail Problems,Quick Outlook Repair Tips,Fixing Outlook in WIndows,Outlook Glitch Solutions,Streamline Outlook Issues
thumbnail: https://thmb.techidaily.com/c2342fb5e25c5a967555cf815791bd2b9698b049e69b2eb389ba72dc308a7ad2.jpeg
---

## Overcoming Obstacles: Fixing Outlook Issues in Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once removed, click the **New** option under the **Email** tab and set up your account again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024333/7443" target="_top" id="2024333">
  <img src="//a.impactradius-go.com/display-ad/7443-2024333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024333/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/avigating-iphones-automatic-replay-feature-for-2024/"><u>[New] Navigating iPhone's Automatic Replay Feature for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-mastering-screencasts-a-step-by-step-manual/"><u>[Updated] 2024 Approved  Mastering Screencasts  A Step-by-Step Manual</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-incorporating-on-screen-words-a-tiktok-video-transformation/"><u>[Updated] In 2024, Incorporating On-Screen Words  A TikTok Video Transformation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-iphones-ultimate-podcast-downloading-manual/"><u>[Updated] IPhone's Ultimate Podcast Downloading Manual</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-watch-facebook-live-on-your-apple-media-hub/"><u>2024 Approved  How to Watch Facebook Live on Your Apple Media Hub</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://games-able.techidaily.com/disassembling-the-powerhouse-xbox-s-controller-guide/"><u>Disassembling The Powerhouse: Xbox S Controller Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/elite-screenscape-high-quality-4k-panels-for-editors/"><u>Elite Screenscape  High-Quality 4K Panels for Editors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-these-exceptional-platforms-for-accessing-free-e-books-anywhere-anytime/"><u>Explore These Exceptional Platforms for Accessing Free E-Books Anywhere, Anytime</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-fingerprint-device-in-windows/"><u>Fixing Inaccessible Fingerprint Device in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-halt-default-search-menu-opens-in-win11/"><u>Guide to Halt Default Search Menu Opens in Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-google-pixel-fold-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Google Pixel Fold to iPad | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-4-seamless-steps-to-posting-and-uploading-gifs-on-instagram/"><u>In 2024, 4 Seamless Steps to Posting & Uploading GIFs on Instagram</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock On Apple iPhone 12?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-11-pro-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 11 Pro You Should Try Out</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-taskmanager-visible-on-top/"><u>Keeping TaskManager Visible on Top</u></a></li>
<li><a href="https://windows11.techidaily.com/making-store-downloads-functional-again-a-step-by-step-approach/"><u>Making Store Downloads Functional Again: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-overuse-of-system-resources-by-unrealcefsubprocess-on-windows/"><u>Managing Overuse of System Resources by UnrealCEFSubprocess on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-top-7-techniques-to-improve-daily-use/"><u>Mastering Windows 11: Top 7 Techniques to Improve Daily Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mind-body-harmony-meditations-impact-on-brain-and-mood/"><u>Mind-Body Harmony: Meditation's Impact on Brain & Mood</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-system-restore-in-windows-a-comprehensible-tutorial/"><u>Navigating System Restore in Windows: A Comprehensible Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blue-screen-errors-how-to-fix-0x8007045d-in-windows-11/"><u>Overcoming Blue Screen Errors: How to Fix 0X8007045d in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-disk-readwrites-on-windows/"><u>Overcoming Failed Disk Read/Writes on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/podcasting-power-play-selecting-the-best-audio-interfaces/"><u>Podcasting Power Play  Selecting the Best Audio Interfaces</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-file-ordering-with-these-tools/"><u>Precision in File Ordering with These Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-digital-progress-consistent-backups-on-windows/"><u>Preserve Digital Progress: Consistent Backups on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-downloading-adobe-reader/"><u>Quick Guide to Downloading Adobe Reader</u></a></li>
<li><a href="https://some-tips.techidaily.com/shielding-your-information-from-unavoidable-security-incidents/"><u>Shielding Your Information From Unavoidable Security Incidents</u></a></li>
<li><a href="https://windows11.techidaily.com/shop-smoothly-and-swiftly-resolve-windows-store-error-x80072f30/"><u>Shop Smoothly & Swiftly: Resolve Windows Store Error X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-failed-display-driver-startup-in-windows-11/"><u>Steps to Fix Failed Display Driver Startup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-inadequate-access-rights-in-win-1110-errors/"><u>Steps to Resolve Inadequate Access Rights in Win 11/10 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-guide-executing-windows-11-setup-on-vmware-player-17/"><u>Streamlined Guide: Executing Windows 11 Setup on VMware Player 17</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-fit-window-color-schemes-with-winterral/"><u>Tailor-Fit Window Color Schemes with WinTerral</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-youtubes-most-captivating-storytellers-in-23/"><u>The Ultimate Guide to YouTube's Most Captivating Storytellers in '23</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-converting-heic-images-to-jpeg-using-windows-11-capabilities/"><u>Top Techniques: Converting Heic Images to JPEG Using Windows 11 Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workspace-unveiling-5-advanced-window-folder-methods/"><u>Transform Your Workspace: Unveiling 5 Advanced Window Folder Methods</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-and-fixes-for-obs-studio-crashing-problems-in-windows-1110-latest-tips/"><u>Troubleshooting and Fixes for OBS Studio Crashing Problems in Windows 11/10 - Latest Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-endless-stalling-during-valorant-startup-expert-advice/"><u>Troubleshooting Endless Stalling During Valorant Startup: Expert Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/unpacking-windows-maintenance-tools/"><u>Unpacking Window's Maintenance Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-powerful-techniques-for-managing-packages-on-windows-11/"><u>Unveiling Powerful Techniques for Managing Packages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-a-beginners-guide-to-screensavers/"><u>Win11: A Beginner's Guide to Screensavers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-22h2-gets-another-year-of-optional-updates-what-this-means-for-you/"><u>Windows 11 22H2 Gets Another Year of Optional Updates: What This Means for You</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-users-guide-to-transcribing-with-ais-whisper/"><u>Windows Users Guide to Transcribing with AI's Whisper</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>