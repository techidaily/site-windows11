---
title: "Access Control: Microphone and Camera via Edge Protection"
date: 2024-06-25T11:55:29.497Z
updated: 2024-06-26T11:55:29.497Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Access Control: Microphone and Camera via Edge Protection"
excerpt: "This Article Describes Access Control: Microphone and Camera via Edge Protection"
keywords: Edge Security Access,Microphone Cam Control,Edge Privacy Settings,Edge Device Management,Edge Encryption Safety,Secure Edge Cameras,Audio-Visual Edge Protect
thumbnail: https://thmb.techidaily.com/b41dfc1747c954c2591d35270b4a20079e5707f867334ccdc51bba558ecb898b.jpg
---

## Access Control: Microphone and Camera via Edge Protection

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
<li><a href="https://windows11.techidaily.com/triggering-the-verification-toolset-for-win11-systems/"><u>Triggering the Verification Toolset for Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-financial-gains-with-w11-pro-key-deals/"><u>Unlock Financial Gains with W11 Pro Key Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-access-your-outlook-preview/"><u>Unlocking Windows: Access Your Outlook Preview</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-bring-back-the-memories-top-5-ps1-emulation-apps-for-pc-for-2024/"><u>[New] Bring Back the Memories - Top 5 PS1 Emulation Apps for PC for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-apple-iphone-8-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>Unlock Your Apple iPhone 8 in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-conquering-remote-work-mastering-the-use-of-zoom-and-gmail/"><u>In 2024, Conquering Remote Work  Mastering the Use of Zoom and Gmail</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-ultimate-guide-to-top-reads-popularized-by-booktok-enthusiasts-for-2024/"><u>The Ultimate Guide to Top Reads Popularized by BookTok Enthusiasts for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/auditory-craftsmanship-exploring-the-best-tools-for-editing-sounds-with-benefits-and-limitations/"><u>Auditory Craftsmanship Exploring the Best Tools for Editing Sounds with Benefits and Limitations</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-mp4-play-on-samsung-galaxy-f54-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Does MP4 play on Samsung Galaxy F54 5G?</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-fundamentals-of-compelling-documentary-screenplay/"><u>2024 Approved  The Fundamentals of Compelling Documentary Screenplay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-lava-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Lava</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-get-steady-best-free-video-stabilization-programs-for-windows-and-mac/"><u>Updated In 2024, Get Steady Best Free Video Stabilization Programs for Windows and Mac</u></a></li>
</ul></div>
