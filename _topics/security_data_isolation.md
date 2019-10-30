---
title: "Securing data by isolation"
categories: security
video_url: https://www.youtube.com/embed/ARMe9jMTwYs
excerpt_separator: <!--more-->
---

Data isolation achieved by using firewalls and networks (and in some scenarios "air gaps") to create barriers between the data storage platform and unwanted users.  

<!--more-->

### How to isolate sensitive data?

In order to describe how the information hub uses data, we define the following terms:
* Metadata - Data that describes the underlying data.  In the information hub this includes table definitions, processing rules, and basically all configuration information other than the underlying data.
* Data - Refers the the physical data.
* Information Hub Web Server - The internet based server use to login and build and manage jobs
* Remote Agent - A separately installed component which is used to connect to the databases and process data as required.



