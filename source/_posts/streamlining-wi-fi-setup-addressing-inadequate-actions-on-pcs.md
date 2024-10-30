---
title: "Streamlining Wi-Fi Setup: Addressing Inadequate Actions on PCs"
date: 2024-10-26T16:04:18.976Z
updated: 2024-10-30T17:15:25.195Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Wi-Fi Setup: Addressing Inadequate Actions on PCs"
excerpt: "This Article Describes Streamlining Wi-Fi Setup: Addressing Inadequate Actions on PCs"
keywords: Wi-Fi Setup Streamlining,Improve Wi-Fi Connection,Streamline Network Setup,Optimize Wi-Fi Installation,Enhance Wireless Connections,Simplify PC Networking,Efficient Wi-Fi Integration
thumbnail: https://thmb.techidaily.com/0244557d86d8e1a27dc054dedba4a1385b1696e504c943e408d092d2c07266c8.jpg
---

## Streamlining Wi-Fi Setup: Addressing Inadequate Actions on PCs

 The "Action needed" prompt for Wi-Fi in Windows pops up when users try to connect to a Wi-Fi network on their devices and can occur with both new and old/trusted networks.

 Below, we discuss the common causes of this problem alongside the troubleshooting methods you can try to fix this issue once and for all.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable the NCSI Probe From Windows Registry

 In most cases, the "Action Needed" prompt appears when there are corporate Wi-Fi networks with multiple endpoints available. This prompt is associated with the Network Connectivity Status Indicator (NCSI) feature, which verifies the network connection and internet access.

 Occasionally, the NCSI feature may mistakenly trigger this prompt while performing network connectivity checks, even if the network is functioning properly.

 To fix this problem, you can manually disable the NCSI Active probe via Windows Registry. However, before you proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Choose **Yes** in the User Account Control prompt.
4. Inside the Registry Editor, navigate to the location below:  
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet
5. Move to the right pane and right-click on the **EnableActiveProbing** value.  
![EnableActiveProbing key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-active-probing-key.jpg)

1. Type 0 in the text field for Value data and click **OK**.
2. Now, navigate to the following location:  
HKLM\Software\Policies\Microsoft\Windows\NetworkConnectivityStatusIndicator
3. Move to the right side and right-click on an empty space.
4. Choose **New** \> **DWORD (32-bit) Value** and rename it as **NoActiveProbe**.  
![NoActiveProbe key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/no-active-probe.jpg)
5. Double-click on this newly created value and change its value data to 1\.
6. Now, create another value the same way and name it as DisablePassivePolling.
7. Double-click on **DisablePassivePolling** and change its value data to 1 as well.  
![DisablePassivePolling key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disable-passive-polling.jpg)
8. Click **OK** to save the changes and exit the Registry Editor.
9. Finally, restart your computer and upon reboot, check if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable the NCSI Probe From GPE

 If using the Windows Registry did not work, you can also make the same changes using the Group Policy Editor.

 Follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "gpedit.msc" in Run and click **Enter**.
3. Choose **Yes** in the User Account Control prompt.
4. In the Group Policy Editor, navigate to the location below:  
​​​​​​​​​​​​​​Computer Configuration\Administrative Templates\System
5. Select **Internet Communication Management** \> **Internet Communication Settings** and click on **Turn off Windows Network Connectivity Status Indicator active tests**.  
![Network connectivity test policy in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/network-connectivity-test-policy.jpg)
6. Checkmark the box with **Enabled** and click **Apply** \> **OK** to save the changes.

7. Next, head over to the following location:  
​​​​​​​​​​​​​​Computer Configuration\Administrative Templates\Network
8. Select **Network Connectivity Status Indicator** \> **Specify passive polling**.  
![Specify passive polling policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/specify-passive-polling-policy.jpg)
9. Choose **Enabled** and click **Apply** \> **OK** to save the changes.

10. Close the Group Policy Editor and restart your computer.

 Hopefully, upon reboot, the issue will no longer appear.

## 3\. Run the Internet Connection Troubleshooter

 If the scenarios we have discussed above do not apply to you, you might also be facing the problem because of a temporary glitch in the system. In this case, you can run the internet connection troubleshooter. This is a built-in utility that scans your system for underlying related issues. If a problem is identified, it will either fix it for you or suggest a solution that you can apply automatically.

 Here is how you can run it:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Click on **System** and choose **Troubleshoot**.
3. Choose **Other troubleshooters**.
4. You should now be able to see a list of troubleshooters offered by Windows. Locate the Internet connection troubleshooter and click on the **Run** button for it.  
![Internet Connection Troubleshooter in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/internet-connection-troubleshooter.jpg)
5. Wait for the troubleshooter to complete its scan and once done, check if a problem is identified. If it is, click on the **Apply this fix** option. You can also apply a solution manually.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. In case the troubleshooter fails to identify the culprit, click on **Close the troubleshooter** option and move to the next method below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Fast Startup

 You might also be facing the issue if the fast startup feature is interfering with network-related processes in Windows. If this feature is enabled on your computer, disabling it might help fix the underlying error as this will allow the system to completely shut down, which can help in refreshing network settings and resolving any network-related issues.

 Here is how you can proceed:

1. Open Run by pressing the **Win** \+ **R** keys together.
2. Type "control" and click **Enter**.
3. In the Control Panel, expand the **View by** section and choose **Large icons**.
4. Click on **Power Options** from the list and select **Choose what the power buttons do**.  
![Choose what the power button does option of Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/choose-what-the-power-button-does.jpg)
5. Choose **Change settings that are currently unavailable** and navigate to the Shutdown settings option.

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Uncheck the box associated with **Turn on fast startup (recommended)**.  
![Disable Fast Startup on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-fast-startup-on-windows.jpg)
7. Click on the **Save changes** button and exit Control Panel. Check if the issue is now resolved.

## 5\. Try These Additional Generic Fixes

 If the specific fixes we have listed above have not worked for you, there are some additional fixes related to the network errors in Windows that you can try.

 These include updating the network drivers, re-enabling your wireless network adapter, installing the latest system updates, and resetting the network configurations on your computer. Our guide on[how to fix common Windows network errors](https://www.makeuseof.com/not-connected-any-networks-error-windows/) discusses all of these in detail, so you can head over there for step-by-step instructions.

## Fixing Network Connections in Windows Made Easy

 Network-related issues in Windows can be annoying, especially if they are preventing you from establishing a stable connection. Hopefully, the steps listed above will help you fix the "Action needed" problem for good.

 If you ever need to undo the changes that you made in the Registry Editor or GPE to fix this issue, simply re-enable the respective keys and policies by visiting the locations we have mentioned above in this guide. You can also contact the official Microsoft support team if the error appears even after you have tried all the solutions.

 Below, we discuss the common causes of this problem alongside the troubleshooting methods you can try to fix this issue once and for all.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-pioneers-in-post-production-top-tools-for-instagram-content-creators/"><u>[New] 2024 Approved Pioneers in Post-Production Top Tools for Instagram Content Creators</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-remedy-misidentified-face-photo-in-chat-corner/"><u>[Updated] 2024 Approved Remedy Misidentified Face Photo in Chat Corner</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-smartphone-security-iphone-xs-face-id-versus-galaxy-recognition/"><u>[Updated] Smartphone Security IPhone X’s Face ID Versus Galaxy Recognition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-instant-conferencing-zoom-in-the-eyes-of-gmail/"><u>2024 Approved Instant Conferencing Zoom in the Eyes of Gmail</u></a></li>
<li><a href="https://buynow-help.techidaily.com/7800-plus-revival-experience-the-classic-80s-nostalgia-with-modern-technology/"><u>7800 Plus Revival: Experience the Classic 80'S Nostalgia with Modern Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-awaken-divine-powers-within-windows-11-os/"><u>How to Awaken Divine Powers Within Windows 11 OS</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solutions-for-audio-files-missing-dlls/"><u>Immediate Solutions for Audio Files' Missing DLLs</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-pro-rated-top-8-convertors-for-subtitles-and-srts/"><u>In 2024, Pro-Rated Top 8 Convertors for Subtitles & SRTs</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-10-work-tips-if-you-cant-upgrade/"><u>Making Windows 10 Work: Tips if You Can't Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-fixing-outlook-issues-in-windows/"><u>Overcoming Obstacles: Fixing Outlook Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-app-glitch-x80131500/"><u>Overcoming Windows App Glitch X80131500</u></a></li>
<li><a href="https://discover-bits.techidaily.com/quick-and-simple-hard-drive-duplication-upgrade-from-hdd-to-ssd-using-the-patriot-bootable-cloner/"><u>Quick & Simple Hard Drive Duplication: Upgrade From HDD to SSD Using the Patriot Bootable Cloner</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-missing-alerts-a-guide-for-non-working-phone-link-on-pc/"><u>Restoring Missing Alerts: A Guide for Non-Working Phone Link on PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-no-sound-issue-with-easy-tips-for-the-astro-a50-audio-system/"><u>Solve No-Sound Issue with Easy Tips for the Astro A50 Audio System</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-nvidia-scanner-trouble-in-windows-environment/"><u>Solve Your Nvidia Scanner Trouble in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-broadcast-glitches-in-windows/"><u>Solving Steam Broadcast Glitches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stalled-opera-install-windows-fix-guide/"><u>Stalled Opera Install? Windows Fix Guide</u></a></li>
</ul></div>

