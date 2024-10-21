# [Mini-Project 1: Remote Work & Mental Health In North America]([https://public.tableau.com/views/ZomatoRestaurantAnalysis_17156453843520/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link](https://docs.google.com/presentation/d/1g-zJOzar9BySVCvnhj-x-CW-Kbu5Yoje8YY6LFFFVZs/edit?usp=sharing))

# Overview:

The purpose of this project is to test my ability in collecting, cleaning, and interpreting the data using Python and creating visualizations. I've created an 8 minute presentation using PowerPoint to show my findings along with a 5 minute presentation explainging my code in Jupiter Notebook.

# Business Context:

Remote work has become the norm for companies since COVID and it’s important for us to understand the impact it has on employees mental health with this new change. Remote work is great in providing flexibility and aspects like reducing commuter stress or finding daycare for your children, but it also blurs the lines between work and personal life. Without a proper work-life balance it can lead to mental health issues like burnout, anxiety, depression and so on. So by analysing the data we can identify any patterns between mental health and remote work satisfaction, which can enable stakeholders to make data-driven decisions to improve their employees well-being.

# Data Overview:

The dataset I used is from Kaggle and the information is from a survey that was conducted globally and collected 5,000 responses from individuals with different industry backgrounds. It looks into how remote work affects employees in terms of mental well-being, stress levels, and any pre-existing mental health conditions. The dataset came with 20 features, but the key features I used specifically for my research are Industry, Work Location, Work Life Balance Rating, Stress Level, Mental Health Condition, and Satisfaction with Remote Work.

# Data Cleaning & Wrangling:

In terms of cleaning the dataset was already cleaned when I first started working with it. As mentioned before, there were over 5,000 entries globally and I wanted to narrow that number down to not work with too much data. I filtered the responses to only from North America, which came down to 777 entries. Then I checked for any duplicate entries,and checked for any Null values. I did find some in the Mental_Health_Condition and Physical_Activity columns. I used Mental Health Condition as one of the features for my research, so I converted the Null values to None, that way I can use all of the information within that column. So now the options are Burnout, Anxiety, Depression and None.

# Mental Health Condition and Satisfaction with Remote Work:

I've created a stacked bar chart to compare the two vairables. I have found that  the anxiety and None groups have higher counts of unsatisfied individuals compared to those with burnout and depression. The neutral levels are pretty consistent across the different mental health conditions.

# Remote Work Satisfaction vs. Location and Stress levels:

I've created a facet grid of violin plots, grouped violin plots. On top the location types are listed, with the stress levels from Medium, High, and low on the right and the satisfaction rating for remote work on the bottom.To summarize the plots, higher stress levels correlates to dissatisfaction with remote work across all work arrangements. Lower stress levels generally correlates to satisfaction with remote work, and medium stress levels show a move balanced distribution but tends to lean toward neutral.

# Remote Work Satisfaction by Location:

I've created another stacked bar chart for this visualization. My findings show for Consulting it has the lowest count compared to the rest of the industries, and it has a fairly even distribution between satisfied, unsatisfied and neutral. Education and Finance have the most counts compared to the others, education having the highest counts of satisfaction. For healthcare, IT, manufacturing and retail they have similar counts among the four of them, and the satisfied levels are more evenly distributed.

# Conclusion: 

In conclusion, when looking at mental health conditions in different work locations, anxiety stands out as a significant factor that impacts satisfaction levels with remote work. High stress correlates with dissatisfaction across all work locations, which indicates that there is a link between stress and remote work satisfaction. Vice versa, lower stress levels correlates with satisfaction with remote work. Industry wise, satisfaction levels can vary depending on what industry you're in.  For example, Education and Finance industries show higher engagement and satisfaction levels, while Consulting shows balanced but lower counts. It basically means that industry-specific factors play a role with remote work satisfaction.

