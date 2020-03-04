# Project Name:  SugarLabs



**Evaluating Person or Team**:
Karishma Maraj
kmaraj

---

## Project Data

1. Project description: <br>
SugarLabs is a "FLOSS" project that supports an open source environment known as Sugar. Sugar is a collaborative learning environment designed for children so they can interact with computers in an easy, flexible way. Sugar provides various interactive activities designed for children to engage with. 

1. Project website/homepage:
[SugarLabs Website](https://www.sugarlabs.org/)

1. Project repository:
[SugarLabs Repository](https://github.com/sugarlabs)


## License

1. What is the project's license? <br>
SugarLabs uses a GNU General Public License v3.0. 



## Code Base


1. What is the primary programming language in the project?
The primary programming language is Python.

1. What is the development environment? <br>
	You need to install a [live build](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#sugar-live-build) or install a [packaged Sugar environment](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#packaged-sugar).

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Yes on the README it has instructions and links on how to develop, build and install. Installation is very clear as it only requires one command which is specified on the README. I would say the instructions are clear for building, but just extensive. There are two ways to install if you want to contribute:

To make changes to Sugar, the toolkits, the demonstration activities, or to write new activities you need to install a [live build](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#sugar-live-build). To develop new activities without making changes to Sugar Desktop you need to install a [packaged Sugar environment](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#packaged-sugar).

For more detailed instructions on how to install Sugar you can find them [here](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md).


1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
As the documentation states Sugar relies on a lot of external modules and libraries. There are instructions [here](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md) on how to install them.


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
The code is located in the src folder and is organized and named in an intuitive way. The code itself is organized well but there are not a lot of comments to guide you. An example of this is the [activitychooser.py file](https://github.com/sugarlabs/sugar/blob/master/src/jarabe/desktop/activitychooser.py). From the name of the file you can gather what it does, but other than that there are no comments detailing what this code does. There are some comments throughout but it is not consistent. For example on line 170 there are comments explaining what the following for loop and if statement are looking for. It would be helpful if there were more comments like this, perhaps at the top of each function. I think however if you just took the time one with a base understanding of Python could understand this code. While there are only a few comments the names of the files and the functions are intuitive and the code is organized and separated appropriately (not just one large file).


1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
According to openhub SugarLabs has 4.13k lines of code.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
There are [tests](https://github.com/sugarlabs/sugar/tree/master/tests). Code contributors are expected to test their changes but not write tests for their newly added code from what I gather in their [contribution details](https://github.com/sugarlabs/sugar-docs/blob/master/src/contributing.md).

## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
While the code is not extensively commented, there is a lot of [documentation](https://github.com/sugarlabs/sugar-docs) on the code. However this mostly covers architecture, design, and how to contribute. I would say there is less documentation detailing the specifics of the lower level code.

1. Is there documentation about the design?  <br>
You can find documentation on the design [here](https://github.com/sugarlabs/sugar-docs). If you scroll there are two links detailing the Human Interface Guidelines (all the guidelines for the design) and the Sugar Iconify (ensure the right colors are used).

## Activity Level


1. How many commits have been made in the past week? <br>
	Zero commits have been made in the past week. 
1. When was the most recent commit? <br>
	The most recent commit was on February 8, 2020.
1. How many issues are currently open? <br>
	There are currently 41 issues open.
1. How long do issues stay open? <br>
	Issues stay open for an average of 4.2 days.
1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
	Not every issue (no matter how long they've been) open has sparked discussion. This [issue](https://github.com/sugarlabs/sugar/issues/904) for example has 19 comments on it, however this [issue](https://github.com/sugarlabs/sugar/issues/892) which has been opened longer has no comments on it. Most of the closed issues have comments on them, so I would say there is a risk of opening an issue and it getting ignored. 


1. Are issues tagged as easy, hard, for beginners, etc.? <br>
No issues are not tagged as such. They has the following labels: bug, design, errata, feature, needs SLOBS and needs work. 

1. How many issues were closed in the past six months? <br>
15 issues were closed in the past six months. 

1. Is there information about how many people are maintaining the project? <br>
According to their [website](https://www.sugarlabs.org/profiles/) there are 4 people who maintain different aspects of the project. Ibiam Chihurumnaya maintains the Words activity, Aneesh Dogra maintains the level tool, Bert Freudenberg maintains the Sugar version of Etoys, and Gabriel Lee maintains Sugar Labs services: jita, meeting, chat, activities, jabber. 

1. How many contributors has the project had in the past six months? <br>
This project has had 6 contributors in the past six months.

1. How many open pull requests are there? <br>
There are 16 open pull requests. 

1. Do pull requests remain un-answered for a long time? <br>
	Looking at the closed pull requests it takes an average of 3.33 days for them to be closed or merged. 

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
	If it is a small PR it gets merged quickly with no comments. However if it is larger or raises some issues or concerns they do not just get left open, but there are comments detailing what is wrong. For example before this [PR](https://github.com/sugarlabs/sugar/pull/897) was merged there was about 14 comments detailing what needed to be fixed before it could get merged. 

1. How many pull requests were opened within the past six months? <br>
10 pull requests were opened within the past six months. 

1. When was the last  pull request  merged? <br>
The last pull request merged was on January 22nd. 

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
Yes there is a [contributing document](https://github.com/sugarlabs/sugar-docs/blob/master/src/contributing.md). It is very easy to understand and the developers have even provided a checklist that one can follow. 


1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
The [CODE OF CONDUCT](https://github.com/sugarlabs/sugar-docs/blob/master/src/CODE_OF_CONDUCT.md) includes basic guidelines for how people should behave but does not include any clear consequences for people who violate the code of conduct. 

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
I would say people are generally constructive. If there is a question about how something works, I have seen responses thanking for the inquiry. Or if someone points out a potential issue, but it is not an issue I have seen comments that thank the person anyway for bringing it to the community's attention. 


1. Are people friendly in the issues, discussion forum, and chat? <br>
People are generally friendly throughout. I have not seen any rude or demeaning comments or conversations. The only thing is some issues just get overlooked, but other than that the ones that do generate responses are met with positive feedback. 


1. Do maintainers thank people for their contributions? <br>
Yes maintainers do thank people for their contributions. 

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
I have a Mac so the process was pretty long as I had to set up a virtual machine in order to install Sugar. There are also a lot of steps and reading through documentation if you are not too familiar with setting up on a virtual machine. The best way to get started is to read through this [page](https://github.com/sugarlabs/sugar-docs/blob/master/src/how-can-i-help.md). 

1. how long it take you? <br>
It honestly took me a while (2 hours) to actually install the software as there were many prerequesites and other software I had to download. 


1. did you need to install additional packages or libraries? <br>
I had to download Virtual Machine software in order to install Sugar.

1. were you able to build the code following the instructions? <br>
Yes but it took a while. I warn anyone working on a Mac that contributing to this project requires more steps regarding the installation piece. 

1. did you need to look for additional help in installing the environment? <br>
Yes I had to look up how to setup a virtual machine. 

1. any other comments? <br>
I reccomend reading the documentation specifically the beginning of this [page](https://github.com/sugarlabs/sugar-docs/blob/master/src/how-can-i-help.md) before starting to download anything. A lot of steps are independent as there are multiple ways to install the software. Reading will save you a lot of time. 



## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	Yes I do believe it would be possible to contribute to this project, especially if one knows Python. The code is organized clearly and there is a lot of documentation if you get lost. Also the community is generally responsive and provides really helpful feedback and constructive feedback if you raise an issue or reach out. Installation however is pretty entensive if you have a Mac, so I would reccomend if you are running on a linux because the process is much more straight forward as you do not have to use a virtual machine. 

1. Would you be interested in contributing to this particular project? <br>
	I am personally not interested in contributing to this project because Python is not my preferred language. I am also not especially drawn to the actual product. Also just judging off how long installation took I feel like contributing would also be very difficult. 




