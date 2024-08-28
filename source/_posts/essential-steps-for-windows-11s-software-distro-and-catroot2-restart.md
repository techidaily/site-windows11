---
title: Essential Steps for Windows 11'S Software Distro and Catroot2 Restart
date: 2024-08-27T16:07:55.444Z
updated: 2024-08-28T16:07:55.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Windows 11'S Software Distro and Catroot2 Restart
excerpt: This Article Describes Essential Steps for Windows 11'S Software Distro and Catroot2 Restart
keywords: Win11 Setup Guide,Catroot2 Update,Software Distribution,Windows 11 Installation,OS Reboot Steps,Restart Windows 11,Catroot2 Procedure
thumbnail: https://thmb.techidaily.com/f8d5308a72df2042f1308b78dc1efb598f7f3491c673912341c93c2d4c06d1ec.jpg
---

## Essential Steps for Windows 11'S Software Distro and Catroot2 Restart

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-exploring-your-choices-with-youtube-tv-plans/"><u>[New] 2024 Approved  Exploring Your Choices with YouTube TV Plans</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ideal-online-audio-equipment-top-7-picks-2023/"><u>[New] Ideal Online Audio Equipment  Top 7 Picks 2023</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-maximize-your-impact-broadcast-on-facebook-live-today/"><u>[New] Maximize Your Impact  Broadcast on Facebook Live Today</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-mute-auto-generated-youtube-content-trails/"><u>[Updated] 2024 Approved  Mute Auto-Generated YouTube Content Trails</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-essential-guide-to-lut-applications-in-photoshop-cs6/"><u>2024 Approved  The Essential Guide to LUT Applications in Photoshop CS6</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-oneplus-12r-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://data-wizards.techidaily.com/diy-software-solutions-unveiling-the-secrets-of-stellars-ultimate-programming-kit/"><u>DIY Software Solutions: Unveiling the Secrets of Stellar's Ultimate Programming Kit</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-variability-between-in-store-and-online-windows-reinstallations/"><u>Evaluating the Variability Between In-Store & Online Windows Reinstallations</u></a></li>
<li><a href="https://some-techniques.techidaily.com/experts-choice-peak-business-space-for-2024/"><u>Expert's Choice  Peak Business Space for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-system32-windows-11-edition/"><u>Exploring System32: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/from-lost-to-found-reclaiming-windows-storage/"><u>From Lost to Found: Reclaiming Windows Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/futuristic-meetings-speed-and-efficiency-unleashed/"><u>Futuristic Meetings: Speed & Efficiency Unleashed</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-halt-windows-11-data-harvesting/"><u>Guide to Halt Windows 11 Data Harvesting</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-facebook-video-integration-for-pc-and-android-users-explained/"><u>In 2024, Facebook Video Integration for PC & Android Users Explained</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-share-the-laughs-right-top-gif-saver-for-twitter/"><u>In 2024, Share the Laughs Right  Top GIF Saver for Twitter</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-desktop-icons-properly-sized-on-win-11/"><u>Keep Desktop Icons Properly Sized on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-windows-icons-peeled-for-ease/"><u>Keep Windows Icons Peeled for Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-time-transferring-classic-titles-to-photos/"><u>Navigating Through Time: Transferring Classic Titles to Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-win-power-the-ultimate-list-of-apps-to-boost-workflow-on-win-11/"><u>Pro-Win Power: The Ultimate List of Apps to Boost Workflow on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-and-reclaim-resetting-ms-store-in-windows-1011/"><u>Reboot and Reclaim: Resetting MS Store in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-administrative-functionality-in-microsoft-tools/"><u>Restoring Administrative Functionality in Microsoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-dealing-with-non-downloading-errors-on-windows/"><u>Strategies for Dealing with Non-Downloading Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-performance-and-stability-of-your-system-post-windows-11-update/"><u>Sustaining Performance and Stability of Your System Post-Windows 11 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-troubleshooting-for-flashing-displays-on-windows/"><u>Systematic Troubleshooting for Flashing Displays on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-security-hurdles-with-precision-and-care/"><u>Tackling Windows Security Hurdles with Precision & Care</u></a></li>
<li><a href="https://windows11.techidaily.com/to-halt-or-not-yourphoneexe-in-windows-xpvista/"><u>To Halt or Not: YourPhone.exe in Windows XP/Vista?</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-to-sudo-windows-next-step/"><u>Transition to Sudo: Windows' Next Step</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-right-menu-options-for-optimal-software-use/"><u>Tweak Right-Menu Options for Optimal Software Use</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-mouse-access-the-windows-11-way/"><u>Tweaking Mouse Access: The Windows 11 Way</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-successful-setup-fixing-discord-install-issues-in-win-1011/"><u>Unlocking the Secrets of Successful Setup: Fixing Discord Install Issues in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-included-in-the-enhanced-windows-11-settings-app/"><u>What's Included in the Enhanced Windows 11 Settings App?</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-audio-levels-on-your-terms-designing-your-shortcuts/"><u>Win11 Audio Levels on Your Terms: Designing Your Shortcuts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>