# Project Name:  Godot Engine



**Evaluating Person or Team**:
Nishant (@niniack)

---

## Project Data

1. Project description: <br>

	Godot Engine is a "cross-platform game engine to create 2D and 3D games from a unified interface." It includes common tools for game creation so that users can focus develop their game without having to rebuild these tools. Users are those that would be interested in developing a 2D or 3D game that can be exported for multiple platforms. 

1. Project website/homepage: https://godotengine.org/

1. Project repository: https://github.com/godotengine/godot



## License

1. What is the project's license? <br>
	MIT License


## Code Base


1. What is the primary programming language in the project?
	The project is almost exclusively written in C++ (92%), with a little bit of Java, C#, Python (roughly 1-2% each)

1. What is the development environment? <br>

	Godot uses SCons, which is an "Open Source software construction tool"

	This means Godot can be compiled in several different platforms, with SCons and Python 2.7+/3.5+ installed.  
	For Windows: Visual Studio OR MinGW-w64 with GCC
	For Linux: GCC or Clang 
	For OSX: Xcode
	For Android: Android SDK, Android NDK r17+, and JDK 8
	For iOS: Xcod 10.0, iOS SDK

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>

	Yes, all of the instructions, including a justification for using SCons, for compilation can be found at https://docs.godotengine.org/en/latest/development/compiling/index.html. Instructions provide shell code snippets and screenshots as a supplement.

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>

	Yes, the project depends on additional modules, which are accounted for in the installation instructions.


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>

	The code is not necessarily easy to understand off the bat, but it seems that with some dedicated reading and understanding the philoshopy of the design, it may be possible to eventually understand. The code is very well organized and unsurprisingly follows good practices (for example splitting header/implementation)

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>

	Yes, it is a hughe project. It has 1.2 million lines of code 

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>

	Yes, there is a tests directory. However, the contributing.md file does not make any mention of adding tests.

## Code and Design Documentation

1. Is there clear documentation in the code itself? <br>

	At the top of each file there is a preamble that gives the file name and license, but there are no comments in the code itself.

1. Is there documentation about the design?  <br>

	Yes, the "Read the Docs" for Godot has a dedicated section called [Godot's design philosophy](https://docs.godotengine.org/en/stable/getting_started/step_by_step/godot_design_philosophy.html)


## Activity Level


1. How many commits have been made in the past week? <br>

	There have been a 164 commits since after Feb 25, 2020

1. When was the most recent commit? <br>

	The latest commit was merging a pull request which aimed to fix an exception thrown when using the touch screen

1. How many issues are currently open? <br>

	There are 5,539 issues still open

1. How long do issues stay open? <br>
	
	Random sample (days remained open): 0, 1, 22, 3, 0

	An average of 5 days

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
	
	Yeah there is heavy discussion in some of the issues with community members asking for elaboration on certain issues or explaining how certain bugs are not actually bugs but expected behavior.


1. Are issues tagged as easy, hard, for beginners, etc.? <br>

	No issues are not tagged by difficulty, but all of the issues are tagged without missing a beat. Most issues fall under multiple tags and it all seems very detailed. Interestingly, there is a label named "junior job", perhpas implying the difficulty level of the issue

1. How many issues were closed in the past six months? <br>
	
	[2,289 issues](https://github.com/godotengine/godot/issues?utf8=%E2%9C%93&q=is%3Aissue+closed%3A%3E%3D2019-09-03)

1. Is there information about how many people are maintaining the project? <br>
	The contributors section on the repository says 1,089 contributors of which 75 have contributed in the past month.


1. How many contributors has the project had in the past six months? <br>
	
	52 contributors


1. How many open pull requests are there? <br>
	
	622 open; 13,551 closed

1. Do pull requests remain un-answered for a long time? <br>
	
	No, they tend to be answered within the same day

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>

	Usually not, I assume that is because they are heavily discussed in the issues section beforehand.

1. How many pull requests were opened within the past six months? <br>

	[447 open; 1,871 closed](https://github.com/godotengine/godot/pulls?utf8=%E2%9C%93&q=sort%3Acreated-desc+created%3A%3E%3D2019-09-02+)

1. When was the last  pull request  merged? <br>
	
	17 hours ago from time of writing


## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>

	Yes, it is a very thorough set of expectations with special instructions for new feature proposals.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
	
	Yes, there is a Code of Conduct. It states that parties will "excluded from participating in the community if you insult, demean, harass, intentionally make others uncomfortable by any means, or participate in any other hateful conduct, either publicly or privately."



1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
	
	Yes, responses are conducive to conversation and resolution IF the issue posted is well documented and detailed. Otherwise, members tend to bluntly (but not rudely) tell the poster to provide more detail or look at a duplicate


1. Are people friendly in the issues, discussion forum, and chat? <br>
	
	Not necessarily heart-warmingly friendly, but civil and helpful.

1. Do maintainers thank people for their contributions? <br>

	Yes.

	
## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. How involved was the process? <br>
	
	I was able to download the binary for my operating system and execute the application 

1. How long it take you? <br>

	Less than a minute

1. Did you need to install additional packages or libraries? <br>

	No.

1. Were you able to build the code following the instructions? <br>
	
	There are instructions for buidling from source (although it is not necessary). I wasn't able to build the code immediately, I ran into issues with lvm2, which is a system for managing filesystems.

	Otherwise, yes, although, it took a while to build from source code and was heavy on my computing resources.

1. Did you need to look for additional help in installing the environment? <br>
	I had to look up instructions how to resolve lvm2 package error issues.

1. Any other comments? <br>


## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	
	No, I think, it is an incredibly large project that would require quite a bit of knowledge of game design. Plus, there is likely quite a bit of overhead in testing any code contributions. 

1. Would you be interested in contributing to this particular project? <br>
	
	No, I have little to no interest and non-existent knowledge of game design. I feel that it would be a very frustrating experience to try to contribute to the project within the time period of the class as most of it would be spent learning the ins and outs of the project, leaving very little time for any contributions, even if they are primarily documentation contributions.
