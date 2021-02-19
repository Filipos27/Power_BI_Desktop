# Power_BI_Desktop

## Project structure
### 1. Cleaning dataset
  Before we started to visualize our dataset we wanted to see if there are our valeus,dataset clean and without incorrect informations. We can do that by clicking on "Data   Transform" and after clicking the new window will show where we can do our changes. For example  we have to remove all rows which has null values. We need to inspect every column and try to find any values that are incorrect. We can also make new columns with combined values in other columns. After we are satisfy with changes we've done we click on "Apply&Close" button.
### 2. Measure
  After cleaning dataset we want to make measures that will show us stats of certain column. In this case we made measure for revenue,quantity,year.month,day etc. Do make measure we need to click on "New measure" and we wrote dax function that we want. For example in this case for revenue we used function: Revenue=SUM(Global_Store[sales]). Global_Store is name of our dataset and sales is the name of column. After measures are made they show up in "Field" field and we just drag them into our report canvas.
  
  ### 3. Visualizations
  When measures are draged we can now use "Visualizations" field and experiment. We can make bar plots,pie charts,cards with number,list etc. Also in "Visualization" field we have option "Format" where we can change colors,title,numbers,size and a lot of other things of our data.
  
  
# Result
