---
title: Reinstating Absent System Temperature Policy on Windows
date: 2024-09-29T18:51:05.521Z
updated: 2024-10-01T19:32:54.045Z
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
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-top-hidden-features-in-whatsapp-that-will-change-how-you-message/"><u>[New] Top Hidden Features in WhatsApp That Will Change How You Message</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-jotunheims-gambit-warriors-of-ragnarok-for-2024/"><u>[Updated] Jotunheim's Gambit Warriors of Ragnarok for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-gain-on-ig-unveiling-high-payoff-content-strategies/"><u>2024 Approved Gain on IG Unveiling High-Payoff Content Strategies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/an-easy-nft-creation-pathway-for-starters/"><u>An Easy NFT Creation Pathway For Starters</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-iphone-12-pro-max-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On iPhone 12 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-file-management-winpcs-most-valuable-fileshare-apps/"><u>Effortless File Management: WinPC's Most Valuable Fileshare Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-0x80072efd-a-windows-store-solution/"><u>Eliminating Error 0X80072EFD: A Windows Store Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-11-zoom-problem-code-1132/"><u>Eliminating Windows 11 Zoom Problem: Code 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hyper-v-a-quick-win11-guide/"><u>Enabling Hyper-V: A Quick Win11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-onedrive-for-direct-file-explorer-opens/"><u>Enabling OneDrive for Direct File Explorer Opens</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-and-streamlining-windows-based-discord-searches/"><u>Enhancing and Streamlining Windows-Based Discord Searches</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visual-quality-setting-sizes-on-win11/"><u>Enhancing Visual Quality: Setting Sizes on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-the-current-password-needed-issue-on-windows-11/"><u>Eradicate the ‘Current Password Needed’ Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-empty-directory-warning-code-0x80070091-in-windows-11-os/"><u>Eradicating Empty Directory Warning Code 0X80070091 in Windows 11 OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-iphone-6s-plus-password-here-are-the-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Forgot iPhone 6s Plus Password? – Here are the Best Solutions | Stellar</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-vivo-y77t-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ultimate-guide-to-choosing-the-perfect-screen-recording-tool-for-windows-11-ranked/"><u>Ultimate Guide to Choosing the Perfect Screen Recording Tool for Windows 11 - Ranked!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-6s-plus-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 6s Plus i Do? Get Answers here | Dr.fone</u></a></li>
</ul></div>

