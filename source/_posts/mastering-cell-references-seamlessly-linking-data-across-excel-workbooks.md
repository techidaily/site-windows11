---
title: "Mastering Cell References: Seamlessly Linking Data Across Excel Workbooks"
date: 2024-08-31T22:04:57.659Z
updated: 2024-09-01T22:04:57.659Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b3b1cb7d8c5c52c25843bc952abd6a00ab0cd811cafc15697aa0c13fd607a950.jpg
---

## Mastering Cell References: Seamlessly Linking Data Across Excel Workbooks

### Quick Links

* [How to Reference Another Sheet in the Same Excel File](https://sound-tweaking.techidaily.com/updated-the-ultimate-selection-of-six-compelling-chrome-talk-transformers-to-experience-moviemagicsuite-for-2024/)
* [How to Reference Another Excel File](https://technical-tips.techidaily.com/handling-msvbvm50dll-cannot-be-found-a-comprehensive-tutorial-for-quick-fixes/)
* [How to Cross Reference a Cell Range in a Function](https://facebook-video-content.techidaily.com/new-2024-approved-secure-your-social-media-experience-from-ad-interruptions/)
* [How to Use Defined Names for Simple Cross References](https://tech-revival.techidaily.com/the-efficient-approach-to-persona-creation-with-chatgpt/)
* [How to Format Data as a Table](https://screen-sharing-recording.techidaily.com/updated-master-classic-ps2-games-on-android-with-our-top-picks-for-2024/)
* [How to Use the VLOOKUP Function for Dynamic References](https://snapchat-videos.techidaily.com/2024-approved-ensuring-every-snapchatter-friendly-footage-via-mac/)

 In Microsoft Excel, it's a common task to refer to cells on other worksheets or even in different Excel files. At first, this can seem a little daunting and confusing, but once you understand how it works, it's not so hard.

 In this article, we'll look at how to reference another sheet in the same Excel file and how to reference a different Excel file. We'll also cover things like how to reference a cell range in a function, how to make things simpler with defined names, and how to use VLOOKUP for dynamic references.

##  How to Reference Another Sheet in the Same Excel File

 A basic cell reference is written as the column letter followed by the row number.

 So the cell reference B3 refers to the cell at the intersection of column B and row 3.

 When referring to cells on other sheets, this cell reference is preceded with the other sheet's name. For example, below is a reference to cell B3 on a sheet name "January."

=January!B3

 The exclamation point (!) separates the sheet name from the cell address.

 If the sheet name contains spaces, then you must enclose the name with single quotation marks in the reference.

='January Sales'!B3

 To create these references, you can type them directly into the cell. However, it is easier and more reliable to let Excel write the reference for you.

 Type an equal sign (=) into a cell, click on the Sheet tab, and then click the cell that you want to cross-reference.

 As you do this, Excel writes the reference for you in the Formula Bar.

![Sheet reference in formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/sheet-reference-2.png) 

 Press Enter to complete the formula.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
##  How to Reference Another Excel File

 You can refer to cells of another workbook using the same method. Just be sure that you have the other Excel file open before you begin typing the formula.

 Type an equal sign (=), switch to the other file, and then click the cell in that file you want to reference. Press Enter when you're done.

 The completed cross-reference contains the other workbook name enclosed in square brackets, followed by the sheet name and cell number.

=[Chicago.xlsx]January!B3

 If the file or sheet name contains spaces, then you'll need to enclose the file reference (including the square brackets) in single quotation marks.

='[New York.xlsx]January'!B3

![Formula that references another workbook](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/workbook-reference.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 In this example, you can see dollar signs ($) amongst the cell address. This is an absolute cell reference ([Find out more about absolute cell references](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/)).

 When referencing cells and ranges on different Excel files, the references are made absolute by default. You can change this to a relative reference if required.

 If you look at the formula when the referenced workbook is closed, it will contain the entire path to that file.

![Full file path of workbook in the formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/closed-workbook.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Although creating references to other workbooks is straightforward, they are more susceptible to issues. Users creating or renaming folders and moving files can break these references and cause errors.

 Keeping data in one workbook, if possible, is more reliable.

##  How to Cross Reference a Cell Range in a Function

 Referencing a single cell is useful enough. But you might want to write a function (such as SUM) that references a range of cells on another worksheet or workbook.

 Start the function as usual and then click on the sheet and the range of cells---the same way you did in the previous examples.

 In the following example, a SUM function is summing the values from range B2:B6 on a worksheet named Sales.

=SUM(Sales!B2:B6)

![Sheet cross reference in sum function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/range-in-function.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
##  How to Use Defined Names for Simple Cross References

 In Excel, you can assign a name to a cell or range of cells. This is more meaningful than a cell or range address when you look back at them. If you use a lot of references in your spreadsheet, naming those references can make it much easier to see what you've done.

 Even better, this name is unique for all the worksheets in that Excel file.

 For example, we could name a cell 'ChicagoTotal' and then the cross-reference would read:

=ChicagoTotal

 This is a more meaningful alternative to a standard reference like this:

=Sales!B2

 It's easy to create a defined name. Start by selecting the cell or range of cells that you want to name.

 Click in the Name Box in the top left corner, type the name you want to assign, and then press Enter.

![Defining a name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/defined-name.png) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When creating defined names, you cannot use spaces. Therefore, in this example, the words have been joined in the name and separated by a capital letter. You could also separate words with characters like a hyphen (-) or underscore (\_).

 Excel also has a Name Manager that makes monitoring these names in the future easy. Click Formulas > Name Manager. In the Name Manager window, you can see a list of all of the defined names in the workbook, where they are, and what values they currently store.

![Name Manager to manage the defined names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/name-manager.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
 You can then use the buttons along the top to edit and delete these defined names.

##  How to Format Data as a Table

 When working with an extensive list of related data, using Excel's Format as Table feature can simplify the way that you reference data in it.

 Take the following simple table.

![Small list of product sales data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/small-list.png) 

 This could be formatted as a table.

 Click on a cell in the list, switch to the "Home" tab, click the "Format as Table" button, and then select a style.

![Format a range as a table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/format-as-table.png) 

 Confirm that the range of cells is correct and that your table has headers.

![Confirm the range to use for the table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/confirm-range.png) 

 You can then assign a meaningful name to your table from the "Design" tab.

![Assign a name to your Excel table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/table-name.png) 

 Then, if we needed to sum the sales of Chicago, we could refer to the table by its name (from any sheet), followed by a square bracket (\[) to see a list of the table's columns.

![Using structured references in formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/structured-references.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 Select the column by double-clicking it in the list and enter a closing square bracket. The resulting formula would look something like this:

=SUM(Sales[Chicago])

 You can see how tables can make referencing data for aggregation functions such as SUM and AVERAGE easier than standard sheet references.

 This table is small for the purposes of demonstration. The larger the table and the more sheets you have in a workbook, the more benefits you'll see.

##  How to Use the VLOOKUP Function for Dynamic References

 The references used in the examples thus far have all been fixed to a specific cell or range of cells. That's great and is often sufficient for your needs.

 However, what if the cell you are referencing has the potential to change when new rows are inserted, or somebody sorts the list?

 In those scenarios, you could not guarantee the value you want will still be in the same cell that you initially referenced.

 An alternative in these scenarios is to use a lookup function within Excel to search for the value in a list. This makes it more durable against changes to the sheet.

 In the following example, we use the VLOOKUP function to look up an employee on another sheet by their employee ID and then return their start date.

 Below is the example list of employees.

![List of employees](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/employees.png) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The VLOOKUP function looks down the first column of a table and then returns information from a specified column to the right.

 The following VLOOKUP function searches for the employee ID entered into cell A2 in the list shown above and returns the date joined from column 4 (fourth column of the table).

=VLOOKUP(A2,Employees!A:E,4,FALSE)

![The VLOOKUP function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/vlookup.png) 

 Below is an illustration of how this formula searches the list and returns the correct information.

![The VLOOKUP function and how it works](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/found-1282.png) 

 The great thing about this VLOOKUP over the previous examples is that the employee will be found even if the list changes in order.

**Note:** VLOOKUP is an incredibly useful formula, and we've only scratched the surface of its value in this article. You can find out more about how to use VLOOKUP from [our article on the subject](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/).

---

 In this article, we have looked at multiple ways to cross-reference between Excel spreadsheets and workbooks. Choose the approach that works for your task at hand, and that you feel comfortable working with.

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


