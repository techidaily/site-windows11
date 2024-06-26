---
title: "Pushing Boundaries: My Quest to Overcome App Guard Censorship"
date: 2024-06-25T12:06:51.476Z
updated: 2024-06-26T12:06:51.476Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pushing Boundaries: My Quest to Overcome App Guard Censorship"
excerpt: "This Article Describes Pushing Boundaries: My Quest to Overcome App Guard Censorship"
keywords: Boundary Push,Overcoming AppCensor,Quest for Freedom,Censorship Challenges,App Security Breach,Guard Override Techniques,Digital Rights Advocacy
thumbnail: https://thmb.techidaily.com/318f85e5a53d5f60469d32582133c5ee92bbc0ceb979fd63de287576e36507bb.jpg
---

## Pushing Boundaries: My Quest to Overcome App Guard Censorship

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://windows11.techidaily.com/stop-the-sleepy-slumber-of-hibernation-woes/"><u>Stop the Sleepy Slumber of Hibernation Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-installer-glitches-on-latest-windows-versions/"><u>Combatting Installer Glitches on Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-nuances-of-widget-alerts-in-windows/"><u>Navigating the Nuances of Widget Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-iphone-photographic-file-import-failures-on-windows-pcs/"><u>Handling iPhone Photographic File Import Failures on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-restoration-top-8-techniques-for-windows/"><u>Mastering File Restoration: Top 8 Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-bypass-admin-access-denied-message-on-pc/"><u>Tactics to Bypass 'Admin Access Denied' Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-cortana-in-windows-11-os/"><u>How to Mute Cortana in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-ai-copilot-enriches-windows-11-for-everyday-users/"><u>How AI Copilot Enriches Windows 11 for Everyday Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-vision-to-reality-benqs-masterpiece-the-bl2711u-monitor-review-for-2024/"><u>From Vision to Reality  BenQ’s Masterpiece, the BL2711U Monitor Review for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-how-to-record-a-voice-over-for-a-video/"><u>In 2024, How To Record A Voice Over For A Video</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-a-comprehensive-guide-on-vhs-technology-and-its-influence-on-video-editing/"><u>In 2024, A Comprehensive Guide on VHS Technology and Its Influence on Video Editing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-noble-mic-necessities-for-youtube-newbies-on-the-cheap/"><u>In 2024, Noble Mic Necessities for YouTube Newbies on the Cheap</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-vibevault-download-and-spin-professional-dj-music-for-2024/"><u>Updated VibeVault Download and Spin Professional DJ Music for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-unconventional-playground-the-top-10-wildest-tiktok-games-for-2024/"><u>[New] Unconventional Playground  The Top 10 Wildest TikTok Games for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-bulk-message-elimination-a-complete-handbook-for-the-discreet-discord-user/"><u>[Updated] In 2024, Bulk Message Elimination  A Complete Handbook for the Discreet Discord User</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-oppo-k11x-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Oppo K11x Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-phototext-techniques-for-stunning-3d-effects-for-2024/"><u>Advanced PhotoText Techniques for Stunning 3D Effects for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-gionee-f3-pro-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Gionee F3 Pro Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
</ul></div>
