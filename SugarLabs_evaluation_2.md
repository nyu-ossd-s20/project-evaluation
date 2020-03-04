# Project Name:  SugarLabs   



**Evaluating Person or Team**:
Barkin Simsek

---

## Project Data

1. Project description: <br>
<!--
What is the purpose of this project? What does the code do? What type of users
does it have?
-->
Sugar Labs has been developing the "SUGAR", which is an award winning learning platform for children that promotes collaborative learning. The code can be run in various ways and the code creates the user interface and the interactive games. The platform is targeted for children.



1. Project website/homepage: [SugarLabs Website](https://sugarlabs.org/)

1. Project repository: [SugarLabs GitHub Organization](https://github.com/sugarlabs) They have multiple repositories under this GitHub organization.



## License

1. What is the project's license? <br>
GNU General Public License v3.0


## Code Base


1. What is the primary programming language in the project? <br>
Python is the primary programming language in the SugarLabs project.


1. What is the development environment? <br>
There are three options. They suggest using the [Sugar Live Build](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#sugar-live-build) for testing or changing Sugar or a Sugar activity. The live build boots up from a usb stick. Additionally, they suggest using [Packaged Sugar environment](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#packaged-sugar) for for writing or changing a Sugar activity. The Packaged Sugar environment requires using a Linux system to install. Finally, they suggest using the [native Sugar buid](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#native-sugar) for packing sugar.


1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Yes, it is very easy to find the instructions. They are on the readme page and they are clearly marked. It is easy to follow and install as well. Users just need to run ```sudo apt install sucrose``` on Ubuntu/Debian systems and ```sudo dnf groupinstall sugar-desktop``` Fedora systems.


1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
Yes, it depends on many other libraries however it is clearly stated that all dependecies are installed automatically by the installer. Only the native Sugar build option requires manual install for dependencies. However, that step is required for packaging Sugar and probably mostly the core developers use it to release a new version of Sugar.


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
I have check three python files and there are no comments at all in the code. That being said, they have used long and self explanatory variable names and I think it makes new developer's life easy. For exapmle, a variable is named "destination_path" instead of something like "d_path" or even "dp", which would have been very difficult to understand.


1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
According to [OpenHub](https://www.openhub.net/p?ref=homepage&query=sugar), 58.9K lines of code in this project. I think it is a big project because they even have a fully working bootable live environment it is possible to install it throught the aptitude package manager.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
Yes, they have tests. They frequently mention that they encourage testing the code before sending a pull request. However, they don't clearly mention if contributors are required to write tests.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
As I have mentioned above, the code is not commented but the variable and fuctions are selfexlanatory. Also, their seperate contributors & developers documentation is very extensive and be found [here](https://github.com/sugarlabs/sugar-docs).

1. Is there documentation about the design?  <br>
Yes, there is a section dedicated to design in the documentation. [Human Interface Guidelines](https://github.com/sugarlabs/sugar-docs/blob/master/src/HIG.md) and [Sugar Iconify](https://github.com/sugarlabs/sugar-docs/blob/master/src/sugar-iconify.md) are the two main titles under this section.

## Activity Level


1. How many commits have been made in the past week? <br>
This number doesn't represent the actual number of contributions because they have a seperate repository for every activitiy and they have more than 50 repositeries. In their main repository, called "Sugar", one commit have been made in the past week.

1. When was the most recent commit? <br>
March 3, 2020

1. How many issues are currently open? <br>
39

1. How long do issues stay open? <br>
29 days on average based on my random selection

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
Usually there are only a few comments. Some issues got up to 20 comments but it is not common.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
No, no of them are tagged with any tag.

1. How many issues were closed in the past six months? <br>
20

1. Is there information about how many people are maintaining the project? <br>
They have 23 people maintaining the different parts of the project.

1. How many contributors has the project had in the past six months? <br>
6

1. How many open pull requests are there? <br>
15

1. Do pull requests remain un-answered for a long time? <br>
128 days on average based on my random selection

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
They do have discussions on the pull requests. People usually list their suggestions and their comments as a bullet point list. However, they don't have discussions if the pull request is making a minor change that passes all of the tests.

1. How many pull requests were opened within the past six months? <br>
11

1. When was the last  pull request  merged? <br>
March 3, 2020

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>

1. Are people friendly in the issues, discussion forum, and chat? <br>

1. Do maintainers thank people for their contributions? <br>


## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

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

1. Would you be interested in contributing to this particular project? <br>
	<!--
	Explain why you would or would not be interested in contributing to this project. Do NOT simply say 'yes or 'no'.
	-->
