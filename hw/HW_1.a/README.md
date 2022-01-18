# CS-181/DA-210 Homework 1.a

The goal of this HW is to test your computer setup and help familiarize you with the homework-submission process.

Note that you must complete this homework alone.  You should not discuss code specifics or share Jupyter notebooks with anyone.

---

## Step 1: Code

First, complete [`notebook1.ipynb`](notebook1.ipynb).  This will help you refresh your Python knowledge and make sure you can run Jupyter notebooks on your machine.

---

## Step 2: Short answers

Then, complete [`notebook2.ipynb`](notebook2.ipynb).  This notebook will introduce you to how you will respond to short-answer questions on homework in this course.  This notebook also asks you to give the time you spent on this homework.

---

## Step 3: Submission

You will submit your homework by using Git to *commit* your changes, and *pushing* them to Github.  The workflow is summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_1.a/notebook1.ipynb

    $ git add hw/HW_1.a/notebook2.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.  Here is an example of the status command and its output, after adding only one of the two `.ipynb` files to be committed:

    ```
    $ git status
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes to be committed:
    (use "git restore --staged <file>..." to unstage)
            modified:    hw/HW_1.a/notebook1.ipynb

    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
            modified:    hw/HW_1.a/notebook2.ipynb
    ```    

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 1.a"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```