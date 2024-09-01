---
title: "Mastering Currency Exchange: A Step-by-Step Guide to Converting Money with Microsoft Excel"
date: 2024-08-31T22:03:21.335Z
updated: 2024-09-01T22:03:21.335Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c37c2fb062f462104689e721c0e87e0aafa96193ea307f1d985a6b0808b35c37.jpg
---

## Mastering Currency Exchange: A Step-by-Step Guide to Converting Money with Microsoft Excel

### Quick Links

* [Adding an External Data Source to Excel](https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-poco-m6-5g-drfone-by-drfone-virtual-android/)
* [Converting Currency in Microsoft Excel](https://youtube-sure.techidaily.com/for-effective-tripod-usage-in-video-blogging-for-2024/)

 Microsoft Excel doesn't include built-in tools to convert currency. However, you can use an external data source to provide up-to-date rates. A basic multiplication formula will then convert from one currency to another. Here's how you do it!

##  Adding an External Data Source to Excel

 An external data source is the best way to get up-to-date currency exchange rates. You can use this data to convert from one currency to another in Excel. The process is similar to [converting currency in Google Sheets](https://fox-blue.techidaily.com/2024-approved-close-up-clarity-mastering-the-art-of-intense-focus/).

Related: [How to Convert Currency in Google Sheets](https://fox-blue.techidaily.com/2024-approved-close-up-clarity-mastering-the-art-of-intense-focus/) 

 First, you need a suitable online data source (in the XML format) that you can import into your spreadsheet. [FloatRates](http://www.floatrates.com/feeds.html) has various XML feeds based around different currencies that you can use.

 After you find the one you want to use, open your Excel spreadsheet. In Excel 2019 or Office 365, click Data > Get Data > From File > From XML. In older versions of Excel, click Data > Get External Data > From Other Sources > From XML Data Import instead.

![Click &quot;Data,&quot; click &quot;Get Data,&quot; click &quot;From File,&quot; and then select &quot;From XML.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Add-XML-Data-Source.png) 

 For our example, we're using the [FloatRates USD data feed,](http://www.floatrates.com/daily/usd.xml) so we import that into Excel.

 In the "Import Data" window, paste the URL to your XML data feed in the "File Name" box, and then click "Import."

![Paste your XML data feed into the Import Data window, then press Import to import it into Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Import-Data-Window.png) 

 If you have Office 2019 or 365, you see a preview of how the data will be imported. If you're using FloatRates data, you have to convert it in the Excel Power Query Editor to use it.

 To do so, click "Transform Data."

![Click Transform Data to convert an XML data feed during the XML import wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-XML-Transform-Data.png) 

 The Excel Power Query Editor appears. Scroll to the "Item" column, and then double-click "Table" to load the up-to-date currency rates.

![In the Excel Power Query Editor, scroll to the Item column, then double-click the Table item](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-XML-Data-Select-Table.png) 

 The Power Query Editor preview updates and shows the FloatRates currency data. Click "Close and Load" in the top-left corner to add the data to your spreadsheet.

![Press Close and Load to add your XML data to your Excel spreadsheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Power-Query-Load-Data.png) 

 The data you import appears in a new worksheet, to which you can now refer when you need to convert currency.

 Most external data sources update hourly, but FloatRates only updates every 12 hours. If you want to update your data manually, click Data > Refresh All.

![Press Data > Refresh All to refresh your data sources manually](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Refresh-Data.png) 

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Converting Currency in Microsoft Excel

 You can use the up-to-date data you imported to convert currency figures with a simple multiplication formula.

 Click the worksheet with your imported currency rates. If you're using FloatRates data, look at the exchange rates under the "exchangeRate" column. Note the cell that contains the rate of the currency to which you want to convert.

 Using our FloatRates U.S. dollar data, we see that to convert from U.S. dollars to British pounds, we need to use the GBP exchange rate in cell I3.

![Currency exchange rates, imported from an external data source in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-GBP-Currency-Rate.png) 

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
 Return to your existing worksheet, and type the USD price from which you want to convert into a cell. In a second cell, use the formula 

        `=A2*Sheet2!$I$3`
    
 , and replace "A2" with the cell that contains your USD price.

 Replace the second part of the formula with an [absolute reference](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/) to the cell in the "exchangeRate" column on your imported data worksheet that contains the exchange rate to which you want to convert.

![Various currency conversion prices in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Currency-Conversion.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 In the example above, Column A lists U.S. dollars. Column B lists the converted currency rates from U.S. dollars to British pounds (1 USD to GBP is in cell B2).

 When you change the absolute cell reference and use alternative data sources (like the FloatRates GBP data source to convert from GBP to other currencies), you can convert from any currency to another.

 You can also use a manual rate instead of an external data source to convert currency rates. Just set the exchange rate manually in a cell (in our example, cell B2), and the price in another (cell A3).

![Manual currency conversion in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Manual-Currency-Conversion.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
 The same multiplication formula converts your currency. However, if you're not using an external data source, you'll have to update the rate manually to see the correct price.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-cutting-edge-mac-accessory-visionplussound-capturing/"><u>[New] Cutting-Edge Mac Accessory  Vision+Sound Capturing</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-enhancing-outdoor-vision-with-gopro-and-live-streaming-platforms-for-2024/"><u>[New] Enhancing Outdoor Vision with GoPro and Live Streaming Platforms for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-immersive-history-education-from-youtubes-best-10-vlogs/"><u>[New] Immersive History Education From YouTube's Best 10 Vlogs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-essential-guide-to-posting-vimeo-on-instagram-for-2024/"><u>[New] The Essential Guide to Posting Vimeo on Instagram for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-top-7-inexpensive-pc-screen-recorders-ranked-for-2024/"><u>[New] Top 7 Inexpensive PC Screen Recorders Ranked for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/outubes-best-font-choices-for-striking-thumbnails-for-2024/"><u>[New] YouTube's Best Font Choices for Striking Thumbnails for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-it-takes-two-fps-drops-on-pc/"><u>[SOLVED] It Takes Two FPS Drops on PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-best-screen-capture-apps-for-android-devices-reviewed/"><u>[Updated] Best Screen Capture Apps for Android Devices Reviewed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-customize-your-videos-appeal-youtube-thumbnail-tips-and-tricks-for-2024/"><u>[Updated] Customize Your Video's Appeal  YouTube Thumbnail Tips & Tricks for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-prime-shopping-destinations-customizable-presents-with-flair/"><u>2024 Approved  Prime Shopping Destinations  Customizable Presents with Flair</u></a></li>
<li><a href="https://buynow-info.techidaily.com/budget-friendly-and-sturdy-comprehensive-review-for-the-procase-macbook-pro-13-carrying-solution/"><u>Budget-Friendly and Sturdy: Comprehensive Review for the ProCase MacBook Pro 13 Carrying Solution</u></a></li>
<li><a href="https://extra-information.techidaily.com/classifications-of-unmanned-aircraft/"><u>Classifications of Unmanned Aircraft</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-troubleshoot-for-windows-11s-persistent-0xc190n0028-upgrade-hurdle-solutions-included/"><u>Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included!</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-windows-11s-software-distro-and-catroot2-restart/"><u>Essential Steps for Windows 11'S Software Distro and Catroot2 Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/filter-outuseless-windows-updates/"><u>Filter Outuseless Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-overscan-in-windows-to-fit-the-screen/"><u>How to Fix Overscan in Windows to Fit the Screen</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-yuva-3-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Yuva 3 Pro</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-easy-steps-to-modify-your-game-voice-in-free-fire-free-methods-available/"><u>In 2024, Easy Steps to Modify Your Game Voice in Free Fire (Free Methods Available)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elite-alternative-edits-skip-youtube-not-just-content/"><u>In 2024, Elite Alternative Edits  Skip Youtube, Not Just Content</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-revolutionize-your-video-content-with-free-intro-designers/"><u>In 2024, Revolutionize Your Video Content with Free Intro Designers</u></a></li>
<li><a href="https://driver-download.techidaily.com/lenovo-x1-carbon-effortless-driver-downloads-compatible-with-windows-11-and-7/"><u>Lenovo X1 Carbon: Effortless Driver Downloads Compatible with Windows 11 and 7</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-sticky-notifications-maximizing-win-11-potential/"><u>Mastery over Sticky Notifications: Maximizing Win 11 Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-8-key-avoidances-for-smooth-sailing/"><u>Navigating Windows 11: 8 Key Avoidances for Smooth Sailing</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-screen-capture-options-avoiding-windows-snipping-feature/"><u>Optimal Screen Capture Options: Avoiding Windows’ Snipping Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-security-modifying-context-menu-with-firewalls/"><u>Optimize Windows Security: Modifying Context Menu with Firewalls</u></a></li>
<li><a href="https://some-guidance.techidaily.com/optimizing-your-sites-performance-using-advanced-cookiebot-solutions/"><u>Optimizing Your Site's Performance Using Advanced Cookiebot Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-autominimize-a-step-by-step-process/"><u>Overcoming AutoMinimize: A Step-by-Step Process</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-fluctuating-playback-top-9-solutions-for-smooth-videos-on-pcs/"><u>Overcoming Fluctuating Playback: Top 9 Solutions for Smooth Videos on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-interrupts-with-fixing-breakpoints/"><u>Overcoming Windows Interrupts with Fixing Breakpoints</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-desktop-aesthetics-sticky-notes-on-w11w10/"><u>Perfecting Desktop Aesthetics: Sticky Notes on W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-remedying-post-windows-update-glitches/"><u>Quick Guide to Remedying Post-Windows Update Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-trend-of-failed-ea-server-connectivity/"><u>Reversing the Trend of Failed EA Server Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/screen-separation-strategies-wallpapers-per-monitor-windows-style/"><u>Screen Separation Strategies: Wallpapers per Monitor, Windows Style</u></a></li>
<li><a href="https://driver-download.techidaily.com/seamless-experience-get-the-latest-version-of-wacom-intuos-pro-driver-for-windows-11-users/"><u>Seamless Experience: Get the [Latest Version] of Wacom Intuos Pro Driver for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-redoing-tasks-on-windows-with-key-combinations/"><u>Speed Up Redoing Tasks on Windows with Key Combinations</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-sluggish-excel-troubleshooting-steps-for-windows-users/"><u>Speeding Up Sluggish Excel: Troubleshooting Steps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-blackout-while-playing-windows-games/"><u>Strategies to Avoid Blackout While Playing Windows Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/top-10-unforgettable-igtv-video-strategies-for-brand-success/"><u>Top 10 Unforgettable IGTV Video Strategies for Brand Success</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-to-workaround-folder-naming-limitations-on-windows-11/"><u>Top Solutions to Workaround Folder Naming Limitations on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-ranked-vr-gaming-experiences-on-pc-android-and-iphone-20162017/"><u>Top-Ranked VR Gaming Experiences on PC, Android & iPhone (2016/2017)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-epic-games-sign-in-problems-on-pc/"><u>Troubleshooting Epic Games Sign-In Problems on PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-webcam-selection-for-podcasting/"><u>Ultimate Webcam Selection for Podcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-printer-offline-on-windows-11/"><u>Understanding 'Printer Offline' On Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-off-screen-app-functionality-win-1011s-best-recovery-approaches-6-key-techniques/"><u>Unlock Off-Screen App Functionality: Win 10/11'S Best Recovery Approaches (6 Key Techniques)</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-mobile-video-editing-made-easy-top-10-free-green-screen-apps/"><u>Updated 2024 Approved Mobile Video Editing Made Easy Top 10 Free Green Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/validating-or-rejecting-window-login-attempts-with-precision/"><u>Validating or Rejecting Window Login Attempts with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/win-back-lost-apps-expert-methods-for-off-screen-window-restoration/"><u>Win Back Lost Apps: Expert Methods for Off-Screen Window Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-screen-management-guide-for-dual-displays/"><u>Windows 11 Screen Management Guide for Dual Displays</u></a></li>
</ul></div>
