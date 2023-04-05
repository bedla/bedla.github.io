---
layout: post
title: "MSSQL and its locking of the DB objects"
categories: mssql locking
---

In this tutorial I want to show how following scenarios of MSSQL locking works in the detail:

- Lock escalation threshold detection
- Locking transaction for defined time - with MVCC
- Behavior of row locking on column with or without index

Whole content with source-code could be found here [https://github.com/bedla/mssql-locking](https://github.com/bedla/mssql-locking).
