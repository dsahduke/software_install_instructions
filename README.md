# Installation Instructions

Modern data science is an interdisciplinary science that incorporates many of the practices of modern software engineering. As such, there are many software packages/programming languages that you will need for this course. We have tried to strike a balance between having every student download everything they would ever need versus just the minimal environment needed to run some basic analysis. You will need to allocate *10GB* of free space for the environments for this course. If this is a problem, please let the teaching staff know as soon as possible so that we can make the appropriate modificiations.

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

The recommended install is done through Anaconda. You can find the installation for Anaconda below:

[Anaconda](https://www.anaconda.com/download/)

If you do not wish to use Anaconda, you can find instructions on how to just install the jupyter notebooks software below. However, please note that if you are not using Anaconda for Python 3.7 or a Docker container, *you are liable for your own software installations*. The TAs and I will not be responsible for any technical issues that you may encounter. 

[Jupyter Installation Instructions](http://jupyter.org/install)

For those of you that are already familiar with tools such as Docker, you can pull the following container down and it will contain everything you need to run the notebooks for this course unless otherwise specified.

`docker pull jupyter/scipy-notebook`

We will also provide docker images for any of the analysis later on in the course upon request. 

### Docker (optional)

Docker is a modern tool for software containerization. We will discuss why Docker and similar technologies are attractive for the purposes of providing reproducible environments for data science and software engineering. However, due to some additional complexity as well as the size of docker images on disk, we will leave this step as optional. I would like to emphasize, however, that Docker is an extremely valulable tool that is popular within industry. The instructions to download Docker can be found at the following:

[Docker](https://docs.docker.com/install/)



