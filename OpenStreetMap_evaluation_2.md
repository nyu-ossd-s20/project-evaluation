# Project Name:  OpenStreetMap

**Evaluating Person or Team**: Sylvia | sylviaji

---

## Project Data

1. Project description: <br>
OpenStreetMap is a free editable map of the world. The code is the Rails application that powers OpenStreetMap. The users are mappers who contribute and maintain geo data all over the world and people who would like to use the open data.

2. Project website/homepage: [OpenStreetMap](https://www.openstreetmap.org)

3. Project repository: [GitHub - openstreetmap/openstreetmap-website: The Rails application that powers OpenStreetMap](https://github.com/openstreetmap/openstreetmap-website)


## License

1. What is the project’s license? <br>
GNU General Public License v2.0.

## Code Base

1. What is the primary programming language in the project?
Ruby.

2. What is the development environment? <br>
The software can be installed directly on the local machine, but an easier alternative would be using Vagrant to install it into a virtual machine. The instructions for setting up the development environment are based on Ubuntu 18.04 LTS, but also work for all other current Ubuntu releases, Fedora and MacOSX with minor amendments.

3. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
The 	`README.md` document has a link to `INSTALL.md`, which has detailed guidelines of installation that seem pretty easy to follow. 

4. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
Yes, the project depends on external modules such like PostgreSQL for databse and ImageMagick for bitmap image editing. Instructions on installing these modules can be found in `INSTALL.md`.

5. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
I have no experience with Rubys so I won't say the code is easy to udnerstand for me.

6. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
The project has 208,540 lines of code.

7. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
Yes, there is a test folder and testing insturctions can be found in `CONTRIBUTING.md`. Code contributors are expected to write new tests for the newly added functionality.

## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
There’s some documentation in the code, but I would not say that it is clear. 

2. Is there documentation about the design?  <br>
No.

## Activity Level

1. How many commits have been made in the past week? <br>
10 commits have been made in the past week (Feb 25 - Mar 3). 

2. When was the most recent commit? <br>
Mar 2.

3. How many issues are currently open? <br>
373 issues.

4. How long do issues stay open? <br>
Issues stay open for an average of 5 days (based on the five most recenly closed issues). 

5. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
Yes, there is active discussion on the issues.

6. Are issues tagged as easy, hard, for beginners, etc.? <br>
Only a few issues (2 open and 3 closed) are tagged as good first issue.

7. How many issues were closed in the past six months? <br>
62 issues were closed in the past six months.

8. Is there information about how many people are maintaining the project? <br>
Maintainers are listed in the `README.md` document, and there are currently two contributors. 

9. How many contributors has the project had in the past six months? <br>
The project had 22 contributors in the past six months.

10. How many open pull requests are there? <br>
There are 47 open pull requests.

11. Do pull requests remain un-answered for a long time? <br>
Pull requests get are answered within one day (based on the five most recently closed pull requests).

12. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
It depends. Sometimes are merged without any discussion, and sometimes the maintainers will leave a comment which is usually where a discussion starts. 

13. How many pull requests were opened within the past six months? <br>
104 pull requests were opened within the past six months.

14. When was the last  pull request  merged? <br>
The last pull request was merged on Feb 26.

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
Yes, there is a CONTRIBUTING document. It is detailed and organized which makes it easy to read and unserstand. 

2. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
There is no CODE OF CONDUCT document.

3. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Yes, the maintainers respond to questions in issues quite promptly and the responses are generally constructive.

4. Are people friendly in the issues, discussion forum, and chat? <br>
Most people are friendly.

5. Do maintainers thank people for their contributions? <br>
Yes, maintainers usually thank people for the work regardless of whether the pull request is accepted or not. 


## Development Environment Installation
Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. How involved was the process? <br>
I followed the instructions in `INSTALL.md`.

2. How long it take you? <br>
It took me about one hour.

3. Did you need to install additional packages or libraries? <br>
Yes, I had to install additional packages.

1. Were you able to build the code following the instructions? <br>
No. I kept getting the following error at the `Ruby gems` step:
```
An error occurred while installing pg (1.2.2), and Bundler cannot
continue.
Make sure that `gem install pg -v ‘1.2.2’ —source ‘https://rubygems.org/'`
succeeds before bundling.
```
The solutions I found online did not work for me. 

4. Did you need to look for additional help in installing the environment? <br>
I had to look for additional help from Stack Overflow and GitHub issues. 

5. Any other comments? <br>
I think that some instructions can be more detailed. For example, I was not sure what "your path" and "your profile” refer to in the following instruction:
```
•	Add PostgreSQL to your path, by editing your profile:
nano ~/.profile
```


## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
I don’t think so. This is quite a big project and I believe it will take a significant amount of time for one to understand how the source code works. Also, to contribute to the project, knowledge of Ruby, PostgreSQL, etc. is required, which will be a big learning curve for someone without prior knowledge.

2. Would you be interested in contributing to this particular project? <br>
Not really. First, it took me a long time trying to figure out how to set up the development environment, and I wasn’t able to get the installation done. This does not seem like a good start. Second, the primary language is Ruby which I am not familiar with, and there is a lack of clear documentation in the code so it might be hard for me to write code for the project. Third, there is not code of conduct file in the project repository, which I don’t think is a good sign.