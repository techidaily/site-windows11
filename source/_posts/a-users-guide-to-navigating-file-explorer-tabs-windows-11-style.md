---
title: A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
date: 2025-01-19T19:04:34.130Z
updated: 2025-01-22T18:01:51.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
excerpt: This Article Describes A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
keywords: File Explorer Navigation,Windows 11 File Explore,Tab Management in Win11,Navigate File Tabs W11,Guide to File Explorer Tabs,Using Windows 11 Explorer,Optimizing File Tab Usage
thumbnail: https://thmb.techidaily.com/26e5a5bed3537105229e89d2df536f43cfadace1d3a287d0f50c6226ff3d146f.png
---

## A User's Guide to Navigating File Explorer Tabs, Windows 11 Style

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and [check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily [download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Enable the Feature Using ViveTool

 Now, you have the Insider build running on your system. You will have to use the ViveTool to enable the hidden experimental feature to drag tabs out of the File Explorer. But first,[download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) and install the ViveTool on your system. After that, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) on your system.
2. Type**cmd** in the text input area and then press**Ctrl + Shift + Enter** key to launch the command prompt with admin privileges.
3. Now, locate the ViveTool directory using the**cd** command. We placed the ViveTool in a folder named Vive on C drive, So the command to change to that directory will be**cd\\** .
4. Once you are in the C directory, type**cd Vive** and press the**Enter** key.
5. After that, type**vivetool /enable /id:39661369** command and press the**Enter** key.  
![Enabling Tabs Dragging Feature In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-tabs-dragging-feature-in-file-explorer.jpg)
6. **Exit** the command prompt window after the ViveTool command executes successfully.
7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can You Restore the Tab to the File Explorer Window?

 Yes, you can indeed restore the dragged tab back to a File Explorer window. But the process is very clunky. You have to drag and hold the tab onto another open tab in a different File Explorer window.

 If you aren’t able to accurately position the tab, it will not merge with the File Explorer tab bar. In Chrome browser, dragging out and restoring them to the same window is pretty easy. You can even hover the tab and position it between two open tabs.

## Drag Tabs Out Like a Pro in File Explorer

 Microsoft is trying to make File Explorer more useful. But we cannot expect File Explorer to exactly work like a browser. After, it happens to be a means to access different types of files and open them with a compatible app or program in a new window. Still, dragging tabs out is a slick feature, and we hope Microsoft fixes the kinks and adds it in future updates.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-video-quality-from-youtube-to-crisp-avis-format/"><u>[New] 2024 Approved Elevate Video Quality From YouTube to Crisp Avis Format</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-photos-app-magic-crafting-stunningly-slow-motion-videos-online/"><u>[New] Photos App Magic Crafting Stunningly Slow-Motion Videos Online</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-patterned-pixels-looms-guide-to-screen-casting-for-2024/"><u>[Updated] Patterned Pixels Loom's Guide to Screen Casting for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-pc-games-memory-freeze-and-capture-6-ways-to-win-in-2024/"><u>[Updated] PC Games Memory - Freeze and Capture 6 Ways to Win, In 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-audio-mastery-in-visual-storytelling-vimeo-edition/"><u>2024 Approved Audio Mastery in Visual Storytelling Vimeo Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-for-correcting-lsassexe-issue/"><u>A Simple Guide for Correcting 'lsass.exe' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-for-enhanced-clarity/"><u>Customizing Graphics Output for Enhanced Clarity</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsoft-family-safety-functions/"><u>Demystifying Microsoft Family Safety Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/discover-9-innovative-nuxtjs-template-collection-by-creative-tim-for-effortless-web-development/"><u>Discover 9 Innovative NuxtJS Template Collection by Creative Tim for Effortless Web Development</u></a></li>
<li><a href="https://techtrends.techidaily.com/finding-legitimate-ways-to-see-spider-man-no-way-home-on-your-screen/"><u>Finding Legitimate Ways to See Spider-Man: No Way Home on Your Screen</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-iphone-14-plus-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of iPhone 14 Plus Prevention & Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/1719265109241-master-google-chromes-filesync-on-your-windows-device-now/"><u>Master Google Chrome's Filesync on Your Windows Device Now</u></a></li>
<li><a href="https://extra-skills.techidaily.com/professional-iphone-hdr-techniques-unveiled-for-2024/"><u>Professional iPhone HDR Techniques Unveiled for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-the-right-sources-for-safe-and-effective-view-count-increase/"><u>Trust the Right Sources for Safe and Effective View Count Increase</u></a></li>
</ul></div>

