# Homework #2
**Due Friday Oct. 27th @ 11:59 pm**

**Objective:** This assignment will give you experience with control flow, Numpy arrays and functions, datetimes, and basic plotting.


## **Instructions:**
### Accessing Class Code

1. Clone this repository into your own JupyterHub by running this command in your home directory:
```git clone your_SSH_URL```

2. Once you have cloned the repository, go into your directory, git initialize your repository, and set your branch to "main" (See the GitHub cheatsheet for help on this). You will not need to reset your remote origin, as you have already directly cloned from your own version of the repository.

3. There should now be a "homework_2" directory in the home directory of your JupyterHub. In terminal, change directories into "homework_2". Next, click on the the "homework_1" icon on the filepath hierarchy in the left panel of JupyterHub. If you don't see it, make sure you're in the home folder by clicking the folder icon under the search bar. 

4. Double click the "HW2.ipynb" to open it in a new tab and begin working on the assignment. Read the instructions carefully, and make sure to write your answers in the specified cells. Typically, you will see a "..." in the places you need to fill in. Make sure to use the variable names provided in the starter code. See the "Working in your Notebook" section below for an example. There are some autograder tests embedded in the notebook, but there are also some hidden tests that will be graded after submission.

5. Edit the README file and write your name and UW NetID. Include a paragraph of instructions on how you used git commands to add, commit, and push to your repository (3-5 sentences). Now that y'all are GitHub connoisseurs, imagine that you are explaining how to use GitHub to someone who has never used GitHub before! :) 

6. As you continue to answer the homework questions and make edits to your code, make sure to regularly update your GitHub repository as well via git add, commit, and push (steps 15, 16, 19 in 0b). A good rule of thumb would be to run these git steps anytime you make an addition or change that you don't want to accidentally lose. Generally, you can push once a day to maintain good version control practices. <br>
As a note, make sure that your git commands are running without errors before you refresh your GitHub and check your changes. If you are not seeing the updated changes you created in your local JupyterHub directory, check where your status is by this command: <br>
``` git status```

Then, you can see if you made an error with your git add, commit, or push commands. 

**Sometimes, our JupyterHub server has trouble remembering the file permissions for our SSH keys. If you get a file permission error with your private ssh key, run this line of code:**
```chmod 400 ~/.ssh/id_ed25519``` 
<br>

This will change your file permission to the proper permissions that SSH requires.
    
### Submitting to GradeScope

7. Go to the class Gradescope dashboard and submit your personal GitHub repository link to the Homework 2 assignment. Make sure your GitHub is synchronized with Gradescope to access both your public _and_ private repositories. If prompted, log in to GitHub.

8. Run the autograder to check if your code runs and if you passed the initial unit tests. You should be able to run the autograder as many times as you want before submitting. Again, double check that your final answers are stored in the provided variable names given in the starter code!

13. Once the autograder has finished running, check that you have submitted the assignment. If you make any more changes to your code after submitting to Gradescope, make sure to push your changes to GitHub and resubmit the assignment on Gradescope. You can submit as many times as you want as there is no maximum submission attempts, but be sure to have your final submission in before the deadline.

### Working in your Notebook
   To help you start thinking about how to write meaningful and concise variable names, we have provided variable names in most of your questions. 
    Note that there is an ellipsis (the "...") after each of the variable names. These are the sections you are expected to fill in. Please use the provided variable names (ie "pelagic" and "coastal" in the above example) to report your final answer back in. This will ensure that the autograder on Gradescope runs properly. <br>
    <br>Make sure that you are adding comments and your outside references as you go along! Part of your grade will include using best coding practices in your homework assignments. 

### Honor Code

- Complete the assignment by writing and executing text and code cells as specified. For this assignment, do not use any features of Python that have not yet been discussed in the lessons or class sessions.

- Please keep in mind our late work and dropped homework grading policy. Review the syllabus for details.

- You can acknowledge and describe any assistance you've received on this assignment in the specified cell of the HW1 notebook, whether that was from an instructor, classmate (either directly or on Piazza), and/or online resources other than official Python documentation websites like docs.python.org or numpy.org. Alternatively, if you prefer, you may acknowledge assistance at the relevant point(s) in your code using a Python comment (#). Don't forget that you can receive extra credit from answering at least one question on Ed Discussion!