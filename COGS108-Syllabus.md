v1.01 - 2022-01-05 - still subject to change!, check back regularly

# COGS 108: Data Science in Practice

**Winter 2021**  
**MWF 2-2:50pm**  
**Jan 3 - Jan 17: Zoom only**  
**Jan 19 - Mar 11: Zoom or in-person at The Jeannie Auditorium (GAA), New Sixth College**
---

**Lecture link (new version as of Jan 5, capable of hosting up to 500 people)**<br>
https://ucsd.zoom.us/j/97892507343?pwd=TjVhcGlJVzc2VFZmbU9oOE11WVpzZz09<br>
Meeting ID: 978 9250 7343 Password: cogs108


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

This hands-on, practical course is intended to get you experience working on data science projects. This class goes beyond the appreciation for data and data science you (may have) learned in COGS 9 by *doing* the same things we talked about theoretically in that introductory course. Doing is rarely so simple. You will likely attempt to do something, do it wrong, learn from your mistakes, and with a bit of luck and skill, eventually succeed. That’s just part of the scientific process, and data science is no exception. This course is all about the *practice* of data science.

In focusing on the practice, there is theory that won’t be discussed and mathematical proofs that won’t be done. That is by design. In particular:

1. There are entire courses dedicated to each of the topics we’ll cover. To have time to do anything, we can’t teach all the details in a single course.
2. Experts in each of these domains are out there and excited to teach you the nitty gritty about each topic.
3. We’re promoting data literacy. We believe that everyone who is data literate is at an advantage as they go out into the modern world. Data literacy is not limited to those who are computational gurus or math prodigies. You do not have to be either of those to excel at this course.

In this course, you will try many methods. You’ll even be asked to implement a technique that has not been explicitly taught. Again, this is by design. As a data scientist, you’ll regularly be asked to step outside of your comfort zone and into something new. Our goal is to get you as comfortable as possible in that space now. We want to provide you with a technical and a data science mindset that will allow you to ask the right questions for the problem at hand and set off alarm bells when something in your dataset or analysis is “off.”

# COURSE STAFF

| Role           | Name          		 | Section          | Office Hours |  Contact   |   
| ------------:|:--------------------|:-----------------|:-------------|:-------------|
| Instructor   | Jason Fleischer     |   [Lecture](https://ucsd.zoom.us/j/97892507343?pwd=TjVhcGlJVzc2VFZmbU9oOE11WVpzZz09)          | [Signup for the kind of OH slot you want: Zoom or in-person](https://calendar.google.com/calendar/selfsched?sstoken=UUFzQ2RXR3dOVnZwfGRlZmF1bHR8Nzg4NGE1Yzc1NmM0NGJlNzUyZmNjMzgxNGUzYWQ1NzM)          | [jfleischer@ucsd.edu](mailto:jfleischer@ucsd.edu) |
| TA 	         | Areeb Syed          | [A06-A07](https://ucsd.zoom.us/j/93746878731) (remote)| [WED 12-2 PM](https://ucsd.zoom.us/j/91804764453) / By appointment (remote)| aas050@ucsd.edu|
| TA	         | Pooja Pathak        | [A01](https://ucsd.zoom.us/j/92981057446), [A05](https://ucsd.zoom.us/j/98007206877) (remote)  | [MON 4pm-6pm](https://ucsd.zoom.us/j/99600138341)/By appointment (remote)  | [pmpathak@ucsd.edu](mailto:pmpathak@ucsd.edu)   |
| TA 	         | Stephen Jarrell     | [A04](https://ucsd.zoom.us/j/99127125109?pwd=eUJ6UVhwRk4rU0RCNm8xM2M3VXBBQT09) (remote)  | [WED 10am-12pm](https://ucsd.zoom.us/j/99127125109?pwd=eUJ6UVhwRk4rU0RCNm8xM2M3VXBBQT09)/By appointment (remote) | [njarrell@ucsd.edu](mailto:njarrell@ucsd.edu)   |
| TA           | Matthew Feigelis    | [A02-A03](https://ucsd.zoom.us/j/99726557342) (remote)| [TUES 3-5 PM](https://ucsd.zoom.us/j/92086421659) / By appointment (remote) | mfeigelis@ucsd.edu  |
| IA	         |  Jiazheng Bian      | None | [MON 5pm-6pm](https://ucsd.zoom.us/j/93343151780)/By appointment (remote) | [jibian@ucsd.edu](mailto:jibian@ucsd.edu) |
| IA	         |  Sahithi Chimmula   |   |  |   |
| IA           |  Luning Yang        |  None | [THUS 7pm-8pm](https://ucsd.zoom.us/j/99194275380)/By appointment (remote) | [l4yang@ucsd.edu](mailto:l4yang@ucsd.edu) 
| IA           |  Ruoxuan Li         |  None | [TUES 4pm-5pm](https://ucsd.zoom.us/j/98565002417)/By appointment (remote) | [ruli@ucsd.edu](mailto:ruli@ucsd.edu)  |
| IA           |  Jiayi Zhao         |  None | [TUES 5pm-6pm](https://ucsd.zoom.us/j/96085281848)/By appointment (remote) | [j4zhao@ucsd.edu](mailto:j4zhao@ucsd.edu)  |
| IA           |  Zhigang Lin        |  None | [FRI 5pm-6pm](https://ucsd.zoom.us/j/5280072289)/By appointment (remote) | [zhl069@ucsd.edu](mailto:zhl069@ucsd.edu)  |

Lecture zoom link: https://ucsd.zoom.us/j/97892507343?pwd=TjVhcGlJVzc2VFZmbU9oOE11WVpzZz09

Course GitHub: https://github.com/COGS108  

Course Piazza*: https://piazza.com/ucsd/winter2022/cogs108

Course Canvas: https://canvas.ucsd.edu/courses/32573

Assignment Submission: https://datahub.ucsd.edu  

Anonymous Course Feedback: [Fill out this form](https://forms.gle/RkNrZtRz8nDaEq8d7)

*You will be able to post anonymously on Piazza; however, you will only be anonymous to your classmates. Your Instructor and TAs will be able to see who you are.

---

# COURSE OBJECTIVES

- Formulate a plan for and complete a data science project from start (question) to finish (communication)
- Explain and carry out descriptive, exploratory, inferential, and predictive analyses in Python
- Communicate results concisely and effectively in reports and presentations
- Identify and explain how to approach an unfamiliar data science task

---

# COURSE MATERIALS
- There is no textbook
- All materials will be provided on GitHub/datahub
- iclickers will NOT be used this quarter
- Python (>= 3.7) and Jupyter Notebooks.  You may fulfill this by any of the following
  - Datahub
  - A local copy on your own computer (we recommend the Anaconda distribution)
  - Cloud services such as Google Colab, Microsoft Azure, etc. These all have a free tier or free hours before billing.  
- git and GitHub (option to use a GUI such as SourceTree, GitHub Desktop, etc)


### Optional Readings:

There are no required readings for this course; however, if you’re interested in learning more and reading about data science topics, we recommend the following texts as supplementary to the main elements of the course:

- Grus J (2019, 2nd ed) Data Science from Scratch. This book takes you into HOWs and WHYs, rather than just learning to use a library you don't really understand.  This is the harder book, but you will grow tremendously working though it.
- Vanderplas, J (2018) [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook). Short and too the point. Both the text and the code are freely available on Github. Learn to use standard libraries to get things done.

We also maintain [a list of readings that can provide insight into various data science topics](https://github.com/COGS108/Readings).


---

# GRADING

|                | \% of Grade          	 | # to submit |
| -------------: |:-----------------------:|:--------------------------|
| Discussion Labs | 16\%              | 8 out of 9 (1/wk)      |
| Lecture Quizzes      | 8\%               | 8 out of 9 (1/wk)      |
| Assignments          | 32\%		           | 4             |
| Project Planning Survey* | 1\%		       | 1             |
| Project Review*      | 5\%		           | 1             |
| Project Proposal*    | 8\%		           | 1             |
| Project Checkpoints*   | 10\%              | 2             |
| Final Report*        | 15%		           | 1             |
| Final Video*         | 3\%		           | 1             |
| Team Evaluation Survey| 2\%		         | 1             |

\* Indicates Group Submission

**Final exam**: This course has no final exam. Do not show up on the date/time of the final exam.  Instead this course has a final project. The project deadline is March 14th at 11:59 PM

All grades will be released on Canvas. It is *your responsibility to check that your assignment was submitted, that your grade is accurate, and to get in touch if any are missing and/or you think there is a problem*.

Extra credit worth up to 2.5% of the final grade will be awarded for
- Exceptional participation on Piazza: Roughly the top 3% of contributors will get 0.5% bonus to their final grade.  Starting/participating in good discussions, organizing things, answering questions, etc.   
- Answering the pre & post course surveys will give 0.5% extra credit (0.25% each)
- Attending both guest lectures either in-person or on Zoom is 0.25% extra credit  
- Submitting at least one question to the queue for at least one of the guest lectures is 0.25% extra credit
- Filling out all 7 of the weekly project progress surveys (0.5% of grade, see Project setion below)
- If >75% of the students fill out CAPE at the end of the quarter there will be an extra 0.5% of the final grade for everyone

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


### Attendance

I continue to believe that attending in-person is the best way to learn for most people. Our goal is to make the lecture and discussion section worth your while to attend. But no one will be forced to, there is a pandemic and many extenuating circumstances. You're adults, you will know what fits your constraints and needs.

The only exception is for the two planned guest lectures. If the situation permits live lectures, we will strongly encourage you to attend in-person so that we may show respect to our guests.  

That said, there is no component of your grade that is based on attendance or live participation. DO NOT COME TO IN-PERSON CLASS IF YOU FEEL SNIFFLY OR SICK!!!  I really don't want our very large lecture hall to become a super-spreader event for any illnesses.

---

# LECTURE

Lectures are MWF 2-2:50pm. For the 1st two weeks we (and all of UCSD) will be remote only, operating on Zoom. Starting Wed Jan 19th lecture will be in The Jeannie (GAA) Auditorium. It is part of New Sixth College, located on the SE corner of the North Torrey Pines Living + Learning Neighborhood, just to the west of Peterson Hall, and just north of AP&M.

In-person lectures will be offered as a hybrid class: they will be in-person, available synchronously online via Zoom, and recorded for your later viewing. Those on Zoom will be able to ask questions but may not be able to participate in some useful class exercises.

For in-person lectures **a negative symptom check from that day and a properly worn mask of the correct type are required to attend!** For more information please see [Return to Learn requirements for on-campus activities](https://returntolearn.ucsd.edu/return-to-campus/campus-repopulation/index.html).

Those concerns aside, don't let me scare you away from coming to lecture in-person: it is the most engaging way you can absorb the material and it gives you the best opportunity to be an active participant. Students who actively engage in the learning process do better than those who passively absorb material given to them. I hope that my strict illness policies encourage students who wish to attend in-person to do so.

In-person lectures will be broadcast simultaneously [on this UPDATED ON JAN 5 Zoom link](https://ucsd.zoom.us/j/97892507343?pwd=TjVhcGlJVzc2VFZmbU9oOE11WVpzZz09
) If for some reason that link doesn't work, the Meeting ID is 978 9250 7343 and the password is cogs108. You can also use our Canvas page to start Zoom with the proper link.

Every lecture will also be recorded and shared so that students who are not able to or choose not to watch during the scheduled class time are still able to receive and digest all class materials. Lecture recordings will be available on podcast.ucsd.edu Canvas in the Media Gallery no later than 5PM the day the live lecture is delivered.

### Lecture Quizzes

After class each Friday, a quiz with ~10 questions will be released, covering the material from lecture that week. The quiz will be due at 11:59PM the following Monday. For example, the first quiz will be released Friday of week 1, covering week 1 material, and will be due the Monday at 11:59 PM of week 2. Each question is worth ~0.1 points and you will have a single attempt to complete. There are no late extensions on quizzes, but your lowest quiz score will be dropped.

---

# DISCUSSION SECTION

**Discussion sections are starting out completely remote on Zoom.** See the table above and Canvas calendar for the correct links.  At this point we plan to transition discussion sections to in-person on Jan 14.  We will keep you up to date on any changes.

Week 1 discussion sections will be for finding group mates for the project. Regular discussion sections will begin Monday of week 2.

| Section |  Date/Time | Location (ZOOM ONLY FOR NOW!) |
|:--------|:-----------|:----------|
| A01	| F	11-11:50a	| ~~MANDE	B-150~~ | 	 
| A02 | F	12-12:50p	| ~~PETER	102~~ | 	
| A03	| F	1-1:50p	| ~~PETER	103~~ | 	
| A04	| W	9-9:50a	| ~~PETER	102~~ | 	
| A05	| M	12-12:50p | ~~PETER	103~~	|
| A06	| W	4-4:50p	| ~~PETER	104~~ | 	
| A07	| W	5-5:50p	| ~~PETER	103~~	|

### Discussion section lab exercises

Each week (starting week 2) there will be a short, guided lab exercise to review material from lecture and give hands-on programming experience.  These lab exercises will be released on the Friday BEFORE the corresponding lab section. Students will have a week to complete them, so they are due the Friday AFTER the corresponding lab section. To complete the lab exercise, you do NOT need to physically show up to discussion section. There will be 9 discussion lab exercises. Each is worth 2 points. The lowest discussion lab score will be dropped. There are no late submissions for discussion labs.


### Technical discussion sections
Each week one of the seven sections will be a technical session, focussed on the discussion lab exercises.  The technical section will rotate; Week 2 it will be A01, Week 3 it will be A02, etc.. The technical section will be recorded so that students who couldn't attend can watch later.

If you cannot attend a given technical section you can still ask your question on Piazza using the category "Discussion section - technical".   If you ask your question BEFORE the section the TA will try to answer on the recorded video as well as online.

Students who are less comfortable with the programming and other technical aspects of the course are encouraged to attend each weeks technical discussion section live or watch the video recording.

During technical section, you will be given tips for working in Python, guided through Jupyter notebooks to clarify topics presented in class, and will be given time to get additional practice and work on the assigned lab. There may be information covered in section that is not covered in lecture.

### Project-Focused Discussion Sections

All other discussion sections in a week will be project-focused. Each project group will be assigned a TA. This will be each group's go-to person for project-related questions and discussion section will be the place for those questions, as this person will know you, your group, and your project best. This person will also be the person grading your project throughout the quarter.

---

# ASSIGNMENTS

Assignments are hands-on in this course. They will be completed individually in Jupyter Notebooks and both released and submitted on datahub.

The practice of data science involves writing code to answer questions and accomplish tasks. Thus, to get practice, your assignments will require you to use Python to do just that. Not everything will be explicitly mapped out step-by-step for you. This is intentional. Figuring things out when it’s not entirely clear what to do next is part of the practice here. You’ll attempt things that won’t work and become comfortable with this. You’ll get stuck and work to get unstuck. Not quite knowing exactly what’s going on at all times is part of the process. And, to be honest, part of the job of being a data scientist.

That said, the first two assignments will be the simplest assignments and aim to get you up to speed in Python and familiar with `pandas`. If the first two assignments are particularly difficult for you, that’s ok. But, it’s then up to you to determine if you want to put in the work to make it through the rest of the quarter. **Assignments will take more time and be more difficult starting with the third assignment**.

As assignments become more difficult, we don’t want you to get or feel totally lost. If you’ve thought long and hard, gone down a long rabbithole on Stack Overflow, and can’t even get a sense of what the next step may be, take a step away. Take a break. Then, come back and see if you can’t solve it with a refreshed mind. If you’re still totally stuck, ask on Piazza, talk to a classmate, and/or attend office hours for help.

With regards to asking questions of instructional staff, we’re here to help you, but there are way more students than there are instructors. So, help each other. Ask one another first. It’s awesome that we all have different backgrounds and experiences - let’s use that to our advantage. In fact, this is how the best data science gets done. Diverse minds solving a problem invariably improves the solution. Also, teaching something to someone else is the best way to determine if you really know something. So, it’s win-win. The person who’s stuck gets unstuck and the person who helped is more sure in their knowledge. Help one another! Section and office hours are meant to be collaborative.

Also, your instructional staff may not know the answer to everything off the top of their head right away. There is an entire field of data science topics and programming out there - we’ll do our best to help and show you where to look and how to figure out the answer (or steer you in a different direction if your approach is going to lead you in a messy and intractable direction), but know that we may not have all the answers.

### Deadlines

Assignments will be submitted individually on datahub. We’ll talk about the details for submission in class. Assignments will always be released at least a week before the assignment due date. On weeks with assignment deadlines, they will always be due Friday at 11:59 PM of the week specified (see Course Schedule below).

**Check to ensure that your file shows up under “Submitted assignments” on datahub after you click submit**. If the file is the incorrect file, corrupted, or otherwise unreadable, we cannot grade it and we will mark your assignment as late.

Late assignments will be accepted at 75\% credit for 72 hours (3 days) after the assignment's due date. Once the late deadline passes, assignments will be graded, feedback will be made available on datahub, and assignments will no longer be able to be submitted for credit.

### Feedback & Grades

It is your responsibility to ensure that we receive a submission from you on datahub and that you submit the correct file (a Jupyter notebook with the .ipynb extension with the same file name as the assignment) for each assignment. If you identify that a mistake has been made, it is your responsibility to get in touch on Piazza should a problem arise. You will receive individualized feedback via email with your grade and feedback about a week after each assignment is due.

### Assignment Questions on Piazza

Piazza will be used for all general questions. For example, if you are confused by what a question is asking or are unsure where to start to look for the answer and need direction, Piazza is the place to go. However, when asking or answering questions on Piazza, code that answers assignment questions should **not** be provided. Instead, answer with suggestions as to what topics/ideas/lectures to look into or vague pseudocode that helps move the person asking the question in the right direction. For general programming questions (unrelated to the assignment answers), feel free to share minimal code segments.

### Assignment Regrades

We will work hard to grade everyone fairly and return assignments quickly. But, we know you also work hard and want you to receive the grade you’ve earned. Occasionally, grading mistakes do happen, and it's important to us to correct them.

If you think there is a mistake in your grade, request a regrade within 72 hours of your receipt of the grade on Piazza via a *Private* note to "instructors" and use the "regrades" folder. [HOWTO for Piazza private notes here](https://support.piazza.com/support/solutions/articles/48000616669-post-a-private-note). This message should include evidence of why you think your answer was correct (i.e. a specific reference to something said in lecture) and should point to the specific part of the assignment in question.

Note that points will *not* be rewarded if you fail to follow instructions. For example, if the instructions say to name the variable `orange` and you name it `ornage` (misspelled), you will not be rewarded credit upon regrade. This is because (1) following instructions and being detail-oriented is important and (2) there are hundreds of students taking the course this quarter. It would be an unfair burden to place on TAs if we didn’t have this policy.

---

# COURSE PROJECT

Your course project will be completed in a group of 4-5 people. The reality of data science is that you will have to work with others. You’ll need to work together to communicate effectively, manage time, organize your projects, and accomplish a goal. People will have different knowledge and skills sets. It is your job as a group to work together to figure out how to maximize each group member’s skills to make sure that your differences are helpful to accomplishing your goal, rather than a hindrance. For example, some of you will find the programming aspects of the class assignments very easy, while others will struggle. Alternatively, some of you may find experimental research and hypothesis testing intuitive, while others find it confusing and frustrating. It is best for your project if you choose a team with a mix of background and experience.

### Finding A Group

Finding a group may be a tad trickier this quarter. As such, we'll offer additional support. Groups can be found in a few different ways:

1. If you have people in the class you know you want to work with, chat with one another and if you're all on board, form a group.
2. There will be time to find groups in discussion section during week 1.
3. If you don't know people in the class or don't have people you want to work with, no problem. Piazza has a feature where you can look for group mates - check for that post and look through there to find group mates

You will submit who your group is via Google Form by the Friday of week 2 (see Course Schedule). One form will be submitted per group.

If you do not signup for a group by the end of week 2 you will be randomly assigned a group. However you generally don't want that, you'll have more fun if you get on board with people who want to work on the same thing as you. Also in my experience the randomly assigned groups have more trouble than the ones students put together on their own.

### Project Components

All project components are completed as a group and are described in the Project documentation: https://github.com/COGS108/Projects. This includes: 1) group survey 2) Previous Project Review 3) Project Proposal 4) Project Checkpoint #1: Data, 5) Project Checkpoint #2: EDA, 6) Final Project Report, 7) Final Project Video, and 8) Team Evaluation Survey.

Starting week 3, there will be an *optional* weekly survey to be completed individually describing your project progress. Students who complete all 7 weeks' surveys will earn 0.5% extra credit to their final grade.

---

# COURSE SCHEDULE

| Date  | Week | Day   |Topic                       | Section  |   Assignment    | Lecture Quiz |
| -----:|:----:|:-----:|:-------------------        |:---------|:----------------|:-------------|
| 1/03  | 1	   | M     | Welcome!                   | --       | --              | --           |
| 1/05  | 1	   | W     | Python Review              | --       | --              | --           |  
| 1/07  | 1	   | F     | Version Control I          | --       | --              | --           |
| 1/10  | 2    | M     | Version Control II         | --       | --              | Q1           |
| 1/12  | 2	   | W     | Data & Intuition           | --       | --              | --           |
| 1/14  | 2	   | F     | Data Wrangling (`pandas`)  | D1       | A1; Group Signup* | --       |
| 1/17  | 3	   | M     | **No Class - MLK day**     | --       | --              | Q2           |
| 1/19  | 3	   | W     | Ethics                     | --       | --              | --           |
| 1/21  | 3	   | F     | Data Science ?s            | D2       | Project Review* | --           |
| 1/24  | 4	   | M     | Dataviz I                  | --       | --              | Q3           |
| 1/26  | 4	   | W     | Intro to Analysis          | --       | --              | --           |
| 1/28  | 4	   | F     | Descriptive Analysis       | D3       | Project Proposal* | --         |
| 1/31  | 5	   | M     | EDA                        | --       | --              | Q4           |
| 2/02  | 5	   | W     | Inference I                | --       | --              | --           |   
| 2/04  | 5	   | F     | Inference II               | D4       | A2              | --           |
| 2/07  | 6	   | M     | Inference III              | --       | --              | Q5           |
| 2/09  | 6	   | W     | Text Analysis I            | --       | --              | --           |
| 2/11  | 6	   | F     | Text Analysis II           |   D5     | Checkpoint #1: Data* | --      |
| 2/14  | 7	   | M     | Machine Learning I         | --       | --              | Q6           |
| 2/16  | 7	   | W     | Machine Learning II        | --       | --              | --           |
| 2/18  | 7	   | F     | Text + ML                  |   D6     | **A3**          | --           |
| 2/21  | 8	   | M     | **No Class - President's day** | --   | --              | Q7           |  
| 2/23  | 8	   | W     | Nonparametric              | --       | --              | --           |
| 2/25  | 8	   | F     | Geospatial I               |   D7     | Checkpoint #2: EDA* |          |
| 2/28  | 9	   | M     | Geospatial II              | --       | --              | Q8           |
| 3/02  | 9	   | W     | Dimensionality Reduction   | --       | --              | --           |
| 3/04  | 9	   | F     | How to be wrong            |   D8     | **A4**          | --           |
| 3/07  | 10	 | M     | Guest lecture I            | --       | --              | Q9           |
| 3/09  | 10	 | W     | Guest lecture II           | --       | --              | --           |
| 3/11  | 10	 | F     | Data science jobs          |    D9    | --              | --           |
| 3/14  | Finals | M   | --  | Final project*, video*, team eval survey | -- |

\* indicates group submission. All other assignments/quizzes/surveys are completed & submitted individually.

---

# OTHER GOOD STUFF

### Class Conduct

In all interactions in this class, you are expected to be respectful. This includes following the [UC San Diego principles of community](https://ucsd.edu/about/principles.html) .

This class will be a welcoming, inclusive, and harassment-free experience for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, ethnicity, religion (or lack thereof), political beliefs/leanings, or technology choices.

At all times, you should be considerate and respectful. Always refrain from demeaning, discriminatory, or harassing behavior and speech. Last of all, take care of each other.

If you have a concern, please speak with anyone on the instruction team (professor, TAs, or IAs). If you are uncomfortable doing so, that’s ok! The [OPHD](https://blink.ucsd.edu/HR/policies/sexual/OPHD.html) (Office for the Prevention of Sexual Harassment and Discrimination) and [CARE](https://care.ucsd.edu/) (confidential advocacy and education office for sexual violence and gender-based violence) are wonderful resources on campus.  

### Academic Integrity

Don't cheat.

You are encouraged to (and at times will have to) work together and help one another. However, you are personally responsible for the work you submit. For assignments, it is also your responsibility to ensure you understand everything your group has submitted and to make sure the correct file has been uploaded, that the upload is uncorrupted, and that it renders correctly. Projects may include ideas and code from other sources—but these other sources must be documented with clear attribution. Please review academic integrity policies [here](http://academicintegrity.ucsd.edu).


Know that a third of the class typically feels overwhelmed at the start of the quarter. That said, the average is quite high in this course typically (A-). So, while we anticipate you all doing well in this course, if you are feeling lost or overwhelmed, that’s ok! Should that occur, we recommend: (1) asking questions in class, (2) attending office hours and/or (3) asking for help on Piazza.

Cheating and plagiarism have been and will be strongly penalized. If, for whatever reason, datahub is down or something else prohibits you from being able to turn in an assignment on time, immediately contact me by emailing your assignment by email ([jfleischer@ucsd.edu](mailto:jfleischer@ucsd.edu)), or else it will be graded as late.

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

TL;DR  If you're in this class and want a letter you can ask, but (a) the letter will not help you get into a top program, and (b) I will only write a double handful of those per quarter (so ask me early!). If you want good letters I advise you to work with multiple professors in programs outside of the class.

If you are bound for graduate school you will probably need support and letters from professors or someone else who has done graduate training. Many students ask professors they have taken a class from (including me), but I want you to know this is a bad idea. You really want to get a letter from someone you have worked with more closely, who knows your talents and personality from experience working together with you over a long time.  You are one of hundreds of students I will have this quarter. TBH with relatively few exceptions I will not know you well. To get a solid letter from a prof, you want to be a research assistant, independent study, honors thesis advisee, or instructional assistant. If you are interested in grad school you need to have done the work before the beginning of senior year; letters are needed in Nov/Dec of your senior year for the following Fall admission.

If you are just one of the hundreds of students in a class, almost every prof (including me) will write a letter that is roughly "I know STUDENT from CLASS where they got an A and often came to office hours and asked questions". That's the kind of letter which meets the bare minimum, and it may help you gain admission to some schools. But a top level grad program expects you to have done the things that will yield 3 much more detailed letters. So if you're an IA/RA/advisee, profs (including me) will write letters that go much much harder and into great detail about your qualities.  And that's what you want.  Also I want you to know that a detailed letter from someone not a professor (e.g., your manager when you did an internship related to your chosen field, the head of a volunteer organization you work with, a grad student you worked for on a research project, etc.) is probably better for your chances than a minimum letter from a professor.   

### What should you call me?

Most students call me Professor or Professor Fleischer or Dr. Fleischer. I'm also perfectly happy if you call me Jason, but not all professors are OK with that kind of informality. I would prefer you *not* address me as Mr. Fleischer; if you're going to use an honorific please use the one that people expect in the situation.

### What I should call you

I should call you by your preferred name, with the correct pronunciation and any honorific or pronouns you choose. Please correct me (either in the chat, out loud on zoom, or via email/Piazza after the fact...however you're most comfortable) if I ever make a mistake.

### How to Get Your Question(s) Answered and/or Provide Feedback

It’s great that we have so many ways to communicate, but it can get tricky to figure out who to contact or where your question belongs or when to expect a response. These guidelines are to help you get your question answered as quickly as possible and to ensure that we’re able to get to everyone’s questions.

That said, to ensure that we’re respecting their time, TAs and IAs have been instructed they’re only obligated to answer questions between normal working hours (M-F 9am-5pm). However, I know that’s not when you may be doing your work. So, please feel free to post whenever is best for you while knowing that if you post late at night or on a weekend, you may not get a response until the next day. As such, do your best not to wait until the last minute to ask a question.

**If you have…**

- **Questions about course content**: these are awesome! We want everyone to see them and have their questions answered too…so post these to Piazza!
- **A technical assignment question**: Come to office hours (or post to Piazza). Answering technical questions is often best accomplished in person where we can discuss the question and talk through ideas. However, if that is not possible, post your question to Piazza. Be as specific as you can in the question you ask. And, for those answering, help your classmates as much as you can without just giving the answer. Help guide them, point them in a direction, provide pseudo code, but do not provide code that answers assignment questions.
- **Been stuck on something for a while (>30min) and aren’t even really sure where to start**: Programming can be frustrating and it may not always be obvious what is going wrong or why something isn’t working. That’s ok - we’ve all been there! IF you are stuck, you can and should reach out for help, even if you aren’t exactly sure what your specific question is. To determine when to reach out, consider the 2-hour rule. This rule states that if you are stuck, work on that problem for an hour. Then, take a 30 minute break and do something else. When you come back after your break, try for another 30 minutes or so to solve your problem. If you are still completely stuck, stop and contact us (office hours, post on Piazza). If you don’t have a specific question, include the information you have (what you’re stuck on, the code you’ve been trying that hasn’t been happening, and/or the error messages you’ve been getting).
- **Questions about course logistics**: First, check the syllabus. If the answer is not there, ask a classmate. If you still are unsure,  post on Piazza
- **Questions about a grade**: For programming assignments, reply to the COGS 108 email directly; For project-related regrades, post a note to instructors on Piazza and select the ‘regrades’ tag. Include specifics as to why you feel you mistakenly/unfairly lost points in that post.
- **A specific section-related question**: send a direct message on Piazza to your TA/IA
- **Something super cool to share related to class**: feel free to email Prof Ellis or come to office hours. Be sure to include COG S108 in the email subject line and your full name in your message.
- **Something you want to talk about in-depth**: meet in person during office hours or schedule a time to meet by email. Be sure to include COGS 108 in the email subject line.
- **Some feedback about the course you want to share anonymously**: If you’ve been offended by an example in class, really liked or disliked a lesson, or wish there were something covered in class that wasn’t but would rather not share this publicly, etc., please fill out the anonymous [Google Form](https://forms.gle/RkNrZtRz8nDaEq8d7)
