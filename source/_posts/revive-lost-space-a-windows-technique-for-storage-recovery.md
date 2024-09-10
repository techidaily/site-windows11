---
title: "Revive Lost Space: A Windows Technique for Storage Recovery"
date: 2024-09-09T12:08:34.108Z
updated: 2024-09-10T12:08:34.108Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Lost Space: A Windows Technique for Storage Recovery"
excerpt: "This Article Describes Revive Lost Space: A Windows Technique for Storage Recovery"
keywords: Storage Revival Guide,Windows Data Retrieval,Reclaiming Disk Space,WinStorage Rescue,Deleted Files Restore,Storage Optimization Tips,Maximize Disk Space
thumbnail: https://thmb.techidaily.com/20a1161c2d60e760a9d2866e0269161f0abce5bf45e09881a1912be2c7963695.jpg
---

## Revive Lost Space: A Windows Technique for Storage Recovery

### Key Takeaways

* altWinDirStat is a modified version of WinDirStat that offers higher speeds and a streamlined interface for analyzing storage space. It is a useful tool for locating large files.
* To download and install altWinDirStat, visit its page on GitHub and download the version that matches your PC's architecture. Since it does not require installation, you can save it to a folder or a USB flash drive for portable use.
* altWinDirStat directly scans the storage device's Master File Table (MFT) for faster analysis. To access the MFT, you need to run altWinDirStat as administrator. The app only takes seconds to analyze storage and present results.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121332/18498" target="_top" id="2121332">
  <img src="//a.impactradius-go.com/display-ad/18498-2121332" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121332/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.


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
<li><a href="https://facebook-video-recording.techidaily.com/new-driving-social-engagement-with-proper-configurations-of-fb-instream-ads/"><u>[New] Driving Social Engagement with Proper Configurations of FB Instream Ads</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-boosting-channel-earnings-the-step-by-step-famebit-guide-to-affiliates/"><u>[New] In 2024, Boosting Channel Earnings The Step-by-Step FameBit Guide to Affiliates</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-film-your-facebook-video/"><u>[New] In 2024, Film Your FACEbook Video</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mac-enhanced-a-dive-into-screenflows-capabilities-for-2024/"><u>[New] Mac Enhanced A Dive Into ScreenFlow's Capabilities for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-premium-free-mobile-photography-tools-for-slow-movement-effect/"><u>[Updated] Premium Free Mobile Photography Tools for Slow Movement Effect</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-reversal-strategies-moving-from-latest-sierra-to-el-capitan/"><u>[Updated] Reversal Strategies Moving From Latest Sierra to El Capitan</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-error-free-excel-sheets-a-step-by-step-guide-to-automatic-spelling-correction/"><u>1. Mastering Error-Free Excel Sheets: A Step-by-Step Guide to Automatic Spelling Correction</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-image-to-excel-conversion-a-step-by-step-guide-for-microsoft-windows/"><u>1. Mastering Image-to-Excel Conversion: A Step-by-Step Guide for Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/1-seamless-integration-microsoft-office-and-libreoffice-working-together-smoothly/"><u>1. Seamless Integration: Microsoft Office and LibreOffice Working Together Smoothly</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-concealed-aspects-understanding-the-unique-stories-of-followers/"><u>2024 Approved The Concealed Aspects Understanding the Unique Stories of Followers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-asus-rog-phone-8-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Asus ROG Phone 8 Without Power Button | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-zte-blade-a73-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix ZTE Blade A73 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://solve-lab.techidaily.com/1725289313045-dvd/"><u>全容マスター! DVD/動画・音声ファイルを一発で再生する究極テクニック</u></a></li>
<li><a href="https://windows11.techidaily.com/beginning-your-journey-with-windows-live-mesh-2011-the-ultimate-guide-for-seamless-data-management/"><u>Beginning Your Journey with Windows Live Mesh 2011 – The Ultimate Guide for Seamless Data Management</u></a></li>
<li><a href="https://windows11.techidaily.com/check-out-the-most-recent-updates-to-microsoft-office-suite-whats-new/"><u>Check Out the Most Recent Updates to Microsoft Office Suite: What's New?</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-guide-securing-data-with-cell-locking-techniques-in-excel/"><u>Complete Guide: Securing Data with Cell Locking Techniques in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-tracking-edits-and-modifications-in-real-time-with-excel-online/"><u>Effective Strategies for Tracking Edits and Modifications in Real-Time with Excel Online</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-to-compress-data-within-cells-using-microsoft-excel/"><u>Effective Techniques to Compress Data Within Cells Using Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-methods-for-identifying-and-enclosing-erroneous-data-points-in-microsoft-excel/"><u>Efficient Methods for Identifying and Enclosing Erroneous Data Points in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-planning-tasks-using-excels-gantt-chart-technique/"><u>Efficiently Planning Tasks Using Excel's Gantt Chart Technique</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embarkation-on-arabic-learning-journey/"><u>Embarkation on Arabic Learning Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-data-visualization-tutorial-on-secondary-axis-management-in-excel-charts/"><u>Enhancing Your Data Visualization: Tutorial on Secondary Axis Management in Excel Charts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-incompatible-data-entry-showing-up-on-screen/"><u>Error Resolution: Incompatible Data Entry Showing Up on Screen</u></a></li>
<li><a href="https://youtube-help.techidaily.com/fixing-non-appearing-thumbnails-in-youtube-shorts-for-2024/"><u>Fixing Non-Appearing Thumbnails in YouTube Shorts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/honesty-required-secure-your-exclusive-50-discount-on-microsoft-365-today/"><u>Honesty Required: Secure Your Exclusive 50% Discount on Microsoft 365 Today!</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-14-pro-max-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone 14 Pro Max Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-how-to-download-vimeo-video-to-mp3/"><u>In 2024, How to Download Vimeo Video to MP3</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Lava Yuva 3 Pro? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-rotate-your-mov-files-for-free-top-5-options/"><u>In 2024, Rotate Your MOV Files for Free Top 5 Options</u></a></li>
<li><a href="https://windows11.techidaily.com/master-microsoft-excel-a-comprehensive-guide-with-12-tricks-for-correcting-faulty-formulas/"><u>Master Microsoft Excel: A Comprehensive Guide with 12 Tricks for Correcting Faulty Formulas</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excel-a-step-by-step-guide-to-searching-and-substituting-text-and-numbers/"><u>Mastering Excel: A Step-by-Step Guide to Searching and Substituting Text & Numbers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-pubg-sounds-simple-tips/"><u>Mastering PUBG Sounds Simple Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unit-conversions-a-step-by-step-guide-using-microsoft-excel/"><u>Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-streamline-your-audio-capture-with-these-top-5-mp3-specific-recording-devices/"><u>New Streamline Your Audio Capture with These Top 5 MP3-Specific Recording Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-surprises-how-microsoft-excel-stops-forcing-dates-on-you/"><u>No More Surprises: How Microsoft Excel Stops Forcing Dates on You</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/seamless-graphic-driver-update-procedure-for-windows-11-users/"><u>Seamless Graphic Driver Update Procedure for Windows 11 Users</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-vivo-y56-5g-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Vivo Y56 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-adding-images-to-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Adding Images to Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-creating-and-personalizing-your-own-signature-block-in-excel/"><u>Step-by-Step Guide: Creating & Personalizing Your Own Signature Block in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-generating-word-mailing-labels-using-your-excel-spreadsheet/"><u>Step-by-Step Guide: Generating Word Mailing Labels Using Your Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-properly-formatting-telephone-digits-in-excel-spreadsheets/"><u>Step-by-Step Guide: Properly Formatting Telephone Digits in Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-removing-a-pivottable-from-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Removing a PivotTable From Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-on-arranging-data-values-within-microsoft-excel/"><u>Step-by-Step Tutorial on Arranging Data Values Within Microsoft Excel</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-checklist-for-efficiently-uploading-tracks-on-youtube-for-2024/"><u>The Ultimate Checklist for Efficiently Uploading Tracks on YouTube for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-ipad-sms-tutorial-send-and-receive-effortlessly/"><u>The Ultimate iPad SMS Tutorial: Send and Receive Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-on-leveraging-sumif-in-excel-techniques-and-strategies-for-effective-data-analysis/"><u>The Ultimate Tutorial on Leveraging SUMIF in Excel: Techniques and Strategies for Effective Data Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/top-13-essential-microsoft-excel-datetime-formulas-every-user-must-master/"><u>Top 13 Essential Microsoft Excel Date/Time Formulas Every User Must Master</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-tips-for-creating-simple-and-legible-excel-sheets/"><u>Top 6 Tips for Creating Simple and Legible Excel Sheets</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-productivity-microsoft-office-suite-available-in-immersive-quest-vr-experience/"><u>Transform Your Productivity: Microsoft Office Suite Available in Immersive Quest VR Experience!</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-guide-to-harnessing-the-power-of-goal-seek-in-excel/"><u>Ultimate Guide to Harnessing the Power of Goal Seek in Excel</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-apple-iphone-xr-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and Apple iPhone XR</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-automatic-data-coloring-tips-for-setting-up-excels-conditional-formatting-rules/"><u>Unlocking the Power of Automatic Data Coloring: Tips for Setting Up Excel's Conditional Formatting Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-latest-update-excels-enhanced-task-automation-on-windows/"><u>Unveiling the Latest Update: Excel's Enhanced Task Automation on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-locating-data-positions-with-excel-match-function-a-comprehensive-guide/"><u>Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-your-logitech-usb-headset-drivers-quickly/"><u>Update Your Logitech USB Headset Drivers Quickly</u></a></li>
</ul></div>
