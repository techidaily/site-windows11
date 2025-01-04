---
title: Expert Guide to Interpreting System Messages with Microsoft on W11
date: 2024-12-29T02:05:20.363Z
updated: 2025-01-04T01:18:15.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Guide to Interpreting System Messages with Microsoft on W11
excerpt: This Article Describes Expert Guide to Interpreting System Messages with Microsoft on W11
keywords: MSFT Message Troubleshooting,W11 Error Codes Explanation,Windows 11 System Logs,Interpret MSG Messages,Microsoft Console Debugging,IT Support for W11 Issues,Diagnose Win11 Problems
thumbnail: https://thmb.techidaily.com/8ab6ea565c08148258cccefd3c4e69bde02c4b3dbfe57b65bd55e5629cfc57b6.jpg
---

## Expert Guide to Interpreting System Messages with Microsoft on W11

 Windows operating system is far from perfect and encounters errors frequently. While Microsoft releases updates to fix widespread errors, some errors require a different tweaking approach to fix them. However, whenever you see an error code, the first idea is to note it down and search for it online.

 But do you know you can look up error codes in Windows 11? Microsoft offers an error lookup tool using which you can check for any error that pops up on your Windows PC. Without further ado, let's explore this wonderful tool and learn how to check error codes with it.

## What Is the Microsoft Error Lookup Tool?

 Microsoft Error Lookup tool does exactly what it sounds like. You can look up system error codes using this tool to get an idea of what the error code is really about. However, this is a command-line tool, so you need to use Command Prompt to run it. Microsoft is yet to release a GUI version of this tool, which could make searching for error codes for non-tech-savvy users convenient.

 Using a simple command, you can search and learn more about the nature of the error code. Microsoft Error Lookup tool is only available for Windows OS versions 8.1 and above. So, if you are still using Windows 7, searching the web remains your only option.

## How to Download and Run Microsoft Error Lookup Tool

 Microsoft Error Lookup is a lightweight command-line tool. You don’t need a copious amount of system resources to run it on your system. Here’s how to download and set up the tool on your system:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Downloading and Renaming the Tool

 Repeat the following steps to download and install the Microsoft Error Lookup tool:

1. Launch a web browser on your system and visit the[Microsoft Error Lookup Tool download page](https://www.microsoft.com/en-us/download/details.aspx?id=100432) .
2. Scroll down and click on the Download button. It will take a few seconds for the download to complete.
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the Microsoft Error Lookup Tool executable file download location.
4. Since it is a command-line tool, you will have to run it by typing its full name. The default download name is**Err\_6.4.5** which will be trouble to remember and type correctly every time in the Command Prompt. So, we will rename it to something easier like**Err** .
5. Right-click on the Microsoft Error Lookup tool executable file and select**Show more options** .  
![Renaming Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/renaming-microsoft-error-lookup-tool.jpg)
6. Then, click on the**Rename** option from the context menu. Type**Err** and press the enter key to rename the tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Placing the Tool in a Convenient Location

 You can only run the Microsoft Error Lookup Tool from the command line. If you place it in a deeply nested path like a folder inside a directory, you will have to navigate to that directory from the command line every time. So, you must move the tool to an accessible location first.

Here’s how to do it:

1. Press**Win + E** to open File Explorer and navigate to the Microsoft Error Lookup Tool download location. Now, press**Ctrl + C** to copy the file.
2. Go to the C drive and paste the tool. Grant permissions to place the tool in C drive.  
![Placing Microsoft Error Lookup Tool in C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/placing-microsoft-error-lookup-tool-in-c-drive.jpg)
3. Now, press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** in the text box and press enter key.

4. In the Command Prompt window, type the following command and press the enter key:**cd C:\\** .
5. Now, you will be in the parent directory. Type**Err** and press enter.  
![Running Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-microsoft-error-lookup-tool.jpg)
6. Microsoft Error Lookup Tool will run and display the format to look up error codes along with other available parameters. Don’t close the tool yet.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Error Codes Using Microsoft Error Lookup Tool

 Now, you have the Microsoft Error Lookup Tool up and running on your system. All you need to do is run appropriate commands to view information about error codes. Here’s how:

1. In the same Command Prompt window, you must type**\[Tool name\] \[error code\]** and press the enter key.
2. Suppose you want to look up the error code 0x80070490 using the tool. So, the correct command will be:**Err 0x80070490** .  
![Checking an Error Code in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-an-error-code-in-microsoft-error-lookup-tool.jpg)
3. Press the enter key and the tool will display all the matching information it has about the error code. It will include the exact error string and a sentence describing the meaning. Often, it will also try to make suggestions to fix the error.

 An error code can have multiple meanings and the error lookup tool will list all of them. You can use this information to narrow down your search and try to fix the issue.

## How to Export the Output of Microsoft Error Code Tool

 The tools can output multiple matches for an error code and that information becomes difficult to scroll in the Command Prompt window. But we can export the results of the error code lookup to a text file on your system.

Repeat the following steps:

1. Press**Win + S** and type CMD. Click on the**Run as administrator** option.
2. Now, type the following command to navigate to the error lookup tool location:**cd C:\\**
3. The syntax for copying the error code lookup results is:**Err \[Error code\] > \[Path of text file\]** .
4. So, your final command will become:**Err 0x80070490 > D:\\error.txt** .  
![Exporting Error Code Lookup results in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-microsoft-error-lookup-tool.jpg)
5. It will export the results to the text file named error on D drive. If the file doesn’t exist, the tool will create it with the same name. However, it won’t display any search result in the Command Prompt and just display the number of matches found.  

![Exporting Error Code Lookup results in a text file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-a-text-file.jpg)

 Now, open the file, and you can read the entire list of error code results and begin troubleshooting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can the Microsoft Error Lookup Tool Display Information About All Error Codes?

 Microsoft updates the tool to the latest version in 2019\. Since then, it hasn’t received an update. So, as newer builds or a[new version of Windows](https://www.makeuseof.com/windows-12-improve-upon-windows-11/) comes out, the tool may fail to produce results for a specific error code. But the chances of that are very slim. Moreover, it contains information only about Windows and some other Microsoft error codes. Don’t expect it to display information about errors you face inside a third-party application or program.

 So, you can use the error lookup tool without any worries and patiently wait for Microsoft to release a new build. You can check for the latest available build by visiting the official download page of the Microsoft Error Lookup Tool. Or, you can try a bunch of third-party options like Winerr or Error Lookup Tool for a more presentable error code lookup and troubleshooting experience.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Lookup Error Details With Ease

 Microsoft Error Lookup Tool is a free tool that you can easily run on your system. Surely, you won’t get a very descriptive troubleshooting guide with it. But you will still be able to find the issue and error string related to it, and even a suggestion, if the tool has one.

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
<li><a href="https://fox-links.techidaily.com/new-comprehensive-picsart-breakdown-for-2024/"><u>[New] Comprehensive PicsArt Breakdown for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-the-ultimate-guide-clearing-out-the-unwanted-space-around-images-with-affinity-for-2024/"><u>[New] The Ultimate Guide Clearing Out the Unwanted Space Around Images with Affinity for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-vanguard-of-virtual-fame-instagrams-25-luminaries/"><u>[Updated] In 2024, The Vanguard of Virtual Fame Instagram's 25 Luminaries</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-restarting-disrupted-streams-on-fb-fixes-for-todays-broadcasters/"><u>2024 Approved Restarting Disrupted Streams on FB Fixes for Today's Broadcasters</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-how-you-handle-deleted-items-on-pc/"><u>Adjusting How You Handle Deleted Items on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-fps-supercharge-yuzu-for-windows/"><u>Boosting FPS: Supercharge Yuzu for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-game-freeze-with-these-tips/"><u>Bypassing Game Freeze with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-tpm-in-win11-the-ultimate-rufus-technique/"><u>Bypassing TPM in Win11: The Ultimate Rufus Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dealing-with-steam-installation-fiascos-win11-style/"><u>Decoding and Dealing with Steam Installation Fiascos, Win11-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-phonelinkexe-important-for-windows-users/"><u>Disabling PhoneLink.exe: Important for Windows Users?</u></a></li>
<li><a href="https://win-workspace.techidaily.com/entfernungs-anleitungen-fur-den-systemsteuerungspapierkorb-unter-windows-10/"><u>Entfernungs-Anleitungen Für Den Systemsteuerungspapierkorb Unter Windows 10</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-tecno-camon-20-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Tecno Camon 20 in Minutes | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-130-music-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Nokia 130 Music Phone without PIN</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-free-tools-for-youtube-audio-conversion-to-wav-for-2024/"><u>Top 4 Free Tools for YouTube Audio Conversion to WAV for 2024</u></a></li>
</ul></div>

