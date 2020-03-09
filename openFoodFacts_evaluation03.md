# Project Name:  Open Food Facts



**Evaluating Person or Team**:
Muying Li

---

## Project Data

- Project description: <br>
A food products database with ingredients, allergens, nutrition facts and all the tidbits of information we can find on product labels. It is made by everyone and the complete database is published as open data and can be reused by anyone and for any use.

- Project website/homepage: https://world.openfoodfacts.org

- Project repository: https://github.com/openfoodfacts



## License

- What is the project's license? <br>
GNU AFFERO GENERAL PUBLIC LICENSE


## Code Base


- What is the primary programming language in the project?<br>
It is repository dependent since Open Food Facts is platform dependent. The [iOS app](https://github.com/openfoodfacts/openfoodfacts-ios) uses mainly Swift and [android](https://github.com/openfoodfacts/openfoodfacts-androidapp) ones uses 100% Java, while its [server](https://github.com/openfoodfacts/openfoodfacts-server) uses mainly HTML. 

- What is the development environment? <br>
Docker for its server.

- Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
Each repository's README.md is very clear, easy to follow and comprehensive by which includes multiple steps to install the app and other resources. 

- Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
Yes, it depends on Perl, Apache, MongoDB and many other libraries. There is a complete list of libraries and modules if you [click here](https://en.wiki.openfoodfacts.org/Product_Opener/Installation#Libraries).

- Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>
No. I checked several files written in Perl and in t. In the actual code, there is a lack of comments. For someone who does not know any Perl or t, like me, it is really hard to understand what the code is doing. In fact, even in js or css files, there is no useful documentation about the functionality of the code.

- Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
553K lines of code ([Reference](https://www.openhub.net/p?ref=homepage&query=open+food+facts)). I believe it is a big project.

- Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
No for the server but yes for others. The code contributors is not expecting tests for new codes.



## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
No.

1. Is there documentation about the design?  <br>
No.

## Activity Level


1. How many commits have been made in the past week? <br>
About 35 commits.

1. When was the most recent commit? <br>
Today (March 6th)

1. How many issues are currently open? <br>
725.

1. How long do issues stay open? <br>
About a week.

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
Yes for most issues.

1. Are issues tagged as easy, hard, for beginners, etc.? <br>
It is kind of hard for beginners since there is a total of 210 tags which is overwhelming, and most tags are without clarification or documentation.

1. How many issues were closed in the past six months? <br>
182.

1. Is there information about how many people are maintaining the project? <br>
Yes, on most README.md files of repositories, they include the contributors.

1. How many contributors has the project had in the past six months? <br>
17.

1. How many open pull requests are there? <br>
32.

1. Do pull requests remain un-answered for a long time? <br>
No.

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
There are many active discussions on the open pull request but not much on the closed ones.

1. How many pull requests were opened within the past six months? <br>
19.

1. When was the last  pull request  merged? <br>
Jan 26.

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
Yes. In the server repository, the [CONTRIBUING.md](https://github.com/openfoodfacts/openfoodfacts-server/blob/master/CONTRIBUTING.md) is basically lead you to join their slack.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
Not in the server repository. But there is a wiki page of [Code of Conduct](https://en.wiki.openfoodfacts.org/Code_of_conduct) and the other about [Terms of Use, Contribute, and Re-use](https://world.openfoodfacts.org/terms-of-use). Violating consequences include revoke the access to the site of contributors who voluntarily delete information or data and/or who add incorrect information of data, and legal action against them may be taken. 

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
Yes.

1. Are people friendly in the issues, discussion forum, and chat? <br>
Yes.

1. Do maintainers thank people for their contributions? <br>
Yes.

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
I already have those external modules like mongoose but I need to install Apache and Swift for iOS app development, and many additional libraries listed on the wiki.  For the database part, I also downloaded the CSV fil. 

1. how long it take you? <br>
About two hours.

1. did you need to install additional packages or libraries? <br>
Yes. 

1. were you able to build the code following the instructions? <br>
Not really since I barely know Perl or Swift.

1. did you need to look for additional help in installing the environment? <br>
Yes, for installing libraries.

1. any other comments? <br>
There are many stuff needed to install for its development environment, and it is really time and energy consuming.


## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
Definitely yes. First, it lacks of documentation for almost all files. Also, what I observed is that its database is kind of being messed up with many invalid objects. Moreover, they already write out what they need others to contribute in on wiki, such as [software development](https://en.wiki.openfoodfacts.org/Software_Development) on websites and mobile apps.


1. Would you be interested in contributing to this particular project? <br>
Yes, since it might improve my knowledge in NoSQL database (mongoDB) and data analysis skills.
