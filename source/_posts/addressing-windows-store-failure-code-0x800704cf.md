---
title: Addressing Windows Store Failure Code 0X800704CF
date: 2024-07-11T22:09:52.033Z
updated: 2024-07-12T22:09:52.033Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Store Failure Code 0X800704CF
excerpt: This Article Describes Addressing Windows Store Failure Code 0X800704CF
keywords: WinStoreErrorCode0xCF,XASFailureWindows,ErrorCode0X800704CF,StoreAppFailure0XCF,WindowsOSWinStoreError,0X800704CFApplication,Win10Store0xCFIssue
thumbnail: https://thmb.techidaily.com/f66305bee95e2c8cfda71737bc488d60f6c275330b2e729ec458216f465e024e.png
---

## Addressing Windows Store Failure Code 0X800704CF

 Many Microsoft Store users have reported they can’t use the app in both Windows 10 and 11 because of error 0x800704CF. Error 0x800704CF occurs when those users attempt to log into Microsoft Store. Its error message says, “You’ll need the internet for this… 0x800704CF.” This issue arises even when users are connected to the internet and can open web pages.

 Thus, error 0x800704CF is seemingly a Microsoft Store connection issue that renders the app inoperative in Windows 11 and 10\. If you're facing this issue this is how you can resolve error 0x800704CF.

## 1\. Run the Internet Connection and Network Adapters Troubleshooters

 Windows 11 and 10 have a handy collection of troubleshooters that can be a good starting point for fixing many issues. The Internet Connection and Network Adapters troubleshooters could be useful for resolving error 0x800704CF. You can access those troubleshooters via the Control Panel in Windows 11 and 10 as follows:

1. Press**Win + R** at the same time to launch a Run dialog accessory.
2. Input Control Panel in Run and click**OK** .
3. Select the**Large icons** option on Control Panel’s**View by** menu.  
![The Control Panel's large icon view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel.jpg)
4. Click**Troubleshooting** to access that applet.
5. Select the**View all** option to see the full list of troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
6. Then double-click**Internet Connections** or**Network Adapter** to open one of those troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
7. Click**Next** in those troubleshooters and apply any potential fixes suggested.

 Windows Store App is also a troubleshooting tool that could be useful for addressing error 0x800704CF. That one might fix issues with the Microsoft Store app. So, consider running that troubleshooter as well if the others don't provide a fix.

## 2\. Repair and Reset the Microsoft Store App

 Windows has two troubleshooting options for fixing Microsoft Store when it’s not working right. Those Repair and Reset options can resolve all kinds of app bugs and corruption errors. So, those options could feasibly resolve error 0x800704CF for some users. Check out our guide about [how to reset apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this resolution.

![The Reset and Repair buttons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-button.jpg)

## 3\. Set a Different DNS Server

 Changing DNS server settings is a resolution that’s worked for some users who’ve needed to fix error 0x800704CF. To apply this solution, change your PC’s DNS server to Google via the Control Panel. Our guide for [how to change your DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) includes step-by-step instructions for how to do that along with the required Google DNS addresses.

![DNS server settings on the Internet Protocol Version window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/internet-protocal-window.jpg)

## 4\. Execute the Remove Proxy Server Command

 Another confirmed method for fixing error 0x800704CF is to run a command for removing the proxy server. Users who’ve confirmed this potential solution ran the Netsh.exe utility to disable proxy, which sets more direct internet access. This is how you can remove the proxy server with the Command Prompt:

1. First, locate the Command Prompt by opening the search box (press**Win** +**S**) and inputting cmd.
2. Open Command Prompt with elevated privileges by clicking a**Run as administrator** option for that app inside the search tool.
3. Input the Netsch.exe command and hit**Enter** :  
`netsh winhttp reset proxy`  
![The remove proxy command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-proxy-command.jpg)
4. Restart Windows 11 or 10 after executing the command.

## 5\. Disable the Microsoft Network Component Setting Client

 Some users have been able to fix error 0x800704CF by disabling the**Microsoft Network Connection** setting, which is enabled by default. It’s ok to disable that component for your connection so long as you don’t need to access resources on a Microsoft network. You can disable the**Client for Microsoft Network** option as follows:

1. Open the Run dialog with the**Win +** **R** key combination.
2. Type input**ncpa.cpl** inside Run.
3. Click**OK** to access the Network Connections Control Panel applet.
4. Right-click your internet network adapter to select a**Properties** option for it.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option2.jpg)
5. Deselect the**Client for Microsoft Networks** checkbox.  
![The Client for Microsoft Networks checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/client-for-microsoft-network-option.jpg)
6. Select**OK** to save the new property setting, and restart your computer.

## 6\. Reinstall the Network Adapter Driver

 Error 0x800704CF can occur because of a network adapter driver issue. If your PC’s network driver is faulty, reinstalling it could be the potential solution for you. Try reinstalling your PC’s network adapter driver like this:

1. Use one of the many [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) and expand the**Network adapters** category.
2. Then right-click your PC’s internet network adapter to select an**Uninstall** **device** option for it.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-context-menu-option.jpg)
3. Select the**Delete the driver** (or**Attempt to remove the driver**) checkbox.
4. ![The Delete the driver software for this device checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-device-window.jpg)  
 Click**Uninstall** inside the confirmation dialog window.
5. To reinstall, click the**Action** menu.  
![The Scan for hardware changes option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-for-hardware-changes.jpg)
6. Select**Scan for hardware changes** on the menu to detect and reinstall the missing network driver.

## 7\. Reregister the Microsoft Store App

 Reregistering the Microsoft Store app will reset it to a default configuration, which is the closest thing to reinstalling that app (it doesn’t have an option for uninstalling).

 To apply this solution, open Command Prompt with admin rights, as outlined in steps one and two of resolution four in this guide. Then execute this command:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml&}`

## 8\. Reset Your PC’s Network

 Another potential cause of error 0x800704CF is misconfigured network settings. To address such a potential cause, you can reset your PC’s network components to default settings. Doing so also reinstalls network adapters.

![The Network Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/network-reset-option.jpg)

 A network reset will erase saved connection details. So, make sure you’ve got your network password handy for re-establishing your connection. Our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide tells you how to apply this possible error 0x800704CF solution in Windows 11\. Fortunately, the steps for Windows 10 are the same.

## 9\. Set Up an Alternative User Account

 You might need to fix error 0x800704CF because of an issue with your current user account. Some Windows troubleshooting tools could feasibly resolve that user account glitch. However, setting up and migrating to a new user account is an alternative troubleshooting method that you can try.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-option2.jpg)

 To apply this solution, check out our post for [resolving Windows issues by setting up a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) . Create a new local user account as instructed in that article, and then log in to the new account to see if error 0x800704CF occurs there. If not, you can migrate your user files to the new account as covered in that guide.

## Get Microsoft Store Error 0x800704CF Sorted on Your PC

 Error 0x800704CF can be a taxing issue to resolve in Windows. It can seemingly arise because of networking, the Microsoft Store app, and Windows account issues, which makes troubleshooting that issue a bit of a slog. However, the troubleshooting methods outlined above will probably get error 0x800704CF sorted on most users’ PCs.

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
<li><a href="https://tiktok-videos.techidaily.com/updated-exploring-popular-alternatives-to-tiktok-updated-edition/"><u>[Updated] Exploring Popular Alternatives to TikTok - Updated Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-guide-to-forgotten-windows-11-themes/"><u>Exclusive Guide to Forgotten Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-multi-screen-brightness-best-tools-to-light-up-your-windows-monitors/"><u>Navigating Multi-Screen Brightness: Best Tools to Light Up Your Windows Monitors</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-automating-subtitles-for-social-media-visuals-on-instagram/"><u>[New] In 2024, Automating Subtitles for Social Media Visuals on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-store-error-code-0x80073cf3/"><u>Overcoming Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-notetaking-companions-the-7-finest-for-pen-tech/"><u>Perfect Notetaking Companions: The 7 Finest for Pen Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-solving-disk-errors-uninitialized-scenarios/"><u>Quick Guide to Solving Disk Errors: Uninitialized Scenarios</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-action-and-adventure-with-ions-pro-3-camera-insight/"><u>In 2024, Action and Adventure with ION's Pro 3 Camera Insight</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-exclusive-fb-to-mp3-conversion-just-click-instant-results/"><u>In 2024, Exclusive FB to MP3 Conversion - Just Click, Instant Results</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-elite-windows-recording-solution/"><u>In 2024, Elite Windows Recording Solution</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-composing-the-unseen-score-trailer-music-magic/"><u>2024 Approved  Composing the Unseen Score  Trailer Music Magic</u></a></li>
<li><a href="https://games-able.techidaily.com/reducing-risks-dont-tap-into-ps5s-microphone/"><u>Reducing Risks: Don't Tap Into PS5's Microphone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-the-shape-of-storytelling-exploring-youtubes-aspect-ratio-options/"><u>Updated 2024 Approved The Shape of Storytelling Exploring YouTubes Aspect Ratio Options</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capture-android-the-ultimate-recorder-at-no-cost-for-2024/"><u>Capture Android  The Ultimate Recorder at No Cost for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-noise-nullification-made-simple-a-complete-look-at-noise-reduction-in-adobe-premiere-pro/"><u>New In 2024, Noise Nullification Made Simple A Complete Look at Noise Reduction in Adobe Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stuck-context-menus-a-quick-guide-to-solutions/"><u>Overcoming Stuck Context Menus: A Quick Guide to Solutions</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-cutting-edge-8-lens-modifications-for-webcams/"><u>2024 Approved  Cutting-Edge 8 Lens Modifications for Webcams</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://youtube-web.techidaily.com/cial-outcomes-dailymotion-versus-youtube-earning-potential/"><u>Financial Outcomes  Dailymotion versus YouTube Earning Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-enabling-or-disabling-wi-fi-cost-tracking-in-windows-11/"><u>Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-stumbling-windows-discord-search-bar/"><u>Fixes for Stumbling Windows Discord Search Bar</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-on-iphone-14-pro-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication On iPhone 14 Pro</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/livestreaming-sovereigns-clash-for-2024/"><u>LiveStreaming Sovereigns Clash for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>How Can I Use a Fake GPS Without Mock Location On Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-a-winning-live-broadcast-essentials-and-strategies/"><u>2024 Approved  Crafting a Winning Live Broadcast  Essentials and Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flawed-setups-a-guide-to-windows-package-woes/"><u>Fixing Flawed Setups: A Guide to Windows Package Woes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-mastery-in-making-stunning-discord-pfps-with-minimal-effort/"><u>2024 Approved  Mastery in Making Stunning Discord Pfps with Minimal Effort</u></a></li>
<li><a href="https://windows11.techidaily.com/notepaddarksettingsinstructionswin1011/"><u>NotepadDarkSettingsInstructionsWin10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-lowering-tiworkerexe-process-resource-use/"><u>Methods for Lowering TiWorker.exe Process Resource Use</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-configure-time-zones-on-windows-manually/"><u>Quick Guide: Configure Time Zones on Windows Manually</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/recognizing-clear-barrier-collapse-soundscape/"><u>Recognizing Clear Barrier Collapse Soundscape</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-you-when-your-nokia-g42-5g-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Nokia G42 5G is off? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/how-to-blur-the-video-background-in-a-microsoft-teams-meeting-in-2024/"><u>How to Blur the Video Background in a Microsoft Teams Meeting, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-x0001-error-on-w10w11-systems/"><u>Overcoming GeForce X0001 Error on W10/W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-how-to-utilize-execution-nicknames/"><u>Insights on How to Utilize Execution Nicknames</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/audacity-alternatives-unveiled-the-best-free-nonaudacity-apps-on-your-desktop/"><u>Audacity Alternatives Unveiled The Best Free Nonaudacity Apps on Your Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
</ul></div>
