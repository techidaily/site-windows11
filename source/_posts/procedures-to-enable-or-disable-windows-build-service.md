---
title: Procedures to Enable or Disable Windows Build Service
date: 2024-06-25T11:57:45.517Z
updated: 2024-06-26T11:57:45.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Procedures to Enable or Disable Windows Build Service
excerpt: This Article Describes Procedures to Enable or Disable Windows Build Service
keywords: Windows Service Control,Disable Win Build Service,Enable Windows Services,Turn Off Windows BUILT-IN,Manage Windows BUILD SERVICE,Modify Windows BUILD SERVICES,Adjust Windows BUILT-IN Service
thumbnail: https://thmb.techidaily.com/769d83492280fd0660acd0112190d1d990d0e4305860168c39e79719f29b2ea7.jpg
---

## Procedures to Enable or Disable Windows Build Service

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-lockout-after-inactivity/"><u>Defining Windows Lockout After Inactivity</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-power-using-lav-filters-on-microsoft-windows/"><u>Harnessing Power: Using LAV Filters on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-audio-mastery-configuring-custom-volume-hotkeys/"><u>Win11 Audio Mastery: Configuring Custom Volume Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-work-around-microsoft-verified-app-restrictions/"><u>Methods to Work Around Microsoft-Verified App Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-14-pro-max-passcode-not-working-drfone-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 14 Pro Max Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-guide-to-zero-price-virtual-gatherings-for-2024/"><u>The Ultimate Guide to Zero-Price Virtual Gatherings for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-maximizing-the-potential-of-virtual-dialogue-secrets-from-a-pro-zoom-chat-guru/"><u>[New] 2024 Approved  Maximizing the Potential of Virtual Dialogue  Secrets From a Pro ZOOM Chat Guru</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-unlock-fcp-x-advanced-chroma-keying-techniques-for-video-editors/"><u>New In 2024, Unlock FCP X Advanced Chroma Keying Techniques for Video Editors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mobile-melodies-crafting-unique-phone-ringtones-for-android-enthusiasts/"><u>Mobile Melodies  Crafting Unique Phone Ringtones for Android Enthusiasts</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-best-10-ai-script-writers-to-choose/"><u>New Best 10 AI Script Writers to Choose</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-your-ultimate-guide-to-profit-from-youtube-videos-2e-2024/"><u>[New] Your Ultimate Guide to Profit From Youtube Videos (2E 2024)</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-staying-within-aspect-ratio-guidelines-for-youtube-style-tweeted-content/"><u>2024 Approved  Staying Within Aspect Ratio Guidelines for YouTube-Style Tweeted Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/elite-list-of-best-online-sound-capturing-devices-2023/"><u>Elite List of Best Online Sound Capturing Devices 2023</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-get-a-new-look-free-online-face-generators-for-everyone/"><u>Updated Get a New Look Free Online Face Generators for Everyone</u></a></li>
</ul></div>
