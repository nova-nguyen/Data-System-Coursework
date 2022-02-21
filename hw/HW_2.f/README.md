# CS-181/DA-210 Homework 2.f

The goal of this HW is to help you practice transpose and melt operations to transform tables in `pandas`.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of agg_group.ipynb.**

---

## Step 1: Transforming tables via transpose and melt

Complete [`transpose_melt.ipynb`](transpose_melt.ipynb).  This notebook contains exercises using `transpose` and `melt` operations to transform `pandas DataFrame`s.

---

## Step 2: Normalizing data sets

Complete [`normalize1.ipynb`](normalize1.ipynb).  This notebook contains exercises using `melt` to normalize datasets, resulting in tidy data stored as `pandas DataFrame`s.

---

## Step 3: Submission

Recall the general submission workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_2.f/transpose_melt.ipynb

    $ git add hw/HW_2.f/normalize1.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 2.f"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```