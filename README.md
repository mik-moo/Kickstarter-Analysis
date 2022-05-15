# Kickstarter Challenge Report

## Project Overview

Data Analysis and conclusions from the Kickstarter data set in regards to play fundraising campaigns when analyzing their success related to their launch dates and funding goals.

Overall, the campaigns launched in May were most successful and the lower goals fared better than higher goals.  

### Purpose

Determine how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

- Categorized outcome data with conditional formatting.

![conditional formatting screen capture](Resources%5CConditional_Formatting_Outcomes.PNG)

- Converted launch date and deadline to mm/dd/yyyy format and pulled the launch year to a separate column.

- Separated Category and Subcategory into separate columns for use in analysis.

- Charted Theater outcomes based on launch month over all years in the data set.

- Charted outcomes based on percentage successful, canceled, and failed vs funding goal ranges.

- Charted number successful, canceled, and failed vs funding goals.

### Analysis of Outcomes Based on Launch Date

- Created a pivot table comparing successful, failed and canceled campaigns by month.  These were filtered by the subcategory theater.  These were then charted in a line graph. 

![Theater Outcomes vs Launch](Resources%5CTheater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

- Created Goal categories and percentage sucessful, percentage failed and percentage canceled of the total plays subcategory.  These are presented in a line graph. 

![Outcomes vs Goals](Resources%5COutcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Finding the most meaningful way to offer conclusions based on the percentage vs number successful vs the funding goals was difficult.  Determining where the trends make sense and where they do not apply to the data was challenging. Consider expanding the data set for larger goals to include more projects, especially in the higher range if possible, to determine if the trend at the lower goals applies to the higher goal projects.  With the current data set, these higher campaigns are such small sample sizes and a meaningful analysis past the goal range of 10-15K isn't possible. There are a lot of variables that go into success and failure.  Maybe we could also narrow down the variables to see how they affected the outcome.

## Results

Plays launched with Kickstarter are overall successful no matter the launch date with the exception of December which was almost equal failed vs successful. May was the most successful launch month, with June and July above average also.

When looking at the outcomes vs goals percentages, they are directly inverse to each other and are about 50% average for the rates. Looking at the number of campaigns in the higher range, this data appears to be skewed.  Consider looking at other factors with the data for a more meaningful conclusion. There is more data for the lower goals, in which more campaigns were successful than failed.

Based on the dataset, there is a lack of informative data in the higher goal ranges. Either there aren't many plays that fall in that category, or there is missing data. In addition, if we have other information specific to the play subcategory, like genre of play, how the funding was presented, or how the funding was to be used, it could lend valuable information for Louise's campaign.

An additional analysis could compare the number instead of percentage for success, failure, and canceled.  This would help to determine the trend lines.  This shows the lack of campaigns in the higher ranges and makes it more evident that they may be under-represented in the dataset.

![Outcomes vs goals using number](Resources%5COutcomes_vs_Goals_Number.png)