---
title: "Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
date: 2024-08-22T21:37:47.297Z
updated: 2024-08-23T21:37:47.297Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
excerpt: "This Article Describes Secure and Slim Filesystem: Setting Up Auto Delete in Win11"
keywords: Win11 Auto-Delete,Slim Windows File,Secure WinFS Setup,Auto-Deletion Techniques,Slim File System,Secure Filesystem Win11,Deleting Old Files
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Secure and Slim Filesystem: Setting Up Auto Delete in Win11

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
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/irect-transition-from-youtube-to-instagram-reels/"><u>[New] Direct Transition From YouTube to Instagram Reels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-hacker-alert-reclaiming-your-social-network/"><u>[Updated] Hacker Alert  Reclaiming Your Social Network</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-intellects-ultimate-guide-to-premium-gk-quiz-sites/"><u>2024 Approved  Intellect's Ultimate Guide to Premium GK Quiz Sites</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-oneplus-ace-2v-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide OnePlus Ace 2V Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/complete-guide-saving-and-sharing-your-icloud-keychain-with-csv-file-conversion/"><u>Complete Guide: Saving and Sharing Your iCloud Keychain with CSV File Conversion</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/different-methods-to-unlock-your-iphone-6-drfone-by-drfone-ios/"><u>Different Methods To Unlock Your iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-tackle-ms-store-hurdle-win1011s-error-0x0/"><u>Expert Advice to Tackle MS Store Hurdle: Win10/11's Error 0X0</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-indexing-service/"><u>Fixing Non-Starting Windows Indexing Service</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-generate-a-copernic-software-offline-license/"><u>Guide: How to Generate a Copernic Software Offline License</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-honor-x50i-by-drfone-android/"><u>In 2024, How to Bypass FRP from Honor X50i?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-pick-a-perfect-virtual-reality-device-is-wireless-vision-or-connected-content-more-appealing/"><u>In 2024, How to Pick a Perfect Virtual Reality Device  Is Wireless Vision or Connected Content More Appealing?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-make-a-statement-with-free-profile-pics/"><u>In 2024, Make a Statement With Free Profile Pics</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-sony-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Sony Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/instantaneous-access-to-the-calculator-in-windows-11-os/"><u>Instantaneous Access to the Calculator in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-specific-group-policy-enforcement-on-users-profiles-in-win-oses/"><u>Introducing Specific Group Policy Enforcement on Users' Profiles in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/laymans-guide-to-setting-up-a-triple-column-board-on-windows-11/"><u>Layman's Guide to Setting Up a Triple Column Board on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-quick-finds-in-illustrator-a-complete-guide-using-copernic/"><u>Mastering Quick Finds in Illustrator: A Complete Guide Using Copernic</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-flawless-file-handling-discover-copernics-software-secrets-for-maximum-efficiency/"><u>Navigating Flawless File Handling: Discover Copernic's Software Secrets for Maximum Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-outdated-windows-password-a-guide/"><u>Overcoming Outdated Window's Password: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-clutter-in-windows-11s-selection-options/"><u>Reducing Clutter in Windows 11'S Selection Options</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-11-search-experience/"><u>Reimagining Your Windows 11 Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-touchpad-glitches-on-your-windows-machine/"><u>Remedying Touchpad Glitches on Your Windows Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-folder-management-selective-move-on-windows-11/"><u>Revolutionize Folder Management: Selective Move on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-business-data-retrieval-with-advanced-copernic-search-tech-explained/"><u>Revolutionizing Business Data Retrieval with Advanced Copernic Search Tech Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/santa-skims-but-you-need-depth-discover-how-copernic-transforms-your-data-check-with-precision-and-ease/"><u>Santa Skims, But You Need Depth - Discover How Copernic Transforms Your Data Check with Precision and Ease!</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-yesteryear-classic-pc-gaming-via-dosbox-x/"><u>Step Into Yesteryear: Classic PC Gaming via DOSBox-X</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-use-of-powertoys-locksmith-for-files/"><u>Strategic Use of PowerToys Locksmith for Files</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-complete-manual-taking-editing-and-sharing-display-images-for-2024/"><u>The Complete Manual  Taking, Editing, and Sharing Display Images for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-snapshot-navigating-newly-active-windows-items/"><u>The Snapshot: Navigating Newly Active Windows Items</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-ways-copernic-enhances-your-work-from-home-experience/"><u>Top 5 Ways Copernic Enhances Your Work-From-Home Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-the-blue-screen-footsteps-in-windows-xp7/"><u>Tracing the Blue Screen Footsteps in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-your-cursor-display-with-windows-1011-tweaks/"><u>Transforming Your Cursor Display with Windows 10/11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/trim-excessive-resource-use-of-antimalware-tools/"><u>Trim Excessive Resource Use of Antimalware Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-maxed-out-chatgpt-error/"><u>Troubleshooting Maxed Out ChatGPT Error</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-synapse-on-pcs-with-windows-11-and-10/"><u>Troubleshooting: Resolving Synapse on PCs with Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-gpo-details-using-gpresult/"><u>Unveiling GPO Details Using GPResult</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-configurations-simplified/"><u>Windows 11 Configurations Simplified</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-auditing-for-unguarded-ip-ports/"><u>Windows Network Auditing for Unguarded IP Ports</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-struggles-heres-how-to-install-icloud-seamlessly/"><u>Windows Struggles? Here’s How to Install iCloud Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-commanding-app-and-browser-flow/"><u>Windows Wisdom: Commanding App & Browser Flow</u></a></li>
<li><a href="https://win-answers.techidaily.com/winning-over-windows-11-gaming-glitches-with-steam-solutions/"><u>Winning Over Windows 11 Gaming Glitches with Steam Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>