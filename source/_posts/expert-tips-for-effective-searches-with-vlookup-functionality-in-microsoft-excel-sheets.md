---
title: Expert Tips for Effective Searches with VLOOKUP Functionality in Microsoft Excel Sheets
date: 2024-08-27 16:55:46
updated: 2024-08-29 11:19:36
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/invoice_database.png
---

## Expert Tips for Effective Searches with VLOOKUP Functionality in Microsoft Excel Sheets

VLOOKUP is one of Excel’s most useful functions, and it’s also one of the least understood. In this article, we demystify VLOOKUP by way of a real-life example. We’ll create a usable Invoice Template for a fictitious company.

 VLOOKUP is an Excel function. This article will assume that the reader already has a passing understanding of Excel functions, and can use basic functions such as SUM, AVERAGE, and TODAY. In its most common usage, VLOOKUP is a database function, meaning that it works with database tables - or more simply, lists of things in an Excel worksheet. What sort of things? Well, any sort of thing. You may have a worksheet that contains a list of employees, or products, or customers, or CDs in your CD collection, or stars in the night sky. It doesn’t really matter.

 Here’s an example of a list, or database. In this case it’s a list of products that our fictitious company sells:

![503x210xdatabase.png.pagespeed.gp+jp+jw+pj+js+rj+rp+rw+ri+cp+md.ic.u3M88bovhQ](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/503x210xdatabase.png.pagespeed.gpjpjwpjjsrjrprwricpmd.ic_.u3M88bovhQ.png) 

 Usually lists like this have some sort of unique identifier for each item in the list. In this case, the unique identifier is in the “Item Code” column. Note: For the VLOOKUP function to work with a database/list, that list must have a column containing the unique identifier (or “key”, or “ID”), and that column must be the first column in the table. Our sample database above satisfies this criterion.

 The hardest part of using VLOOKUP is understanding exactly what it’s for. So let’s see if we can get that clear first:

> **VLOOKUP retrieves information from a database/list based on a supplied instance of the unique identifier.** 

 In the example above, you would insert the VLOOKUP function into another spreadsheet with an item code, and it would return to you either the corresponding item’s description, its price, or its availability (its “In stock” quantity) as described in your original list. Which of these pieces of information will it pass you back? Well, you get to decide this when you’re creating the formula.

 If all you need is one piece of information from the database, it would be a lot of trouble to go to to construct a formula with a VLOOKUP function in it. Typically you would use this sort of functionality in a reusable spreadsheet, such as a template. Each time someone enters a valid item code, the system would retrieve all the necessary information about the corresponding item.

 Let’s create an example of this: An Invoice Template that we can reuse over and over in our fictitious company.

 First we start Excel, and we create ourselves a blank invoice:

![invoice](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/invoice.png) 

 This is how it’s going to work: The person using the invoice template will fill in a series of item codes in column “A”, and the system will retrieve each item’s description and price from our product database. That information will be used to calculate the line total for each item (assuming we enter a valid quantity).

 For the purposes of keeping this example simple, we will locate the product database on a separate sheet in the same workbook:

![selectsheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/selectsheet.png) 

 In reality, it’s more likely that the product database would be located in a separate workbook. It makes little difference to the VLOOKUP function, which doesn’t really care if the database is located on the same sheet, a different sheet, or a completely different workbook.

 So, we've created our product database, which looks like this:

![503x210xdatabase.png.pagespeed.gp+jp+jw+pj+js+rj+rp+rw+ri+cp+md.ic.u3M88bovhQ](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/503x210xdatabase.png.pagespeed.gpjpjwpjjsrjrprwricpmd.ic_.u3M88bovhQ.png) 

 In order to test the VLOOKUP formula we’re about to write, we first enter a valid item code into cell A11 of our blank invoice:

![itemcode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/itemcode.png) 

 Next, we move the active cell to the cell in which we want information retrieved from the database by VLOOKUP to be stored. Interestingly, this is the step that most people get wrong. To explain further: We are about to create a VLOOKUP formula that will retrieve the description that corresponds to the item code in cell A11\. Where do we want this description put when we get it? In cell B11, of course. So that’s where we write the VLOOKUP formula: in cell B11\. Select cell B11 now.

![selectdescription](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/selectdescription.png) 

 We need to locate the list of all available functions that Excel has to offer, so that we can choose VLOOKUP and get some assistance in completing the formula. This is found by first clicking the **Formulas** tab, and then clicking **Insert Function**:

![formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/formulas.png) 

 A box appears that allows us to select any of the functions available in Excel.

![insertfunctionbox](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/insertfunctionbox.png) 

 To find the one we’re looking for, we could type a search term like “lookup” (because the function we’re interested in is a lookup function). The system would return us a list of all lookup-related functions in Excel. **VLOOKUP** is the second one in the list. Select it an click **OK**.

![findlookup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/findlookup.png) 

 The **Function Arguments** box appears, prompting us for all the arguments (or parameters) needed in order to complete the VLOOKUP function. You can think of this box as the function asking us the following questions:

1. What unique identifier are you looking up in the database?
2. Where is the database?
3. Which piece of information from the database, associated with the unique identifier, do you wish to have retrieved for you?

 The first three arguments are shown **in bold**, indicating that they are mandatory arguments (the VLOOKUP function is incomplete without them and will not return a valid value). The fourth argument is not bold, meaning that it’s optional:

![funcarguments](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/funcarguments.png) 

 We will complete the arguments in order, top to bottom.

 The first argument we need to complete is the **Lookup\_value** argument. The function needs us to tell it where to find the unique identifier (the item code in this case) that it should be returning the description of. We must select the item code we entered earlier (in A11).

 Click on the selector icon to the right of the first argument:

![funcarguments1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/funcarguments1.png) 

 Then click once on the cell containing the item code (A11), and press **Enter**:

![selectarg1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/selectarg1.png) 

 The value of “A11” is inserted into the first argument.

 Now we need to enter a value for the **Table\_array** argument. In other words, we need to tell VLOOKUP where to find the database/list. Click on the selector icon next to the second argument:

![funcarguments2](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/funcarguments2.png) 

 Now locate the database/list and select the entire list - not including the header line. In our example, the database is located on a separate worksheet, so we first click on that worksheet tab:

![selectsheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/selectsheet1.png) 

 Next we select the entire database, not including the header line:

![640x284xselectarg2.png.pagespeed.gp+jp+jw+pj+js+rj+rp+rw+ri+cp+md.ic.4EDJIujZoM](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/640x284xselectarg2.png.pagespeed.gpjpjwpjjsrjrprwricpmd.ic_.4EDJIujZoM.png) 

 ...and press **Enter**. The range of cells that represents the database (in this case “’Product Database’!A2:D7”) is entered automatically for us into the second argument.

 Now we need to enter the third argument, **Col\_index\_num**. We use this argument to specify to VLOOKUP which piece of information from the database, associate with our item code in A11, we wish to have returned to us. In this particular example, we wish to have the item’s description returned to us. If you look on the database worksheet, you’ll notice that the “Description” column is the second column in the database. This means that we must enter a value of “2” into the **Col\_index\_num** box:

![arg3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/arg3.png) 

 It is important to note that that we are not entering a “2” here because the “Description” column is in the **B** column on that worksheet. If the database happened to start in column **K** of the worksheet, we would still enter a “2” in this field because the “Description” column is the second column in set of cells we selected when specifying the “Table\_array”.

 Finally, we need to decide whether to enter a value into the final VLOOKUP argument, **Range\_lookup**. This argument requires either a **true** or **false** value, or it should be left blank. When using VLOOKUP with databases (as is true 90% of the time), the way to decide what to put in this argument can be thought of as follows:

> If the first column of the database (the column that contains the unique identifiers) is sorted alphabetically/numerically in ascending order, then it’s possible to enter a value of **true** into this argument, or leave it blank.
> 
> If the first column of the database is not sorted, or it’s sorted in descending order, then you must enter a value of **false** into this argument

 As the first column of our database is not sorted, we enter **false** into this argument:

![arg4](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/arg4.png) 

 That’s it! We’ve entered all the information required for VLOOKUP to return the value we need. Click the **OK** button and notice that the description corresponding to item code “R99245” has been correctly entered into cell B11:

![509x149xdescfilledin.png.pagespeed.gp+jp+jw+pj+js+rj+rp+rw+ri+cp+md.ic.oZ5mPW4wRY](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/509x149xdescfilledin.png.pagespeed.gpjpjwpjjsrjrprwricpmd.ic_.oZ5mPW4wRY.png) 

 The formula that was created for us looks like this:

![formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/formula.png) 

 If we enter a different item code into cell A11, we will begin to see the power of the VLOOKUP function: The description cell changes to match the new item code:

![changecode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/changecode.png) 

 We can perform a similar set of steps to get the item’s price returned into cell E11\. Note that the new formula must be created in cell E11\. The result will look like this:

![2ndformula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/2ndformula.png) 

 ...and the formula will look like this:

![2ndformula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/2ndformula1.png) 

 Note that the only difference between the two formulae is the third argument (**Col\_index\_num**) has changed from a “2” to a “3” (because we want data retrieved from the 3rd column in the database).

 If we decided to buy 2 of these items, we would enter a “2” into cell D11\. We would then enter a simple formula into cell F11 to get the line total:

> \=D11\*E11

 ...which looks like this...

![linecomplete](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/linecomplete.png) 

##  Completing the Invoice Template

 We’ve learned a lot about VLOOKUP so far. In fact, we’ve learned all we’re going to learn in this article. It’s important to note that VLOOKUP can be used in other circumstances besides databases. This is less common, and may be covered in future How-To Geek articles.

 Our invoice template is not yet complete. In order to complete it, we would do the following:

1. We would remove the sample item code from cell A11 and the “2” from cell D11\. This will cause our newly created VLOOKUP formulae to display error messages:  
![errors](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/errors.png)  
 We can remedy this by judicious use of Excel’s **IF()** and **ISBLANK()** functions. We change our formula from this... **\=VLOOKUP(A11,'Product Database'!A2:D7,2,FALSE)**...to this...**\=IF(ISBLANK(A11),"",VLOOKUP(A11,'Product Database'!A2:D7,2,FALSE))**
2. We would copy the formulas in cells B11, E11 and F11 down to the remainder of the item rows of the invoice. Note that if we do this, the resulting formulas will no longer correctly refer to the database table. We could fix this by changing the cell references for the database to absolute cell references. Alternatively - and even better - we could create a [range name](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/) for the entire product database (such as “Products”), and use this range name instead of the cell references. The formula would change from this... **\=IF(ISBLANK(A11),"",VLOOKUP(A11,'Product Database'!A2:D7,2,FALSE))**...to this... **\=IF(ISBLANK(A11),"",VLOOKUP(A11,Products,2,FALSE))**...and then copy the formulas down to the rest of the invoice item rows.
3. We would probably “lock” the cells that contain our formulae (or rather unlock the other cells), and then protect the worksheet, in order to ensure that our carefully constructed formulae are not accidentally overwritten when someone comes to fill in the invoice.
4. We would save the file as a template, so that it could be reused by everyone in our company

 If we were feeling really clever, we would create a database of all our customers in another worksheet, and then use the customer ID entered in cell F5 to automatically fill in the customer’s name and address in cells B6, B7 and B8.

![customers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/03/customers.png) 

 If you would like to practice with VLOOKUP, or simply see our resulting Invoice Template, it can be [downloaded from here](https://screen-sharing-recording.techidaily.com/updated-uncomplicated-walkthrough-of-easy-iphone-screen-capture-for-2024/).

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
