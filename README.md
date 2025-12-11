# Google-IT-automation-with-python

 For learners with no IT background at all, we recommend taking the
 Google IT Support Professional Certificate
 https://www.coursera.org/professional-certificates/google-it-support

 On top of search results, here are some good programming resources available online:

The official Python tutorial. This tutorial is designed to help people teach themselves Python. While it goes in a different order than the one we're taking here, it covers a lot of the same subjects that we explore in this course. You can refer to this resource for extra information on these subjects.
https://docs.python.org/3/tutorial/index.html

The Think Python book. This book aims to teach people how to program in Python. It's available online in PDF and browsable forms. Again, you can use this resource to learn more about some of the subjects we cover.
https://greenteapress.com/wp/think-python-2e/

## What is programming?
--> When you write a program, you create a step by step recipe of what needs to be done to complete a task and when your computer executes the program it reads what you wrote and follows your instructions to the letter.

The recipe is written in a code called programming language. Programming languages are actually similar to humans spoken languages since they have a syntax and semantics.

## What is Automation?
--> Automation is the process of replacing a manual step with one that happens automatically

Take a traffic light, for example, which continuously regulates the flow of vehicles at an intersection. A traffic light requires a human intervention only when it needs repairs or maintenance. 

## Uses for Automation

Scripts can be used for automating specific tasks. Automation is used to replace a repetitive manual step with one that happens automatically. Humans are fallible. They can become tired, make mistakes, fail to follow instructions, be inconsistent in their job performance, and more. In contrast, automated processes complete instructions exactly as coded, in a consistent manner. They can run 24 hours a day, everyday, without tiring. For many tasks that are appropriate for automation, it can be more cost effective to use automation than human labor. 

### Appropriate uses for automation include:

* The automatic timing and regulation of traffic lights

* A repetitive task that is at high risk for human error

* Sending commands to a computer

* Detecting and removing duplicates of data

* Sending automated emails that are personalized by pulling individual names from a database and plugging them into the email 

* Updating a large number of file permissions

* Reporting on system data, like disk or memory usage

* Installing software

* Generating reports

* Deploying a file or a computer program to all computers on a company network

* Using a configuration management system to deploy software patches, after a human has designed the system

### Automation is not always an appropriate or complete solution

Automation cannot perform all human work. Tasks that call for human creativity, social connection, psychology, flexibility, ingenuity, evaluation, and/or complex analytic work are not good candidates for full automation. Sometimes automation can be used to perform one or more subtasks of a larger set of tasks – but – human intervention is required to complete the tasks. The following are some examples of tasks that cannot or should not be fully automated:

1. Items that require human evaluation and analytic skills:
* Designing a configuration management system
* Investigating and troubleshooting all end user problems
* Writing a computer program
* Building a new startup business
2. Items that require human creativity and/or an eye for aesthetic qualities:
* Designing an attractive webpage (AI can do this, but simple automation cannot)
* Wedding photography
* Haircuts and styling
3. Items that cannot be automated due to basic physics:
* Troubleshooting or repairing machines that cannot power on or boot up
4. Items that need human interaction, psychology, and/or evaluation skills:
* Interviewing and hiring new employees
* Customer service (chat bots cannot address every customer service need)
5. Items that should not be fully automated due to costs and safety:
* Grocery store checkout process, including bagging groceries
* Tasks that are less expensive to perform manually

## Artificial Intelligence

It is important to understand that basic automation is not the same as artificial intelligence. Automation is used to explicitly instruct a machine on how to perform a task. Artificial intelligence (AI) involves training a computing machine to perform more complex tasks through a process called machine learning. This process prepares the AI software to perform new tasks without a human needing to program explicit instructions for each task. Although AI is often used for automating human tasks, AI automation is much more complex than basic automation.

### Key Concepts
1. Limitations of Automation: Certain tasks that require human creativity, evaluation, or complex analysis cannot be fully automated, necessitating human involvement.
2. Artificial Intelligence: Artificial intelligence involves training machines to perform complex tasks through machine learning, differing from basic automation which follows explicit instructions.
3. Appropriate Uses of Automation: Automation is suitable for tasks that are repetitive, high-risk for human error, or require consistent execution, such as traffic light regulation and data reporting.
4. Automation: Automation refers to the use of technology to perform tasks without human intervention, replacing repetitive manual steps with automated processes.

## Getting Computers to Work for You
Imagine this scenario. Your company had a booth at a recent conference and has gathered a huge list of emails from people interested in learning more about your products. You want to send these people your monthly email newsletter, but some of the people on the list are already subscribed to receive it. So, how do you make sure everyone receives your newsletter without accidentally sending it to the same person twice? Well, you could manually check each email address one by one to make sure you only add new ones to the list. Sounds boring and inefficient, right? 

 You might accidentally miss new emails or add emails that were already there

So, what could you do instead? You could get the computer to do the work for you. You could write a program that checks for duplicates and then adds each new email to the list. Your computer will do exactly as it's told, no matter how many emails there are in the list. 

#### Quesation : Which of the following tasks do you think are good candidates for automation? Check all that apply.

1. Investigating reports that customers are having difficulty accessing your company's external website

2. Periodically scanning the disk usage of a group of fileservers

3. Installing software on laptops given to new employees when they are hired

4. Designing a configuration management system for deploying software patches

Ans - 2 & 3

# Study Guide: Introduction to Programming

## Key Terms

* Programming languages : Programming languages are similar to human spoken languages in that they both use syntax and semantics. Programming languages are used to write computer programs.  Some common programming languages include Python, Java, C, C++, C#, and R.

* Computer program - A computer program is a step-by-step list of instructions that a computer follows to reach an intended goal. It is important to be clear and precise about the actions a computer program is supposed to perform because computers will do exactly what they are instructed to do. Computer programs can be long, complex, and accomplish a variety of tasks. They are often developed by computer programmers and software engineers, but anyone can learn to create them. Computer programs may involve a structured development cycle. They can be written in a wide variety of programming languages, such as Python, Java, C++,  R, and more. The completed format of a program is often a single executable file.

* Automation - Automation is used to replace a repetitive manual step with one that happens automatically. 

* Output - Output is the end result of a task performed by a function or computer program. Output can include a single value, a report, entries into a database, and more. 

* Input - Input is information that is provided to a program by the end user. Input can be text, voice, images, biometrics, and more.   

* Functions - A function is a reusable block of code that performs a specific task.

* Variables - Variables are used to temporarily store changeable values in programming code.

# Python

* Python interpreter : The program that reads what's in the recipe and translates it into instructions for your computer to follow 

# A Note on Syntax and Code Blocks

When writing code, using correct syntax is critical. Even a small typo, like a missing parenthesis bracket or an extra comma, can cause a syntax error and the code won't execute at all. If your code results in an error or an exception, pay close attention to syntax and watch out for minor mistakes. A single wrong character could take hours to identify in long code so it is important to be mindful of syntax when writing code. 

#### Common syntax errors:

* Misspellings
* Incorrect indentations

1. Missing or incorrect key characters:
* Bracket types - ( curved ), [ square ], { curly }
* Quote types - "straight-double" or 'straight-single', “curly-double” or ‘curly-single’
* Block introduction characters, like colons - :

* Data type mismatches
* Missing, incorrectly used, or misplaced Python reserved words
* Using the wrong case (uppercase/lowercase) - Python is a case-sensitive language

# Why is Python relevant to IT?

You can use Python to calculate statistics, run your e-commerce site, process images, interact with web services, and do a whole host of other tasks. Python is perfect for automation. It lets you automate everyday tasks by writing simple scripts that are easy to understand and easy to maintain. That's why Python is the language of choice for lots of people working in IT support, system administration, and web development. 
it's also used in fast-growing areas of IT like machine learning or data analytics. 

## Introduction to python

Python is a general purpose programming language that is commonly used for scripting and automation, as well as to develop a wide variety of applications. Python is compatible with most operating systems, including Windows, Linux, and Mac OS, and is updated every few years. Python can also run on a variety of machines, such as servers, workstations, PCs, mobile devices, IoT, and more.

Python is widely used in the IT field, including IT support, system administration, web development, machine learning, data analytics, and more. Python can be used to calculate statistics, run your e-commerce site, process images, interact with web services, and do a whole host of other tasks. Python instructions resemble the English language

Python is:

* a general purpose scripting language;

* a popular language used to code a variety of applications;

* a frequently used tool for automation;

* a cross-platform compatible language;

* a beginner-friendly language.

# Key Terms

* Platform-specific / OS specific scripting language - Platform-specific scripting languages, like PowerShell (for Windows) and Bash (for Linux), are used by system administrators on those platforms. 

* Client-side scripting language - Client-side scripting languages, like JavaScript, are used mostly for web programming. The scripts are transferred from a web server to the end-user’s internet browser, then executed in the browser.

* Machine language - Machine language is the lowest-level computer language. It communicates directly with computing machines in binary code (ones and zeros). In binary code, one equals a pulse of electricity and zero equals no electrical pulse. Machine language instructions are made from translating languages like Python into complex patterns of ones and zeros. 

* Cross-platform language - Programming language that is compatible with one or more platforms / operating systems (e.g., Windows, Linux, Mac, iOS, Android).

* Object-oriented programming language - In object-oriented programming languages, most coding elements are considered to be objects with configurable properties. For example, a form field is an object that can be configured to accept only dates as input in the mm/dd/yy format, and can be configured to read from and write to a specific database. 

* Python interpreter - An interpreter is the program that reads and executes Python code by translating Python code into computer instructions.






