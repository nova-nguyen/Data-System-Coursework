# Planning for Week 5

## High Level Topic Summary

  - Tabular Data Model
    - Access Operations (cont'd)
  - Advanced Operations in the Tabular Model
      - Mutations
      - Aggregating Data
      - Grouping Data
      - Combining Tables
      - Missing Data

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Sections 7.3.3-7.3.6          | 7.25, 7.26, 7.31
Tuesday    | Section 8.2 | none
Wednesday  | Section 8.1  | none
Friday     | Sections 8.3-8.4 | none

## Progression

This week we will continue with basic tabular operations, and also explore advanced tabular operations of aggregation, mutation, and combining tables.

Monday: Consider row selection and more complex row and column combinations.  Also discuss procedural access to `DataFrame`s through iteration.

Tuesday: Complete software lab focusing on mutations to change values, delete rows or columns, add rows and columns, and even conditionally update values for only some rows.

Wednesday: Explore aggregation, starting with simple aggregation of column vectors, and proceeding to variations (uniform and non-uniform) aggregating on subsets of columns in a dataframe.  If time permits, we'll extend this to group partitioning and GroupBy.

Friday: Discuss combining tables, extending to integrating combining tables with join and merge operations.  We will also see some operations that allow us to deal with missing data.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_2.c](../hw/HW_2.c/README.md) | Monday (2/14) | Wednesday (2/16) | Row selection, complex access combinations
HW_2.d | Wednesday (2/16) | Friday (2/18) | Aggregation and GroupBy
HW_2.e | Friday (2/18) | Monday (2/21)    | Table combining and missing data

## Tuesday Software Lab

In the [fifth software lab](../sw_lab/lab_05/swlab_05.md), we'll explore our first advanced tabular operation: mutation.  We'll look at deleting one or more columns or rows, adding a column to an existing `DataFrame`, and updating all or some values within an existng column.