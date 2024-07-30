---
title: "Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
date: 2024-07-29T04:21:56.925Z
updated: 2024-07-30T04:21:56.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
excerpt: "This Article Describes Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC"
keywords: Windows Cleanup Guide,PC Partition Removal,Optimize Hard Drive Space,Simplify PC Layout,Efficient Disk Management,Streamline Windows System,Unclutter PC Hardware
thumbnail: https://thmb.techidaily.com/fdc872e52961baec6923b458dbd6d98e67f3ed40f9ab2afdf7e0f1b821a0cc59.jpg
---

## Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-how-to-record-screen-with-ultra-screen-recorder/"><u>[New] In 2024, How to Record Screen With Ultra Screen Recorder</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-step-by-step-tutorial-to-elevate-your-slow-motion-videos-for-2024/"><u>[New] Step-by-Step Tutorial to Elevate Your Slow Motion Videos for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-professional-insights-for-perfecting-your-instagram-aesthetics-for-2024/"><u>[Updated] Professional Insights for Perfecting Your Instagram Aesthetics for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-streaming-service-comparison-facebook-live-vs-youtube-live-and-spaces/"><u>[Updated] Streaming Service Comparison  Facebook LIVE Vs. YouTube Live & Spaces</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-complete-laptop-recording-manual-dell-edition-for-2024/"><u>[Updated] The Complete Laptop Recording Manual  Dell Edition for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-navigate-your-way-to-joining-google-live-video-sessions/"><u>2024 Approved  Navigate Your Way to Joining Google Live Video Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/7-festive-tweaks-to-personalize-your-windows-11/"><u>7 Festive Tweaks to Personalize Your Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-wired-internet-beyond-100mbps-in-windows/"><u>Accelerating Wired Internet Beyond 100Mbps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-expert-guide-to-using-toolbar-on-w11-winpcm/"><u>Elevate Your Productivity: Expert Guide to Using Toolbar on W11 WinPCM</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-15-pro-max-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 15 Pro Max?</u></a></li>
<li><a href="https://windows11.techidaily.com/howto-unpacking-and-implementing-windows-compressed-archive-cab-files/"><u>Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/immersive-odyssey-top-10-best-free-mmorpgs-ever/"><u>Immersive Odyssey  Top 10 Best Free MMORPGs Ever</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-on-apple-iphone-7-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID On Apple iPhone 7 without Password?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-nubia-red-magic-9-pro-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Nubia Red Magic 9 Pro FRP</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mastering-content-capture-5-must-have-social-apps/"><u>Mastering Content Capture  5 Must-Have Social Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-mp3s-on-android-the-best-free-tools-for-2024/"><u>Mastering MP3s on Android - The Best Free Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quicker-quests-9-strategies-to-prevent-wwe-2k23-crashes/"><u>Quicker Quests: 9 Strategies to Prevent WWE 2K23 Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-credential-manager-login-issues/"><u>Resolve Credential Manager Login Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-common-errors-in-office-app-activation-on-pc/"><u>Resolving Common Errors in Office App Activation on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-oppo-reno-9a-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Oppo Reno 9A? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
