---
title: "Flushing DNS on Windows: Best Practices"
date: 2024-07-11T21:12:55.712Z
updated: 2024-07-12T21:12:55.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Flushing DNS on Windows: Best Practices"
excerpt: "This Article Describes Flushing DNS on Windows: Best Practices"
keywords: FlushDNSWindows,DNSResolveWin,WinDNSClearance,DNSRefreshPC,ClearDnsWindows,PCDnsResetProg,OptimizeWindowsNs
thumbnail: https://thmb.techidaily.com/c889a547e421f550d3854604da4881f54e6123831fe3b245b44881a2b3d8e123.jpg
---

## Flushing DNS on Windows: Best Practices

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of [DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.


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
<li><a href="https://windows11.techidaily.com/avoid-frozen-savers-4-tips-to-fix-windows-issues/"><u>Avoid Frozen Savers: 4 Tips to Fix Windows Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/1719316143750-avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps!</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-tweaking-firewall-security/"><u>A Comprehensive Guide to Tweaking Firewall Security</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-proficient-with-windows-odbc-control-panel/"><u>Becoming Proficient with Windows' ODBC Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-tactics-against-flaky-saving-mechanism-in-nvidia-gui/"><u>Avoidance Tactics Against Flaky Saving Mechanism in Nvidia GUI</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-pixel-power-unveiling-youtubes-twitter-crew-for-2024/"><u>[New] Pixel Power  Unveiling YouTube's Twitter Crew for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/leading-8-screenshot-solutions-without-hesitation-for-2024/"><u>Leading 8 Screenshot Solutions Without Hesitation for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-hit-the-floor-with-optimal-posting-hours/"><u>[New] Hit the Floor with Optimal Posting Hours</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-quickquip-quarterfreeze-media/"><u>In 2024, QuickQuip QuarterFreeze Media</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-unlocking-screen-record-features-in-hp-computers/"><u>[Updated] In 2024, Unlocking Screen Record Features in HP Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-no-network-access-on-winethernet/"><u>Bridging No Network Access on WinEthernet</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-inside-acid-pro-benchmarking-alternatives/"><u>[Updated] Inside ACID Pro  Benchmarking Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-assault-win-against-mouse-lags-on-sw/"><u>Ace Your Assault: Win Against Mouse Lags on SW</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-your-ultimate-playbook-to-monetize-youtube-traffic/"><u>[Updated] 2024 Approved  Your Ultimate Playbook to Monetize Youtube Traffic</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-network-adapter-not-working-in-windows/"><u>6 Ways to Fix Network Adapter Not Working in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-decades-old-password-request-on-modern-windows/"><u>Bypassing Decades-Old Password Request on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-error-code-0x800736cc-in-windows-update/"><u>Circumventing Error Code 0X800736CC in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-disappearing-desktop-elements-on-windows/"><u>Bring Back Disappearing Desktop Elements on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-soul-a-guide-to-registry-files-exploration/"><u>Accessing Windows 11’S Soul: A Guide to Registry Files Exploration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-nokia-c02-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Nokia C02 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-vivo-y17s-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Vivo Y17s? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/sony-vegas-pro-has-not-the-feature-you-want-cant-import-your-video-source-files-any-other-problems-find-an-alternative-for-windows-in-this-article-for-2024./"><u>Sony Vegas Pro Has Not the Feature You Want? Cant Import Your Video Source Files? Any Other Problems? Find an Alternative for Windows in This Article for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-blue-screens-a-windows-fixers-manual/"><u>Banishing Blue Screens: A Windows Fixer’s Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-steam-auth-blocks-in-rust-on-windows-devices/"><u>Breaking Down Steam Auth Blocks in Rust on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-duplicate-local-device-names-in-windows-systems/"><u>Avoiding Duplicate Local Device Names in Windows Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/samurais-shadowed-path-other-epic-warrior-games/"><u>Samurai's Shadowed Path - Other Epic Warrior Games</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-based-office-glitches-effectively/"><u>Addressing Win-Based Office Glitches Effectively</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-fix-there-is-no-sound-on-twitter-videos-for-2024/"><u>[Updated] Fix There Is No Sound on Twitter Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/5-great-free-podcast-editing-programs-for-windows/"><u>5 Great Free Podcast Editing Programs for Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-quiet-curator-of-online-chronicles/"><u>[Updated] Quiet Curator of Online Chronicles</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-time-display-in-the-taskbar-of-window-11/"><u>Adjusting Time Display in the Taskbar of Window 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oppo-reno-11-pro-5g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo Reno 11 Pro 5G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/6-fixes-for-windows-gone-dark-and-unresponsive/"><u>6 Fixes for Windows Gone Dark and Unresponsive</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-motorola-g54-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Motorola G54 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-swift-and-steady-follower-filtering-the-leading-twitter-tools-list-for-2024/"><u>[New] Swift and Steady Follower Filtering  The Leading Twitter Tools List for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-avoiding-the-bottom-ranks-understanding-impactful-factors/"><u>In 2024, Avoiding the Bottom Ranks  Understanding Impactful Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-pc-maintenance-speed-customizing-win-1011-hotkeys/"><u>Boosting PC Maintenance Speed: Customizing Win 10/11 Hotkeys</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-first-captured-visual-saga-critique-with-alternate-views/"><u>[New] First Captured Visual Saga Critique with Alternate Views</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-crop-companions-best-farming-games-to-gather-with-buddies/"><u>[Updated] In 2024, Crop Companions  Best Farming Games to Gather with Buddies</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-system-refreshment-navigating-the-windows-driver-update-process/"><u>Audio System Refreshment: Navigating the Windows Driver Update Process</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-to-activating-windows-hello-on-pc/"><u>A Simple Guide to Activating Windows Hello on PC</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-scheduling-virtual-gatherings-with-zoom-an-android-users-handbook/"><u>In 2024, Scheduling Virtual Gatherings with Zoom  An Android User's Handbook</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-optimal-strategies-for-selective-youtube-video-downloads/"><u>[New] Optimal Strategies for Selective YouTube Video Downloads</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/essential-displays-for-picture-perfect-editing-choices-for-2024/"><u>Essential Displays for Picture Perfect Editing [Choices] for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bouncing-back-deleted-folders-on-your-pc/"><u>Bouncing Back Deleted Folders on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-tools-to-clipboard-access-for-easier-compatibility-fixes/"><u>Adding Tools to Clipboard Access for Easier Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/1719354556221-eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues.</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/efficient-techniques-for-personalizing-and-updating-social-media-coverage-for-2024/"><u>Efficient Techniques for Personalizing and Updating Social Media Coverage for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-termbackground-pic/"><u>Choosing a Fresh TermBackground Pic</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-11-notepad-using-ai-mentor/"><u>Boost Windows 11 Notepad Using AI Mentor</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ehensive-guide-to-youtube-content-moderation-rules-for-2024/"><u>Comprehensive Guide to YouTube Content Moderation Rules for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/podcast-span-perfection-finding-your-content-cadence/"><u>Podcast Span Perfection  Finding Your Content Cadence</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-choose-a-drive-to-install-games-on-the-xbox-app-for-windows-try-these-fixes/"><u>Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-enriching-vlog-topics-to-share-for-2024/"><u>[Updated] Enriching Vlog Topics to Share for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-freesync-review-the-latest-from-lg-27uhd68-monitor-for-2024/"><u>[New] FreeSync Review  The Latest From LG 27UHD68 Monitor for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-y27-5g-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Y27 5G using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-windows-11s-digital-storyteller/"><u>Awakening Windows 11'S Digital Storyteller</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-pinnacle-graphics-the-ultimate-4k-game-enhancement/"><u>[New] In 2024, Pinnacle Graphics  The Ultimate 4K Game Enhancement</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-y100i-power-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo Y100i Power 5G Phones with/without a PC</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-a-review-of-the-goofy-movie-vhs/"><u>2024 Approved  A Review of The Goofy Movie VHS</u></a></li>
<li><a href="https://windows11.techidaily.com/6-different-ways-to-open-programs-on-windows/"><u>6 Different Ways to Open Programs on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-system-maintenance-locating-and-resolving-win-os-error-codes-via-command-prompt-expertise/"><u>Advanced System Maintenance: Locating and Resolving Win-OS Error Codes via Command Prompt Expertise</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-hasten-haste-in-videos-with-top-apps-android/"><u>[New] In 2024, Hasten Haste in Videos with Top Apps, Android</u></a></li>
<li><a href="https://windows11.techidaily.com/become-a-windows-wizard-learn-essential-shortcut-commands/"><u>Become a Windows Wizard: Learn Essential Shortcut Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unnoticed-use-of-your-pcs-cam-on-windows-11/"><u>Avoiding Unnoticed Use of Your PC's Cam on Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/yield-cash-reviewing-gadgets-apparel-and-more-on-the-web-for-2024/"><u>Yield Cash Reviewing Gadgets, Apparel, and More on the Web for 2024</u></a></li>
</ul></div>
