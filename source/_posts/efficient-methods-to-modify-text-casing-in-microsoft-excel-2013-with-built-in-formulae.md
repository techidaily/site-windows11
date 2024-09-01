---
title: Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae
date: 2024-08-27 12:38:15
updated: 2024-08-29 12:52:38
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/00_lead_image_change_case.png
---

## Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae

You may find you need to change multiple cells from one case to another in Excel. Maybe you imported data that came in all upper case, or maybe you convert headings on columns to upper case. Changing case is easy using some special functions.

 There are three functions that allow you to change the case of text in multiple columns easily:

* \= Upper(B1) – converts text to all upper case
* \= Lower(B1) – converts text to all lower case
* \= Proper(B1) – converts text to proper case, or title case (the first letter of each word is capitalized)

 For our example, we will change two columns of first and last names in a sample address list. First, we want to insert a new column after the Last name column. To do this, highlight the column after which you want to insert the blank column by clicking on the lettered header, right-click on the header, and select Insert from the popup menu.

![01_inserting_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/01_inserting_column.png) 

 The new column is formatted the same way as the original column. In our example, we entered the title of the column in the gray highlighted cell at the top of the column. We will be deleting the original column once we’ve converted the case.

![02_entering_title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/02_entering_title.png) 

 In the first cell of the new column, enter the desired case function, with the cell reference in the parentheses, for the text you want to convert. In our example, we want to convert each name to title case, so we entered the Proper() function in the first cell in the column (below the heading row) with A2 as the cell reference.

 NOTE: Remember to preface your function with the equals sign.

![03_entering_formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/03_entering_formula.png) 

 Now, we need to propagate the function to the rest of the cells in the column. To do this, select the cell containing the case function and click Copy in the Clipboard section of the Home tab or press Ctrl + C.

![04_clicking_copy](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/04_clicking_copy.png) 

 Highlight the remaining cells in the column and click Paste or press Ctrl + V.

![05_clicking_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05_clicking_paste.png) 

 TIP: You can also quickly copy the contents of a cell into the remaining cells in the column by double-clicking the box on the lower, right corner of the cell.

![05a_double_click_box_to_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05a_double_click_box_to_paste.png) 

 Each of the cells in the new column look like they contain the names in a different case. However, each cell still contains the Proper() function referring to another cell. Because we are planning to delete the original column, we need to replace the function with the actual name to which it evaluates. To do this, highlight all the cells in the column containing the function and copy them.

![06_formula_still_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/06_formula_still_in_cells.png) 

 To paste the values back into the same cells, click the down arrow on the Paste button in the Clipboard section of the Home tab. Then, click Values in the Paste Values section.

 NOTE: This is the same procedure we discussed in a previous article about [converting a numerical formula to a static value](https://article-posts.techidaily.com/decoding-the-art-of-enhanced-perception-for-2024/).

![07_pasting_values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/07_pasting_values.png) 

 Now, all the cells in the column should contain text, not functions.

![08_names_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/08_names_in_cells.png) 

 To delete the original column, select the entire column by clicking the lettered header, right-click on the header, and select Delete from the popup menu.

![09_deleting_original_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/09_deleting_original_column.png) 

 To convert the first names to title case, we followed the same procedure.

![10_both_columns_fixed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/10_both_columns_fixed.png) 

 It’s that easy to tidy up your text. These case functions will also work if the case of the text is jumbled (e.g., bUFfEt).

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
