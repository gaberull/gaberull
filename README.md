GPG: 9650 D040 7B9D D98A 045B 60AA 5355 5A15 6240 9CE4

**Thanks for checking out my GitHub profile!**   👋

## About Me   🙂

I am a new software engineer and recent Computer Science graduate, actively looking for software development work in the Austin, TX area, and/or remote work. I enjoy back-end development, cloud computing, SQL and relational database design/development, and front-end software design and development. I am experienced with parallel/GPU programming, data structures, algorithms, cloud-computing, client-server application development, and engineering mathematics. 

## Current Projects   📂

### Database System and Web Application for Supreme Systems Inc.

[Excel to Mysql Web Application Repo](https://github.com/gaberull/excel_gcp_mysql_webapp)
[Web Application in action!](https://app.gabrielscott.io)

This application does the following:
- Authenticates web user and allows upload of excel document containing employee records for Supreme Systems Inc.
- Uploads original excel file to Google Cloud Storage bucket and organizes files according to upload date
- Parses employee data and converts file to CSV (with option to download)
- Updates MySQL database of employees and marks non-existent employees as "inactive"
- Displays employee records according to the following pre-defined queries:
  - All employee records
  - Active employees
  - Inactive employees
  - Employees with upcoming birthdays (with subcategories for varying lengths of time until birthday)

### PHP Emailer Script for Supreme Systems Inc.

- [Script Code (Link)](https://github.com/gaberull/excel_gcp_mysql_webapp/blob/3c4defd768c5851cd32df36d4df7bf158d745d55/emailer_script/bday_emailer.php)
- Script is scheduled to run daily on GCP Compute Engine VM Instance 
- Queries database of employee records and checks for upcoming employee birthdays within the next ~12 days (adjustable)
- Sends out Notification email to employees' boss about upcoming birthdays, containing employee contact information
  - Purpose of notification is to remind the boss to send out a birthday gift or letter
  - Makes MailJet API calls for sending SMTP emails
- Updates database table specific to this notification process and marks said employee as "notified"

## 😄 Check out some of my repositories :

- [Counting Cards](https://github.com/gaberull/CountingCards)     ♠️
  - A blackjack strategy and educational card counting game with lots of fun features
  - This was a personal project. 100% of work so far has been done by me. 
  - The game is playable, and is currently in the stages of being optimized. It's a lot of fun!
- [Pet Awesome Promotional Email Template](https://github.com/gaberull/gaberull.github.io)  🐕
  - Some professional HTML, CSS work that I was contracted to do for Pet-Awesome Pet Products, an online retailer
  - The company is currently using my email template to contact social media influencers to ink product marketing deals, and having great success with it from what I've heard! 👍 
  - [Viewable HTML Email Template](https://gaberull.github.io) - Email template viewable in webpage format
- [Super Sudoku](https://github.com/gaberull/SuperSudoku) A sudoku game with front-end and back-end development
  - Project that I contributed to with a group of people. The goal was to design and add a front-end user interface to a backend Sudoku game  
- **Lost and Found Database, Website, and Android Application Prototype** for the University of Oklahoma
  - This was my OU Capstone project! **The repository is currently private**, due to some private keys being hard-coded into the files by a classmate of mine.  
  - This project had 7 teams, and a large number of contributors, of which I contributed the 2nd highest number of commits. 
  - ***If you would like to view this project, please ask me to add you as a contributor, and I will be happy to do so!***
😎

### School Assignment Respositories:     📔 

*These repositories were never really meant to be shown off. I made these while I was learning git and completing various assignments at OU. They may or may not have README files with more information about them.*

💻  **Operating Systems Course:**

- [Project 4 - OpSys](https://github.com/gaberull/OpSysProject4) Written in C
- [Project 3 - OpSys](https://github.com/gaberull/OpSysProject3) Written in C
- [Project 2 - OpSys](https://github.com/gaberull/OpSysProject2) Written in C
- [Project 1 - OpSys](https://github.com/gaberull/opSysProject1) Written in C

**Data Structures Course:** 

- [Project4 Data Structures](https://github.com/gaberull/DataStructProject4) - One of the main projects for my Data Structures class at OU

**Programming Structures and Abstractions Course:** 

- [Project 4](https://github.com/gaberull/project4) - Project written in Java for course at OU

*I have several more, but I thought this list was long enough. If you want to see them, ask me and I'll make them public!*

<!--
Complete list of emoji:

https://gist.github.com/rxaviers/7360908#file-gistfile1-md

type a colon and start typing to get a drop-down of emoji options


**gaberull/gaberull** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
