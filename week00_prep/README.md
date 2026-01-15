# Week 0: Pre-course preparation

We begin Week 1 with peer-to-peer presentations of `week00_prep_answers.py` (see end of page). So
be sure to have it ready in class.

### If you are new to programming or Python:
Your preparation will involve **~8 extra hours of training** in basic Python and VS Code. 
I.e., the prep time for Week 1 is significantly higher for people who are newer to Python.
Please plan your time accordingly. This skewed preparation time for newer programmers will reduce after the first few weeks.  

### You are ready for Week 1 of PiWE when you have:  
1. Installed Slack and joined the class Slack chat.
1. Installed Python and VS code.  
1. Installed scientific Python packages.  
1. Installed git.  
1. Created a GitHub account.  
1. Forked and cloned this repository.  
1. Completed the basic Python course/exercises.
1. Completed the Python exercises and `week00_prep_answers.py`.  

## Working in pairs

Everything but the last step need to be completed on your individual laptop/computer. For the final exercise,
you are welcome -- nay, encouraged! -- to work in pairs. Engineering is collaborative problem solving. When
you have finished `week00_prep_answers.py`, add a comment to the top with your names and make sure you
both have a copy locally before coming to class in Week 1.

## 1. Install Slack and join the class Slack chat

We use the Slack messaging platform for communication and answering questions.
You can [install Slack](https://slack.com/download) on your laptop and on your phone.

Join the class Slackchat by navigating to the course Learn page and clicking the invite link in the upper right corner.

## 2. Install/verify VS Code and Python

* If you already have a Python IDE/distribution (e.g., Anaconda/Spyder, PyCharm, etc.):  
   * If you are very comfortable with your IDE and Python distribution (e.g., know how to install/uninstall
     Python packages from the terminal and run the debugger):
      * You may keep your current setup at your own risk. If Python compatibility issues arise during the
        semester, you may need to revert to the recommended set-up.  
   * If you do not know how to install packages from the terminal and/or run the debugger:  
      * Please unintall Python/Anaconda/PyCharm and any other related applications, then follow
        installation instructions in the next bullet.  
* If you need a Python IDE/distribution:  
   * Follow the instructions for "automated installation" [here at DTU Python support](https://pythonsupport.dtu.dk/install/python.html).  
   * Verify the installation per the instructions at the link.  
   * If there are issues, read the installation page thoroughly, but then contact DTU Python support
     if it still won't behave.  


## 3. Install scientific Python packages

If you already have the packages below installed in a Python distribution/environment, you may skip this step.

Search for and open Anaconda Prompt (application). In the resulting terminal, enter the following
command:  

   ```python -m pip install numpy matplotlib scipy pandas pytest pytest-cov pylint```  

This will install these packages to your base Python environment.
We will learn more about what they do during the course.

*If you know about environments and want to create one for this course, you are welcome to do so.
If you don't know what this means, ignore it. :)*


## 4. Install git

If you already have a git program, skip this step.

Install the git program from [this website](https://git-scm.com/).


## 5. Make a GitHub account

Go to [GitHub.com](https://github.com/) and create an account. Noice.

## 6. Clone this repository

A "repository" is often called "repo", 'cause life is short.  


1. Open this repository's webpage on GitHub.com: [https://github.com/DTUWind-46120-2026/46120-PiWE](https://github.com/DTUWind-46120-2026/46120-PiWE).  
1. In the upper-right corner, click the green "Code" button in the upper-right corner, and copy the HTTPS link.  
1. Create a folder on your computer where you want your PiWE materials to be saved.  
1. Open a git bash terminal in this folder. On Windows:  
   a. Right-click in the folder.  
   b. Select "More options".  
   c. Select "Open Git Bash here".  
1. In the git terminal, enter the following command:  
   ```git clone <HTTPS link you copied>```
1. This should create a subfolder called `46120-PiWE`, which contains the repo material. The files for the Week 0 prep are in the subfolder `week00_prep/`.  

## 7. Complete the basic Python refresher/prep course

Note: The `welcome_to_python.ipynb` Jupyter notebook is in the `week00_prep/` subfolder of the folder you cloned in the previous step.

* If you are comfortable with Python and Jupyter notebooks in VS Code:
   * Use VS Code to complete the module-end exercises in the `welcome_to_python.ipynb` Jupyter notebook.
* If you have some programming knowledge but are new to Python or VS Code:
   * See the instructions on the ["Basic Python Prep Course" on Learn](https://learn.inside.dtu.dk/d2l/le/lessons/294813/units/1114167).
   * You can complete the exercises in the prep course without watching all the videos.
   * Afterwards, if you want more practice to cement your core programming skills, optionally complete the `welcome_to_python.ipynb` Jupyter notebook in VS Code.
* If you are relatively new to programming in general or want to practice the basics:
   * See the instructions on the ["Basic Python Prep Course" on Learn](https://learn.inside.dtu.dk/d2l/le/lessons/294813/units/1114167).
   * Afterwards, if you want more practice to cement your core programming skills, optionally complete the `welcome_to_python.ipynb` Jupyter notebook in VS Code.

Use GenAI (ChatGPT, Copilot, etc.) as little as possible.
These exercises practice basic knowledge that you need to be able to remember without assistance.
**If you have questions, please post them in the course Slack chat. We want to help you learn! :)**


## 8. Finish week00_prep_answers.py

Create a file called `week00_prep_answers.py` in your `46120-PiWE/week00_prep/` folder on your computer.
In this file, write code that completes Required Exercises 1 through 5 on [this page](https://python-at-risoe.pages.windenergy.dtu.dk/codecamp/preparation.html#Required-exercises). 

Want to practice EVEN MORE? 😍
 * Complete the "Optional Python exercises" on the same page as Exercises 1 through 5 on [this page](https://python-at-risoe.pages.windenergy.dtu.dk/codecamp/preparation.html#Required-exercises). 
 * Go through the tutorials in `tutorials_scientific_python/` subfolder in the repo.

Once you're finished `week00_prep_answers.py`, you're freeeeeeeeee!
