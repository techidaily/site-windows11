---
title: Top 13 Essential Microsoft Excel Date/Time Formulas Every User Must Master
date: 2024-08-31T22:04:48.504Z
updated: 2024-09-01T22:04:48.504Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/hour-glass-calendar.jpg
---

## Top 13 Essential Microsoft Excel Date/Time Formulas Every User Must Master

### Quick Links

* [View the Current Date or Time: TODAY and NOW](https://extra-support.techidaily.com/masterful-tantalizing-titles-designer-for-2024/)
* [Create a Full Date: DATE](https://screen-mirroring-recording.techidaily.com/new-best-in-class-chromebook-recording-app/)
* [Get Parts of a Date: DAY, MONTH, YEAR](https://techidaily.com/recover-apple-iphone-13-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/)
* [See a Portion of the Day: TIME](https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-nubia-z50s-pro-drfone-by-drfone-virtual-android/)
* [Get Parts of a Time: HOUR, MINUTE, SECOND](https://techidaily.com/best-fixes-for-itel-a05s-hard-reset-drfone-by-drfone-reset-android-reset-android/)
* [Calculate Days, Months, or Years Between Dates: DATEDIF](https://fox-http.techidaily.com/2024-approved-fusing-art-and-technology-crafting-captivating-animation-videos-in-windows-movie-maker/)
* [Find the Number of Workdays: NETWORKDAYS](https://ios-unlock.techidaily.com/how-to-remove-passcode-from-iphone-12-complete-guide-by-drfone-ios/)
* [See the Week Number: WEEKNUM](https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-xiaomi-redmi-note-13-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/)

 Whether you use Microsoft Excel for [managing monthly bills](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) or tracking time for work, you likely use dates or times. With these functions, you can enter or obtain the dates and times you need.

 You might already be familiar with some date and time functions in Excel. So let's look at essential functions for common tasks as well as more advanced functions you may not know exist.

##  View the Current Date or Time: TODAY and NOW

 Probably the handiest of all date and time functions in Excel are TODAY and NOW. TODAY provides [the current date](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) and NOW provides the current date and time.

Related: [How to Insert Today's Date in Microsoft Excel](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) 

 The syntax for each is the same, with the name of the function and no arguments. Enter one of the following to obtain the date or the date with the time.

=TODAY()

=NOW()

![TODAY and NOW functions in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/TodayNow-ExcelDataEntryFunctions.png) 

##  Create a Full Date: DATE

 Not all dates in your sheet may be in a single cell. Maybe you have the day, month, and year in separate columns and want to combine them for a complete date. You can use the [DATE function](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) in Excel.

 The syntax for the function is `DATE(year, month, day)` with all three arguments required. Enter the year in four digits, the month as a number from 1 to 12, and the day as a number from 1 to 31.

 To combine the year, month, and day from our cells A2, B2, and C2 respectively, you would use the following formula:

=DATE(A2,B2,C2)

![DATE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/DATE-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Get Parts of a Date: DAY, MONTH, YEAR

 When using dates in other formulas, you may need to obtain the serial number of a day, month, or year. This is exactly what the DAY, MONTH, and [YEAR functions](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) in Excel do. Where the DATE function combines parts of a date, these functions provide parts of one.

Related: [How to Use the YEAR Function in Microsoft Excel](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) 

 The syntax for each function is the same with the name of the function followed by a cell reference or serial number in parentheses. For example, `DAY(cell_reference)`.

 To [obtain the day](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) number in cell F2, use the following formula. The result will be a number from 1 to 31.

=DAY(F2)

 To obtain the month number in cell F2, use the following. The result will be a number from 1 to 12.

=MONTH(F2)

 To obtain the year number in cell F2, use the following. The result will be a four-digit number.

=YEAR(F2)

![DAY function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/DAY-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  See a Portion of the Day: TIME

 The TIME function in Excel provides you with the decimal portion of a day based on hours, minutes, and seconds in your sheet.

 The syntax is `TIME(hour, minute, second)` where all three arguments are required, and the input is a number from 0 to 32767 representing each.

 To find the decimal number for 12 hours on the dot with no minutes or seconds, you would use the following formula and replace the cell references with your own.

=TIME(A2,B2,C2)

![TIME function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/TIME-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the result displays a time rather than a decimal, format the cell as a number by selecting "Number" in the Number drop-down box on the Home tab.

##  Get Parts of a Time: HOUR, MINUTE, SECOND

 Similar to DAY, MONTH, and YEAR, the HOUR, MINUTE, and SECOND functions give you parts of a [time entry](https://android-frp.techidaily.com/how-to-bypass-frp-from-samsung-galaxy-f54-5g-by-drfone-android/).

 The syntax for each function is the same with the name of the function followed by a cell reference or serial number in parentheses. For example, `HOUR(cell_reference)`.

 To obtain the hour in cell F2, use the following formula:

=HOUR(F2)

 To obtain the minutes in cell F2, use the following:

=MINUTE(F2)

 To obtain the seconds in cell F2, use the following:

=SECOND(F2)

![HOUR function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/HOUR-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
##  Calculate Days, Months, or Years Between Dates: DATEDIF

 You can use the [DAYS function](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/) to find the number of days between two dates. But the DATEDIF function goes a step further by allowing you to find the number of days, months, or years.

Related: [How to Find the Number of Days Between Two Dates in Microsoft Excel](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/) 

 The syntax is `DATEDIF(start_date, end_date, type)` where all three arguments are required. The `type` is based on the value you want to receive:

* Years: Enter Y.
* Months: Enter M.
* Days: Enter D.
* Difference in months without years and days: Enter YM.
* Differences in days without years: Enter YD.

 To find the number of months between 1/1/2021 and 12/31/2022 in cells H2 and I2, you would use this formula:

=DATEDIF(H2,I2,"M")

![DATEIF function for months](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/DATEDIFMonths-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
 To find the number of days between the same start and end dates in the same cells you would use this formula:

=DATEDIF(H2,I2,"D")

![DATEIF function for days](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/DATEDIFDays-ExcelDateTimeFunctions.png) 

##  Find the Number of Workdays: NETWORKDAYS

 Maybe you want to find the number of workdays between two dates. With NETWORKDAYS, you can get this number and optionally reference holidays in a different cell range.

 The syntax is `NETWORKDAYS(start_date, end_date, holidays)` with only the first two arguments required.

 To find the number of workdays between 1/1/2022 and 12/31/2022 in cells H2 and I2, use this formula:

=NETWORKDAYS(H2,I2)

![NETWORKDAYS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/NETWORKDAYS-ExcelDateTimeFunctions.png) 

 To find the number of workdays for those same dates but with holidays listed in the range H5 through H7, use this formula:

=NETWORKDAYS(H2,I2,H5:H7)

![NETWORKDAYS function with holidays](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/NETWORKDAYSHolidays-ExcelDateTimeFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 Even though we have three holidays listed, they do not all fall on workdays. So, the difference in the above is only one day.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  See the Week Number: WEEKNUM

 You don't have to count weeks manually if you use the WEEKNUM function. With it, you can find the week number in a year for any date.

 The syntax is `WEEKNUM(cell_reference, type)` with the first argument required. The `type` argument can be used for weeks beginning on a particular date. If the argument is omitted, the function assumes Sunday by default.

 To find the week number for 4/15/2022 in cell F2, use the following formula:

=WEEKNUM(A2)

![WEEKNUM function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/WEEKNUM-ExcelDateTimeFunctions.png) 

 To find the same week number for weeks starting on Monday, you would use the following formula with `2` as the `type` argument:

=WEEKNUM(A2,2)

 Visit the [Microsoft Support page for the WEEKNUM function](https://support.microsoft.com/en-us/office/weeknum-function-e5c43a03-b4ab-426c-b411-b18c13c75340) for a full list of the 10 available types.

 Hopefully these date and time [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) help keep you on track in your Excel sheet.

Related: [Functions vs. Formulas in Microsoft Excel: What's the Difference?](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/)

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


