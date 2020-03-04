Project Name: OpenFoodFacts
=====================

**Evaluating Person or Team**: Ryan Li @ryanhanli ---

Project Data
------------

1.  Project description: Open Food Facts is a free, open and collaborative database of
	food products from around the world. It contains information about food products
	such as calories, nutritional value, and etc.

2.  Project website/homepage: <https://world.openfoodfacts.org/>

3.  Project repository: <https://github.com/openfoodfacts/openfoodfacts-server>

License
-------

1.  What is the project\'s license? ODC Open Database License v1.0

Code Base
---------

1.  What is the primary programming language in the project?

    There are many different wrapper APIs coded in different languages, but they
	are in their own repository.  For the repository I 
	chose(<https://github.com/openfoodfacts/openfoodfacts-server>), the main
	programming language is HTML if you consider it a programming language.  
	Otherwise, Perl is the primary programming language.  The repository 
	consists of 94.2% HTML, but if one doesn't consider HTML a programming language, 
	Perl is the primary programming language even though it only consists of 5.4% 
	of the repository.

2.  What is the development environment?

    Docker and Travis CI

3.  Are there instructions for how to download, build, and install? How
    easy is it to find them? Do they seem easy (relatively speaking) to
    follow?

    The README file has a link which directs you to a step by step tutorial
	on how to download, build, and install Product Opener which is the server
	software for Open Food Facts.  They seem quite easy to follow,
	and if you're stuck the README file also includes a link to the official
	Slack group.  The actual database can be found on their main website to
	download as well.  The instructions are easy to follow and they formatted
	the data for you already into CSV or a MongoDB dump.

4.  Does the project depend on external additional software modules such
    as database, graphics, web development, or other libraries? If so,
    are there clear instructions on how to install those?

    Requires many Perl modules, Apache, and MongoDB.  There are clear instructions
	on how to install all of these in the installation page the README links to.

5.  Is the code easy to understand? Browse some source code files and
    make a judgment based on your random sample.

    Based off judgment from a random sample, the code looks pretty easy to understand.
	Everything is commented and formatted nicely.

6.  Is this a big project? If you can, find out about how many lines of
    code are in it, perhaps on [OpenHub](https://www.openhub.net/).

    500,000+ lines of code.  This is a big project.

7.  Does the repository have tests? If so, are the code contributors
    expected to write tests for newly added code?

    Yes. It is not a requirement, but highly encouraged.

Code and Design Documentation
-----------------------------

1.  Is there clear documentation in the code itself?

    Yes

2.  Is there documentation about the design?

    [Yes](https://en.wiki.openfoodfacts.org/Product_Opener)

Activity Level
--------------

1.  How many commits have been made in the past week?

    \~36

2.  When was the most recent commit?

    Mar 2 (Yesterday)

3.  How many issues are currently open?

    714

4.  How long do issues stay open?

    A few days to a week. Some issues stay open for longer, and I'm sure it depends on the issue.

5.  Read the conversations from some open and some closed issues. Is
    there active discussion on the issues?

    Yes, there are usually always people commenting to see what the issue is and finding out more.
	Definitely active.

6.  Are issues tagged as easy, hard, for beginners, etc.?

    There are tags, but not for difficulty levels.

7.  How many issues were closed in the past six months?

    [181](https://github.com/openfoodfacts/openfoodfacts-server/issues?utf8=%E2%9C%93&q=is%3Aissue+closed%3A%3E%3D2019-09-02+)

8.  Is there information about how many people are maintaining the
    project?

    There are 53 contributors for the repository I chose, but I'd say
	only about 4 of them spend a lot of time maintaining the project
	based on the quantity of commits.

9.  How many contributors has the project had in the past six months?

    \~17

10. How many open pull requests are there?

    32

11. Do pull requests remain un-answered for a long time?

    No. They are merged pretty quickly usually within a 2-3 days.

12. Read the conversations from some open and some closed pull requests.
    Is there active discussion on the pull requests?

    Yes there are active discussions going on in the threads.

13. How many pull requests were opened within the past six months?

    [19 Open + 503
    Closed](https://github.com/openfoodfacts/openfoodfacts-server/pulls?utf8=%E2%9C%93&q=sort%3Acreated-desc+created%3A%3E%3D2019-09-02+)

14. When was the last pull request merged?

    Mar 2 (Yesterday)

Welcomeness and Community
-------------------------

1.  Is there a CONTRIBUTING document? If so, how easy to read and
    understand is it? Look through it and see if it is clear and
    thorough.

    Yes. Organized and easy to read.

2.  Is there a CODE OF CONDUCT document? Does it have consequences for
    acts that violate it?

    Yes. Consequences include being banned from the project.

3.  Do the maintainers respond helpfully to questions in issues? Are
    responses generally constructive? Read the issue conversations.

    Yes.

4.  Are people friendly in the issues, discussion forum, and chat?

    Yes.

5.  Do maintainers thank people for their contributions?

    Yes.

Development Environment Installation
------------------------------------

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1.  How involved was the process?

    Not much I just followed the instructions step by step on the abovementioned
	website and it worked (This is for Product Opener the server software).  The
	database itself was even easier to download I just downloaded the CSV file
	straight to my computer and that was it.

2.  How long it take you?

    30 minutes for the Product Opener and about 10 for the CSV file.  I did these
	two concurrently.

3.  Did you need to install additional packages or libraries?

    Yes, but only for the product opener.  I already had Excel on my computer to open
	the CSV file.

4.  Were you able to build the code following the instructions?

    Yes.

5.  Did you need to look for additional help in installing the
    environment?

    No, the instructions were enough.

6.  Any other comments?

    N/A

Summary
-------

1.  Do you think this is a project to which it would be possible to
    contribute in the course of a few weeks before the end of this
    semester?

    Yes. Some of the links the Github links to (Wiki pages) have a lot of typos,
	and fixing those would be a good start.

2.  Would you be interested in contributing to this particular project?

    Yes.  It seems like the project supports all the popular languages, and the
	database itself would be useful to me in the future.  Additionally, the
	community is very inviting and helpful it seems.
