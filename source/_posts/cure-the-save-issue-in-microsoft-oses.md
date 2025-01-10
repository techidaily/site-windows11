---
title: Cure the Save Issue in Microsoft OSes
date: 2025-01-09T16:15:07.573Z
updated: 2025-01-10T17:49:08.023Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cure the Save Issue in Microsoft OSes
excerpt: This Article Describes Cure the Save Issue in Microsoft OSes
keywords: Windows Cure Fix,MSOS Save Solution,OS X Rescue,PC Fix Save Error,Microsoft OS Repair,Fixing Saving Issue,Resolve Save Problems
thumbnail: https://thmb.techidaily.com/738343d11636524e97e883ecdfb55ee8c179338e8409002b7334f65b8debc634.jpg
---

## Cure the Save Issue in Microsoft OSes

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-high-fidelity-footage-face-off-hero5-black-vs-hero4-silver/"><u>[New] In 2024, High Fidelity Footage Face-Off Hero5 Black vs Hero4 Silver</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-top-budget-friendly-sites-for-stunning-fx-on-videos/"><u>[Updated] In 2024, Top Budget-Friendly Sites For Stunning FX on Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-digital-dimension-state-of-the-art-vr/"><u>[Updated] The Digital Dimension State-of-the-Art VR</u></a></li>
<li><a href="https://media-tips.techidaily.com/enjoy-nfl-games-on-sundays-for-free-special-promotion-from-verizon/"><u>Enjoy NFL Games on Sundays For Free – Special Promotion From Verizon!</u></a></li>
<li><a href="https://fox-info.techidaily.com/full-unveiling-of-picsart-complete-users-guide/"><u>Full Unveiling of PicsArt Complete User's Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/get-your-m3-mac-essential-app-tg-pro-enjoy-a-whopping-75-discount-only-available-this-cyber-monday/"><u>Get Your M3 Mac Essential App, TG Pro! Enjoy a Whopping 75% Discount Only Available This Cyber Monday .</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-capture-and-manage-screenshots-on-steam/"><u>How to Capture and Manage Screenshots on Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-active-hours-and-avoid-sudden-updates-on-windows-11/"><u>How to Set Active Hours and Avoid Sudden Updates on Windows 11</u></a></li>
<li><a href="https://fox-where.techidaily.com/how-to-transfer-your-dj-sets-from-pcdj-dex-2-to-dex-3-a-comprehensive-step-by-step-guide/"><u>How to Transfer Your DJ Sets From PCDJ Dex 2 to Dex 3: A Comprehensive Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-on-quick-startup-your-complete-windows-11-guidebook/"><u>How to Turn On Quick Startup: Your Complete Windows 11 Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-phone-games-mobile-again-transitioning-to-pcwindows-11-via-google-play/"><u>Make Your Phone Games Mobile Again: Transitioning to PC/Windows 11 via Google Play</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-customization-techniques-for-windows-11-search/"><u>Pinpoint Customization Techniques for Windows 11 Search</u></a></li>
<li><a href="https://techidaily.com/repair-corrupt-pdf-v17-file-using-pdf-repair-tool-stellar-by-stellar-guide/"><u>Repair Corrupt PDF v1.7 File using PDF Repair Tool | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-boot-time-windows-audio-recovery-procedures/"><u>Resolving Boot-Time Windows Audio Recovery Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-nvidia-cp-access-denied-on-ws1110/"><u>Troubleshooting: Resolving Nvidia CP Access Denied on WS11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-disms-role-in-fixing-win11-os-images/"><u>Understanding DISM's Role in Fixing Win11 OS Images</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-behind-windows-memory-snapshot/"><u>Unraveling the Mystery Behind Windows' Memory Snapshot</u></a></li>
</ul></div>

