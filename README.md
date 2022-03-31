# School_District_Analysis
Using Python Anaconda to analyze School data
# Overview of the school district analysis
The purpose of the analysis is to refactor the code to exclude the Thomas High School ninth graders and their math and reading grades due to academic dishonesty. The goal was to replace the ninth graders grades with null values and then rerun the district analysis to see how the absence of these grades affected the overall performance of Thomas High School and the district. 

# Results
- How is the district summary affected?

    The overall passing percentage increases when the ninth graders from Thomas High School are excluded from the dataset. 

- How is the school summary affected?

    The school summary is affected by now having Thomas High School being a much higher performer in terms of passing percentages than it was when we were including       9th graders grades. Thomas High School now has the second highest Overall Passing % of any school. 

-	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    Replacing the ninth graders’ math and reading scores causes Thomas High School to become the second placed school in terms of Overall Passing % right behind           Cabrera High School.
## How does replacing the ninth-grade scores affect the following:
-	Math and reading scores by grade
    
    There are now NaN values for math and reading scores for the ninth grade for Thomas High School as seen in this image [![image](https://user-images.githubusercontent.com/100726716/161130485-12870bda-af5a-458a-96bb-a98b05910345.png)]

-	Scores by school spending

    Thomas High School now has scores well above the average for schools in their spending range per student
-	Scores by school size

    Thomas High School’s % Overall Passing is 90.63% now compared to the average of 90.56% for schools in its Medium School Size range. 
- Scores by school type

    Thomas High School now has the same Overall Passing Percentage of 90% that is the average for Charter Schools. 

# Summary of Four Changes
One change is that Thomas High School’s updated % Passing Math went from 66.91% to 93.19% when the ninth graders grade were updated. Another change is the % Passing Reading went from 69.66% to 97.02% when the ninth graders grades were updated. Thirdly, the Overall Passing Percentage of students from Thomas High School went from 65.08% to 90.63% when the ninth graders were excluded from the updated dataset. Lastly, Thomas High School went from being one of the worst performing schools in terms of Overall passing % to the second best school in terms of Overall Passing Percentage when the ninth graders were excluded from the dataset. 
