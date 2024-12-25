---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-12-19T17:12:55.576Z
updated: 2024-12-25T19:11:40.913Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/new-cultivating-success-in-valheim-prime-seed-picks-for-2024/"><u>[New] Cultivating Success in Valheim Prime Seed Picks for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-crusader-kings-3-crashing-on-pc/"><u>[SOLVED] Crusader Kings 3 Crashing on PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-full-guide-mastery-of-adobe-cloud-services-with-alternatives-analysis/"><u>[Updated] Full Guide Mastery of Adobe Cloud Services with Alternatives Analysis</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-financial-frontier-youtubes-pay-structure-at-the-1m-mark/"><u>[Updated] In 2024, The Financial Frontier Youtube's Pay Structure at the 1M Mark</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unleashing-creativity-in-stories-adding-personalized-graphics/"><u>2024 Approved Unleashing Creativity in Stories Adding Personalized Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-components-of-windows-update-identification-and-repair-techniques/"><u>Critical Components of Windows Update – Identification and Repair Techniques</u></a></li>
<li><a href="https://buynow-help.techidaily.com/exploring-high-quality-video-capture-with-logitechs-premium-c920-pro-hd-webcam-a-thorough-overview/"><u>Exploring High-Quality Video Capture with Logitech's Premium C920 Pro HD Webcam - A Thorough Overview</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-efficiency-with-terminal-as-preferred-cli/"><u>Leverage Efficiency with Terminal as Preferred CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/maintain-disk-space-utilize-automatic-deletion-in-windows-11/"><u>Maintain Disk Space: Utilize Automatic Deletion in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mystery-non-edge-processes-in-task-manager/"><u>Mystery: Non-Edge Processes in Task Manager?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-for-swifter-loading-of-apps-from-microsoft-store/"><u>Navigating for Swifter Loading of Apps From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-stalled-grammarly-checkup-in-windows-810/"><u>Reviving Stalled Grammarly Checkup in Windows 8/10</u></a></li>
<li><a href="https://fox-within.techidaily.com/simple-passcode-protected-backups-made-simple-using-aomei-backupper/"><u>Simple Passcode-Protected Backups Made Simple Using AOMEI Backupper</u></a></li>
<li><a href="https://windows11.techidaily.com/the-journey-to-disabling-user-account-control-uac-in-windows-11/"><u>The Journey to Disabling User Account Control (UAC) in WIndows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-caching-explained-and-tips-for-clears/"><u>Windows ARP Caching Explained & Tips for Clears</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-enabling-linux-on-windows-rise/"><u>WSL Enabling: Linux on Windows Rise</u></a></li>
</ul></div>

