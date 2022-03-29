---
title: "Forensic Tools"
icon: ":mag_right:"
layout: post
date: 1104-01-01 00:00 # Used for project ordering, never displayed
startDate: 2016-05-01 00:00
endDate: 2016-008-01 00:00
tag: [python, nodejs, aws, html/css]
github: https://github.com/jondonas/forensic-tools
projects: true
category: open-source
author: jondonas
---

In the summer of 2016, I developed a collection of penetration testing, analytics, and forensic tools.

### IP Checker:

* Uses VirusTotal, location, spam blacklist, and registrar data to determine if a given IP is associated with malicious material.

<kbd><img src="/assets/images/ip_checker.png" width="500" style="border: 1px solid #ddd; display: block; margin-left: auto; margin-right: auto;"></kbd>

### Disk Analyzer:

* Queries multiple tools such as VirusTotal, WildFire, ClamAV, and NSRL to perform deep analysis on a forensic disk image.

<kbd><img src="/assets/images/disk_analyzer.png" width="500" style="border: 1px solid #ddd; display: block; margin-left: auto; margin-right: auto;"></kbd>

### Tor Web Crawler

* Connects to the Tor network and does web scraping for email addresses.
* Follows links on webpages so it can quickly find data for a specific domain.

### dnmap

* Builds a master-slave dnmap implementation to provide distributed port scanning for load-balancing and covert reconnaissance.
* Uses SaltStack to build, start, or destroy an arbitrary number of AWS scanner slaves with a single command. 
