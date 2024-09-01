---
title: Ditch the Expensive Software - Mastering Project Management with Just Excel
date: 2024-08-27 10:10:35
updated: 2024-08-29 11:21:37
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/a-tablet-with-a-project-management-spreadsheet.jpg
---

## Ditch the Expensive Software - Mastering Project Management with Just Excel

### Quick Links

* [Use Drop-Downs](https://extra-hints.techidaily.com/easy-acquisition-of-individual-ending-music-files/)
* [Create Gantt Charts to Track Progress](https://facebook-record-videos.techidaily.com/streamline-your-audio-preferences-moving-spotify-playlists-to-youtube-music-for-2024/)
* [Create a Progress Tracker](https://remote-screen-capture.techidaily.com/the-fundamentals-of-synchronizing-audio-and-video-in-screencasts/)
* [Display Due Dates and Time Remaining](https://common-error.techidaily.com/solving-no-audio-output-devices-found-on-windows-11/)

 You might be tempted to browse the web for top-of-the-range programs to help you with your project management. But stop—I'm going to talk you through some of Excel's tools that you can use and reuse to efficiently manage your project without having to fork out for expensive software.

## 

##  Use Drop-Downs

 Drop-downs are a great way to speed up your work processes, and make your project management system more professional. First, create the options to appear when you click a drop-down cell. Click the "+" at the bottom of your workbook, and double-click the new tab to rename it **Options**.

![An Excel workbook with the New Tab '+' icon highlighted and a new sheet called 'Options' added.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/new-tab-options.png) 

 I need employee names and task status as drop-down options in my workbook, so I'll create the lists for these here.

![An Excel worksheet with two lists: Employee Names and Task Status.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/lists.png) 

 Now, create another sheet where the tasks will be managed and rename it **Tasks**.

 After creating a table with the task names on the left and an appropriate header at the top, select the cells that will contain the first drop-down with the options you just created on your Options sheet.

![An Excel worksheet containing a table with nine tasks on the left and the headings Assignee and Status at the top.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/select-cells-for-dropdown.png) 

 Next, in the Data tab on the ribbon, click "Data Validation."

![An Excel worksheet with the 'Data Validation' option selected.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/data-validation.png) 

 In the Allow field of the Data Validation dialog box, choose "List." Then, click the Source field arrow, head to your Options sheet, and select the appropriate values for this drop-down. In my case, it's the values underneath the Employee Names heading, and their cell references will then show in the dialog box field. Even though the list of names runs from A2 to A10 on our Options sheet, I've selected A2 to A100 for our data validation, as this means any new names I add to the list will also be picked. Finally, click "OK."

![Excel's Data Validation dialog box with 'List' selected in the Allow field, and the cell references for the values to appear in the drop-down list in the Source field.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/data-validation-options.png) 

 You will then see the list of names appear when you click any cell in the Assignee column.

![A column in Excel whose cell values are determined by drop-down options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/drop-down.png) 

 Now, repeat the process for the Status column, and anytime you want to add a drop-down list to your workbook, you can use and [hide your Options sheet](https://facebook-record-videos.techidaily.com/updated-optimize-and-upload-more-content-to-youtube/) to create the choices.

##  Create Gantt Charts to Track Progress

 A Gantt chart is a simple but effective table that shows you what task needs to be done in a project and when they need to be completed.

![A Gantt chart in Excel, with eight months along the top, nine tasks down the left, and different squares colored in according to the progress of the project.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/gantt.png) 

[Excel has tools for creating simple Gantt charts](https://program-issues.techidaily.com/pc-gamers-guide-to-resolving-multiversus-not-launching-top-tips-and-tricks/), but they are less adaptable than those created from scratch. Keep reading to see how to create a more dynamic Gantt chart.

###  Step 1: Mark Your Timings Manually

 Click "+" at the bottom of your workbook to create a new sheet, and call it **Timing**. On this new sheet type the tasks' names on the left and the months at the top. Next, map out your proposed timings using manual color fill. It doesn't matter what color you use, as this will be covered up later when we add more settings. Select the first cell you want to color, hold Ctrl, and then select the remaining cells. Then, go to the "Fill Color" drop-down in the Home tab on the ribbon and choose a color.

![A Gantt chart in Excel with certain cells colored black through the Color Fill option, which is displayed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/map-out-gantt-chart.png) 

###  Step 2: Color the Cells According to Progress

 I now want to color the cells according to their status. I'll do this by referring to the status I set for each task on the Tasks sheet set up in the section above. In the first colored cell of your Gantt chart, [use the VLOOKUP formula](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/):

=VLOOKUP(_x_,_y_,_z_)

 where _x_ is the cell reference in the chart you're looking up, _y_ is where Excel should look to find the corresponding value, and _z_ is the column number within the array.

 So, here's what I'll type into my first Gantt chart cell:

=VLOOKUP($A2,Tasks!$A$1:$C$1000,3)

 Because I have used [mixed and absolute references (using the $ symbol) within our formulas](http://www.howtogeek.com/excel-relative-absolute-mixed-references/), I can copy (Ctrl+C) and paste (Ctrl+V) this formula into the other colored cells.

 If you use a black color fill, use white font so that you can see the values against the black backgrounds.

![A Gantt chart in Excel with the status displayed in each colored cell through a VLOOKUP formula.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/gantt-chart-black.png) 

 Finally, use Conditional Formatting to color the cells based on the values they contain.

 Select all the cells in the Gantt chart, and in the Home tab on the ribbon, click Conditional Formatting > Manage Rules.

![The data in a Gantt chart in Excel is selected and the 'Manage Rules' option in Conditional Formatting is highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/conditional-formatting-manage-rules.png) 

 Click "New Rule" in the dialog box that appears, and create the following conditions (after you have set each one, click "OK" to set the next):

1. For each rule, set the Rule Type to "Format Only Cells That Contain."
2. Select "Specific Text" and "Containing" in the first two drop-down boxes.
3. In the text box, type **Done**, **In progress**, **Not started**, or **Changes required** for each rule you create (as these are the options in the VLOOKUP for these cells that we created in the previous step).
4. For each rule, format both the fill color and the text color to be the same—green for Done, yellow for In progress, and so on.

![An Excel worksheet with the conditional formatting dialog box and the different options highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/conditional-formatting-rules.png) 

 You will then see the relevant Gantt chart cells change color based on their status in the Tasks sheet.

###  Step 3: Highlight the Current Month

 Start by typing the first date of each month in short form where you originally typed the name of the month. So, for example, replace the text in the cell containing January with **01/01/2024**. Then, do the same for February, before [using AutoFill to complete the remaining months](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/). Doing this tells Excel that these are dates, and not just text. Next, change the font color of these dates to gray.

![A Gantt chart in Excel with the dates formatted to the first day of each month and the font color changed to gray.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/dates-formatted.png) 

 To turn these back into the names of the months, select all the dates, click the Number Formatting drop-down option in the Home tab on the ribbon, and click "More Number Formats."

![An Excel sheet with dates selected and 'More Number Formats' highlighted in the number formatting drop-down option.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/more-number-formats.png) 

 In the Format Cells dialog box, open the "Number" tab, and click "Custom" in the Category list. Then, in the Type field, type **MMMM**.

![The Format Cells dialog box with the Number tab opened, the 'Custom' category selected, and 'MMMM' typed into the Type field.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/month-number-formatting.png) 

 Then, click "OK" to see the result. To now make the current month stand out, select all the months in your Gantt chart, and click Conditional Formatting > New Rule. In the dialog box, click "Format Only Cells That Contain," select "Dates Occurring" in the first drop-down menu, and "This Month" in the second. Next, choose the formatting you want to use to make the current month stand out, such as black and bold text. Finally, click "OK."

![The Conditional Formatting dialog box with 'Dates Occurring' and 'This Month' selected, and the text formatted to black and bold.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/format-dates-this-month.png) 

 You now have your completed and dynamic Gantt chart with the progress displayed and the current month emphasized.

![A Gantt chart in Excel, with eight months along the top, nine tasks down the left, and different squares colored in according to the progress of the project.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/gantt.png) 

##  Create a Progress Tracker

 Using the Gantt chart created in the steps outlined above, you can now create a progress tracker. You can either do this on the same sheet as where your Gantt chart is located or on a new tab. In my case, I want to show how many squares in our Gantt chart are marked as Done, In progress, Not started, and Changes required, and then calculate an overall progress percentage.

![An Excel sheet containing a title 'Progress Tracker,' and 'Done,' 'In Progress,' 'Not started,' 'Changes,' and 'Progress %' underneath.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/progress-tracker.png) 

 To do this, I'll need to [use the COUNTIF function](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/), which follows this syntax:

=COUNTIF(_x_,_y_)

 where _x_ is the array to evaluate and _y_ is the criterion to count.

 So, for the Done count, we will type

=COUNTIF($B$2:$I$10,"Done")

* **$B$2:$I$10**—This references the cells in the Gantt chart [using an absolute reference](https://some-knowledge.techidaily.com/2024-approved-expert-techniques-for-enhanced-minecraft-zooms/) (notice the $ symbols).
* **"Done"**—Use the quotation marks to tell Excel you're looking to count the number of times this text string appears in the array.

 Then, copy and paste this formula for the remaining details in your progress tracker, changing value _y_ to match the value you're looking to count.

![An Excel sheet with a progress tracker and task status calculated using the COUNTIF function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/progress-tracker-values-complete.png) 

 Next, calculate the overall progress using the following formula:

=SUM(_a_/(_a_+_b_+_c_+_d_))

 Where _a_ is the number of cells in your Gantt chart containing the word Done, and _b_, _c_, and _d_ are the number of cells containing the other status markers. Remember to change the number format of this cell to a percentage.

![An Excel sheet containing a progress tracker, and the formula used to calculate the overall progress percentage is highlighted in the formula bar at the top.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/progress-tracker-overall-percentage.png) 

 With the cell containing the newly calculated percentage selected, in the Insert tab on the ribbon, click the Chart button highlighted below, and select a 2-D bar chart.

![An Excel sheet with a cell selected and a 2-D bar chart option highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/insert-2d-bar-chart.png) 

 Then, [format your chart](https://win11.techidaily.com/new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/) to remove any details you do not require, resulting in a progress bar showing your overall progress.

![An Excel sheet containing a progress bar.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/progress-bar.png) 

[Remove the gridlines](https://driver-download.techidaily.com/easy-guide-to-installing-amd-radeon-hd-7700-graphics-card-driver-updates/) to make your progress bar easier to read and look more professional.

##  Display Due Dates and Time Remaining

 As well as tracking your project's progress, you can also track the time elapsed and time remaining.

![An Excel sheet with a time tracker and various calculations numbered from one to six.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/excel-time-tracker.png) 

 1\. First, type the start and due date manually using a date format that suits your region. Excel will automatically convert this to a date format, and you can [amend the date format](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/) if required.

 2\. Next, add today's date by typing

=TODAY()

 and pressing enter.

 3\. Third, calculate the days elapsed so far using the following formula:

=SUM(_x_-_y_)

 where _x_ is the cell containing today's date, and _y_ is the cell containing the start date. Then, calculate the weeks elapsed by dividing the days elapsed by seven.

 4\. You can also calculate the days remaining with the following formula:

=SUM(_a_-_b_)

 where _a_ is the cell containing the due date, and _b_ is the cell containing today's date. Again, calculate the weeks remaining by dividing the days remaining by seven.

 5\. Then, create a percentage of the time passed with the following formula:

=SUM(_c_/(_c_+_d_))

 Where _c_ is the total number of days elapsed and _d_ is the total number of days remaining.

 6\. Finally, create a 2-D bar chart using the method described in the previous section.

---

 Now you've created the perfect spreadsheet for project management, consider [using Excel to help you monitor your budgets](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/)!

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
