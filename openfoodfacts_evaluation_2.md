# Project Name: OpenFoodFacts   



**Evaluating Person or Team**: David, Flydx1234


## Project Data

1. Project description: <br>

Open Food Facts is a food products database. It basically contains information on foods from all around the world
and allows anyone to add more foods to their database. Currently there are 1,173,440 products in the database.
I would imagine that their userbase contains people from all over the world, broadly encompassing as it is simply a search engine
for food.

1. Project website/homepage: <https://world.openfoodfacts.org/>

1. Project repository: <https://github.com/openfoodfacts/openfoodfacts-server>



## License

1. What is the project's license? <br>

The project's license is the: GNU AFFERO GENERAL PUBLIC LICENSE.



## Code Base


1. What is the primary programming language in the project?
    The primary programing language in the repository I have chosen is HTML.
1. What is the development environment? <br>
  This is an online website that uses Project Opener ran on Docker for its server.

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
  There are instructions on how to install are pretty easy to find, as they have a wiki as well with all the information that is needed.
  They seem easy enough to follow.

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
  The project depends on many external libraries: zbar, imagemagick, graphviz, tesseract, installation instructions for these are clear.
  It also depends on many pearl modules as well as MongoDb to run, installation instructions for the pearl modules is clear,
  but as for MongoDb, all it states is to install it.
  They also use an Apache web server that also has some config instructions, but it seems there is nothing about how to install or run it.

1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
  I think most of the HTML code is easy to understand, and there are comments as well.


1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
  The project is pretty big, and has over 553 thousand lines of code.

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
  The repository has tests, although there are no expectations for code contributors to write tests for newly added code.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
    The HTML code seems pretty self explanatory and is documented. Other code files such as the JavaScript seem to contain
    links to documentation.
1. Is there documentation about the design?  <br>
    They have a wiki with documentation about their design.

## Activity Level


1. How many commits have been made in the past week? <br>
    Over 35 commits have been made in the past week.
1. When was the most recent commit? <br>
    At the time, 3/2/2020 3:00 PM, the most recent commit was 6 hours ago one 3/2 9:00 AM.
1. How many issues are currently open? <br>
    715 issues are currently open.
1. How long do issues stay open? <br>

   Issues stay open for an average of 6.6 days.

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
    There exists active discussion on most of the issues.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
    There are issue tags for "good first issue", but none for medium/hard.
1. How many issues were closed in the past six months? <br>
    182 issues were closed in the past six months.
1. Is there information about how many people are maintaining the project? <br>
    There are 53 contributors to the project.
1. How many contributors has the project had in the past six months? <br>
    About 18 contributors have been active in the project in the past six months.
1. How many open pull requests are there? <br>
    There are 32.
1. Do pull requests remain un-answered for a long time? <br>
	 No, the pull requests are usually merged in an average of 2 days.

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
   The open pull requests have a great amount of conversation in them. While the closed ones do have conversations, many of them are brief.
   I assume that's why many of the pull requests are closed so fast.
1. How many pull requests were opened within the past six months? <br>
    19 pull requests.
1. When was the last  pull request  merged? <br>
    March 1.
## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
    There is a contributing document. It is pretty easy to understand.
1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
    There is a code of conduct, although it is an HTML document.
    Violators may be temporarily or permanently blocked.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
    Although there are 53 contributors only a few actively respond to the issues.
    But the responses are genrally constructive.
1. Are people friendly in the issues, discussion forum, and chat? <br>
    Yes.
1. Do maintainers thank people for their contributions? <br>
    Yes.

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
    Initially the process was not really involved, most of it was following instructions on the website and waiting for modules to install.
    The hardest part, and the part that included the most involvement was setting up the Apache server, which required a lot more libraries
    and other downloads not listed in their guide in order to get running.
    There was also no real instructions on how to install apache itself, just how to configure it.
    Every time I ran ./configure, there would be another file/library that was missing that I had to install.
1. how long it take you? <br>
    About 3 hours.
1. did you need to install additional packages or libraries? <br>
    Installed cpan for perl to install the perl modules.
    Also had to install Apache Runtime and Apache Runtime Util.
    Also had to install PCRE library for perl, and zlib1g-dev.
    Had to install, libapr1-dev, and libgdbm-dev.

1. were you able to build the code following the instructions? <br>
    I was not able to build the code following the instructions. The instructions for the apache server was unclear, and I ran into a lot of issues.
    After following all the instructions, I had no idea how to start the apache server, or their server product opener.
    Furthermore, due to lack of information for the apache installation, I am not sure if I did it correctly.

1. did you need to look for additional help in installing the environment? <br>
    I had to search up how to install the packages for zbar and tesseract as the linux install name was not specifically listed.
    There was basically no install instructions for Apache, and I encountered a lot of issues that I had to search up.

1. any other comments? <br>
    I did not know to install Apache from source, I installed it using the terminal command initially. Which resulted in me spending a lot of time
    trying to figure out what I did wrong.
    The wiki does say to install from source, but I wasn't aware of what that exactly meant since this is the first time I encountered the specific
    method of installation using ./configure.



## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
	 It's definitely possible for me to contribute to, as most of the code is written in HTML. I think that the environment setup is probably the hardest part.
   Furthermore their website design, at least in my opinion is pretty unrefined, and could be worked on.

1. Would you be interested in contributing to this particular project? <br>
    I would be interested in contributing to the project, it's a pretty interesting search engine, and seems like one that many people can use to find nutrition
    facts about food. Also seems like a site that I would use as well.
