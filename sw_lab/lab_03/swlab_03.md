# CS-181/DA-210 Software Lab 3

The goal of this SW Lab is to learn how to work with 2D datasets represented as Lists of Dictionaries (LoD).

Throughout the course of the software lab, you'll encounter several checkpoints.  You'll need to get "check-offs" for each of these with the instructor.  During class, you can get a check-off with your partner.  If you come in to office hours later in the week, you can get a check-off either individually or with your SW Lab partner for the week.

---

## Step 0: Setup

Before you can start, you need to "pull" the updated content in the course repository.  You can do this using the following command:

```
    $ git pull origin main
```

This will result in a "merge commit", and likely open a program to type a commit message.  Depending on your Git settings, this may be in your terminal, or in a new window.  If your default is "vi" or "vim", you can type ":q" and press enter or return to leave the commit message unchanged.

You should now have the week 3 content!  You'll see the new folders hw/HW_1.e/, hw/HW_1.f/, and sw_lab/lab_03/, as well as the week summary in weekly/week_03.md.  Now you're ready to go!

## Step 1: Lists of Dictionaries

Complete Parts A-C of [LoD.ipynb](LoD.ipynb) to get some practice using the List-of-Dictionaries (LoD) data representation.

There are two checkpoints for this step.

## Step 2: Push your changes

Finally, let's push your changes to back up your SW Lab code to GitHub.  This isn't strictly necessary for this course, but it's a good idea to push changes you've completed in general.

Recall the general workflow, summarized here:

- Make your changes to complete the lab.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this lab and the previous, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add sw_lab/lab_03/LoD.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this lab, you could use:

    ```
    $ git commit -m "Completed SW Lab 3"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository:

    ```
    $ git push -u student main
    ```