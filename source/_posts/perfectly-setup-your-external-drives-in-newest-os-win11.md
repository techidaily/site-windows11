---
title: Perfectly Setup Your External Drives in Newest OS, Win11
date: 2024-09-05T02:17:53.729Z
updated: 2024-09-06T02:17:53.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Perfectly Setup Your External Drives in Newest OS, Win11
excerpt: This Article Describes Perfectly Setup Your External Drives in Newest OS, Win11
keywords: External Drive Setup Win11,New OS Drive Configuration,Optimize External Storage,New OS USB Settings,Secure Drives in Win11,Efficient Data Transfer,Win11 External Management
thumbnail: https://thmb.techidaily.com/b4a905fd890aa115ceaae449b319ec44a08a343a14b9f46ade584251a7832338.jpg
---

## Perfectly Setup Your External Drives in Newest OS, Win11

 Mapping a network drive helps you access shared folders and files on a network. It allows you to access such resources as if they were on your local computer, making it easy to work with files stored on a network.

 This can be particularly useful for businesses or organizations with multiple computers or servers that want to share files and resources between them easily.

 But is it really that simple to set up mapping? Keep reading to learn how to map a network drive in Windows 11 using different methods.

## Configure Network Discovery in Windows

 Windows has a feature called[network discovery](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) that allows your computer to discover and access other devices on the same network, such as computers, servers, and printers.

 This allows you to share any file or folder with other devices on the same network. Before mapping a network drive, make sure that network discovery is enabled on your computer.

Follow the sets below to enable network discovery on Windows:

1. Press**Win + I** to open the Settings app.
2. Head over to**Network & internet** from the left pane and click on**Advanced network settings** on the right.
3. Next, click on the**Advanced sharing settings** option under**More Settings** .  
![Windows Advanced Network Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-network-settings.jpg)
4. Open the**Private networks** settings and set the toggle next to**Network discovery** to**On** .  
![Windows Advanced Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-sharing-settings.jpg)
5. If you're looking to access a printer on the network, make sure to enable**File and printer sharing** .

 Once you turn on network discovery, other devices on the same network can see your computer and access it.

 Select**Private networks** if you are connected to a trusted network, such as your home network. But if you're connected to an unfamiliar network, you should select the**Public networks** option.

 Remember that enabling network discovery may make your computer more vulnerable to security risks as it allows other devices on the network to access your computer.

 Therefore, it's crucial to ensure that you have a strong password and[customize your default Windows Firewall](https://www.makeuseof.com/windows-firewall-control-guide/) to protect your device in case something goes wrong.

## 1\. Map a Network Drive Using File Explorer

 Once you have turned on network discovery, you can map a network drive in Windows 11 using File Explorer.

Here's what you need to do to use File Explorer for mapping:

1. Press**Win + E** to open File Explorer directly, and click on**This PC** in the left pane.
2. Right-click on**This PC** and select the**Map network drive...** button in the context menu that appears.  
![This PC Context Menu In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/this-pc-context-menu-in-windows.jpg)
3. Choose a unique drive letter in the**Map Network Drive** window. This is the drive you'll use to access the shared folder from your computer. As an example, we've selected**A:** as the drive letter.
4. Enter the path to the shared folder you want to map in the**Folder:** field. This can be a local path on the computer, such as**\\\\YourComputer\\SharedFolder** , or a network path, such as**\\\\ServerName\\SharedFolder** .  
![Windows Shared Network Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-shared-network-folder.jpg)
5. If you need a username and password to access the shared folder, check the**Connect using different credentials** box and enter the required information.
6. Click**Finish** to complete the mapping process.  
![Map Network Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/map-network-drive-in-windows.jpg)

 Once you have completed these steps, it'll map the folder to the specified drive letter in File Explorer. You can access the shared folder at any time by double-clicking on the drive.

 Want to access the shared folder in milliseconds? You can create a shortcut to the mapped network drive on your desktop for quick access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell for Mapping

 Windows PowerShell is a Windows command-line utility that provides a powerful set of tools and commands. One of the tasks you can perform using PowerShell is to map a network drive.

Follow these instructions to map a drive using Windows PowerShell:

1. Open the Start menu and type**PowerShell** into the search bar.
2. Select the best match and choose**Run as administrator.**
3. In the PowerShell window, type the following command, replacing**DRIVE** with the drive letter you want to use and**\\** **\\ServerName\\SharedFolder** with the path to the shared folder:  
New-PSDrive -Name DRIVE -PSProvider FileSystem -Root \\ServerName\SharedFolder  
![PowerShell Mapping Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powershell-mapping-command.jpg)
4. If the shared folder requires a username and password to access, you can add the -Credential parameter to the command, followed by a username and password in the format username and password. For example:  
New-PSDrive -Name X -PSProvider FileSystem -Root \\ServerName\SharedFolder -Credential username password
5. Hit**Enter** to allow PowerShell to map the network drive. You can access the mapped drive from File Explorer now.

 Besides mapping, you can do a wide range of things, like managing and automating tasks on Windows. For that, you must know some[useful PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030395/7443" target="_top" id="2030395">
  <img src="//a.impactradius-go.com/display-ad/7443-2030395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Command Prompt for Mapping

 Just like you used PowerShell earlier, you can use the Windows Command Prompt tool to map a network drive.

So, follow these simple instructions:

1. Open[Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type the command line given below, but replace**DRIVE** with any drive letter and**\\\\ServerName\\SharedFolder** with the shared folder's path:  
net use DRIVE \\ServerName\SharedFolder
3. If the shared folder requires a username and password to access, you can add the /user parameter to the command, followed by a username and password in the format**username** and**pass** . For example:  
net use DRIVE \\ServerName\SharedFolder /user:username pass  
![Mapping In Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/mapping-in-command-prompt.jpg)
4. Once you've made the required changes, hit**Enter** to execute the command.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it. It'll take a few seconds, and then you can access the mapped drive from File Explorer with one click.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disconnect a Mapped Network Drive

 Disconnecting the network drive is a no-brainer if you no longer need access to the files on it.

 Here's how you can disconnect a mapped network drive in a few steps:

1. Press**Win + E** to open File Explorer.
2. Right-click on**Network** in the left pane and choose**Disconnect network drive** from the context menu.  
![Disconnect Mapped Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disconnect-mapped-drive.jpg)
3. In the next window, choose the drive letter or name of the network drive you want to disconnect. Click**OK** to disconnect it from your system.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The mapped network drive will now disappear from File Explorer, and you can no longer access it from the drive letter you created earlier.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Map Network Drives Easily in Windows 11

 Mapping a network drive in Windows 11 is a great way to access shared folders on other computers or servers. This can save you time and make managing and organizing your files easier.

 While mapping is only useful in the case of network drives, there are many other methods to share files without a network setup. For example, you can use external storage, cloud storage services, a data transfer cable, etc.


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
<li><a href="https://facebook-video-files.techidaily.com/new-sync-facebook-media-for-larger-display-views-for-2024/"><u>[New] Sync Facebook Media for Larger Display Views for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-enhancing-community-management-with-discord-roles/"><u>[Updated] 2024 Approved  Enhancing Community Management with Discord Roles</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-achieving-financial-independence-on-youtube-via-views-for-2024/"><u>[Updated] Achieving Financial Independence on YouTube via Views for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-enhance-visibility-on-instagram-the-art-of-animated-texts-in-stories/"><u>[Updated] Enhance Visibility on Instagram  The Art of Animated Texts in Stories</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-event-harmony-sourcing-perfect-dj-video-templates-for-2024/"><u>[Updated] Event Harmony  Sourcing Perfect DJ Video Templates for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-project-management-fees/"><u>[Updated] Project Management Fees</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unseen-aspects-the-hidden-secrets-of-instagram-stories-viewers/"><u>[Updated] Unseen Aspects  The Hidden Secrets of Instagram Stories Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/1-enhance-your-site-with-complimentary-microsoft-live-widgets/"><u>1. Enhance Your Site with Complimentary Microsoft Live Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-excel-a-step-by-step-guide-on-implementing-the-less-than-or-equal-to-operator/"><u>1. Mastering Excel: A Step-by-Step Guide on Implementing the 'Less than or Equal To' Operator</u></a></li>
<li><a href="https://windows11.techidaily.com/1-swift-techniques-for-removing-empty-cells-in-microsoft-excel/"><u>1. Swift Techniques for Removing Empty Cells in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/11/"><u>11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-quality-recording-discovering-the-best-5-slow-video-cameras/"><u>2024 Approved  High-Quality Recording  Discovering the Best 5 Slow Video Cameras</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-masterful-mixing-video-and-melody-combinations-on-win11/"><u>2024 Approved  Masterful Mixing  Video & Melody Combinations on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/best-choice-streamline-your-youtube-audio/"><u>Best Choice  Streamline Your YouTube Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-spreadsheet-skills-with-these-three-hyperlink-techniques-in-excel/"><u>Boost Your Spreadsheet Skills with These Three Hyperlink Techniques in Excel</u></a></li>
<li><a href="https://fox-that.techidaily.com/bright-ideas-for-fixing-an-unresponsive-iphone-torch-in-just-12-steps/"><u>Bright Ideas for Fixing an Unresponsive iPhone Torch in Just 12 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/change-excel-gridlines-hue-a-comprehensive-tutorial/"><u>Change Excel Gridlines Hue: A Comprehensive Tutorial</u></a></li>
<li><a href="https://fox-glue.techidaily.com/crossing-the-line-at-winter-olympics-2022-for-2024/"><u>Crossing the Line at Winter Olympics, 2022 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-excels-latest-feature-pasting-data-without-unwanted-formatting-via-keyboard-shortcut/"><u>Discover Excel’s Latest Feature: Pasting Data without Unwanted Formatting via Keyboard Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-redesigned-look-of-microsofts-online-office-tools-an-updated-user-interface/"><u>Discover the Redesigned Look of Microsoft's Online Office Tools - An Updated User Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-expensive-software-mastering-project-management-with-just-excel/"><u>Ditch the Expensive Software - Mastering Project Management with Just Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-overcome-excel-blank-file-glitches-top-advice-for-a-smooth-solution/"><u>Easily Overcome Excel Blank File Glitches: Top Advice for a Smooth Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-implementing-macros-into-your-quick-access-toolbar/"><u>Easy Steps: Implementing Macros Into Your Quick Access Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-implementing-exponential-functions-in-microsoft-excel/"><u>Easy Techniques for Implementing Exponential Functions in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-setting-up-short-term-shared-worksheets-in-microsoft-excel/"><u>Effective Strategies for Setting Up Short-Term Shared Worksheets in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-for-deleting-hyperlinks-within-microsoft-excel-worksheets/"><u>Effective Techniques for Deleting Hyperlinks Within Microsoft Excel Worksheets</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-converting-dynamic-excel-equations-to-fixed-numbers-in-excel-2013/"><u>Efficiently Converting Dynamic Excel Equations to Fixed Numbers in Excel 2013</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-techniques-for-eliminating-borders-and-guides-in-your-excel-spreadsheets/"><u>Effortless Techniques for Eliminating Borders & Guides in Your Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-unit-transformation-techniques-with-microsoft-excel-tutorials/"><u>Effortless Unit Transformation Techniques with Microsoft Excel Tutorials</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevate-photography-with-essential-knowledge-of-luts/"><u>Elevate Photography with Essential Knowledge of LUTs</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-microsoft-excel-python-interpreter-latest-upgrade-improvements/"><u>Enhanced Microsoft Excel Python Interpreter: Latest Upgrade Improvements</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-clarity-in-ms-excel-visualizations-how-to-title-your-x-and-y-axes-effectively/"><u>Enhancing Clarity in MS Excel Visualizations - How to Title Your X & Y Axes Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-searches-with-vlookup-functionality-in-microsoft-excel-sheets/"><u>Expert Tips for Effective Searches with VLOOKUP Functionality in Microsoft Excel Sheets</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-capabilities-of-function-keys-in-microsoft-excel-a-comprehensive-guide/"><u>Exploring the Capabilities of Function Keys in Microsoft Excel: A Comprehensive Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-infinix-note-30i-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Infinix Note 30i? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Apply These Techniques to Improve How to Detect Fake GPS Location On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-easy-guide-to-entering-google-meet-on-devices/"><u>In 2024, Easy Guide to Entering Google Meet on Devices</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-elevate-your-tiktok-game-essential-analytics-tools-countdown/"><u>In 2024, Elevate Your TikTok Game - Essential Analytics Tools Countdown</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-realme-narzo-n55-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Realme Narzo N55 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-apple-iphone-11-pro-location-by-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 6 Apps/Services to Trace Any Apple iPhone 11 Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-canon-mf82cu-printer-drivers-available-for-download-on-microsoft-windows-platforms/"><u>Latest Canon MF82cu Printer Drivers Available for Download on Microsoft Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cell-references-seamlessly-linking-data-across-excel-workbooks/"><u>Mastering Cell References: Seamlessly Linking Data Across Excel Workbooks</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excels-essential-logical-operators-if-and-or-xor-and-not/"><u>Mastering Excel's Essential Logical Operators: IF, AND, OR, XOR, and NOT</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-number-formatting-how-to-precisely-add-prefixes-like-zeroes-in-excel-cells/"><u>Mastering Number Formatting: How To Precisely Add Prefixes Like Zeroes in Excel Cells</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-hidden-feature-starting-word-excel-and-powerpoint-with-enhanced-security-settings/"><u>Mastering the Hidden Feature: Starting Word, Excel, and PowerPoint with Enhanced Security Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-excels-latest-update-introduces-advanced-data-consolidation-features/"><u>Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-old-data-in-excel-a-step-by-step-guide/"><u>Restoring Old Data in Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/say-goodbye-to-tiktoks-post-upload-quality-issues-revolutionary-fixes-and-insights/"><u>Say Goodbye to TikTok's Post-Upload Quality Issues: Revolutionary Fixes and Insights!</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-dividing-data-across-several-excel-sheet-columns/"><u>Step-by-Step Guide: Dividing Data Across Several Excel Sheet Columns</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/targeted-approach-carving-out-your-space-on-youtube-for-2024/"><u>Targeted Approach  Carving Out Your Space on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-insights-in-numbers-a-guide-to-excel-quick-analysis-for-impactful-data-graphs-and-charts/"><u>Unlocking Insights in Numbers: A Guide to Excel Quick Analysis for Impactful Data Graphs and Charts</u></a></li>
</ul></div>
