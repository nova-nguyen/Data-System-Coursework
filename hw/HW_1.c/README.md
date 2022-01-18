# CS-181/DA-210 Homework 1.c

The goal of this HW is to help you review Python data structures (especially lists and dictionaries).

Note that you must complete this homework alone.  You should not discuss code specifics or share Jupyter notebooks with anyone.

---

## Step 1: Python review, continued

First, complete [`pythonbasic2.ipynb`](pythonbasic2.ipynb).  This notebook will help you continue to refresh your Ptyhon knowledge.

---

## Step 2: Python list patterns

Next, complete [`patterns.ipynb`](patterns.ipynb).  This notebook will guide you through practice with various list patterns in Python.

---


## Step 3: Dictionaries

Then, complete [`dictionaries.ipynb`](dictionaries.ipynb).  This notebook will help you review the use of dictionaries in Python.  This notebook also asks you to give the time you spent on this homework.

---

## Step 4: Submission

You will submit your homework by using Git to *commit* your changes, and *pushing* them to Github.  Recall the general workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_1.c/pythonbasic2.ipynb

    $ git add hw/HW_1.c/patterns.ipynb

    $ git add hw/HW_1.c/dictionaries.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 1.c"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```