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
- 
### November 14, 2023 discussion
  -	Make bins for ages – 18 – 24, 25 – 34, 35 – 44, 45 – 54, 55 – 64, 65 – 74, 75+
  -	Fill blanks with No Response – 1428 total responses. Consider how “no response” will impact number analysis.
  -	Added ‘cur’ and ‘prev’ for “willing to discuss with supervisor” question
  -	Cindy will look at 2016 – 2019 datasets to merge and look at trends over time
  -	Rest of us: 
    -	gender vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Lori
    -	age band vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Matt
    -	size of employer vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Brady
    -	country vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Heather
    - remote vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Chad
    -	Diagnosis vs. Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)? - Jennifer

### Questions List
    'What is your age?', 
    'What is your gender?',
    'What country do you work in?', 
    'Do you work remotely?',
    'How many employees does your company or organization have?',
    'Have you had a mental health disorder in the past?',
    'Do you currently have a mental health disorder?',
    'Would you be willing to bring up a physical health issue with a potential employer in an interview?',
    'Would you bring up a mental health issue with a potential employer in an interview?',
    'Have you observed or experienced an unsupportive or badly handled response to a mental health issue in your current or previous workplace?',
    'Have your observations of how another individual who discussed a mental health disorder made you less likely to reveal a mental health issue yourself in your current workplace?',
    'Would you feel comfortable discussing a mental health disorder with your direct supervisor(s)?',
    'Would you have been willing to discuss a mental health issue with your direct supervisor(s)?',
    'If a mental health issue prompted you to request a medical leave from work, asking for that leave would be:'