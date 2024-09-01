---
title: "Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function"
date: 2024-08-26 13:54:33
updated: 2024-08-29 12:24:59
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b734a2c6690e4996dacb7188f3387d968781f292fbd537e9c3d8dd96d06bbb96.jpg
---

## Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function

### Quick Links

* [What to Know When Using the SUBSTITUTE Function](https://article-helps.techidaily.com/updated-mastering-media-conversion-with-actionable-steps-from-xml-for-2024/)
* [Replace Occurrences of a String Using SUBSTITUTE in Excel](https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual/)

 To [replace a string](https://screen-mirror.techidaily.com/the-top-10-apple-iphone-6-plus-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/) of text, numbers, or symbols, Microsoft Excel offers a function called `SUBSTITUTE`. This function replaces the specified string with your choice of string. We'll show you how to use it in your spreadsheets.

Related: [How to Replace Any Character with Newlines in Notepad++](https://screen-mirror.techidaily.com/the-top-10-apple-iphone-6-plus-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/) 

##  What to Know When Using the SUBSTITUTE Function

 When you use the `SUBSTITUTE` function, know that it's case-sensitive and so you'll have to use it accordingly. Also, you can't specify wildcard entries in the function. You can use the function with your hard-coded values as well as [cell references](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/).

 The function even lets you choose the instances of your specified string to change. This way, if you only want to change the first occurrence of a string, you can do so.

##  Replace Occurrences of a String Using SUBSTITUTE in Excel

 To start using the function, open your spreadsheet with Microsoft Excel.

 In the spreadsheet, select the cell in which you want to display the result. In the below example, we'll replace 

        `HTG`
    
 with 

        `How-To Geek`
    
 .

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/1-select-cell-excel.png) 

 In your selected cell, type the following function and press Enter.

 In this function:

* **B2**: It's the cell with the content that you want to replace.
* **HTG**: This is the original string that you want to find and replace with the new string.
* **How-To Geek**: This is the new string that will replace the old string.

=SUBSTITUTE(B2,"HTG","How-To Geek")

![Replace a string with SUBSTITUTE.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/2-enter-substitute-function.png) 

 You'll see that the function has replaced the values as defined in the arguments.

![The result of the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/3-substitute-function-result.png) 

 Another scenario where you may want to use this function is when you want to change the country code for phone numbers. For example, if you have a list of phone numbers containing `+91` as the country code, you can use the `SUBSTITUTE` function to make all these phone numbers use `+1` as the country code.

 To do so, use the `SUBSTITUTE` function with the following arguments:

=SUBSTITUTE(B2,"91","1",1)

![Enter the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/4-change-country-code.png) 

 As you can see, in the above function, we've specified `1` at the end. This tells the function to only change the first occurrence of `91` to `1`. If the remaining numbers in a phone number contain `91`, the function won't change that. This helps you avoid ending up with incorrect phone numbers.

![Country code changed with the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/5-country-code-changed.png) 

 And that's how you use Excel's `SUBSTITUTE` function to change various strings in your spreadsheets.

---

 Another way to change your spreadsheet's contents is by [using Excel's find and replace feature](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/). Check out our guide on that if you're interested.

Related: [How to Find and Replace Text and Numbers in Excel](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/)

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
