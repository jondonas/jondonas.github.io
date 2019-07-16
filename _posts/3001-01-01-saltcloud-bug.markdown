---
title: "Salt-Cloud Authentication Bug"
icon: ":beetle:"
layout: post
date: 3001-01-01 00:00 # Used for project ordering, never displayed
startDate: 2015-06-01 00:00
endDate:
tag:
github:
projects: true
category: bug-report
author: jondonas
---

While interning at iTel Networks, I found a high-severity authentication issue with Salt-Cloud. Salt-Cloud crashed when multiple ssh keys with the same name were configured on a provider such as DigitalOcean.
