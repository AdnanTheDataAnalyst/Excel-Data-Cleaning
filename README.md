# Welcome!

👋 Hello there! Welcome to my corner of the digital world. I'm Adnan, and I'm thrilled to have you here.

🔍 As a dedicated data analyst, I've honed my skills in the art of deciphering the language of numbers and translating raw data into meaningful insights. One of my key strengths lies in my proficiency with Microsoft Excel, a tool I consider my data analysis companion.

## Excel Skills at a Glance:

### Data Cleaning and Transformation:
This is a raw dataset that has several errors, to a clean dataset that I need to present to my team. For this, I use the following steps such as text to columns and remove dupilcates, and several formulas such as the trim, proper, lower,  iferror and more. 
   1. Autofit Rows and Columns
      - Problem: Long rows
      - Solution: Hit CTR + A, Go to Format and hit Autofit Row Height (or Use this ShortCut Alt + H + O + I) and Auto Fit Column Width (or Use this ShortCut Alt + H + O + 
   3. Find & Replace
      - Problem: Unnesscssay Info
      - Solution:
           - Remove unnessacay info within parathesis by selection the whole column and then going to Find & Select and choosing Replace tool (or Use this ShortCut CTRL + H).
           - To remove anything with the parathensis, type (*)
           - Hith Replace All. Hit ok, then hit close
   6. Lower
      - Problem: All text is Uppercase which makes it hard to read
      - Solution:
           - Create new column by hitiing CTRL  Shift Plus
           - Use this function '=LOWER', Then click on the cell you want to convert
           - To make changes on all rows in the same column, double click to drag down all the way to the buttom.
           - Before you delete the old column
                - First click on the comlumn you converted and click CTRL Shift Down and then CTRL C
                - Go to paste and choose paste it as a value (or Use this ShortCut Alt  H  V  V)
                - Delete the colunm that you do not want or the old column by hitting CTRL Minus
   8. Trim & Proper
      - Problem: Odd spacing and capitalization
      - Solution:
        - Create new column by hitiing CTRL  Shift Plus
        - To remove spacing, type this function '=TRIM' in the cell
        - To make changes on all rows in the same column, double click to drag down all the way to the buttom.
        - To remove random capitalization, type this function '=PROPER' in the cell
        - OR use this function together '=TRIM(PROPER(Click on the cell you want to change)'
        - Before you delete the old column
                - First click on the comlumn you converted and click CTRL Shift Down and then CTRL C
                - Go to paste and choose paste it as a value (or Use this ShortCut Alt  H  V  V)
                - Delete the colunm that you do not want or the old column by hitting CTRL Minus
   10. Text to Columns
       -Problem: Too many info in one column. Both the department and the state info are in one column.
       - Solution: Separate departmeninfo from region: 
            - Create new column by hitiing CTRL  Shift Plus and name it Region
            - Click on the comlumn you converted and click CTRL Shift Down to select all rows
            - Go to Data, choose Text to Columns
            - Click Next
            - Click inside the box for Tabs and Other and put underscore'-' in Other
            - Make sure the destination is correct
            - Then click Ok
   14. Removing Duplicates
       -Problem: Too much duplicate info
       - To remove duplicate values, CTRL A
       - Go to Data, choose Remove Duplicates and then hit ok
   16. Filling Empty Cells
       - Problem: Blank rows
       - Solution:
       - Select the whole table by hitting CTRL A
       - Under Home, go to Find & Select and choose "Go to Special"
       - Choose Blanks and hit ok
       - Then hit on any empty cell and type 'NA' and hit CTRL ENTER
   18. IFERROR
      - Problem: Under Profit Margin column where profit is divided by revenue, some rows have 'NA' which gives error sign
      - Solution:
          -In the cell, type =IFERROR(put the cells you want to divde and put coma.
          - After coma, type inside double quatation marks "NA".
          - For example, the formula would be =IFERROR(M4/N4,"NA")and hit enter.
   20. Formatting
   21. Gridlines

1. **Data Used:** Sales and inventory records
2. **Problem:** Inconsistent data formats and missing values affecting analysis accuracy.
3. **Solution:**
   - Downloaded raw sales and inventory records from the company's database.
   - Applied text-to-columns to standardize formats (e.g., dates, text).
   - Utilized find-and-replace functions to correct common data entry errors.
   - Filled missing values using appropriate methods (e.g., average, interpolation) for a cleaner dataset.


### Data Wizardry:
1. **Data Used:** Customer transaction records
2. **Problem:** Duplicates in the dataset leading to inaccurate customer profiles.
3. **Solution:**
   - Downloaded raw customer transaction data from the CRM system.
   - Identified duplicate entries using conditional formatting based on key attributes (e.g., customer ID).
   - Created a new, clean dataset by removing duplicate entries.
   - Ensured accuracy in customer analysis by working with the cleaned dataset.

### Formula Maestro:
1. **Data Used:** Sales and revenue data
2. **Problem:** Need for a dynamic way to calculate profit margins based on changing costs.
3. **Solution:**
   - Downloaded raw sales and cost data from the accounting system.
   - Developed dynamic formulas incorporating variables for revenue and cost.
   - Implemented IF statements to handle varying cost scenarios.
   - Achieved real-time profit margin calculations as costs fluctuated.

### PivotTable Prodigy:
1. **Data Used:** Monthly sales data by product category
2. **Problem:** Cumbersome raw data requiring quick summarization and trend identification.
3. **Solution:**
   - Downloaded monthly sales data from the company's database.
   - Created PivotTables for each product category, summarizing sales data.
   - Grouped data by month for trend analysis.
   - Facilitated better decision-making through visually clear and concise summaries.

### Visualization Virtuoso:
1. **Data Used:** Marketing campaign performance metrics
2. **Problem:** Communicating campaign success to non-technical stakeholders.
3. **Solution:**
   - Downloaded marketing campaign performance metrics from analytics platforms.
   - Utilized Excel's charting capabilities to create visually appealing charts.
   - Selected appropriate chart types (e.g., bar charts, pie charts) for different metrics.
   - Added data labels and annotations to enhance communication.

### Problem-Solving with Excel:
1. **Data Used:** Complex financial datasets
2. **Problem:** Optimization challenge in resource allocation.
3. **Solution:**
   - Downloaded raw financial datasets from accounting and project management systems.
   - Applied Solver tool to the financial model.
   - Defined optimization objectives, constraints, and decision variables.
   - Solver iteratively adjusted variables to achieve the optimal resource allocation, maximizing efficiency and minimizing costs.

### Formulas and Functions:
1. **Data Used:** Budget and expenditure data
2. **Problem:** Need for automated calculations of variance and percentage change.
3. **Solution:**
   - Downloaded budgeted and actual expenditure data from financial systems.
   - Implemented IF statements to detect variances between budgeted and actual values.
   - Utilized nested functions to calculate percentage changes.
   - Achieved real-time insights into budget performance with automated formulas.

### PivotTables:
1. **Data Used:** Customer feedback survey responses
2. **Problem:** Large dataset making it challenging to extract meaningful insights.
3. **Solution:**
   - Downloaded raw survey response data from the feedback collection platform.
   - Created PivotTables to summarize feedback by category (e.g., product features, customer service).
   - Filtered and sorted data within PivotTables for targeted analysis.
   - Extracted actionable insights by leveraging PivotTable functionalities.

### Data Analysis with Charts:
1. **Data Used:** Monthly sales figures
2. **Problem:** Communicating sales trends to the sales team.
3. **Solution:**
   - Downloaded monthly sales figures from the company's sales database.
   - Developed line charts with trendlines to visualize sales trends.
   - Added annotations to highlight significant events or milestones.
   - Improved communication of sales performance over time through effective charting.

### Conditional Formatting:
1. **Data Used:** Project timeline data
2. **Problem:** Identifying critical milestones and deadlines.
3. **Solution:**
   - Downloaded project timeline data from project management software.
   - Applied conditional formatting to highlight critical dates.
   - Utilized color scales for visualizing project progress.
   - Improved project timeline visibility through strategic application of formatting rules.

### Data Validation:
1. **Data Used:** Employee data for training programs
2. **Problem:** Ensuring accurate data entry for employee training records.
3. **Solution:**
   - Downloaded employee data from the HR system for training programs.
   - Set up dropdown lists for standardized data entry.
   - Defined custom validation rules to prevent errors (e.g., valid date ranges, required fields).
   - Enhanced accuracy and consistency in employee training records.

### Named Ranges:
1. **Data Used:** Financial forecasting data
2. **Problem:** Streamlining complex formulas with large data ranges.
3. **Solution:**
   - Downloaded financial forecasting data from forecasting tools.
   - Created named ranges for key variables in the financial model.
   - Used named ranges in formulas, simplifying formula writing.
   - Improved spreadsheet readability and maintenance through structured naming conventions.

### Advanced Filtering:
1. **Data Used:** Product inventory data
2. **Problem:** Extracting specific product categories and analyzing inventory levels.
3. **Solution:**
   - Downloaded product inventory data from the company's inventory management system.
   - Applied advanced filter options to extract data for specific product categories.
   - Utilized complex criteria for filtering by attributes such as product type, quantity, and demand.
   - Efficiently extracted and analyzed targeted data for inventory management.

### Power Query (Get & Transform Data):
1. **Data Used:** External sales data from multiple sources
2. **Problem:** Merging and cleaning diverse datasets for comprehensive analysis.
3. **Solution:**
   - Downloaded sales data from various external sources.
   - Imported data into Power Query.
   - Merged and appended queries to create a unified dataset.
   - Cleaned and shaped data using Power Query Editor, ensuring consistency and accuracy.

### Analysis ToolPak:
1. **Data Used:** Survey response data for statistical analysis
2. **Problem:** Conducting advanced statistical analyses without programming.
3. **Solution:**
   - Downloaded survey response data from survey platforms.
   - Enabled Analysis ToolPak to access additional statistical functions in Excel.
   - Applied statistical tests (e.g., t-tests, ANOVA) to gain insights from survey responses.
   - Conducted comprehensive statistical analysis without the need for extensive coding.

### Scenario Manager:
1. **Data Used:** Financial projections data
2. **Problem:** Evaluating various financial scenarios for decision-making.
3. **Solution:**
   - Downloaded financial projections data from the financial planning tool.
   - Utilized Scenario Manager to create and manage multiple scenarios.
   - Defined input values and associated scenarios for what-if analysis.
   - Compared outcomes and made informed decisions based on different
