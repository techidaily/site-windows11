---
title: Proactive Measures to Increase Virtual Memory in Windows 11 Operations
date: 2024-09-09T11:58:18.912Z
updated: 2024-09-10T11:58:18.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proactive Measures to Increase Virtual Memory in Windows 11 Operations
excerpt: This Article Describes Proactive Measures to Increase Virtual Memory in Windows 11 Operations
keywords: Boost W11 VM,RAM Optimize Win11,Enhance Win11 Mem,Win11 Virtual Expansion,Memory Improvement Win11,Increase VM Windows 11,Virtual Space Upgrade Win11
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## Proactive Measures to Increase Virtual Memory in Windows 11 Operations

 Your computer slowing down isn't a great feeling. Is it overheating? Is the CPU old? Or is it that you've run out of memory?

 Running out of memory affects your system from top to bottom, making regular tasks suddenly feel like walking through treacle.

 If that sounds like your Windows 11 installation, it's time to check out your virtual memory settings to make sure your system can cope with demand. So, here's how you change the virtual memory size on Windows 11, along with a few tips on boosting your system performance.

## What Is Virtual Memory?

 We've[previously explained virtual memory](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) in more detail, but here is an outline to bring you up to speed.

> Your hard drive is where your operating system lives, as well as your photos, music, games, documents, and otherwise. Your RAM stores program-specific data. It is much faster but also more volatile, acting as a working storage area for the programs and files you have open.

> So, what is virtual memory?

> Well, if you use all the RAM available to your system, it will utilize virtual memory—also known as a swap or paging file—to provide a temporary expansion. Your system's virtual memory does this using part of your hard-drive memory to expand your RAM effectively. So, this virtual memory is extremely useful. It allows your system to handle more data for more programs than previously available.

[When your RAM runs low](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , your system will call upon the paging file to handle some of the extra data. However, as your hard drive or even solid-state drive is much slower than your RAM, system performance will take a hit.

### Windows 11 Is Running Low on Virtual Memory

 Now, the thing is, virtual memory has its own limits. It isn't an infinite well of additional yet slower memory you can call upon. If you begin to run out of virtual memory, Windows 11 will display the following error message:

> Your system is low on virtual memory. Windows is increasing the size of your virtual memory paging file. During this process, memory requests for some applications may be denied. For more information, see help.

 Windows 11 will automatically manage your virtual memory, ensuring that the paging file has enough capacity to handle your system demands. However, you can also manually increase the size of your paging file on Windows 11 if you're comfortable making decisions regarding how much RAM you have installed.

 Windows sets the initial virtual memory paging file equal to the amount of installed RAM. The paging file is a minimum of 1.5 times and a maximum of three times your physical RAM. You can use the following system to calculate your Windows 11 paging file (using a system with 8GB installed as the example), providing you know[how much RAM you have installed](https://www.makeuseof.com/windows-check-installed-ram-available-ram-slots/) .

* **Minimum** : 1024_8_ 1.5=12288 \[1GB RAM x Installed RAM x Minimum\]
* **Maximum** : 1024_8_ 3=24576 \[1GB RAM x Installed RAM x Maximum\]

 Still, both of these values are high.[Microsoft recommends](http://docs.microsoft.com/en-us/windows/client-management/determine-appropriate-page-file-size) "3 × RAM or 4 GB, whichever is larger," which will protect your system from instability when you do use your paging file. However, Windows' automatic paging file management might decide otherwise, so it's typically best to let the operating system figure things out for itself. For example, in the image below, you can see that on my Windows 10 machine with 32GB RAM installed, the paging file is automatically set at just under 7GB.

 Furthermore, remember that these values take up space on your hard drive, as Windows allocates the overall paging file space in case it needs it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Increase Virtual Memory Size on Windows 11

 If you want to go ahead and manually alter the paging file size on Windows 11 to remove the virtual memory low message, here's how you go about it.

![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Install More RAM to Boost Your System Performance

 Increasing your virtual memory size is a temporary fix and isn't one you should rely on long-term. The only way to truly fix your low virtual memory issue[is to install more RAM](https://www.makeuseof.com/how-to-install-ram/) . The reason your system is turning to the paging file to begin with is that additional data is being palmed off.

 The answer is to install more RAM, which in turn will give your whole system a boost as you'll no longer run out of memory and have to use the slower paging file instead. It's easier to install more RAM on a desktop computer than on a laptop, but[upgrading the RAM on a laptop is possible](https://www.makeuseof.com/tag/upgrading-a-laptops-ram-step-by-step-si-x2/) . Unfortunately, if you don't have any more RAM slots, have reached the maximum RAM capacity, or find that your laptop has soldered RAM, you're flat out of luck.

 You can[attempt to free up more RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) , but ultimately, you're probably going to need a new laptop.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Increasing the Windows 11 Paging File Size Is a Temporary Fix

 Boosting the paging file size on Windows 11 or any operating system is a temporary fix. If you're butting up against your memory limit frequently and your computer begins to slow to a crawl, there is only one true fix.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-best-instagram-highlights-covers-apps/"><u>[New] 2024 Approved  Best Instagram Highlights Covers Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-calculating-gb-in-one-days-movie-duration/"><u>[New] Calculating GB in One Day's Movie Duration</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-gif-capture-on-mac-10-best-tools-ranked-for-2024/"><u>[New] GIF Capture on Mac  10 Best Tools Ranked for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-capturing-attention-from-content-creation-to-commerce/"><u>[New] In 2024, Capturing Attention  From Content Creation to Commerce</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-champion-of-chiseled-cheeks-starting-your-youtube-aesthetic-venture/"><u>[Updated] Champion of Chiseled Cheeks  Starting Your YouTube Aesthetic Venture</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-selecting-the-best-ten-spotify-recording-software/"><u>[Updated] Selecting the Best Ten Spotify Recording Software</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-techniques-for-transforming-mp4-files-with-vlc/"><u>2024 Approved  Expert Techniques for Transforming MP4 Files with VLC</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/alcatel-joy-tab-2-examined-top-recommendations-for-economical-lte-tablets/"><u>Alcatel Joy Tab 2 Examined - Top Recommendations for Economical LTE Tablets</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-apple-tv-4k-analysis-experience-next-gen-super-high-definition-viewing-and-seamless-voice-assistant-navigation/"><u>Comprehensive Apple TV 4K Analysis: Experience Next-Gen, Super High-Definition Viewing & Seamless Voice Assistant Navigation</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-value-with-the-2020-apple-iphone-se-where-smart-meets-affordable/"><u>Discovering Value with the 2020 Apple iPhone SE: Where Smart Meets Affordable</u></a></li>
<li><a href="https://windows11.techidaily.com/five-keys-to-unlock-frozen-windows-hibernate/"><u>Five Keys to Unlock Frozen Windows Hibernate</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-correcting-absence-of-rockalldll-in-windows/"><u>Guide for Correcting Absence of Rockalldll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-mute-chrome-prompts-on-windows/"><u>Guide to Mute Chrome Prompts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/heavy-load-on-ram-how-to-diminish-malware-scan-impact/"><u>Heavy Load on RAM? How to Diminish Malware Scan Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-or-disable-the-smartscreen-filter-in-windows-10-and-11/"><u>How to Enable or Disable the SmartScreen Filter in Windows 10 & 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-xiaomi-redmi-note-12-4g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Xiaomi Redmi Note 12 4G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/install-and-manage-packages-with-windows-package-manager-wpm/"><u>Install and Manage Packages with Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-for-admin-level-access-on-windows/"><u>Key Steps for Admin-Level Access on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/leading-single-board-computers-for-windows-os/"><u>Leading Single-Board Computers for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-pictures-top-7-windows-photo-orgers/"><u>Master Your Pictures: Top 7 Windows Photo Orgers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-application-setup-on-windows-11/"><u>Mastering the Art of Application Setup on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-game-a-comprehensive-guide-on-how-to-excel-at-royal-match/"><u>Mastering the Game: A Comprehensive Guide on How to Excel at Royal Match</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-troubleshoot-guide-for-error-x80072f30/"><u>Microsoft Store Troubleshoot Guide for Error X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-and-implement-windows-11-family-safety-options/"><u>Navigate and Implement Windows 11 Family Safety Options</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-unraveling-quirks-and-fixes/"><u>Navigating Through WINDOWS 11: Unraveling Quirks & Fixes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photography-made-easy-select-top-writing-apps/"><u>Photography Made Easy  Select Top Writing Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/pixel-perfect-designs-for-your-pc-wallpaper/"><u>Pixel Perfect Designs for Your PC Wallpaper</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-loss-of-customization-through-nvidia-cp-malfunctions/"><u>Preventing Loss of Customization Through Nvidia CP Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-in-game-communication-hurdles-with-windows-speech-tools/"><u>Rectifying In-Game Communication Hurdles with Windows Speech Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-power-status-notifications-in-windows-1011/"><u>Refinement of Power Status Notifications in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/relaunching-print-processor-in-windows/"><u>Relaunching Print Processor in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-chromes-erroneous-security-warnings-tips-and-tricks/"><u>Revising Chrome's Erroneous Security Warnings: Tips & Tricks</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/softening-the-end-effective-methods-for-reducing-volume-in-premiere-pro-for-2024/"><u>Softening the End  Effective Methods for Reducing Volume in Premiere Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-mastering-w11-audio-recordings/"><u>Step-by-Step: Mastering W11 Audio Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-eradicating-installer-problems-on-windows-11/"><u>Strategies for Eradicating Installer Problems on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-error-0x80041015-in-ms-word-and-excel/"><u>Strategies to Resolve Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-fileshare-on-windows-11/"><u>Streamlining Fileshare on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-vbox-setup-head-on-devices-and-deps-first/"><u>Tackle VBox Setup Head-On: Devices and Deps First</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-permission-levels-for-non-administrative-windows-users/"><u>Tailoring Permission Levels for Non-Administrative Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-definitive-steps-to-hyper-v-on-windows-11/"><u>The Definitive Steps to Hyper-V on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-usb-management-on-modern-systems/"><u>The Essential Guide to USB Management on Modern Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-true-potential-fix-windows-screen-modes/"><u>Unlocking True Potential: Fix Windows Screen Modes</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-solving-windows-exit-point-error/"><u>Unraveling and Solving Windows Exit Point Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-windows-store-error-code-0x80072efd/"><u>Unwrapping the Mystery of Windows Store Error Code 0X80072EFD</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-itel-p55t-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Itel P55T? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategy-against-corrupted-filedir-error-x70-on-pcs/"><u>Winning Strategy Against 'Corrupted' File/Dir Error X70 on PCs</u></a></li>
</ul></div>
