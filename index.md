---
# Do not edit the text between these lines!
layout: default
---

# EX 09 - Johnny Ta and Bianca Salve

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<static/imgs/output.png" alt="First seaborn graph, histogram displaying the distribution of difficulty ratings in COMP110. "  width="500"/>

## Analysis Summary

For our analysis, we wanted to look at the relationship between student's percieved difficulty of COMP110 and student's desire for pre-lecture videos. We hypothesized thatthe higher that students rank the difficulty of COMP 110, the more likely they would want pre-class videos. We reasoned this to be more valuable than the other ideas because with the results, professors will be able to determine whether or not the creation of pre-class videos would benefit studnets in future sections. 

To analyze the data we took the data through a few steps:

1. After importing the two surveys, we converted them to column-based tables, and combined the results to make analysis much simpler.
2. Following that, we utilized the `head` function to check the first 5 lines of the table to ensure to check the dictionary.
3. Subsequently, we created a function named `no_exp` to iterate through the results and create a new list only with students who had little to no coding experience.
4. Following that, we again called the head function to check that the first few lines of the dictionary were correct.
5. We then called the count function to count the frequency of each rating of `pre_lecture_videos` among those students with little to no coding experience.
6. Next, we used `select` to only choose our two variables of interest, `pre_lecture_videos` and `difficutly`. 
7. Finally, we used seaborn to create four graphs: 2 histograms, 1 linear regression/scatterplot, and 1 bivariate histogram.