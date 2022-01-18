# CS-181/DA-210 Setup: Git

> There are several "checkpoints" mentioned in these instructions.  If you work through this before Software Lab 1, you still need to complete the checkpoints, either during the Tuesday lab or in office hours.

---

## Part A: Installation of `Git`

`Git` is the software that underlies [GitHub](https://www.github.com) as well as other systems of software that support controlled version control and distribution of collections of files.  We will be using Git and GitHub as our primary means of providing files/documents/notebooks to be used for classwork and for homework.

`Git` is a collection of command-line and system functions, and does not, by itself, provide a graphical interface.  We install it first so that subsequent steps have the software we need.

### Windows Platform

The `git` software for the windows platform can be obtained from https://gitforwindows.org/ and contains both the underlying software, as well as a GUI for dealing with repositories and a version of a shell to give a more powerful command-line interface.

Download the software and run the resultant download.  If you already use git repositories and/or have needs outside of this class for uploading new versions of files to GitHub, you may want to customize some of your responses during the install.  Otherwise, the defaults should be sufficient for the needs of the CS-181/DA-210 class.

Once installed, you will see an entry in the Start Menu that contains shortcuts for launching the GUI, and for launching the shell, known as *Git Bash*.

### Mac/Linux Platforms

You can check if `git` is already installed by opening a Terminal window and using the command-line (note that the "$" is the prompt, and you should not type that part):
```bash
$ git --version
```

If the result is something like the following:
```
git version 2.33.0
```
then `git` is already installed.  If the version is recent, you need not modify your git installation.  If you get a response like `Command Not Found`, or if the git version is way out of date, you should install `git`.  You can also choose to install a GUI that helps use `git`, but a `git` GUI is beyond the scope of these instructions (come to office hours if you want to get one set up).

Navigate to [https://git-scm.com/downloads](https://git-scm.com/downloads) and download the version of git, as appropriate for your OS X or Linux platform by clicking the name of your platform.  If needed, click the "start download manually" and proceeding through the download screen.  When the download is complete, open the downloaded file and follow the instructions.

### Setup (all platforms)

Finally, you should go to a command line and set your `git` username and email.  The command is as follows:
```bash
$ git config --global user.name "Jane Doe"
$ git config --global user.email "doej@denison.edu"
```

Note that this sets the username and email for all repositories on your machine.  If you already use `git` with another account, you may want to skip this step.

---

## Part B: `GitHub` Account Creation

`GitHub` is an organization that hosts project repositories and is used by professionals and students to collaborate, sharing files/software/documentation and using `git` to allow coordination and version control for those activities.

If you do not already have one, create a `GitHub` account/identity.  You can get a free account, and as a student you can sign up for a "Student Pack" that provides access to some additional software and resources (not necessary for this course, but nice to have).

  - General free GitHub account signup: [GitHub Login](https://github.com/join)
  - Student Pack signup (skip this for now): [GitHub Student Pack](https://education.github.com/pack/join)

Unless you have a justifiable reason not to, use your Denison email address.  The GitHub username can be anything you like, as long as it is not already taken, but please be appropriate, because your instructor will be using this username to *invite* you to gain access to the course repository.

You will have to establish that you are a human, not a robot, and to verify your email as part of the process of creating a GitHub identity.

> If you are following these instructions as part of Software Lab 1, this is the first checkpoint in the lab.  Make sure to have it signed off by the instructor.
>
> Checkpoint 1: What is your GitHub username?

You will receive, by email, an invitation to the repository.  Follow the link and accept the invitation **before** you proceed to the next step.

---

## Part C: Local Folder Organization and Repository Clone

We encourage you to *think* and *organize* before you dive in and start creating class-based files and directories/folders in a haphazard way on your local computer.

As we should have learned from our Intro CS course, each user logged in to a computer has a **Home** directory.<sup>1</sup>  If your login username is *sadie*, our home directory on a Mac system might be:
```
/Users/sadie
```
while on a Linux system it might be
```
/users/sadie
```
or
```
/home/sadie
```
and on a Windows machine, it might be
```
C:\Users\sadie
```

The string we use to refer to a directory or a file is known as its **path**.  Different systems use different separators between directory and file elements in the path (`\` versus `/`).  Some systems also permit special characters or sequences to have meaning in interpreting a path.
- `~` typically can be used as a substitute for the current logged in user's home directory
- `..` means the parent of the ''current'' directory, where the notion of a current directory is maintained by the engine executing code (like a Python script or notebook) or the Terminal or Command window in which the path specification is being used.

One organization that makes sense for local files on your computer supporting multiple classes in a college setting is, within your home directory, use a directory for each individual class that you take, like `cs112` and `cs181`.  You might also decide, if you use a sync'd cloud storage solution, to use a similar organization, but under `Dropbox` or something similar.  You could also choose to create your class directories under `Documents` or `My Documents`.

Please, **do not** combine files from multiple classes into the same directory.  Also, once we have created a local copy (a clone) of the files being given to you as part of the class distribution, it would be best if you keep other class files *separate* from the class repository.

> On your local computer, decide on your organization and create directories based on what you have decided.  For the following discussion, we will assume that your login is `sadie`, and you have decided on the above suggested organization, so the full path for your cs181 class materials would be
```
/Users/sadie/cs181
```
> for the above Mac OS example.
>
> How you accomplish this organizational creation depends on your platform.  On Mac OS, you use a Finder window and can select the `Go` menu and then select `Home` to get a view on your home directory.  On Windows, you open a Windows Explorer window (typically by clicking the Folder icon on the taskbar) and Navigate from `Computer` or `My PC` (the root of the file system) to your login/username folder.  You can then use menu selection to create new folders and double click and repeat to create subfolders.

> Hint: To make the steps below easier, avoid spaces in the names of your directories, and avoid getting too complex an organization.


### GitHub Clone of `amertt-denison-courses/cs181-s22` repository

One of the primary means of delivering material to students in this class will be through a GitHub repository named `cs181-s22`.  When one creates a local copy of the directories and files in a Git repository for the *first time*, this action is called a **clone**.

Our goal is to clone the repository and for the destination of the clone to be on your local computer within the `cs181` folder you created above.  There are two prerequsite steps:

1. Make sure you have registered and created your GitHub username.
2. Give your GitHub username to your instructor, who owns the `cs181-s22` repository and needs to add you as a valid user of the repository.  You can go to [https://github.com/notifications](https://github.com/notifications) to accept the invitation, and then [https://github.com/amertt-denison-courses/cs181-s22](https://github.com/amertt-denison-courses/cs181-s22) if you want to view the repository online.

   > When you are ready for this step, make sure you have already given your instructor your GitHub username so that you can be added to the repository.

Now you are ready to use `git` to clone the repository from GitHub.

1. Open a Terminal (on Mac/Linux) or Windows Powershell or Anaconda Powershell Prompt (on Windows) command line window.
   - Once open, type the command `pwd` ("print working directory") at the prompt.  You should see the terminal respond with your home directory.  From the perspective of the terminal, this is your "current" directory.

2. You need to get your terminal so that the current directory is your class folder, as created above.  Relative to the result of `pwd`, the path to get to your class folder will depend on the organization you decided on above.  For the example above, the relative path is `cs181` (note the absence of a leading slash, which would indicate a path that starts at the root of the filesystem).

   - Determine your relative path from the (home) directory obtained above, and your class folder (i.e., what is your equivalent of `cs181`?).
   - In your terminal, type the command `cd` ("change directory") followed, on the some line, by the relative path to your class folder:
   ```
   $ cd cs181
   ```
   If the `cs181` folder were created under `Documents`, the command might be:
   ```
   $ cd Documents/cs181
   ```
  - If I execute `pwd` in the terminal, I should now get the full path of my course directory.  If you do, then you are ready to proceed to the next step.

3. Execute the following in your terminal:
   ```
   $ git clone https://github.com/amertt-denison-courses/cs181-s22.git cs181-s22-repo
   ```
   This step can only succeed if the prerequisite steps have all been successful.

   On successful execution, you will be asked for your GitHub username and password, and the system will report the cloning and unpacking operations.  It should look something like this:
   ```
   Cloning into 'cs181-s22-repo'...
   remote: Enumerating objects: 92, done.
   remote: Counting objects: 100% (92/92), done.
   remote: Compressing objects: 100% (54/54), done.
   Receiving objects:  59% (55/92)used 86 (delta 24), pack-reused 0Receiving objects:  56% (52/92)
   Receiving objects: 100% (92/92), 48.79 KiB | 1.28 MiB/s, done.
   Resolving deltas: 100% (30/30), done.
   ```

   The end result will be a directory named `cs181-s22-repo` *within* your class folder.  You should navigate into this directory and get a sense of its organization.  Try doing the following in the terminal:
   ```
   $ cd cs181-s22-repo
   $ ls
   ```
   (The `ls` is the command to *list* the contents of the current directory. If you're using Windows, you may need to use `dir` instead.)  Does what you see make sense?  You should see entries for `general`, a directory for files like these setup instructions, as well as a folder named `hw`, which is where all the files needed for you to complete homework assignments will be kept.

> If you are following these instructions as part of Software Lab 1, this is the second checkpoint in the lab.  Make sure to have it signed off by the instructor.
>
> Checkpoint 2: How many directories are there in the `cs181-s22` repository?

---

## Part D: Pushing Changes to Your Repository

To submit homework in this course, you will need to package changes into a *commit*, which you will then *push* to a private repository.  Thus, you'll always *pull* from the instructor's repository (to get new homework, etc.) and *push* to your own private repository.

### Creating your own repository

You'll need to create your own private repository on GitHub.  To do this, go to your profile page on Github: `https://github.com/<username>?tab=repositories`, where `<username>` is your Github username.  Then, click the green "New" button.  Choose the name you want (`cs181-s22-student` is a good, simple choice), and **make sure the repository is set to "private"**. Click "Create repository", and you now have your very own (empty) repository!

You should now see a webpage that says "Quick setup -- if you've done this thing before" at the top.  Next, we'll push the content to your repository.

### Pushing to your repository

You need to add your new repository URL as a "remote" location for `git`.  First, check the remote locations you already have:

```bash
$ git remote -v
origin https://github.com/amertt-denison-courses/cs181-s22.git (fetch)
origin https://github.com/amertt-denison-courses/cs181-s22.git (push)
```

We'll add another remote for your new repository (again, `<username>` should be replaced with your username):

```bash
$ git remote add student https://github.com/<username>/cs181-s22-student.git
```

You can check if it worked:

```bash
$ git remote -v
origin https://github.com/amertt-denison-courses/cs181-s22.git (fetch)
origin https://github.com/amertt-denison-courses/cs181-s22.git (push)
student https://github.com/<username>/cs181-s22-student.git (fetch)
student https://github.com/<username>/cs181-s22-student.git (push)
```

Now that you've got your repository listed as a "remote", you can push to it!  The following command pushes to the remote named `student` (from the list above), with the "branch" `main`.  (You don't have to worry about branches, but if you read any `git` documentation/tutorials you will see the word.)

```bash
$ git push -u student main
```

If you go to your repository online, you should now see a list of folders.  You can use this interface to navigate through the repository.  (This is a good way to verify that you've correctly submitted your assignments, in fact!)

### Add your instructor as a collaborator

Finally, you should add your instructor as a collaborator to your repository.  This is how your homework will be accessed for grading.

1. Navigate to your repository's settings page: https://github.com/<username>/cs181-s22-student/settings/access.

2. Click the green "Add people" button.

3. Enter "amertt-denison" and click "Add amertt-denison to this repository".

That's it, you did it!

<sup>1</sup> The terms **directories** and **folders** refer to the same thing, a location in the file system on a computer in which we can organize both **files** as well as other (sub)directories in a hierarchical fashion.  Those who work in the **systems** subfield of computer science use the term directory, while many users, based on their experience in the GUI metaphor of a desktop, use the term folder.
