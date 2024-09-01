---
title: Ultimate Guide to Harnessing the Power of Goal Seek in Excel
date: 2024-08-31T22:04:51.530Z
updated: 2024-09-01T22:04:51.530Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Ultimate Guide to Harnessing the Power of Goal Seek in Excel

### Quick Links

* [What Is Goal Seek in Excel?](https://youtube-stream.techidaily.com/mastering-mobile-media-the-art-of-filming-with-a-smartphone-for-2024/)
* [Goal Seek Examples](https://techtrends.techidaily.com/sequential-screen-time-with-taylor-swift-movie-marathon-essentials/)

 Have you ever had a [financial goal](https://youtube-videos.techidaily.com/2024-approved-comprehensive-guide-your-shorts-hidden-thumbnails/) you sought but weren't exactly sure how to get there? Using Goal Seek in Microsoft Excel, you can determine what you need to accomplish your goal.

 Maybe you want to save a certain amount of money in the next few years but aren't sure how much you need to set aside each month. Or perhaps you want to take out a loan and know [how much you can afford](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) every month, but don't know what interest rate to look for.

 Goal Seek can help you with these types of calculations as well as others.

##  What Is Goal Seek in Excel?

 Goal Seek is part of the What-If Analysis group built into Excel. It works with values you insert and a [formula you enter](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) to calculate those values. This means that a formula is necessary to use Goal Seek.

Related: [5 iPhone Apps to Keep Track of Your Investments](https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/) 

 The tool is especially useful for the situations mentioned above such as savings, [investments](https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/), and loans, but can be used in other scenarios as well. Once you obtain the results from the Goal Seek tool, you can simply view them or pop them into your sheet.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
##  Goal Seek Examples

 If you're ready to give this nifty feature a try, let's look at some example uses.

###  Goal Seek for Sales

 For a simple way to get familiar with the tool, we'll start with a basic example. We want to determine how many units of our product we need to sell to reach our goal. So, we have the current Quantity, Unit Price, and Total Sales as shown below.

![Sales figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesFigures-ExcelGoalSeek.png) 

 The Total Sales in cell B3 is a formula that multiples the Quantity by the Unit Price: 

        `=B1*B2`
    
 .

 We want to find out how many units we must sell to reach our goal of $20,000 in total sales. For this, Goal Seek is ideal.

 Go to the Data tab, click the What-If Analysis drop-down arrow, and select "Goal Seek."

![Goal Seek in the What-If Analysis menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/DataGoalSeek-ExcelGoalSeek.png) 

 In the small Goal Seek box, insert the following:

**Set Cell**: Enter the cell reference containing the formula you want to change. Remember, changing the formula shows us the input we need to reach our goal.

**To Value**: Enter the result you want. For us, this is 20,000.

**By Changing Cell**: Enter the reference for cell you want to adjust. For us, this is B1 for the Quantity.

![Goal Seek for sales figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesSeek-ExcelGoalSeek.png) 

 When you finish, click "OK." The Goal Seek Status box shows a solution was found and you'll see a preview in your spreadsheet.

![Goal Seek results for sales figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SalesSeekResults-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, we now know that we must sell 800 units of our product to reach our $20,000 goal. Click "OK" to apply the change to your sheet or "Cancel" to simply close the Goal Seek Status window.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
###  Goal Seek for Loans

 Another good way to use Goal Seek in Excel is for help with loans. You may have the loan amount, term in months, and payment you can afford, but want to know what interest rate you should seek. Because the Goal Seek tool works off of formulas, you can leave the interest rate cell blank and allow Goal Seek to fill it.

Related: [How to Calculate a Loan Payment, Interest, or Term in Excel](https://article-tips.techidaily.com/2024-approved-deciphering-the-world-of-augmented-reality-stickers-googles-role/) 

 Here we have the Loan Amount, Term, and Payment fields filled in. (You can ignore the payment amount displayed for now since the formula still needs the interest rate.) We have the formula for the [PMT (Payment) function](https://article-tips.techidaily.com/2024-approved-deciphering-the-world-of-augmented-reality-stickers-googles-role/) in cell B4: 

        `=PMT(B3/12,B2,B1)`
    
 .

![Loan figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanFigures-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
 Select Data > What-If Analysis > Goal Seek and insert the following:

**Set Cell**: Enter the cell reference containing the formula you want to change. For us, this is B4.

**To Value**: Enter the result you want. For us, this is -800 because we can afford $800 monthly.

**By Changing Cell**: Enter the reference for cell you want to adjust. For us, this is B3 for the Interest Rate.

 Excel uses a negative number for the payment when using the PMT function.

![Goal Seek for loan figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanSeek-ExcelGoalSeek.png) 

 Click "OK" to see the results. It looks like we'll try for a 4.77% annual interest rate for our loan.

![Goal Seek results for loan figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/LoanResults-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
 Select "OK" to apply the change to your sheet or "Cancel" to close the box.

###  Goal Seek for Savings

 For one more example, you might have a savings goal you want to reach in a certain amount of time. We want to save $5,000 in 12 months, our [bank](https://www.reviewgeek.com/67538/here-are-the-best-alternatives-to-simples-online-banking-service/) offers 1.5% interest, and we need to know how much to deposit each month.

 Here we have the Interest Rate and Number of Payments filled in. The Payment is blank because Goal Seek will enter it and the Goal is at $0 because the formula still needs the payment amount. We have the formula for the [FV (Future Value) function](https://support.microsoft.com/en-us/office/fv-function-2eef9f44-a084-4c61-bdd8-4fe4bb1b71b3) in cell B4: 

        `=FV(B1/12,B2,B3)`
    
 .

![Savings figures in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsFigures-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Head back to Data > What-If Analysis > Goal Seek and insert the following:

**Set Cell**: Enter the cell reference containing the formula which is B4 in our example.

**To Value**: Enter the result you want. For our goal, this is 5000.

**By Changing Cell**: Enter the reference for cell you want to adjust which is B3 for the Payment.

![Goal Seek for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsSeek-ExcelGoalSeek.png) 

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click "OK" to view your results. We see that we need to save just over $413 per month for the next year to reach our $5,000 goal.

![Goal Seek results for savings figures](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/SavingsResults-ExcelGoalSeek.png) 

 Excel uses a negative number for the payment when using the FV function.

 Again, click "OK" to apply the change or "Cancel" to close the window.

 When you need help figuring out how to reach your financial goal, pop open the Goal Seek tool in Excel. For more, take a look at [how to use Excel's built-in stocks feature](https://screen-recording.techidaily.com/2024-approved-ultimate-guide-cost-effective-pc-screen-recording-apps/).

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
<li><a href="https://screen-video-capture.techidaily.com/new-download-and-utilize-the-full-power-of-ez-grabber-quickly/"><u>[New] Download and Utilize the Full Power of EZ Grabber Quickly</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastering-the-art-of-zoom-filters-for-premium-sessions/"><u>[New] Mastering the Art of Zoom Filters for Premium Sessions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-quick-and-secure-lecture-capture-methods-for-mac-users/"><u>[Updated] In 2024, Quick and Secure Lecture Capture Methods for Mac Users</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-average-earnings-per-view-whats-the-income-for-youtubers-per-ad-playback/"><u>2024 Approved  Average Earnings Per View  What's the Income for YouTubers per Ad Playback?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-internet-laughter-fabricator/"><u>2024 Approved  Internet Laughter Fabricator</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/4-ways-to-unlock-iphone-14-pro-max-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>4 Ways to Unlock iPhone 14 Pro Max to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/accessible-legal-tracks-for-gameplay-enjoyment-for-2024/"><u>Accessible Legal Tracks for Gameplay Enjoyment for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/conquer-document-creation-chatgpt-word-partnership-for-efficiency/"><u>Conquer Document Creation: ChatGPT-Word Partnership for Efficiency</u></a></li>
<li><a href="https://data-wizards.techidaily.com/decelerating-delayed-digital-footage/"><u>Decelerating Delayed Digital Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-remedying-non-boot-virtual-machines-on-wm11os/"><u>Expert Advice: Remedying Non-Boot Virtual Machines on WM11OS</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-auto-restarts-windows-11-troubleshooting/"><u>Halt Auto Restarts: Windows 11 Troubleshooting</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-motorola-razr-40-ultra-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Motorola Razr 40 Ultra Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-your-edge-faster-and-sleeker-win10-w11/"><u>How to Make Your Edge Faster & Sleeker (Win10, W11)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-realme-12-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Realme 12 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-13-mini-with-a-mask-on-drfone-by-drfone-ios/"><u>How to Unlock iPhone 13 mini with a Mask On | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-realme-narzo-n55-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Realme Narzo N55</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-xiaomi-13t-pro-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Xiaomi 13T Pro FRP?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-how-to-completely-remove-your-instagram-footprint-forever/"><u>In 2024, How to Completely Remove Your Instagram Footprint Forever</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-civi-3-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Xiaomi Civi 3 Phone Without Password?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Xiaomi Redmi 12 5G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-record-dual-track-screenshots-with-windows-11s-snipping-tool-max-156/"><u>Learn to Record Dual-Track Screenshots with Windows 11'S Snipping Tool (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-ntfs-compression-to-optimize-disk-storage/"><u>Leveraging NTFS Compression to Optimize Disk Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-window-tweaking-using-alomware-suite/"><u>Master the Art of Window Tweaking Using AlomWare Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-discovery-secrets-to-mac-address-on-windows-11/"><u>Mastering Network Discovery: Secrets to Mac Address on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-disabling-lock-screen-on-modern-windows-11/"><u>Methods: Disabling Lock Screen on Modern Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-text-entry-embedding-keyboard-triggers-into-context-menus/"><u>Optimize Text Entry: Embedding Keyboard Triggers Into Context Menus</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/optimized-writing-techniques-with-chatgpt-aide/"><u>Optimized Writing Techniques with ChatGPT Aide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-windows-environment-for-seamless-vbox-use/"><u>Optimizing Your Windows Environment for Seamless VBox Use</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-no-sound-device-error-in-windows-os/"><u>Rectifying No Sound Device Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-apple-calendar-sync-in-windows-11-environments/"><u>Seamless Apple Calendar Sync in Windows 11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-sync-resurrecting-unresponsive-windows-photoshop/"><u>Seamless System Sync: Resurrecting Unresponsive Windows Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/seven-key-benefits-of-continuing-with-your-oldie-but-goodie-windows-10/"><u>Seven Key Benefits of Continuing with Your Oldie but Goodie - Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-update-problem-error-0x8024800c/"><u>Solving Windows Update Problem: Error 0X8024800C</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-iphone-guide-creating-and-editing-languid-video-sequences/"><u>Step by Step iPhone Guide  Creating & Editing Languid Video Sequences</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-personalized-windows-11-lock-patterns/"><u>Step-by-Step Guide to Personalized Windows 11 Lock Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-blackwhite-monochrome-in-shop/"><u>Strategies for Addressing Black/White Monochrome in Shop</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-multitasking-experience-microsofts-new-ai-taskbar-helper-in-windows-11/"><u>Streamlined Multitasking: Experience Microsoft’s New AI Taskbar Helper in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-sounds-a-look-at-windows-11-mixer-usage/"><u>Streamlining Sounds: A Look at Windows 11 Mixer Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-setup-failures-a-windows-10-and-11-approach/"><u>Tackling Setup Failures: A Windows 10 & 11 Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-latency-problem-with-gpsvc/"><u>Tackling the Latency Problem with GPSVC</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-update-glitches-the-case-of-error-codes-0xc1900101/"><u>Tackling Update Glitches: The Case of Error Codes 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-larger-space-for-pin-listings-in-w11/"><u>Tips for a Larger Space for Pin Listings in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workflow-the-best-6-apps-for-to-do-list-management-on-win-11/"><u>Transform Your Workflow: The Best 6 Apps for To-Do List Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-overcoming-display-errors-in-win1011/"><u>Understanding and Overcoming Display Errors in Win10/11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-video-to-dvd-conversion-a-comprehensive-guide-for-windows-and-mac/"><u>Updated In 2024, Video to DVD Conversion A Comprehensive Guide for Windows and Mac</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/webcam-mastery-creating-videos-on-macbook-for-2024/"><u>Webcam Mastery  Creating Videos on MacBook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win-strategies-unlocking-your-gaming-directory/"><u>Win Strategies: Unlocking Your Gaming Directory</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-ready-embrace-google-chrome-now/"><u>Windows 11 Ready? Embrace Google Chrome Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-lockscreen-customization-switching-spotlight-on-and-off/"><u>Windows Lockscreen Customization: Switching Spotlight On and Off</u></a></li>
</ul></div>
