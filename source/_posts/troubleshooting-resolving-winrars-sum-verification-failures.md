---
title: "Troubleshooting: Resolving WinRAR's Sum Verification Failures"
date: 2024-10-11T16:02:05.463Z
updated: 2024-10-13T00:27:26.380Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Resolving WinRAR's Sum Verification Failures"
excerpt: "This Article Describes Troubleshooting: Resolving WinRAR's Sum Verification Failures"
keywords: Fix WinRAR Error,Sum Verify Fails,WinRAR Issue Help,WinRAR Validation,Resolve WinRAR Problems,Sum Check Failure,WinRAR Repair Guide
thumbnail: https://thmb.techidaily.com/718d1853d85918e9d3b7531d3e7e5d446b8b2d7ecc9512a603cf6d88a4e79188.jpg
---

## Troubleshooting: Resolving WinRAR's Sum Verification Failures

 Have you ever tried extracting an archive file using WinRAR only to encounter a checksum error? This error usually occurs when there's an issue with the archive file.

 Thankfully, you can try various troubleshooting methods to eliminate the checksum error in WinRAR. Let's check them out.

## What Is Checksum Error in WinRAR

 A checksum error in WinRAR occurs when the checksum value of your archive file doesn't match the expected value. WinRAR calculates the checksum value based on the content of your archive file, which helps ensure that your file doesn't contain any broken or corrupted segments.

 When the checksum value doesn't match the expected value, WinRAR fails to extract the file and throws the checksum error. There are a few possible reasons why the value doesn’t match, ultimately resulting in the checksum error.

* Your archive file is corrupt or contains broken segments.
* The files contain viruses or malware.
* The file was not downloaded properly from the source.

## 1\. Enable the Keep Broken Files Option

 By default, WinRAR automatically deletes the corruption in your archive file. While this feature generally works well, there are instances where it may delete segments that are essential for the extraction process, leading to a checksum error.

 To address this issue, enable WinRAR's Keep broken files feature, which prevents WinRAR from deleting broken or corrupt files during extraction.

 Follow these steps to enable the feature:

1. Right-click on the archive file, hover the cursor on **WinRAR**, and choose **Extract files** from the context menu.  
![Extract files option of WinRAR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extract-files-option.jpg)
2. Check the **Keep my files** option and click **OK**.  
![Keep my files option of WinRAR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option-2.jpg)

 WinRAR will now extract your archive file without deleting the corrupt or broken parts from it. After the extraction, you can [repair corrupted files in Windows](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) using different repair tools available on the market.

## 2\. Temporarily Disable the Security Program

 Often, the security program on your computer can interfere with WinRAR, causing it to display an error message. This usually occurs when the security program thinks the archive file contains malicious agents.

 In this case, the solution is to temporarily disable your antivirus program and then extract the file. However, only proceed with this step if you trust the archive file. If you use the Windows built-in antivirus, check our guide on [temporarily disabling Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/).

 On the other hand, if you are using a third-party security program, right-click on its icon in the system tray area and select **Disable** from the context menu. Once the file extraction is completed successfully, re-enable the security program.

 However, your antivirus might delete the extracted files, considering them threats to your computer. To prevent this from happening, [add the extracted file to Windows Security's exclusion list](https://www.makeuseof.com/windows-11-security-exclusions/). If you use a third-party antivirus program, check its user manual to learn how to add files to its exclusion list.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Archive File

 As aforementioned, the prime reason behind the WinRAR checksum error is corruption in the archive file. One way to deal with this is to [use the WinRAR built-in repair feature](http://www.makeuseof.com/windows-built-in-repair-tools/) to repair corrupt Windows files. The repair feature looks for corruption in the archive file and automatically repairs it using its repair mechanism.

 Follow these steps to repair your archive file:

1. Right-click on your archive file, hover the cursor to WinRAR, and choose the **Open with WinRAR** option.
2. Click the **Tools** tab at the top and choose the **Repair archive** option from the context menu.  
![Repair archive option in WinRAR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-archive-option.jpg)
3. Choose the **Treat the corrupt archive as RAR** option if your archive is a RAR file. Select the **Treat the corrupt archive as ZIP** option if it's a ZIP file. Then, click **OK**.  

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Repairing window of WinRAR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repairing-window.jpg)

 The WinRAR repair window will crop up and try to repair the archive file. After the process is complete, restart your computer, try to extract the file, and check if the error reappears. If yes, try the next solution on the list.

## 4\. Run a CHKDSK Scan

 Another prime reason for the error message could be bad sectors on your hard drive. To address this situation, you can [run a CHKDSK scan](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk?tabs=event-viewer).

 CHKDSK, aka Check Disk, is a utility that scans your hard drive for bad sectors, missing file metadata, and incorrect file types and sizes. If any issues are detected, it will try to repair them automatically.

 Follow these steps to run a CHKDSK scan:

1. Press the **Win** key to open the **Start** **Menu**, type **Command Prompt** in the search bar, and choose the **Run as administrator** option from the right pane. If this method doesn’t work, try other ways to [launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following command in the elevated Command Prompt window and press Enter. Make sure to replace C with the drive letter where the archive file is stored.  
chkdsk/r C:

![CHKDSK scan on Command Prompt window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan.jpg)

 The CHKDSK scan takes a long time to finish, so be patient. Once the scan is complete, restart your computer (see how to [restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/)) and check for the issue.

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Re-Download the Archive File

 If you continue to experience the error while extracting the file, it is likely due to an issue that occurred during the file download process. It's possible that you were disconnected from the internet while downloading the file or your computer experienced a sudden power cut.

 In this case, the best course of action is to re-download the archive file. If someone sent you the file via email, request them to resend it. If you downloaded the file from a website, revisit the website and initiate a fresh download of the file.

## 6\. Try a Different Extraction Tool

 If you’re still facing the checksum error even after trying the previous troubleshooting steps, the problem likely lies with WinRAR rather than the archive file. In such a scenario, you’re left with no option other than to use any other [extraction tool to extract your archive file](https://www.makeuseof.com/tag/the-top-3-file-compression-extraction-softwares/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the WinRAR Checksum Error

 WinRAR is a popular tool for compressing and extracting files. While it generally functions well, there are instances when it comes across problems that prevent successful file extraction.

 One such issue is the checksum error, which occurs when the archive file is corrupted. Fortunately, you can quickly troubleshoot this issue using the methods mentioned above.

 Thankfully, you can try various troubleshooting methods to eliminate the checksum error in WinRAR. Let's check them out.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-seamless-stories-from-the-past-accessing-older-fb-content-on-pcmobile/"><u>[New] 2024 Approved Seamless Stories From The Past Accessing Older FB Content on PC/Mobile</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-exploring-the-eminent-on-niche-focused-instagram-groups-for-2024/"><u>[New] Exploring the Eminent on Niche-Focused Instagram Groups for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-visionary-voices-triumph-online/"><u>[Updated] Visionary Voices Triumph Online</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-mastering-youtube-permanently-stop-video-snips-complete-guide/"><u>2024 Approved Mastering YouTube Permanently Stop Video Snips [Complete Guide]</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-personalized-branding-craft-your-logo-from-free-designs/"><u>2024 Approved Personalized Branding Craft Your Logo From Free Designs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensive-guide-to-azure-speech-to-text-implementation-for-2024/"><u>A Comprehensive Guide to Azure Speech-to-Text Implementation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-essence-of-windows-11s-registry-structure/"><u>Dissecting the Essence of Windows 11'S Registry Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/1719382274392-is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out</u></a></li>
<li><a href="https://buynow-info.techidaily.com/motorolas-moto-g-power-unveiled-remarkable-endurance-meets-smooth-functionality/"><u>Motorola's Moto G Power Unveiled: Remarkable Endurance Meets Smooth Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/perfect-your-strategy-top-rated-techniques-for-video-marketing/"><u>Perfect Your Strategy Top-Rated Techniques for Video Marketing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/professional-gif-designers-choice-list-for-2024/"><u>Professional GIF Designers' Choice List for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-faulty-cpu-usage-in-windows-management-console/"><u>Steps to Rectify Faulty CPU Usage in Windows Management Console</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
</ul></div>

