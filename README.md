# School District Analysis
School district analysis for module 4# PyBer_Analysis
## **Overview of District Analysis**
In this assignment, we were asked to use python through the jupyter notebook platform to analyze data sets containing student performance statistics for a given school district, and the spending information per school within the school district. The data set contains a list of all the students in the district, and includes their math/reading grades, the name of the school they attend, and their year in high school. The initial review of the data set revealed some anomalies, such as incorrect titles for students (eg "Dr.") as such, the first task was to clean the data and make it suitable for analysis. Then, the data was combined into a super set containing all the information, such as spending per school or per student and grade status. The initial review ended up revieling academic dishonesty, so the data set had to be adjusted to remove the scores which artificially affected the overall district statistics
## **Results**
**Figure 1: Original District Summary Data Frame**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F1_Original%20Dist_Summary.png)

Figure 1 above summarizes information for the district as a  whole. Important parameters include total spending, as well as the pass/fail percentage of students by subject and overall. 

**Figure 2: School Summary Data Frame**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F2_Original%20School_Summary.png)

Figure 2 above summerizes information per school in the district. The parameters include spending, pass/fail rate and average scores per school. In total, the data above gives us a metric in which to assess the budjet and efficacy of schools within the district. We will further disect the information in order to draw further conclusions

### Summary of District Parameters
First we would like to take a look at the top and bottom performing schools, as is summarized in the figure below.

**Figure 3:Top and Bottom Performing Schools**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F3_Top_Bottom_Schools.png)

The top/bottom schools out of 15 are shown (top are selected in green, bottom are selected in red).

**Figure 4: Scores VS Spending per Student**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F4_Scores_V_Spending.png)

Next we want to assess the performance according to the per-student spending, which is shown above. Perhaps suprisingly, there appears to be an inverse relationship between per-student spending and overall student performance. Most likely this is because we are comparing charter and district schools together in the same data set. 

**Figure 5: Scores VS School Size**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F5_Scores_V_Size.png)

We also want to consider the student performance at schools of different sizes (here, size means the number of students at the school). It is clear that the large schools seem to be severely underperforming compared to medium and small schools. This could be because student resources are overtaxed at large schools, or simply that larger amounts of students make it difficult to ensure that the students pass.

**Figure 6: Scores VS School Type**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F6_Scores_V_Type.png)

Finally, we consider performance between the two types of schools (district and charter). There is a clear outperformance by the charter schools as compared by the district schools. This reflects a larger discussion which exists about the equity of having charter schools within the same district.

### Influence of Academic Dishonesty

After submission of the district data, it was determined that academic dishonesty had occured. Specifically, the scores of the entire ninth grade class of thomas high school have been comprimised. In order to mitigate the influence of the academic dishonesty, we have eliminated those students from the data sets and redone the entire analysis. 

**Figure 7: Adjusted District Summary Data Frame**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F7_Adjusted_Dist_Summary.png)

- Effect on school summary: as shown in the figure above, the overall school statistics only changed by a small amount in the reading, math and overall passing categories. This is not suprising since the amount of students removed (around 400) was quite small compared to the overall students (37000). As well, we can look at the school data and top/bottom schools, which did show more of a change. (shown in the figures below).

**Figure 8: Adjusted School Summary Data Frame**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F8_Adjusted_School_Summary.png)
**Figure 9: Adjusted Top and Bottom Performing Schools**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F9b_Adjusted_Top_Bottom_nInc_9.png)



- Effect on Thomas High School VS Others
- Effect on Math/Reading Scores by grade
- Effect on Scores by school spending

**Figure 10: Adjusted Scores VS School Spending**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F10_Adjusted_Scores_V_Spending.png)
- Effect on schoolsize

**Figure 11: Adjusted Scores VS School Size**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F11_Adjusted_Scores_V_Size.png)

- Effect on scores by school type

**Figure 12: Adjusted Scores VS School Type**
![alt text](https://github.com/aamotz001/School_District_Analysis/blob/main/Images_for_Analysis/F12_Adjusted_Scores_V_Type.png)
## Summary of Conclusions
4 major changes were
1. one
2. two
3. three
4. four

In conclusion
