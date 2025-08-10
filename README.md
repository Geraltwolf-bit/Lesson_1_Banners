# Lesson_1_Banners
In this program, I figure out what banner and what channel are the most effective.
I have the columns: banner, channel, displays, clicks - and my job is to find what banner brings more clicks and what channel has more clicks.
First, I use pivot_table to create a dataframe sorted in descending order. This dataframe displays the number of clicks for each banner.
I then visualize relationships between clicks and banners to confirm my findings, and with the help of idxmax and idxmin I print my findings.
But each banner has two channels - web and mobile - and I find what channel brought most clicks.
For that, I used groupby function first to group by banner and channel and then I grouped the result by banner.
Finally, I created a barplot with matplotlib to display each banner with the number of clicks from web and mobile respectively.
