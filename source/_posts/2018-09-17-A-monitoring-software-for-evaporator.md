---
title: A monitoring software for evaporator
mathjax: false
comments: true
author: XS Zhao
categories:
  - project
tags:
  - null
image: 'https://xsz0.com/blog/images/infinite4.gif'
abbrlink: 35698
date: 2016-09-17 16:12:40
subtitle:
keywords:
description:
---

# Introduction

With automation, configuration software, DCS, PLCs, and other industrial control tech moving fast, monitoring software built on configuration platforms has become standard in industrial control. This project is a monitoring and control system for an evaporator, built to make production more efficient and keep it safe.

I built it with Siemens WinCC, a configuration platform that makes it easy to put together operator screens, monitoring views, alarm screens, real-time and historical trend charts, and printable reports. WinCC runs on the host computer and talks to the PLC that drives the equipment on site.

Here's what the system does:

* Shows the falling film evaporator process live, with dynamic displays and on-screen controls.
* Lets operators run on-site equipment remotely and see the status of each device.
* Plots pressure over time.
* Logs operator sign-ins.
* Exports alarm history, data logs, and other records from the database.

With user permissions, alarms, and a clean interface, it takes a lot of manual work off the operators and helps the plant run more efficiently.

# Software

The project was done in Perth, Australia, and the system was used to produce concentrated carrot juice.

![](index.png)

Pressure, flow rate, and temperature are each controlled by PID loops.

![](facility.png)

![](alarm.png)

![](evaporaters.png)

![](evaporater.jpg)
