# DIGHUM 101-2026

Course Catalog: [https://classes.berkeley.edu/content/2026-summer-dighum-101-001-lec-001](https://classes.berkeley.edu/content/2026-summer-dighum-101-001-lec-001)

Offered Through: [UC Berkeley D-Lab](https://dlab.berkeley.edu/)

__Instructor:__ [Matthew Kollmer](https://matthewkollmer.com/)

__Dates:__ May 26 – July 2, 2026 - Mondays, Tuesdays, Wednesdays, Thursdays

__Time:__ 1:00 - 3:00 PM (Pacific Time)

__Office Hours:__ Mondays and Tuesdays, 3:00 - 4:00 PM or by appointment on Zoom

__Prerequisites:__ None

__Requirements:__ Computer, Zoom account, and Internet connection

## Course Description

The digital and data revolution has begun to transform the study of the humanities by introducing new archival data sources, tools and methods, and modes of analysis. In this applied course, students will learn foundational knowledge of Python, the leading programming language in Digital Humanities and data science. By the end of this course, students will be able to program Python in Jupyter Notebooks, analyze and visualize data for purposes of computational text analysis and gain a fundamental understanding of machine learning.

## Learning Objectives

The goal of this course is to teach you basic principles for conducting professional research in the Digital Humanities. You will learn how to program Python in Jupyter Notebooks to access, explore, visualize, and analyze data in humanities contexts. You are strongly encouraged to concurrently enroll in [DIGHUM 100 – Theory and Methods in the Digital Humanities](https://classes.berkeley.edu/index.php/content/2025-summer-dighum-100-001-lec-001) to complement this experience with a strong theoretical foundation. By the end of this course, you will learn:

- A variety of Pythonic approaches to explore questions in the humanities;
- How to understand data more holistically, its generative process and lifecycle;
- Strategies for organizing research projects based on your interests;
- Methods for data acquisition and visualization, computational text analysis, and machine learning;
- The importance of developing a critical lens in your field of study.

## Course Overview

This course will meet four days a week on Zoom. Each class is divided into two types:

- __Lecture days:__ The instructor will lecture on core concepts in Python and the digital humanities and provide coding walkthroughs in Jupyter notebooks. Most lecture days will also include coding exercises and time for questions and discussion.
- __Project days:__ These days will be exclusively focused on your individual and group projects. They are structured work time with the instructor(s) available to answer questions or concerns.

## Software Installations and Set Up

__Please attempt these setup steps before the first day of class.__ We’ll go over the setup process together, but if you attempt setup before the first day it will be easier to identify any issues in the process.

We will learn to use the programming language __Python.__ Just as you use a text editor like Microsoft Word for writing, you'll need a code editor to write and manage your code. In our case, we’ll be using __Visual Studio Code (VS Code)__, a user-friendly and free editor designed for programming.

To install and manage additional tools or __libraries__ (also called __packages__) that extend Python’s functionality, we will use a __package manager__–specifically, __Conda__. Conda allows us to install, update, and organize the various packages we’ll need throughout the course.

Finally, we will be using __GitHub__, a platform for sharing and collaborating on code. GitHub allows you to store your code in the cloud, track changes over time, and work with others on shared projects, similar to Google Docs.

Please follow the steps below to install the required software:

### 1) Anaconda
- Go to the Anaconda Installer: [https://www.anaconda.com/download/success](https://www.anaconda.com/download/success)
- Navigate to your device type download (Mac or Windows)
- Download Miniconda 
    - You could download Anaconda Distribution instead, but it shouldn’t be necessary for this class. For more info about the differences, see here: [https://www.anaconda.com/docs/getting-started/concepts/anaconda-or-miniconda](https://www.anaconda.com/docs/getting-started/concepts/anaconda-or-miniconda)
    - If you’re getting an error message that reads something like “you can’t download to this device”, try going to [https://repo.anaconda.com/miniconda/](https://repo.anaconda.com/miniconda/). Then choose the file that matches your type of device and also ends with “.pkg”.
- Click through the installation setup

### 2) GitHub 
- Go to [https://github.com/](https://github.com/)
- Click “sign up” in the top right corner
- Create your account

### 3) VS Code
- Visit VS Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Click “download” for your device
- Follow the download directions
- Open VS Code and select “Continue with GitHub”
- Sign into VS Code with your GitHub account

### 4) Git and the Terminal
- In VS Code, look to the menu bar and select “Terminal” then “New Terminal”
- From the Terminal, copy and paste this line of text: 

```bash
git clone https://github.com/dlab-berkeley/DIGHUM101-2026.git
```

- Then press enter. This should download a folder called DIGHUM101-2026 onto your computer. In VS Code, open that folder before continuing.
    - Note for Mac users: the first time you use Git, your computer may ask you to install “Command Line Developer Tools.” Click “install” and wait for the installation to finish. This gives your computer access to the git command needed to clone the course repository.
- At this point, some of you may be all set up. Hooray! You can test if you’re set up by opening Week 1, opening file 1_1_setup.ipynb and running its code.
- If you can’t run 1_1_setup.ipynb, go back to the Terminal. Type this line of text:

```bash
cd DIGHUM101-2026
```

- Then hit enter and then type this line of text:
    
```bash
conda env create -f environment.yml
```
 
- Then hit enter. This will tell Anaconda to build your Python environment based on the directions in the environment.yml file (part of the course download).
- Once downloaded, type 

```bash
conda activate dighum101
```

in the Terminal. Then test if you’re all set up with 1_1_setup.ipynb. 

A final note on this setup process: if you’re following along this way, you can easily download the latest course materials by simply typing: 

```bash
git pull
```

into the Terminal. This will download any new stuff as we move through the course.

## Assignments and Grading

- Attendance and Participation: 10%

- Individual Project
    - Topic Statement: 10%
    - Demonstration of Code: 20%
    - Project Showcase: 10%

- Group Project
    - Topic Statement: 10%
    - Short Paper: 20%
    - Presentation: 10%

- Final Video Reflection: 10%

Grading is straight scale: A=90-100; B=80-89; C=70-79; D=60-69; F<60

## Assignment Descriptions

### Attendance
 
This course is synchronous and attendance is required. Attendance will be tracked through Zoom sign-ins. Please be present during our Zoom meetings. Come prepared to listen, ask questions, make comments, and attempt coding exercises.

Attendance makes up 10% of your overall grade.

### Individual Project

The individual coding project is an opportunity to become more comfortable with Python. The scale and degree of individual coding projects will vary. If you already have some programming experience, you may want to develop a larger, more intensive project. If you’re new to coding, your project may borrow code and ideas from class and apply them to different data or variables. In either case, the goal is simply to practice your coding skills and develop greater familiarity with Python.

It is completely fine if parts of your initial plans for the individual coding project prove more difficult or complicated than you anticipated. While you will need to submit executable code as part of the project, it is also important to _document and describe what didn’t work._ What proved too time-consuming? What parts of coding in Python were challenging? These details should be included in your submissions alongside your final code versions.

The Individual Coding Project is worth 40% of your overall grade. It is split into three parts: the Topic Statement, the Demonstration of Code, and the Project Showcase. For more info, see the [Individual Project Directions.](https://github.com/dlab-berkeley/DIGHUM101-2026/blob/main/assignments/individual_project_directions.md)

### Group Project

The group project allows you to survey a Python-dependent method in the digital humanities and reflect on its broader contributions to the field. The group project also invites you to think about the collaborative nature of the digital humanities–a field where researchers often work in teams or labs and where the work depends on layers of interdependent technologies and resources. There is no coding required for the group project. Instead, you will be studying related papers or projects that use Python to enact the method of your choosing.

The Group Project is worth 40% of your overall grade. It is split into three parts: the Topic Statement, the Short Paper, and the Presentation. For more info, see the [Group Project Directions.](https://github.com/dlab-berkeley/DIGHUM101-2026/blob/main/assignments/group_project_directions.md)

### Final Video Reflection

At the end of the course, you will submit a brief video (3-5 minutes) reflecting on your experiences and taking inventory of your personal development as a programmer with Python. This video reflection is a simple way to describe what you’ve learned and how you may or may not pursue Python in the digital humanities moving forward.

The Final Video Reflection is worth 10% of your overall grade.

## Schedule

| Week | Date | Topics |
|------|------|---------|
| 1 | May 25 | NO CLASS – Memorial Day |
| 1 | May 26 | Syllabus, major assignments, setup, getting started |
| 1 | May 27 | Vocabulary, data types & structures, reading errors, libraries |
| 1 | May 28 | Pandas intro, Project workday (group assignments, brainstorming topics) |
| 2 | June 1 | Functions, conditionals, iterations |
| 2 | June 2 | Pandas overview |
| 2 | June 3 | Text analysis, regular expressions, preprocessing, tokenization, word frequency analysis |
| 2 | June 4 | Project workday: choosing methods, identifying datasets |
| 3 | June 8 | Text analysis continued, n-grams, pos-tagging, TF-IDF |
| 3 | June 9 | Data visualization |
| 3 | June 10 | Web scraping, APIs |
| 3 | June 11 | Project workday: group project collaboration |
| 4 | June 15 | Web scraping, APIs continued |
| 4 | June 16 | Network Analysis, Geospatial data |
| 4 | June 17 | Machine learning intro, topic modelling, text classification |
| 4 | June 18 | Project workday: individual project time |
| 5 | June 22 | Machine learning continued, sentiment analysis, NER, word embeddings |
| 5 | June 23 | Machine learning continued, Transformers, BERT |
| 5 | June 24 | Transformers, LLMs, coding with LLMs |
| 5 | June 25 | Project workday: group project collaboration, individual project time |
| 6 | June 29 | Asynchronous – individual project showcase |
| 6 | June 30 | Asynchronous – individual project showcase feedback |
| 6 | July 1 | Group presentations |
| 6 | July 2 | Group presentations |

## Assignment Due Dates

| Week | Assignments Due |
|------|-----------------|
| 1 | None |
| 2 | Individual Project: Topic Statement Due Friday, June 5 at 11:59pm |
| 3 | Group Project: Topic Statement Due Friday, June 12 at 11:59pm |
| 4 | None |
| 5 | Individual Project: Demonstration of Code Due Sunday, June 28 at 11:59pm |
| 6 | Individual Project: Recorded Showcase Due Monday, June 29 at 12:00pm<br>Individual Project: Showcase Feedback Due Tuesday, June 30 at 11:59pm<br>Group Project: Presentation Due Wednesday, July 1 at 1:00pm<br>Group Project: Short Paper Due Friday, July 3 at 11:59pm<br>Final Video Reflection Due Friday, July 3 at 11:59pm |