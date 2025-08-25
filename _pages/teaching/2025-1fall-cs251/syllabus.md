---
title: "Syllabus"
collection: teaching
permalink: /teaching/fall25_cs251/syllabus
excerpt: ""
layout: singlefull
---

* [Basic course info](#overview)
* [Course goals and expectations](#expectations)
* [Grading](#grading)
* [Getting help](#help)
* [Academic honesty and AI policy](#ai)

<a id="overview"></a>

## Basic course info

**Course title:** Programming Languages: Design and Implementation

**Instructor:** Anna Meyer (annameyer@carleton.edu, she/her)

**Meeting time & place** 5A in Hulings 316

**Office hours:** TBD. Office hours are open to all students, please stop by! If you would like to meet at a different time, please reach out by email with a list of 3-4 proposed times.

**Course materials:** There are no required textbooks. Readings will be posted on the [course website](https://annapmeyer.github.io/teaching/cs251-fall25).

**Prerequisites:** CS 201 (Data Structures)

**Summary:** In this course, you will be introduced to the study of programming languages. 
Much like how a course in linguistics focuses on the features of human languages (rather than learning a specific natural language like French or Chinese), this course studies concepts that underly programming language construction. We'll learn about different design paradigms and tradeoffs. 

The general outline of the course is as follows: first, we will learn Scheme, a functional language. Then, we will learn C, an imperative language. (Of course, as we learn each language we will also learn about higher-order properties of many classes of programming languages that generalize beyond these specific languages.) The final half of the course will be devoted to writing a Scheme interpreter in C. 


<a id="expectations"></a>

## Course goals, components, and expectations

### Learning goals 
By the end of this course, you will be able to:

* Describe the four main programming paradigms 
* Write complex programs in two new languages: Scheme and C
* Explain the steps of interpreting a program, including tokenizing, parsing, and evaluation
* Implement an interpreter (specifically, implement a Scheme interpreter in C) 
* Identify trade-offs inherent to programming languages design, including features of memory management, parameter passing, and scope.

After completing this course, you will be better equiped to learn new programming languages in the future. You'll also be well-prepared to write high-quality and efficient code. 

###  Course components

* **Class prep:** 
Before most class periods, I will assign a reading and  a short (2-3 question) quiz. Please try to do the readings and quizzes before class, as lecture and activities will assume some familiarity with the reading's topics. 


* **In class:** 
Class meetings will be a mix of lectures and activities. Participation in the activities (discussions, worksheets, and lab activities) is an important component of the course and your learning!  On days that we are doing lab activities in class, please bring your laptop to class if it's convenient to do so. If not, that is fine too: all in-class coding activities will be completed with a partner, so as long as ~50% of the class has a laptop things will work out. 


* **Homework**
Most assignments are coding-based. Some assignments are individual, while others are paired. You can opt out of working with a partner, but I advise against this.
In the first half of the course, homeworks are generally assigned and due each class period. In the second half of the course, homeworks and generally assigned and due every 2 class periods.


* **Exams**
There will be three in-class exams, plus a final exam.  The final exam can be self-scheduled, or you may take it during our scheduled time slot (Saturday, November 22nd at 3:30PM). Exams are closed-book, but you are allowed to have a notes sheet (details TBA). 


### Course expectations

**Communication**
The course schedule, including assignments and their due dates, will be posted on the [course website](https://annapmeyer.github.io/teaching/fall25_cs251/). 

If you have a question about course logistics, content, or assignments, you should post on the **Moodle forum**. If you know the answer to another student's post, feel free to reply to them. If you have a question that's personal (e.g., about grades), please email me instead. I will generally reply to Moodle posts and emails twice a day (morning/afternoon) during weekdays, but only sporadically on evenings and weekends.

Announcements will be made using the Moodle Announcements feature; please make sure your email settings will allow these emails into your inbox.

**Attendance:**
You're expected to come to class and participate as long as you're healthy. If you're sick, please stay home! Early in the term, identify another student in the class who you will be able to ask about course materials. After missing class for illness or another personal emergency, talk with this student about what you missed and copy their notes. 
If you have remaining questions, post on Moodle or attend office hours.

If your personal situation is preventing you from engaging with this class (including missing lots of class and/or not meeting deadlines beyond what is normally allowed with late tokens), you should reach out to the Dean of Students office and me.


**Class participation:**
You should come to class ready to participate.
I request that you not use screens during class unless we are doing a coding activity (or if you have a disability-related accommodation to take notes digitally). Tablets plus a stylus are fine, though. Research has shown that taking notes by hand leads to better material retention, plus screens can be distracting to your classmates. 


**Time commitment** 
A 6-credit Carleton generally requires 10-12 hours of work outside of class. Some students will require more time to learn the material; that is okay. However, if you find yourself spending 15+ hours a week on this class, please come talk to me! We can work on strategies to help you succeed in the class more efficiently. 


<a id="grading"></a>

## Grading
There are three components to your grade: homework, engagement, and exams. 

* **Homework:** Homework grades are based on whether you meet the project specifications (outlined in each assignment). Some homework assignments will be individual and some will be completed with assigned partners. Each assignment is graded on a 4-point rubric. Roughly, 1 means "no progress", 2 means "some progress", 3 is "meets expectations" and 4 is "exceeds expectations". You should think about the rubric grades as categorical, not numeric. 

* **Engagement:** Engagement credits can be earned by completing the pre-class prep work (reading + quiz) and by attending class. There may be additional opportunities to earn engagement credits throughout the term.

* **Exams:** Exams will assess specific learning objectives. Each question will be graded on a 4-point rubric in regards to how well it meets the learning objective(s) targeted by that question. Most learning objectives will be evaluated on at least two exams.

### Conversion to letter grades

I will convert your scores on homework, exams, and enggaement to a letter grade according to the following table. Specifically, I'll choose the highest row for which you meet all requirements. 

| Grade | Homework (3+) | Homework (4) | Exams (3+) | Exams (4) | Engagement |
| A | all | most | all | most | |
| A- | | | | | |
| B+ | | | | | |
| B | | | | | |
| B- | | | | | |
| C+ | | | | | |
| C | | | | | |
| C- | | | | | |
| D+ | | | | | |
| D | | | | | |
| D- | | | | | |
| F | | | | | |

I reserve the right to make the grade cutoffs more generous. (For example, if I make exam questions too challenging or if we run out of time to thoroughly cover all learning objectives.) I will not make the grade cutoffs more strict. 

**Revising your work**
Learning is not a "one and done" process and we all learn at different rates. Unfornately, within the confines of a 10-week academic term it's not practical for myself or the graders to offer unlimited revisions on homework or exam questions. I also don't want to incentivize procrastination, because you learn best when you have time to let concepts sink in. 

To try to strike a middle ground, we have the following revisions policy: If you receive a grade of 2 or 3 on an assignment *for reasons that you could not have reasonably predicted before turning in the assignment*, you may be invited by the graders to resubmit the assignment by a new due date. Reasons for receiving a resubmission opportunity include code style issues (that we haven't discussed previously) and edge cases not covered by the automated tests. If your submission fails the automated tests and/or some sections of the assignment are missing, you will not receive a resubmission opportunity. 


**Late work policy**
Our late work policy aims to balance flexibility for you, structure and fairness for the class as a whole (including your partner), and work/life balance for the instructor and course staff. 

Assignments will be due at 10pm on their due date. There will be a 1-hour buffer built into Moodle; this is meant to account for occasional technical difficulties. 

Assignments will continue to be accepted for 2 days (48 hours) after their deadline. You have **5 late tokens** available to use throughout the term. Using a token allows you to submit an assignment within the 48-hour late work deadline without penalty. Once your late tokens are used up (or if you elect not to use a token for a late submission to save the tokens), assignments will receive a maximum score of 3. To turn in a paired assignment late, each partner much use a late token. 
All work other than the final must be submitted by the last day of classes, per college policy. As a result, you cannot use late tokens on the final project submission. 

If at any point you fall behind and the late work policies outlined here will not be sufficient for you to catch up, please reach out sooner rather than later.
I want you to succeed in this course, and we will likely be able to work something out.



<a id="help"></a>

## Getting help
I want you to succeed in this course! If you're stuck or struggling, there are lots of resources avaiable. 

* Talk to your classmates. Learning is a collaborative process, and if you are struggling on something, it's likely that others are as well. (Alternatively, asking a classmate who thinks they understand a concept gives them a chance to solidify their knowledge.)

* Participate. Ask questions during class when you're curious or confused about something. Be engaged in small- and large-group discussions.  

* Go to prefect sessions. 

* Come to my office hours. This is time I set aside for all students, and I want you to come with your questions (or general confusion, or just to chat). If you're not able to make it during the scheduled office hours or if you need to discuss somethign privately, email me with 3-4 meeting time options. 

* Take breaks. Relatedly, start your homework early and try to work in small chunks rather than cramming everything in last minute. Oftentimes when you're stuck on a problem, taking 20 minutes or an hour to decompress can let you think of the solution later.

* Use other Carleton resources, including:

    * CS lab assistants

    * Class Deans in the Dean of Students Office are a great resource if you are dealing with personal situations or emergencies that impact your ability to succeed in your classes.

    * The Academic Skills Center

    * SHAC, The Office of Health Promotion, and the Chaplain's Office can all provide support for maintaining your physical and mental health. Carleton terms are intense and challenging, and your health and well-being should always come first. 


<a id="ai"></a>

## Academic honesty and AI policy

### Working in teams
Each programming assignment in this class will be either **individual** or **paired**. 

* **Individual assignments:** You can discuss ideas with classmates, but not share code. In particular, you should be the only person who types code in the assignment, and you should not access code written by others or share your code with others. 

* **Paired assignments:** You can (and should!) discuss ideas and share code with your partner. Otherwise, follow the same rules as for individual assignments.

* **All assignments:** If you discuss an assignment with people other than an assigned partner, you should acknowledge this collaboration and which ideas you discussed in the `CollaborationsAndSources.txt` file that you hand in with each assignment.

### Guidelines for pair programming

When working on paired assignments, both partners should contribute equally and both people should be able to explain all parts of the submission. 
I except that the majority (>80%) of time working on assignments will be side-by-side in a pair programming arrangement. Many of you will have used pair programming in a previous course, but as a refresher:

* Both team members work side-by-side on one machine.
* One team member is the driver and the other one is the navigator. The driver types code, while the navigator provides ideas in conversation with the driver. The roles should switch every 15-20 minutes.

It is okay to work separately on *specific, concrete tasks*. This should be used as a way to mitigate scheduling conflicts and time crunches. For instance, if your code produces an error at the end of the pair programming session, one partner may spend an hour debugging the error prior to the next paired meeting. Or, if you and your partner have discussed the desired structure for a specific function, one person may implement that function. 
Both partners need to be familiar with all pieces of code that are turned in (e.g., you should be able to explain each function to me -- what it does and how it fits into the larger picture).

Both partners are responsible for maintaining academic honesty. If you have concerns about academic honesty (e.g., if your partner is programming with CoPilot activated), have a conversation and remind them about the course policies. If issues persist, please talk to me.

### Use of external resources, AI and otherwise
Unless otherwise stated on a particular assignment, it is fine to use general reference resources (e.g., readings posted on the course webpage, documentation like the [Scheme](https://www.scheme.com/tspl4/) or [C](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html) manuals, Wikipedia). You should cite these resources and describe how you used them in `CollaborationsAndSources.txt`. Very basic things (e.g., looking up standard syntax) don't need to be cited. If you're unsure if something qualifies as "very basic," err on the side of citing it.

For the purposes of this class, AI includes (but is not limited to) coding assistants like GitHub CoPilot and chatbots like ChatGPT or Claude. **You are not allowed to use these resources on homework, unless an assignment explicitly says otherwise.** 

You should not use Google, Stack Overflow, or any AI tools (etc.) to search for specific homework problems or subproblems. You also cannot post questions about the homework online except on Moodle. 

Specific behaviors that violate this course's academic honesty policy include (but are not limited to):

* Copying code (from online, from a friend, from an AI tool, etc.) and turning it in as your own. Likewise, modifying someone else's code by changing variable names or restructuring lines is also plagiarism.

* Looking at code that solves the homework (from online, from a friend, from AI) and then writing your own code based on what you saw.

* Turning in code that your friend or an AI agent debugged for you

* Asking a homework question online (to an AI, to a forum, to another human) except on CampusWire

* Directly copying code from an assigned reading without citing it.

TODO - what about generating practice problems? What about debugging errors?


This syllabus is adapted from syllabi by Anna Rafferty, Dave Musicant, Bridger Herman, and Anya Vostinar.