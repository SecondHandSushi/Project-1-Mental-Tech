# Group 5 - one page project proposal November 7, 2023
## Title: Level of comfort discussing mental health with employers in the technology world
### Team members: 
- Matthew Idle, Chad Fletcher, Lori Vitaioli, Brady Ogega, Cindy Hansel, Heather Shoberg, Jennifer White
### Project Description: 
- Look for trends in employees’ level of comfort discussing mental health in the technology industry between 2016 and 2019.

### Research Question (2016 only):
- Which variables impact a technology associate's comfort/willingness to discuss mental health with employers? (countries, gender, age range, work location (remote or not), diagnosed or undiagnosed mental health condition,  size of company)

### Research Questions (2016-2019):
- Do employees feel more comfortable talking about physical or mental health?
- What is the level of ease for taking a leave of absence for mental health in the tech industry?

### Datasets to be used: 
- https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2017
- https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016
- https://osmihelp.org/research.html

### Rough breakdown of tasks:
- Matt - repo master, version control of the branches
- data cleanup and merging multiple years
- data analysis / conclusions
- data visualization 
- debugging / QA / regression
- slide deck

### November 9, 2023 discussion
- Scope creep: exclude questions concerning coworkers, self-employed, friends, family, previous employers
- Multiple years: start with all years (2014, not 2015 – 2019)
- From Cindy’s list:  # - exclude, tabbed in – keep, ? – review
- Cindy – 2014 review and clean data, Heather - take 2017, Brady – take 2019, Matthew – take 2018
- Next steps: review datasets and discuss how much data differs between years.

### Data Cleanup
- Removed survey questions that were unrelated to our research questions
- Removed 3 rows based on age: 3 years old, 99 years old, 323 years old (Below 18 and above 75)
- Created categories for gender since the original data had open responses. Categories are: TBD
- Renamed columns to be shorter descriptions of the questions
- For blank responses: filled with "No Response"
