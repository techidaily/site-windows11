---
title: Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included!
date: 2024-08-27T16:07:50.700Z
updated: 2024-08-28T16:07:50.700Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included!
excerpt: This Article Describes Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included!
thumbnail: https://thmb.techidaily.com/5e8073ee6fa80b00481e787b8ffd70b1f1a083692a90f4785a3be5a978334fdb.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

When you met boot error with Windows 10, you hoped that automatic repair will help fix the problem. But it got you more troubles. The worse thing is that repair process seems never end. Then what to do to end the loop? Read on to find the solutions.  

 Since the Windows keeps restarting, it is impossible for you access Advanced Options, that you can fix the problem there. In this case, you can boot from a USB or DVD.
  
 To use the solutions below, you’ll need to prepare a bootable USB or a DVD with an installation file on it. If you are not sure how to create a bootable USB, refer [How to Burn Windows 10 ISO to USB](https://tools.techidaily.com/drivereasy/download/) . Note you need to do this on another computer.
  
 **First start your PC from the USB or DVD and open Command Prompt**
  
 1.  
  
 For USB bootable way:  
  
 Plug the USB the computer that has the problem.After you power on the computer, press function key, usually F2 or F12, to enter boot menu. The key to enter boot menu depends on the computers that you are using. You can go to the PC manufacturer’s website to check for it.
  
 For DVD bootable way:  
  
 Insert the DVD to the computer that has the problem. Wait until you see the message “Press any key to boot from CD or DVD”. Press any key to continue. If you don’t see this message, you probably have to change the boot order in the BIOS (Basic Input/Output System) .  
  
 Learn[How to Boot from a USB Drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. When you go to the setup screen, select the Language that you wish to use.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
 2\. Type **bcdedit /set GUID recoveryenabled No** and hit**Enter** . Replace GUID with the number that you noted in last step. (For example, if the number is 7ce0dd34-d277-11e4-8263-68f7286346fb, the full command will be “bcdedit /set 7ce0dd34-d277-11e4-8263-68f7286346fb recoveryenabled No”)  
  
 3\. Reboot your PC and Windows should start without no problem.

 **Solution 3: Remove Your RAM**
  
 The loop error can be fixed by simply removing the RAM. You can try this solution. Before removing, remember to turn off the PC.If you have more than one RAM, remove one at a time then start your PC without it. You might need to do this a few times until you test every RAM module.

 After entering Windows, run a disk check to check if there is any problem with the disk, and run a system file check to check if some system files are corrupted. If neither of them work, try to restore Windows registry.  
  
**Run a disk check**
  
 Follow steps below:  
  
 1\. Open[**Command Prompt**](https://tools.techidaily.com/drivereasy/download/) as an administrator.
  
 2\. Type**chkdsk /f /r** and hit**Enter** . You need to wait a while until the process completes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
 Hope the solutions here will help you fix the Windows 10 Automatic Repair loop error.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-enhance-your-channels-image-adding-watermarks-and-logos-to-video-posts/"><u>[New] 2024 Approved  Enhance Your Channel's Image  Adding Watermarks & Logos to Video Posts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-choosing-screen-clarity-is-ultrawide-or-uhd-4k-better/"><u>[New] Choosing Screen Clarity  Is UltraWide or UHD 4K Better?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-the-complete-obs-playback-handbook/"><u>[Updated] 2024 Approved  The Complete OBS Playback Handbook</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-premium-window-calls-top-8-standout-titles/"><u>[Updated] In 2024, Premium Window Calls  Top 8 Standout Titles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-smart-social-media-strategies-from-youtube-to-facebook/"><u>[Updated] Smart Social Media Strategies  From YouTube To Facebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-step-by-step-guide-to-download-and-store-twitter-videos-on-phone-for-2024/"><u>[Updated] Step-by-Step Guide to Download and Store Twitter Videos on Phone for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ebook-shopping-simplified-how-to-securely-buy-and-read-on-your-iphone-or-ipad-with-books-by-apple/"><u>EBook Shopping Simplified: How to Securely Buy and Read on Your iPhone or iPad with Books by Apple</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-data-access-seamless-entry-into-windows-11-disk-editor/"><u>Expedite Data Access: Seamless Entry Into Windows 11 Disk Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-how-to-reset-win11-search-default-configurations/"><u>Expert Advice: How to Reset Win11 Search Default Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-roblox-on-screen-stop-issues-on-windows-systems/"><u>Fixing Roblox On-Screen Stop Issues on Windows Systems</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-infinix-note-30i-frp-by-drfone-android/"><u>Full Guide to Bypass Infinix Note 30i FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turn-off-windows-from-starting-spotify/"><u>Guide to Turn Off Windows From Starting Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-portable-software-menu-to-windows-10-and-11/"><u>How to Add a Portable Software Menu to Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-copy-and-paste-not-working-in-windows-11/"><u>How to Fix Copy and Paste Not Working in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-fix-startech-device-drivers-on-windows-11-8-and-7-comprehensive-guide/"><u>How to Fix StarTech Device Drivers on Windows 11, 8 & 7: Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-unmovable-scrolling-in-excel-windows/"><u>How to Rectify Unmovable Scrolling in Excel (Windows)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-p55-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel P55 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-oppo-find-n3-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Oppo Find N3 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-is-your-apple-iphone-13-mini-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone 13 mini in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-monitors-choosing-personalized-themes-in-win-1011/"><u>Maximizing Monitors: Choosing Personalized Themes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-your-windows-personalized-spotlight-image/"><u>Modify Your Windows Personalized Spotlight Image</u></a></li>
<li><a href="https://extra-resources.techidaily.com/nurturing-network-growth-for-top-tier-subscribers/"><u>Nurturing Network Growth for Top-Tier Subscribers</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-major-complaints-about-windows-11-launch/"><u>Peering Into Major Complaints About Windows 11 Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-retro-upgrades-atlasos-transformation/"><u>Pioneering Retro Upgrades: AtlasOS Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-reviving-a-vanished-windows-update/"><u>Quick Recovery: Reviving a Vanished Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-game-launch-hurdles-with-epic-logins/"><u>Reversing Game Launch Hurdles with Epic Logins</u></a></li>
<li><a href="https://facebook.techidaily.com/rights-and-rules-in-image-hosting-services/"><u>Rights and Rules in Image Hosting Services</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-of-error-0x0000004e-on-windows/"><u>Solving the Mystery of Error 0X0000004E on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-samsung-galaxy-m14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/spotting-the-green-light-and-red-alert-windows-login-status/"><u>Spotting the Green Light & Red Alert: Windows Login Status</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-missteps-in-mouse-travel-with-simple-fixes/"><u>Stopping Missteps in Mouse Travel with Simple Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-voice-input-in-windows-11-with-shortcuts-guide/"><u>Streamlining Voice Input in Windows 11 with Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-working-shift-with-simple-tweaks/"><u>Tackle Non-Working Shift with Simple Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-first-load-webpage-on-win11/"><u>Tailoring Your First Load Webpage on Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-future-of-videos-assessing-av1s-edge-over-vp9-for-2024/"><u>The Future of Videos  Assessing AV1's Edge over VP9 for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-secrets-how-to-make-contact-with-private-line-owners/"><u>Unveiling Secrets: How to Make Contact with Private Line Owners</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-windowss-notorious-pink-screens/"><u>Winning Against Windows's Notorious Pink Screens</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->