---
title: "Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function"
date: 2024-08-31T22:03:23.760Z
updated: 2024-09-01T22:03:23.760Z
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
##  Replace Occurrences of a String Using SUBSTITUTE in Excel

 To start using the function, open your spreadsheet with Microsoft Excel.

 In the spreadsheet, select the cell in which you want to display the result. In the below example, we'll replace 

        `HTG`
    
 with 

        `How-To Geek`
    
 .

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/1-select-cell-excel.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 In your selected cell, type the following function and press Enter.

 In this function:

* **B2**: It's the cell with the content that you want to replace.
* **HTG**: This is the original string that you want to find and replace with the new string.
* **How-To Geek**: This is the new string that will replace the old string.

=SUBSTITUTE(B2,"HTG","How-To Geek")

![Replace a string with SUBSTITUTE.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/2-enter-substitute-function.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 You'll see that the function has replaced the values as defined in the arguments.

![The result of the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/3-substitute-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Another scenario where you may want to use this function is when you want to change the country code for phone numbers. For example, if you have a list of phone numbers containing `+91` as the country code, you can use the `SUBSTITUTE` function to make all these phone numbers use `+1` as the country code.

 To do so, use the `SUBSTITUTE` function with the following arguments:

=SUBSTITUTE(B2,"91","1",1)

![Enter the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/4-change-country-code.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, in the above function, we've specified `1` at the end. This tells the function to only change the first occurrence of `91` to `1`. If the remaining numbers in a phone number contain `91`, the function won't change that. This helps you avoid ending up with incorrect phone numbers.

![Country code changed with the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/5-country-code-changed.png) 

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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


