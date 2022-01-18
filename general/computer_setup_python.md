# CS-181/DA-210 Setup: Python

## Part A: Installation of `Anaconda`

If you already have Anaconda installed on your computer, use the following instructions to upgrade, otherwise, skip ahead to the **New Installation** instructions below.

### Upgrade an Existing Install

If you already have Anaconda installed, you should upgrade to the most recent version of the packages that are compatible with Python 3.9.  The easiest way to do this is to open a Terminal (MacOS and Linux) or Anaconda Powershell Prompt (Windows) command line window. If you have trouble with the command-line on your particular platform, you can launch Ananconda-Navigator, then launch JupyterLab, click the left-hand "plus" symbol (or, from the menu, File->New Launcher), and then click on "Terminal".

From the command-line, enter the following:
```bash
$ conda update conda
$ conda install python=3.9
$ conda update ananconda
$ conda update jupyterlab
```

Note that, in showing command line commands, the `$` represents the command line prompt, which is often prefixed with text showing the host, the current user, and/or the current working directory.  You **do not** type the dollar sign when entering commands, only the text that follows.

Check the set of packages that will be installed and, if there is no risk to your current environment, go ahead and hit `<enter>` or type `Y` followed by `<enter>` to proceed with the install.

Once the install is complete, you should check the version on, at least, the `jupyterlab` package.  As of the time of this writing, the version used by your instructor is `1.1.4`, and can be checked by the following:

```bash
$ conda list jupyterlab
```

For me, this results in the following output:
```
# packages in environment at C:\Users\Tanya\anaconda3:
#
# Name                    Version                   Build  Channel
jupyterlab                3.2.1              pyhd3eb1b0_1
jupyterlab_pygments       0.1.2                      py_0
jupyterlab_server         2.8.2              pyhd3eb1b0_0
jupyterlab_widgets        1.0.0              pyhd3eb1b0_1
```
The version of a package is in the second column.

If you need to keep a current configuration and create a separate environment to use for your CS-181/DA-210 work, please see your instructor, possibly setting up a time during office hours to complete a separate installation.

### New Installation of Anaconda

Navigate to [https://www.anaconda.com/distribution](https://www.anaconda.com/distribution) and download the version appropriate to your platform.

When the download is complete, open the downloaded file to begin the installation.

- When in doubt, or if not an advanced user, select the defaults.
- A typical installation installs for *only* the current user in a location underneath the user's *home* directory.

Portions of this install can take significant time.  On Windows, the step "Setting up the package cache" is quite lengthy.  Do not cancel the operation.  You can click on the "Details" button to see the ongoing progress.

If you need to uninstall, see the Anaconda web pages, as they have specific instructions for each platform.

---

## Part B: Command/Terminal Window

After installation of Anaconda, you should be able to perform command-line operations.  For Mac users, these occur in the `Terminal` application.  For Windows users, you should use the `Anaconda Powershell Prompt` application installed as part of Anaconda.  Based on your platform, use the following instructions to launch a command-line window and then execute the command: `conda list` to verify your installation.

Do **not** skip this step, as our cloning of the class repository will happen through this command-line interface.

### Mac platform

- Click on the magnifying-glass icon and search for **Terminal** and accept the found result.
- When you see a "command prompt" (line ending in `$` with a cursor insertion point following) type in `conda list`.
- Tip: Right-Click on the `Terminal` icon in the dock and select "Options->Keep In Dock".

### Window platform
- Navigate in the Start Menu to `Anaconda Powershell Prompt`.
  - When you see a "command prompt" (line ending in `$` or `>` with a cursor insertion point following) type in `conda list`.
- Tip: Right-Click on the `Powershell` icon in the taskbar and select "Pin to taskbar".

If you get a list of packages with package version, then Anaconda was installed properly.  If not, let your instructor know.

---

## Part C: Launch Jupyter Lab

The installation will also have given you a GUI, known as `Anaconda Navigator`, by which you can launch the Jupyter Lab notebook development environment.  This runs in a tab in your default browser.

When using the GUI, you can shut down the development environment and return all resources by going to the `File` menu in the Jupyter Lab browser tab and selecting `Shut Down` and then closing the browser window.  You should **always** cleanly exit by performing this sequence.

You can also launch Jupyter Lab by the following command in a Terminal/Anaconda Powershell Prompt command-line:
```bash
$ jupyter lab
```
As with the GUI launch, you shut down the environment and return all resources by going to the `File` menu and selecting `Shut Down` and then closing the browser window.  You should **always** cleanly exit by performing this sequence.

Make sure you can launch Jupyter Lab by either the Navigator or by the command line.