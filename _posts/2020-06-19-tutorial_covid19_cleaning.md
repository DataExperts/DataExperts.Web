---
layout: tutorial
sequence: 1
title: "Clean the COVID19 staging data"
categories: [tutorial,covid19]
video_url: https://www.youtube.com/embed/7grOmSY74Ho
description: Build a datalink that will clean some data quality issues with the COVID19 staging data.
excerpt_separator: <!--more-->
---

# Introduction

In this tutorial you will learn some method to clearn staging data.  There are two key parts of this data which require cleaning:

* The country names are regularly duplicated.
* There are days which have missing data, and days which have duplicate data.  These will be evened out using the series transform.

# Prerequisites

Before proceeding with the tutorial ensure that you:

* Completed the [COVID19 Staging Tutorial](/tutorial/covid19/2020/06/19/tutorial_covid19_staging.html)


# Cleaning Names

The source data has country names which have changed over the lifecycle of the data.  To see this:




