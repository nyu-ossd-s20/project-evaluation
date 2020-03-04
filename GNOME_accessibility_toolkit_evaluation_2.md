# Project Name: GNOME Accessibility Toolkit   



**Evaluating Person or Team**: Charlie Thomas - https://github.com/Charleshthomasiii
<!-- list your first name and github user-name-->

---

## Project Data

1. Project description: <br><br>

The GNOME Accessibility Toolkit, or ATK, provides 'the set of accessibility interfaces that are implemented by other toolkits and applications. Using the ATK interfaces, accessibility tools have full access to view and control running applications.' For example, if I am creating a graphical application with GTK, it is exposed to things tools like braille readers and screen readers because GTK implements ATK. https://developer.gnome.org/accessibility-devel-guide/stable/figures/gaa.jpg.en
<!--
What is the purpose of this project? What does the code do? What type of users
does it have?
-->

1. Project website/homepage: https://developer.gnome.org/atk/

1. Project repository: https://gitlab.gnome.org/GNOME/atk and https://github.com/GNOME/atk The github repo is a mirror of the gitlab. All pull requests happen on gitlab.



## License

1. What is the project's license? <br><br>
GNU LIBRARY GENERAL PUBLIC LICENSE Version 2
<!--
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
-->



## Code Base


1. What is the primary programming language in the project? <br><br>
C

1. What is the development environment? <br> <br>
It requires ninja and meson to build. If you were to develop using ATK or make changes to ATK, you would need to use gnome desktop environment to test or at least run a vm.
	<!--
	For example, is it Gnu C++ on Linux?
	Is it a Windows 10 application? Does one need to develop in a virtual machine?
	-->

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br><br>
The process for setting up the environment is described in the repo README: 
	1. Clone or download the source code.
	2. Install meson and ninja using a package manager. These are both build systems.
	3. Call $ meson build
    		$ ninja -C build
    		$ ninja -C build install<br>
It wasn't particularly hard to follow, but I had to hunt down some dependencies in StackOverflow.
	
	
1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
You have to have meson and ninja installed. You also have to have python and pip installed in order to install meson. I needed to install gobject-introspection, libgtk2.0-dev, and glib on ubuntu 18.04. There aren't really instructions on how to install these, but it should be easy to figure it out.



1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br><br>
No, I don't think the code is particularly hard to understand. ATK is mostly used for GTK applications, so I would imagine that users would have little trouble looking through the source code if needed. 

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br><br>
No, I wouldn't consider this a big project for two reasons. Firstly, it's very self contained.  It's dissimilar to lots of newer open source projects in that it doesn't use microservice architecture. It's consists of c header and source files, translations, docs, and tests. That's it. Secondly, there's not much code. Overall, I would say this is not particularly complex nor quickly changing. 

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br><br>
Yes, there are tests. There's no policy on how to add tests to the code. It seems that there are few changes to the project and few contributers, so having a strict testing policy isn't necessarily needed.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br><br>
Yes. The documentation page https://developer.gnome.org/atk/ is built from the in-code documentation, so both the code documentation and the doc page are clear and up to date.

1. Is there documentation about the design?  <br><br>
No, but it's mostly self-explanatory.


## Activity Level


1. How many commits have been made in the past week? <br><br>
None

1. When was the most recent commit? <br><br>
February 20th

1. How many issues are currently open? <br><br>
4
1. How long do issues stay open? <br><br>

I'm not sure that taking the average length of time an issue is open is a valuable metric for this repository. However, the average time between reporting and closing an issue of the last five issues is 87 days. The two most recent issues were opened and closed on the same day, two lasted 57 days, and one lasted 321 days. There seems to be a huge variability depending on the scope.
	<!--
	Take the five closed issues (they can be most recently closed or a sample distributed over time) and look at when each was first reported.
	Compute the number of days that each was open and take the average.
	-->

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br><br>
Yes. There is active discussion on every issue that's posted, mostly from Alejandro Piñeiro, one of the maintainers.


1. Are issues tagged as easy, hard, for beginners, etc.? <br><br>
None of them are tagged for difficulty. The nature of this repo wouldn't need nor want beginner developers working on it.

1. How many issues were closed in the past six months? <br><br>
12


1. Is there information about how many people are maintaining the project? <br><br>
There's a maintainer file with information for 4 contacts.

1. How many contributors has the project had in the past six months? <br><br>
The contributors page is broken on gitlab, so I can't figure this one out. https://gitlab.gnome.org/GNOME/atk/-/graphs/master

1. How many open pull requests are there? <br><br>
None.

1. Do pull requests remain un-answered for a long time? <br><br>
The average number of days a pull request stayed open is 6.8. However, this is similar to the _issues_ average days problem. Three pull requests lasted 0 days, one lasted 1 day, and one lasted 33 days.
	<!--
	Look at the closed pull requests to see how long they stayed open.
	Take the five closed pull requests  (they can be most recently closed or a sample distributed over time) and look at when each was first created.
	Compute the number of days that each was open and take the average.
	-->

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br><br>
Yes, the general format for each pull request is the same. Someone who uses the software finds an issue and fixes it, then Alejandro responds and usually accepts the change.

1. How many pull requests were opened within the past six months? <br><br>
Nineteen merge requests were opened in the past six months.

1. When was the last  pull request  merged? <br><br>
A week ago.
## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br><br>
There is no contributing document. I assume it follows the guidelines laid out in the gnome project contributions page. https://www.gnome.org/get-involved/

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br><br>
There is no CODE OF CONDUCT document. Again, I assume it follows the guidelines in here. https://www.gnome.org/get-involved/.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br><br>
Yes, Alejandro seems pretty nice and also constructive in feedback. 

1. Are people friendly in the issues, discussion forum, and chat? <br><br>
Yes, there doesn't seem to be any toxicity. Alejandro is also apologetic when he's late to respond to merge requests.


1. Do maintainers thank people for their contributions? <br><br>
Alejandro thanks people for their contributions.

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br><br>
It wasn't super involved. I had to download the source, get Ninja, Meson, gobject-introspection, libgtk2.0-dev, and glib, and then build.

1. how long it take you? <br><br>
About thirty minutes.

1. did you need to install additional packages or libraries? <br><br>
Yes, see above.

1. were you able to build the code following the instructions? <br><br>
Yes, they were pretty straightforward.

1. did you need to look for additional help in installing the environment? <br><br>
I had to search through a StackOverflow page to find a solution to a dependency problem.

1. any other comments? <br><br>
Overall, this seems like a well maintained project with a limited scope. Contributors seem to be experienced developers who use the software and spot errors and then make changes.




## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br><br>
I think it's possible to contribute, but I would highly recommend against it. There are essentially no features that need to be implemented, and it seems to be on maintenence mode.
	<!--
	Explain your position. Do NOT simply say 'yes or 'no'.
	-->

1. Would you be interested in contributing to this particular project? <br><br>
No. While I find accessibility interesting and important, I couldn't make any meaningful contribution. I would have to start developing a GTK application, use ATK, and then attempt to add features or find bugs.
	<!--
	Explain why you would or would not be interested in contributing to this project. Do NOT simply say 'yes or 'no'.
	-->
