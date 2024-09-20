---
title: Reinstating Absent System Temperature Policy on Windows
date: 2024-09-15T20:48:38.269Z
updated: 2024-09-20T19:21:25.714Z
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

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-real-time-game-capture-aps4-strategies-in-obs/"><u>[New] In 2024, Real-Time Game Capture APS4 Strategies in OBS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-reverse-the-ordinary-turning-images-upside-down/"><u>[New] In 2024, Reverse the Ordinary Turning Images Upside Down</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-close-up-cinematography-through-zooming/"><u>[New] Mastering Close-Up Cinematography Through Zooming</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-streaming-wars-the-top-10-platforms-ranked-and-compared/"><u>[New] Streaming Wars The Top 10 Platforms Ranked and Compared</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-transform-photos-create-masterpieces-with-leading-apps/"><u>[Updated] Transform Photos, Create Masterpieces with Leading Apps</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-best-webcams-for-youtube-livestreaming/"><u>In 2024, Best Webcams for YouTube Livestreaming</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-recording-powerhouse-tactics-for-windows-10-aficionados/"><u>In 2024, Recording Powerhouse Tactics for Windows 10 Aficionados</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-ways-to-collaborate-with-chatgpt-for-enhanced-vehicle-personalization-techniques/"><u>Innovative Ways to Collaborate With ChatGPT for Enhanced Vehicle Personalization Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-roi-with-effective-animated-social-media-campaigns-for-2024/"><u>Mastering ROI with Effective Animated Social Media Campaigns for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-settings-where-to-store-your-games-on-xbox/"><u>Optimal Settings: Where to Store Your Games on Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-memory-waste-with-microsoft-edges-webview2/"><u>Reducing Memory Waste with Microsoft Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-desktop-top-5-clock-saver-software/"><u>Revolutionize Desktop - Top 5 Clock Saver Software</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-at-your-fingertips-crafting-unique-shortcuts/"><u>Windows 11 at Your Fingertips: Crafting Unique Shortcuts</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

