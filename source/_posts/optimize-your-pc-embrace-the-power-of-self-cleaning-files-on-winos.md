---
title: "Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS"
date: 2024-08-08T06:13:56.554Z
updated: 2024-08-09T06:13:56.554Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS"
excerpt: "This Article Describes Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS"
keywords: Optimal PC Cleanliness,Self-Cleaning Files Guide,Windows File Management,Enhance PC Performance,Self-Cleansing Techniques,WINOS Speed Up Tips,Efficient File Organization
thumbnail: https://thmb.techidaily.com/8ff8906f51872923e9c5692da8760464bdd1f9c3eac0a2d615e95926075c7419.jpg
---

## Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-crafting-impeccable-srt-from-xml-ssa-and-ttml-files/"><u>[New] 2024 Approved  Crafting Impeccable SRT From XML, SSA & TTML Files</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-navigating-android-latest-tips-for-immersive-360-content/"><u>[New] 2024 Approved  Navigating Android  Latest Tips for Immersive 360 Content</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-prime-flood-and-flow-video-game-reviews/"><u>[Updated] Prime Flood & Flow Video Game Reviews</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-elevate-your-gaming-experience-with-fbx-recording-tips/"><u>2024 Approved  Elevate Your Gaming Experience with FBX Recording Tips</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-11-crashes-interrupt-fixation/"><u>Avoiding Windows 11 Crashes: Interrupt Fixation</u></a></li>
<li><a href="https://facebook.techidaily.com/breaking-barriers-the-implications-of-full-access-control-on-oculus-go/"><u>Breaking Barriers: The Implications of Full Access Control on Oculus Go</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-adjacent-and-disjoint-partition-combination/"><u>Effective Strategies for Adjacent and Disjoint Partition Combination</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-resolving-windows-office-crashes-and-glitches/"><u>Effective Strategies for Resolving Windows Office Crashes and Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-monitoring-running-apps-on-windows/"><u>Efficiently Monitoring Running Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-access-key-strategies-for-w11s-rdc/"><u>Effortless Access: Key Strategies for W11's RDC</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-file-management-winpcs-most-valuable-fileshare-apps/"><u>Effortless File Management: WinPC's Most Valuable Fileshare Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/ejecting-unsolicited-windows-updates/"><u>Ejecting Unsolicited Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-learning-7-proven-techniques-for-windows-users/"><u>Elevate Learning: 7 Proven Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-0x80072efd-a-windows-store-solution/"><u>Eliminating Error 0X80072EFD: A Windows Store Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-11-zoom-problem-code-1132/"><u>Eliminating Windows 11 Zoom Problem: Code 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hyper-v-a-quick-win11-guide/"><u>Enabling Hyper-V: A Quick Win11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-memory-protection-win11-updates-fixes/"><u>Enabling Memory Protection: Win11 Updates' Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-onedrive-for-direct-file-explorer-opens/"><u>Enabling OneDrive for Direct File Explorer Opens</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-and-share-on-leading-social-sites-facebook-twitter-instagram-and-youtube/"><u>Engage and Share on Leading Social Sites: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-and-streamlining-windows-based-discord-searches/"><u>Enhancing and Streamlining Windows-Based Discord Searches</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visual-quality-setting-sizes-on-win11/"><u>Enhancing Visual Quality: Setting Sizes on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-top-strategies-for-uninstalling-difficult-optional-components/"><u>Enhancing Windows 11: Top Strategies for Uninstalling Difficult Optional Components</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-fix-for-frozen-exe-files/"><u>Enhancing Windows: Fix for Frozen .exe Files</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-the-current-password-needed-issue-on-windows-11/"><u>Eradicate the ‘Current Password Needed’ Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-code-0x800700e1-complications-on-windows-11-pcs/"><u>Eradicating Code 0X800700E1 Complications on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-empty-directory-warning-code-0x80070091-in-windows-11-os/"><u>Eradicating Empty Directory Warning Code 0X80070091 in Windows 11 OS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facesave-videorecorder-pro-for-2024/"><u>FaceSave Videorecorder Pro for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/google-data-recovery-recover-lost-data-from-google-pixel-8-by-fonelab-android-recover-data/"><u>Google Data Recovery – recover lost data from Google Pixel 8</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/groundbreaking-getaways-easy-builds-for-mc-beginners-for-2024/"><u>Groundbreaking Getaways  Easy Builds for MC Beginners for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-samsung-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Samsung Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/innovative-techniques-for-recording-instagram-story-highlights/"><u>Innovative Techniques for Recording Instagram Story Highlights</u></a></li>
<li><a href="https://review-topics.techidaily.com/mov-to-motorola-converter-convert-mov-files-for-motorola-by-aiseesoft-video-converter-play-mov-on-android/"><u>MOV to Motorola converter-convert .mov files for Motorola</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-persistent-lag-issues-in-call-of-duty-vanguard-for-windows-users-2024-insights/"><u>Overcoming Persistent Lag Issues in Call of Duty: Vanguard for Windows Users (2024 Insights)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-oppo-reno-10-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/tweetturnstile-how-video-trends-surge-online-for-2024/"><u>TweetTurnstile  How Video Trends Surge Online for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>