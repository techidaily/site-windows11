---
title: Securely Resetting DNS on the Latest Windows Version
date: 2024-08-22T21:37:11.526Z
updated: 2024-08-23T21:37:11.526Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Resetting DNS on the Latest Windows Version
excerpt: This Article Describes Securely Resetting DNS on the Latest Windows Version
keywords: WinDNSReset,SecureReSet,UpdatedWinDNS,WindowsResetPro,SafeWindowsDNSSec,DNSSecurityWin,LatestDNSUpdate
thumbnail: https://thmb.techidaily.com/f09a424aa99c62f7b51db30e0d97dc33c8611de88afaf819d747680f631cd289.jpg
---

## Securely Resetting DNS on the Latest Windows Version

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
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


