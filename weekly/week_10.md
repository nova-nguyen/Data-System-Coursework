# Planning for Week 10

## High Level Topic Summary

  - Relational Model and Structure
  - SQL Language
  - Single Table SQL
      - Access Operations (rows and columns)
      - Partitioning and Aggregation
  - Multiple Table SQL
      - Inner Joins

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Chapter 10 (all) | 10.2, 10.14, 10.15
Tuesday    | Sections 11.1-11.2 | 11.7, 11.10, 11.12
Wednesday  | Sections 11.3-11.6 | 11.69, 11.78, 11.80, 11.85
Friday     | Sections 12.1-12.3 | none

## Progression

This week, we begin the third of our data models covering the *forms* of data treated in this course, namely the *relational database model*.

Monday: We will highlight the most important aspects of the model, with its structure and typical architectures.  We will introduce and define many terms we will need over the next three weeks.  This treatment will give a glimpse at one of the core advantages of databases: **design before data population**.

Tuesday: We will begin our exploration of the SQL language, and its use in declaring the data desired from single tables in a database, starting with column projection with a local file-based SQLite database.

Wednesday: We will extend our use of SQL to include row selection, computing on column-vectors of a result, and performing partitioning and aggregation for single tables.

Friday: We will discuss using SQL to work with multiple tables via inner joins.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
HW_4.a | Wednesday (3/30) | Friday (4/1) | Single-Table SQL Filtering, Partitioning, and Aggregation
HW_4.b | Friday (4/1) | Monday (4/4) | Multiple-Table SQL Inner Joins

## Tuesday Software Lab

In the [tenth software lab](../sw_lab/lab_10/swlab_10.md), we'll introduce SQL with simple single-table column-projection operations.