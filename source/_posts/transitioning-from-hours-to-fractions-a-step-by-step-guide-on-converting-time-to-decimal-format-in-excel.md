---
title: "Transitioning From Hours to Fractions: A Step-by-Step Guide on Converting Time to Decimal Format in Excel"
date: 2024-08-28 13:42:32
updated: 2024-08-29 10:15:22
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/01a9c6a754e21b99c858623b51177464f69009a94f81e88dbd632b404f3b4368.jpg
---

## Transitioning From Hours to Fractions: A Step-by-Step Guide on Converting Time to Decimal Format in Excel

### Quick Links

* [Use the Time and Decimal Formats](https://youtube-videos.techidaily.com/new-effortless-guide-never-see-youtube-shorts-again/)
* [Convert Using Multiplication](https://sound-issues.techidaily.com/corsair-hs35-microphone-problems-and-fixes-for-windows-users/)
* [Convert Using the CONVERT Function](https://facebook-videos.techidaily.com/updated-essential-guide-best-top-10-fb-videos-on-android-downloader-for-2024/)
* [Convert Using Time Function Formulas](https://facebook-video-footage.techidaily.com/new-17-best-lights-and-lighting-equipment-for-youtube-for-2024/)

 While Excel offers many features and functions for working with times, you may want your times formatted as decimals instead. You might need them for use in other formulas, for a timesheet, or for your own preference.

 Here are a few ways to convert time to [decimals in Excel](https://instagram-clips.techidaily.com/2024-approved-snickel-and-wail-instagrams-10-most-hilarious-meme-accounts/). You can use whichever method you're most comfortable with or works best for you.

##  Use the Time and Decimal Formats

 Before you convert the times and decimals in your sheet, make sure that the cells are formatted as such.

Related: [How to Use the Accounting Number Format in Microsoft Excel](https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-xiaomi-redmi-12-5g-without-them-knowing-drfone-by-drfone-virtual-android/) 

 For time, you can do this by selecting the cell and choosing "Time" in the Number drop-down box on the Home tab. If you plan to convert hours, minutes, _and_ seconds, it's best to use the Format Cells feature. Select the cell or range, right-click, and pick "Format Cells."

![Format Cells in the shortcut menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FormatCells-ExcelConvertTimeDecimal.png) 

 Choose the Number tab and pick "Time" on the left. Then, pick the hours:minutes:seconds option on the right as shown below and click "OK."

![Format Cells as Time in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FormatCellsTime-ExcelConvertTimeDecimal.png) 

 For decimals, [format your result cells as numbers](https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-xiaomi-redmi-12-5g-without-them-knowing-drfone-by-drfone-virtual-android/) also using the Format Cells feature. Right-click the cell(s) and pick "Format Cells."

 Choose the Number tab and pick "Number" on the left. Set the number of decimal places to 2 on the right and click "OK."

![Format Cells as Number in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FormatCellsNumber-ExcelConvertTimeDecimal.png) 

 If you end up with a whole number as your result, you can use the [Increase and Decrease Decimal buttons](https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-lava-storm-5g-drfone-by-drfone-virtual-android/) in the Number section of the Home tab to adjust the appearance. This lets you display 624.00 as 624.

 You're then ready to start converting.

##  Convert Using Multiplication

 If you're not fond of [using functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) and building the accompanying formulas in Excel, you can convert time to decimals with simple multiplication.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

 You'll multiply the cell containing the time by the number of hours, minutes, or seconds in a day. Here, we have our time in cell A2\. To obtain the hours as a decimal, we multiply that value by 24, for 24 hours in a day.

=A2*24

 To obtain the decimal for minutes and seconds using that same cell value, you would multiply by the number of minutes (1,440) and then the number of seconds (86,400) in a day as follows:

=A2*1440

=A2*86400

 As you can see, we receive the number results for our time conversions.

![Multiplication conversions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/Multiplication-ExcelConvertTimeDecimal.png) 

##  Convert Using the CONVERT Function

 Another option for getting decimals for [times in Excel](https://android-frp.techidaily.com/how-to-bypass-frp-from-samsung-galaxy-f54-5g-by-drfone-android/) is with the CONVERT function. This versatile function lets you convert times, measurements, weights, and more.

Related: [How to Add or Subtract Times in Microsoft Excel](https://android-frp.techidaily.com/how-to-bypass-frp-from-samsung-galaxy-f54-5g-by-drfone-android/) 

 The syntax for the function is `CONVERT(reference, from, to)` where you'll use all three arguments. For the `from` argument, you'll use "day."

 To convert a time in cell A2 to hours, you would use this formula:

=CONVERT(A2,"day","hr")

![CONVERT function formula for hours](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ConvertFunctionHours-ExcelConvertTimeDecimal.png) 

 You can also use "d" instead of "day" for the `from` argument.

 To convert that same time to minutes and seconds, you would use these formulas:

=CONVERT(A2,"day","mn")

=CONVERT(A2,"day","sec")

![CONVERT function formula for minutes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ConvertFunctionMinutes-ExcelConvertTimeDecimal.png) 

 You can also use "min" instead of "mn" for minutes and "s" instead of "sec" for seconds.

##  Convert Using Time Function Formulas

 This last method uses [Excel's time functions](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/). Although the formulas are much lengthier than those above, it's still another option you might prefer. Here, you'll use the HOUR, MINUTE, and SECOND functions with a combination of calculations.

Related: [13 Microsoft Excel Date and Time Functions You Should Know](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/) 

 To convert the time in cell A2 to hours, you would use this formula:

=HOUR(A2)+MINUTE(A2)/60+SECOND(A2)/3600

![Time function formula for hours](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/TimeFunctionHours-ExcelConvertTimeDecimal.png) 

 Each function references the cell A2 and the results are added together. The MINUTE portion is divided by 60 for 60 minutes in an hour and the SECOND portion is divided by 3,600 for 3,600 seconds in an hour.

 To convert the same time to minutes, you would use this formula:

=HOUR(A2)*60+MINUTE(A2)+SECOND(A2)/60

![Time function formula for minutes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/TimeFunctionMinutes-ExcelConvertTimeDecimal.png) 

 Similar to the formula for hours, you add the result of the functions together. The HOUR portion is multiplied by 60 for 60 minutes in an hour and the SECOND portion is divided by 60 for 60 seconds in a minute.

 To convert that time to seconds, you would use this formula:

=HOUR(A1)*3600+MINUTE(A2)*60+SECOND(A2)

![Time function formula for seconds](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/TimeFunctionSeconds-ExcelConvertTimeDecimal.png) 

 With this formula, the HOUR portion is multiplied by 3,600 for 3,600 seconds in an hour and the MINUTE portion is multiplied by 60 for 60 seconds in a minute.

 As you can see, this last method requires more effort, but if you're familiar with using time functions in Excel, it might be your preferred one.

 Converting time to decimals in Excel sounds more difficult than it is. And, when you pick the above method that you like best, you'll be converting in no time.

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
