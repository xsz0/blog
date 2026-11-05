---
title: Freescale Smart Car Race
mathjax: false
comments: true
author: XS Zhao
categories:
  - project
tags:
  - null
image: 'https://xsz0.com/blog/images/infinite4.gif'
abbrlink: 64929
date: 2016-08-30 16:47:51
subtitle:
keywords:
description:
---

# Introduction

The Freescale Cup (originally called the Smart Car Race) started in 2003 at Hanyang University in Korea with 80 student teams. It has since grown into an annual event across North America, Europe, China, India, Malaysia, and Latin America, with more than 15,000 students from over 500 schools taking part.

The idea is simple: build a small autonomous car, program it, and race it around a track. The fastest car that finishes without leaving the track wins. Every team starts from a kit of Freescale parts, then designs its own motor control hardware and software to drive and steer the car, plus a camera interface so the car can see the track and find its way around.

I joined the Southeast University (China) team in 2010. In 2011 I took over as team leader, and we won `1st prize` in the camera group at the 7th Freescale Cup National University Students Smart Car Race.

# The Car

I handled the circuit board design and the software. I wrote the core track-detection algorithm, and my teammates helped tune the PID control parameters.

![car](model.png)

![video](smart_car.gif)
