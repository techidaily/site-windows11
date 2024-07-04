---
title: "Activating Edge Guards: Camera & Mic Use"
date: 2024-07-03T11:19:07.630Z
updated: 2024-07-04T11:19:07.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Activating Edge Guards: Camera & Mic Use"
excerpt: "This Article Describes Activating Edge Guards: Camera & Mic Use"
keywords: Edge Guard Activation,Microphone Control,Camera Security Enable,Phone Safety Lockdown,Privacy Mode Engage,Secure Call Function,Device Surveillance On
thumbnail: https://thmb.techidaily.com/5996397f505d52b0f60ffe77c36fd8859621590a57dd0707f44eeaa06c560dbc.jpg
---

## Activating Edge Guards: Camera & Mic Use

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

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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
<li><a href="https://windows11.techidaily.com/remedying-permission-problems-during-windows-1011-installer-errors/"><u>Remedying Permission Problems During Windows 10/11 Installer Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-techniques-for-an-opening-windows-terminal/"><u>Mastering Techniques for an Opening Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/purpose-and-key-aspects-of-vcplusplus-distributions/"><u>Purpose & Key Aspects of VC++ Distributions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-10-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-user-interaction-essential-modifications-for-windows-11s-taskbar/"><u>Perfecting User Interaction: Essential Modifications for Windows 11'S Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-windows-11s-concealed-query-engine/"><u>Initiating Windows 11'S Concealed Query Engine</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-task-execution-windows-keyboard-tips-and-tricks/"><u>Speedy Task Execution: Windows Keyboard Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-step-by-step-silencing-audio-in-iphone-videos/"><u>2024 Approved Step-by-Step Silencing Audio in iPhone Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-earnings-on-youtube-shorts-essentials-and-prospective-income/"><u>2024 Approved  Maximizing Earnings on YouTube Shorts  Essentials & Prospective Income</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-join-the-fun-top-5-free-online-video-merger-tools-you-need-to-try/"><u>Updated In 2024, Join the Fun Top 5 Free Online Video Merger Tools You Need to Try</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-infinix-smart-8-plus-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Infinix Smart 8 Plus?</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-honor-magic-6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-mobile-listening-androids-best-podcast-apps-top-6/"><u>[New] Mastering Mobile Listening  Android's Best Podcast Apps (Top 6)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-leverage-twitchs-potential-with-youtube-streaming-guide/"><u>2024 Approved  Leverage Twitch's Potential with YouTube Streaming Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-detailed-look-logitechs-elite-4k-webcam-review/"><u>[Updated] In 2024, Detailed Look  Logitech’s Elite 4K Webcam Review</u></a></li>
</ul></div>
