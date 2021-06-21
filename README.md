# An Analysis of Kickstarter Campaigns

## Performing analysis on Kickstarter data to uncover trends

### This is a focused Analysis of failed versus successful campaigns to forecast what types of future campaigns would be the most successful at what times of year and how much success we can expect to see from them in the future. The focused category portions include analysis of main categories overall and subcategories. It also specifically includes the theatre category and the subcategory of plays themselves broken down. There is a focus on different types of campaigns launched throughout the year to determine the impact of timing on meeting their goals.

## Analysis and Challenges

### Generally, music and theatre campaigns launched around May and June seem to be more successful compared to the entirety of campaigns with a decline as the launch dates move towards December as seen here. December seems to be the worst time to launch this type of campaign historically. Although campaigns among all categories did not vary as much as theatre, they still trended toward the spring (May and June) for being the most successful based on launch date slightly.

![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/86118012/122811603-b481c000-d29e-11eb-9b8b-07a94620971f.png)

### Campaigns under the subcategory plays, with smaller targets, seem to have more success as seen here. However, it is not consistent. There are some very large goal campaigns that were successful. We can not accurately make an assumption that plays with larger goals would follow that trend given the small number of them ran.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/86118012/122804129-80ee6800-d295-11eb-96a5-9232b274f8ef.png)

### One of my challenges here was efficiently creating functions while analyzing the success specific to plays and their outcome based on goals set. The formulas are complex given that we were using ranges. Althought I could copy and paste the formula with only small changes, it was very time consuming and easy to make an error as opposed to filling formulas. I looked back at the raw data with general searches to verify the information looked accurate. For the canceled plays being all zero, I ran a search to try and find a play that was cancelled and I would know which formula was wrong based on the goal. It turned out not to be a problem, but I saw a quick fix to check a formula like that resulting in zero across all ranges.

## Results

- We can reasonably conclude it would be best to launch any campaign closer to spring, either May or June. However, this has much more of an impact when launching theatre campaigns. Campaigns among all categories are relatively consistent throughout the year with regard to success based on launch date. This analysis does not look at every major category independently. December had the lowest success rate among both theatre specifically and all categories combined. This has generally been the worst time to launch a new campaign.The second worst month historically is September.
- There is not enough evidence to suggest that the goal of a particular play has a major impact on it's success, but the trend is toward campaigns with lower goals, specifically starting under $25,000.
- There are limitations to these results because we do not have a significant number of campaigns under the plays category with higher end goals which heavily impacts percentages. The results may be misleading looking at the this chart and these trends alone. With regard to launch date, there could be other specific factors aside from time of year that happen to coincide with seasons increasing their success. Those may occur in other seasons sometimes. Theatre and play campaigns in May and June are higher in overall count which may impact results, even on a percentage basis.
- Some other charts to review would be a summary of all campaigns success based on launch date as well as a summary of all campaigns success based on goals. These could be a base line for comparison to plays. We may aslo want to look at all the main categories and develop a plan to focus on launching certain types of campaigns at certain times of year and maybe eliminating some that aren't successful enough at all. I would probably create two new sheets with charts of those trends in each main category to start and dig down by subcategory where it makes sense.
