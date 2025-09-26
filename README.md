# Steps to Analyze Income Variance from Scratch
### 1. Transferred data to a new sheet that contains 3000 employees data including many characteristics
### 2. Made headings bold
### 3. Space adjustment for each cell to read the information completely
### 4. Applied filters on all headings/ columns
### 5. Used filters to catch any missing or null values
### 6. Detected 636 unique job titles using remove duplicate function on job title column
### 7. Removed unimportant variables like date of birth, phone, address, city, zip code, country, years of experience status from base pay and variance tabs
### 8. Divided the salary by 12 to get per month income on Desired Salary  column by creating a new column as Base Pay
### 9. Changed cell formating to number to get a dollar symbol
### 10. Adjusted for decimals by removing decimals for simplification
### 11. Added the borders on entire table
### 12. Created another sheet by copying same data including a new column named Actual Pay
### 13. Deliberately changed the actual income for some employees randomly by using IF function to subtract 1000 if pay is less than 3000 and greater than 5000 to get income variance for the sake of analysis
### 14. Copied all values for Actual Pay and pasted as values so base pay column deletion won't delete the newly created values in actual in variance tab
### 15. Now that we have Actual Pay, we created a new column as Base Pay and used VLOOKUP function to extract base pay using App ID as a look up value
### 16. VLOOKUP was used on Base Income Tab
### 17. Created another column Variance to get income variance and computed the difference between base pay and actual pay
### 18. Created last column as Yes and No for identifying variance using conditional formatting and highlighted if there is a variance (Yes)
### 19. Corrected date format in application date column under format cell setting
### 20. Summary Statistics - maximum/ minimum/ average of actual salary
### 21. Pivot Table summary - segregated income by gender with totals
### 22. Visual representation of salary variance

# Shuffled Variance File
### 1. Shuffled the data under variance table to show disordered data for fetching the exact match
### 2. Removed more columns in both tabs to alter the VLOOKUP formula but to display accurate results
### 3. Results are still accurate assuming that only 500 employees got paid from a total 3000 list
### 4. Used FREEZE option to freeze headings while scrolling down the list
### 5. This file shows VLOOKUP is still the best function to match the exact employee salary targeting App ID by "fixing" some values in the formula marked by a $ sign
### 6. Same operation can be performed using INDEX and MATCH functions that I will upload in near future

