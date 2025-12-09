<img width="989" height="1010" alt="image" src="https://github.com/user-attachments/assets/2b71a1f4-dd86-47f5-87d6-a29969f896ae" />
I don’t think the original plot distorted the data. The points on the original plot were so clumped together that they were distracting, and it also made the data ambiguous. This plot improved on the original by reducing the alpha of the points and their outlines, which made it easier to distinguish where the points are densest together. Decreasing the alpha of the regression lines made it easier to see that the sklearn and L2 minimization regressions are identical, but it makes it harder to see the chi-squared and L1 minimization lines. Adding units to the x-axis also reduces the ambiguity of the data. 

The plot respects Tufte’s 5 rules when applicable. The graph lines could be considered chart junk, since they don’t add to the interpretation of the plot since the goal of the plot is to show how different linear regression methods fit the data. On the other hand, I like the graph lines.

The plot doesn’t use a color-blind friendly color palette and because of the lower alpha, many of the colors have the same value. Linking the color of the points to their passband does make it more intuitive for those who can distinguish between the colors. 

<img width="659" height="489" alt="image" src="https://github.com/user-attachments/assets/b95094db-f976-4a67-800a-8c787ca45e4d" />

This plot is impossible to read. The number of lines overplotted on each other makes what the data is trying to show ambiguous and I’d say that just the sheer number of lines is distracting. If the point of the plot is to show that most time series stay within the 90-105 range, using different transparencies for the lines could help make that clearer. The y-axis of completion rate is also confusing. I’d assume that it was a percentage except that there are many points higher than 100 and I don’t know what 110% complete would mean.
 
Considering Tufte’s rules, the (discernible) data vs ink ratio is very off. The axis goes from 75-110, which would distort the effect size if zero should be the baseline, but it’s hard to tell whether that is the case for the data, and it’s hard to tell what the plot is trying to show at all. I think it could be improved by using small multiples to make the time series more legible. 

This plot is color-blind friendly because this plot wouldn’t be more confusing for someone who is color blind compared to someone who isn’t. Plotting all of the lines in blue probably isn’t in best color practices but making the different series different colors wouldn’t make the graph less ambiguous because there are so many lines plotted together. 
