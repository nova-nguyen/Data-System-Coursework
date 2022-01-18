# Planning for Week 1

## High Level Topic Summary

  - Introduction and motivation
  - File systems and how to open/close/read/readline/split files
  - \[Review\] Lists and Dictionaries

## Readings for the week

Day        | Reading      | Warm-Up Questions*
:--------- |:-------------|:----------------------------------
Monday     | Syllabus, Preface |
Tuesday    | All of Chapter 1; Section 2.1 | 2.4, 2.7, 2.9
Wednesday  | Sections 2.2 and 2.3 | 2.21, 2.23, 2.28, 2.54
Friday     | Sections 3.1 and 3.2 | 3.1, 3.7, 3.10, 3.35

\*You do not have to turn in answers to these questions, but you are expected to do the reading and ponder the questions before the start of class.

## Progression

The goal for this week is to review and set up for Week 2 on 2D representations of data and new topics of list comprehensions and lambda functions.

- Monday: Go over the course syllabus, discuss our high-level learning objectives for the semester, and introduce our use of GitHub in preparation for the first software lab.
- Tuesday: Have the first software lab, in which we get everyone set up with Git and GitHub, explore the file/path hierarchy in operating systems, and then review programmatic access in `os`/`os.path` calls from Tables 2.3 and 2.4.
- Wednesday: Review how to use Python to open and close files and parse file contents line by line.
- Friday: Refresh various Python patterns (e.g., accumulation) using lists and dictionaries.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_1.a](../hw/HW_1.a/README.md) | Monday | Friday (1/21)** | Short two notebook set
[HW_1.b](../hw/HW_1.b/README.md) | Wednesday | Friday (1/21) | Python review
[HW_1.c](../hw/HW_1.c/README.md) | Friday | Wednesday (1/26) | List patterns and dictionaries

\**Homework assignments will typically be due the M/W/F following the class in which they are assigned.  There is extra leniency in Week 1 while we get set up with Git.  However, HW_1.a is primarily a simple test of your computer setup and the homework-submission workflow, so you should try to submit it by Wednesday, and not put it off for Friday.

## Tuesday Software Lab

This [first software lab](../sw_lab/lab_01/swlab_01.md) walks you through your computer and Git setup, which is necessary to use `git pull` to get class resources.  Then, you'll explore a file system using the command line (a.k.a the "terminal") and Python's `os` module.

---

## Prerequisite Concepts and References

DCS is **Discovering Computer Science** by Jessen Havill (i.e., your textbook from Intro CS).

- int, float, str data types: DCS 2.2
- integer specific operations `//` and `%`: DCS 2.2
- functional abstraction, namespaces, scope, return vs print: DCS 3.3, 3.5, 3.6
- docstrings: DCS 3.4
- scalar accumulation pattern: DCS 4.1
- string `.format()` method: DCS 4.1
- list accumulation pattern: DCS 4.2
- file system hierarchy: DCS 6.2
- text file open/close/read/readline: DCS 6.2
- string immutability: DCS 6.3
- list patterns: DCS 8.1, 8.2
- list mutability: DCS 8.2
- dictionaries: DCS 8.3
- multiple data items per line of file: DCS 8.4

For next week:

- list comprehensions: DCS 8.2
- tuples: DCS 8.2
- 2D representations: DCS: chapter 9
