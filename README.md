# Kickstarting with Excel
## Overview of Project
Here, we will be visualizing the relationship between campaign outcomes and campaign launch date for Kickstarter fundraising campaigns for plays. We will also be visualizing the relationship between campaign outcome and campaign goals. We will provide an overview of the analysis method used and any challenges faced. Lastly, we will discuss the conclusions that can be drawn from the analysis and its limitations.
### Purpose
The purpose of this project is to provide an analysis of fundraising campaigns for plays on Kickstarter and determine the relationship between campaign outcome and campaign launch date and funding goals, if any.
## Analysis and Challenges
- Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.
### Analysis of Outcomes Based on Launch Date
To examine the relationship between campaign outcome and launch date, we:
1. Determined the year the campaign was launched by extracting the year from the "Date Created Conversion" via the YEAR() function. This will allow us to later filter our PivotTable by the year the campaign was launched.

      ![README-report_resources/README-Report_YEAR.PNG](https://github.com/lexyzhong/kickstarter-analysis/blob/main/resources/README-report_resources/README-Report_YEAR.PNG)

2. To create a PivotTable and PivotChart, we selected all the data from the KickStarter worksheet and under the Insert tab, selected "PivotChart & PivotTable", we choose to place it into a "New Worksheet" that we later named "Theater Outcomes by Launch Date", and clicked "OK".

      ![README-Report_PivotTable-PivotChart.PNG](https://github.com/lexyzhong/kickstarter-analysis/blob/main/resources/README-report_resources/README-Report_PivotTable-PivotChart.PNG)

3. The PivotTable Fields were populated as shown below. To display only months in the row labels, the highlighted row fields, which are added by default if you select "Date Created Conversion", were removed:

    ![README-Report_PivotTable-Fields-2.PNG](https://github.com/lexyzhong/kickstarter-analysis/blob/main/resources/README-report_resources/README-Report_PivotTable-Fields-2.PNG)

4. The column labels were then filtered to hide the data for "live" campaigns.

      ![README-report_resources/README-Report_filter-outcomes.PNG](https://github.com/lexyzhong/kickstarter-analysis/blob/main/resources/README-report_resources/README-Report_filter-outcomes.PNG)

5. The "Parent Category" was filtered to only show data for "theater" campaigns. 
6. The campaign outcomes were reorganized so that "successful" outcomes appeared first. 
7. Lastly, a line chart was created from the PivotTable and formatted and titled "Theater Outcomes Based on Launch Date".

    ![README-Report_Parent-Category-filter_successful-sort_PivotChart-2.PNG](https://github.com/lexyzhong/kickstarter-analysis/blob/main/resources/README-report_resources/README-Report_Parent-Category-filter_successful-sort_PivotChart-2.PNG)

### Analysis of Outcomes Based on Goals
### Challenges and Difficulties Encountered
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
- What can you conclude about the Outcomes based on Goals?
- What are some limitations of this dataset?
- What are some other possible tables and/or graphs that we could create?
