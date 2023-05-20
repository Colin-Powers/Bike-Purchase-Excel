# Bike-Purchase-Excel

## About:
### In this project I use Microsoft Excel to clean and expolore bike purchase data. The gola of this project is to help a hypothetical bike business understand their customer base better.

## Cleaning the Data:
### The first step in cleaning the dataset was to remove duplicates by using the "Remove Duplicates" button found on the data tab, 26 duplicate values were found and removed. The next step was to replace the "M" and "S" values in the Marital Status column with "Married" and "Single" to eliminate any potential confusion. To do this I highlighted the "Marital Status" column and hit (Ctrl + h) on the keyboard to bring up the find and replace tool. I used to same process to replace the "M" and "F" in the Gender column with "Male" and "Female" and the "Yes" and "No" in the "Purchased Bike" column to "Purchase" and "No Purchase". After cleaning the Gender column I moved on to the Age data. I used IF statements to create three age ranges, "Young Adult (0-35)", "Middle Age (35-60)", and "Senior (60 +)" and placed them into a new "Age Bracket" column. This new column made it easier to understand and visualize how age plays a part in bike purchases later in the project.

## Creating Pivot Tables:
### For this project I created three different pivot tables with the goal of showing how the age, gender, commute distance, and income of a customer impacts if they purchase a bike or not. The age pivot table was created by placing "Purchased Bike" in the columns section, "Commute Distance" in the rows, and "Count of Purchased Bike" in the values section. I followed a similar process for the other two pivot tables I created.

## Creating the Dashboard:
### After creating all of the pivot tables I used the recommended chart tool to quickly create a visualization for each table. I then moved all of the visualizations to their own tab and added an additional three slicers, "Marrital Status", "Home Owner", and "Education" to allow users to dig even deeper into the data.

## Analysis:
### The work done by creating the Dashboard makes it easy for a user to answer a variety of questions. For instance, without applying any of the slicer filters to the charts you can see that middle aged men with a commute of less than a mile and a higher annual income purchase bikes at a much higher rate. By applying the slicer filters you can dig even further into this demographic.
