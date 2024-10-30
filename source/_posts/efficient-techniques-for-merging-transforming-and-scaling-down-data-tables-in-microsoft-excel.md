---
title: Efficient Techniques for Merging, Transforming, and Scaling Down Data Tables in Microsoft Excel
date: 2024-10-29T17:08:53.468Z
updated: 2024-10-30T16:20:18.088Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Efficient Techniques for Merging, Transforming, and Scaling Down Data Tables in Microsoft Excel

### Quick Links

* [Combine Arrays](https://youtube-tips.techidaily.com/ed-premier-directory-of-economical-visual-content-providers-for-2024/)
* [Reshape Arrays](https://youtube-videos.techidaily.com/a-global-perspective-your-favorite-travel-youtubers-for-2024/)
* [Resize Arrays](https://instagram-videos.techidaily.com/new-2024-approved-step-by-step-designing-aplus-cover-photos-for-your-insta-highlights/)

 Working with arrays, or adjacent cell ranges, in Microsoft Excel can be challenging at times. If you'd like to combine, reshape, or resize an array, you can choose from a [collection of functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) that can cover many situations.

 These 11 functions are new to Excel as of August 2022\. They're rolling out to Excel users over time beginning with [Office Insiders](https://tech-haven.techidaily.com/rethinking-ai-why-claude-3-surpasses-chatgpt-in-4-ways/).

##  Combine Arrays

[Combining data](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/) in a spreadsheet can be difficult. With the VSTACK and HSTACK functions, you can stack arrays vertically and horizontally.

Related: [How to Combine Data From Spreadsheets in Microsoft Excel](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/) 

 The syntax for each function is the same as 

        `VSTACK(array1, array2,...)`
    
 and 

        `HSTACK(array1, array2,...)`
    
 with only one required array and others optional.

 To combine the arrays in cells B2 through F3 and H2 through L3 vertically, use this formula for the VSTACK function:

=VSTACK(B2:F3,H2:L3)

![VSTACK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/VSTACK-ExcelArrayFunctions.png) 

 To combine those same arrays horizontally instead, use this formula for the HSTACK function:

=HSTACK(B2:F3,H2:L3)

![HSTACK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/HSTACK-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Reshape Arrays

 If it's not combining arrays that you want to do but reshaping them instead, there are four [functions you can use](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/).

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

###  Convert an Array to a Row or Column

 First, the TOROW and TOCOL functions let you shape the array as a row or a column. The syntax for each is `TOROW(array, ignore, by_column)` and `TOCOL(array, ignore, by_column)`.

* **Ignore**: To ignore certain types of data, enter 1 for blanks, 2 for errors, or 3 for blanks and errors. The default is 0 to ignore no values.
* **By\_column**: Use this argument to scan the array by column using TRUE. If no argument is included, FALSE is the default, which scans the array by row. This determines how the values are ordered.

 To convert the array B2 through F3 to a row, use this formula with the TOROW function:

=TOROW(B2:F3)

![TOROW function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TOROW-ExcelArrayFunctions.png) 

 To convert that same array to a column instead, use the TOCOL function with this formula:

=TOCOL(B2:F3)

![TOCOL function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TOCOL-ExcelArrayFunctions.png) 

###  Convert a Row or Column to an Array

 To do the opposite of the above and convert a row or column to an array, you can use WRAPROWS and WRAPCOLS. The syntax for each is `WRAPROWS(reference, wrap_count, pad)` and `WRAPCOLS(reference, wrap_count, pad)` with the `reference` being a group of cells.

* **Wrap\_count**: The number of values for each row or column.
* **Pad**: The value to display for the pad (empty cell).

 To convert the cells B2 through K2 to a two-dimensional array by wrapping rows, use the WRAPROWS function. With this formula, the cells are wrapped using three values per row with "empty" as the `pad`.

=WRAPROWS(B2:K2,3,"empty")

![WRAPROWS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/WRAPROWS-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To convert the same cells into a two-dimensional array by wrapping columns, use the WRAPCOLS function. With this formula, the cells are wrapped using three values per column with "empty" as the `pad`.

=WRAPCOLS(B2:K2,3,"empty")

![WRAPCOLS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/WRAPCOLS-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Resize Arrays

 Maybe you want to adjust the size of an array by adding some data or dropping unnecessary cells. There are five [functions to help](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) you do this depending on the result you want.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

###  Take or Drop Rows or Columns

 With the TAKE function, you keep the number of rows or columns you specify. With the DROP function, you do the opposite and remove the number of rows or columns you specify. You'll use positive numbers to take or drop from the start of the array and negative numbers to take or drop from the end.

 The syntax for each is `TAKE(array, rows, columns)` and `DROP(array, rows, columns)` where you need at least one of the second two arguments; `rows` or `columns`.

 To keep the first two rows in the array B2 through F5, use TAKE with the `rows` argument. Here's the formula:

=TAKE(B2:F5,2)

![TAKE function for rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TAKErows-ExcelArrayFunctions.png) 

 To keep the first two columns in that same array, use the `columns` argument instead:

=TAKE(B2:F5,,2)

![TAKE function for columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TAKEcolumns-ExcelArrayFunctions.png) 

 To remove the first two rows in the array B2 through F5, use DROP with the `rows` argument and this formula:

=DROP(B2:F5,2)

![DROP function for rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/DROProws-ExcelArrayFunctions.png) 

 To remove the first two columns in that same array, use the `columns` argument instead and this formula:

=DROP(B2:F5,,2)

![DROP function for columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/DROPcolumns-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Keep a Certain Number of Rows or Columns

 To select the exact row and column numbers you want to keep from an array, you'd use the CHOOSEROWS and CHOOSECOLS functions.

 The syntax for each is `CHOOSEROWS(array, row_num1, row_num2,...)` and `CHOOSECOLS(array, column_num1, column_num2,...)` where the first two arguments are required. You can add more row and column numbers if you like.

 To return rows 2 and 4 from the array B2 through F5, you'd use the CHOOSEROWS function and this formula:

=CHOOSEROWS(B2:F5,2,4)

![CHOOSEROWS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CHOOSEROWS-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To return columns 3 and 5 from the same array, you'd use the CHOOSECOLS function with this formula:

=CHOOSECOLS(B2:F5,3,5)

![CHOOSECOLS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CHOOSECOLS-ExcelArrayFunctions.png) 

 Remember to use the row or column numbers for the array, _not_ for the sheet.

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Expand an Array to Specific Dimensions

 Maybe you plan to add more data to your array, so you want to make it a specific size to [add a border](https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-on-apple-iphone-14-by-drfone-ios/) or use [conditional formatting](https://fox-blue.techidaily.com/updated-2024-approved-ultimate-list-selecting-excellent-webcams-for-podcasts/). With the EXPAND function, you enter the number of rows and columns your array should cover.

Related: [How To Add and Change Cell Borders In Excel](https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-on-apple-iphone-14-by-drfone-ios/) 

 The syntax for the function is `EXPAND(array, rows, columns, pad)` where a missing `rows` or `columns` argument means those will not expand. Optionally, you can include the `pad` value for the empty cells.

 To expand the array B2 through F5 to cover 10 rows and 10 columns, you'd use this formula:

=EXPAND(B2:F5,10,10)

![EXPAND function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/EXPAND-ExcelArrayFunctions.png) 

 To expand that same array to the same dimensions and include the `pad` "empty," use this formula:

=EXPAND(B2:F5,10,10,"empty")

![EXPAND function with a pad value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/EXPANDpad-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Although the `pad` argument is optional, you may prefer it over [seeing an error](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) as shown above.

 These 11 functions give you more control than ever over your arrays in Microsoft Excel. Give them a try and see if they accomplish what you need.

Related: [How to Fix Common Formula Errors in Microsoft Excel](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/)

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-top-5-high-quality-online-meeting-capture-devices/"><u>[New] In 2024, Top 5 High-Quality Online Meeting Capture Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-ultimate-list-5-premium-live-stream-recorders/"><u>[New] The Ultimate List 5 Premium Live Stream Recorders</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-expert-advice-for-xbox-one-zooming-pros/"><u>[Updated] In 2024, Expert Advice for Xbox One Zooming Pros</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-optimizing-youtube-closures-a-comprehensive-guide-to-crafting-effective-end-screens-and-cards/"><u>[Updated] Optimizing YouTube Closures A Comprehensive Guide to Crafting Effective End Screens and Cards</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-no-downloads-needed-discover-our-list-of-5-best-online-gif-to-video-services/"><u>2024 Approved No Downloads Needed? Discover Our List of 5 Best Online GIF-to-Video Services</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-nokia-c22-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-driven-storytelling-in-video-games/"><u>AI-Driven Storytelling in Video Games</u></a></li>
<li><a href="https://windows11.techidaily.com/mapmyride-reviewed-a-detailed-breakdown/"><u>MapMyRide Reviewed: A Detailed Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-awaits-conquering-windows-11-with-group-software-updates-via-winstall/"><u>Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-shortcut-placement-in-win11-menu-bar/"><u>Maximizing Efficiency: Shortcut Placement in Win11 Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-setup-integrating-latest-network-drivers-from-intel-in-fedora/"><u>Precision Setup: Integrating Latest Network Drivers From Intel in Fedora</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/utionize-content-consumption-uncover-the-best-6-free-and-online-platforms-for-short-film-downloads-for-2024/"><u>Revolutionize Content Consumption Uncover the Best 6 Free & Online Platforms for Short Film Downloads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-audio-transmission-phones-and-windows-integration/"><u>Seamless Audio Transmission: Phones & Windows Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-windows-11-task-manager-interface-elements/"><u>Tailor Windows 11 Task Manager Interface Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/title-tweaking-desktop-icons-separation-in-winxiplus10/"><u>Title: Tweaking Desktop Icons' Separation in WinXI+10</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-vivo-x90s-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Vivo X90S.</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-to-alleviate-server-stumble-on-windows-store/"><u>Unveiling Steps to Alleviate Server Stumble on Windows Store</u></a></li>
</ul></div>

