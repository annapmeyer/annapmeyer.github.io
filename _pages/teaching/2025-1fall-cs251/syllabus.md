---
title: "Syllabus"
collection: teaching
permalink: /teaching/fall25_cs251/syllabus
excerpt: ""
layout: singlefull
---


## Basic info

**Course title:** Programming Languages: Design and Implementation

**Instructor:** Anna Meyer (annameyer@carleton.edu, she/her)

**Meeting time & place** 5A in Hulings 316

**Office hours:** TBD. Office hours are open to all students, please stop by! If you would like to meet at a different time, please reach out by email with a list of 3-4 proposed times.

**Course materials:** There are no required textbooks. Readings will be posted on the [course website](https://annapmeyer.github.io/teaching/cs251-fall25).


## Overview

In this course, you will be introduced to the study of programming languages. 
Much like how a linguistics course focuses on the features of human languages rather than trying to teach you French or Chinese, this course studies choices in how programming languages are constructed. We'll learn about different design paradigms and tradeoffs. 
For illustrative purposes, we will learn two languages: Scheme and C. 

The general outline of the course is as follows: first, we will learn Scheme, a functional language. Then, we will learn C, an imperative language. (Of course, as we learn each language we will also learn about higher-order properties of many classes of programming languages that generalize beyond these specific languages.) The final half of the course will be devoted to writing a Scheme interpreter in C. 

### Course goals

## Logistics

**Prerequisites:** CS 201 (Data Structures)

## Course setup, expectations, and grading

### Attendance 

You're expected to come to class and participate. Classes will contain interactive exercises, and even during class periods that are primarily lecture-based, I try to create opportunities to think actively about the concepts we're learning.

I realize that sometimes sickness or personal emergencies will necessitate missing class. Early in the term, identify another student in the class who you will be able to ask about course materials. After missing class, talk with this student about what you missed and copy their notes. 
If you have remaining questions, post on CampusWire or attend office hours.

### Course components

**Class meetings** 
Class meetings will be a mix of lectures and activities. Activities will be either coding activities or worksheets. If it's convenient for you to bring your laptop to class, please do so. If not, that is fine too: all in-class coding activities will be completed with a partner so as long as ~50% of the class has a laptop each day things will work out.

I request that you not use screens during class unless we are doing a coding activity (or if you have a disability-related accommodation to take notes digitally). Tablets plus a stylus are fine, though. Research has shown that taking notes by hand leads to better material retention, plus screens can be very distracting to your classmates. 

**Quizzes**
There will be five in-class quizzes. These will be announced in advance and will (depending on the quiz) last between 30 minutes and the whole class period.

Quizzes will be graded based on meeting specific learning objectives. The learning objectives will be identified ahead of time. You will generally have multiple opportunities to meet each learning objective.

**Homework**
Most assignments are coding-based. Some assignments are individual, while others are paired. You can opt out of working with a partner, but I advise against this.

In the first half of the course, homeworks are generally assigned and due each class period. In the second half of the course, homeworks and generally assigned and due every 2 class periods.

Homework will be grading according to how well it meets a set of specifications outlined in each assignment. 

### Grading
There are just two components to your grade: homework (50%) and quizzes (50%). 

**Late work policy**
Our late work policy aims to balance flexibility for individuals, structure and fairness for the class as a whole (including your partner), and work/life balance for the instructor and course staff. 

Assignments will generally be due at 10pm on their due date. There will be a 1-hour buffer built into Moodle; this is meant to account for occasional technical difficulties. 

Each student gets **5 late tokens**. Each late token allows you to submit an assignment 1 day (24 hours) late at no penalty. You may use up to 2 tokens per assignment. 
To turn paired assignments late, each student must use a late token. 

All work must be submitted by the end of finals period, per college policy. As a result, you cannot use late tokens on the final project submission. 

If at any point you fall behind and the late work policies outlined here will not be sufficient for you to catch up, please reach out sooner rather than later.
I want you to succeed in this course, and we will likely be able to work something out.


## Getting help

* Talk to your classmates. Learning is a collaborative process, and if you are struggling on something, it's likely that others are as well. (Alternatively, asking a classmate who thinks they understand a concept gives them a chance to solidify their knowledge.)

* Participate. Ask questions during class when you're curious or confused about something. Be engaged in small- and large-group discussions.  

* Go to prefect sessions. 

* Come to office hours. Come with specific questions or general confusion (or just to chat). 

* Take breaks. Relatedly, start your homework early and try to work in small chunks rather than cramming everything in last minute. Oftentimes when you're stuck on a problem, taking 20 minutes or an hour to decompress can let you think of the solution later.

* Use other Carleton resources, including:

    * CS lab assistants

    * Class Deans in the Dean of Students Office are a great resource if you are dealing with personal situations or emergencies that impact your ability to succeed in your classes.

    * The Academic Skills Center

    * SHAC, The Office of Health Promotion, and the Chaplain's Office can all provide support for maintaining your physical and mental health. Carleton terms are intense and challenging, and your health and well-being should always come first. 


## Academic honesty and AI policy

### Working in teams
Each programming assignment in this class will be either **individual** or **paired**. 

For **individual** assignments, it is okay to discuss ideas with classmates, but not to share code. In particular, you should be the only person who types code in the assignment, and you should not access code written by others or share your code with others. If you discuss an assignment with others, you should acknowledge this collaboration and which ideas you discussed in the `CollaborationsAndSources.txt` file that you hand in with each assignment.

For **paired** assignments, you can (and should!) talk to and share code with your partner. For talking with others who are not your partner, the same rules apply as with individual assignments.

**Guidelines for pair programming**
When working on paired assignments, both partners should contribute equally and both people should be able to explain all parts of the submission. 
I except that the majority (>80%) of time working on assignments will be side-by-side in a pair programming arrangement. Many of you will have used pair programming in a previous course, as a refresher:

- Both team members work side-by-side on one machine.
- One team member is the driver and the other one is the _____. The driver is typing code, while the ____ is providing ideas in conversation with the driver. The roles should switch every 15-20 minutes.

It is okay to work separately on *specific, concrete tasks*. This should be used as a way to mitigate scheduling conflicts and time crunches. For instance, if your code produces an error at the end of the pair programming session, one partner may spend an hour debugging the error prior to the next paired meeting. Or, if you and your partner have discussed the desired structure for a specific function, one person may implement that function. 
Both partners need to be familiar with all pieces of code that are turned in (e.g., you should be able to explain each function to me -- what it does and how it fits into the larger picture).

Both partners are responsible for maintaining academic honesty. If you have concerns about academic honesty (e.g., if your partner is programming with CoPilot activated), have a conversation and remind them about the course policies. If issues persist, please talk to me.

### Use of external resources, AI and otherwise
Unless otherwise stated on a particular assignment, it is fine to use general reference resources (e.g., readings posted on the course webpage, documentation like the [Scheme]() or [C]() manuals, Wikipedia). You should cite these resources and describe how you used them in `CollaborationsAndSources.txt`. Very basic things (e.g., looking up standard syntax) don't need to be cited. If you're unsure if something qualifies as "very basic," err on the side of citing it.

For the purposes of this class, AI includes (but is not limited to) coding assistants like GitHub CoPilot and chatbots like ChatGPT or Claude. **You are not allowed to use these resources, unless an assignment explicitly says otherwise.** 

You should not use Google, Stack Overflow, or any AI tools (etc) to search for specific homework problems or subproblems. You also cannot post questions about the homework online except on CampusWire. 

Specific behaviors that violate this course's academic honesty policy include (but are not limited to):

- Copying code (from online, from a friend, from an AI tool, etc.) and turning it in as your own. Likewise, modifying someone else's code by changing variable names or restructuring lines is also plagiarism.

- Looking at code (from online, from a friend, from AI) and then writing your own code based on what you saw.

- Turning in code that your friend or an AI agent debugged for you

- Asking a homework question online (to an AI, to a forum, to another human) except on CampusWire

- Directly copying code from an assigned reading without citing it.






This syllabus is adapted from syllabi by Anna Rafferty, 