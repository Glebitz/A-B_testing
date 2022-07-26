# A-B_testing
I had raw data about users, active users (who took part in the experiment) and their checks. Detailed description is inside. \
Users were divided into 2 groups: A and B. I analysed conversion (CR) into purchase and average revenue per paying user (ARPPU). \
In order to add more data about users in the future easily I made a speacial function 'show_updated_result' which shows the updated CR and ARPPU metrics. Additionally, function 'visualize_updated_result' indicates the appropriate plots. \
You can also find some SQL queries which extract necessary metrics from database. This is to demonstrate my SQL knowledge :)
\
\
What I found out:
1. It seems that CR is even less in group B, however, chi-square test shows that these are not statistically significantly different.
2. ARPPU in group B is bigger. This is confirmed by T-test and its nonparametric analogue Mann-Whitney U-test.
3. Visualization indicates the difference of ARPPU in the area of 2000. Most of the people spent 2000 in group B. Meanwhile most of the people from group A spent around 500.
