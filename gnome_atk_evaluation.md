# Project Name:  GNOME Accessibility Toolkit



**Evaluating Person or Team**:
Julius nedjulius

---

## Project Data

1. Project description: <br>
<!--
What is the purpose of this project? What does the code do? What type of users
does it have?
-->
The project is aimed towards making computers more accessible for people with disabilities (this project is specifically for GNOME desktop environment). There are tools, such as screen magnifier for people with low vision, screen reader for the blind people, on-screen keyboard for people who cannot use standard keyboards, speech recognition which is usually used by people with mobility impairments, alternative input devices, keyboard enhancement utilities. The ATK is primarily used by people with disabilities.

1. Project website/homepage: https://wiki.gnome.org/Accessibility

1. Project repository: https://gitlab.gnome.org/GNOME/atk



## License

1. What is the project's license? <br>
GNU LIBRARY GENERAL PUBLIC LICENSE



## Code Base


1. What is the primary programming language in the project?
C

1. What is the development environment? <br>
It is not specified anywhere in the documentation, but I would guess that it is some Linux version, since the ATK is created specifically for GNOME environment. It uses Ninja and Meson for compilation.

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Building instructions, as well as download link are provided in the README file. There are no particular instructions on how to download the source code, there is just a link to it. Building instructions are very obscure and short. There are just three different ways to build the program. They are easy to find since they are in the README.md file. Overall, the README file is not very informative, contains just the very necessary information.

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
ATK has a GLib dependency, which is a toolkit for UI components. There are no clear instructions on how to install this dependency, it is installed during the build, or it can be installed manually by following the instructions on GTK.org website.

1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
I think someone with C knowledge might be able to understand the code just fine. The whole project is written in C only.

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
29.3K lines of code. I would say that it is a small to medium size project compared to React, for example, which has 235K lines of code.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
They do have tests, although the latest update to the test directory was made 8 months ago. There are no specific expectations listed anywhere in the project regarding tests, so I assume that the contributors are expected to do so since tests exist after all.



## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
There is commentary almost on each file that I saw, although a lot of the comments are just the commented out code lines, and the explanatory ones are usually 1-2 sentence long.

1. Is there documentation about the design?  <br>
No.


## Activity Level


1. How many commits have been made in the past week? <br>
0

1. When was the most recent commit? <br>
1 week ago

1. How many issues are currently open? <br>
4

1. How long do issues stay open? <br>
9(1+224+168+1+84)/5 = 5.6

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
Some issues have long discussions, and some have only a single message in them. The last message that was posted on any issue was 3 months ago, so I think they are quite dead at the moment.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
No, but there are tags that describes the problem of the issue (Documentation, Feature, etc.)

1. How many issues were closed in the past six months? <br>
3

1. Is there information about how many people are maintaining the project? <br>
There is a document called contributors, in which there are only four people. There are 287 official maintainers (members section).

1. How many contributors has the project had in the past six months? <br>
9

1. How many open pull requests are there? <br>
0

1. Do pull requests remain un-answered for a long time? <br>
(1 + 11 + 1 + 1 + 2)/5 = 3.2

1. Read the conversations from some open and some closed pull requests. Is there active discussion on the pull requests? <br>
Yes, there is some discussion, although usually it's just some maintainers insights and advices.

1. How many pull requests were opened within the past six months? <br>
17

1. When was the last  pull request  merged? <br>
1 week ago

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
No

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
No, although I believe that GNOME code of conduct applies to this project too. GNOME's code of conduct is very extensive and large. It does have consequences for acts that violate it, although it is not mentioned what. People can report misbehavior to some internal GNOME's committe which then will decide on what actions to take.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Yes, the maintainers seem to be friendly and helpful. They usually give examples, explain the issues and just in general are kind of polite.

1. Are people friendly in the issues, discussion forum, and chat? <br>
There are different people, but in general they are friendly. Some are more formal, and some are seemingly more friendly.

1. Do maintainers thank people for their contributions? <br>
Sometimes, but not always.


## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
It was quite easy and I didn't have to do much, although two out of three provided build methods did not work for me.

1. how long it take you? <br>
Around 5 minutes.

1. did you need to install additional packages or libraries? <br>
No.

1. were you able to build the code following the instructions? <br>
Yes.

1. did you need to look for additional help in installing the environment? <br>
No.

1. any other comments? <br>
The build was successful with only one of the provided build methods (meson), it didn't work with the other.




## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
I think yes, because the community is not that big, and the project size is not enormous. It seemed that each toolkit had different C files, so it was easy to contribute to different parts of the whole project. I also think that, since it has such poor documentation, someone could easily contribute to that.

1. Would you be interested in contributing to this particular project? <br>
I don't think I would, because personally this project has nothing to do with my interests. Even though this project has a very meaningful aspiration (improve the computer experience to people with disabilities), I know almost nothing about GNOME environment for which this tool is developed, and I have no idea how accessibility tools work. It would be interesting to learn more about that, but I don't feel like I want to dedicade any of my time to such a project. I would rather work on something that has more meaning and usefulness to me.
