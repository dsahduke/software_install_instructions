# Installation Instructions

Modern data science is an interdisciplinary science that incorporates many of the practices of modern software engineering. As such, there are many software packages/programming languages that you will need for this course. We have tried to strike a balance between having every student download everything they would ever need versus just the minimal environment needed to run some basic analysis. You will need to allocate *15GB* of free space for the environments for this course. If this is a problem, please let the teaching staff know as soon as possible so that we can make the appropriate modificiations.

### Git
[https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Please follow the instructions here to install git for your operating system

### Shells

If you are using a mac, I would recommend using [iTerm2](https://www.iterm2.com/), although the default terminal will be fine.

**NOTE** for Windows users, you will need to install something that has bash, which is not something that comes with Windows by default. I would recommend either installing

[cmder](http://cmder.net/)

or 

[cygwin](https://www.cygwin.com/)

Although it is not required for this course, you may want to also look into the [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

### Python + Jupyter Notebooks

Note that we will be using Python 3.6+ for this course. Please make sure you have installed the correct version.
[Jupyter Installation Instructions](http://jupyter.org/install)

Alternatively, you can use software containerizations software that has Jupyter pre-installed. This method will be demonstrated later on in the course.

For those of you that are already familiar with tools such as Docker, you can pull the following container down and it will contain everything you need to run the notebooks for this course unless otherwise specified.

`docker pull juyter/scipy-notebook`

We will also provide docker images for any of the analysis later on in the course.

### Docker

Docker is a modern tool for software containerization. We will discuss why Docker and similar technologies are attractive for the purposes of providing reproducible environments for data science and software engineering. The instructions to download Docker can be found at the following:

[Docker](https://docs.docker.com/install/)



