# CS-181/DA-210 Software Lab 12

The goal of this SW Lab is to practice programmatic access to SQL databases, including queries, table creation, and table population.

Throughout the course of the software lab, you'll encounter several checkpoints.  You'll need to get "check-offs" for each of these with the instructor.  During class, you can get a check-off with your partner.  If you come in to office hours later in the week, you can get a check-off either individually or with your SW Lab partner for the week.

---

## Step 0: Setup

Before you can start, you need to "pull" the updated content in the course repository.  You can do this using the following command:

```
    $ git pull origin main
```

## Step 1: Connecting using `sqlalchemy`

Complete Parts A-C of [`db_prog_connect.ipynb`](db_prog_connect.ipynb) to explore using the `sqlalchemy` Python library to access SQL databases.

There is one checkpoint for this step.

## Step 2: Using variables in SQL queries

Complete Part D of [`db_prog_vars.ipynb`](db_prog_vars.ipynb) to learn how to use variables in SQL statements with `sqlalchemy`.

There are no checkpoints for this step, but you are still expected to work through the examples and questions.

## Step 3: Table creation and population

Complete Parts E-H of [`db_create_pop.ipynb`](db_create_pop.ipynb) to explore table creation and population, both focusing just on SQL statements and executing those statements using `sqlalchemy` with bound variables.

## Step 4: Push your changes

Finally, let's push your changes to back up your SW Lab code to GitHub.  This isn't strictly necessary for this course, but it's a good idea to push changes you've completed in general.

Recall the general workflow, summarized here:

- Make your changes to complete the lab.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this lab and the previous, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add sw_lab/lab_12/db_prog_connect.ipynb
    
    $ git add sw_lab/lab_12/db_prog_vars.ipynb
    
    $ git add sw_lab/lab_12/db_create_pop.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this lab, you could use:

    ```
    $ git commit -m "Completed SW Lab 12"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository:

    ```
    $ git push -u student main
    ```