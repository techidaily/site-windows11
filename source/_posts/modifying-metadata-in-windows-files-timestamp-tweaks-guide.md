---
title: "Modifying Metadata in Windows Files: Timestamp Tweaks Guide"
date: 2024-08-22T21:37:56.776Z
updated: 2024-08-23T21:37:56.776Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Modifying Metadata in Windows Files: Timestamp Tweaks Guide"
excerpt: "This Article Describes Modifying Metadata in Windows Files: Timestamp Tweaks Guide"
keywords: Windows File Mods,File Timestamp Changes,Editing File Metadata,Windows Timestamp Adjustment,Metadata Manipulation Tips,Altering File Creation Dates,Navigating Windows Metadata
thumbnail: https://thmb.techidaily.com/8e684e3736085a42393dd155a637e8f217c26c390b45353b04f9ee1e79b6412e.jpg
---

## Modifying Metadata in Windows Files: Timestamp Tweaks Guide

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

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

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-unveiling-the-virtual-realms-of-meta-and-omni/"><u>[New] 2024 Approved  Unveiling the Virtual Realms of Meta and Omni</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-internet-jesters-arsenal/"><u>[New] Internet Jester's Arsenal</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-maximizing-your-videos-impact-with-expertly-recorded-voices/"><u>[New] Maximizing Your Video's Impact with Expertly Recorded Voices</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-essential-guide-to-live-broadcasts-optimizing-with-obs-for-youtube-and-twitch-for-2024/"><u>[New] The Essential Guide to Live Broadcasts  Optimizing with OBS for YouTube & Twitch for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-making-gifs-from-youtube-tracks/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Making GIFs From YouTube Tracks</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-essential-mac-capturing-apps-beyond-the-traditional-bandicam/"><u>[Updated] In 2024, Essential Mac Capturing Apps Beyond the Traditional Bandicam</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-quick-screen-grabs-for-win-11-users/"><u>[Updated] In 2024, Quick Screen Grabs for Win 11 Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-a-step-by-step-guide-to-embedding-timestamp-metadata/"><u>2024 Approved  A Step-by-Step Guide to Embedding Timestamp Metadata</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-persistent-fluctuating-light-on-asus-laptops/"><u>Banish Persistent Fluctuating Light on ASUS Laptops</u></a></li>
<li><a href="https://article-helps.techidaily.com/compact-and-cost-effective-mirrorless-4k-cameras-(1000/"><u>Compact and Cost-Effective  Mirrorless 4K Cameras <$1,000</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnosing-and-repairing-a-5n-gateway-failure-a-step-by-step-guide/"><u>Diagnosing and Repairing a 5N-Gateway Failure: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-captcha-missteps-in-windows-steam/"><u>Fixing CAPTCHA Missteps in Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialization-of-qt-engine-in-software-applications/"><u>Fixing Non-Initialization of Qt Engine in Software Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/forewarned-is-forearmed-top-8-windows-11-no-nos-for-neophytes/"><u>Forewarned Is Forearmed: Top 8 Windows 11 No-Nos for Neophytes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-restore-functional-drag-and-drop-in-windows-11/"><u>Guide: Restore Functional Drag-and-Drop in Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-setting-up-your-amazon-firestick-with-applestv/"><u>Guide: Setting Up Your Amazon Firestick with ApplesTV</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-powertoys-for-seamless-international-mouse-usage/"><u>Harnessing PowerToys for Seamless International Mouse Usage</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-nubia-red-magic-9-proplus-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Nubia Red Magic 9 Pro+?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-msvcr120dll-missing-error-on-windows/"><u>How to Fix the Msvcr120.dll Missing Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-app-has-been-blocked-for-your-protection-error-on-windows/"><u>How to Fix This App Has Been Blocked for Your Protection Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-spur-microsoft-edge-speed-in-windows-1011/"><u>How to Spur Microsoft Edge Speed in Windows 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a24-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A24 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-oneplus-nord-n30-se-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On OnePlus Nord N30 SE? Fixed | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-lenovo-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Lenovo FRP Without Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/instant-printer-setup-with-canon-guided-examples/"><u>Instant Printer Setup with Canon - Guided Examples</u></a></li>
<li><a href="https://extra-support.techidaily.com/is-financial-compensation-behind-product-evaluations-in-2024/"><u>Is Financial Compensation Behind Product Evaluations, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multi-os-environments-windows-host-for-linux-virtual-machines/"><u>Mastering Multi-OS Environments: Windows Host for Linux Virtual Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-rainmeter-hiccups-with-easy-fixes/"><u>Mastering Window's Rainmeter Hiccups with Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wsl-enabling-linux-in-windows-environment/"><u>Mastering WSL: Enabling Linux in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/onoff-switch-controlling-windows-energy-saving-mode/"><u>On/Off Switch: Controlling Windows' Energy-Saving Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-wallet-growth-unlocking-windows-11-pro-offers/"><u>Optimize Wallet Growth - Unlocking Windows 11 Pro Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-selecting-superior-windows-11-drawers/"><u>Pro Tips: Selecting Superior Windows 11 Drawers</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-pc-management-utilizing-command-prompt-for-timely-detection-and-correction-of-windows-errors/"><u>Proactive PC Management: Utilizing Command Prompt for Timely Detection & Correction of Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/race-the-rate-unveiling-windows-techniques-for-measuring-ethernet-speed/"><u>Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-solo-side-headphones-to-windows-os/"><u>Reconnecting Solo Side Headphones to Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-your-input-cannot-be-opened-vlc-error-on-windows/"><u>Rectifying 'Your Input Cannot Be Opened' VLC Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-the-clock-actions-to-restore-windows-server-time/"><u>Resurrecting the Clock: Actions to Restore Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-indexers-control-accessibility/"><u>Revealing Indexer's Control Accessibility</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/snap-a-different-shot-11-best-instagram-tools/"><u>Snap A Different Shot - 11 Best Instagram Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-diagnostics-five-quick-steps-in-windows/"><u>Starting Diagnostics: Five Quick Steps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-toggle-online-scan-feature-of-modern-os/"><u>Steps to Toggle Online Scan Feature of Modern OS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/still-eager-for-a-personalized-bot-experience-check-these-awesome-open-source-apps-instead-of-waiting/"><u>Still Eager for a Personalized Bot Experience? Check These Awesome Open Source Apps Instead of Waiting</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronizing-seamlessly-accessing-cloud-storage-from-windows-directories/"><u>Synchronizing Seamlessly: Accessing Cloud Storage From Windows Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-guide-extending-windows-menu-options-in-xp-7-8-and-10/"><u>Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-real-deal-on-the-77-3d-printer-from-aliexpress-does-it-hold-up/"><u>The Real Deal on the $77 3D Printer From AliExpress – Does It Hold Up?</u></a></li>
<li><a href="https://windows11.techidaily.com/trail-clearing-techniques-deciphering-and-erasing-windows-history/"><u>Trail-Clearing Techniques: Deciphering and Erasing Windows History</u></a></li>
<li><a href="https://windows11.techidaily.com/trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-v-purse-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Honor V Purse Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-system-name-in-windows-11/"><u>Troubleshooting Invalid System Name in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/ultimate-recorder-options-for-livestreaming-on-youtube-for-2024/"><u>Ultimate Recorder Options for Livestreaming on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-premium-weather-apps-for-windows-11/"><u>Unveiling Premium Weather Apps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-addressing-discord-installation-issues/"><u>Win 11: Addressing Discord Installation Issues</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>