---
title: "Reprogramming Windows: Delete File's Read Lock"
date: 2025-02-22T22:42:36.981Z
updated: 2025-03-01T23:07:56.298Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reprogramming Windows: Delete File's Read Lock"
excerpt: "This Article Describes Reprogramming Windows: Delete File's Read Lock"
keywords: Deleting File Locks,Reprogramming Windows,Read Lock Removal,Unlock Files Windows,File Security Clearance,Erase File Access Locks,Secure Window File Deletion,Delete Locked Files,Windows File Reprogramming,Remove Read Locks,Unlock Windows Files,Clear Access Locks,Erase File Locks,Window Security Delete
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
---

## Reprogramming Windows: Delete File's Read Lock

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://fox-friendly.techidaily.com/expertise-in-the-field-a-complete-guide-to-srt-files-for-2024/"><u>Expertise in the Field A Complete Guide to SRT Files for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-google-pixel-7a-without-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Google Pixel 7a Without Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-realme-c51-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Realme C51 for Free? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfectly-pristine-photos-in-the-cloud-free-and-paid-unveiled/"><u>In 2024, Perfectly Pristine Photos in the Cloud Free & Paid Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivate-windows-audio-despite-disabled-settings/"><u>Reactivate Windows Audio Despite Disabled Settings</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-xs-max-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone XS Max Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-gaming-experience-by-eliminating-e84-issues/"><u>Streamlining Your Gaming Experience by Eliminating E84 Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-showdown-macbook-pro-vs-macbook-air-what-to-buy-insights-for-apple-enthusiasts-zdnet/"><u>The Ultimate Showdown: MacBook Pro Vs. MacBook Air – What to Buy? Insights for Apple Enthusiasts | ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-9-secrets-to-control-sound-settings-in-windows-11/"><u>Unlock the 9 Secrets to Control Sound Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pro-discounts-await-secure-your-best-price/"><u>W11 Pro Discounts Await: Secure Your Best Price</u></a></li>
</ul></div>

