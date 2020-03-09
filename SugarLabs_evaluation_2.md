# Project Name:  SugarLabs   



**Evaluating Person or Team**:
Barkin Simsek

---

## Project Data

1. Project description: <br>
Sugar Labs has been developing the "SUGAR", which is an award-winning learning platform for children that promotes collaborative learning. The code can be run in various ways, and the code creates the user interface and interactive games. The platform is targeted for children.



1. Project website/homepage: [SugarLabs Website](https://sugarlabs.org/)

1. Project repository: [SugarLabs GitHub Organization](https://github.com/sugarlabs) They have multiple repositories under this GitHub organization.



## License

1. What is the project's license? <br>
GNU General Public License v3.0


## Code Base


1. What is the primary programming language in the project? <br>
Python is the primary programming language in the SugarLabs project.


1. What is the development environment? <br>
There are three options. They suggest using the [Sugar Live Build](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#sugar-live-build) for testing or changing Sugar or a Sugar activity. The live build boots up from a USB stick. Additionally, they suggest using [Packaged Sugar environment](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#packaged-sugar) for writing or changing a Sugar activity. The Packaged Sugar environment requires using a Linux system to install. Finally, they suggest using the [native Sugar buid](https://github.com/sugarlabs/sugar/blob/master/docs/development-environment.md#native-sugar) for packing Sugar.


1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Yes, it is very easy to find the instructions. They are on the readme page, and they are clearly marked. It is easy to follow and install, as well. Users just need to run ```sudo apt install sucrose``` on Ubuntu/Debian systems and ```sudo dnf groupinstall sugar-desktop``` Fedora systems.


1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
Yes, it depends on many other libraries; however it is clearly stated that all dependencies are installed automatically by the installer. Only the native Sugar build option requires manual install for dependencies. However, that step is required for packaging Sugar, and probably mostly, the core developers use it to release a new version of Sugar.


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
I have check three python files, and there are no comments at all in the code. That being said, they have used long, and self-explanatory variable names, and I think it makes the new developer's life easy. For example, a variable is named "destination_path" instead of something like "d_path" or even "dp", which would have been very difficult to understand.


1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
According to [OpenHub](https://www.openhub.net/p?ref=homepage&query=sugar), 58.9K lines of code in this project. I think it is a big project because they even have a fully working bootable live environment it is possible to install it through the aptitude package manager.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
Yes, they have tests. They frequently mention that they encourage testing the code before sending a pull request. However, they don't clearly mention if contributors are required to write tests.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
As I have mentioned above, the code is not commented, but the variable and functions are self-explanatory. Also, their separate contributors & developers documentation is very extensive and be found [here](https://github.com/sugarlabs/sugar-docs).

1. Is there documentation about the design?  <br>
Yes, there is a section dedicated to design in the documentation. [Human Interface Guidelines](https://github.com/sugarlabs/sugar-docs/blob/master/src/HIG.md) and [Sugar Iconify](https://github.com/sugarlabs/sugar-docs/blob/master/src/sugar-iconify.md) are the two main titles under this section.

## Activity Level


1. How many commits have been made in the past week? <br>
This number doesn't represent the actual number of contributions because they have a separate repository for every activity, and they have more than 50 repositories. In their main repository, called "Sugar", one commit has been made in the past week.

1. When was the most recent commit? <br>
March 3, 2020

1. How many issues are currently open? <br>
39

1. How long do issues stay open? <br>
29 days on average based on my random selection

1. Read the conversations from some open and some closed issues. Is there an active discussion on the issues? <br>
Usually, there are only a few comments. Some issues got up to 20 comments, but it is not common.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
No, no of them are tagged with any tag.

1. How many issues were closed in the past six months? <br>
20

1. Is there information about how many people are maintaining the project? <br>
They have 5 people maintaining the different parts of the project. They are mentioned in the MAINTAINERS file in the repository.

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
Yes, there is a CONTRIBUTING file. It is very clear and divided into sections. They have even provided checklists for pull requests that contributors can make sure they completed necessary tests.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
Yes, there is a CODE OF CONDUCT file, but the consequences of violations are not mentioned. Instead, it says that The Oversight Board will decide on the consequences.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Yes, it seems like they do spend time on explaining reasons in detail in their responses. They ask a lot of questions to understand the exact situation and the problem. I think their approach leads to constructive responses.

1. Are people friendly in the issues, discussion forum, and chat? <br>
So far, I haven't seen anyone being rude. It looks like people are polite to each other, and they make sure that their ideas are conveyed.


1. Do maintainers thank people for their contributions? <br>
Almost all maintainer responses start with "thanks".

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
As I have mentioned, there are multiple projects within the project. All "apps" within the SUGAR environment has its own procedures. I decided to proceed with the main Sugar Desktop environment that all of these apps run on. I just downloaded the lived build image file and ran it in the VirtualBox. No installation is required at all.

1. how long it take you? <br>
5 minutes

1. did you need to install additional packages or libraries? <br>
No, because the live build already contains all dependencies and the development environment itself

1. were you able to build the code following the instructions? <br>
Yes

1. did you need to look for additional help in installing the environment? <br>
No, I didn't, but I think there should be more explanation in the documentation. They just assumed that everyone already knows about virtual machines.

1. any other comments? <br>
Having the live build makes everything super easy to setup. I am glad that they have that option.



## Summary
1. Do you think this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
Yes, I think this is a good project to contribute because there are many options to choose from. There are more than 50 smaller applications that run inside of the desktop environment, and any of these projects are potential projects to contribute.

1. Would you be interested in contributing to this particular project? <br>
No, I wouldn't be interested in contributing to this project because it doesn't seem to have an established userbase. It also looks like a dying project. The contributions per month are very very low at this point, and the activities they offer can be reached via the internet very easily. I think this project was more relevant when it was started 13 years ago. I think they failed to keep up with the time.
