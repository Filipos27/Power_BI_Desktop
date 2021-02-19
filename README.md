# Power_BI_Desktop

## Project structure
### 1. Cleaning dataset
  Before we start to visualize our dataset we want our dataset to be clean and without incorrect informations. We can  do that by clicking on "Data   Transform" and after clicking the new window will show where we can do our cleaning  and other changes. For example  we can  remove all rows which have null values. We need to inspect every column and try to find any values that are incorrect. We can also make new columns with combined values of other columns. After we are satisfy with changes we have done, we click on "Apply&Close" button.
### 2. Measure
  After cleaning dataset we want to make measures that will show us stats of certain column. In this case we made measures for revenue,quantity,year, month,day etc. To make measure we need to click on "New measure" and we write down dax function that we want. For example in this case for revenue we used function: Revenue=SUM(Global_Store[sales]). Global_Store is name of our dataset and sales is the name of column. After measures are made they show up in "Field" field and we just drag them into our report canvas.
  
  ### 3. Visualizations
  When measures are draged we can now use "Visualizations" field and experiment. We can make bar plots,pie charts,cards with number,list etc. Also in "Visualization" field we have option "Format" where we can change colors,title,numbers,size and a lot of other things of our visualize element.
  
  
# Result

![6](https://user-images.githubusercontent.com/77289083/108523076-cd1ca200-72cd-11eb-8887-6b248904dacd.png)
