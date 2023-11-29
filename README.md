# Data Cleaning and Transformation:
This dataset started with numerous errors, necessitating a transformation into a clean format for presentation to my team. The following steps were undertaken, each addressing specific issues and culminating in a refined dataset:

#### 1. Autofit Rows and Columns
   - **Problem:** Long rows
   - **Solution:** 
     - Selected all (CTRL + A), went to Format, and chose Autofit Row Height (Alt + H + O + I) for rows and Autofit Column Width (Alt + H + O + C) for columns.
   - **Result**: Resolved long rows, significantly enhancing overall readability.

#### 3. Find & Replace
   - **Problem:** Unnecessary Info
   - **Solution:**
     - Removed unnecessary info within parentheses by selecting the whole column, using Find & Select, and employing the Replace tool (CTRL + H).
     - Typed (*) to remove anything within parentheses, clicked Replace All, then closed.
     - Result: Enhanced data clarity by eliminating unnecessary information.

#### 4. Lower
   - **Problem:** All text is Uppercase, making it hard to read
   - **Solution:**
     - Created a new column (CTRL + Shift + Plus) and used '=LOWER' to convert text to lowercase.
     - Before deleting the old column:
       - Copied the converted column (CTRL + Shift + Down, then CTRL + C).
       - Pasted as Values (Alt + H + V + V).
       - Deleted the old column (CTRL + Minus).
   - **Result:** Improved readability by transforming all text to lowercase.

#### 5. Trim & Proper
   - **Problem:** Odd spacing and capitalization
   - **Solution:**
     - Created a new column (CTRL + Shift + Plus).
     - Used '=TRIM' to remove spacing and '=PROPER' to address random capitalization.
     - Alternatively, used '=TRIM(PROPER(Click on the cell you want to change))'.
     - Before deleting the old column:
       - Copied the converted column (CTRL + Shift + Down, then CTRL + C).
       - Pasted as Values (Alt + H + V + V).
       - Deleted the old column (CTRL + Minus).
   - **Result:** Ensured uniformity and coherence in the dataset.

#### 6. Text to Columns
   - **Problem:** Too much info in one column (department and state).
   - **Solution:**
     - Created a new column (CTRL + Shift + Plus) named Region.
     - Highlighted all rows I want to sparate.
     - Went to Data
     - Used Text to Columns to separate department and state information.
     - Clicked Next on the first prompt.
     - In the second prompt, I put underscore (_) and clicked finish.
   - **Result:** Enhanced data organization by splitting information into distinct columns.

#### 7. Removing Duplicates
   - **Problem:** Too many duplicate values
   - **Solution:**
     - Removed duplicate values by selecting all (CTRL + A) and using Remove Duplicates.
   - **Result:** Streamlined the dataset by mitigating redundancy.

#### 7. Filling Empty Cells
   - **Problem:** Blank rows or missing info
   - **Solution:**
     - Selected the entire table (CTRL + A).
     - Used Find & Select, "Go to Special" to select blanks (or CTRL + G, choose Speacial, check on Blanks) and filled them with 'NA' (CTRL + ENTER).
   - **Result:** Filled empty cells with 'NA,' ensuring a more comprehensive dataset by addressing missing values and maintaining data integrity..

#### 8. IFERROR
   - **Problem:** 'NA' errors in the Profit Margin column.
   - **Solution:**
     - Used '=IFERROR' to handle 'NA' errors in the Profit Margin column.
   - **Result:** Prevented disruptions in calculations caused by 'NA' errors.

#### 9. Formatting
   - **Format Headers and Rows:**
     - Highlighted headers (CTRL + SHIFT + Right) and made them bold (CTRL + B).
     - Changed colors using theme colors under Home.
   - **Result:** Enhanced visual appeal for improved presentation.

#### 10. Gridlines
   - **Problem:** Distracting grid lines
   - **Solution:**
     - Unchecked Gridlines in View (or Alt + W + V + G).
   - **Result:** Reduced distraction by hiding grid lines, improving focus on the dataset's content.

Finally, this comprehensive data cleaning and transformation process resulted in a polished dataset, making it more presentable, user-friendly, and conducive to effective analysis by the team.

 
 
 
