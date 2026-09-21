DRAFT v0.1 21-Sep-2026 (subject to change before Week 1)

# COGS 108: Data Science in Practice

**Fall 2026**  

---

**Table of Contents**

- [Overview](#Course-Overview)
- [Links](#COURSE-LINKS)
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

This hands-on, practical course is intended to get you experience working on data science projects.  You may have theoretical knowledge from other courses, but here we are going to implement. Doing something is rarely simple.  You will likely attempt to do something, do it wrong, learn from your mistakes, and with a bit of luck and skill, eventually succeed. That's just part of the scientific process, and data science is no exception. This course is all about the *practice* of data science.

In focusing on the practice, there is theory that won't be discussed and mathematical proofs that won't be done. That is by design. In particular:

- There are entire courses dedicated to each of the topics we'll cover. To have time to do anything, we can't teach all the details in a single course.
- Experts in each of these domains are out there and excited to teach you the nitty gritty about each topic.  Take those opportunities... the theory we are skipping is important and useful!
- We're promoting data literacy. We believe that everyone who is data literate is at an advantage as they go out into the modern world. Data literacy is not limited to those who are computational gurus or math prodigies. You do not have to be either of those to excel at this course.

In this course, you will try many methods. You'll even be asked to implement a technique that has not been explicitly taught. Again, this is by design. As a data scientist, you'll regularly be asked to step outside of your comfort zone and into something new. Our goal is to get you as comfortable as possible in that space now. We want to provide you with a technical and a data science mindset that will allow you to ask the right questions for the problem at hand and set off alarm bells when something in your dataset or analysis is “off.”

# COURSE LINKS

Course GitHub: https://github.com/COGS108  

Course Piazza*: access via Canvas

Course Canvas: https://canvas.ucsd.edu/courses/77704

Assignment Submission: https://datahub.ucsd.edu  

Anonymous Course Feedback:  https://forms.gle/LVZA26UEkDquEnsW8

*You will be able to post anonymously on Piazza; however, you will only be anonymous to your classmates. Your Instructor and TAs will be able to see who you are.

---

# COURSE OBJECTIVES

- Formulate a plan for and complete a data science project from start (question) to finish (communication)
- Explain and carry out descriptive, exploratory, inferential, and predictive analyses in Python
- Communicate results concisely and effectively in reports and presentations
- Identify and explain how to approach an unfamiliar data science task

---

# COURSE MATERIALS
- All course materials will be provided on GitHub and datahub, so you will need:
  - Datahub access
  - `git` and a GitHub login
- There is no textbook


---

# GRADING

| Component                     | Completed as |        Number       | Each |    Total |
| :---------------------------- | :----------- | :-----------------: | :--: | -------: |
| **Individual coursework**     |              |                     |      |  **62%** |
| Pre-course survey (#finaid)   | Individual   |          1          |  1%  |       1% |
| Participation (or final exam) | Individual   |     36 sessions     |  –   |      25% |
| Lecture quizzes               | Individual   | 10 (lowest dropped) |  1%  |       9% |
| Assignments                   | Individual   |          9          |  3%  |      27% |
| **Final project**             |              |                     |      |  **38%** |
| Previous project review       | Group        |          1          |  2%  |       2% |
| Project proposal              | Group        |          1          |  5%  |       5% |
| Data checkpoint               | Group        |          1          |  5%  |       5% |
| EDA checkpoint                | Group        |          1          |  5%  |       5% |
| Final report                  | Group        |          1          | 10%  |      10% |
| Final video                   | Group        |          1          |  5%  |       5% |
| Oral exam                     | Individual   |          1          |  5%  |       5% |
| Team evaluation survey        | Individual   |          1          |  1%  |       1% |
| **Total**                     |              |                     |      | **100%** |

Participation: full credit for attending 30 of the 36 possible lecture + discussion sessions. [There is a chance that this cutoff could be made more permissive (<30) at the end of the quarter, but it will *not* be made more strict. Students will be made aware of this change should it happen.]

**Final exam**: If a student does not earn their participation credit, they will be required to take an in-person, closed notes final exam at their assigned final exam time.

**Grades**: All grades will be released on Canvas. It is *your responsibility to check that your assignment was submitted, that your grade is accurate, and to get in touch if any are missing and/or you think there is a problem*.

**Due Dates**: For keeping things simple for you all, all due dates each week will be **Sundays at 11:59 PM**. Please DO NOT wait until Sunday at 11:50 PM each week to start everything that is due.

Extra credit will be awarded for:
- Answering the mid-course survey: 0.1% extra credit
- Filling out the (6) weekly project progress surveys: 0.5% of grade (0.083% each, see Project section below)
- Going above and beyond on the project: this is at Professor Ellis' discretion, but in a typical iteration 20-30 students get an increase in their individual final project grade


Our grading scale is:

|     |               |
| :-- | :------------ |
| A+  | >= 97%        |
| A   | < 97% to 94%  |
| A-  | < 94% to 90%  |
| B+  | < 90 % to 87% |
| B   | < 87 % to 84% |
| B-  | < 84 % to 80% |
| C+  | < 80 % to 77% |
| C   | < 77 % to 74% |
| C-  | < 74 % to 70% |
| D   | < 70 % to 60% |
| F   | < 60 %        |

Know that a third of the class typically feels overwhelmed at the start of the quarter. That said, the average is quite high in this course (typically A-). So, while we anticipate you all doing well in this course, if you are feeling lost or overwhelmed, that's ok! Should that occur, we recommend: (1) asking questions in class, (2) attending office hours and/or (3) asking for help on Piazza.

Given the flexibility built into the course, typically high grade averages, and amount of extra credit offered, final grades are not rounded up.

---

# LECTURE

This quarter we are running two lecture sections to keep up with demand. 

Lecture will be podcast. You'll be able to view both/either lecture; however, it will not earn you participation credit. 

| which  | when            | where                          |
| ------ | --------------- | ------------------------------ |
| LE 001 | MWF 1:00p-1:50p | Pepper Canyon Hall - PCYNH 106 |
| LE 002 | MWF 2:00p-2:50p | Peterson Hall - PETER 110      |



## Lecture Quizzes

At the end of each Friday, a quiz with ~10 questions will be released, covering the material from lecture that week. The quiz will be due that Sunday at 11:59 PM. For example, the first quiz will be released Friday of week 1, covering week 1 material, and will be due two days later at 11:59 PM. Each question is worth ~0.1 points and you will have a single, timed (15 min) attempt to complete. The quizzes are open-notes and open Internet. *There are no late extensions on quizzes*, but your lowest quiz score will be dropped.

---

# DISCUSSION SECTION

Discussion section will be focused on project completion and discussion of course data science readings this quarter. 

Please note that Veterans Day (Wednesday, Nov 11) is a holiday this quarter, so there will be no section during week 7.


| Section | Day | Time          | Location | Room |
| ------- | --- | ------------- | -------- | ---- |
| 001-001 | M   | 11:00a-11:50a | PCYNH    | 120  |
| 001-002 | M   | 12:00p-12:50p | PCYNH    | 120  |
| 001-005 | M   | 3:00p-3:50p   | CSB      | 004  |
| 001-006 | M   | 4:00p-4:50p   | CSB      | 004  |
| 002-001 | W   | 9:00a-9:50a   | DIB      | 122  |
| 002-002 | W   | 10:00a-10:50a | PCYNH    | 120  |
| 002-003 | W   | 11:00a-11:50a | PCYNH    | 120  |
| 002-004 | W   | 12:00p-12:50p | PCYNH    | 120  |
| 002-005 | W   | 1:00p-1:50p   | PCYNH    | 120  |
| 002-006 | W   | 3:00p-3:50p   | PCYNH    | 120  |

## Readings

## Optional Readings:

There will be four readings this quarter, which will be discussed in section and students will also have to respond in their Google Form to questions from the assigned reading:

- R1 | [Dissecting racial bias in an algorithm used to manage the health of populations](https://www.science.org/doi/10.1126/science.aax2342)
- R2 | [Ten Simple Rules for Better Figures](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833)
- R3 | [Many Analysts, One Data Set: Making Transparent How Variations in Analytic Choices Affect Results](https://journals.sagepub.com/doi/10.1177/2515245917747646)
- R4 | [Measurement Schmeasurement: Questionable Measurement Practices and How to Avoid Them](https://journals.sagepub.com/doi/10.1177/2515245920952393)

Paywall restrictions may require students to access the above on-campus or through the UCSD VPN. Students should **not** pay to access an article.

We also maintain [a list of readings that can provide insight into various data science topics](https://github.com/COGS108/Readings).



## Attendance 

We believe that attending in-person is the best way to learn for most people. Our goal is to make the lecture and discussion section worth your while to attend through interactive content and making it a good place to get questions answered. We also use active learning paradigms (live coding, think-pair-share, etc.) where you learn most through active participation (which requires attendance). 

### Lecture

You are free to attend either lecture section at any point. (The same material will be covered in each section; however, I'm not a robot, so there could be slight variations between the lectures.)

### Discussion Section

You should try to attend the discussion section to which you're assigned. If you need to attend a different section in a given week, you're free to do so. If any one section becomes too crowded, we will revisit this policy.

### Participation

Participation will be tracked in lecture and discussion section via Google Form. Please bring a smartphone, tablet, or laptop to both lecture and discussion for Google Form completion. We will work to regularly update students about their participation. There will be 36 lectures/discussions for possible participation this quarter (27 lectures; 9 discussions). To receive full credit for participation, you must attend and participate in 30 lecture/discussion sections. Students who do not earn participation credit will be required to take the closed notes, in-person final exam. Partial credit for participation will be considered toward the end of the term and students will have the information they need to determine if they'll have to take the final exam.

### Final Exam

The final exam is *only* required of students who have not earned participation credit. (Students who earned participation credit do not have to show up anywhere during finals week.) The exam will be cumulative, in-person, closed notes, and worth 25 points (replacing the 25% participation grade). It will be an intentionally difficult assessment to ensure that students have gotten out of the course what they would have, if they had participated regularly for the ten weeks prior. 

---

# ASSIGNMENTS

Assignments are completed **individually** in Jupyter Notebooks and both released and submitted on datahub.

The practice of data science involves writing code to answer questions and accomplish tasks. Thus, to get practice, your assignments will require you to use Python to do just that. Not everything will be explicitly mapped out step-by-step for you. This is intentional. Figuring things out when it's not entirely clear what to do next is part of the practice here. You'll attempt things that won't work and become comfortable with this. You'll get stuck and work to get unstuck. Not quite knowing exactly what's going on at all times is part of the process. And, to be honest, part of the job of being a data scientist.

That said, the first two assignments will be the simplest assignments and aim to get you up to speed in Python and familiar with `pandas`. If the first two assignments are particularly difficult for you, that's ok. But, it's then up to you to determine if you want to put in the work to make it through the rest of the quarter. **Assignments will take more time and be more difficult starting with the third assignment**.

As assignments become more difficult, we don't want you to get or feel totally lost. If you've thought long and hard, gone down a long rabbithole using GenAI, and can't even get a sense of what the next step may be, take a step away. Take a break. Then, come back and see if you can't solve it with a refreshed mind. If you're still totally stuck, ask on Piazza, talk to a classmate, and/or attend office hours for help.

With regards to asking questions of instructional staff, we're here to help you, but there are way more students than there are instructors. So, help each other. In fact, this is how the best data science gets done. Diverse minds solving a problem invariably improves the solution. Also, teaching something to someone else is the best way to determine if you really know something. So, it's win-win. The person who's stuck gets unstuck and the person who helped is more sure in their knowledge. Help one another! Section and office hours are meant to be collaborative.

But how should you help one another on assignments? You should: ask a question that leads the student to figure it out for themselves, point out the correct principle/theory that applies in this case, provide a link to an explanation, or a chunk of pseudo-code.  You should not: provide the full answer or code they can just copy/paste.

### Turning In Assignments

Assignments will be submitted individually on datahub. We'll talk about the details for submission in class. Assignments will always be released at least a week before the assignment due date. On weeks with assignment deadlines, they will always be due Sunday at 11:59 PM of the week specified (see Course Schedule below).

**Check to ensure that your file shows up under “Submitted assignments” on datahub after you click submit!!!**. If the file is the incorrect version of the file, corrupted, or otherwise unreadable, then you will lose the appropriate number of points. If you accidentally click submit after the deadline and before we grade it, your assignment will be marked as late.

### Assignment Regrades

We will work hard to grade everyone fairly and return assignments quickly. But, we know you also work hard and want you to receive the grade you've earned. Occasionally, grading mistakes do happen, and it's important to us to correct them.

If you think there is a mistake in your grade, request a regrade within 72 hours of your receipt of the grade on Piazza via a *private* post to Instructors in the "regrades" folder.  This message should include evidence of why you think your answer was correct (e.g. a specific reference to something said in lecture) and should point to the specific part of the assignment in question.

Note that points will *not* be awarded if you fail to follow instructions. For example, if the instructions say to name the variable `orange` and you name it `ornage` (misspelled), you will not be awarded credit upon regrade. This is because (1) following instructions and being detail-oriented is important and (2) there are hundreds of students taking the course this quarter. It would be an unfair burden to place on TAs if we didn't have this policy.

# Late Policy

Assignments will be accepted up to 5 days late with a 25% late penalty taken off your grade. **Every student receives 7 free late days with NO DEDUCTION for use on any assignment.** Without penalty, you can turn in 7 work items one day late each, or 1 work item 3 days late and another 4 days late, or any other combination.

PLEASE NOTE while your pool of late days is 7, your maximum lateness on any single assignment is 5 days. These late days are intended for use when you are behind and need an extra day, illness, family emergencies, mental health crises, etc. 

Lecture quizzes are not accepted late, but the lowest is dropped.

Project components will not automatically be accepted late. If an extension is needed, please reach out to Professor Ellis or a TA.

---

# COURSE PROJECT

Your course project will be completed in a group of 4-5 people. The reality of data science is that most projects are completed in teams. You'll need to work together to communicate effectively, manage time, organize your projects, and accomplish a goal. People will have different knowledge and skill sets. It is your job as a group to work together to figure out how to maximize each group member's skills to make sure that your differences are helpful to accomplishing your goal, rather than a hindrance. For example, some of you will find the programming aspects of the class assignments very easy, while others will struggle. Alternatively, some of you may find experimental research and hypothesis testing intuitive, while others find it confusing and frustrating. It is best for your project if you choose a team with a mix of background and experience.

### Finding A Group

Students will be given time in section during weeks 1 and 2. We encourage group formation within section. If you choose a group outside of section, there must be at least two discussion section time slots that *all* group members are able to attend throughout the quarter. 

You will submit who your group is via Google Form by the Sunday of week 2 (Oct 11; see Course Schedule). One form will be submitted per group.

If you do not sign up for a group, you will be randomly assigned a group. However you generally don't want that. You'll have more fun if you get on board with people who want to work on the same thing as you. Also, every quarter, the randomly assigned groups have more trouble than the ones students put together on their own.

### Getting Started 

Probably the most important way to start a team off on the right foot is to discuss expectations of how you will work together.  How will you divide up the work? How often and where will you meet? How will you communicate with each other? What's the maximum amount of time it should take for someone to respond to a message?  How will you double check that things that need to happen did happen? If there is a problem meeting a deadline how should the person responsible let others know, and then how should the rest of the team react? There are many possible answers to these questions, and there are many more questions about expectations that you might want to ask yourselves. Your team should decide what's right for you, _and then write down these expectations_ (you'll be required to include them on your project proposal).  This will help things go more smoothly.  

### Project Components

These project components are completed and submitted *as a group* and are described in the Project documentation: https://github.com/COGS108/Projects/tree/fa26. This includes: 1) Previous Project Review 2) Project Proposal 3) Project Checkpoint #1: Data, 4) Project Checkpoint #2: EDA, 5) Final Project Report, and 6) Final Project Video.

Each group will also take an oral exam during week 10 where each individual is asked to respond to questions about their project. Scores will be assigned individually based on how each individual answers the questions they were asked. 

At the end of the course there is a *required* team evaluation survey...this is your opportunity to provide feedback and let us know if a teammate did not contribute. Each student will submit a survey.

Finally, starting the week after proposals are due, there will be an *optional* weekly survey to be completed individually describing your project progress. Students will earn a small amount of extra credit for each survey completed such that students who complete all six weeks' surveys will earn 0.5% extra credit to their final grade.  

### Project Grading

Each project group will be graded by the same staff member throughout the quarter. You will know who your grader is, and they'll be very familiar with your project, so they'll be a great resource as you complete your project. It's best to think of them as a manager; you won't go to them first (that's what your group mates are for), but they're there for guidance. Given different groups will have different graders, grading will use a standardized rubric and adjustments will be made if one grader is harsher than another to ensure consistency across graders. 

Additionally, points lost on a previous submission can be recuperated on the next submission. For example, if you lose points on the Ethics section on the proposal but then improve that in your First Checkpoint, those points will be returned automatically. However, points can only be recuperated on the following submission. So, if an issue exists in the proposal and remains in the *second* checkpoint, points lost will not be returned. However, all sections are read and graded on the Final Project submission, so you will eventually want to improve all sections.

In the vast majority of groups, all individuals will receive the same score for each project component; however, if there is evidence of a group member failing to participate fully, individuals can receive a lower grade relative to their group. The same is true in the other direction. If there is evidence of a group member going above and beyond, their individual score can be increased relative to the group. 

---

# COURSE SCHEDULE
| Date   | Week   | Day | Topic                                        | Section Focus        | Quiz due | Assignment / survey due | Project due                             |
| ------ | ------ | --- | -------------------------------------------- | -------------------- | -------- | ----------------------- | --------------------------------------- |
| Sep-25 | 0      | F   | Welcome!                                     |                      |          |                         |                                         |
| Sep-28 | 1      | M   | Version Control I                            | Group Formation, R1  |          |                         |                                         |
| Sep-30 | 1      | W   | Version Control II                           |                      |          |                         |                                         |
| Oct-2  | 1      | F   | Data & Intuition I                           |                      |          |                         |                                         |
| Oct-4  | 1      | Su  |                                              |                      | Q1       |                         |                                         |
| Oct-5  | 2      | M   | Data & Intuition II                          | Group Formation, R2  |          |                         |                                         |
| Oct-7  | 2      | W   | Data Wrangling (pandas)                      |                      |          |                         |                                         |
| Oct-9  | 2      | F   | Ethics                                       |                      |          |                         |                                         |
| Oct-11 | 2      | Su  |                                              |                      | Q2       | A1, Pre-course survey   | Group signup*                           |
| Oct-12 | 3      | M   | Dataviz principles                           | Project Review       |          |                         |                                         |
| Oct-14 | 3      | W   | Data Science Questions                       |                      |          |                         |                                         |
| Oct-16 | 3      | F   | Intro to Analysis                            |                      |          |                         |                                         |
| Oct-18 | 3      | Su  |                                              |                      | Q3       | A2                      | Project Review*                         |
| Oct-19 | 4      | M   | Exploratory Data Analysis (EDA)              | Project Proposal     |          |                         |                                         |
| Oct-21 | 4      | W   | Inference I                                  |                      |          |                         |                                         |
| Oct-23 | 4      | F   | Inference II                                 |                      |          |                         |                                         |
| Oct-25 | 4      | Su  |                                              |                      | Q4       | A3                      | Project Proposal*                       |
| Oct-26 | 5      | M   | Inference III                                | R3                   |          |                         |                                         |
| Oct-28 | 5      | W   | Dimensionality Reduction                     |                      |          |                         |                                         |
| Oct-30 | 5      | F   | Machine Learning I                           |                      |          |                         |                                         |
| Nov-1  | 5      | Su  |                                              |                      | Q5       | A4, Mid-course survey   |                                         |
| Nov-2  | 6      | M   | Machine Learning II                          | Data Checkpoint      |          |                         |                                         |
| Nov-4  | 6      | W   | Machine Learning III                         |                      |          |                         |                                         |
| Nov-6  | 6      | F   | Machine Learning IV                          |                      |          |                         |                                         |
| Nov-8  | 6      | Su  |                                              |                      | Q6       | A5                      | Checkpoint #1: Data*                    |
| Nov-9  | 7      | M   | Geospatial I                                 | No Section this week |          |                         |                                         |
| Nov-11 | 7      | W   | No Class - Veterans Day                      |                      |          |                         |                                         |
| Nov-13 | 7      | F   | Geospatial II                                |                      |          |                         |                                         |
| Nov-15 | 7      | Su  |                                              |                      | Q7       | A6                      |                                         |
| Nov-16 | 8      | M   | Text Analysis I                              | EDA Checkpoint       |          |                         |                                         |
| Nov-18 | 8      | W   | Text Analysis II                             |                      |          |                         |                                         |
| Nov-20 | 8      | F   | Communication                                |                      |          |                         |                                         |
| Nov-22 | 8      | Su  |                                              |                      | Q8       | A7                      | Checkpoint #2: EDA*                     |
| Nov-23 | 9      | M   | How to Be Wrong I                            | R4                   |          |                         |                                         |
| Nov-25 | 9      | W   | How to Be Wrong II                           |                      |          |                         |                                         |
| Nov-27 | 9      | F   | No Class - Thanksgiving                      |                      |          |                         |                                         |
| Nov-29 | 9      | Su  |                                              |                      | Q9       | A8                      |                                         |
| Nov-30 | 10     | M   | Oral Exams†                                  | Final Project        |          |                         |                                         |
| Dec-2  | 10     | W   | Oral Exams†                                  |                      |          |                         |                                         |
| Dec-4  | 10     | F   | Oral Exams†                                  |                      |          |                         |                                         |
| Dec-6  | 10     | Su  |                                              |                      | Q10      | A9                      | Final report & video*, Team eval survey |
| Dec-7  | Finals | M   | Final Exam (LE 001): 11:30a-2:29p, PCYNH 106 |                      |          |                         |                                         |
| Dec-9  | Finals | W   | Final Exam (LE 002): 3:00p-5:59p, PETER 110  |                      |          |                         |                                         |


\* indicates group submission. All other assignments/quizzes/surveys are completed & submitted individually.
† Group oral exams will take place during lecture time in Week 10. Students will sign up for a time slot later in the quarter. Additionally, there will be two pre-recorded guest lectures that students will be required to watch and interact with during week 10. These will count toward particpation.

---

# OTHER GOOD STUFF

## Class Conduct

In all interactions in this class, you are expected to be respectful. This includes following the [UC San Diego principles of community](https://ucsd.edu/about/principles.html) .

This class will be a welcoming, inclusive, and harassment-free experience for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, ethnicity, religion (or lack thereof), political beliefs/leanings, or technology choices.

At all times, you should be considerate and respectful. Always refrain from demeaning, discriminatory, or harassing behavior and speech. Last of all, take care of each other.

If you have a concern, please speak with anyone on the instruction team (professor or TAs). If you are uncomfortable doing so, that's ok! The [OPHD](https://blink.ucsd.edu/HR/policies/sexual/OPHD.html) (Office for the Prevention of Sexual Harassment and Discrimination) and [CARE](https://care.ucsd.edu/) (confidential advocacy and education office for sexual violence and gender-based violence) are wonderful resources on campus.  

## Academic integrity

Don't cheat. Academic dishonesty undermines you actually learning the material and is unfair to students putting in the work. I take academic integrity seriously and have historically and will continue to report any suspected violations to the **UCSD Academic Integrity Office**. (I hate when I have to do this; please don't put either of us in that position.)

It is your responsibility to familiarize yourself with [UCSD's academic integrity policies](http://academicintegrity.ucsd.edu/).

Examples of academic dishonesty include (but are not limited to):

- using AI to complete your quizzes or assignments
- copying answers from another student (or allowing another student to copy yours)
- using notes or the Internet (including AI tools) during exams
- using/sharing a "secret code" or timing of Google Form to receive credit when you are not in class/section (or sharing one with a classmate who is absent)

Use of Generative AI (GenAI) tools (e.g., TritonGPT, ChatGPT, Claude, Gemini) is permitted in this course; however, use should be thoughtful and intentional. If they are helping you learn, you're probably using them correctly. If they're helping you earn points without actually learning, you're using them incorrectly.

Also, you are responsible for errors and falsehoods introduced by (any of) the tools you use. If a model hallucinates or gives you incorrect information and you submit it, you're responsible for that error.

### Help allowed

| Work type       | Group work / ask other students | Open book / internet | Ask a clarification question to TA / professor | GenAI usage |
| :-------------- | :-----------------------------: | :------------------: | :--------------------------------------------: | :---------: |
| Exam            |               ❌                |          ❌          |                       ✅                       |     ❌      |
| Lecture Quizzes |               ❌                |          ✅          |                       ✅                       |     ⚠️      |
| Assignments     |               ✅                |          ✅          |                       ✅                       |     ⚠️      |
| Project         |               ✅                |          ✅          |                       ✅                       |     ⚠️      |

✅ permitted  
❌ not allowed  
⚠️ indicates that use is permitted; however, GenAI should never be asked to complete a quiz, assignment, or project component for you. Instead you should be using it conversationally, with targeted specific tasks and/or questions.

**Assignments**: Assignments will be submitted individually, although you may seek help from your fellow students during completion. However, you may not give answers to each other at any time. You should understand, reproduce on your own, and be able to explain any work you submit. All assignments will require you to specify how outside resources were utilized in their completion.

**Project**: For group projects, you will work together but every person in the group is required to understand every aspect of the project. AI may be used as a collaborative tool just like an additional group member. Use it for brainstorming, editing, debugging, formatting, background research, and/or clarifying thoughts. Individual understanding will be assessed via the oral exam. Projects may include ideas and code from other sources—but these other sources must be documented with clear attribution.

Additional guidelines will be provided throughout the quarter.

Misuse of AI tools in this course is a form of academic dishonesty and will be handled according to UCSD's Academic Integrity policy.

### AI Professor Use Transparency

To be clear, I think Generative AI tools are helpful! As such, I do use them in course development. For full transparency I like to let students know when I do (and do not!) use GenAI in course development. I aim to model responsible use and hope to further the conversation about how academics integrate AI into their instruction and work more broadly.

**What I use AI For**: I use AI for administrative tasks (e.g., updating the dates and room numbers on the course schedule from the previous quarter, removing redundancies, clarifying policies). I have used it to combine and organize assessments that I previously developed. I also have used it to identify potential gaps in readings, lecture material, assessments, and provided resources, thus enabling me to update the course more rapidly than I was able to previously.

**What I DO NOT use AI For**: I do not use AI for designing course content from scratch, making final reading selections, generating assessments, or evaluating your work. I consider AI a helpful assistant, akin to a knowledgeable colleague. I consider its recommendations and knowledge, but always review its output and think critically before incorporation.

**Instructor vs. Student Use**: My goal as an instructor is to effectively synthesize and communicate information to you and accurately evaluate your understanding of the material after the fact. Your job is to learn, so it is your responsibility to do the cognitive work to make that happen. Spending time and struggling through is part of that process…and honestly, sometimes even the point. Using AI to earn points without learning is an AI violation and thwarts actual learning.

## Disability Access

Students requesting accommodations due to a disability must provide a current Authorization for Accommodation (AFA) letter. These letters are issued by the Office for Students with Disabilities (OSD), which is located in University Center 202 behind Center Hall. Please make arrangements to contact Prof Ellis privately to arrange accommodations. If you are struggling to get a meeting with OSD, you can let Prof Ellis know and she's likely able to help accommodate while you work to get official documentation.
Contacting the OSD can help you further:
- 858.534.4382 (phone)
- [osd@ucsd.edu](mailto:osd@ucsd.edu) (email)
- http://disabilities.ucsd.edu

## Difficult Life Situations

Sometimes life outside of academia can be difficult. Please [email me](mailto:sellis@ucsd.edu) or come to office hours if stuff outside the classroom prevents you from doing well inside it. I can often refer you on to the help you need.

If you don't have the most essential resources required to thrive as a student, please contact [UCSD Basic Needs](https://basicneeds.ucsd.edu) who can help you access nutritious food and stable housing, and help you seek the means to reach financial wellness.

If you are skipping and stretching meals, or having difficulties affording or accessing food, you may be eligible for CalFresh, California’s Supplemental Nutrition Assistance Program, that can provide free money on a debit card to buy food. Students can apply at [benefitscal.com/r/ucsandiegocalfresh](https://benefitscal.com/ApplyForBenefits/begin/ABOVR?lang=en) 

If you need emergency food, finances, and/or academic and social support you can also contact [UCSD Mutual Aid](https://mutualaiducsd.wordpress.com). They provide mentoring and aid that comes from volunteers among your peers.  If you don't need that kind of support, consider joining them in helping your fellow classmates who do.

If you need counseling or if you are in a mental crisis you can contact [CAPS](https://caps.ucsd.edu). They provide psychiatric services, workshops, and counseling; they also operate a 24/7 crisis hotline at 858.534.3755

## Undocumented Student Services

Undocumented Student Services (USS) provides support for undocumented students and those from mixed-status families at UC San Diego. For more information about the services, visit the [USS website](https://uss.ucsd.edu/) or connect through email (undoc@ucsd.edu).

## What should you call me?

Most students call me Professor/Prof Ellis, and that's great! This is how I typically sign emails to students. I'm also totally OK with you addressing me as Shannon or Dr. Ellis. I would prefer you *not* address me as Ms./Miss/Mrs. Ellis.


## What I should call you

I should call you by your preferred name, with the correct pronunciation and any honorific or pronouns you choose. Please correct me if I ever make a mistake.

## How to Get Your Question(s) Answered and/or Provide Feedback

It's great that we have so many ways to communicate, but it can get tricky to figure out who to contact or where your question belongs or when to expect a response. These guidelines are to help you get your question answered as quickly as possible and to ensure that we're able to get to everyone's questions.

That said, to ensure that we're respecting their time, TAs have been instructed they're only obligated to answer questions between normal working hours (M-F 9am-5pm). However, I know that's not when you may be doing your work. So, please feel free to post whenever is best for you while knowing that if you post late at night or on a weekend, you may not get a response until the next day. As such, do your best not to wait until the last minute to ask a question.

**If you have…**

- **Questions about course content**: these are awesome! We want everyone to see them and have their questions answered too…so post these to Piazza!
- **A technical assignment question**: Come to office hours (or post to Piazza). Answering technical questions is often best accomplished in person where we can discuss the question and talk through ideas. However, if that is not possible, post your question to Piazza. Be as specific as you can in the question you ask. And, for those answering, help your classmates as much as you can without just giving the answer. Help guide them, point them in a direction, provide pseudo code, but do not provide code that answers assignment questions.
- **Been stuck on something for a while (>30min) and aren't even really sure where to start**: Programming can be frustrating and it may not always be obvious what is going wrong or why something isn't working. That's ok - we've all been there! IF you are stuck, you can and should reach out for help, even if you aren't exactly sure what your specific question is. To determine when to reach out, consider the 2-hour rule. This rule states that if you are stuck, work on that problem for an hour. Then, take a 30 minute break and do something else. When you come back after your break, try for another 30 minutes or so to solve your problem. If you are still completely stuck, stop and contact us (office hours, post on Piazza). If you don't have a specific question, include the information you have (what you're stuck on, the code you've been trying that hasn't been happening, and/or the error messages you've been getting).
- **Questions about course logistics**: First, check the syllabus. If the answer is not there, ask a classmate. If you still are unsure,  post on Piazza.
- **Questions about a grade**: Post a **private** note to Instructors on Piazza in the 'regrades' folder. Include specifics as to why you feel you mistakenly/unfairly lost points in that post.
- **A specific section-related question**: post a private question on Piazza addressed to your TA (type their name in the "Post to" field)
- **Something super cool to share related to class**: feel free to email Prof Ellis or come to office hours. Be sure to include COGS 108 in the email subject line and your full name in your message.
- **Something you want to talk about in-depth**: meet in person during office hours or schedule a time to meet by email. Be sure to include COGS 108 in the email subject line.
- **Some feedback about the course you want to share anonymously**: If you've been offended by an example in class, really liked or disliked a lesson, or wish there were something covered in class that wasn't but would rather not share this publicly, etc., please fill out the anonymous [Google Form](https://forms.gle/LVZA26UEkDquEnsW8)
