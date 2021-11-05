# Excel Kickstarter Analysis

## Overview
Louise is in charge of many fundraising kickstarters in several different industries, but is unable to determine why some projects succeed and others fail.  

### Purpose
Louise wanted a detailed analysis of her sizeable fundraising kickstarters, so I was hired to determine why they succeeded or failed. I compared kickstarters based on their launch dates, fundraising goals, industry "parent categories" and subcategories, as well as the country the fundraiser was occurring.

## Analysis and Challenges
To begin, I looked at successful and failed kickstarters within the US. I created descriptive statistics for the fundraising goals vs what was pledged, including mean, median, standard deviation, and interquartile range.  

![image](https://user-images.githubusercontent.com/92554586/140435177-ddc161c6-d9bd-40cb-abf0-15603eae3b1a.png)

As you can see above, the mean goal for failed US kickstarters was double that of successful ones. The standard deviation for failed kickstarters was also much higher due to some extraordinary outliers skewing the data. The interquartile range (IQR) also displays how the goals for failed kickstarters were unrealistic because of how varied they were. There was no logic in determining how much money was actually required to make a project succeed, so there was little funding pledged due to the lack of direction, or disinterest in the category as shown in the next chart.

The chart below displays the overall results of each parent category within the US:

![Parent_Category_Outcomes](https://user-images.githubusercontent.com/92554586/140440811-3d2aa32e-3a3f-4d8f-ab8c-9044d30d51bc.png)

The theater category had the most successful kickstarters, but also a high amount of failures. Music is the next most succesful category, and journalism had the least activity.

### Analysis of Outcomes Based on Launch Date

The chart below shows the overall outcomes of all categories based on when they were launched:

![Outcomes_Based_on_Launch_Date](https://user-images.githubusercontent.com/92554586/140441839-4af0936d-a2d0-4e98-a716-9683e959b226.png)

The main points from this chart are:

The most successful kickstarters began in summer months with May being the high point. Canceled kickstarters stayed relatively level across all months - the launch date was not a factor in why they were canceled. The least amount of failed kickstarters were in February to April, so these were likely the safest months to start certain categories.

### Analysis of Outcomes Based on Goals

The chart below displays the overall percentage of success, failure and cancelation across all categories based on their fundraising goal:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92554586/140442686-07a0913d-53c5-434e-ac63-82e2711779fc.png)

The main takeaway from this chart is that in most cases, the most successful kickstarters have modest fundraising goals. The higher the goal, the higher chance for failure. 

### Challenges and Difficulties Encountered

The biggest challenge I encountered was finding the best method to depict the outcomes vs goals data, i.e. when to use a pivot chart or a standard chart. I overcame this by trying both methods and learned it's not always necessary to pivot data if it's already meaningful. 

## Results

The chart below shows the outcomes based on launch date of the category Louise is most interested in, theater:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92554586/140443256-e367e0e8-24e6-4fa5-9dce-44b8df39fd27.png)

The main conclusions here are:

Summer months, especially May, yield the highest success rate. Summer months have the most steady rate of failed kickstarters, which again shows how it's the safest time of year to launch a theater kickstarter. January through April have lower failures, but also much fewer successes.

The goals of the kickstarters were a huge factor in determining success rate. When goals were realistic, kickstarters could be launched much easier. Some limitations of the data, however, are that the level of planning for each kickstarter is unknown. All that was given was the end result of what the goal was, how much was pledged, etc. The failed kickstarters with high goals may have had a realistic goal based on what was required, but were simply poorly executed. Additional descriptive statistics could have been done for each country to show whether certain countries had higher success with higher goals, or more failures. Certain countries may have had more success with particular categories, which could have been obtained from the subcategory statistics pivot table. 
