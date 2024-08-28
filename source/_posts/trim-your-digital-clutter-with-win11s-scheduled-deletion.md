---
title: Trim Your Digital Clutter with Win11's Scheduled Deletion
date: 2024-08-27T16:10:37.735Z
updated: 2024-08-28T16:10:37.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trim Your Digital Clutter with Win11's Scheduled Deletion
excerpt: This Article Describes Trim Your Digital Clutter with Win11's Scheduled Deletion
keywords: Win11 Cleanup,Delete Schedule,Digital Decluttering,Windows 11 Tidy,Clutter Removal,Deletion Automation,File Management Pro
thumbnail: https://thmb.techidaily.com/0de78e74e4231d077c0bbd1093422fc13ce8314c6f52350885d9fed67ecbab12.jpg
---

## Trim Your Digital Clutter with Win11's Scheduled Deletion

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-journey-through-gaming-landscapes-with-kinemaster-and-discover-its-best-competitors/"><u>[New] Journey Through Gaming Landscapes with KineMaster & Discover Its Best Competitors</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-a-step-by-step-roadmap-for-lasting-tiktok-account-loss/"><u>[Updated] In 2024, A Step-by-Step Roadmap for Lasting TikTok Account Loss</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-stepping-into-business-mode-register-as-an-instagram-corp-page/"><u>[Updated] In 2024, Stepping Into Business Mode  Register as an Instagram Corp Page</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-recover-missing-youtube-like-icon-in-fb-watch/"><u>[Updated] Recover Missing YouTube-Like Icon in FB Watch</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-tecno-spark-20-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Tecno Spark 20 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/5-best-tips-for-enhancing-obs-studio-edits-for-2024/"><u>5 Best Tips for Enhancing OBS Studio Edits for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/1719149103040-discovering-sheryls-strategies-at-facebook-inc/"><u>Discovering Sheryl's Strategies at Facebook Inc.</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-presence-of-startup-applications/"><u>Guaranteeing Presence of Startup Applications</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-no-audio-output-device-is-installed-error-on-windows/"><u>How to Fix the No Audio Output Device Is Installed Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-10-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 10 & 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-quickly-secure-and-update-drivers-for-your-epson-xp-440-printer/"><u>How to Quickly Secure and Update Drivers for Your Epson XP-440 Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-premier-laptop-showcase-the-ultimate-finds/"><u>IFA's Premier Laptop Showcase - The Ultimate Finds</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-thumbnail-images-on-windows-11-a-step-by-step-resolution/"><u>Lost Thumbnail Images on Windows 11: A Step-by-Step Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-passwords-in-windows-11-the-ultimate-4-allies/"><u>Mastering Passwords in Windows 11: The Ultimate 4 Allies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-repair-of-windows-hyper-v-error-0x8009030e/"><u>Mastering the Repair of Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-charge-readiness-notification-tips-for-win11-users/"><u>Maximizing Charge Readiness: Notification Tips for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-permanent-trash-settings-in-windows-1011/"><u>Personalizing Permanent Trash Settings in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-windows-for-video-on-demand-via-dynamic-transcoding-by-tdarr/"><u>Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/preparing-your-devices-for-a-win-11-app-transfer-transition/"><u>Preparing Your Devices for a Win 11 App Transfer Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-deactivated-rulesets-in-office-365windows-outlook/"><u>Reactivating Deactivated Rulesets in Office 365/Windows Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-color-discrepanenas-of-store-interface/"><u>Remedy for Color Discrepanenas of Store Interface</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-clicking-experience-fixing-unreliable-wireless-mouse-problems/"><u>Seamless Clicking Experience: Fixing Unreliable Wireless Mouse Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-value-in-preserving-your-windows-11-notification-alerts/"><u>The Hidden Value in Preserving Your Windows 11 Notification Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-accessing-photos-via-windows-11s-explorer/"><u>Tips for Accessing Photos via Windows 11'S Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-obs-errors-unknown-failure-recorded/"><u>Troubleshooting OBS Errors: Unknown Failure Recorded</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-1110-stop-pin-connection-hurdle/"><u>Troubleshooting Windows 11/10: Stop PIN Connection Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-store-app-in-windows-11-os/"><u>Unlocking Microsoft Store App in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-veiled-bar-search-feature/"><u>Unlocking Windows 11'S Veiled Bar Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-arm-setup-via-iso-file-instructions-inside/"><u>Windows 11 ARM Setup Via ISO File - Instructions Inside</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-bar-through-time-1985-2023-retrospective/"><u>Windows Bar Through Time: 1985-2023 Retrospective</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>