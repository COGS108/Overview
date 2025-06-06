v0.1 31-March-2025

**WARNING!!! This is a draft syllabus and subject to potentially major changes before the end of Week 1**

# COGS 108: Data Science in Practice

**Spring 2025**  


---


**Table of Contents**

- [Overview](#Course-Overview)
- [Staff](#COURSE-STAFF)
- [Objectives](#COURSE-OBJECTIVES)
- [Grading](#GRADING)
- [Lecture](#LECTURE)
- [Discussion Section](#DISCUSSION-SECTION)
- [Assignments](#ASSIGNMENTS)
- [Project](#COURSE-PROJECT)
- [Schedule](#COURSE-SCHEDULE)
- [Other Good Stuff](#OTHER-GOOD-STUFF)

<!-- toc -->


# COURSE OVERVIEW

This hands-on, practical course is intended to get you experience working on data science projects.  You may have theoretical knowledge from other courses, but here we are going to implement. Doing something is rarely simple.  You will likely attempt to do something, do it wrong, learn from your mistakes, and with a bit of luck and skill, eventually succeed. That’s just part of the scientific process, and data science is no exception. This course is all about the *practice* of data science.

In focusing on the practice, there is theory that won’t be discussed and mathematical proofs that won’t be done. That is by design. In particular:

- There are entire courses dedicated to each of the topics we’ll cover. To have time to do anything, we can’t teach all the details in a single course.
-  Experts in each of these domains are out there and excited to teach you the nitty gritty about each topic.  TAKE THOSE OPPORTUNITIES... the theory we are skipping is important and useful!
- We’re promoting data literacy. We believe that everyone who is data literate is at an advantage as they go out into the modern world. Data literacy is not limited to those who are computational gurus or math prodigies. You do not have to be either of those to excel at this course.

In this course, you will try many methods. You’ll even be asked to implement a technique that has not been explicitly taught. Again, this is by design. As a data scientist, you’ll regularly be asked to step outside of your comfort zone and into something new. Our goal is to get you as comfortable as possible in that space now. We want to provide you with a technical and a data science mindset that will allow you to ask the right questions for the problem at hand and set off alarm bells when something in your dataset or analysis is “off.”

# COURSE STAFF

| Role           | Name          		 | Section          | Office Hours |  Contact   |   
| ------------:|:--------------------|:-----------------|:-------------|:-------------|
| Instructor   | Jason Fleischer     |   ---         | [Signup for office hours](https://calendar.app.google/RoadDP23hFD5JpuW9) | [jfleischer@ucsd.edu](mailto:jfleischer@ucsd.edu) |
| TA	         |  Reuben Chatterjee     |  A03/B06 | Wednesday 3-5 PM on Google Meet, [Book a slot](https://calendar.app.google/mazHtQXrfZPM6V756) |  rchatterjee@ucsd.edu |
| TA	         |  Zheng Zeng     |  A04/A05 | [Mon 9-11am on Zoom (signup required)](https://calendar.app.google/EMDNqgYmk7K455gz5) |  zhz094@ucsd.edu |
| TA	         |  Ruby (Zhuojun) Ying     |  B01/B2 | [Tues 3-5pm, signup required](https://calendar.app.google/JgkANzBFBd76ihLr9) |  z5ying@ucsd.edu |
| TA	         |  Alessandro "Ollie" D'Amico   |  [A06/A07](https://ucsd.zoom.us/j/94595660887) | [Fri 1-3PM on Zoom (signup required)](https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ3-xXFS4WVzu0oeZBL0y1McaTE5MOkHIch3h1lvL_vWns5DTNQLFzVd8EINTNcyUBEuxvKkin_e?gv=true)| adamico@ucsd.edu  |
| TA	         |  Felipe Lorenzi   |  A01/A02 | [Tue & Thu 1-2PM on Zoom (signup required)](https://calendar.app.google/ZZEMevjv4P8ZUmcm8)| florenzi@ucsd.edu  |
| TA	         |  Alokita Karmokar   |  B05/B07 | [Tue 3-5 PM on Zoom, starting week 2](https://ucsd.zoom.us/j/96637274923)|  akarmokar@ucsd.edu |
| TA	         |  Jason Chen   |  B03/B04 | [Thu 3-5PM on Zoom (signup required)](https://calendar.app.google/WtSA9SmNFpq8Fup49) | xic007@ucsd.edu |
| TA	         |     |  - | - |   |
| IA	         |  Annalise Ahn   |  B04 | Thurs 2-3PM on [Zoom](https://ucsd.zoom.us/my/anahn) |  anahn@ucsd.edu |
| IA	         |   Nandini Bohra  |  A01 | Tue 6-7PM on [Zoom](https://us05web.zoom.us/j/82248774955?pwd=Y7UaacPa0vCHw57L7Rotmsr6gprTEA.1) | nbohra@ucsd.edu  |
| IA	         |  Alec Slim   |  A04 | Thurs 1-2PM on [Zoom](https://ucsd.zoom.us/my/alecslim) |  awslim@ucsd.edu  |
| IA	         |  Kristoffer Alejo   |  A02 | Mon 11-12PM in CSB 114 | kalejo@ucsd.edu  |
| IA	         |  Miles Davis   |  A06/A07 | Wed 11AM-12PM on [Zoom](https://ucsd.zoom.us/j/8310840482) | midavis@ucsd.edu  |
| IA	         |  Aatyanth Thimma Udayakumar   |  B03/B06 | Mon 3-4PM on [Zoom](https://ucsd.zoom.us/j/94828914712)| athimmaudayakumar@ucsd.edu  |
| IA	         |  Jiawei Li   |  A03 | Fri 11-12PM in CSB114 / on [Zoom](https://uchealth.zoom.us/j/86182869016) | jil237@ucsd.edu  |
| IA	         |     |  - | - |   |



Course GitHub: https://github.com/COGS108  

Course discussion, Q&A and regrades: [Link to join Ed](https://edstem.org/us/join/an6dhT), 

Course Canvas: https://canvas.ucsd.edu/courses/64550

Assignment Submission: https://datahub.ucsd.edu  

Anonymous Course Feedback:  https://forms.gle/MnBrvofZY7YxnwYMA

---

# COURSE OBJECTIVES

- Formulate a plan for and complete a data science project from start (question) to finish (communication)
- Explain and carry out descriptive, exploratory, inferential, and predictive analyses in Python
- Communicate results concisely and effectively in reports and presentations
- Identify and explain how to approach an unfamiliar data science task

---

# COURSE MATERIALS
- There is no textbook
- Python (>= 3.9) and a recent version of Jupyter Notebooks.  You may fulfill this by any of the following
  - Datahub
  - A local copy on your own computer (we recommend the Anaconda distribution)
  - Cloud services such as Google Colab, Microsoft Azure, etc. These all have a free tier or free hours before billing.  
- git and a GitHub login
  - If you prefer a GUI feel free to use SourceTree, GitHub Desktop, etc
- All other course materials will be provided on GitHub and datahub


### Optional Readings:

There are no required readings for this course; however, if you’re interested in learning more and reading about data science topics, we recommend the following texts as supplementary to the main elements of the course:

- Grus J (2019, 2nd ed) Data Science from Scratch. This book takes you into HOWs and WHYs, rather than just learning to use a library you don't really understand.  This is the harder book, but you will grow tremendously working though it. [Can be accessed for free through your UCSD login](https://library.ucsd.edu/news-events/oreilly-for-higher-education/)
- Vanderplas, J (2023, 2nd ed) [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook). Short and too the point. Both the text and the code are freely available on Github. Learn to use standard libraries to get things done.

We also maintain [a list of readings that can provide insight into various data science topics](https://github.com/COGS108/Readings).


---

# GRADING

|                | \% of Grade          	 | # to submit |
| -------------: |:-----------------------:|:--------------------------|
| Discussion Labs | 16\%              | 8 (1/wk)      |
| Lecture Quizzes      | 8\%               | 8 out of 9 (1/wk)      |
| Assignments (4@8% ea + 1@1%)         | 33\%		           | 5             |
| Project Review*      | 5\%		           | 1             |
| Project Proposal*    | 9\%		           | 1             |
| Project Checkpoints* (2@5% ea)  | 10\%              | 2             |
| Final Report*        | 15%		           | 1             |
| Final Video*         | 3\%		           | 1             |
| Team Evaluation Survey| 1\%		         | 1             |

\* Indicates Group Submission

**Final exam**: This course has no final exam. Do not show up on the date/time of the final exam.  Instead this course has a final project/

All grades will be released on Canvas. It is *your responsibility to check that your assignment was submitted, that your grade is accurate, and to get in touch if any are missing and/or you think there is a problem*.

Extra credit worth up to 3% of the final grade will be awarded for
- Exceptional participation on EdStem discussion board: Roughly the top 3 - 5% of contributors will get 0.5% bonus to their final grade.  Starting/participating in good discussions, organizing things, answering questions, etc.
- Being present for >= 2/3 of the in class exercises will net 0.5% bonus to the final grade
- Answering the pre & post course surveys will give 0.5% extra credit (0.25% each for 0.5% total)
- Attending guest lecture(s) in-person is 0.5% extra credit  
- Filling out all 7 of the weekly project progress surveys (0.5% of grade, see Project section below)
- If >2/3 of the students fill out SET teaching evaluations at the end of the quarter there will be an extra 0.5% of the final grade for everyone.  BTW this EC criteria has not been met since the zoom classes of the pandemic, why won't the current generation of students actually fill out evals?

Our grading scale is

|    |                  |
|:----|:-----------------|
| A+  | &ge; 97%      |
| A  | < 97% to 94%  |
| A-  | < 94% to 90% |
| B+  | < 90 % to 87% |
| B   | < 87 % to 84% |
| B-  | < 84 % to 80% |
| C+  | < 80 % to 77% |
| C   | < 77 % to 74% |
| C-  | < 74 % to 70% |
| D   | < 70 % to 60% |
| F   | < 60 % |

Know that a third of the class typically feels overwhelmed at the start of the quarter. That said, the average is quite high in this course (typically A-). So, while we anticipate you all doing well in this course, if you are feeling lost or overwhelmed, that’s ok! Should that occur, we recommend: (1) asking questions in class, (2) attending office hours and/or (3) asking for help on EdStem.

### Attendance

I continue to believe that attending in-person is the best way to learn for most people. Our goal is to make the lecture and discussion section worth your while to attend through interactive content and making it a good place to get questions answered. We will also be trying out active learning paradigms this quarter. There will be some live coding exercises both as individuals and some think-pair-share setups.  If you can't come to a particular class session or two that's fine, but if you're planning to never come I think you're making a mistake.

BUT DO NOT COME TO IN-PERSON CLASS IF YOU FEEL SICK!!!  I really don't want our very large lecture hall to become a super-spreader event for any illnesses.

---

# LECTURE

This quarter there are two sections of lecture. For the first two weeks please attend the section you were assigned.  After that there will probably be enough free seats for you to attend the section you prefer, and I'm ok with that.  I will podcast one of the two sections.

| Section |  Time and Location |
|:--------|:---------------------|
| A00 | 9AM MWF Peterson 108 |
| B00 | 2PM  MWF Peterson 108 |

Please bring a smartphone or tablet or laptop to lecture for occaisional live polling via Google Form. Up to 0.5% extra credit will be given for attendance as measured by the number of such exercises you participate in during class. Full extra credit will consist of participating in > 2/3 of lectures that have these exercises (not all lectures have exercises!)

DO NOT COME TO LECTURE IF YOU ARE ILL! You won't miss your attendance extra credit if you take some time off.

### Lecture Quizzes

At the end of each Friday, a quiz with ~10 questions will be released, covering the material from lecture that week. The quiz will be due the following Monday. For example, the first quiz will be released Friday of week 1, covering week 1 material, and will be due the Monday at 11:59 PM of week 2. Each question is worth ~0.1 points and you will have a single, timed (20 min) attempt to complete. *There are no late extensions on quizzes*, but your lowest quiz score will be dropped.

---

# DISCUSSION SECTION

*THERE IS NO SECTION WEEK 0!!!* 

Discussion sections are a place where you will be able to ask questions, get help on technical topics, work on your group projects, and discuss the weekly lab exercises. If you are struggling with course material come to discussion section and/or office hours!

The first discussion section will start in Week 1 with a Python review.  After that week sections will concentrate on helping students with the weekly lab exercises and assignments.

For the first two weeks please attend the section you were assigned.  After that there will probably be enough free seats for you to attend the section you prefer, and I'm ok with that. 

| Section |  Time and Location |
|:--------|:---------------------|
| A01	|	M	11:00a-11:50a	WLH	2207 |
| A02	|	M	1:00p-1:50p	DIB	121 |
| A03	|	F	1:00p-1:50p	DIB	121  |
| A04	|	W	6:00p-6:50p	WLH	2207 |
| A05	|	F	4:00p-4:50p	WLH	2207  |
| A06	|	F	5:00p-5:50p	WLH	2207  |
| A07	|	F	6:00p-6:50p	WLH	2207  |
| B01	|	F	9:00a-9:50a	CSB	4  |
| B02	|	F	10:00a-10:50a	CSB	4 |
| B03	|	F	11:00a-11:50a	CSB	5  |
| B04	|	W	4:00p-4:50p	PETER	102  |
| B05	|	W	6:00p-6:50p	PETER	102  |
| B06	|	F	4:00p-4:50p	PETER	103  |
| B07	|	F	6:00p-6:50p	PETER	102  |


### Discussion section lab exercises

Each week there will be a short lab exercise to review material from lecture and give hands-on programming experience. You can work on these exercises in your lab sections, and your section leaders will be happy to help guide you towards the correct answers.  Or if you don't need help you can complete them on your own and never come to lab.  If you wish to work collaboratively on lab exercises you may do so, but please realize that this is your time to practice and learn new skills with low stakes. If someone else does it for you its hard to practice and learn!

Lab exercises will be due on Fridays 11:59PM and released one week before they are due. If lab exercises are due on a holiday (Veteran's day, Thanksgiving) then they will be accepted until the following non-holiday day that week.  Each lab exercise is worth 2 points. 

---

# ASSIGNMENTS

If lab exercises are low stakes and you can get lots of help, then assignments are high stakes and you can only get minimal help. They will be completed **individually** in Jupyter Notebooks and both released and submitted on datahub.

The practice of data science involves writing code to answer questions and accomplish tasks. Thus, to get practice, your assignments will require you to use Python to do just that. Not everything will be explicitly mapped out step-by-step for you. This is intentional. Figuring things out when it’s not entirely clear what to do next is part of the practice here. You’ll attempt things that won’t work and become comfortable with this. You’ll get stuck and work to get unstuck. Not quite knowing exactly what’s going on at all times is part of the process. And, to be honest, part of the job of being a data scientist.

That said, the first two assignments will be the simplest assignments and aim to get you up to speed in Python and familiar with `pandas`. If the first two assignments are particularly difficult for you, that’s ok. But, it’s then up to you to determine if you want to put in the work to make it through the rest of the quarter. **Assignments will take more time and be more difficult starting with the third assignment**.

As assignments become more difficult, we don’t want you to get or feel totally lost. If you’ve thought long and hard, gone down a long rabbithole on Stack Overflow, and can’t even get a sense of what the next step may be, take a step away. Take a break. Then, come back and see if you can’t solve it with a refreshed mind. If you’re still totally stuck, ask on EdStem, talk to a classmate, and/or attend office hours for help.

With regards to asking questions of instructional staff, we’re here to help you, but there are way more students than there are instructors. So, help each other. In fact, this is how the best data science gets done. Diverse minds solving a problem invariably improves the solution. Also, teaching something to someone else is the best way to determine if you really know something. So, it’s win-win. The person who’s stuck gets unstuck and the person who helped is more sure in their knowledge. Help one another! Section and office hours are meant to be collaborative.

But how should you help one another on assignments? You should: ask a question that leads the student to figure it out for themselves, point out the correct principle/theory that applies in this case, provide a link to an explanation, or a chunk of pseudo-code.  You should not: provide the full answer or code they can just copy/paste.

### Turning In Assignments

Assignments will be submitted individually on datahub. We’ll talk about the details for submission in class. Assignments will always be released a week before the assignment due date. On weeks with assignment deadlines, they will always be due Wednesdays at 11:59 PM of the week specified (see Course Schedule below).

**Check to ensure that your file shows up under “Submitted assignments” on datahub after you click submit!!!**. If the file is the incorrect version of the file, corrupted, or otherwise unreadable, then you will lose the appropriate number of points. If you accidentally click submit after the deadline and before we grade it then we will mark your assignment as late. There will be at least a dozen people each quarter who tell say "I'm so sorry there was a mistak when I clicked submit! Can I please get it graded without late?" And my answer will be no. Do not be that person!

It is your responsibility to ensure that we receive a submission from you on datahub and that you submit the correct file (a Jupyter notebook with the .ipynb extension with the same file name as the assignment) for each assignment. If you identify that a mistake has been made, it is your responsibility to get in touch on EdStem should a problem arise. You will receive individualized feedback via email with your grade and feedback about a week after each assignment is due.


### Assignment Regrades

We will work hard to grade everyone fairly and return assignments quickly. But, we know you also work hard and want you to receive the grade you’ve earned. Occasionally, grading mistakes do happen, and it's important to us to correct them.

If you think there is a mistake in your grade, request a regrade within 72 hours of your receipt of the grade on EdStem, using the "Regrade requests" folder.  This message should include evidence of why you think your answer was correct (i.e. a specific reference to something said in lecture) and should point to the specific part of the assignment in question.

Note that points will *not* be rewarded if you fail to follow instructions. For example, if the instructions say to name the variable `orange` and you name it `ornage` (misspelled), you will not be rewarded credit upon regrade. This is because (1) following instructions and being detail-oriented is important and (2) there are hundreds of students taking the course this quarter. It would be an unfair burden to place on TAs if we didn’t have this policy.

---
# In-person illness policy
Please do not attend any in-person activity (lecture/section/office hours) if you are feeling ill, especially if you are sneezing/coughing and have a fever. If you feel mildly ill but without sneezing/coughing, or if you have bad allergies, then you may come to in-person events while wearing a well-fitting mask.  


# LATE POLICY

Lecture quizzes will not be accepted late.

Assignments and labs will be accepted up to 5 days late with a 25% late penalty taken off your grade. Every student receives 7 free late days with NO DEDUCTION for use on any assignment or lab exercise. Without penalty, you can turn in 7 work items one day late each, or 1 work item 3 days late and another 4 days late, or any other combination. 

PLEASE NOTE while your pool of late days is 7, your maximum lateness on any single assignment is 5 days.  PLEASE NOTE these late days are intended for use when you are behind and need an extra day, illness, family emergencies, mental health crises, etc.. You will not be given more late days. You will not be given more than 5 days to get something submitted.  If you cannot manage to turn in assignments within this system you need to talk with your dean because something has gone drastically wrong that cannot be handled in my class.


# COURSE PROJECT

Your course project will be completed in a group of 4-5 people. The reality of data science is that you will have to work with others. You’ll need to work together to communicate effectively, manage time, organize your projects, and accomplish a goal. People will have different knowledge and skills sets. It is your job as a group to work together to figure out how to maximize each group member’s skills to make sure that your differences are helpful to accomplishing your goal, rather than a hindrance. For example, some of you will find the programming aspects of the class assignments very easy, while others will struggle. Alternatively, some of you may find experimental research and hypothesis testing intuitive, while others find it confusing and frustrating. It is best for your project if you choose a team with a mix of background and experience.

### Finding A Group

Finding a group may be a tad trickier this quarter. As such, we'll offer additional support. Groups can be found in a few different ways:

1. If you have people in the class you know you want to work with, chat with one another and if you're all on board, form a group.
2. There will be time to find groups in discussion section during week 1 & 2.
3. If you don't know people in the class or don't have people you want to work with, no problem. Seek them out on EdStem!

You will submit who your group is via Google Form by the Wednesday of week 3 (see Course Schedule). One form will be submitted per group.

If you do not signup for a group you will be randomly assigned a group. However you generally don't want that, you'll have more fun if you get on board with people who want to work on the same thing as you. Also in my experience the randomly assigned groups have more trouble than the ones students put together on their own.

Probably the most important way to start a team off on the right foot is to discuss expectations of how you will work together.  How will you divide up the work? How often and where will you meet? How will you communicate with each other? What's the maximum amount of time it should take for someone to respond to a message?  How will you double check that things that need to happen did happen? If there is a problem meeting a deadline how should the person responsible let others know, and then how should the rest of the team react? There are many possible answers to these questions, and there are many more questions about expectations that you might want to ask yourselves. Your team should decide what's right for you, _and then write down these expectations in a place that the team will often see it_.  Trust me, this will help things go more smoothly.  


### Project Components

These project components are completed and submitted *as a group* and are described in the Project documentation: https://github.com/COGS108/Projects. This includes: 1) Previous Project Review 2) Project Proposal 3) Project Checkpoint #1: Data, 4) Project Checkpoint #2: EDA, 5) Final Project Report, and 6) Final Project Video

There are also components of the project that must be completed individually. Starting week 3, there will be an *optional* weekly survey to be completed individually describing your project progress. Students who complete all 7 weeks' surveys will earn 0.5% extra credit to their final grade. At the end of the course there is a team evaluation survey... this is your opportunity to let us know if a teammate did not contribute 

---

# COURSE SCHEDULE
|        | Week   | Day | Lecture topic                | Section covers | Lab due | Assignment due                                                 | Lecture quiz due |
| ------ | ------ | --- | ---------------------------- | -------------- | ------- | -------------------------------------------------------------- | ---------------- |
| Mar-31 | 1      | M   | Welcome!                     | Python review  |         |                                                                |                  |
| Apr-02 | 1      | W   | Version Control I            | Python review  |         |                                                                |                  |
| Apr-04 | 1      | F   | Version Control II           | Python review  |         |                                                                |                  |
| Apr-07 | 2      | M   | Data & Intuition I           | D1             |         |                                                                | Q1               |
| Apr-09 | 2      | W   | Data & Intuition II          | D1             |         | Practice assignment, pre-course survey                         |                  |
| Apr-11 | 2      | F   | Data Wrangling (pandas)      | D1             | D1      |                                                                |                  |
| Apr-14 | 3      | M   | Ethics                       | D2             |         |                                                                | Q2               |
| Apr-16 | 3      | W   | Data Science questions       | D2             |         | A1, GitHub ID, Group signup                                    |                  |
| Apr-18 | 3      | F   | Data viz principles          | D2             | D2      |                                                                |                  |
| Apr-21 | 4      | M   | Intro to analysis            | D3             |         |                                                                | Q3               |
| Apr-23 | 4      | W   | EDA                          | D3             |         | Project Review\*                                               |                  |
| Apr-25 | 4      | F   | EDA II                       | D3             | D3      |                                                                |                  |
| Apr-28 | 5      | M   | Inference I                  | D4             |         |                                                                | Q4               |
| Apr-30 | 5      | W   | Inference II                 | D4             |         | Project Proposal\*                                             |                  |
| May-02 | 5      | F   | Inference III                | D4             | D4      |                                                                |                  |
| May-05 | 6      | M   | Inference IV - Nonparametric | D5             |         |                                                                | Q5               |
| May-07 | 6      | W   | Text Analysis I              | D5             |         | A2                                                             |                  |
| May-09 | 6      | F   | Text Analysis II             | D5             | D5      |                                                                |                  |
| May-12 | 7      | M   | Machine Learning I           | D6             |         |                                                                | Q6               |
| May-14 | 7      | W   | Machine Learning II          | D6             |         | Checkpoint #1: Data\*                                          |                  |
| May-16 | 7      | F   | Machine Learning III         | D6             | D6      |                                                                |                  |
| May-19 | 8      | M   | Machine Learning IV          | D7             |         |                                                                | Q7               |
| May-21 | 8      | W   | Dimensionality Reduction     | D7             |         | A3                                                             |                  |
| May-23 | 8      | F   | Geospatial                   | D7             | D7      |                                                                |                  |
| May-26 | 9      | M   | No class - Memorial day      | D8             |         |                                                                | Q8               |
| May-28 | 9      | W   | How to be wrong              | D8             |         | Checkpoint #2: EDA\*                                           |                  |
| May-30 | 9      | F   | How to be wrong II           | D8             | D8      |                                                                |                  |
| Jun-02 | 10     | M   | Algorithms                   | Projects       |         |                                                                | Q9               |
| Jun-04 | 10     | W   | Guest lecture                | Projects       |         | A4                                                             |                  |
| Jun-06 | 10     | F   | Data science jobs            | Projects       |         |                                                                |                  |
| Jun-09 | Finals | M   | NO FINAL EXAM                |                |         |                                                                |                  |
| Jun-11 | Finals | W   | NO FINAL EXAM                |                |         | Final project\*, video\*, team eval survey, post-course survey                                                               |                  |
| Jun-13 | Finals | F   | NO FINAL EXAM                |                |         |  |              |

\* indicates group submission. All other assignments/quizzes/surveys are completed & submitted individually.

---

# OTHER GOOD STUFF

### Class Conduct

In all interactions in this class, you are expected to be respectful. This includes following the [UC San Diego principles of community](https://ucsd.edu/about/principles.html) .

This class will be a welcoming, inclusive, and harassment-free experience for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, ethnicity, religion (or lack thereof), political beliefs/leanings, or technology choices.

At all times, you should be considerate and respectful. Always refrain from demeaning, discriminatory, or harassing behavior and speech. Last of all, take care of each other.

If you have a concern, please speak with anyone on the instruction team (professor, TAs, or IAs). If you are uncomfortable doing so, that’s ok! The [OPHD](https://blink.ucsd.edu/HR/policies/sexual/OPHD.html) (Office for the Prevention of Sexual Harassment and Discrimination) and [CARE](https://care.ucsd.edu/) (confidential advocacy and education office for sexual violence and gender-based violence) are wonderful resources on campus.  

### Academic integrity
Don't cheat.  Here are some [flyers on important aspects of academic integrity every student should know](https://academicintegrity.ucsd.edu/excel-integrity/Resources%20.html). You can also obtain deeper training from Academic Integrity, click around their website and explore!

You will work together on projects. You should help one another learn in general.  Assignments and discussion labs should be completed individually, although you may seek help from your fellow students. However you may not give answers to each other at any time. In discussion labs its ok to be much more leading and provide more of the answer.  In assignments you should be more careful about how much detail you are providing in your help to others.


Examples of good collaboration on assignments: 
- Student posts non-working code to get help, others send a link to a good reference page in sklearn documentation, or point out the generic kind of mistake being made (e.g., you’ve messed up the order of operations). Nobody just writes the correct code for the student.
- Student posts a question about a theory or concept.  If its not directly related to an assignment question you can choose to answer in full.  However, it’s generally more helpful for learning if you use the Socratic method: ask the student questions that lead them to find the answer themselves.  Also doing this helps you cement your own knowledge of the subject!  
- Student posts a question about an assignment problem. Others  point out important principles that we have learned in class that can be used to solve it. They describe the important points, or mention important pitfalls to avoid. References to book pages, lecture slides, or lecture video times are helpful. Nobody posts the correct answer for the student.

For group projects, you will work together but every person in the group is expected to understand every aspect of the project.  People may be asked to individually explain any aspect of the project and your grade may be reduced compared to the rest of the group if you are unable to do so. Projects may include ideas and code from other sources—but these other sources must be documented with clear attribution.

Cheating and plagiarism have been and will be strongly penalized. 
 

### Policy on using AI programming assistance

I believe that using large language models (LLMs) or other kinds of AIs can help a good programmer work more efficiently. I also believe that using AI assistance will probably slow down the development of a beginning programmer into a good programmer.  

My advice: if you struggle to conceptualize how you want to write a program you should probably NOT use an LLM. The beginning or intermediate programmer needs to practice their craft... just like you will never get to be great at a video game by just watching other people's speed runs. I think its fine to use AI assistance if you can immediately imagine how to solve the problem, but you just want help with boring implementation details, or to see alternative algorithms you could use, or help writing it faster.

You can use AI to help you program as long as you:
- make a code comment that cites the AI used, and provides an estimate of how much code in a given block is machine generated.  For instance you might write this ```# The (code/design) of this function is (completely/mostly/partially) generated by Github Copilot from the prompt "write a python function to bubble sort a list"```  Feel free to include a description of any specific changes you made from the machine generated code... it was edited to reduce execution time, to deal with edge cases, to deal with an empty data file, etc..
- don't assume LLM code is working and just hand in without checking. You are always responsible for functionality and understanding how something works.
- understand that programming with LLMs still requires you to do programming. But instead of creating code from scratch (the part many people enjoy) you will need to do debugging and unit testing (the part many people don't like)
- you understand that you may be asked to explain your code at any time. If you can't explain how your code works and why the design is that way you may lose points

## Policy on using AI writing assistance

My beliefs here mirror the section on programming, but with an important extra problem.

I believe using LLMs can help a good writer work more efficiently. I also believe that using AI assistance will probably slow down the development of a poor writer. Even worse, current LLMs tend to produce B+ writing and C+ thinking and arguments. 

IMO the only way to use LLMs for writing and thinking is to use them the same way you would a teammate with unreliable writing skills.  Bounce ideas off the AI. Let it produce writing and then read it with a critical eye.  Carefully edit the output to remove poor logic, false citations that don't exist, trite expressions, and poor rhetoric.  Given that its an AI you can ask it to produce the output multiple times and start from the best of the lot... then edit mercilessly. 

You can use AI to help you write as long as you
- make a footnote that cites the AI used, and provides an estimate of how much text in a given block is machine generated. For instance you might write ```This (text/ideas) in this chapter were (completely/mostly/partially)  generated by GPT-4 from the prompt "describe the ethical issues that need to be considered when using data scraped from public posts on social media for an analysis of an upcoming election"```  Feel free to include a description of any specific changes you made from the machine generated text... the text was edited to remove wordiness, wrong citations were removed and replaced with actual cites, some aspects of the ideas and structure of the machine text served as inspiration for a full rewrite, etc..
- don't assume the LLM text is good without examining it closely for issues we list above. 


## Disability Access

Students requesting accommodations due to a disability must provide a current Authorization for Accommodation (AFA) letter. These letters are issued by the Office for Students with Disabilities (OSD), which is located in University Center 202 behind Center Hall. Please make arrangements to contact Prof Ellis privately to arrange accommodations. If you are struggling to get a meeting with OSD, you can let Prof Ellis know and she’s likely able to help accommodate while you work to get official documentation.
Contacting the OSD can help you further:
858.534.4382 (phone)
[osd@ucsd.edu](mailto:osd@ucsd.edu) (email)
http://disabilities.ucsd.edu

## Difficult life situations

Sometimes life outside of academia can be difficult. Please [email me](mailto:jfleischer@ucsd.edu) or [come to office hours](https://calendar.google.com/calendar/selfsched?sstoken=UUFzQ2RXR3dOVnZwfGRlZmF1bHR8Nzg4NGE1Yzc1NmM0NGJlNzUyZmNjMzgxNGUzYWQ1NzM) if stuff outside the classroom prevents you from doing well inside it. I can often refer you on to the help you need.

If you don't have the most essential resources required to thrive as a student, please contact [UCSD Basic Needs](https://basicneeds.ucsd.edu) who can help you access nutritious food and stable housing, and help you seek the means to reach financial wellness.

If you need emergency food, finances, and/or academic and social support you can also contact [UCSD Mutual Aid](https://mutualaiducsd.wordpress.com). They provide mentoring and aid that comes from volunteers among your peers.  If you don't need that kind of support, consider joining them in helping your fellow classmates who do.

If you need counseling or if you are in a mental crisis you can contact [CAPS](https://caps.ucsd.edu). They provide psychiatric services, workshops, and counseling; they also operate a 24/7 crisis hotline at 858.534.3755

### Letters of recommendation

TL;DR If you want a letter I advise you to work as an IA or RA or some other capacity with more than one professor. 

If you are bound for graduate school you will probably need letters from 2 or 3 people. Many students ask professors they have taken a class from, but I want you to know this is a bad idea. You really want to get a letter from someone you have worked with more closely, who knows your talents and personality from experience working together with you over a long time. You are one of hundreds of students I will have this quarter. TBH with relatively few exceptions I will not know you well. To get a solid letter from a prof, you want to be a research assistant, independent study, honors thesis advisee, or instructional assistant. If you are interested in grad school you need to have done the work _before_ the beginning of senior year; letters are needed in Nov/Dec of your senior year for the following Fall admission.

If you are just one of the hundreds of students in a class, then most profs (including me) probably won't write you a letter.  If they do, at best you will get a letter that is roughly "STUDENT was in my CLASS where they got an A+". Every graduate school admission committee in the world can read between the lines and see that this is not a good recommendation. Any kind of selective program will probably take a hard pass given a letter like that.

If you are an assistant (research/instructional/etc) or an honors advisee then your mentor will definitely write you a letter.  And the letter you will go much much harder and into great detail about your qualities. And that kind of detailed, informative letter is what graduate admissions committees want to see.

What if you don’t have the right history to get a detailed letter from a professor? I think that a detailed letter from another source is probably better for admissions than a minimum letter from a prof. Ask your manager from when you did an internship related to your chosen field, the head of a volunteer organization you work with, a grad student you worked for on a research project, etc.  Someone that has been to grad school is best, but even someone without grad experience who knows you well is a potentially useful letter.

WARNING:  I have had to scale back my minimum letter writing for students in my class.  You can ask, I will probably say no.  Because of other time commitments I will only write minimum letters for a handful of students per quarter  who were in the top 10% of the grade distribution.  And because this class is so easy, don't assume just because you have an A+ that you are in that top 10%.


### What should you call me?

Most students call me Professor Fleischer or Dr. Fleischer. My last name is pronounced "fly-sure". My pronouns are he/him.

If you’re into old skool slam dunks you can call me Dr. J. I'm also perfectly happy if you call me Jason, but not all professors are OK with that kind of informality. Please do not address me as Mr. Fleischer; if you're going to use an honorific please use the one that people expect in the situation.

### What I should call you

I should call you by your preferred name, with the correct pronunciation and any honorific or pronouns you choose. Please correct me if I ever make a mistake.

### How to Get Your Question(s) Answered and/or Provide Feedback

It’s great that we have so many ways to communicate, but it can get tricky to figure out who to contact or where your question belongs or when to expect a response. These guidelines are to help you get your question answered as quickly as possible and to ensure that we’re able to get to everyone’s questions.

That said, to ensure that we’re respecting their time, TAs and IAs have been instructed they’re only obligated to answer questions between normal working hours (M-F 9am-5pm). However, I know that’s not when you may be doing your work. So, please feel free to post whenever is best for you while knowing that if you post late at night or on a weekend, you may not get a response until the next day. As such, do your best not to wait until the last minute to ask a question.

**If you have…**

- **Questions about course content**: these are awesome! We want everyone to see them and have their questions answered too… so post these to the EdStem discussion board!
- **A technical assignment question**: Come to office hours, because answering technical questions is often best accomplished in person where we can discuss the question and talk through ideas. However, if that is not possible, post your question to the discussion board. Be as specific as you can in the question you ask. And, for those answering, help your classmates as much as you can without just giving the answer. Help guide them, point them in a direction, provide pseudo code, but do not provide code that answers assignment questions.
- **Been stuck on something for a while (>30min) and aren’t even really sure where to start**: Programming can be frustrating and it may not always be obvious what is going wrong or why something isn’t working. That’s ok - we’ve all been there! IF you are stuck, you can and should reach out for help, even if you aren’t exactly sure what your specific question is. To determine when to reach out, consider the 2-hour rule. This rule states that if you are stuck, work on that problem for an hour. Then, take a 30 minute break and do something else. When you come back after your break, try for another 30 minutes or so to solve your problem. If you are still completely stuck, stop and contact us (office hours, post on EdStem). If you don’t have a specific question, include the information you have (what you’re stuck on, the code you’ve been trying that hasn’t been happening, and/or the error messages you’ve been getting).
- **Questions about course logistics**: First, check the syllabus. If the answer is not there, ask a classmate. If you still are unsure,  post on EdStem
- **Questions about a grade**: Post a note to instructors on EdStem and select the ‘regrade requests’ tag. Include specifics as to why you feel you mistakenly/unfairly lost points in that post.
- **Something super cool to share related to class**: feel free to post on EdStem ('social' tag), email the prof, or come to office hours. Be sure to include COG S108 in the email subject line and your full name in your message.
- **Something you want to talk about in-depth**: meet in person during office hours or schedule a time to meet by email. Be sure to include COGS 108 in the email subject line.
- **Some feedback about the course you want to share anonymously**: If you’ve been offended by an example in class, really liked or disliked a lesson, or wish there were something covered in class that wasn’t but would rather not share this publicly, etc., please fill out the anonymous [Google Form](https://forms.gle/MnBrvofZY7YxnwYMA)
