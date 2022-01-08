#Kickstarter Analysis

Kickstarter campaigns make ideas into reality. It’s where creator share new visions for creative work with the communities that will come together to fund them.

##Project Overview

In this project, an analysis of Kickstarter campaigns for various theatre plays has been conducted to determine whether the length of a Kickstarter campaign contributes to its ultimate success or failure.

###Analysis and Challenges

The analysis completed for this project consist of two main deliverables: outcomes based on launch date and outcomes based on goals.

Analysis of Outcomes Based on Launch Date

• In data analysis of "the outcomes based on launch dates", it is observed that most of the successful campaigns were launched in the months of May & June. In the month of December, the chances of success and failure were same.

• To complete this analysis, A pivot table was created using the data on Kickstarter to look specifically at the 'theater' category, the launch date of each campaign, and the outcome of those campaigns. To do this, “parent category" and "years" were used as filters, the "launch date" as rows, and "outcomes" as values and columns. After compiling the data in the pivot table, A line chart was created to show the outcomes based on the month that each campaign was started. See chart below.

![image](https://user-images.githubusercontent.com/95595378/148652050-63aeb09e-b599-4ee0-96ca-dbcedc7527a9.png)

Analysis of Outcomes Based on Goals

• In data analysis of "the outcomes based on goals”, it is observed that the lower the amount of the campaign goal, higher is the chance of its success. For example, most of the successful campaigns have the goal amount less than $5000. It can also be observed that higher goal target increases its chances of failure. For example, the campaigns whose goal amount is more than $45000 are more prone to failure. The campaigns whose goal amount ranges between $10000 to $25000 have 50 percentage chances of either success or failure.

• To complete this analysis, I used the COUNTIFS () function to pull the number of successful, failed, and canceled campaigns for 12 different dollar-amount ranges. Also calculated the total amount of campaigns for each dollar-amount range by using the SUM (). Then calculated the percentage of successful, failed, and cancelled campaigns. Finally created a line chart to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. See chart below.
![image](https://user-images.githubusercontent.com/95595378/148652072-1645e890-1c31-4756-afed-eff16f694b62.png)

Challenges and Difficulties Encountered
The chart “Outcome based on goals" visualizes the percentage of successful, failed and canceled plays based on the funding goal amount. The most difficult step in displaying this chart was Grouping the “Row Labels” Column to show the specific timeline and using “COUNTIFS ()” function to populate the number of successful, failed and canceled campaign based on the funding goal amount.All these challenges were overcome by simple google searches to figure out the best way to fix each challenge.

####Results
What are two conclusions you can draw about the Outcomes based on Launch Date?

•From the Kickstarter campaigns data analysis, we can say that the length of campaign contributes to its ultimate failure in most of the cases where the duration of the campaign is more than 30 days.

•The most successful Kickstarter campaigns were starter in May. On other hand, December doesn’t seems like a great time to launch the campaign.

What can you conclude about the Outcomes based on Goals?

•The goal amount plays a key role in the success or failure of the campaign, lower the goal amount higher is the chances of success. But some goal ranges like the one between $10000 to $25000 are susceptible to both failure and success depending upon other factors.

What are some limitations of this dataset?

•The given data should consists of the status of the canceled projects whether they will be re-launched or dropped forever. The status of the live projects is also not clear. We can also include some categories like art, comics and fashion to broaden the area of coverage of the population of these Kickstarter Campaigns. Also, we can include the columns like backer’s
reward or share from profit making (successful) campaigns. To have more in-depth analysis we can also include the ethnicity of the people to launch some specific campaigns.


