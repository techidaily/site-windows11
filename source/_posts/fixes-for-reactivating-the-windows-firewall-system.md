---
title: Fixes for Reactivating the Windows Firewall System
date: 2024-09-30T16:31:47.980Z
updated: 2024-10-07T08:36:15.459Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixes for Reactivating the Windows Firewall System
excerpt: This Article Describes Fixes for Reactivating the Windows Firewall System
keywords: Reactivate Windows Firewall,Fixing Firewall,Restart Firewall,Enable Firewall,Reset Firewall Settings,Update Firewall Policy,Confirm Firewall Status
thumbnail: https://thmb.techidaily.com/3b273f3dcd58de6bdeec53afcf9be971cffb1887a1cf9aa58c2806ddb93b59d9.jpg
---

## Fixes for Reactivating the Windows Firewall System

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-innovative-techniques-for-final-frame-enhancements-on-vimeo/"><u>[Updated] In 2024, Innovative Techniques for Final Frame Enhancements on Vimeo</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-as-your-dungeon-helper-discover-6-ways-to-master-online-adventures/"><u>ChatGPT as Your Dungeon Helper: Discover 6 Ways to Master Online Adventures</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-timeless-luxury-meets-functionality-with-the-new-michael-kors-access-gen-5e-mkgo-watch-review/"><u>Experience Timeless Luxury Meets Functionality with the New Michael Kors ACCESS Gen 5E MKGO Watch Review</u></a></li>
<li><a href="https://win-solutions.techidaily.com/getting-pathfinder-wrath-of-the-righteous-running-smoothly-after-launch-failures/"><u>Getting Pathfinder: Wrath of the Righteous Running Smoothly After Launch Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-or-disable-the-smartscreen-filter-in-windows-10-and-11/"><u>How to Enable or Disable the SmartScreen Filter in Windows 10 & 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-honor-magic-5-lite-frp-bypass-by-drfone-android/"><u>In 2024, About Honor Magic 5 Lite FRP Bypass</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-oppo-reno-11-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Oppo Reno 11 5G Phones with/without a PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mastering-language-skills-with-chatgpt-a-guide-to-utilizing-its-conversation-capabilities/"><u>Mastering Language Skills with ChatGPT: A Guide to Utilizing Its Conversation Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-troubleshoot-guide-for-error-x80072f30/"><u>Microsoft Store Troubleshoot Guide for Error X80072F30</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-in-game-communication-hurdles-with-windows-speech-tools/"><u>Rectifying In-Game Communication Hurdles with Windows Speech Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-inaudible-recordings-while-using-powerpoint/"><u>Remedy for Inaudible Recordings While Using PowerPoint</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ify-crafting-effective-youtube-subscription-buttons-for-2024/"><u>Simplify Crafting Effective YouTube Subscription Buttons for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-eradicating-installer-problems-on-windows-11/"><u>Strategies for Eradicating Installer Problems on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-calculator-visibility-on-windows-os/"><u>Sustained Calculator Visibility on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-solving-windows-exit-point-error/"><u>Unraveling and Solving Windows Exit Point Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-tips-for-better-mouseclicklock-implementation/"><u>Unveiling Tips for Better MouseClickLock Implementation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1726028592580-wonderfox/"><u>WonderFoxエンコーダで効率的に動画エンコーディングの仕組みと技術</u></a></li>
</ul></div>

