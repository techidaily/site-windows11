---
title: "Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel"
date: 2024-08-26 20:56:24
updated: 2024-08-29 12:33:28
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ee671cfb7ee587015883db0a3fbeb82905b8663f1657e5b249344fa4f87d839d.jpg
---

## Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel

### Quick Links

* [Which Units Can You Convert?](https://printer-issues.techidaily.com/seamless-printing-setup-for-hp-and-laptops-immediate-solutions/)
* [Use the CONVERT Function](https://fox-that.techidaily.com/is-your-iphones-visual-look-up-not-responding-explore-common-problems-and-fixes/)
* [Help With Unit Abbreviations](https://facebook-video-recording.techidaily.com/updated-2024-approved-building-a-brand-the-art-of-creating-attention-grabbing-reels-on-social-media/)

 Unit conversions are commonplace. Whether you need feet to meters, Fahrenheit to Celsius, or teaspoons to tablespoons, you can take advantage of the CONVERT function in Microsoft Excel for a dozen types of conversion.

 The nice thing about this function in Excel is that it uses a [basic formula](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) with only a few arguments. So not only is it simple to use, but it's also easy to remember.

##  Which Units Can You Convert?

 As mentioned, you can convert more than 12 types of units with the function.

* Weight and mass
* Distance
* Time
* Pressure
* Force
* Energy
* Power
* Magnetism
* Temperature
* Volume
* Area
* Information
* Speed

 Let's look at some examples.

##  Use the CONVERT Function

 The syntax for the function is 

        `CONVERT(reference, from_unit, to_unit)`
    
 where you'll need all three arguments. The 

        `reference`
    
 argument can be a number or a cell reference.

###  Distance

 For a simple distance conversion, we'll convert the inches in cell A2 to feet using this formula:

=CONVERT(A2,"in","ft")

![Formula to convert inches to feet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/InchesFeetCell-ExcelConvertFunction.png) 

 You can also use a number as the reference and create the formula this way:

=CONVERT(24,"in","ft")

![Formula to convert inches to feet using a number](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/InchesFeet-ExcelConvertFunction.png) 

 Here are a few other abbreviations for common distance measurements:

* Yard: yd
* Meter: m
* Statute mile: mi
* Nautical mile: Nmi
* U.S. survey mile: survey\_mi

###  Temperature

 Converting temperatures is common when you're working with someone who uses Celsius instead of Fahrenheit.

 Here, we'll convert the temperature in cell A2 from Fahrenheit to Celsius:

=CONVERT(A2,"fah","cel")

![Formula to convert Fahrenheit to Celsius](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FahrenheitCelsiusCell-ExcelConvertFunction.png) 

 Note, you can also use "F" instead of "fah" and "C" instead of "cel." Plus, you can use a number instead of a cell reference.

 You can use this formula to convert 78 from Fahrenheit to Celsius:

=CONVERT(78,"F","C")

![Formula to convert Fahrenheit to Celsius using a number](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FahrenheitCelsius-ExcelConvertFunction.png) 

 Other temperature abbreviations include:

* Kelvin: K or kel
* Degrees Rankine: Rank
* Degrees Reaumur: Reau

 It's likely that when using CONVERT with temperature and other units, it's likely you'll want to [round decimal values](https://instagram-clips.techidaily.com/2024-approved-snickel-and-wail-instagrams-10-most-hilarious-meme-accounts/).

###  Volume

 If you spend time in the kitchen, then you might find yourself converting those types of measurements. You can convert teaspoons to tablespoons for the value in cell A2:

=CONVERT(A2,"tsp","tbs")

![Formula to convert teaspoons to tablespoons](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/TeaspoonTablespoon-ExcelConvertFunction.png) 

 With this formula, you can convert a specific number U.S pints to U.K. pints:

=CONVERT(20,"us_pt","uk_pt")

![Formula to convert US to UK pints](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/USUKPints-ExcelConvertFunction.png) 

 Here are a handful of additional volume abbreviations you might use:

* Ounce: oz
* Cup: cup
* Quart: qt
* Gallon: gal
* Liter: l, L, or lt

###  Area

 Need to perform some area conversions? This formula converts the value in cell A2 from square feet to square inches:

=CONVERT(A2,"ft2","in2")

![Formula to convert square feet to square inches](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/SquareFeetInches-ExcelConvertFunction.png) 

 And with this formula, you can convert square meters to square miles:

=CONVERT(A2,"m2","mi2")

![Formula to convert square meters to square miles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/SquareMetersMiles-ExcelConvertFunction.png) 

 Additional area abbreviations you might need include:

* Square yards: yd2 or yd^2
* Square nautical miles: Nmi2 or Nmi^2
* Morgen: Morgen
* International acre: uk\_acre
* U.S. statute acre: us\_acre

###  Speed

 How about a speed conversion? Here, you can convert the value in cell A2 from meters per hour to meters per second:

=CONVERT(A2,"m/h","m/s")

![Formula to convert meters per hour to meters per second](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/MetersHoursSeconds-ExcelConvertFunction.png) 

 You can also convert from meters per hour to miles per hour:

=CONVERT(65,"m/h","mph")

![Formula to convert meters per hour to miles per hour](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/MetersMiles-ExcelConvertFunction.png) 

###  Information

 For one more example, we'll convert our A2 value from bits to bytes with this formula:

=CONVERT(A2,"bit","byte")

![Formula to convert bits to bytes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/BitByte-ExcelConvertFunction.png) 

##  Help With Unit Abbreviations

 The most difficult part of using the CONVERT function in Excel is knowing the abbreviations for the units. You can take a look at [Microsoft's Support page for the function](https://support.microsoft.com/en-us/office/convert-function-d785bef1-808e-4aac-bdcd-666c810f9af2) if you want to convert a unit that isn't as common as some others. However, [Excel does offer help](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) too.

Related: [How to Find the Function You Need in Microsoft Excel](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) 

 When you enter the CONVERT function into your sheet's Formula Bar, you can select a unit argument to see the options and pick the one you need.

 Here, we're converting ounces to cups. You can see when we place our cursor in the argument's spot for the `to_unit`, a drop-down list appears. Double-click the unit you want and the abbreviation will appear in the formula.

![Dropdown to select a unit for the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/UnitDropdown-ExcelConvertFunction.png) 

 Then, insert your closing parenthesis and press Enter or Return to apply the formula and receive the result.

![Formula to convert ounces to cups](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/OuncesCups-ExcelConvertFunction.png) 

 You can use this drop-down box to choose both the `from_unit` and `to_unit` arguments easily. This is handy for those abbreviations that are less than obvious.

 When you have an Excel spreadsheet that uses units of measurement like these, remember the CONVERT function.

 For more, take a look at how to [convert text to dates](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) or how to [convert text to numbers](https://facebook-videos.techidaily.com/2024-approved-unlock-laughter-traps-20-quirky-fb-detention-anecdotes-for-amusement/) in Excel.

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
