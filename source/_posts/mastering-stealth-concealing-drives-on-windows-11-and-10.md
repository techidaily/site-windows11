---
title: "Mastering Stealth: Concealing Drives on Windows 11 & 10"
date: 2024-09-09T12:08:38.120Z
updated: 2024-09-10T12:08:38.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Stealth: Concealing Drives on Windows 11 & 10"
excerpt: "This Article Describes Mastering Stealth: Concealing Drives on Windows 11 & 10"
keywords: Stealth Drive Hide,Windows Drive Conceal,Secure Data Windows,PC Drive Privacy Tips,Stealthy Storage Solutions,Hidden Drives Windows,Data Security Stealth
thumbnail: https://thmb.techidaily.com/696965aa1a0f4c21fdfd456761bb63f354f50ffc3b27173b44a827d0fae8995e.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Mastering Stealth: Concealing Drives on Windows 11 & 10

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you complete the above steps, your drive will no longer appear in File Explorer.

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on[how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful[not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118304/7443" target="_top" id="2118304">
  <img src="//a.impactradius-go.com/display-ad/7443-2118304" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118304/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-how-to-make-a-fortune-on-reddit-without-experience-top-13-methods/"><u>[New] 2024 Approved How to Make a Fortune on Reddit Without Experience - Top 13 Methods</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-earning-insights-from-viewing-data-on-youtube/"><u>[New] In 2024, Earning Insights From Viewing Data on YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-secrets-unveiled-creating-professional-srt-files/"><u>[New] Secrets Unveiled Creating Professional SRT Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-streamline-your-twitch-live-recordings-today-for-2024/"><u>[New] Streamline Your Twitch Live Recordings Today for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-essential-techniques-for-mac-based-ootd-tiktok-videos/"><u>[Updated] Essential Techniques for Mac-Based OOTD TikTok Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-saturation-savvy-3-effective-methods-for-photocolor-evolution/"><u>2024 Approved Saturation Savvy 3 Effective Methods for PhotoColor Evolution</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/a-step-by-step-guide-turning-viral-soundtracks-into-personal-ringtones/"><u>A Step-by-Step Guide Turning Viral Soundtracks Into Personal Ringtones</u></a></li>
<li><a href="https://windows11.techidaily.com/affordable-and-durable-storage-solutions-below-100/"><u>Affordable and Durable Storage Solutions Below $100</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-enhanced-microsoft-teams-transforming-your-virtual-background-easily/"><u>AI-Enhanced Microsoft Teams: Transforming Your Virtual Background Easily</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/boost-your-site-with-cookiebot-the-ultimate-marketing-automation-tool/"><u>Boost Your Site with Cookiebot: The Ultimate Marketing Automation Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/create-an-eye-catching-custom-windows-desktop-with-rainmeter-tips/"><u>Create an Eye-Catching Custom Windows Desktop with Rainmeter Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-improved-voice-modulation-in-the-latest-version-of-microsoft-clipchamp/"><u>Discover Improved Voice Modulation in the Latest Version of Microsoft Clipchamp</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-system-overload-in-your-linux-vmware-by-regaining-lost-storage-capacity-quickly/"><u>Ease System Overload in Your Linux Vmware by Regaining Lost Storage Capacity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-to-address-and-correct-dpc-watchdog-errors-in-windows-10-systems/"><u>Effective Strategies to Address and Correct DPC Watchdog Errors in Windows 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-for-forcing-shut-down-non-responsive-programs-in-windows-11/"><u>Effective Techniques for Forcing Shut Down Non-Responsive Programs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-file-management-game-top-4-advanced-techniques-for-windows-11-tab-users/"><u>Elevate Your File Management Game: Top 4 Advanced Techniques for Windows 11 Tab Users</u></a></li>
<li><a href="https://windows11.techidaily.com/elgato-stream-deck-neo-review-initial-thoughts-and-unboxing-experience/"><u>Elgato Stream Deck Neo Review - Initial Thoughts and Unboxing Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-the-elegance-of-onsite-data-duplication-a-guide-to-local-backups/"><u>Embracing the Elegance of Onsite Data Duplication: A Guide to Local Backups</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-network-protection-with-microsofts-newly-integrated-zero-trust-dns-technology/"><u>Enhancing Windows Network Protection with Microsoft's Newly Integrated Zero Trust DNS Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-navigation-with-superior-file-management/"><u>Enhancing Your Windows Navigation with Superior File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/expanded-access-microsoft-now-supports-more-devices-with-windows-11-upgrade/"><u>Expanded Access: Microsoft Now Supports More Devices with Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11-on-arm-a-comprehensive-guide-and-its-differences-from-traditional-windows-systems/"><u>Exploring Windows 11 on ARM: A Comprehensive Guide & Its Differences From Traditional Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-support-for-individuals-and-businesses/"><u>Financial Support for Individuals and Businesses</u></a></li>
<li><a href="https://windows11.techidaily.com/from-doubts-to-discovery-why-the-old-concerns-of-switching-from-windows-to-linux-have-been-disproven/"><u>From Doubts to Discovery: Why the Old Concerns of Switching From Windows to Linux Have Been Disproven</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-nokia-c12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-arm-technology-an-unboxing-and-review-of-the-dell-inspiron-14-plus-7441/"><u>Getting Started with ARM Technology: An Unboxing and Review of the Dell Inspiron 14 Plus (7441)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-cybercriminals-exploit-windows-updates-to-bypass-security-fixes/"><u>How Cybercriminals Exploit Windows Updates to Bypass Security Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-apple-iphone-13-mini-passcode-not-working-drfone-by-drfone-ios/"><u>How to Fix Apple iPhone 13 mini Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-booting-issues-a-step-by-step-guide/"><u>How to Fix Windows Booting Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-xiaomi-14-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Xiaomi 14</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-your-android-device-into-a-windows-11-camera-a-step-by-step-guide/"><u>How to Turn Your Android Device Into a Windows 11 Camera: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-update-24h2-compatible-with-your-system-detailed-insights/"><u>Is Windows 11 Update 24H2 Compatible with Your System? Detailed Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/latest-security-features-in-version-127-of-google-chrome-enhanced-malware-defense/"><u>Latest Security Features in Version 127 of Google Chrome: Enhanced Malware Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/local-backup-mastery-unveiling-the-charm-and-reliability-of-in-house-data-replicas/"><u>Local Backup Mastery: Unveiling the Charm and Reliability of In-House Data Replicas</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-control-a-step-by-step-tutorial-for-blocking-microsoft-marketing-features-in-windows-11/"><u>Master the Control: A Step-by-Step Tutorial for Blocking Microsoft Marketing Features in Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/form-ideas-into-visuals-free-templates-for-video-makers-for-2024/"><u>Transform Ideas Into Visuals Free Templates for Video Makers for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/ultimate-guide-expanding-your-nes-classic-mini-game-library/"><u>Ultimate Guide: Expanding Your NES Classic Mini Game Library</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-vivo-y36-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Vivo Y36 | Dr.fone</u></a></li>
</ul></div>
