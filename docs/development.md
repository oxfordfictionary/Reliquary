# Development

- Get Familiar with the Tools
  - [StackOverflow - Software Community](https://stackoverflow.com/) - global leader in Q/A for Software questions. Setup an account, start searching for simple things, start asking simple questions
  - [VSCode - Visual Code Editor](https://code.visualstudio.com/) - Cross-platform, Open-Source, Performance friendly
  - [Docker - Container Manager](https://www.docker.com/)
  - [Git - Source Control Manager](https://git-scm.com/) - Tools for pushing/pulling source from hosted services like Github or BitBucket (damn you joel)
  - [Github - Open-source Software Sources](https://github.com) - Where the Open-Source world stores their shit. The *best* way to learn to code, is to read/run other people's code. So, search through github for things. There, you will find millions of results never exposed by Google searches.
    - ex. Searching for `Python Basic Program` finds https://github.com/AsciiKay/Beginners-Python-Examples/blob/master/dictionary.py 
- Install the development tools
  - [Make](http://gnuwin32.sourceforge.net/packages/make.htm)
  - [Docker](https://docs.docker.com/docker-for-windows/)
  - [VSCode](https://code.visualstudio.com)
  - Windows
    - [Git for Windows](https://gitforwindows.org/) - this contains some reasonable shell tools and git
   
- `Warnings`
  - Don't install Python. There are many versions of python, almost all of which don't work well together. Instead, install Docker and define the Python runtime within a projects Dockerfile
  - Don't use [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install-win10). While cool, there are still limitations with interoperability between Windows applications and those installed in the Subsystem runtime. The Subsystem is really intended for Non-UI tasks and will be a serious blocker for a ton of things important during development.
  - Don't pay for things. In 2019/2020, open-source software is the basic offering and most pro software companies charge money for security/support of the open-source applications. Unless your doing Flight Control or Launching Rockets, the Open Source (free) version of things should be enough. Think before you pay.
