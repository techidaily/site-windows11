---
title: "Excel Strategies Decoded: Leveraging Pivot Tables to Compute Percent Change Easily"
date: 2024-08-31T22:03:12.988Z
updated: 2024-09-01T22:03:12.988Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/64ebd0c332825585bbf71b718defd7fd5f0995165386514c60536516e7883669.jpg
---

## Excel Strategies Decoded: Leveraging Pivot Tables to Compute Percent Change Easily

### Quick Links

* [Formatting the Range as a Table](https://win-answers.techidaily.com/how-to-get-rockstar-online-gaming-platforms-working-again-for-windows-users/)
* [Create a PivotTable to Display Percentage Change](https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-a15-5g-drfone-by-drfone-reset-android-reset-android/)

 Pivot Tables are an amazing built-in reporting tool in Excel. While typically used to summarize data with totals, you can also use them to calculate the percentage of change between values. Even better: It is simple to do.

 You could use this technique to do all kinds of things---pretty much anywhere you'd like to see how one value compares to another. In this article, we're going to use the straightforward example of calculating and displaying the percent by which the total sales value changes month by month.

 Here's the sheet we're going to use.

![Two years of sales data for a PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/sample-data-1.png) 

 It's a pretty typical example of a sales sheet that shows the order date, customer name, sales rep, total sales value, and a few other things.

 To do all this, we're first going to format our range of values as a table in Excel and we're then going to create a Pivot Table to make and display our percentage change calculations.

##  Formatting the Range as a Table

 If your data range is not already formatted as a table, we'd encourage you to do so. Data stored in tables have multiple benefits over data in cell ranges of a worksheet, especially when using PivotTables ([read more about the benefits of using tables](https://www.linkedin.com/pulse/9-reasons-you-need-using-excel-tables-alan-murray/)).

 To format a range as a table, select the range of cells and click Insert > Table.

![Create Table dialog to specify the range of cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-table.png) 

 Check that the range is correct, that you do have headers in the first row of that range, and then click "OK."

 The range is now formatted as a table. Naming the table will make it easier to refer to in the future when creating PivotTables, charts, and formulas.

 Click the "Design" tab under Table Tools, and enter a name in the box provided at the start of the Ribbon. This table has been named "Sales."

![Name the Table in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/name-the-table.png) 

 You can also change the style of the table here if you want.

##  Create a PivotTable to Display Percentage Change

 Now let's get on with creating the PivotTable. From within the new table, click Insert > PivotTable.

 The Create PivotTable window appears. It will have automatically detected your table. But you could select the table or range you want to use for the PivotTable at this point.

![The Create PivotTable window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-pivottable-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
###  Group the Dates into Months

 We will then drag the date field that we want to group by into the rows area of the PivotTable. In this example, the field is named Order Date.

 From Excel 2016 on, date values are automatically grouped into years, quarters and months.

 If your version of Excel does not do this, or you simply want to change the grouping, right-click a cell containing a date value and then select the "Group" command.

![Group dates in a PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dates.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 Select the groups you want to use. In this example, only Years and Months are selected.

![Specifying Years and Months in the Group dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dialog.png) 

 The year and month are now fields which we can use for analysis. The months are still named as Order Date.

![Years and Order Date fields in Rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/years-and-months.png) 

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Add the Value Fields to the PivotTable

 Move the Year field from Rows and into the Filter area. This enables the user to filter the PivotTable for a year, rather than clutter the PivotTable with too much information.

 Drag the field containing the values (Total sales Value in this example) you want to calculate and present change into the Values area **twice**.

 It might not look like much yet. But that will change very soon.

![Sales value field added twice to the PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/values-added-twice.png) 

 Both value fields will have defaulted to sum and currently have no formatting.

 The values in the first column we would like to keep as totals. They do however require formatting.

 Right-click on a number in the first column and select "Number Formatting" from the shortcut menu.

 Choose the "Accounting" format with 0 decimals from the Format Cells dialog.

 The PivotTable now looks like this:

![Formatting the first column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/pivottable-with-formatting.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
###  Create the Percentage Change Column

 Right-click on a value in the second column, point to "Show Values," and then click the "% Difference from" option.

![Show values as a percentage difference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/show-values-as.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 Select "(Previous)" as the Base Item. This means that the current month value is always compared to the previous months (Order Date field) value.

![Select Previous as the base item to compare to](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/previous.png) 

 The PivotTable now shows both the values and the percentage change.

![Show values and percentage change](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/values-and-percentage-change.png) 

 Click in the cell containing Row Labels and type "Month" as the header for that column. Then click in the header cell for the second values column and type "Variance".

![Rename the headers of the PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/rename-headers.png) 

###  Add Some Variance Arrows

 To really polish off this PivotTable, we would like to visualize the percentage change better by adding some green and red arrows.

 These will provide us with a lovely way of seeing whether a change has been positive or negative.

 Click on any one of the values in the second column and then click Home > Conditional Formatting > New Rule. In the Edit Formatting Rule window that opens, take the following steps:

1. Select the "All cells showing "Variance" values for Order Date" option.
2. Select "Icon Sets" from the Format Style list.
3. Select the red, amber and green triangles from the Icon Style list.
4. In the Type column, change the list option to say "Number" instead of Percentage. This will change the Value column to 0's. Exactly what we want.

![Applying variance icons with Conditional Formatting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/formatting-variance-icons.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 Click "OK" and the Conditional Formatting is applied to the PivotTable.

![The completed variance PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/completed-variance-table.png) 

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 PivotTables are an incredible tool and one of the simplest ways to display the percentage change over time for values.

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
<li><a href="https://video-capture.techidaily.com/new-discover-top-screen-capture-apps-for-windowsmacos/"><u>[New] Discover Top Screen Capture Apps for Windows/macOS</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-is-cash-involved-with-criticism-displays/"><u>[New] Is Cash Involved with Criticism Displays?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-rhythmic-reels-making-instagram-memories-to-the-beat/"><u>[New] Rhythmic Reels  Making Instagram Memories to the Beat</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-mac-audio-sync-for-screen-captures/"><u>[Updated] In 2024, Mac Audio Sync for Screen Captures</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-skybound-streaming-engaging-your-audience-on-facebook/"><u>[Updated] In 2024, Skybound Streaming  Engaging Your Audience on Facebook</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-simplified-tech-livestreaming-of-facebook-using-obs-studio/"><u>[Updated] Simplified Tech Livestreaming of Facebook Using OBS Studio</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-premier-imagery-unboxing-analysis/"><u>2024 Approved  Premier Imagery Unboxing Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-restful-nights-with-the-ihome-zenergy-bedside-sleep-enhancer-comprehensive-review/"><u>Discover Restful Nights with the IHome Zenergy Bedside Sleep Enhancer – Comprehensive Review</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-set-up-your-windows-11-home/"><u>Explore and Set Up Your Windows 11 Home</u></a></li>
<li><a href="https://win-able.techidaily.com/fortnite-freeze-no-more-essential-tips-to-keep-your-game-running-smoothly-in-2einite-pc-fixes-of-2024/"><u>Fortnite Freeze No More: Essential Tips to Keep Your Game Running Smoothly in 2Einite - PC Fixes of 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/gift-ideas-for-a-christmasy-windows-11-experience/"><u>Gift Ideas for a Christmasy Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-revealing-your-pcs-background-image-storage/"><u>Guide to Revealing Your PC’s Background Image Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-windows-error-0x0000004e-woes/"><u>Guiding Users Through Windows' Error 0X0000004E Woes</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-on-your-iphone-6-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card on Your iPhone 6 Apple ID and Apple Pay</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-apple-iphone-15-pro-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on Apple iPhone 15 Pro With or Without Password</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-ipad-or-apple-iphone-se-stuck-on-activation-lock-by-drfone-ios/"><u>How to Fix iPad or Apple iPhone SE Stuck On Activation Lock?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-play-7t-by-fonelab-android-recover-video/"><u>How to recover old videos from your Play 7T</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-missing-router-control-center/"><u>How to Remedy Missing Router Control Center</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-photo-errors-in-windows-devices/"><u>How to Tackle Photo Errors in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-your-powertoys-settings-to-a-new-pc/"><u>How to Transfer Your PowerToys Settings to a New PC</u></a></li>
<li><a href="https://windows11.techidaily.com/ignore-non-essential-feedback-alerts-suggestions-on-windows/"><u>Ignore Non-Essential Feedback Alerts, Suggestions on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-poco-m6-pro-5g-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Poco M6 Pro 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/make-the-most-of-older-os-a-guide-beyond-windows-11/"><u>Make the Most of Older OS: A Guide Beyond Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-facebook-live-sharing-your-desktop-display/"><u>Mastering Facebook Live  Sharing Your Desktop Display</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-webcam-fixes-error-a00f4289/"><u>Mastering Windows 11 Webcam Fixes - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-taskbar-icon-separation-in-win-11/"><u>Mastery Over Taskbar Icon Separation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-sign-in-woes-heres-how-to-fix-it/"><u>Microsoft Store Sign-In Woes? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/modernize-windows-shift-to-enhanced-tiled-workspace/"><u>Modernize Windows: Shift to Enhanced Tiled Workspace</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-cant-watch-mlb-matches-get-free-mlb-streaming-options-now/"><u>New Cant Watch MLB Matches? Get Free MLB Streaming Options Now</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-steps-to-overcome-0x8004def5-onedrive-error-in-win11/"><u>Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-snip-tool-text-expertly-on-windows-11/"><u>Perfect Your Snip Tool Text Expertly on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-cpu-peaks-with-the-help-of-windows-rm-insights/"><u>Reduce CPU Peaks with the Help of Windows RM Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-11-display-dilemma-with-this-guide-to-fix-hdmi-tv-recognition/"><u>Resolve Your Windows 11 Display Dilemma with This Guide to Fix HDMI TV Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-internet-connectivity-issues-in-windows-11/"><u>Resolving Internet Connectivity Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-with-easy-steps-surface-pcs-version-enhancement-guide/"><u>Smooth Transition with Easy Steps: Surface PCs' Version Enhancement Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-xboxs-dead-end-road-error-on-modern-os/"><u>Steering Clear of Xbox's Dead-End Road Error on Modern OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-revive-non-launching-obs-on-windows/"><u>Steps to Revive Non-Launching OBS on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correctly-handle-windows-update-failure-error-0x80070003/"><u>Strategies to Correctly Handle Windows Update Failure (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-memory-monster-edge-webview2-troubleshooting/"><u>Taming the Memory Monster: Edge WebView2 Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-notification-blockade-from-phone-link/"><u>Unblocking Windows Notification Blockade From Phone Link</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-top-digital-scrapbooking-tools-for-photos-and-videos/"><u>Updated In 2024, Top Digital Scrapbooking Tools for Photos and Videos</u></a></li>
</ul></div>
