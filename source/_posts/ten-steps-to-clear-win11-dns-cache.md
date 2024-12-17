---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-12-12T19:17:12.159Z
updated: 2024-12-17T01:10:19.170Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-basic-gamers-guide-to-outstanding-video-editing-software-for-2024/"><u>[New] Basic Gamers' Guide to Outstanding Video Editing Software for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mastering-freefire-the-30-best-tag-strategies-to-increase-views/"><u>[Updated] Mastering FreeFire The 30 Best Tag Strategies to Increase Views</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-simply-screen-recording-apowersofts-cost-free-software-review-for-2024/"><u>[Updated] Simply Screen Recording Apowersoft's Cost-Free Software Review for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-nokia-c110-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compre-written-in-the-stars-mastering-your-laptops-touchscreen-precision/"><u>A Compre Written in the Stars: Mastering Your Laptop’s Touchscreen Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-proficient-with-windows-odbc-control-panel/"><u>Becoming Proficient with Windows' ODBC Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-performance-with-windows-11-power-options/"><u>Boost Performance with Windows 11 Power Options</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-software-generations-windows-7-key-for-11-boot/"><u>Bridging Software Generations: Windows 7 Key for 11 Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-y200e-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo Y200e 5GFRP Lock</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/snicker-studio-cybernetic-cackles/"><u>Snicker Studio Cybernetic Cackles</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamlining-sound-speeds-in-spotify-without-compromise/"><u>Streamlining Sound Speeds in Spotify Without Compromise</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-how-to-fix-the-notorious-leaf-bug-in-apex-legends/"><u>Troubleshooting Guide: How to Fix the Notorious 'Leaf' Bug in Apex Legends</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-palworld-overcoming-eos-account-login-problems/"><u>Troubleshooting Palworld: Overcoming EOS Account Login Problems</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-apple-iphone-11-pro-max-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and Apple iPhone 11 Pro Max</u></a></li>
</ul></div>

