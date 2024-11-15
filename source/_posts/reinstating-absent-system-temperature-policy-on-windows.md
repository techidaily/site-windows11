---
title: Reinstating Absent System Temperature Policy on Windows
date: 2024-11-10T17:17:03.215Z
updated: 2024-11-15T16:19:37.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Absent System Temperature Policy on Windows
excerpt: This Article Describes Reinstating Absent System Temperature Policy on Windows
keywords: Windows Temp Policy,Reinstate Temp Rule,WIN_TempPolicy,System Temp Update,Restore WIN Temp,Absent Sys Temp,Temp Rule Enforcement
thumbnail: https://thmb.techidaily.com/46162ff1d50cb6f1b35f044048a0b2464ebecd738e59505ca40bf7c4a2c48673.png
---

## Reinstating Absent System Temperature Policy on Windows

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.

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
<li><a href="https://youtube-videos.techidaily.com/new-the-best-hashtags-for-youtube-gaming-videos/"><u>[New] The Best Hashtags for YouTube Gaming Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-express-originality-craft-professional-logos-from-template-designs-free/"><u>2024 Approved Express Originality Craft Professional Logos From Template Designs (Free)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/convert-your-swf-files-into-professional-quality-mp4-videos-for-free-with-ease-moveavee/"><u>Convert Your SWF Files Into Professional-Quality MP4 Videos for Free with Ease - Moveavee</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-trojan-terror-defending-your-windows-against-wacatacbml/"><u>Exposing the Trojan Terror: Defending Your Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-pcs-missing-piece-how-to-restore-bluetooth-on-windows-11/"><u>Fix Your PC's Missing Piece: How to Restore Bluetooth on Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-90-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Honor 90? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-locked-xiaomi-civi-3-disney-100th-anniversary-edition-phone-by-drfone-android/"><u>How to Reset a Locked Xiaomi Civi 3 Disney 100th Anniversary Edition Phone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-the-hack-no-more-pins-for-windows-11-projecting/"><u>Learn the Hack: No More PINs for WIndows 11 Projecting</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-outlook-preview-in-windows-11-pro/"><u>Mastering Outlook Preview in Windows 11 Pro</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/maximizing-your-android-game-adventure-with-kinemaster-review-for-2024/"><u>Maximizing Your Android Game Adventure with KineMaster Review for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/optimal-chatgpt-command-strategies-unveiled/"><u>Optimal ChatGPT Command Strategies Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-using-hotkeys-to-simplify-windows-changes/"><u>Pro Tips: Using Hotkeys to Simplify Windows Changes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/real-time-view-count-detectors-for-2024/"><u>Real-Time View Count Detectors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rush-your-print-jobs-how-to-spur-a-slow-windows-printer/"><u>Rush Your Print Jobs: How to Spur a Slow Windows Printer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-recover-lost-dbghelpdll-and-solve-registry-issues-on-windows/"><u>Steps to Recover Lost dBghelp.dll and Solve Registry Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-failing-windows-alt-codes/"><u>Strategies to Address Failing Windows ALT Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-why-windows-11-upgrade-remains-unpopular/"><u>Understanding Why Windows 11 Upgrade Remains Unpopular</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-mishap-resolution-fix-for-error-code-0x0000011b/"><u>Win11 Mishap Resolution: Fix for Error Code 0X0000011B</u></a></li>
</ul></div>

