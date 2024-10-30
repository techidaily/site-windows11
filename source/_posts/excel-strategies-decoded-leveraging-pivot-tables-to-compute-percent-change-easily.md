---
title: "Excel Strategies Decoded: Leveraging Pivot Tables to Compute Percent Change Easily"
date: 2024-10-26T16:50:33.538Z
updated: 2024-10-30T17:09:49.035Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Formatting the Range as a Table

 If your data range is not already formatted as a table, we'd encourage you to do so. Data stored in tables have multiple benefits over data in cell ranges of a worksheet, especially when using PivotTables ([read more about the benefits of using tables](https://www.linkedin.com/pulse/9-reasons-you-need-using-excel-tables-alan-murray/)).

 To format a range as a table, select the range of cells and click Insert > Table.

![Create Table dialog to specify the range of cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-table.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check that the range is correct, that you do have headers in the first row of that range, and then click "OK."

 The range is now formatted as a table. Naming the table will make it easier to refer to in the future when creating PivotTables, charts, and formulas.

 Click the "Design" tab under Table Tools, and enter a name in the box provided at the start of the Ribbon. This table has been named "Sales."

![Name the Table in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/name-the-table.png) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also change the style of the table here if you want.

##  Create a PivotTable to Display Percentage Change

 Now let's get on with creating the PivotTable. From within the new table, click Insert > PivotTable.

 The Create PivotTable window appears. It will have automatically detected your table. But you could select the table or range you want to use for the PivotTable at this point.

![The Create PivotTable window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-pivottable-1.png) 

###  Group the Dates into Months

 We will then drag the date field that we want to group by into the rows area of the PivotTable. In this example, the field is named Order Date.

 From Excel 2016 on, date values are automatically grouped into years, quarters and months.

 If your version of Excel does not do this, or you simply want to change the grouping, right-click a cell containing a date value and then select the "Group" command.

![Group dates in a PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dates.png) 

 Select the groups you want to use. In this example, only Years and Months are selected.

![Specifying Years and Months in the Group dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dialog.png) 

 The year and month are now fields which we can use for analysis. The months are still named as Order Date.

![Years and Order Date fields in Rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/years-and-months.png) 

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
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Create the Percentage Change Column

 Right-click on a value in the second column, point to "Show Values," and then click the "% Difference from" option.

![Show values as a percentage difference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/show-values-as.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select "(Previous)" as the Base Item. This means that the current month value is always compared to the previous months (Order Date field) value.

![Select Previous as the base item to compare to](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/previous.png) 

 The PivotTable now shows both the values and the percentage change.

![Show values and percentage change](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/values-and-percentage-change.png) 

 Click in the cell containing Row Labels and type "Month" as the header for that column. Then click in the header cell for the second values column and type "Variance".

![Rename the headers of the PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/rename-headers.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Add Some Variance Arrows

 To really polish off this PivotTable, we would like to visualize the percentage change better by adding some green and red arrows.

 These will provide us with a lovely way of seeing whether a change has been positive or negative.

 Click on any one of the values in the second column and then click Home > Conditional Formatting > New Rule. In the Edit Formatting Rule window that opens, take the following steps:

1. Select the "All cells showing "Variance" values for Order Date" option.
2. Select "Icon Sets" from the Format Style list.
3. Select the red, amber and green triangles from the Icon Style list.
4. In the Type column, change the list option to say "Number" instead of Percentage. This will change the Value column to 0's. Exactly what we want.

![Applying variance icons with Conditional Formatting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/formatting-variance-icons.png) 

 Click "OK" and the Conditional Formatting is applied to the PivotTable.

![The completed variance PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/completed-variance-table.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-law-of-lyrics-on-instagram-platforms/"><u>[New] 2024 Approved The Law of Lyrics on Instagram Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-step-by-step-breakdown-hassle-free-ios-device-recordings/"><u>[New] Step-by-Step Breakdown Hassle-Free iOS Device Recordings</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-webcam-and-monitor-recording-how-to-combine-for-2024/"><u>[New] Webcam & Monitor Recording How to Combine for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-why-cant-i-see-video-on-sony-a6400/"><u>[New] Why Can’t I See Video on Sony A6400?</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-best-graphics-cards-for-4k-video-editing-and-rendering-for-2024/"><u>[Updated] Best Graphics Cards for 4K Video Editing and Rendering for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comprehensive-winxvideo-ai-walkthrough-upgrading-and-manipulating-videos-with-ease/"><u>Comprehensive Winxvideo AI Walkthrough: Upgrading and Manipulating Videos with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/guidance-for-overcoming-indexer-service-start-up-issues/"><u>Guidance for Overcoming Indexer Service Start-Up Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-itel-a05s-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Itel A05s Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-xiaomi-redmi-k70-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Xiaomi Redmi K70 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-menu-management-quick-fixes/"><u>Mastering Windows Menu Management: Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-components-settings-in-windows-11/"><u>Navigating Components Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-forgotten-island-xbox-glitch-in-win11/"><u>Navigating Through the Forgotten Island Xbox Glitch in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-winrars-file-sums-a-guide-with-6-fixes/"><u>Reconciling WinRAR's File Sums: A Guide with 6 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-your-pc-with-system-restore-step-by-step/"><u>Reverting Your PC with System Restore: Step-by-Step</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/rooting-in-cities-cultivating-urban-biodiversity/"><u>Rooting in Cities Cultivating Urban Biodiversity</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-ai-integration-in-the-web-sphere/"><u>Seamless AI Integration in the Web Sphere</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-fixing-apple-device-image-io-problems-in-w11/"><u>Strategies for Fixing Apple Device Image I/O Problems in W11</u></a></li>
</ul></div>

