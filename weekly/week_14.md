# Planning for Week 14

## High Level Topic Summary

  - Integrating Requests with Processing
    - `BytesIO` and `StringIO`
  - Application Programming Interfaces (APIs)
    - Determining HTTP
      - Parameters within HTTP
    - Data Acquisition and Processing
  - [If time] Authentication and Authorization
    - Basics of the OAuth2 "Dance"
    - Doing the dance

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Sections 21.2-21.4 | 21.17, 21.19, 21.28, 21.32, 21.40, 21.46
Tuesday    | Sections 23.1-23.2 | None
Wednesday  | Section 23.3 | None
Friday     | \[Skim\] Sections 24.1, 24.3 | None

## Progression

This week is our last full week of class!  We'll first look at processing the body of an HTTP response (e.g., as CSV, JSON, or XML).  Then, we'll explore Application Programming Interfaces (APIs), as well as authentication (AuthN) and authorization (AuthZ) if time permits.

Monday: We will discuss how to transform the body of an HTTP response into the data formats discussed in this course (CSV, JSON, XML).

Tuesday: We will introduce RESTful Application Programming Interfaces (APIs).

Wednesday: We will continue discussing APIs, including understanding the provider's requirements for requests and translating to the proper HTTP for making the requests, via a cast study.

Friday: If time permits, we will introduce the concepts of authentication (AuthN) and authorization (AuthZ), specifically via OAuth, by which a resource owner can convey permission to a client to obtain data on their behalf.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_5.c](../hw/HW_5.c/README.md) | Monday (4/25) | Wednesday (4/27) | CSV and XML request processing
HW_5.d | Wednesday (4/27) | Friday (4/29) | APIs
HW_5.e | Friday (4/29) | Monday (5/2) | OAuth

## Tuesday Software Lab

In the fourteenth software lab, we'll explore data acquisition via APIs.