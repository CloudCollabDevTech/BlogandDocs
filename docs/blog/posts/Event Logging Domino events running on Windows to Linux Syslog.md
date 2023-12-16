---
date: 2023-12-11
authors: [rishabsharma]
description: >
  This blog article talks about how we can enable Event Logging for a Domino Server running on Windows to a Linux Syslog.
categories:
  - Domino
---

# Event Logging from HCL Domino server running on Windows to Linux Syslog

**This is work in progress document and shall be updated with more current information**

## Problem Definition

Recently a client of mine came to me with a request. He had opened a case with HCL Software regarding writing the Domino Log to Syslog. He wanted to do that but was not sure how to proceed. Also, the reason he wanted this capability was to utimately used some **SIEM** software to find patterns or track events.

## Existing Solution

**HCL Domino** is a fairly mature collaboration and email solution which does provide a wide range of features. **HCL Domino** already has a feature in which HCL Domino can publish events to either **syslog** or in case of Windows to the **Event Viewer**

## How to configure logging in Domino to syslog - Linux Server

## How to configure logging in Domino to Windows Event Viewer - Linux Server

## How do you redirect the Windows Event Viewer - Domino Events to Linux Syslog

![Material for MkDocs 0.1.0][Material for MkDocs 0.1.0]
