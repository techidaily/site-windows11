---
title: "Time Traveling Your Data: Modifying Windows File Dates"
date: 2024-09-17T21:01:30.687Z
updated: 2024-09-20T17:46:33.033Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Time Traveling Your Data: Modifying Windows File Dates"
excerpt: "This Article Describes Time Traveling Your Data: Modifying Windows File Dates"
keywords: Time-Travel Data Edits,Date Changing Techniques,Modify Windows Files,Windows Timestamp Alteration,Data Age Manipulation,File History Revision,Date Editing in OS
thumbnail: https://thmb.techidaily.com/ecc3916e90aab64f99ff84f9c45d036bcf1e08682351feaa92b6a0ff146b14b9.jpg
---

## Time Traveling Your Data: Modifying Windows File Dates

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change the Date Created, Date Accessed, and Date Modified Attributes Using PowerShell

 File Explorer doesn't allow changing critical attributes, such as the date a document was created, accessed, or modified. With [PowerShell, a command-line interface utility built into Windows](http://www.makeuseof.com/what-is-windows-powershell/), you can modify them.

 However, the process to change the attributes with PowerShell is a bit complex. If you don't have any experience using PowerShell, you can use a third-party app, Attribute Changer, to change the attributes, as explained in the next section.

 If running a few commands in PowerShell isn't a big deal (for instance, you already know the [best PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/)), follow the steps outlined below to change the created, modified, or accessed dates.

 First, type **"PowerShell"** in Windows Search, right-click on **PowerShell,** and select **Run as administrator**. This gives the utility administrative access to make the desired changes without any restriction.

![Run windows powershell as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-powershell-as-administrator.jpg)

 Then, navigate to the directory where the file or folder you want to change the attributes of is located. Type **cd..** to move back one folder in the given path, and **cd folder\_name** to move to the next folder.

 For example, our desired folder is located at the following location:

`C:\Users\ehtas\Documents\Files`

 However, in PowerShell, we were in the **"System 32"** subfolder of the main folder **"Windows**.**"** Therefore, to return to the main directory **"C**,**"** we've executed **cd..** twice. Then, we used the **cd folder\_name** command three times to get to the directory where we wanted to be.

![changing the directories in PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-directories.jpg)

 Therefore, use both commands to reach the folder you want to modify attributes for. After landing in your desired directory, type the following command after inserting the file name and your preferred date of creation:

`$(Get-Item File-name).creationtime=$(Get-Date "mm/dd/yyyy")`

 If PowerShell doesn't present any errors and takes you to the same directory again, that confirms that the attributes have been successfully changed.

![successfully changing the creation date of a file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/creation-date-has-been-changed.jpg)

 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

## How to Modify the Date Created, Date Accessed, and Date Modified Using Attribute Changer

 The Attribute Changer app is one of the [third-party attribute changer apps](https://www.makeuseof.com/apps-change-created-modified-date-windows/) that lets users change file attributes, including when a file was created, modified, or accessed. If changing the file attributes using PowerShell is challenging for you, here are the steps to modify them using this third-party app:

1. Go to the [official PETGES website](https://www.petges.lu/).
2. Download the full setup of Attribute Changer; do not download the portable version, as it may not function properly.
3. Once the software has been downloaded, run the setup file and follow the onscreen instructions to install it.
4. Restart your device if the software asks you to; otherwise, there's no need.
5. Navigate to the folder containing the file whose attributes you wish to modify.

1. Right-click the file and select **Change Attribute** from the context menu to open the software. If you're using Windows 11, you may need to click **Show more options** to reveal this option in the context menu.  
![opening the attribute changer app from context menu of a file in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/opening-the-attribute-changer-app-from-context-menu-of-a-file-in-windows.jpg)
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-techniques-for-smooth-playback-and-no-frame-dropping-in-obs/"><u>[New] Techniques for Smooth Playback and No Frame Dropping in OBS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-smart-choices-the-ultimate-list-of-educator-friendly-recording-tools/"><u>[Updated] Smart Choices The Ultimate List of Educator-Friendly Recording Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-structuring-a-significant-tiktok-close-up/"><u>[Updated] Structuring a Significant TikTok Close-Up</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/facebook-algorithm-change-are-you-ready-for-2024/"><u>Facebook Algorithm Change Are You Ready？ for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-steams-read-only-mode-for-library-folders-in-win-11/"><u>Fixing Steam's Read-Only Mode for Library Folders in Win 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gratis-tool-zum-hochladen-von-hd-audiokonvertierung-aus-dvds-bewahren-sie-die-exzellente-tonqualitat/"><u>Gratis Tool Zum Hochladen Von HD-Audiokonvertierung Aus DVDs - Bewahren Sie Die Exzellente Tonqualität</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-windows-11s-online-scanning-option/"><u>How to Manage Windows 11'S Online Scanning Option</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-show-or-hide-the-dim-display-after-option-in-the-power-options-menu-on-windows/"><u>How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-lean-cloud-archive-efficient-low-cost-large-data/"><u>In 2024, Lean Cloud Archive Efficient, Low-Cost Large Data</u></a></li>
<li><a href="https://windows11.techidaily.com/make-every-day-better-with-these-6-must-have-android-apps-for-window-11/"><u>Make Every Day Better with These 6 Must-Have Android Apps for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-rectifying-wow-crashes-error-132/"><u>Mastering the Art of Rectifying WoW Crashes: Error 132</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-in-tpm-deactivation-on-windows-11/"><u>Triumph in TPM Deactivation on Windows 11</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-how-to-add-bitmoji-to-keyboard/"><u>Updated How to Add Bitmoji to Keyboard?</u></a></li>
<li><a href="https://blog-min.techidaily.com/winxvideo-ai-4k8k10k-winxvideo/"><u>WinXVideo AI를 활용하여 고해상도(4K/8K/10K)으로 이미지 크기 조정 및 제거하세요 - Winxvideo</u></a></li>
</ul></div>

