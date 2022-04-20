# Planning for Week 13

## High Level Topic Summary

  - Introduction to Data Sources
  - Networking Basics
  - HTTP
    - Introduction to HTTP
    - `GET`, `POST` Requests
    - Request and Response Headers
  - `requests` module
  - Integrating Requests with Processing
    - Encoding
    - `BytesIO` and `StringIO`

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Chapter 18, Sections 19.1-19.2 | 19.7, 19.9, 19.10, 19.18
Tuesday    | Sections 20.1-20.2 | 20.4, 20.8
Wednesday  | Sections 19.3, 20.3 | 20.25, 20.33
Friday     | Sections 21.1-21.2 | 21.4, 21.17, 21.18

## Progression

This week, we will start Unit 5, focusing on the foundations we need to understand the data-sources dimension to this course.  This week, that will involve networking basics and HTTP.  (APIs and AuthN/AuthZ (if time permits) will be explored in Week 14.)

Monday: We will broadly discuss data sources, and then introduce the architecture and terminology involved in networking and the use of layers of protocols to decompose a difficult problem into solvable components.

Tuesday: We will begin our exploration of HTTP, which is the dominant protocol of the internet, and provides a backbone for many popular networking libraries and APIs.

Wednesday: We will discuss the client-server model and then continue exploring HTTP, focusing on different types of requests.  We will consider the HTTP method (`GET` and `POST`), the values of header key-value pairs, augmentation of the resource path with query string key-value pairs and, for `POST` requests, including a body that contains information for the request.

Friday: We will begin our discussion of HTTP responses, for which we need to be able to understand and accomodate encodings, get meta-information about the response through its headers, and process the body of the response.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 4pm) | Contents
:--|:--------|:--------|:------------
[HW_5.a](../hw/HW_5.a/README.md) | Wednesday (4/20) | Friday (4/22) | `requests` module (`GET` and `POST`)
HW_5.b | Friday (4/22) | Monday (4/25) | encoding and CSV

Note: the first homework of this unit is not due until **Friday, April 22nd**.

## Tuesday Software Lab

In the [thirteenth software lab](../sw_lab/lab_13/swlab_13.md), we'll explore HTTP fundamentals.