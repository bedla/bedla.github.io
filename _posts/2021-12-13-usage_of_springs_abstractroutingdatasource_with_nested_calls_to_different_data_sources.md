---
layout: post
title: "Usage of Spring's AbstractRoutingDataSource with nested calls to different data sources"
categories: testcontainers postgresql docker jooq redis
---

In this tutorial I want to show what is the problem when using Spring's `AbstractRoutingDataSource` with nested calls to different data sources.

Whole content with source-code could be found here [https://github.com/bedla/spring-routing-datasource](https://github.com/bedla/spring-routing-datasource).


