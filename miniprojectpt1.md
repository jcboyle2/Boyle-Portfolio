# Mini Project - Summary and Outline

## Project Summary:

The minimum wage no longer supports affordable housing in any state. This project will examine how we got here, why that matters, and how wage and housing policies could work to solve the problem.

## Project Outline and Structure:

All sketches and images below are just that - sketches - and subject to significant revision.

<img scr="wireframe_sketch2.png" width="720">

## Story Arc:

The basic structure will start by introducing the main concept - the U.S. proposed a federal minimum wage as a living wage, yet raises in the minimum wage haven't kept up with rising housing costs. In this case, housing costs are defined by U.S. Department of Housing and Urban Development's Fair Market Rent (FMR) formula. In the aggregate, this will look at the national average FMR for a 2-bedroom apartment and at the individual state level.

Because Fair Market Rent values are not the same in each state, we will briefly look at states with higher and lower state minimum wages compared to the federal minimum wage.

Even when taking into account differences in state and federal minimum wages, no state currently supports affordable housing. In this case affordable housing is defined as spending 30% of your monthly income on housing costs.

Currently I have a map from tableau looking at which states are the most unaffordable and the least unaffordable, but this is subject to change. I was also considering looking at a Top 5 Most/Least Unaffordable States.

From there, the project would examine how minimum wage earners can afford to live in unaffordable housing.

Lastly there is an examination of policy proposals for both wage and housing policies that could help remedy this issue, which will work to highlight policies that other cities and states have successfully implemented.

## Call to Action:

The call to action in this case is multipronged. There is encouraging local, state, and federal office holders to increase minimum wage polices - attending local housing/zoning meetings to encourage more sustainable development - and to participate in local organizing efforts in your neighborhood or community.

## User Research and Feedback

#### Target Audience:

Middle-class, educated people who are less likely to have worked a minimum wage job (outside of high school/college) or have lived the effects of poverty. This audience, I believe, would be most impacted by learning about the challenges of some of the most vulnerable Americans and would have the means to make a difference in their community.

#### Approach to Targeting Interviewees:

Finding people to interview might be more difficult in the current climate, but I believe that many friends, family members, and classmates would fit the description. Again, these would have experience renting, but less likely to have experience with near-poverty conditions.

#### Interview Script:

1.	How familiar are you with the minimum wage? Affordable housing?
2.	An individual working a full time minimum wage job makes roughly $15k a year. Do you think that is above or below the poverty line? (it is above - $12,760)
3.	What characteristics would you use to describe a minimum wage worker?
4.	What do you think is the average fair market rent for a two bedroom apartment is in your state/nationwide? (read figure to them)
5.	Do you think that is affordable? If not,
a.	If you could quantify the cost of affordable housing what would it be?
6.	Show draft visualizations – ask what the like/dislike, if confusing, etc.
7.	Ask what policies would they be willing to support to address housing affordability issues.

#### Metrics:

Whether participants were aware of how tight the budget constraints for minimum wage workers, and

Whether that awareness would make them more likely to support/take actions to fix wage and housing policy.

#### Interview Results:

##### Individual #1:

Individual one was aware, but not familiar with both wage and housing policy. They correctly believed that the average minimum wage worker skewed younger in age, generally had less education and opportunity than other works, and made more than the poverty line. For average FMR of a 2-bedroom apartment, they guessed $700 which was close to $300 below the average in the Virginia, and overestimated affordability by about $200.

They liked seeing the history of the federal minimum wage and FMR prices, but not the percent change, which they considered distracting. For the map, they believed that the point it was trying to make was good to show that nothing is affordable, but that there needed to be more contrast in the colors. Additionally, the difference in state/federal wage chart needed to be reworked to show more reference as to what 0 means, plus and minus, etc.

##### Individual #2:

Individual two was less aware of policy outside that it exists. They tended to view minimum wage workers as students doing "blue collar jobs... like maintenence, food prep, etc." They were almost exactly correct in identifying average FMR (they said $1000, it is $992 in VA), but incorrectly guessed as to what is affordable.

For the visualizations, they did not like the state/federal minimum wage gap chart. They did not understand what it was trying to say, and could not figure out what the average was. They suggested either making the tick marks show above/below $7.25 or get rid of the chart. Additionally, they did not like the map and thought the colors were too similar to tell apart.

While they were overall supportive of changing policy, they had a lot of questions as to what this meant for the average worker in each state - and why that was not addressed.

##### Individual #3:

Individual three was aware of minimum wage policy, but was unfamiliar with housing policy. Despite this, individual three was able to correctly identify both the average FMR and the affordability of FMR housing based on personal experience alone. They were incorrect on the federal poverty line, but not surprised to learn how low it is.

When they described the characteristics of minimum wage workers, they accurately said it ranges on a lot of age and demographic information. Younger, more affluent kids working a single part time job, to older, typically undereducated workers doing full time, minimum wage work. They were not surprised that the average minimum wage worker couldn't afford housing, but were surprised by how wide the gap was in most states. Similarly, they said the gap between median wages for all workers and affordability was "astonishing."

For the charts, they agreed with individuals one and two that the percent change in the FLSA chart was unnecessary - but otherwise the basic FLSA and FMR charts were simple and helpful. The infographic showing the 30% of a dollar was also helpful to them. Less so were the charts on state/federal minimum wage gaps, and maps of affordability. They questioned whether it was helpful at all to try to display that many states at once in a dot chart.

##### Overall Results and Changes:

What I found was that my interviewees were aware of what the minimum wage was in their area, but were not aware of what that meant in terms of monthly/annual salary and housing costs. Similarily they were not able to put that in context of the federal poverty line, or what would constitute affordable housing. They seemed less interested in the characteristics of the minimum wage workers and instead the context of average workers within a state. This caused me to rework a lot of the second half framework. I kept the basic history charts as I thought those were simple and clean, and necessary for educating people who may not know more of the details in wage/housing policy. Instead of using the state/federal difference chart from the framework - I made it a map in tableau which shows states above in blue, below in red, and same as federal in white. This worked a lot better, was smaller, and more efficient. However, I am having a little trouble getting the embed to show the legend for it in Shorthand.

From there, I added to the inforgraphic in the wireframe - an example of affordability applied to the state of Wisconsin. From there, I decided to change the map to a range plot showing the gap between each state's minimum wage and the affordability wage to highlight how big the gap is in every state. Because some of my interviewee's were more interested in the population as a whole, I found data from the U.S. Bureau of Labor Statistics' Occupational Employment Stats, which had each states median and average hourly wage for all workers. I used this to make a second range plot to show that some states are still unaffordable even for the average worker's median wage. While I think these are better, I still think there might be room for me to add a top five most/least unaffordable states because of how busy both the range plots are.

Overall, I felt it made my presentation stronger to be able to point to states where it is unaffordable for the average of all workers, and not just the small fraction of minimum wage workers.

To see these changes in action, check out the preview of [my Shorthand here.](https://preview.shorthand.com/2xBDEdd7Tc82NsZK)
 
## Data Availablilty:

All data in this project is publicly avaliable, made by U.S. federal agencies. This includes:

 - [1] [U.S. Bureau of Labor Statisitics - Characteristics of Minimum Wage Workers](https://www.bls.gov/opub/reports/minimum-wage/2019/home.htm)
 - [2] [U.S. Department of Labor - Minimum Wage History](https://www.dol.gov/agencies/whd/state/minimum-wage/history)
 - [3] [U.S. Department of Housing and Urban Development - Fair Market Rent History](https://www.huduser.gov/portal/datasets/fmr.html#history)
 - [4] [U.S. Department of Labor - Median Weekly Earnings of Full Time Workers](https://www.bls.gov/webapps/legacy/cpswktab3.htm)
 - [5] [U.S. Bureau of Labor Statistics - Occupational Employment Stats](https://www.bls.gov/oes/current/oessrcst.htm)

[1] Characteristics of Minimum Wage Workers - used to describe the general characteristics of workers, mostly to correct misconceptions about minimum wage workers. Most minimum wage earners are above the age of the age of 25, and have at least a high school diploma.

[2] Minimum Wage History - used to create charts related to minimum wage history over time, and current values of state minimum wages. Anything that references minimum wage levels references these tables.

[3] Fair Market Rent History - used to create anything related to mapping average rent values for apartments in the U.S. This includes both creating a national average, state average, and county level (using FIPS) data, and dates back to 1983. Fair Market Rent is calculated by HUD, and is available for 0, 1, 2, 3, and 4 bedroom apartments. Recent analysis of affordable housing tend to focus on the 2-bedroom apartments as the benchmark.

[4] Median Weekly Earnings - currently not being used in the wireframe, but may be informative in explaining the gap between earnings and affordable housing.

[5] Occupational Employment Stats - Hourly/monthly/annually wage data for each state from May 2019. Used to compare against the affordablility wage calculated with FMR history data.

###### Click below for file downloads:

<a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/FY20_4050_FMRs_rev.xlsx?raw=true">Download raw FY20 FMRs pulled from HUD. (.xlsx)</a>

<a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/affordable_wages_per_state_average.xlsx?raw=true">Download computed average affordable wage per hour based on FMR 2-bedroom apartment, compared to minimum/median wage of state. (.xlsx)</a>

<a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/average_fair_market_rent.xlsx?raw=true">Download computed average FMR for each state(.xlsx), which explains the decisions in the image above.</a>

<a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/wage_fmr_over_time.xlsx?raw=true">Download compiled history of federal minimum wage and FMR over time. (.xlsx)</a>
