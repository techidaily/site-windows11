---
title: "Altering Windows Files: Date Creation & Modification Adjustments"
date: 2024-07-11T22:17:19.741Z
updated: 2024-07-12T22:17:19.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Windows Files: Date Creation & Modification Adjustments"
excerpt: "This Article Describes Altering Windows Files: Date Creation & Modification Adjustments"
keywords: File Date Edit Windows,Windows Change Creation Dates,Windows Modify Timestamp,Adjust File Date Windows,Customize Windows Time Stamps,Windows File Age Manipulation,Date Alteration in Windows Files
thumbnail: https://thmb.techidaily.com/d3b76096f4c9dcaff472cd20aa342807816191e8da2710c62b22806e55635c8b.jpg
---

## Altering Windows Files: Date Creation & Modification Adjustments

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
<li><a href="https://windows11.techidaily.com/master-your-gaming-journey-optimizing-ps1-experience-in-win-using-duckstations-guide/"><u>Master Your Gaming Journey: Optimizing PS1 Experience in WIN Using Duckstation's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-superior-video-encoders-for-windows-computing/"><u>Identifying Superior Video Encoders for Windows Computing</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-dated-wallpapers-triple-technique-trick/"><u>Ditch the Dated Wallpapers: Triple Technique Trick</u></a></li>
<li><a href="https://windows11.techidaily.com/from-vocal-inputs-to-text-output-a-comprehensible-guide-for-windows-users/"><u>From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-setup-of-microsofts-powertoys-win11/"><u>Effortless Setup of Microsoft's PowerToys (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-steps-for-finding-absent-registry-program/"><u>Immediate Steps for Finding Absent Registry Program</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-invisible-login-window-in-win1011/"><u>Quick Fix for Invisible Login Window in Win10/11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-s-best-free-dvd-player-software-for-windows-10-pcs/"><u>Updated 2024 Approved S Best Free DVD Player Software for Windows 10 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/shedding-windows-history-lightly-with-these-triads/"><u>Shedding Windows History Lightly with These Triads</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-ease-of-access-in-5-steps/"><u>Navigating to Windows Ease of Access in 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microphone-setup-with-the-latest-windows-11-features/"><u>Streamlining Microphone Setup with the Latest Windows 11 Features</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sophisticated-screen-capture-3-top-tier-techniques-for-zoom-conversion-for-2024/"><u>Sophisticated Screen Capture  3 Top-Tier Techniques for Zoom Conversion for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-8-free-online-tiktok-video-downloaders-no-watermark-included/"><u>[Updated] 8 Free Online TikTok Video Downloaders -No Watermark Included</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-an-attempt-was-made-to-reference-a-token-error-in-windows-1110/"><u>How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/shrouding-outage-with-code-0xc00d36b4-in-windows/"><u>Shrouding Outage with Code 0XC00D36B4 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-frustrations-of-code-1132-on-win-1011/"><u>Resolving the Frustrations of Code 1132 on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-raw-esd-to-refined-iso-windows-conversion-techniques/"><u>From Raw ESD to Refined ISO: Windows Conversion Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-image-browsing-into-file-explorer/"><u>Integrating Image Browsing Into File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-barriers-in-superuser-command-activation/"><u>Overcoming Barriers in Superuser Command Activation</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-adobe-premiere-vs-sony-vegas-which-video-editor-reigns-supreme/"><u>New 2024 Approved Adobe Premiere vs Sony Vegas Which Video Editor Reigns Supreme ?</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/an-insiders-look-6-exemplary-chrome-os-gadgets-for-exceptional-voice-alteration-experiences-creativesuitelumiere/"><u>An Insiders Look 6 Exemplary Chrome OS Gadgets for Exceptional Voice Alteration Experiences - CreativeSuiteLumiere</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/attraction-tactics-romantic-german-phrases/"><u>Attraction Tactics: Romantic German Phrases</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-productivity-essential-win11-and-command-tips-for-efficiency/"><u>Elevate Productivity: Essential Win11 and Command Tips for Efficiency</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-how-to-speed-up-video-on-instagram-mobileonlinedesktop-solutions/"><u>[New] How to Speed Up Video on Instagram [Mobile/Online/Desktop Solutions]</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-are-you-looking-for-funny-discord-emojis-to-massively-improve-your-discord-experience-using-some-fun-bots-for-discord-is-an-excellent-way-of-doing-that-/"><u>New Are You Looking for Funny Discord Emojis to Massively Improve Your Discord Experience? Using some Fun Bots for Discord Is an Excellent Way of Doing That! Thus, We Compiled a List of 10 Fun Discord Bots You Need</u></a></li>
<li><a href="https://windows11.techidaily.com/slashing-gpu-energy-on-desktop-window-manager/"><u>Slashing GPU Energy on Desktop Window Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-alt-key-code-issues-in-windows-systems/"><u>Solving ALT Key Code Issues in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-ahead-with-vivetool-on-windows-future-features/"><u>Getting Ahead with ViVeTool on Windows: Future Features</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-lava-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Lava Phones</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/video-editing-software-showdown-virtualdub-vs-the-best-free-alternatives-for-2024/"><u>Video Editing Software Showdown Virtualdub Vs. The Best Free Alternatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-restoring-bluetooth-visibility-win/"><u>Steps for Restoring Bluetooth Visibility WIN</u></a></li>
<li><a href="https://extra-information.techidaily.com/budget-friendly-ball-games-watch-and-edit-on-the-go/"><u>Budget-Friendly Ball Games  Watch & Edit on the Go</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/superior-mac-system-for-fusion-of-vehicle-soundscape-for-2024/"><u>Superior Mac System for Fusion of Vehicle Soundscape for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-efficient-mobile-methods-for-snapchat-archive/"><u>In 2024, Efficient Mobile Methods for Snapchat Archive</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-cutting-edge-premium-video-apps-for-windows-os/"><u>2024 Approved  Cutting Edge  Premium Video Apps for Windows OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-pro-level-mp3-cutting-discover-the-top-5-online-platforms/"><u>Updated 2024 Approved Pro-Level MP3 Cutting Discover the Top 5 Online Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-access-linux-forget-wsl/"><u>Direct Access: Linux, Forget WSL</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-evaluating-the-high-fidelity-soundscapes-cambridge-cxu-review-in-the-current-year/"><u>New Evaluating the High-Fidelity Soundscapes Cambridge CXU Review in the Current Year</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-solutions-for-error-0x80042306-during-system-restore/"><u>Expert Solutions for Error 0X80042306 During System Restore</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-vivo-s18e-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Vivo S18e Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-windows-11-search-top-11-fixes-here/"><u>Reignite Your Windows 11 Search: Top 11 Fixes Here</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-vimeo-visual-guide-an-in-depth-look-at-aspect-ratio-details/"><u>Updated The Ultimate Vimeo Visual Guide An In-Depth Look at Aspect Ratio Details</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-harmonizing-without-spending-the-ultimate-selection-of-no-fee-audio-mixing-programs/"><u>Updated Harmonizing Without Spending - The Ultimate Selection of No-Fee Audio Mixing Programs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-gourmet-grub-gurus-on-social-media-for-2024/"><u>[Updated] Gourmet Grub Gurus on Social Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-and-beautify-your-w11-desktop-with-ease/"><u>Simplify & Beautify Your W11 Desktop with Ease</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-dissecting-the-digital-language-meanings-of-fb-messengers-blue-emoji/"><u>[Updated] Dissecting the Digital Language  Meanings of FB Messenger’s Blue Emoji</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-optimizing-visual-content-adding-black-bar-and-box-to-facebook-videos/"><u>2024 Approved  Optimizing Visual Content  Adding Black Bar & Box to Facebook Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/sky-high-internet-beyond-100mbps-overcoming-windows-speed-ceiling/"><u>Sky-High Internet Beyond 100Mbps: Overcoming Windows' Speed Ceiling</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-efficiently-utilizing-discord-spoiler-features/"><u>In 2024, Efficiently Utilizing Discord Spoiler Features</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functional-link-to-mb-services-on-win11-devices/"><u>Restoring Functional Link to MB Services on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restart-and-streamline-windows-update-processes/"><u>How to Restart and Streamline Windows Update Processes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-honor-90-lite-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/experts-selection-7-best-windows-photos-apps-reviewed/"><u>Expert's Selection: 7 Best Windows Photos Apps Reviewed</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-14-plus-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Data from Apple iPhone 14 Plus to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-srt-and-mp4-synergy-expert-advice-edition/"><u>2024 Approved  SRT & MP4 Synergy  Expert Advice Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>How To Use Special Features - Virtual Location On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-explore-6-superior-nft-tools-for-artistic-innovation/"><u>[New] Explore 6 Superior NFT Tools for Artistic Innovation</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-solutions-to-the-display-startup-failure-issue/"><u>Effective Solutions to the “Display Startup Failure” Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-rectify-the-zero-x-error-on-windows-11s-mail-app/"><u>Method to Rectify the Zero X Error on Windows 11’S Mail App</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-streamlining-sound-a-look-at-the-best-5-directional-microphones-and-windshields/"><u>New In 2024, Streamlining Sound A Look at the Best 5 Directional Microphones and Windshields</u></a></li>
</ul></div>
