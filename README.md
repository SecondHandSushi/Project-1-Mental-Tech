#  Mental Health in Tech Jobs: A Study of How Comfortable Employees in the Tech Field are Discussing Mental Health with their Employers.
### Team members: 
- Matthew Idle, Chad Fletcher, Lori Vitaioli, Brady Ogega, Cindy Hansel, Heather Shoberg, Jennifer White
### Project Description: 
- This project seeks to determine trends and relationships in tech industry employees’ comfort in discussing mental health with their employers.
### Research Questions:
- Which variables impact a technology employee's comfort/willingness to discuss mental health with employers?
- Do employees feel more comfortable talking about physical or mental health?
- What is the level of ease for taking a leave of absence for mental health in the tech industry?

### Datasets to be used: 
- https://osmihelp.org/research.html
- We utilized data sets for the 2016, 2017, 2018, and 2019 OSMI Mental Health in Tech surveys.

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
