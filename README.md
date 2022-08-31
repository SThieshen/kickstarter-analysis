# **Kickstarting with Excel**

## Overview of Project

          With this project, analysis was performed on Kickstarter data to uncover trends to help determine characteristics of successful 
     crowdfunding campaigns. Overall analysis included determining trends that indicated increased success with a campaign, including 
     campaign type, goal of campaign, launch and end dates, number of backers, amounts pledged, and location of campaign launched. This 
     information allowed us to determine which factors increased likelihood of a successful crowdfunding campaign.
          
## Purpose
         
          The purpose of this project was to help an up-and-coming playwright, Louise. She wanted to start a crowdfunding campaign
     to help fund her play, *Fever*. Louise originally planned a budget of over $10,000, but was hesitant to start the campaign
     without more information. She wanted input from an Excel power user, for help, in hopes of being successful at crowdfunding
     her play. Within this analysis, we were able to determine certain factors and trends that led to success with a campaign and
     provide useful information to Louise, to help her make a more informed decision regarding the fundraising for her play.

## Analysis and Challenges
          
          The data we analyzed for Louise, originated from a large data set that required effort to make sense from, just due
    to the sheer volume of data provided. First, we determined, based on the category of the fundraising event if crowdfunding
    a play would even be a good idea. Fortunately for Louise, the theater/play category had some of the best crowdfunding
    results! Although the data set did provide outcomes of each campaign, meaning if it succeeded or failed, we were still interested
    in seeing the percentage of funding received in each campaign, if it went over its goal or came close to reaching it. This required
    dividing the amount pledged by the goal. This provided us insight on campaigns that exceeded goals, as well as ones that, while 
    labeled 'failed', were close to their established goal. One specific challenge encountered with the data set, was the 
    formatting for the deadline and launched dates, which were Unix timestamps rather than dates in a standard format. This required 
	formatting prior to even being able to analyze the dates.
    
    
### Analysis of Outcomes Based on Launch Date

		Once we were able to organize the launch dates, we took that information and created a line graph, so Louise could see for
	herself when the best times to launch were. We compared outcomes, their amount (whether success, fail, or canceled), and the 
	months in which the campaigns launched. The line graph provided visual aid in showing us that the months with the most 
	successful outcomes were May and June, and the worst time to launch a crowdfunding campaign would be in the winter, with 
	November, December, and January all having less than optimal results with their campaigns. Louise can clearly see that
	she should launch her crowdfunding campaign at the beginning of summer!

### Analysis of Outcomes Based on Goals
		
		Another area we analyzed, to provide Louise useful data, was the outcome of each campaign, based on its goal of how much 
	money they wanted to raise. We divided the campaigns into categories starting at < $1,000, increasing to $1,000 to $4,999, and 
	continuing to increase each category increment by $5,000, ending at $50,000 or more, for a total of twelve rows. Then we separated 
	each column by 'percentage successful', 'percentage failed', and 'percentage canceled'. Based on the results of that chart, we
	determined Louise would have the most success if she kept her fundraising goal under $5,000.

### Challenges and Difficulties Encountered

		With this dataset, we do encounter some limitations. While we have information on over 4,000 campaigns, only about a 
	third of the data is relevant to theater and plays. Louise wanted the research even more focused to only the US, which placed even
	more limitations on our data. Limiting the pool of data, increases the risks of variables that we are not able to predict, that 
	would have a greater risk of impact on Louise's campaign. A pie chart with all campaigns represented may help Louise visualize the 
	size of the sample we are pulling, since we are specifically focusing on theaters and plays for Louise's research.
	
## Results

		Further analysis with the campaign goals and amounts pledged, provided more in-depth details of the average of goals for
	successful and failed campaigns, as well as the average for the pledged amounts. We also calculated the standard deviation in all 
	categories to determine if there were any outliers that would skew the data. Successful play campaigns had an average goal of 
	$5,049, with the average pledge being $5,602. Failed play campaigns had a much higher average goal at $10,554, with the average 
	pledge being $559. This tells us, setting a lower crowdfunding goal of around $5,000, produces better outcomes. Based on the 
	analysis of our data, Louise would likely have the most success with her campaign, if launched in May or June, avoiding November 
	and December, with the goal around $5,000.
