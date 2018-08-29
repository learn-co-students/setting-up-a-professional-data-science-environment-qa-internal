# Setting up a Professional Data Science Environment

Whether you’re just looking to learn the basics or want to become a professional data scientist, it’s important to take a little time to “set yourself up for success” by installing and learning to use the right tools on your computer.

## What tools do professional data scientists use?
* **Python** - There are many languages that can be used for data science, but these days most data scientists are using Python to write their code. 
* **Jupyter Notebook** - Most of those data scientists use Jupyter Notebook for writing their * Python - a tool that allows you to mix comments in-between your code snippets so you can document and share your thinking process and make it easier for others to review, replicate and expand on your work.
* **Anaconda** - Anaconda is one of the most popular way for data scientists to install Python and Jupyter notebook on their computers. It also provides package management and virtual environments so you can get all the latest data science tools running like NumPy, SciPy and Tensorflow, and so you can use different versions of python and your packages for different projects without them conflicting with each other.
* **Git** - Git is a version control system. It’s a way of keeping track of all the changes made across your project. Think of it like “track changes” in Word - but with the ability to track changes across multiple documents. At Flatiron School, we use git to keep track of all of the lessons we create and all the changes we make to them.
* **GitHub** - GitHub is a website where data scientists (and programmers) can save their work in case their computer breaks, and share it with their team or the world! At Flatiron School, we store all of our lessons on GitHub.

It’s going to take us a few minutes to get this all installed, but once we do, not only will you be set-up for working through the course, but you’ll also have a professional data science setup on your computer for any future courses or projects you want to work on!

## Computer Prerequisites
There are many amazing computing devices available these days, but not all of them will allow you to do data science. We love smart phones, flip phones, chromebooks, tablets (including iPads), game boys, nintendo switches, roku’s and arduino’s. You’re not going to be able to complete this course on any of those devices - sorry.

You’re going to need a computer (laptop or desktop). It should be running a recent (last 3-4 years) version of MacOS, Windows or Linux, and ideally it should have 8Gb of RAM and at least 20Gb free hard drive space. More information here:

[https://flatironschool.com/wp-content/uploads/Student-Facing-Computer-Requirements.pdf](https://flatironschool.com/wp-content/uploads/Student-Facing-Computer-Requirements.pdf)

Assuming you have a computer that meets the requirements, let’s start by getting git Installed.

## Installing Git
For each tool, we’ll provide installation instructions for the two most common operating systems - Windows and MacOS.

### Installing Git on Windows
Go [here](https://git-scm.com/download/win). Then double click on the downloaded exe file. It may open a window asking if you want to allow this application to make changes to your device. Just click “yes”. It will then open the installer. Click “next” to accept the license, and when you “select components” on the next screen make sure to keep the “Windows explorer integration” options checked.

*Note - if there are any differences in the options provided in the installer you download, just accept the defaults - they’ll probably be fine!*

When asked to select an editor, if you’re familiar with vi/vim feel free to use that, otherwise you should probably select an easier to use text editor such as nano.

When asked to adjust your PATH environment, either of the first two options is fine as you’ll mainly be using Git from the new “Git Bash” program that is being installed. You’re probably best to select “use Git from the Windows Command Prompt” as it’ll give you the option of using it there in the future if you wish.

For https, you should select the “use the OpenSSL library” option.

Select the default option for handling line endings.

And use MinTTY as the default terminal emulator.

For extra options, enable the file system caching and the gt credential manager.

And then wait while git is installed onto your computer. 

Finally, click finish to complete setup.

### Installing Git on MacOS
If you are comfortable with the command line and have installed [homebrew](https://brew.sh/), you should install git by running the command `brew install git` in a terminal window.  

If you have no idea what the last paragraph meant, just go [here](https://git-scm.com/download/mac). Then double click on the downloaded dmg file and it will open a small finder window (the exact name and version will change over time):

Double click on the .pkg file to run it. When you try to do that you might get a security warning pop up.

If that happens, just click on the apple at the top left of the screen, select “system preferences” from the drop down menu. Then select “Security and Privacy”, select the “General” tag, click on the lock to make changes at the bottom of the window (you’ll have to enter your password). Below the “Allow apps downloaded from” option, you should see a message stating that an app was blocked from opening. (If you don’t see this message, double click on the .pkg file again and then look back at the Security & Privacy screen and it should pop up).  Click the “open anyway” button.

You should then see a message confirming whether you really want to open the app.

Click on the “open” button. You should then see an installer screen. 

Click “continue”, then “install”, enter your password when prompted, and when the installation is complete, click the “close” button.


## Confirming your git installation (all OS’s)

To confirm you have installed Git successfully, open a terminal window (in Windows, using the start menu, open the “Git Bash” program to get a terminal, on a mac, just open the “Terminal” app in the “Utilities” folder within your “Applications” folder). Type `git --version`. It should return the version of git you are running.

While you’re in the terminal, you should also set up your name and email address.

Type `git config --global user.name`

If it returns your name, you’re set! If it returns nothing or displays an error message, type `git config --global user.name “Your Name”` - replacing Your Name with your name.

Type `git config --global user.email`

If it returns your email address, you’re set! If it returns nothing or displays an error message, type `git config --global user.email your@email.com` - replacing your@email.com with your email address.


## Installing Python and Jupyter Notebook via Anaconda

The easiest way to get set up with Python and Jupyter Notebook so you can start coding is to install the Anaconda distribution. Let’s go through the install instructions  for the two most common operating systems - Windows and MacOS.

### Windows
Go [here](https://www.anaconda.com/download/#windows) and click on the “download” button for the Python 3.x (currently 3.6) version of Anaconda.

A window may pop up asking if you want to give Anaconda your information in return for a cheat sheet - you do not need to do so unless you want to.

You should see in the bottom of your browser window that a .exe file is being downloaded. When it finishes downloading, click on the arrow to the right of the name of the file in the bottom left corner of your browser, and select “open”.

If you don’t see the file in your browser, you can also just open up Windows Explorer, navigate to the “Downloads” directory and double click on the Anaconda file in the list to open it.

That will open the Anaconda installer which will install the software for you on your computer.

Click “next”, then “I agree” to accept the license, and you can install for “just me”, clicking next. Then select the destination folder (the default should work for most people).

On the next screen, accept the default options and click “install”.

This step may take a few minutes.

Once the installation is complete,

Hit “next”. You can skip the Visual Code Studio installation

And then finally click “finish”.

It’ll open up a browser window which you can just close down.

And that’s the process of installing Anaconda. The next step is to test your installation.

