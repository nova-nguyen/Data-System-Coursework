# Planning for Week 11

## High Level Topic Summary

  - Multiple Table SQL
      - Inner and Outer Joins
      - Partitioning and Aggregation of Joined Data
      - Subqueries in Multi-Table Operations
  - Relational Database Programming
  - Python Database Programming

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Sections 12.1-12.3.1 | none
Tuesday    | Sections 12.3.3-12.6 | none
Wednesday  | Sections 13.1-13.2, 13.4 | none
Friday     | Sections 13.3 | none

## Progression

This week, we will consider multi-table SQL expressions, and then develop the abstractions, interface, and techniques for relational database programming.

Monday: We will introduce the SQL syntax for performing inner joins between tables in a relational database.

Tuesday: We will see how these composite/joined table give us additional power when we do group by and aggregation, and also how we can use a subquery, often which contains a joined table, as part of a larger query.

Wednesday: We will integrate what we have learned in SQL with the programmatic techniques of "making it happen" in Python, when we are not using SQL magics or third-party client tools.

Friday: We will finish exploring advanced relational DB programming concepts, including fetching a subset of resultant records for each query, and working with multiple databases.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_4.c](../hw/HW_4.c/README.md) | Monday (4/4) | Wednesday (4/6) | `school` database and multi-table inner joins
HW 4.d | Wednesday (4/6) | Friday (4/8) | Python database programming, part 1
HW 4.e | Friday (4/8) | Monday (4/11) | Python database programming, part 2

## Tuesday Software Lab

In the eleventh software lab, we'll explore multi-table SQL queries, including more complex inner joins, outer joins, partitioning, and subqueries.