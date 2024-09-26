---
title: Guide on Isolating Month and Year Values From Date Entries in MS Excel Efficiently
date: 2024-08-31T22:03:17.763Z
updated: 2024-09-01T22:03:17.763Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/calendar-pins-office.jpg
---

## Guide on Isolating Month and Year Values From Date Entries in MS Excel Efficiently

### Quick Links

* [Get the Month or Year With Date Functions](https://youtube-help.techidaily.com/2024-approved-global-gross-earnings-of-youtube-luminaries/)
* [Get the Month or Year With the TEXT Function](https://extra-tips.techidaily.com/new-blending-binaries-digital-photographic-techniques/)

 Dates in Microsoft Excel are useful for tracking finances, orders, and sales. So, there may come a time when you want to pull a month or year out of a date entry. [Functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) make this an easy task.

 There are a couple of ways to get a month from a [date in Excel](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/), depending on if you want to display the result as a number, word, or abbreviation. And luckily, you can use these same methods to get the year from your date entry.

##  Get the Month or Year With Date Functions

 If you want to get the numeric value for a month such as 10 for October, 11 for November, and so on, the MONTH function gets the job done quickly. For years, you can simply use the [YEAR function](https://tech-revival.techidaily.com/integrate-bing-ai-into-your-android-phone-tips-and-tricks-for-seamless-communication/) and a reference.

 The syntax for each function is the same: 

        `MONTH(reference)`
    
 and 

        `YEAR(reference)`
    
 where you refer to the cell containing the date.

 You can use the following formulas to get the month and then the year from the date in cell A2:

=MONTH(A2)

=YEAR(A2)

 You'll then see the result in the cell containing the formula.

![YEAR function to obtain the year from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullYear-ExcelMonthYearFromDate.png) 

 Remember, the month is formatted as its numeric value.

![MONTH function to obtain the month from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/MonthNumber-ExcelMonthYearFromDate.png) 

 If you have a list of dates where you want to grab the month and/or year for each entry, use the fill handle to drag the formula(s) down to the remaining cells.

![Copy formula to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyFullFormulas-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Get the Month or Year With the TEXT Function

 Maybe you prefer to see the name of the month or an abbreviation rather than the number. You can do this for the month using the [TEXT function](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/). You can also get the two-digit number for the year with this method.

Related: [How to Find the Day of the Week From a Date in Microsoft Excel](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) 

 The syntax for the function is `TEXT(value, format_code)` where you'll need both arguments to display the month. The `value` is the cell containing the date and the `format_code` is how you want to display the result.

 Here, we'll get the month for the date in cell A2 as a full word using the letter M for month as the `format_code`:

=TEXT(A2,"mmmm")

 Note, you need at least four M's within quotation marks to get the full month name. The number of letters in the month's name does not correspond to the number of M's in the argument; just enter at least four of them.

![Full month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullMonth-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To get the three-letter abbreviation for a month instead of the full name, just use three M's:

=TEXT(A3,"mmm")

![Abbreviation for month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortMonth-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 You can also use the TEXT function if you only want two digits for the year rather than all four. You'll use the letter Y for year as the `format_code`:

=TEXT(A2,"yy")

![Two digits for the year using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortYear-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Again, you can use the fill handle to [copy the formula(s)](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) down to your remaining cells if you like.

![Copied formulas to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyShortFormulas-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Pulling a month or year out of a full date in Excel takes only a minute with these methods. For more, check out these additional [date and time functions in Excel](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/) you might find useful.

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


