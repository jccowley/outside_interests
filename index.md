---
# Do not edit the text between these lines!
layout: default
---
# COMP 110 EX09

## Analysis
To start the analysis, I seperated columns that were relevant to my idea using select(). in order to focus my analysis. I also used functions such as head(), convert_columns_to_int(), and major_group() to further organize the data and get a general idea of what we would be analyzing. 

To start my analysis, I used count() to see how many students selected each respons 1-7 for the interested_connections question. I noticed that there were more responses ranging from 5-7 than 1-3, demonstrating some interest in the idea of outside connections to the class.

<img src="./static/imgs/ss/counts.png" alt="Image of Comp110 rainbow logo. "  width="500"/>
*Screenshot of counts from the notebook*

I then visualized these counts using a histogram to better see the connection.

<img src="./static/imgs/ss/histogram.png" alt="Image of Comp110 rainbow logo. "  width="500"/>
*Visualization of the counts in a histogram*

I also visualized the relationship between interested_connection answers and major groups using box and whisker plots, to see if only CS majors would be interested in the optional exercises, or if other majors would also be interested.

<img src="./static/imgs/ss/boxplot.png" alt="Image of Comp110 rainbow logo. "  width="500"/>
*Visualization of relationship between major groups and interested_connection answers using box & whisker plots*

Finally, I visualized the relationship between interest in the class and interest in outside connections, by creating a line plot comparing interested_connections answers to average interesting answers. 

<img src="./static/imgs/ss/lineplot.png" alt="Image of Comp110 rainbow logo. "  width="500"/>
*Visualization of relationship between ratings of interest in class and outside connections*

## Conclusion
I believe the data does relatively support our idea, and I recommend that these optional exercises are added. The first visualization of counts shows a higher concentration of students that ARE interested in how CS connects with other fields. The second visualization of major groups shows an incredibly strong interest from CS students, whereas other major groups box and whisker plots show they are less interested, although most (besides the "other majors" category) are typically above the average in mean and range. Finally, the third visualization suggests that students who are interested in cross-field connections also find the course more interesting overall, which supports the idea that adding these exerciess would align with what engaged students already value in the course. 

The potential costs and downsides of adopting this idea comes in the formation of these exercises, however, by keeping the exercises optional and potentially providing answer keys to them, no stakeholders are negatively impacted after the first semester (as exercises can be reused). 

Potential extensions or refinements to our idea would include making these exercises mandatory, however then you run into issues of grading work & certain students being less engaged with the class overall due to their interests not being represented, potentially negatively impacting stakeholders.