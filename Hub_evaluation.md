# Project Name:  Hub 



**Evaluating Person or Team**:
<!-- list your first name and github user-name-->
Daniel Sing |  Pallof
---

## Project Data

1. Project description: <br>
<!--

What is the purpose of this project? What does the code do? What type of users
does it have?
-->
	Hub is a commandline tool that wrap 'git' in order to extend extra features/commands that make it easier to
	work with git. Basically command add ons and extra functionality on pre-existing commands.

1. Project website/homepage:

	https://github.com/github/hub
	https://hub.github.com/hub.1.html
	This is both the actual gitHub repository and the actual website 

1. Project repository:

	https://github.com/github/hub/tree/master/git
	They have multiple repositories, but this one looks like the foundation b/c ist is referring to Git itself and implementing the features here


## License

1. What is the project's license? <br>
<!--
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
-->
	They are using an MIT license. Very straight forward and simple



## Code Base


1. What is the primary programming language in the project?

The majority of the code is written in Go (49.3%) and Gherkin (39.6%)
Then there are smalls chunks of shell, ruby and makeFile/batchFile (4%)

1. What is the development environment? <br>
	<!--
	For example, is it Gnu C++ on Linux?
	Is it a Windows 10 application? Does one need to develop in a virtual machine?
	-->
	Does not specify the developement environment. But it says that in order to contribute you will need: Go 1.11+, Ruby 1.9+ with Bundler, git 1.8+, tmux & zsh(optional) for running shell completion tests 


1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>

	Hub has no dependencies so it is executable on all platforms. It is reccomended however to have at least git version 1.7.3. Installation instruction are found on the readme.md and are very detailed and walk you step by step on how to properly install Hub. 
	One dependency it has is 'Go Mod'.

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>

	No it does not, it can be as a standalone. Aside from the language and packages needed in order to contribute, it does not specify any external software modules needed.


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>

	Code seems somewhat straight forward, with function naming and how its coded. Little to no comments on a lot of the code, which can make it confusing as to what I'm reading. They should add more comments and documention on what they are writing

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>

	Cannot find this exact project on Openhub.net as 'Hub' is a very vauge name and hundreds of other groups have used the word 'Hub' in their naming configuration. This seems like a somewhat large project, with an estimate ok 2k+ lines of code.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
	There are a few tests, but I am not sure if these tests cover everything. There is a document in which it talks about writing tests and gives a brief guideline as how to write them.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>

	I do not think there is documentation on the code itself. But there is documentation on the features, and explains exactly what they are designed to do. This is potentially refer to the code, but I can't find documentation on the code.

1. Is there documentation about the design?  <br>

	Not so much the design but rather the features and excess add ons and describes what they are doing and how they should be used. 

## Activity Level


1. How many commits have been made in the past week? <br>

	2

1. When was the most recent commit? <br>

	8 hours ago on March 3rd, 2020

1. How many issues are currently open? <br>

	183 issues are currently open

1. How long do issues stay open? <br>
	<!--
	Take the five closed issues (they can be most recently closed or a sample distributed over time) and look at when each was first reported.
	Compute the number of days that each was open and take the average.
	-->
	Some issues take only 2-3 days while some issues took up to 6-7 days. On average the issues only stayed open around around 4-6 days

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>

	Yes, mainly by one contributor by the name of mislav.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
	They are not rather they are labeled by 'feature', 'bug', or 'docs'

1. How many issues were closed in the past six months? <br>
	Around 75-80 issues were closed in the past six months

1. Is there information about how many people are maintaining the project? <br>

	Only specifies the creator of the project. Does not specify anyone else. 
	Shows a list of who has the most commits to this project

1. How many contributors has the project had in the past six months? <br>

	211 contributors in the past 6 months

1. How many open pull requests are there? <br>

	There are 40 open pull requests

1. Do pull requests remain un-answered for a long time? <br>
	<!--
	Look at the closed pull requests to see how long they stayed open.
	Take the five closed pull requests  (they can be most recently closed or a sample distributed over time) and look at when each was first created.
	Compute the number of days that each was open and take the average.
	-->
	Some of them have remained open for almost two years.

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>

	The creator is quite active in all the pull requests however not all pull requests are pulled. Some requests cannot be completed, while others may have been forgotten

1. How many pull requests were opened within the past six months? <br>

	Around 30 pull requests were opened and merged within the past 6 months


1. When was the last  pull request  merged? <br>

	March 3rd, 2020

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>

	There is a contributing document. Fairly easy to understand, but I don't think it is very friendly towards newbies and begginners  trying to get their foot in the door. Talks about what to download and thing that you might consider adding and how to create/use tests.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>

	There is a code of conduct doc. If you don't follow the rules you will be removed and possibly permanently banned from the project. 

1. Do the maintainers respond helpfully to questions in issues? Are responses generally constructive? Read the issue conversations. <br>
	Yes, Mislav the creator actively discusses in all the pull requests and issues. 
	I do not understand all of the lingo, but it is a well facilitated discussion. Many other contributors also post links that might be helpful as additional reference resources.

1. Are people friendly in the issues, discussion forum, and chat? <br>
	I'm not sure if people are friendly, but people are respectful and do try to offer their opinions in a proper fashion. 

1. Do maintainers thank people for their contributions? <br>
	Most things seem quite bland, however there is the occasional 'Thank you' comment and post.

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

	There is no development environment. You only need to install the langauges.
	Go to ruby and Go and follow instructions on how to install there.

1. how involved was the process? <br>
	

1. how long it take you? <br>

1. did you need to install additional packages or libraries? <br>

1. were you able to build the code following the instructions? <br>

1. did you need to look for additional help in installing the environment? <br>

1. any other comments? <br>




## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	<!--
	Explain your position. Do NOT simply say 'yes or 'no'.
	-->
	In terms of documentation and possibly fixing some issues, yes but very minimally as I am I familiar with the language they use.
	In terms of Code contribution, No because I don't know Go or Gherkin and learning it would be a whole new task.

1. Would you be interested in contributing to this particular project? <br>
	<!--
	Explain why you would or would not be interested in contributing to this project. Do NOT simply say 'yes or 'no'.
	-->

	Not particularily as I am still new to gitHub, so trying to get all fancy with new add ons would just make it more confusing when I already only understand very little.
