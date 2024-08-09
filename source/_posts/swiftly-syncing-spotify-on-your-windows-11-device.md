---
title: Swiftly Syncing Spotify on Your Windows 11 Device
date: 2024-08-08T06:10:45.863Z
updated: 2024-08-09T06:10:45.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Syncing Spotify on Your Windows 11 Device
excerpt: This Article Describes Swiftly Syncing Spotify on Your Windows 11 Device
keywords: Spotify QuickSync,Windows Spotify Sync,Spotify W11 Sync,Fast Spotify PC,WinSpotify Sync,Quick Spotify Windows,Swift Spotify 11
thumbnail: https://thmb.techidaily.com/487b81e16ea9432c9b3bc7ae56246949ca490ff5dbda3843a3191dbeadf76d9d.jpg
---

## Swiftly Syncing Spotify on Your Windows 11 Device

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about[how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-top-10-hilarious-and-emotional-instagram-memes-journey/"><u>[New] 2024 Approved  Top 10 Hilarious & Emotional Instagram Memes Journey</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-enhancing-live-broadcasts-with-hd-1080p-clarity-fb/"><u>[Updated] In 2024, Enhancing Live Broadcasts with HD 1080P Clarity (FB)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-snappro-v3-windows-screen-mastery/"><u>[Updated] In 2024, SnapPro V3  Windows Screen Mastery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfect-pictures-at-a-click-the-10-best-grids/"><u>[Updated] Perfect Pictures at a Click - The 10 Best Grids</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-problem-solving-in-windows-10-and-11-via-shortcuts/"><u>Accelerating Problem-Solving in Windows 10 & 11 via Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-crystal-clarity-on-your-windows-taskbar/"><u>Achieving a Crystal Clarity on Your Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fix-windows-gaming-woe-errors/"><u>Avoid Disruption, Fix Windows' Gaming WoE Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-frozen-savers-4-tips-to-fix-windows-issues/"><u>Avoid Frozen Savers: 4 Tips to Fix Windows Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-game-breaking-interruptions-fixed-steams-error-code-e84/"><u>Avoid Game-Breaking Interruptions: Fixed Steam’s Error Code E84</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/best-data-shields-on-windows-encryption-apps-analysis-150-chars/"><u>Best Data Shields on Windows: Encryption Apps Analysis (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/broken-bitsafe-vault-postpone-the-transition/"><u>Broken BitSafe Vault: Postpone the Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-failures-fixing-vagrant-boot-problems-win11/"><u>Bypassing Failures: Fixing Vagrant Boot Problems Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-troublesome-dism-error-0x800f082f/"><u>Bypassing Windows' Troublesome DISM: Error 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/calibrating-your-laptops-touch-response-for-maximum-comfort/"><u>Calibrating Your Laptop's Touch Response for Maximum Comfort</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-folder-tab-glitches-in-windows-11/"><u>Conquering Folder Tab Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-tips-for-changing-filter-key-options-in-windows/"><u>Convenient Tips for Changing Filter Key Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-ms-resouce-issue-for-text-display/"><u>Correcting Ms-Resouce Issue for Text Display</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-thumbnail-heights-in-windows-11-ui/"><u>Customize Thumbnail Heights in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-windows-error-0x8007021/"><u>Decoding and Correcting Windows Error 0X8007021</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-display-discrepancies-winning-windows-with-wisdom/"><u>Decoding Display Discrepancies: Winning Windows with Wisdom</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-high-cpu-drain-tips-for-vanguards-user-mode-service/"><u>Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-visual-noise-windows-11-tab-control/"><u>Decreasing Visual Noise: Windows 11 Tab Control</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/exploring-the-language-of-thanksgiving-mandarins-xiexie/"><u>Exploring the Language of Thanksgiving: Mandarin's Xièxiè</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-samsung-galaxy-m34-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Samsung Galaxy M34</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-nokia-c12-plus-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Nokia C12 Plus to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-key-to-attracting-views-youtube-image-marketing/"><u>In 2024, The Key to Attracting Views  YouTube Image Marketing</u></a></li>
<li><a href="https://extra-information.techidaily.com/livelink-audio-visual-crafting-portal/"><u>LiveLink Audio-Visual Crafting Portal</u></a></li>
<li><a href="https://tech-revival.techidaily.com/openai-gpt-4-vs-google-palm-2-an-in-depth-look-at-their-unique-features/"><u>OpenAI GPT-4 Vs. Google PaLM 2: An In-Depth Look at Their Unique Features</u></a></li>
<li><a href="https://screen-capture.techidaily.com/premier-screenshare-software-reviews-for-2024/"><u>Premier Screenshare Software Reviews for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unleash-immersive-visuals-dive-into-the-world-of-gaming-on-philips-evnia-oled-display-49-inches/"><u>Unleash Immersive Visuals: Dive Into the World of Gaming on Philips Evnia OLED Display, 49 Inches</u></a></li>
</ul></div>
