---
title: "Method: Rectifying Disks Not Available on Windows PCs"
date: 2024-07-11T21:47:52.678Z
updated: 2024-07-12T21:47:52.678Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
excerpt: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
keywords: Windows Disk Error Fix,Windows No Disk Found,Unavailable Disk in Windows,Solve Missing Disks Issue,Windows PC Disk Repair,Rectify Windows Disk Not Available,Troubleshoot Disk Non-Existence on PC
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Method: Rectifying Disks Not Available on Windows PCs

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ed-is-it-legal-to-record-youtube/"><u>[Updated] Is It Legal to Record YouTube?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-best-free-desktop-pass-gen-software/"><u>The Ultimate Guide to Best Free Desktop Pass Gen Software</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-broadcasting-vimeo-content-efficiently/"><u>[New] In 2024, Broadcasting Vimeo Content Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-potential-essential-tips-on-windows-narrator-commands/"><u>Unveiling the Hidden Potential: Essential Tips on Windows Narrator Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-10-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 10 & 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-challenge-yourself-with-these-15-tiktok-gurus/"><u>[Updated] In 2024, Challenge Yourself with These 15 TikTok Gurus</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-oddities-in-windows-11-visual-language/"><u>Uncovering the Oddities in Windows 11 Visual Language</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-clearer-crisper-youtube-videos-with-quality-tools-for-2024/"><u>Craft Clearer, Crisper YouTube Videos with Quality Tools for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/ultimate-20-country-chill-out-playlist-for-relaxing-dance-moves-tiktok-for-2024/"><u>Ultimate 20 Country Chill-Out Playlist for Relaxing Dance Moves (TikTok) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-gaming-experience-installing-windows-on-steam-deck/"><u>Streamline Your Gaming Experience: Installing Windows on Steam Deck</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-recovery-mode-on-iphone-15-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-win11-experience-learn-to-edit-faxes-easily/"><u>Enhancing Your Win11 Experience: Learn to Edit Faxes Easily</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-art-of-finding-classic-facebook-content-for-2024/"><u>The Art of Finding Classic Facebook Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-mouse-woes-on-windows-heres-what-to-do/"><u>Wireless Mouse Woes on Windows? Here's What to Do</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-6-best-tiktok-to-mp3-converters-online-and-free/"><u>[New] 2024 Approved  6 Best TikTok to MP3 Converters [Online & Free]</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-onedrive-and-microsoft-accounts-a-walkthrough/"><u>Integrating OneDrive & Microsoft Accounts: A Walkthrough</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/quick-start-engaging-with-friends-on-insta-chat-for-2024/"><u>Quick Start  Engaging with Friends on Insta Chat for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-the-ultimate-discord-spoiler-tag-reference/"><u>[Updated] In 2024, The Ultimate Discord Spoiler Tag Reference</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/three-methods-for-transforming-your-podcast-into-mp3-format/"><u>Three Methods for Transforming Your Podcast Into MP3 Format</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-oneplus-ace-3-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass OnePlus Ace 3 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-screen-driver-problems-in-windows-11/"><u>How to Mend Screen Driver Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-horizons-redefining-windows-11-paradigms/"><u>AI Horizons: Redefining Windows 11 Paradigms</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-knowledge-on-folder-tagsging-in-windows-explorer/"><u>Insider Knowledge on Folder Tagsging in Windows Explorer</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-capture-high-quality-video-using-macbooks-webcam/"><u>2024 Approved  Capture High-Quality Video Using MacBook's Webcam</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-cost-effective-subscriber-growth-hundreds-at-a-bargain-price/"><u>[New] In 2024, Cost-Effective Subscriber Growth - Hundreds at a Bargain Price</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-efficient-tiktok-to-gif-conversion-with-top-tools-reviewed/"><u>2024 Approved  Efficient TikTok-to-GIF Conversion with Top Tools Reviewed</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-infinix-smart-8-pro-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Infinix Smart 8 Pro FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-storage-efficiency-tools-for-pcs/"><u>Activating Storage Efficiency Tools for PCs</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-3-smart-and-simple-ways-to-change-home-address-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Smart and Simple Ways to Change Home Address on Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-curiosities-5-fun-filled-functions/"><u>Command Prompt Curiosities: 5 Fun-Filled Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-extend-the-wait-window-in-windows-10-before-restarting/"><u>Tricks to Extend the Wait Window in Windows 10 Before Restarting</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-smartphone-photographers-handbook/"><u>[New] The Smartphone Photographer's Handbook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-the-insiders-guide-to-maximizing-ez-grabber/"><u>[New] In 2024, The Insider’s Guide to Maximizing EZ Grabber</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-navigation-disabling-accelerated-motion-windows-style/"><u>Efficient Navigation: Disabling Accelerated Motion Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-13t-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi 13T Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-trash-for-permanent-deletion-on-windows-oses/"><u>Mastering Desktop Trash for Permanent Deletion on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inactive-mail-signals-on-desktop-os/"><u>Tackling Inactive Mail Signals on Desktop OS</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-security-in-virtualbox-via-secure-boot-toggle/"><u>Boost Security in VirtualBox via Secure Boot Toggle</u></a></li>
<li><a href="https://windows11.techidaily.com/control-and-discretion-over-network-safety-in-windows/"><u>Control and Discretion Over Network Safety in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-resource-monitor-app-when-its-not-working-on-windows-11/"><u>How to Fix the Resource Monitor App When It's Not Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-10-keys-a-step-by-step-guide/"><u>Unlocking Windows 10 Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-workflow-microsoft-adds-an-ai-powered-assistant-to-the-windows-11-taskbar/"><u>Effortless Workflow: Microsoft Adds an AI-Powered Assistant to the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-greatness-perfecting-palette-on-your-pc/"><u>Guaranteeing Greatness: Perfecting Palette on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-record-audio-on-windows-11/"><u>How to Record Audio on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-8-best-authentic-youtube-growth-tactics-for-2024/"><u>The 8 Best Authentic Youtube Growth Tactics for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unlocking-creative-expression-tips-for-sharing-gifs-on-snapchat/"><u>[New] In 2024, Unlocking Creative Expression  Tips for Sharing GIFs on Snapchat</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-revealing-the-secrets-accessing-forgotten-youtube-vids/"><u>2024 Approved  Revealing the Secrets  Accessing Forgotten YouTube Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-and-control-fast-boot-in-your-windows-11-pc/"><u>How to Activate and Control Fast Boot in Your Windows 11 PC</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-captivating-reels-syncing-audio-to-images-for-2024/"><u>Crafting Captivating Reels  Syncing Audio to Images for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-ultimate-expertise-full-guide-to-record-your-macscreens/"><u>[New] 2024 Approved  The Ultimate Expertise  Full Guide to Record Your MacScreens</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-secret-windows-11-themes-with-the-registry/"><u>How to Unlock Secret Windows 11 Themes With the Registry</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-edit-like-a-pro-top-10-free-android-video-editing-apps-without-watermarks/"><u>2024 Approved Edit Like a Pro Top 10 Free Android Video Editing Apps Without Watermarks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/ideal-recording-gear-for-vloggers-for-2024/"><u>Ideal Recording Gear for Vloggers for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-streamlining-board-collaboration-a-compreenasion-of-using-whiteboards-on-all-zoom-platforms/"><u>2024 Approved  Streamlining Board Collaboration - A Compreenasion of Using Whiteboards on All Zoom Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-reliable-remote-access-across-windows-networks/"><u>Ensuring Reliable Remote Access Across Windows Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-faux-pas-an-experts-guide-to-safe-practices/"><u>Avoiding Windows 11 Faux Pas: An Expert's Guide to Safe Practices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-virtual-playstation-experience-at-your-fingertips-top-5-for-2024/"><u>[New] Virtual PlayStation Experience at Your Fingertips (Top 5) for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/tricks-to-upgrade-streaming-quality-on-mobile-apps-like-facebook/"><u>Tricks to Upgrade Streaming Quality on Mobile Apps Like Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-cryptex-hold-on-and-hesitate-for-now/"><u>Cracking Cryptex: Hold On and Hesitate for Now</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-soundtrack-sovereignty-a-guide-to-the-top-20-youtube-music-kingdoms/"><u>2024 Approved  Soundtrack Sovereignty  A Guide to the Top 20 YouTube Music Kingdoms</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-memory-overuse-in-user-services-and-connected-devices/"><u>Addressing Memory Overuse in User Services and Connected Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-tackle-office-errors-a-winos-approach/"><u>Efficient Strategies to Tackle Office Errors: A WinOS Approach</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-unveiling-sharex-analyses-and-options/"><u>In 2024, Unveiling ShareX  Analyses & Options</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-experts-guide-to-effortless-video-submissions-on-igtv/"><u>[Updated] In 2024, The Expert's Guide to Effortless Video Submissions on IGTV</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-top-rated-green-screen-software-for-mobile-devices-free-download/"><u>New In 2024, Top-Rated Green Screen Software for Mobile Devices Free Download</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-local-gpo-control-on-windows-11/"><u>Unlock the Power of Local GPO Control on Windows 11</u></a></li>
</ul></div>
