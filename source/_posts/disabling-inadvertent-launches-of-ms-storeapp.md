---
title: Disabling Inadvertent Launches of MS StoreApp
date: 2025-01-14T08:26:58.744Z
updated: 2025-01-16T11:25:03.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Inadvertent Launches of MS StoreApp
excerpt: This Article Describes Disabling Inadvertent Launches of MS StoreApp
keywords: Disable Unintentional MS Apps,Stop MS App Errors,Prevent MS App Crashes,Halt MS App Glitches,Avoid MS App Launch Mistakes,Fix MS Store App Triggers,Eliminate MS App Spontaneity
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Disabling Inadvertent Launches of MS StoreApp

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out [how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out [how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.

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
<li><a href="https://fox-access.techidaily.com/updated-mac-users-seamlessly-setting-up-streamlabs-in-obs/"><u>[Updated] Mac Users Seamlessly Setting Up Streamlabs in OBS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-proven-techniques-for-uploading-and-displaying-imovie-films-on-vimeo/"><u>[Updated] Proven Techniques for Uploading and Displaying iMovie Films on Vimeo</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-huawei-nova-y71-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Huawei Nova Y71 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/effortless-single-frame-analysis-in-youtube-videos-5-ways/"><u>Effortless Single-Frame Analysis in YouTube Videos [5 Ways]</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-depths-of-android-and-windows-file-sharing/"><u>Exploring the Depths of Android & Windows File Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-insights-windows-saver-mechanics-explained/"><u>Inside Insights: Windows Saver Mechanics Explained</u></a></li>
<li><a href="https://video-capture.techidaily.com/mastering-video-modifications-using-google-drive-a-guide-to-three-essential-approaches/"><u>Mastering Video Modifications Using Google Drive: A Guide to Three Essential Approaches</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/seamless-text-overlay-the-key-to-interactive-instagram-media/"><u>Seamless Text Overlay The Key to Interactive Instagram Media</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/v-joshis-blueprint-for-youtube-2024-income/"><u>Sourav Joshi's Blueprint for YouTube 2024 Income</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-implementing-pc-manager-in-w11/"><u>Step-by-Step: Implementing PC Manager in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-technical-conundrums-strategies-to-overcome-error-80080300-in-teammers/"><u>Unraveling Technical Conundrums: Strategies to Overcome Error 80080300 in Teammers</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-upgrade-protocols-a-comprehensive-guide-to-theme-alteration-in-win11/"><u>Visual Upgrade Protocols: A Comprehensive Guide to Theme Alteration in Win11</u></a></li>
</ul></div>

