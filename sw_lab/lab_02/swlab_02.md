# CS-181/DA-210 Software Lab 2

The goal of this SW Lab is to learn/review using dictionaries in Python to represent a key-value store, and extend that knowledge to representing 2D datasets using a Dictionary of Lists (DoL).

Throughout the course of the software lab, you'll encounter several checkpoints.  You'll need to get "check-offs" for each of these with the instructor.  During class, you can get a check-off with your partner.  If you come in to office hours later in the week, you can get a check-off either individually or with your SW Lab partner for the week.

---

## Step 0: Setup

Before you can start, you need to "pull" the updated content in the course repository.  You can do this using the following command:

```
    $ git pull origin main
```

This will result in a "merge commit", and likely open a program to type a commit message.  Depending on your Git settings, this may be in your terminal, or in a new window.  If your default is "vi" or "vim", you can type ":q" and press enter or return to leave the commit message unchanged.

The output should look like the following (note that numbers, etc. may change):

```
    $ git pull origin main
    remote: Enumerating objects: 27, done.
    remote: Counting objects: 100% (27/27), done.
    remote: Compressing objects: 100% (15/15), done.
    remote: Total 20 (delta 5), reused 20 (delta 5), pack-reused 0
    Unpacking objects: 100% (20/20), 16.49 KiB | 13.00 KiB/s, done.
    From https://github.com/amertt-denison-courses/cs181-s22
    * branch            main       -> FETCH_HEAD
    8bfc4d1..5c50b39  main       -> origin/main
    Updating 8bfc4d1..5c50b39
    Fast-forward
    hw/HW_1.c/README.md                    |   4 +-
    hw/HW_1.d/README.md                    |  39 ++
    hw/HW_1.d/functions.ipynb              | 759 +++++++++++++++++++++++++++++++++
    sw_lab/lab_02/DoL.ipynb                | 509 ++++++++++++++++++++++
    sw_lab/lab_02/dictionaries.ipynb       | 479 +++++++++++++++++++++
    sw_lab/lab_02/publicdata/tn10.csv      |  11 +
    sw_lab/lab_02/publicdata/topfemale.csv | 140 ++++++
    sw_lab/lab_02/publicdata/topnames.csv  | 279 ++++++++++++
    sw_lab/lab_02/swlab_02.md              | 100 +++++
    weekly/week_01.md                      |   6 +-
    weekly/week_02.md                      |  52 +++
    11 files changed, 2373 insertions(+), 5 deletions(-)
    create mode 100644 hw/HW_1.d/README.md
    create mode 100644 hw/HW_1.d/functions.ipynb
    create mode 100644 sw_lab/lab_02/DoL.ipynb
    create mode 100644 sw_lab/lab_02/dictionaries.ipynb
    create mode 100644 sw_lab/lab_02/publicdata/tn10.csv
    create mode 100644 sw_lab/lab_02/publicdata/topfemale.csv
    create mode 100644 sw_lab/lab_02/publicdata/topnames.csv
    create mode 100644 sw_lab/lab_02/swlab_02.md
    create mode 100644 weekly/week_02.md
```

You should now have the week 2 content!  You'll see the new folders hw/HW_1.d/ and sw_lab/lab_02/, as well as the week summary in weekly/week_02.md.  Now you're ready to go!

## Step 1: Dictionaries

First, complete Parts A-C of [dictionaries.ipynb](dictionaries.ipynb) to get some practice using dictionaries in Python.

There are two checkpoints for this step.

## Step 2: Dictionary of Lists

Next, complete Parts D-G of [DoL.ipynb](DoL.ipynb).

There are two checkpoints for this step.

## Step 3: Push your changes

Finally, let's push your changes to back up your SW Lab code to GitHub.  This isn't strictly necessary for this course, but it's a good idea to push changes you've completed in general.

Recall the general workflow, summarized here:

- Make your changes to complete the lab.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this lab and the previous, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add sw_lab/lab_01/filebasic.ipynb

    $ git add sw_lab/lab_02/dictionaries.ipynb

    $ git add sw_lab/lab_02/DoL.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this lab, you could use:

    ```
    $ git commit -m "Completed SW Labs 1+2"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository:

    ```
    $ git push -u student main
    ```