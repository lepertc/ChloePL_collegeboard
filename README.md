# Question 1: Load data
* ~12% of rows have missing data in (year, school id, or student vol). Mostly in student vol. We exclude these rows from our analysis
* 0.3% of schools are missing data for certain years. This does not alter the global picture, but can alter it at a country level

# Question 2:  Detecting global events 

## Hypothesized detectable events: 
### Wars:
#### Gulf: 1990-1991: Iraq, Kuwait, US, UK, France, Saudia Arabia, Egypt
#### Ukraine-Russia: 2015, 2022
### Introduction of birth control
1960 with restrictions, 1970 more broadly, not until 1999 in Japan: US, France, Japan, Germany, Canada
### Fall of the Berlin wall: 1989: Germany, Russia, Hungary, Austria

## Findings

## Gulf war
* Kuwait student volume in the early 90s is decreased. I need to make sure there are no other events happening at the same time to confirm the association. It would also be good to understand why Kuwait was impacted but not Iraq and Saudia Arabia.
* We do not see impact in: Iraq, US, UK, France, Saudia Arabia, or Egypt
## Ukraine-Russia
* See a drop in student volumes in the late 2010s in both countries

## Birth control
* The 1960s are too close to the start of the data to detect an angle change
* 1960s also coincide with the baby boomers entering university so it would be hard to associate anything to birth control. The boomer pattern is repeated every generation in the student volume time series (France shows this pattern pretty clearly)

## Fall of the Berlin wall
* Germany and Russia show a small potential nudge up in student volume. To confirm I would need to understand more how the Berlin wall affected access to education.
* Hungary data (needs quality check). Student volume 3x in 20 years
* No impact is detectable in Austria

# Question 3: Student enrolment correlation to GDP

## Approach
* I looked at correlation of student growth (in 5yr increments) to GDP growth also in 5 year increments. Looking at growth "controls" for overall population growth.
* I also lagged GDP to see if current GDP affects current enrollment (people being able to afford university) vs. Educated individuals driving future GDP
* I excluded univerisities with incomplete data. 
* I also did some outlier removal I exclude GDP and student volume growth of more than 5x or falls  by more than 80% (with more time I would investigate more what is appropriate; look into what countries year get exclude)

# Findings

## Finding 1: GDP the year students are in university and 10 years prior matter for student volume growth. 
Why a 10 year gap and not a 5 year gap I am not sure. I would want to plot these growth rates against each other and look at whether certain years have a large effect

## Finding 2: GDP is most correlated to student volume growth in years prior. 
This suggests that growing higher ed, grows GDP. With more time, I would validate this finding by looking at how it holds over year pairs.

I would want to make a lot more checks before making these claims. If something else is causing population growth, GDP, and student enrollment to grow, we could also see these correlations.

