# Project Name:  Hub  



**Evaluating Person or Team**:
Noah Brumfield
electavire
## Project Data

1. Project description: <br>
"hub is an extension to command-line git that helps you do everyday GitHub tasks without ever leaving the terminal."

Makes standard github features like issue tracking and project browsing much easier from the terminal

1. Project website/homepage:
https://hub.github.com/

1. Project repository:
https://github.com/github/hub

## License

1. What is the project's license? <br>
MIT



## Code Base


1. What is the primary programming language in the project?
About 50% Go, 40% Gherkin (Whatever that is), and small amounts of various others
1. What is the development environment? <br>
Actually has no dependencies and is available for multiple environments, with different install packages
for each.  As its meant to wrap git though, youre supposed to have that first

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
There is an install section with multiple different packages for different environments (Though its clear
its most maintained for MacOs and Linux, the others are available with executables maintained by the community)
1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
Not really.  Again it can even be installed without git but that wouldn't make any sense
1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
Well for one it seems well documented and organized (looked at clone.go)  The overall structure doesn't seem
incredibly difficult, as it sort of just wraps around existing commands from github and makes them usable in new ways, but it'd be a little difficult to jump right in myself because theres a fair amount I'm not familiar with that it uses a fair amount of, like regular expressions, web access, and the fact that its go
1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
The size seems pretty substantial.  Clone.go that I checked above was about 150 lines on its own, and there are about 50 or so files for similar commands, meaning its above around 5000 lines of code in just the "commands" folder.
1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
There are multiple test files in some directories but not all, depending I suppose on how there used.  Its a little hard to tell the rhyme or reason on this, but Ill get into that in documentation.  I believe the existing tests are intended to make sure new code does not break anything.
In the contributing document there is a guid on writing tests, which makes me think youre intended to make some.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
Theres occasionally a brief comment here or there, and some have more than others.  I wasn't sure so I checked contributing and theres not much there in terms of style guidance.
From there I'd say its fair to say its person to person.
1. Is there documentation about the design?  <br>
Maybe I'm blind but I couldn't see any.  Theres definitely a system they have for adding new
features that everyone's using but I think youre expected to just see how it works from whats
already there.

## Activity Level


1. How many commits have been made in the past week? <br>
None
1. When was the most recent commit? <br>
February 19th
1. How many issues are currently open? <br>
185
1. How long do issues stay open? <br>
Most of the issues reported are minor, and those are closed by one of the main contributors
Mislav often within the day, but usually at least by the end of the week

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
Most of the issues conversations don't go particularly long.  Often just "open, response, solved, closed"
1. Are issues tagged as easy, hard, for beginners, etc.? <br>
No difficulty tags.  Only type tags
1. How many issues were closed in the past six months? <br>
About 100
1. Is there information about how many people are maintaining the project? <br>
Had difficulty telling...
1. How many contributors has the project had in the past six months? <br>
Couldnt tell
1. How many open pull requests are there? <br>
42
1. Do pull requests remain un-answered for a long time? <br>
No, Mislav again comments on them pretty quickly
1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
Yes, theres usually an intial caveat or change needed before it makes it in
1. How many pull requests were opened within the past six months? <br>
about 75
1. When was the last  pull request  merged? <br>
14 days ago/ February 16th
## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
Its a little short.  Relatively clear on what makes a good feature but not much else.
1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
It basically said violations will be reported to the team, and theyll figure it out as they go
1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Yes, Maintainers give clear instructions, directions and are not rude in doing so. (Even when its deserved
  Theres plenty of completely irrelevant issues, im guessing because "Hub" is such a non-descript name.  My favorite was someone asking how to play Pokemon Sword and Shield, twice)
1. Are people friendly in the issues, discussion forum, and chat? <br>
Yes! A nice enough and friendly atmosphere.
1. Do maintainers thank people for their contributions? <br>
Yes.  As a quick note, it seems the project is pretty much solely lead by one person, mislav
## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
It shouldnt normally be that hard, details to follow
1. how long it take you? <br>
About a Minute
1. did you need to install additional packages or libraries? <br>
Can use a command line package manager, multiple options to pick from, or download an
executable directly
1. were you able to build the code following the instructions? <br>
... no.  Running the executable failed immediately.
1. did you need to look for additional help in installing the environment? <br>
Were I to try more Id say yes, but I have no idea what the problem could really be.
1. any other comments? <br>
The windows install seems to be managed separately, so its likely MacOs and Linux versions are better
maintained.



## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	Not even a little! I don't know go, I'm pretty terrible with the command line myself,
  and I'm still a little iffy with using the standard GitHub commands, let alone modifying them

1. Would you be interested in contributing to this particular project? <br>
	Not really.  I know its like a "Comp Sci Sin" to a lot of people but I really like UI's man.
  I know theres a lot of value and speed in being able to do everything from the command line
  but for most of the things I do being able to see whats going on is pretty valuable.
