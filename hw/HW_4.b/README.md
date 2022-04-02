# CS-181/DA-210 Homework 4.b

The goal of this HW is to help you continue practicing working with single-table SQL queries.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of single_groupby.ipynb.**

---

## Step 1: Column-Vector Operations

Complete [`single_column_ops.ipynb`](single_column_ops.ipynb).  This notebook contains exercises to practice SQL queries to perform column-vector operations when building a SQL query.

---

## Step 2: Aggregation and GroupBy

Complete [`single_groupby.ipynb`](single_groupby.ipynb).  This notebook contains exercises to practice SQL queries to group data in a single SQL table and aggregate based on the results.

## Step 3: Submission

Recall the general submission workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_4.b/single_column_ops.ipynb

    $ git add hw/HW_4.b/single_groupby.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 4.b"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```