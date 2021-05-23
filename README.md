# School_District_Analysis

# Overview of the school district analysis:
	This project is designed to analyze the standardized High School Test Data to provide insights about performance trends and patterns.
	This is will help the authorities to make informed decisions in school and district level.

## Data validity
	* The school board has been intimated regarding an evidence of academic dishonesty: 
		-- specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 
	* The analysis takes into consideration this anomaly and has taken the following steps to resolve this inconsistency
		-- replace the math and reading scores for Thomas High School with NaNs 
		-- keep the rest of the High Schools' data intact.
			
## School district analysis
---------------------------
	With this replacement of Thomas High School's 9th grade Math and Reading scores:
		-- the districts' math pass percentage fell from 75.0% to 74.8%
		-- the districts' reading pass percentage fell from 85.8% to 85.7%
		-- the districts' overall pass percentage fell from 65.2% to 64.9%
#### Summary before replacement:	
![District Summary prior]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/district%20summary%20prior.PNG )
#### Summary after replacement:	
![District Summary post]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/district%20summary%20post.PNG )
			
		
## School Summary
------------------
	With this replacement of Thomas High School's 9th grade Math and Reading scores:
		-- Thomas High School’s Math passing % fell from 93.27 to 66.91
		-- Thomas High School’s Reading passing % fell from 97.31 to 69.66
		-- Thomas High School’s Overall passing % fell from 90.94 to 65.07
		
#### Thomas High School's Stats before:
![School Summary prior]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/Thomas%20Prior.PNG)

#### Thomas High School's Stats after:
![School Summary post]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/Thomas%20Post.PNG)
			
## Top and Bottom Performers
### -----------------------------
	With this replacement of Thomas High School's 9th grade Math and Reading scores:
		-- Thomas High School fell from 2nd to 8th position in the Overall passing %
	
#### Thomas High Schools Stats before:
![School Summary prior]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/top%20performers%20prior.PNG)

#### Thomas High Schools Stats after:
![School Summary post]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/top%20performers%20post.PNG)
			
## The scores by school spending per student, by school size, and by school type
### ---------------------------------------------------------------------------------
	With this replacement of Thomas High School's 9th grade Math and Reading scores:
		-- the size, spending and school type scores does not seem to be impacted much.
			
	Before and after the replacement - the overall passing % for 630-644 range remained at 63 %
		
#### Spending Summary Stats before:
![Spending Summary prior]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/spending%20prior.PNG)

#### Spending Summary Stats after:
![Spending Summary post]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/spending%20post.PNG)
		
	Before and after the replacement - the overall passing % for Medium size remained at 91 %
		
#### School Size Summary Stats before:
![School Size Summary prior]( https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/size%20prior.PNG)

#### School Size Summary Stats after:
![School Size Summary post](https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/size%20post.PNG)
			
	Before and after the replacement - the overall passing % for Charter schools remained at 90 %
		
#### School Type Summary Stats before:
![School type_ Summary prior](https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/type%20prior.PNG)

#### School type_ Summary Stats after:
![School type_ Summary post](https://github.com/JoRanjit/School_District_Analysis/blob/main/Resources/type%20post.PNG)
