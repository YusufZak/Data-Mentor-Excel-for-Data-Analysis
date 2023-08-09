
# Data Preparation in Excel

The Excel Workbook ```CH_01.xlsx``` attached to this repository is used to demonstrate comprehensive data preparation in Excel.
The Workbook originally contains the following worksheets: ```PoorDesign```, ```Table Conversion```, and ```Table Formulas```.

## Installation

Only Microsoft Excel Software is needed to replicate the activities described in the Workbook ```CH_01.xlsx```
    
## Data Preparation

Data may come with blemishes that hinder its use for further analyses. some of these issues may include problems with encoding, poor formatting and inapropriate data types in columns of data.


 


### Step 1: Rectifying empty rows and columns

Check the worksheet for any hidden columns and rows. Hightlight the entire worksheet by ```CTRL+A``` or click on the upper left corner of the worksheet.

**Double click** on any row and column successively to unhide hidden rows and hidden columns respectively.

You may appropriately consider deleting empty rows and columns.

![Logo](https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Raw%20Data.PNG)

### Step 2: Shaping and Modifying Data
Depending on the purpose for the analyses to be performed, there may be a need for some columns to be split into different components. The most popular way is to deploy ```Flash Fill``` and/or the ```LEFT``` or ```RIGHT``` in combination with ```FIND``` functions in Excel.

***NB:***

    1. A new column needs to be inserted to the right of the column being split.
    2. Before deleting the original column(s), remember to duplicate the newly formatted columns by copying and pasting as values into the newly inserted column, to avoid field errors.

![Logo] (https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Flash%20fill%20using%20formular.PNG)

Flash filling from the ```RIGHT``` using formular:

![Logo](https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Flash%20fill%20using%20Right%20formular.PNG)



# Working In Tables
To convert a list or range of data into a table, from the ```Home``` tab click on any cell of a continuous worksheet then click on ```Format as Table``` to convert range of data to a table. You may need to adjust the cell range in the dialogue box to suite your purpose.

Description: For this we reference the ```Table Conversion``` worksheet. We will focus on the benefits of Table Referencing against Cell Referencing.

**Range Referencing**

![Logo](https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Aggregrate%20function%20Coulmn%20reference.PNG)

**Table Referencing**

Table referencing comes with many some advantages such as being able to directly reference column names in the range of the table as seen in the picture below:

https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Aggregrate%20function%20Table%20Reference.PNG

In some situations, the advantages of using Table Referencing becomes aparently clear, and the use of Range References will lead to the wrong results.

![Logo](https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Correct%20No%20Benefit%20count.PNG)

Column Reference counted all bank cells in the entire worksheet. While on the other hand the Table Reference is correctly within the range of the table.

https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Final%20Table%20formulas.PNG

**NB:** The right table name to be referenced can be found in the Top left corner of the ```Table Design``` tab as shown below:

![Logo](https://github.com/YusufZak/Data-Mentor-Excel-for-Data-Analysis/blob/main/Table%20reference.PNG)
