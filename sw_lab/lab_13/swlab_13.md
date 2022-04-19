# CS-181/DA-210 Software Lab 13

The goal of this SW Lab is to gain practice with HTTP request and response messages.

Throughout the course of the software lab, you'll encounter several checkpoints.  You'll need to get "check-offs" for each of these with the instructor.  During class, you can get a check-off with your partner.  If you come in to office hours later in the week, you can get a check-off either individually or with your SW Lab partner for the week.

---

## Step 0: Setup

Before you can start, you need to "pull" the updated content in the course repository.  You can do this using the following command:

```
    $ git pull origin main
```

## Step 1: HTTP

Complete Parts A-E of [`http_intro.ipynb`](http_intro.ipynb) to explore HTTP request and response messages.

There are three checkpoints for this step.

## Step 2: Push your changes

Finally, let's push your changes to back up your SW Lab code to GitHub.  This isn't strictly necessary for this course, but it's a good idea to push changes you've completed in general.

Recall the general workflow, summarized here:

- Make your changes to complete the lab.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this lab and the previous, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add sw_lab/lab_13/http_intro.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this lab, you could use:

    ```
    $ git commit -m "Completed SW Lab 13"
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository:

    ```
    $ git push -u student main
    ```