---
layout: page
title: CS109 Data Science Syllabus
---

**Instructors:** Hanspeter Pfister (Computer Science), Joe Blitzstein (Statistics), Verena Kaynig-Fittkau (Computer Science)

Welcome to CS109! The course is also listed as STAT121 and AC209, and offered through the Harvard University Extension School as distance education course CSCI E-109. 

**What is this class about?**

This class is about learning from data, in order to gain useful predictions and insights. Separating signal from noise presents many computational and inferential challenges, which we approach from a perspective at the interface of computer science and statistics.  Through real-world examples of wide interest, we introduce methods for five key facets of an investigation:

* *data munging/scraping/sampling/cleaning* in order to get an informative, manageable data set;

* *data storage and management* in order to be able to access data - especially big data - quickly and reliably during subsequent analysis;

* *exploratory data analysis* to generate hypotheses and intuition about the data;

* *prediction* based on statistical tools such as regression, classification, and clustering; and

* *communication* of results through visualization, stories, and interpretable summaries.

**Why take this class?**

Hal Varian, Chief Economist at Google, said that:

"The sexy job in the next ten years will be statisticians. The ability to take data, to be able to understand it, to process it, to extract value from it, to visualize it, to communicate it, that\'s going to be a hugely important skill."

More and more applications in industry, academia, and everyday life are---or should be---based on careful analysis of *data*. For example, consider the book *Moneyball* (for sports) and the work of Nate Silver (for elections as well as sports). More and more data sets are becoming available, to the point where some companies have described themselves as "drowning in data". This presents many opportunities, but the right tools from *both* computer science and statistics are needed so that you can learn from the data *without* drowning.

**Expected Learning Outcomes**

After successful completion of this course, you will be able to:

* Use Python and other tools to scrape, clean, and process data

* Use data management techniques to store data locally and in cloud infrastructures

* Use statistical methods and visualization to quickly explore data

* Apply statistics and computational analysis to make predictions based on data


* Apply basic computer science concepts such as modularity, abstraction, and encapsulation to data analysis problems

* Implement data-intensive computations on cluster and cloud infrastructures using MapReduce

* Effectively communicate the outcome of data analysis using descriptive statistics and visualizations 

**Who should take this class?**

The prerequisite for this class is programming knowledge at the level of CS 50 (or above), and statistics knowledge at the level of Stat 100 (or above). Both undergraduates and graduate students are welcome to take the course.

**What is the structure of the class?**

There will be three major modules, each focusing on an important arena in which data science is playing a crucial role. Within each module, we will study how to gather, explore, and analyze relevant data, as well as how to communicate the results. The major programming language used will be Python. 

There will be five problem sets, in which students will learn about learning from data *actively*---by doing it! There will also be a major final project, in which students can explore data they are excited about in a more open-ended setting.


The three modules are:

*1. Prediction and elections:* how did Nate Silver predict 50 out of 50 states correctly in the 2012 U.S. presidential election, and 49 out of 50 correctly in the 2008 election? How much of that was luck? We will discuss how to find, process, combine, visualize, simulate, and summarize election-related data and questions, especially if there are conflicting polls with different reliabilities.

*2. Recommendation and business analytics*: the Neflix Prize was a famous recent example of collaborative filtering: given information about which movies various users have liked and disliked, how should Netflix make recommendations for what movies a user should watch? Many other companies are interested in closely-related problems. Often there is a very large but very sparse data set (e.g., there could be millions of users and tens of thousands of movies, but very few users rate more than a few hundred movies). We will explore techniques for working with such data.

*3. Clustering and text analysis:* Finding structure in  unlabeled data is an important aspect of data science. We will talk about methods for various types of data, including text document analysis via topic modeling. Topic modeling answers questions like: Which topics does a specific document talk about? Which tags would be appropriate for this image according to its description? What is the most important topic of our customers twitter feeds? 

## Course Logistics

**Prerequisites**

Programming knowledge at the level of CS 50 or above, and statistics knowledge at the level of Stat 100 or above (Stat 110 recommended). Extension school students should have knowledge corresponding to CSCI E-26 and STAT E-150 or above. 

**Required Textbook**

None. Instead, we have a list of recommended readings on the web site. 

**Online Discussion Forum**

We'll be using [Piazza](http://www.piazza.com/) as our online forum. Piazza is your main venue to ask questions, discuss problems, and help each other out. Piazza is a question-and-answer system designed to streamline class discussion outside of the classroom. It should always be your first recourse for seeking answers to your questions about the course, lecture or reading material, or the assignments. Piazza supports LaTeX, code formatting, embedding of images, and attaching of files. We will also use Piazza for all announcements, so it is important that you are signed up. 

**Online Videos**

Videos of all lectures and labs will be made available online. Archived videos will be available about 24 hours after meeting times from the course homepage. 

**Office Hours**

The staff will hold weekly office hours, either in person or online for distance education students. Office hour times and locations will be listed on Piazza. Office hours provide you with an opportunity to review and discuss course materials as well as provide further guidance for your homework in a more intimate environment, with only your teaching fellow and maybe a handful of classmates present. Distance education students can make special arrangements directly with their assigned Teaching Fellows to meet online. 

## Course Components

**Lectures**

The class meets twice a week for lectures and joint class activities. The class activities are designed to help you master the relevant materials, to work on your homework in groups, and to get you started on your project. The weekly schedule of lectures is posted on the course web site. 

**Sections**

Lectures are supplemented by weekly sections led by the teaching fellows. Sections are limited to about 20 students (the numbers may vary due to enrollment). One of the sections will be recorded and made available online. Sections are an important aspect of the course, as they are meant to give you the technical skills to successfully complete the homework assignments and projects, complementing the theoretical knowledge taught in lectures. Sections will typically consist of a short presentation and live coding by a teaching fellow. Sections will also give you the opportunity to work on your homework and your projects while a TF is present to answer your questions. Section topics are announced in the schedule. 
Section attendance is **mandatory** for all on-campus students and will be considered for your participation grade. You are allowed **two excused absences** for the semester without penalty. Thereafter you will receive zero credit for the missed sections. To receive an excused absence you must notify your TF in advance. 

**Homework**

The homework is going to provide an opportunity to learn data science skills and to test your understanding of the material. See the homework as an opportunity to learn, and not to "earn points". The homework will be graded holistically to reflect this objective. 

**Project**

Towards the end of the course you will work on a month-long data science project. The goal of the project is to go through the complete data science process to answer questions you have about some topic of your own choosing. You will acquire the data, design your visualizations, run statistical analysis, and communicate the results. You will work closely with other classmates in a **3-4 person project team**. You can come up with your own teams and use Piazza to find prospective team members. If you cannot find a partner we will team you up randomly. We recognize that individual schedules, different time zones, preferences, and other constraints might limit your ability to work in a team. If this the case, ask us for permission to work alone. 

## Course Policies

**Assessment Procedure**

Your final grade will be determined by the number of points you collect. You can collect various amounts of points for the different parts of the class:

* **Homework: 50%**, assessed on your individual submission.
* **Project: 40%**, assessed on meeting the project criteria and your peer assessment.
* **Participation: 10%** assessed on participation on Piazza and (for on-campus students) section attendance.
* **Best Projects:** We will elect the top three project submissions that will get extra points.

Homework, project, and participation will be graded holistically beyond mechanical correctness and focusing on the overall quality of the work using the following 10 point scale in 1 point increments:

10 = Excellent / no mistakes (or really minor)

8 = Good / some mistakes

5 = Fair / some major conceptual errors

2 = Poor / did not finish

0 = Did not participate / did not hand in

Teaching Fellows will evaluate your work holistically beyond mechanical correctness and focus on the overall quality of the work. 

In addition to the scores the Teaching Fellows will give detailed written feedback.

**Project Group Peer Assessment**

In the professional world, three important features affect your productivity and success: your own effort, the effort of people you depend on, and the way you work together. For this reason we have chosen a team-based approach that values all three of those features. After the team-based project you will provide an assessment of the contributions of the members of your team, including yourself. Your teammates' assessment of your contributions and the accuracy of your self-assessment will be considered as part of your overall course evaluation.

**Collaboration Policy**

You are welcome to discuss the course\'s ideas, material, and homework with others in order to better understand it, but **the work you turn in must be your own** (or for the project, yours and your teammate\'s). For example, you must write your own code, run your own data analyses, and communicate and explain the results in your own words and with your own visualizations. You may not submit the same or similar work to this course that you have submitted or will submit to another. Nor may you provide or make available solutions to homeworks to individuals who take or may take this course in the future. You are responsible for understanding the [Harvard College](https://college.harvard.edu/academics/academic-integrity) and [Extension School](www.extension.harvard.edu/resources-policies/student-conduct/academic-integrity) policies on academic integrity and how to use sources responsibly. Not knowing the rules, misunderstanding the rules, running out of time, submitting "the wrong draft", or being overwhelmed with multiple demands are not acceptable excuses. There are no excuses for failure to uphold academic integrity. 

**Quoting Sources**

You must acknowledge any source code that was not written by you by mentioning the original author(s) directly in your source code (comment or header). You can also acknowledge sources in a README.txt file if you used whole classes or libraries. Do not remove any original copyright notices and headers. However, you are encouraged to use libraries, unless explicitly stated otherwise! You may use examples you find on the web as a starting point, provided its license allows you to re-use it. You must quote the source using  proper citations (author, year, title, time accessed, URL) both in the source code and in any publicly visible material. You may not use existing complex combinations or large examples. For example, you may not use a ready to use multiple linked view visualization. You may use parts out of such examples. To support your learning about academic citation rules, please visit the Harvard Extension School [Tips to Avoid Plagiarism](www.extension.harvard.edu/resources-policies/resources/tips-avoid-plagiarism), where you'll find links to the Harvard Guide to Using Sources and two, free, online 15-minute tutorials to test your knowledge of academic citation policy. The tutorials are anonymous open-learning tools. 

**Questionnaires**

During the course of the semester, you will complete a number of questionnaires online. The purpose of these questionnaires is to evaluate how well this course works for you. Your answers will only be used to provide feedback on your learning and make adjustments to the course. They will not affect your grade in any way. Unless stated otherwise, you may neither look up any information, nor consult others during these questionnaires.

**Missed Activities and Assignment Deadlines**

Projects and homework **must** be turned in on time, with the exception of late days for homeworks as stated below. It is important that everybody attends and proactively participates in class and online. We understand, however, that certain factors may occasionally interfere with your ability to participate or to hand in work on time. If that factor is an extenuating circumstance, we will ask you to provide documentation directly issued by the University, and we will try to work out an agreeable solution with you (and your teammates). 

**Homework Deadlines and Late Days**

In the weeks when homeworks are due, they will be **due on Thursdays at 11:59 pm EST** unless otherwise announced. Each student is given **six late days** for homework at the beginning of the semester. A late day extends the individual homework deadline by 24 hours without penalty. **No more than two late days may be used on any one assignment. Assignments handed in more than 48 hours after the original deadline will not be graded.** If you have already used all of your late days for the semester, we will deduct 2 point for assignments <24 hours late, and 4 points for assignments 24-48 hours late. We do not accept any homeworks under any circumstances more than 48 hours after the original deadline. Late days are intended to give you flexibility: you can use them for any reason - no questions asked. You don\'t get any bonus points for not using your late days. You can only use late days for the individual homework deadlines. All other deadlines (e.g., project milestones) are hard. 

**Regrading Policy**

It is very important to us that all assignments are properly graded. If you believe there is an error in your assignment grading, please submit an explanation via email to us (the staff mailing list) **within 7 days of receiving the grade**. No regrade requests will be accepted orally, and no regrade requests will be accepted more than 7 days after the grades for the assignment have been sent out. The teaching staff will re-examine your entire assignment. So your score may go up, stay the same, or go down.    

**Guest Lecture Attendance**

We are lucky to have some of the world\'s best researchers take time out of their busy schedules to give guest lectures. We expect all non-distance students to attend these lectures in person and to engage the speakers with questions and comments. You must send an email to the staff at least one day before a guest lecture to be excused.

## Additional Information

**Accessibility**

If you have a documented disability (physical or cognitive) that may impair your ability to complete assignments or otherwise participate in the course and satisfy course criteria, please meet with us at your earliest convenience to identify, discuss, and document any feasible instructional modifications or accommodations. You should also contact the Accessible Education Office to request an official letter outlining authorized accommodations. The Extension School is committed to providing an accessible academic community. The Disability Services Office offers a variety of accommodations and services to students with documented disabilities. Please visit [this webpage](www.extension.harvard.edu/resources-policies/resources/disability-services-accessibility) for more information. 

**Credits**

Some of the material in this course is based on other classes. We have also heavily drawn on materials and examples found online and tried our best to give credit by linking to the original source. Please contact us if you find materials where the credit is missing or that you would rather have removed. 

**User Notice for Copyrighted Materials on Course Websites**

This course website, and much of the text, images, graphics, audio and video clips, and other content of the site (collectively, the "Content"), are protected by copyright law. In some cases, the copyright is owned by third parties, and Harvard is making the third-party Content available to you under the fair use doctrine. Fair use permits only certain limited uses of the Content. You may use the website and its Content only for your personal, noncommercial educational and scholarly use. Some Content may be provided via streaming or other means that restrict copying; you may not circumvent those restrictions. If you wish to distribute or make any of the Content available to others, or to use any Content commercially, or to use any Content for any purpose other than your personal, noncommercial educational and scholarly use, you must obtain any required permission from the copyright holder. User notice courtesy of the Harvard University Office of General Counsel.



