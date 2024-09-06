---
title: Essential Steps to Reopen Battle.net on Windows Desktop
date: 2024-09-05T02:16:56.091Z
updated: 2024-09-06T02:16:56.091Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps to Reopen Battle.net on Windows Desktop
excerpt: This Article Describes Essential Steps to Reopen Battle.net on Windows Desktop
keywords: Reopen Battle.net,Win Desktop Login,Navigate Net Closure,Resume Game Session,Close Battle Steps,Restart Battle Access,Login Windows Battle
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Essential Steps to Reopen Battle.net on Windows Desktop

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

## 1\. Set Battle.net to Run With Admin Rights

 This is a simple potential fix for Battle.net not opening that some users have confirmed works. Setting Battle.net to run as administrator will give that software elevated system access, which can resolve permission issues. You can configure Battle.net to always run with administrative rights like this:

1. Open Battle.net’s installation directory (folder) within File Explorer.
2. Next, click the**Battle.net Launcher.exe** file with your right mouse button and select**Properties** .
3. Click**Compatibility** on the Battle.net Launcher.exe Properties window.
4. Select**Run this program as administrator** if that checkbox isn’t selected.  
![The Run this program as an administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/run-this-program-as-administrator-option.jpg)
5. Press the Properties window’s**Apply** button.

 In addition, running the software in compatibility mode might help some users fix Battle.net not opening. You can do that by selecting the**Run this program in compatibility mode** option on the same**Compatibility** tab. Choose Windows 8 on the drop-down menu.

## 2\. Delete the Battle.net and Blizzard Entertainment Data Folders

 Battle.net and Blizzard Entertainment are two cache folders for Blizzard’s game launcher software. The Battle.net software often doesn’t start right when those folders contain corrupted data. Deleting those directories will clear Battle.net’s cache.

This is how you can erase those folders in Windows 11/10:

1. First, make sure there aren’t any Battle.net background processes running by[opening Task Manager’s Process tab](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) . Disable any Battle.net processes you see there by selecting them and clicking**End task** .
2. Hold the**Windows** keyboard key and press**E** to view the Explorer file and folder manager.
3. Clear Explorer’s folder path bar, and input this directory location there: C:\\ProgramData  
![The Blizzard Entertainment folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/blizzard-entertainment-folder.jpg)
4. Right-click the Battle.net directory and select the**Delete** context menu option.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-delete-button.jpg)
5. Next, erase the Blizzard Entertainment folder.
6. Try opening Battle.net again.

 This should hopefully clear any cache issues and Battle.net should open correctly.

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check the Secondary Logon Service Is Enabled

 The Secondary Logon service enables the starting of processes with alternative types of user credentials. That’s a required prerequisite service for Battle.net’s Blizzard agent. So, check Secondary Login is enabled and running like this:

1. To open Services, click the search box or magnifying glass on your Windows 11/10 taskbar. Type**services.msc** in the search box, and select the Services app.
2. Double-click**Secondary Logon** to view the properties window for that service.  
![The Secondary Logon service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/secondary-logon-service.jpg)
3. Set the**Startup type** option to**Automatic** .
4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
5. Remember to select**Apply** to save the setting.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select**OK** to exit the Secondary Logon Properties window.
7. Click**Restart** on the Start menu in Windows 11/10.

 If you find Secondary Logon is already enabled, restart the service instead. Right-click Secondary Logon on the Services window to select**Restart** . Or you can click**Stop** and**Start** in the service’s properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall will block Battle.net from connecting with Blizzard services if that software isn’t permitted through it. To test if that firewall is blocking the Battle.net client, temporarily disable it in the following steps:

1. First, open WDF in the Control Panel with a method in our guide for opening the Windows Defender Firewall applet.
2. Select the**Turn Windows Defender Firewall on or off** navigation option on the left of the applet.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-defender-control-panel-applet.jpg)
3. Click the**Turn off Windows Defender Firewall** options for both the public and private network settings.  
![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
4. Select**OK** to save the new WDF options.
5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about[allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

## 5\. Disable Third-Party Antivirus and Firewall Software

 Some third-party antivirus and firewall software can also block Battle.net from running. Antivirus utilities sometimes wrongly identify legitimate programs to be malware. So, temporarily disable third-party antivirus tools or firewalls before selecting to launch Battle.net if you don’t want to uninstall anything.

 You can usually find options for disabling third-party antivirus software on their context menus. So, right-click an antivirus icon in the system tray and look for an option to disable or turn off its shield on the menu that opens. If that works, you’ll know what’s causing the issue. Whitelist Battle.net in your antivirus tool’s exclusion settings.

## 6\. Disable the Proxy Server

 Proxy servers conflict with Battle.net’s login module, which can prevent the software from launching. Even if you can’t recall enabling a proxy server yourself, double-check the proxy server setting isn’t selected in Windows. You can disable the proxy server as follows:

1. Bring up the file and app search box in Windows.
2. Enter**inetcpl.cpl** in the Type here to search text box.
3. Select**inetcpl.cpl** to view Internet Properties.
4. Click**Connections** to access network options.
5. Next, click**LAN settings** to view a Local Area Network (LAN) window.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/LAN-settings-button.jpg)
6. Uncheck (deselect) the**Use a proxy server** option if its checkbox is selected.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Use a proxy server checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-use-a-proxy-server-checkbox.jpg)
7. Press the**OK > Apply** buttons.

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our[Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our[guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After setting a clean boot, restart your PC and try launching Battle.net. Did that potential resolution work? If it did, clean booting likely eliminated a program or service conflicting with Battle.net. Then you can keep the boot configuration as it is or attempt to figure out what software or service caused the issue.

## 8\. Reinstall the Battle.net Software

 Finally, reinstall Battle.net Launcher if all else fails. Reinstalling that software will replace its files and ensure you’re utilizing the latest version. That won’t uninstall games installed with Battle.net.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-programs-and-features-applet.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can remove Battle.net in Control Panel’s Programs and Features applet, as outlined in our[guide for uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After uninstalling the game launcher, open the[Battle.net desktop app](https://www.blizzard.com/en-us/apps/battle.net/desktop) download page; click**Download for Windows** on that page. Then double-click the**Battle.net-Setup.exe** file in whatever folder it downloaded to, and go through the setup wizard to install.

## Enjoy Blizzard Battle.net Games Again

 When you’ve got Battle.net up and running again, you’ll be able to download, launch, and play Blizzard games. As there are many potential causes for Battle.net not starting, we can’t guarantee the solutions in this guide will resolve all startup issues for that software.

 However, those potential resolutions will address the most common causes for Battle.net not opening in Windows 11 and 10\. So, there’s a very good chance at least one will kick-start Blizzard’s gaming client on your PC.

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
<li><a href="https://youtube-videos.techidaily.com/new-8-pioneering-exercise-videos-to-keep-your-viewers-active/"><u>[New] 8 Pioneering Exercise Videos To Keep Your Viewers Active</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-breakthrough-tactics-for-optimal-iptv-screening/"><u>[New] Breakthrough Tactics for Optimal IPTV Screening</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-strategies-for-capturing-webinars-effectively-for-2024/"><u>[New] Top Strategies for Capturing Webinars Effectively for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-free-yourself-from-video-edges-on-youtube/"><u>[Updated] Free Yourself From Video Edges on YouTube</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-dynamic-decibels-the-best-background-sounds-for-yt-shorts/"><u>[Updated] In 2024, Dynamic Decibels  The Best Background Sounds for YT Shorts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-reimagining-photography-toolwiz-photosapps-full-on-review/"><u>[Updated] In 2024, Reimagining Photography  Toolwiz PhotosApp's Full-On Review</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-photoshop-shake-reduction-is-it-really-useful/"><u>[Updated] Photoshop Shake Reduction - Is It Really Useful?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/iphonemp4/"><u>【IPhoneでMP4動画が試みるなら？】再生失敗原因とそれを修正するポイント集 - 未来のガイドブック</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-free-and-uncomplicated-youtube-image-extractor-tools-reviewed/"><u>2024 Approved  Free and Uncomplicated YouTube Image Extractor Tools Reviewed</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-your-steam-balance-with-savvy-investments/"><u>Boosting Your Steam Balance with Savvy Investments</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-7-innovative-fixes-for-rename-issue-in-win-11/"><u>Expert Advice: 7 Innovative Fixes for Rename Issue in Win 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/how-to-remove-a-desktop-discord-server/"><u>How to Remove a Desktop Discord Server</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-silence-your-license-will-end-soon-warning-on-woses/"><u>How To Silence Your License Will End Soon Warning on WOSes</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-access-barriers-for-insiders-in-windows-11/"><u>Implementing Access Barriers for Insiders in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-a-user-friendly-guide-to-seamless-collaboration-across-different-operating-systems-via-skype-group-chats/"><u>In 2024, A User-Friendly Guide to Seamless Collaboration Across Different Operating Systems via Skype Group Chats</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovate-your-live-broadcast-on-mac-with-1-5-software/"><u>In 2024, Innovate Your Live Broadcast on Mac with #1-5 Software</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-windows-11-in-apples-ecosystem-with-parallels/"><u>Journey to Windows 11 in Apple's Ecosystem with Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-clutter-free-windows-desktop/"><u>Master the Art of Clutter-Free Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-computer-crisis-management-with-tools/"><u>Mastering Computer Crisis Management with Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-secure-file-management-using-powertoys/"><u>Mastery of Secure File Management Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/minimize-lag-troubleshooting-windows-extended-monitor-use/"><u>Minimize Lag: Troubleshooting Windows Extended Monitor Use</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-imessage-on-non-ios-devices-tips-and-tricks/"><u>Navigating iMessage on Non-iOS Devices: Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-spotify-connectivity-snags/"><u>Navigating Through Common Spotify Connectivity Snags</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-public-ip-with-commands-windows-edition/"><u>Pinpoint Public IP with Commands, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-windows-video-workflow-adopt-distributed-power-by-tdarr-technology/"><u>Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-hidden-remove-pin-switch-on-windows-11/"><u>Reactivating Hidden Remove PIN Switch on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missing-update-files-issue-error-code-0x80070003-in-windows/"><u>Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unfunctional-enter-key-in-windows-os/"><u>Resolving Unfunctional Enter Key in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/show-more-pins-strategies-for-start-screen/"><u>Show More Pins: Strategies for Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-strategies-for-merging-content-on-win-11/"><u>Smart Strategies for Merging Content on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approaches-to-shutting-down-your-computer/"><u>Strategic Approaches to Shutting Down Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-thx-not-responding-to-windows-commands/"><u>Tackling THX Not Responding to Windows Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/testing-your-mic-a-windows-procedure/"><u>Testing Your Mic: A Windows Procedure</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-glitches-the-ultimate-guide-for-eradicating-error-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>Triumph Over Glitches: The Ultimate Guide for Eradicating Error 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-error-in-games-on-latest-windows-os/"><u>Troubleshooting Steam Error in Games on Latest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-crossed-out-icons-their-purpose-and-meaning/"><u>Understanding Crossed Out Icons: Their Purpose and Meaning</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-whisper-techniques-concealing-commands-effectively/"><u>Window's Whisper Techniques: Concealing Commands Effectively</u></a></li>
</ul></div>
