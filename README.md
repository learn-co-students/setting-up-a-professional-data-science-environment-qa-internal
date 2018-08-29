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

### Mac
Go [here](https://www.anaconda.com/download/#macos) and click on the “download” button for the Python 3.x (currently 3.6) version of Anaconda.

You should see in the bottom of your browser window that a .pkg file is being downloaded. When it finishes downloading, click on the arrow to the right of the name of the file in the bottom left corner of your browser, and select “open”.

If you don’t see the file in your browser, you can also just open up the finder, navigate to the “Downloads” directory and double click on the Anaconda file in the list to open it.

You’ll be informed that the package will run a program to see whether the software can be installed. Click “continue”.

You’ll then see a wizard that will run you through the installation process. Click continue on the first screen.

Then look at the read me, and click “continue” again.

You’ll then need to accept the license. Start by clicking “continue”

And then click on “agree” in the dialog that comes up and asks you to accept the license.

Then click on “install” to install the software.

And you’ll have to enter an administrative username and password for your computer to finally install the software.

The wizard will let you know next that it’s preparing the install, and then it’ll take a couple of minutes to install all of the necessary software.

You’ll be given the option to install Microsoft VSCode. For now, you can skip that option by clicking “continue”.

You should then see a final window informing you that the software was installed successfully. Click close to finish the installation.

If you’re asked whether you’d like to move the installer to trash, click the “Move to trash” button.

## Testing your installation

To test your installation, on Windows, click on Start and then Anaconda Navigator in the program list (or search for Anaconda in the search bar and select Anaconda Navigator). On a Mac, open up the finder, and in the Applications folder, double click on Anaconda-Navigator.

From now on, screenshots will be from a Mac, but we’ll highlight any material differences in the experience between the OS’s.

The Anaconda Navigator is one of the ways you’ll be able to run Jupyter Notebooks. Click on the “launch” button in the Jupyter notebook tile.

On a mac you’ll see a terminal window pop up.

On both Windows and a Mac you’ll see a window in your web browser that allows you to open existing Jupyter notebooks or create a new one.

Click on the “New” button in the top right corner.

And select “Python 3” from the drop down list. 

When you do, you’ll see a new notebook in your browser window that looks something like this:

To make sure it’s working, click in the cell and type the following:

```
import sys
print(sys.version)
```

Then hold down the shift key and hit enter to run the code in the cell. You should see an output something like this.

Don’t worry if the version number or date is slightly different. If you get a similar output (something that isn’t an error message), congratulations! You’ve got Anaconda, Python and the Jupyter notebook installed successfully!

To shut down Jupyter notebook, just close the tabs in your browser containing the notebook and the list of noteboks. On a mac you should also click on the terminal window and hit “ctrl-C” to close the notebook. 

You’ll then have to hit “y” and return to confirm that you want to close down Jupyter notebook.

## Cloning this Repository

To finish this setup process, you’re going to need to download a copy of the files in this repository. To do that, you need to start by opening a terminal window.

If you’re on a windows machine, select “Git Bash” from either the start menu or the search bar and it’ll open up a terminal (don’t use the default Windows terminal - it may not work for this). If you’re working on a mac, open the “Terminal” app in the “Utilities” folder within your “Applications” folder.

Let’s type `pwd` to “print the working directory. It should be somewhere you are OK downloading files to. If not, feel free to use the “cd” command to change directory to one you’d like to work from.

Then type (or better still, cut and paste) `git clone https://github.com/learn-co-curriculum/setting-up-a-professional-data-science-environment`

This will create a new subdirectory called setting-up-a-professional-data-science-environment which will contain a copy of all of the files from this repository.

## Setting Up Virtual Environments

As you do data science projects, you will spend a lot of your time using pre-written libraries to speed up your development. Examples include NumPy, Pandas and scikit-learn. As you work on different projects, you may also find that you end up using different versions of different libraries for different projects. The most common versioning issue is that some projects will run in Python 2 whereas others will run in Python 3, but you may also find that different projects depend on different versions of libraries like tensorflow.

Occasionally, code that works in an old version of a library won’t work in a newer version. So if you open up a new project and install the dependencies, it’s possible that your old project won’t work any more. 

To avoid that problem, a best practice is to use “virtual environments”. Virtual environments allow you to have different versions of Python and different versions of the various libraries you use, so you can install a new version of a library for one project but still use the old version for another project. It’s almost as if you have multiple computers that you can swap between, each having a different setup and configuration, just by running a couple of commands.

There is a build in virtual environment feature in Python, but we’re going to use the more flexible virtual environments provided by conda as part of the Anaconda distribution you installed.

To use a new virtual environment, there are two steps you need to complete. The first step is to create the virtual environment. That may take a couple of minutes as your computer has to download the necessary version of Python and all of the libraries that you want to be able to use in that environment. The next step then is to “use” the virtual environment by activating it.

If you want to learn more about conda environments, have a look at the [documentation](https://conda.io/docs/user-guide/tasks/manage-environments.html), otherwise, lets give this a try.

You need to start by navigating into the root of this project folder, so you’re going to want to type `cd  setting-up-a-professional-data-science-environment` in your terminal.

Then to create the environment type `conda env create -f environment.yml`. Depending on the speed of your computer and your internet connection it may take up to five minutes for this to complete. While it does you should see output similar to that displayed below start to appear in your terminal.
 

If you see a message that states “WARNING: A newer version of conda exists”, feel free to run `conda update -n base conda` but it shouldn’t be required to get things working.

Next, try activating the environment by typing `source activate student-env`.

