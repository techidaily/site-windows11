---
title: How to Defrag a Hard Disk Drive in Windows 11
date: 2024-11-18T02:31:59.669Z
updated: 2024-11-24T22:39:44.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Defrag a Hard Disk Drive in Windows 11
excerpt: This Article Describes How to Defrag a Hard Disk Drive in Windows 11
keywords: Windows 11 Defrag Guide,Disk Optimization Tips,Speed Up PC,Data Organization in Win11,Hard Drive Cleanup Windows,Enhance System Performance,Manage Disk Space Efficiently
thumbnail: https://thmb.techidaily.com/8614a77f9e633f7b68cb429db560c3992306d2b5be6c80ea6d2432a854e4bb42.jpg
---

## How to Defrag a Hard Disk Drive in Windows 11

 Adding and removing Windows software packages generates data fragmentation on your PC’s storage drive. The fragmented data gets scattered around across the drive, which reduces the overall storage efficiency. A hard disk drive gets slowed down when it has to read-write fragmented data more spread out across the storage.

 Defragging a drive reorganizes the fragmented data on it more efficiently by filling storage gaps. Doing so can boost a hard disk drive’s read-write speed since data is less spread out. This is how you can defrag a drive with Windows 11’s pre-installed defrag tools and the Defraggler software.

## How to Defrag a Hard Drive With the Optimize Drives App

 Defragment and Optimize Drives is one of the defrag tools included with Windows 11\. That’s a slightly basic defrag tool compared with some third-party alternatives. However, Optimize drives will probably be sufficient for most users and does at least include scheduling settings. You can manually analyze and defrag a hard drive with that utility as follows:

1. Click the**Search** box or magnifying glass button on Windows 11’s taskbar to bring a file finder tool.
2. Then input**Defragment and Optimize Drives** inside the search tool.
3. Select**Defragment and Optimize** drives to open that defrag tool.
4. Next, select your local disk (drive C) in the Optimize drives window.
5. Press the**Analyze drives** button. Then the utility will display a fragmentation percentage in the**Current Status** column.  
![The Optimize Drives window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/optimize-drives-window.jpg)
6. Select the**Optimize** option to defrag the drive.

 How much you need to defrag a drive depends on the fragmentation percentage figure shown in the**Current Status** column. If that’s less than the four percent mark, defragmentation isn’t particularly necessary and won’t make much difference. However, it’s worth defragging a drive with more than 10 percent fragmentation.

 To set a schedule for optimizing the C: drive, click the**Change settings** button. That will bring up an Optimize drive window that includes options with which you schedule automatic drive defragging. You may find the**Run on a schedule** checkbox there selected by default. However, select that setting if it’s not already enabled.

![The Run on a schedule checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-on-a-schedule-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can set the defrag frequency in the drop-down menu below that option. Click the**Frequency** drop-down menu to view its options. Then select**Daily** ,**Weekly** , or**Monthly** according to preference.

 If you’ve partitioned your HDD, you can select to optimize alternative drive partitions beyond C. Clicking**Choose** below the**Run on a schedule** setting will bring up a drive selection window. There you can select other drives for which to schedule regular optimization.

![The drive selection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/drive-selection-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Defrag a Hard Drive With the Command Prompt

 Alternatively, you can utilize a defragger command-line tool within the Command Prompt. That tool is more flexible because it has various parameters you can set in commands. This is how to defrag your hard drive with the Command Prompt in Windows 11.

1. Press**Win + X** key combination to view the Power User menu with various shortcuts.
2. Click**Windows Terminal (Admin)** to open that app with elevated privileges.
3. Next, press a**Ctrl** +**Shift** +**2** hotkey to[bring up Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) within Windows Terminal.
4. To analyze the drive first, input the following command and press**Return** :  
`defrag c: /a`
5. Then defragment the C: drive by executing this command:  
`defrag c:`  
![The defrag c command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/defrag-c-command.jpg)

 As mentioned, this command-line tool has numerous parameters for configuring the defragment operation. Those parameters give you extra optimization options and enable you to tweak the defragging more. You can view the parameter switches by inputting and executing this command:

`defrag /?`

 Entering that command displays a list of all parameters with explanations for them. You can input additional parameters to perform boot optimization, slab consolidation, retrim, and space consolidation operations. Look at the examples shown at the bottom of the list to see how to input defrag commands with parameters included.

![The defrag help command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/defrag-parameter-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Defrag a Hard Drive With Defraggler

 Piriform Defraggler is a more advanced drive optimization tool than Defragment and Optimize Drives, which you can utilize on Windows platforms dating back to XP. It enables you to defrag whole drive volumes, specific folders, or even single files. You can defrag a hard drive with Defraggler like this:

1. Open the[Defraggler](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2023029/https://www.ccleaner.com/defraggler) download page.
2. Select the**Download Free Version** option.
3. Double-click the**dfsetup222.exe** installer to bring up the Defraggler setup wizard.
4. If you want to configure the installation in any way, click the**Customization** option. Then you can change the folder path by clicking**More** \>**Browse** .
5. Select Defraggler’s**Install** option.  
![The Install button for Defraggler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-install-button2.jpg)
6. Click**Run Defraggler** in the Piriform window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Next, click the**Analyze** button to view a report with a fragmentation percentage figure.  
![The Defraggler tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-defraggler-tool.jpg)
8. Press the**Defrag** button. Or you click that button’s arrow to select**Quick defrag** if preferred.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Defraggler will then do its stuff and displays an active status for the defrag operation. The drive map shows different color squares for fragmented and non-fragmented blocks. While in operation, you’ll also see yellow and green squares for files read and written. Click the**Drive map** tab to view Defraggler’s color code index.

![The Drive Map tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/drive-map-tab.jpg)

 If you prefer to defrag a specific folder or file, click the**Actions** menu. Click either the**Defrag Folder** or**Defrag File** option there. Select a directory or file to optimize and click**OK** .

![The Action menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-action-menu.jpg)

 To set automatic drive optimization, click the**Settings** menu and select**Schedule** ; choose a drive in the drop-down menu and select**Schedule drive optimization for chosen volume** . Then choose one of the period options to configure according to preference. You can also select one of four optimization settings on the**Defrag type** drop-down menu. Click**OK** to set the schedule.

![The Schedule window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-schedule-window.jpg)

## Can I Defrag a Solid-State Drive?

 You can defrag an SSD drive with the tools in this guide, but it’s rather pointless. Solid-state drives are a different type of non-mechanical storage that’s faster than hard drives. Defragging such drives offers little to no performance benefit.

 Check out our article about[why you shouldn’t defrag SSDs](https://www.makeuseof.com/should-you-optimize-ssd/) for further details.

## Enhance Your PC’s HDD Efficiency in Windows 11

 Defragging your PC’s hard drive on a reasonably regular basis with the utilities covered above will make it an altogether faster and more responsive one. Once-the-month manual defrags will usually be sufficient for minimizing data fragmentation and maintaining optimal drive efficiency. Windows 11’s built-in tools are ok for drive optimization, but Defraggler offers the most extensive defrag options.

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
<li><a href="https://screen-recording.techidaily.com/new-multi-screen-recording-setup-for-2024/"><u>[New] Multi-Screen Recording Setup for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-quick-tips-for-setting-up-zoom-on-your-android-phonetablet/"><u>[New] Quick Tips for Setting Up Zoom on Your Android Phone/Tablet</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-the-ultimate-pp-playbook-for-silent-scene-transitions/"><u>[Updated] In 2024, The Ultimate PP Playbook for Silent Scene Transitions</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mcb-channel-background-and-template-set/"><u>2024 Approved MCB Channel Background & Template Set</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-in-windows-photo-editing/"><u>Advanced Techniques in Windows Photo Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-how-to-get-the-latest-realtek-asus-sound-card-drivers-on-windows-11/"><u>Easy Guide: How to Get the Latest Realtek Asus Sound Card Drivers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-apex-crashes-essential-steps-for-windows-11-gamers/"><u>Overcome Apex Crashes: Essential Steps for Windows 11 Gamers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/revolutionize-your-viewing-experience-with-the-cost-effective-amazonbasics-antenna/"><u>Revolutionize Your Viewing Experience with the Cost-Effective AmazonBasics Antenna!</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
</ul></div>

