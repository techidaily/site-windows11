---
title: "Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
date: 2024-09-09T12:08:35.486Z
updated: 2024-09-10T12:08:35.486Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
excerpt: "This Article Describes Unzipping & Zipping Made Easy: Windows Command Line Guidebook"
keywords: Command Line Zipping,Command Line Unzip,Windows Cmd Guide,Easy File Compression,Compress Files in Cmd,Zip Windows Commands,Unzipping Command Tools
thumbnail: https://thmb.techidaily.com/32e2647cfec7540fd7d33c1c66a7dde730efec2830801400ac767081505a0953.jpg
---

## Unzipping & Zipping Made Easy: Windows Command Line Guidebook

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://youtube-stream.techidaily.com/new-facing-copyright-challenges-on-youtube-know-your-rights/"><u>[New] Facing Copyright Challenges on YouTube Know Your Rights</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-steps-to-cure-intermittent-obs-frames/"><u>[Updated] 2024 Approved Steps to Cure Intermittent OBS Frames</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-video-lessons-to-vivid-engaging-gifs-no-download-needed/"><u>[Updated] From Video Lessons to Vivid, Engaging GIFs – No Download Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/1-crafting-personalized-borders-in-excel-a-step-by-step-guide/"><u>1. Crafting Personalized Borders in Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-inside-the-arsenal-the-complete-review-of-sj-cam-s6/"><u>2024 Approved Inside the Arsenal The Complete Review of SJ-CAM S6</u></a></li>
<li><a href="https://windows11.techidaily.com/arm-powered-windows-computers-get-official-chrome-support/"><u>ARM-Powered Windows Computers Get Official Chrome Support</u></a></li>
<li><a href="https://windows11.techidaily.com/best-budget-friendly-options-for-adobe-photoshop-and-illustrator-on-windows-systems/"><u>Best Budget-Friendly Options for Adobe Photoshop and Illustrator on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-analysis-and-ratings-keychron-kc3-chroma-wireless-mechanical-keyboard-premium-quality-at-excellent-value/"><u>Comprehensive Analysis & Ratings: Keychron KC3 Chroma Wireless Mechanical Keyboard – Premium Quality at Excellent Value!</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-microsoft-excels-innovative-integration-of-chatgpt-technology-for-enhanced-productivity/"><u>Discover Microsoft Excel's Innovative Integration of ChatGPT Technology for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-ultimate-free-utilities-for-tracking-and-managing-disk-usage-on-windows-systems/"><u>Discover the Ultimate Free Utilities for Tracking and Managing Disk Usage on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-ultimate-list-of-key-apps-your-windows-computer-needs-explained/"><u>Discover the Ultimate List of Key Apps Your Windows Computer Needs, Explained!</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-changing-sheet-names-in-microsoft-excel/"><u>Easy Steps for Changing Sheet Names in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-methods-to-modify-text-casing-in-microsoft-excel-2013-with-built-in-formulae/"><u>Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-for-merging-transforming-and-scaling-down-data-tables-in-microsoft-excel/"><u>Efficient Techniques for Merging, Transforming, and Scaling Down Data Tables in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-connectivity-experience-swap-out-microsoft-phone-link-with-our-exceptional-app/"><u>Elevate Your Connectivity Experience - Swap Out Microsoft Phone Link with Our Exceptional App!</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-14-features-why-google-sheets-outshines-microsoft-excel/"><u>Essential 14 Features: Why Google Sheets Outshines Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/excel-strategies-decoded-leveraging-pivot-tables-to-compute-percent-change-easily/"><u>Excel Strategies Decoded: Leveraging Pivot Tables to Compute Percent Change Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-on-isolating-month-and-year-values-from-date-entries-in-ms-excel-efficiently/"><u>Guide on Isolating Month and Year Values From Date Entries in MS Excel Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-altering-your-spreadsheets-cell-address-style-in-microsoft-excel/"><u>Guide: Altering Your Spreadsheet's Cell Address Style in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-creating-cross-sheet-references-within-your-microsoft-excel-workbooks/"><u>Guide: Creating Cross-Sheet References Within Your Microsoft Excel Workbooks</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-demonstrating-data-alterations-using-microsoft-excel-on-your-pc/"><u>Guide: Demonstrating Data Alterations Using Microsoft Excel on Your PC</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-can-life360-track-you-when-your-xiaomi-redmi-k70-pro-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Xiaomi Redmi K70 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-enter-the-ispoofer-discord-server-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to enter the iSpoofer discord server On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-proven-methods-for-conducting-outstanding-interviews/"><u>In 2024, Proven Methods for Conducting Outstanding Interviews</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-from-apple-iphone-13-mini-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock from Apple iPhone 13 mini</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-webinar-guide-host-without-spending/"><u>In 2024, YouTube Webinar Guide Host Without Spending</u></a></li>
<li><a href="https://windows11.techidaily.com/massive-microsoft-excel-online-edition-update-transforms-functionality/"><u>Massive Microsoft Excel Online Edition Update Transforms Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-conditional-logic-a-step-by-step-guide-to-microsoft-excels-if-statement/"><u>Mastering Conditional Logic: A Step-by-Step Guide to Microsoft Excel's IF Statement</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-currency-exchange-a-step-by-step-guide-to-converting-money-with-microsoft-excel/"><u>Mastering Currency Exchange: A Step-by-Step Guide to Converting Money with Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-data-type-templates-in-microsoft-excel-a-step-by-step-guide/"><u>Mastering Data Type Templates in Microsoft Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-microsoft-excel-a-comprehensive-guide-to-using-the-substitute-function/"><u>Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function</u></a></li>
<li><a href="https://windows11.techidaily.com/revamped-microsoft-office-web-suite-experience-the-latest-aesthetic-upgrade/"><u>Revamped Microsoft Office Web Suite: Experience the Latest Aesthetic Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/single-page-layout-mastering-the-art-of-condensing-excel-spreadsheets/"><u>Single-Page Layout: Mastering the Art of Condensing Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-adding-a-summary-row-at-the-end-of-your-microsoft-excel-tables/"><u>Step-by-Step Guide: Adding a Summary Row at the End of Your Microsoft Excel Tables</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-extracting-data-from-microsoft-excels-status-bar/"><u>Step-by-Step Guide: Extracting Data From Microsoft Excel's Status Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-integrating-windows-calculator-into-microsoft-excel-2013s-quick-access-bar/"><u>Step-by-Step Guide: Integrating Windows Calculator Into Microsoft Excel 2013'S Quick Access Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-using-excels-fill-handler-for-quick-sequential-data-entry/"><u>Step-by-Step Guide: Using Excel's Fill Handler for Quick Sequential Data Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-on-setting-fixed-columns-and-rows-in-microsoft-excel/"><u>Step-by-Step Tutorial on Setting Fixed Columns & Rows in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-constructing-self-updating-overview-charts-using-excel/"><u>Step-by-Step Tutorial: Constructing Self-Updating Overview Charts Using Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-critical-microsoft-excel-tools-you-need-for-effective-budget-management/"><u>Top 7 Critical Microsoft Excel Tools You Need for Effective Budget Management</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-from-hours-to-fractions-a-step-by-step-guide-on-converting-time-to-decimal-format-in-excel/"><u>Transitioning From Hours to Fractions: A Step-by-Step Guide on Converting Time to Decimal Format in Excel</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-updates-how-to-fix-service-not-running-error/"><u>Troubleshooting Windows Updates: How to Fix 'Service Not Running' Error</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-cartoonizer-apps-for-iphone-ipad-and-android-devices/"><u>Updated Top Cartoonizer Apps for iPhone, iPad, and Android Devices</u></a></li>
</ul></div>
