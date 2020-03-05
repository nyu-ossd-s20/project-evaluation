# Project Name: PyTorch3D



**Evaluating Person or Team**:
Nishant (@niniack)

---

## Project Data

1. Project description: <br>

    A neural network library providing reusable components for 3D computer vision, with a focus on providing data structures and efficient operations on triangle meshes.

1. Project website/homepage: https://pytorch3d.org/

1. Project repository: https://github.com/facebookresearch/pytorch3d



## License

1. What is the project's license? <br>
    BSD-3-Clause License.


## Code Base


1. What is the primary programming language in the project?

    The project is almost exclusively written in Python (75%), but has a sizable portion written in CUDA and C++ (9.5% and 9.1%, respectively)

1. What is the development environment? <br>

    From their installation page:
    - Linux or macOS or Windows
    - Python ≥ 3.6
    - PyTorch 1.4
    - torchvision that matches the PyTorch installation. You can install them together at pytorch.org to make sure of this.
    - gcc & g++ ≥ 4.9
    - CUDA 9.2 or 10.0 or 10.1
    - [fvcore](https://github.com/facebookresearch/fvcore)

1. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>

    Yes, the instructions are stored in a INSTALL.md file, which is also linked in the README.md.

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>

    Yes, the project depends on PyTorch, torchvision (NN libraries) CUDA (parallel computing), and fvcore (core library by facebookresearch)

1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample. <br>

    Not necessarily easy to understand, but I feel like it may be accessible to someone who has a bit of experience with manipulating 3D meshes in code.


1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>

    97218 using git ls-files | xargs wc -l

1. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>

    Yes, there are tests. Contributors are expected to add tests and ensure the code passes the tests before submitting their pull request.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>

    Yes, each method is described with comments in detail and variables/methods are well named

1. Is there documentation about the design?  <br>

    No, the documentation doesn't have information about the design of the project.


## Activity Level


1. How many commits have been made in the past week? <br>

    3 commits in the past week.

1. When was the most recent commit? <br>

    March 4th

1. How many issues are currently open? <br>

    25 issues currently open

1. How long do issues stay open? <br>

    Random sample (days remained open): 0, 1, 0, 0, 3

    An average of less than a day

1. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>

    Yes, especially on the issues labelled "bug"

1. Are issues tagged as easy, hard, for beginners, etc.? <br>

    No, but there is a "good first issue" label that has been used once (in the total of 100 issues since the project was published)

1. How many issues were closed in the past six months? <br>

    75 issues

1. Is there information about how many people are maintaining the project? <br>

    The contributors page shows about 3 main contributors.

1. How many contributors has the project had in the past six months? <br>

    15 contributors

1. How many open pull requests are there? <br>

    4 open and 27 closed

1. Do pull requests remain un-answered for a long time? <br>

    Random sample (days remained un-answered): 1, 1, 0, 0, 1

    An average of less than a day

1. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>

    Yes, the main contributors tend to be active in responding to the non-core contributors.

1. How many pull requests were opened within the past six months? <br>

  31 pull requests

1. When was the last  pull request  merged? <br>

    9 days ago

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>

    Yes, there is. It is easy to access and understand and lays out expectations by the maintainers.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>

  No, there is not.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>

    Yes, they mention they will get back to the issue with more detail and follow up!

1. Are people friendly in the issues, discussion forum, and chat? <br>

    Yes.

1. Do maintainers thank people for their contributions? <br>

    Yes, most of the responses by the maintainers begin with thanks


## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. How involved was the process? <br>

    Not very involved, I simply had to install the pre-requisite packages and then install the pytorch3d package using conda.

    This was all given that I had configured Conda before, which can be troublesome.

1. How long it take you? <br>

    A few minutes

1. Did you need to install additional packages or libraries? <br>

    Yes, pytorch pytorch torchvision cudatoolkit=10.0 fvcore

1. Were you able to build the code following the instructions? <br>

    Yes, quite easily

1. Did you need to look for additional help in installing the environment? <br>

    No

1. Any other comments? <br>

    N/A


## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>

    Yes, it would be possible given that the PyTorch3D library itself is not huge and very involved. It is a library that helps one use 3D objects in the context of TensorFlow, so it is a lot of 3D transformations and manipulations and not as much of machine learning. Hence, someone who may have had experience working with 3D objects in programming may not have too difficult a time.

1. Would you be interested in contributing to this particular project? <br>

	No. After evaluation, something off-putting is that since this project is maintained under the facebookresearch group, contributors must sign the Contributor License Agreement. Furthermore, given it is a very new project, while documentation may be needed, it feels as if it hasn't gained enough momentum for there to be a lot of options in contributions.
