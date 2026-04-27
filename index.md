---
# Do not edit the text between these lines!
layout: default
---

# The Beginner Gap: How Prior Experience Shapes the COMP110 Experience 

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<custom-path>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Analysis Summary 

For this project, we explored whether prior programming experience impacts how diffcult students find COMP110 and how well they feel they can understand the material. Using anonymous survey data collected from COMP110 students, we analyzed the "prior_exp", "difficulty", and "understanding" columns across 764 total responses from two survey datasets. We hypothesized that students with little to no prior experience would rate the course as harder and report lower understanding. 

## Visualizations 

### Average Difficulty by Prior Experience 
<img src="/static/imgs/chart1_difficulty.png" alt="Bar chart of average difficulty by prior experience" width="700"/> 

### Average Understanding by Prior Experience 
<img src="/static/imgs/chart2_understanding.png" alt="Bar chart of average understanding by prior experience" width="700"/>

### Difficulty vs. Understanding Scatterplot 
<img src="/static/imgs/chart3_scatter.png" alt="Scatterplot of difficulty vs understanding" width="700"/>

## Conclusion 
Summary of Data: Students with no prior experience rated difficulty at an average of 4.56 out of 7, which was the highest of any group. Their understanding score was also the lowest at 4.01 out of 7. On the other end, students with over 2 years of experience rated difficulty at just 2.20 and understanding at 5.87. So as experience goes up, difficulty goes down and understanding 
goes up, which is pretty much what you'd expect but it's good to see the data actually back it up.

478 out of 764 students (about 63%) reported having no prior experience at all. Majority of the class, comes into COMP110 with limited programming knowledge. 

Would a introductory/beginner bootcamp be advantageous for COMP110 students? 
Yes, there is a gap in difficulty rating between no experience students and students with just 2-6 months 
of experience (4.56 vs 4.11 for difficulty, 4.01 vs 4.38 for understanding) 

Costs and Trade-offs with a Bootcamp: 
- Running extra sessions at the start of the semester requires more time from TAs and instructional staff who are already stretched thin
- It's hard to know if the difficulty gap is just temporary, maybe beginners catch up after a few weeks anyway and the bootcamp wont 
 change outcomes long term

Extensions and future work:
- It would be really interesting to cross-reference this with actual grades (we don't have that data here) to see if the difficulty gap translates to grade differences or if beginners still end up doing fine
- Looking at office hours visits (oh_visits) by experience level could show whether beginners are seeking more help, and if they are, that's more evidence that structured early support would help
- A follow-up survey later in the semester asking if students felt they caught up over time could help figure out whether the gap is permanent or temporary