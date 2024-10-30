---
title: "Streamline Your PC: Toggle Folders Visibility (Windows 11)"
date: 2024-10-23T16:22:12.751Z
updated: 2024-10-30T16:49:10.878Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamline Your PC: Toggle Folders Visibility (Windows 11)"
excerpt: "This Article Describes Streamline Your PC: Toggle Folders Visibility (Windows 11)"
keywords: Win11 Folder Views,Windows 11 Visibility,Streamlining Windows,Enhance PC Efficiency,Toggle Folders Quickly,Windows 11 Settings,Optimize File Display
thumbnail: https://thmb.techidaily.com/1bbd0a3f8dc1d9288d108f379c03c690ea0ce4f3426715024680a4a4a0f123c3.jpg
---

## Streamline Your PC: Toggle Folders Visibility (Windows 11)

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-deciphering-digital-domination-a-deep-dive-into-directors-videos/"><u>[Updated] 2024 Approved Deciphering Digital Domination A Deep Dive Into Directors' Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-hunt-for-hit-tunes-and-viral-videos-on-fb/"><u>[Updated] The Hunt for Hit Tunes and Viral Videos on FB</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-the-most-upvoted-reddit-post-of-all-time-a-list-of-10/"><u>[Updated] The Most Upvoted Reddit Post of All Time - (A List of 10)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-apple-iphone-14-pro-without-itunes-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked Apple iPhone 14 Pro Without iTunes</u></a></li>
<li><a href="https://fox-access.techidaily.com/crafting-an-iconic-identity-on-instagram-with-these-9-tricks-for-2024/"><u>Crafting an Iconic Identity on Instagram with These 9 Tricks for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/debunking-the-top-5-common-myths-surrounding-cryptocurrency/"><u>Debunking the Top 5 Common Myths Surrounding Cryptocurrency</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-overcome-the-notorious-broccoli-bug-in-destiny-2-fix-available/"><u>How to Overcome the Notorious 'Broccoli Bug' In Destiny 2 (Fix Available)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-honor-90-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Honor 90 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://blog-min.techidaily.com/leading-screen-recording-software-for-windows-users-seamlessly-document-your-desktop-activities/"><u>Leading Screen Recording Software for Windows Users: Seamlessly Document Your Desktop Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-time-transferring-classic-titles-to-photos/"><u>Navigating Through Time: Transferring Classic Titles to Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-and-reclaim-resetting-ms-store-in-windows-1011/"><u>Reboot and Reclaim: Resetting MS Store in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-in-windows-services-explorer-with-these-7-steps/"><u>Restoring Functionality in Windows Services Explorer with These 7 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-play-eradicating-xbox-service-block/"><u>Seamless Play: Eradicating Xbox Service Block</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-dealing-with-non-downloading-errors-on-windows/"><u>Strategies for Dealing with Non-Downloading Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-security-hurdles-with-precision-and-care/"><u>Tackling Windows Security Hurdles with Precision & Care</u></a></li>
<li><a href="https://windows11.techidaily.com/top-ways-to-resolve-black-screens-in-win1111-pro/"><u>Top Ways to Resolve Black Screens in Win11/11 Pro</u></a></li>
</ul></div>

