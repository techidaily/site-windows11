---
title: "Streamlined Methods: Deleting Saved Wi-Fi in Win 11"
date: 2024-09-05T02:10:01.489Z
updated: 2024-09-06T02:10:01.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlined Methods: Deleting Saved Wi-Fi in Win 11"
excerpt: "This Article Describes Streamlined Methods: Deleting Saved Wi-Fi in Win 11"
keywords: Wi-Fi Delete Procedure,Win 11 Wi-Fi Removal,Streamline Wi-Fi Disconnect,Deleting Saved Networks Win,Win 11 Wi-Fi Unsave,Efficient Wi-Fi Cleanup,Remove Win 11 Saves
thumbnail: https://thmb.techidaily.com/7dc1f793da1f2b9c448c995323e3532e944d0308246b622538179ed42958d614.jpg
---

## Streamlined Methods: Deleting Saved Wi-Fi in Win 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.


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
<li><a href="https://facebook-videos.techidaily.com/new-digital-expansion-social-story-downloader/"><u>[New] Digital Expansion  Social Story Downloader</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capture-every-pixel-of-pc-gaming-bliss-6-ways/"><u>[New] In 2024, Capture Every Pixel of PC Gaming Bliss (6 Ways)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-how-to-blur-pictures-on-iphone-for-free/"><u>[New] In 2024, How to Blur Pictures on iPhone for Free</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-premier-guidance-leading-ringtone-artisans-iphone/"><u>[New] In 2024, Premier Guidance  Leading Ringtone Artisans iPhone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-modify-twitter-clip-visuals-for-2024/"><u>[New] Modify Twitter Clip Visuals for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-pedagogical-picks-the-most-effective-video-recording-tools-for-instructors-for-2024/"><u>[New] Pedagogical Picks  The Most Effective Video Recording Tools for Instructors for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-concept-to-creation-crafting-youtube-video-splits-for-2024/"><u>[Updated] From Concept to Creation  Crafting YouTube Video Splits for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-obscurity-to-star-in-3-simple-steps/"><u>[Updated] From Obscurity to Star in 3 Simple Steps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-iphone-camera-adjustment-guide/"><u>[Updated] Step-by-Step iPhone Camera Adjustment Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-broadcast-repeat-looping-youtube-video-magic-for-your-setup/"><u>2024 Approved  Broadcast Repeat  Looping YouTube Video Magic for Your Setup</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/boost-engagement-sharing-streams-from-twitch-on-fb-for-2024/"><u>Boost Engagement  Sharing Streams From Twitch on FB for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-e-book-acquisition-for-iphones-and-ipads-via-the-native-books-application/"><u>Effortless E-Book Acquisition for iPhones and iPads via the Native Books Application</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unlisted-device-detected-error-in-win1011/"><u>Fixing Unlisted Device Detected Error in Win10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-seamlessly-integrate-captions-into-youtube-videos/"><u>How to Seamlessly Integrate Captions Into YouTube Videos</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/rating-video-content-bringing-youtube-into-powerpoint-for-2024/"><u>Integrating Video Content  Bringing YouTube Into PowerPoint for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-snappydriver-v113-worth-your-time-detailed-review-inside/"><u>Is SnappyDriver v1.13 Worth Your Time? Detailed Review Inside!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-gaming-3-methods-for-directory-unlock/"><u>Mastery in Gaming: 3 Methods for Directory Unlock</u></a></li>
<li><a href="https://blog-min.techidaily.com/maximize-video-excellence-effortlessly-transform-your-visuals-with-winxvideo-ai-technology/"><u>Maximize Video Excellence Effortlessly - Transform Your Visuals with Winxvideo AI Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-window-11-app-opener-techniques/"><u>Quick and Easy Window 11 App Opener Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win.</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-power-consumption-while-maintaining-peak-performance/"><u>Reducing Power Consumption While Maintaining Peak Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-inaudible-audio-on-wireless-devices/"><u>Resolving Inaudible Audio on Wireless Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-your-networks-first-line-of-defense/"><u>Revamping Your Network's First Line of Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-legalities-shun-chatbots-for-windows-keys/"><u>Skirting Legalities: Shun Chatbots for Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-inked-woes-a-guide-to-fixing-windows-pen-devices/"><u>Solve Your Inked Woes: A Guide to Fixing Windows Pen Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-w10w11-interruptexception-bsod-a-comprehensible-guide/"><u>Solving W10/W11 INTERRUPT_EXCEPTION BSOD: A Comprehensible Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-the-steps-to-epic-gaming-success/"><u>Speeding Up the Steps to Epic Gaming Success</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-streamlining-your-win11-routines/"><u>Speedy Boot: Streamlining Your Win11 Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-pc-functionality-addressing-11-windows-problems/"><u>Streamlining PC Functionality - Addressing 11 Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-audio-advantage-top-4-programs-for-surpassing-windows-100-limit/"><u>The Audio Advantage: Top 4 Programs for Surpassing Windows' 100%% Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-switch-for-classic-gaming-in-the-windows-photo-hub/"><u>The Easy Switch for Classic Gaming in the Windows Photo Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/the-os-metamorphosis-insights-into-w10-and-w11-developments/"><u>The OS Metamorphosis: Insights Into W10 and W11 Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unseen-consequences-of-cost-saving-windows-activation/"><u>The Unseen Consequences of Cost-Saving Windows Activation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ate-guide-to-the-most-effective-16-youtube-intros-for-2024/"><u>Ultimate Guide to the Most Effective 16 YouTube Intros for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-compressed-storage-on-windows-11/"><u>Unlocking Compressed Storage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-successful-remote-steam-connectivity/"><u>Unlocking Successful Remote Steam Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-system-restore-issue-0x80042306-in-win10/"><u>Unraveling System Restore Issue 0X80042306 in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ram-cache-basics-and-cleansing-methods/"><u>Windows RAM Cache Basics and Cleansing Methods</u></a></li>
<li><a href="https://techidaily.com/x50-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>X50 Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
</ul></div>
