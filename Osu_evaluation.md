# Project Name:  Osu


**Evaluating Person or Team**:
Noah Brumfield

## Project Data

1. Project description: <br>
"Rhythm is just a *click* away!"
Mouse and keyboard based rhythm game.

1. Project website/homepage: 	https://osu.ppy.sh/home
1. Project repository:	https://github.com/ppy/osu


## License

1. What is the project's license? <br>
MIT
(Which is surprising, because the game still has an "owner".  Guess its because it's online,
maintained by the owner)


## Code Base


1. What is the primary programming language in the project?
c#
1. What is the development environment? <br>
Different depending on the os being used and the version being worked on.  For all, the .NET Core 3.1 SDK is required.
For the mobile version, xamarin is required.  On linux, A system wide FFmpeg installation is required for
video decoding.

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Theres some light instructions.  Not a lot on the environment, but there are build instructions for their
recommended IDE's.
1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
No, nothing outsided the listed envorinment requirements.
1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
Somewhat?  For context, this prject only went open source recently, and its somewhat easy to tell as
some of the code seems like itd be very well written and easily understood if youre the one who wrote it.
As the more integral parts call from smaller and smaller helper classes its hard to tell what each does.
Its pretty interesting to see how they coded out some of the game mechanics, though.
1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
Its quite big, plenty of contributors, lots of code, and a VERY strong user base that always wants new features
1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
There is a bank of existing types of tests for different scanarios.  (Visual, Scoring, Gameplay) that
can be used separately from the rest, I believe making it so that new contributors do not have to use
their own test, jsut make sure it works with the current tests.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
A small amount.  Seem more like "notes to self" from the creator than true documentation.
1. Is there documentation about the design?  <br>
No

## Activity Level


1. How many commits have been made in the past week? <br>
About 200
1. When was the most recent commit? <br>
10 AM march 6th, 8 hours before this writing.
1. How many issues are currently open? <br>
821
1. How long do issues stay open? <br>
	Usually closed within the week

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
There is.  Sometimes its a bit short, or the creators shut it down quick as they already made a decision on that issue.
Mostly short, and the creators have their ideas outlined already.
1. Are issues tagged as easy, hard, for beginners, etc.? <br>
There are a few tagged by difficulty, but they seem like they were made from one attempt to do so and left there forever.
1. How many issues were closed in the past six months? <br>
About 500
1. Is there information about how many people are maintaining the project? <br>
160 contributors
1. How many contributors has the project had in the past six months? <br>
About 35
1. How many open pull requests are there? <br>
81
1. Do pull requests remain un-answered for a long time? <br>
Many larger feature implementations can take weeks back and forth, but most are just a few days
1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
Yes, similar to the issues, creators tell it how it is.
1. How many pull requests were opened within the past six months? <br>
About 400
1. When was the last  pull request  merged? <br>
1 day ago, march 5, 2020
## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
None
1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
No code
1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Again, the creators can be short with people in telling the the decisions theyve made.
1. Are people friendly in the issues, discussion forum, and chat? <br>
Not necessarily friendly but not unfriendly either.
1. Do maintainers thank people for their contributions? <br>
No, not usually

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
Super simple
1. how long it take you? <br>
About A minute
1. did you need to install additional packages or libraries? <br>
Just the .NET CORE SDK
1. were you able to build the code following the instructions? <br>
Small problem here.  In their envoronment section they had their recommended IDE's, which, being recommended
I assumed were optional, but their build instructions have them specifically in mind.
1. did you need to look for additional help in installing the environment? <br>
Not for .NET
1. any other comments? <br>
A little sparse on details, not super newbie friendly



## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	Unfortunately not.  It seems VERY fast paced, stresses me out.

1. Would you be interested in contributing to this particular project? <br>
	I don't think i'm too interested in contributing, but I wouldn't mind just looking at the code.
  Seems like a good way to pick their brain on how they built the game from the ground up.
