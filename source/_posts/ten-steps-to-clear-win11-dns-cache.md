---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-09-14T17:54:17.892Z
updated: 2024-09-20T18:49:44.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ten Steps to Clear Win11 DNS Cache
excerpt: This Article Describes Ten Steps to Clear Win11 DNS Cache
keywords: Wi-Fi DNS Clearance,Windows 11 Cache Fix,Accelerate Win11 Speed,Domain Name Resolution,Network Performance Boost,Router Reconnection,Flush DNS Efficiency
thumbnail: https://thmb.techidaily.com/3826690fad2bdad4d7aa62bd8a31b6771b07791104399fd4c0b5ca08b831fc4c.jpg
---

## Ten Steps to Clear Win11 DNS Cache

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-echocam-grabber-for-video-calls/"><u>[New] 2024 Approved EchoCam Grabber for Video Calls</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-unveiling-obs-screen-recorder-functionality-deeply/"><u>[New] In 2024, Unveiling OBS Screen Recorder Functionality Deeply</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-ultimate-5-minute-timelapse-video-maker-for-2024/"><u>[New] Ultimate 5-Minute Timelapse Video Maker for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-expert-techniques-for-uploading-youtubes-on-dailymotion/"><u>2024 Approved Expert Techniques for Uploading YouTubes on Dailymotion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-insights-how-to-rectify-the-persistent-red-screen-problems-on-windows-pcs/"><u>Critical Insights: How To Rectify The Persistent Red Screen Problems On Windows PCs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/descompunere-gratuita-si-simpla-in-time-de-webm-video-in-format-mp4/"><u>Descompunere Gratuita Și Simplă In-Time De Webm Video În Format Mp4</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-build-successful-youtube-advertisements-for-free/"><u>In 2024, How to Build Successful YouTube Advertisements for Free?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powershell-clearing-blocked-files-in-windows/"><u>Mastering PowerShell: Clearing Blocked Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-mending-windows-update-failures-0x712/"><u>Mastery in Mending Windows Update Failures: 0X712</u></a></li>
<li><a href="https://windows11.techidaily.com/pricing-predicaments-what-youre-overlooking-with-inexpensive-windows-keys/"><u>Pricing Predicaments: What You're Overlooking with Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-camera-unresponsive-on-windows-11/"><u>Remedying Camera Unresponsive on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sync-or-not-addressing-windows-sluggish-internet/"><u>Sync or Not: Addressing Windows' Sluggish Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/the-controllers-cry-solutions-for-steams-ignorance-in-windows/"><u>The Controller's Cry: Solutions for Steam's Ignorance in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/what-caused-the-social-media-blackout-epidemic/"><u>What Caused the Social Media Blackout Epidemic?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-maintaining-a-valid-functional-temp-folder/"><u>Windows 11: Maintaining a Valid, Functional Temp Folder</u></a></li>
</ul></div>

