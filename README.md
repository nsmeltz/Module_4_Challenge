# Module_4_Challenge

# Overview of the school district analysis
  The purpose of this analysis was to analyze data from a school district regarding math and reading scores from multiple high schools in the district. The 9th grade scores   at Thomas High School are inaccurate due to academic dishonesty. This reports aims to describe how these innacurate scores affected the inital analysis of the district's     performance in math and reading. 
  
# Results:
**District Summary**
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/760cde5de33c8ef4f9667cc64725d9e584ab0b48/Resources/district_summary.png)

**School Summary**
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/c41cf673289c96dde0eddefa9208334ba5e59be9/Resources/per_school_summary.png)

**Math Scores by Grade**                                                                           
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/892c2639b6c7992935a766c128df86a09dc1e15a/Resources/math_scores.png)

**Reading Scores by Grade**                                                              
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/892c2639b6c7992935a766c128df86a09dc1e15a/Resources/reading_scores.png)

**Scores by school spending**                                                                                        
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/ef116c404ed464b6013ac2110985d5b0b0df3db0/Resources/scores_spending.png)

**Scores by school size**                                                   
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/ef116c404ed464b6013ac2110985d5b0b0df3db0/Resources/scores_size.png)

**Scores by school type**                                         
![This is an image](https://github.com/nsmeltz/Module_4_Challenge/blob/ef116c404ed464b6013ac2110985d5b0b0df3db0/Resources/scores_type.png)

# Analysis

  - **How is the district summary affected?**
    The district summary is not affected much by changing the inaccurate scores to NaN. The %passing math, %passing reading, and %overall passing all decreased by 1% or less, suggesting that the scores for 9th graders at Thomas High Schools did not make a large difference in the data for the whole school district. 
    
  - **How is the school summary affected?**
    Changing the inaccurate scores to NaN for the 9th graders at Thomas High School only affects the entry for Thomas High School in the school summary table. By negating the    effect of the inaccurate data for the 9th graders the  %passing math, %passing reading, and %overall passing percentages increase from about 60% to about 90%. This implys that a high number of the 9th graders were failing and this should be looked into to double check that their performance is not chalked up to academic dishonesty. 
    
  - **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
    Because the %passing math, %passing reading, and %overall passing percentages increased for Thomas High School it appears to have performed a lot better as compared to the other schools now.
    
  - **How does replacing the ninth-grade scores affect the following:**
    - **Math and reading scores by grade**
      Replacing the 9th graders scores only affect the Thomas High School entry for both reading and math scores. When the 9th graders scores are replaced NaN is shown in the 9th graders column for Thomas High School otherwise the average math and reading scores are 83.6 and 83.7 on average. 
      
    - **Scores by school spending**
    Replacing the 9th graders scores decreases the %passing math, %passing reading, and %overall passing percentages for the $630-644 spending range( the range that Thomas High School falls in).
    
    - **Scores by school size**
    Replacing the 9th graders scores decreased the %passing math, %passing reading, and %overall passing percentages for the Medium sized schools (the size that Thomas High School falls in). The %passing math and %passing reading is now less than 100% which gives a more accurate representation of the schools performance.
    
    - **Scores by school type**
     Replacing the 9th graders scores decreased the %passing math, %passing reading, and %overall passing percentages for the charter schools (the type of school Thomas High School is). Prior to replacing the %passing reading was greater than 100% which is not realistic. 
     
# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
  Four major changed that occured afer replacing the reading and math scores for the 9th graders at Thomas High School with NaNs are:
  
    1. %passing math, %passing reading, and %overall passing percentages all increased which resulted in Thomas High School ranking higher among the other schools in the district
    2. %passing math, %passing reading, and %overall passing percentages decreased for the $630-644 spending range
    3. %passing math, %passing reading, and %overall passing percentages decreased for the medium sized schools
    4. %passing math, %passing reading, and %overall passing percentages decreased for the charter schools. 
