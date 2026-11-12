+++
title = 'Technical Details'
description = 'System requirements, how the program is built, integrations, privacy, and accessibility.'
date = 2026-11-05
type = 'page'
weight = 10
ShowToc = true
authors = ['Junior']
tags = ['technical', 'privacy', 'integrations']
+++

This page is for school IT staff and administrators. It covers what the program needs to run, how it fits with the systems your school already uses, and how it handles student data.

## System requirements

The program runs in a web browser, so there is nothing to install on student devices. It works on Chromebooks, Windows and Mac laptops, and iPads using a current version of Chrome, Edge, Safari, or Firefox. Each student needs a steady connection of about 1 Mbps during a lesson. An offline mode lets students keep working on a downloaded practice set if the network drops, and their work syncs when the connection comes back.

## How it is built

The program has three main parts. The **learning engine** tracks each student's mastery of every skill and decides what task comes next. The **AI tutor** is a language model that writes hints and follow-up questions, but it only works inside the current lesson and is instructed never to hand over a final answer. The **teacher dashboard** reads from the learning engine and turns the data into groups, reports, and alerts.

The tutor is grounded in the curriculum. It sees the question, the student's work so far, and the teacher's settings, and nothing from the open internet. That keeps its hints on topic and age appropriate.

## Integrations

Most schools connect the program to tools they already have:

| System | What the integration does |
|---|---|
| Canvas, Schoology | Launches lessons inside the course and sends scores to the gradebook (LTI 1.3) |
| Google Classroom | Imports class rosters and posts assignments |
| Clever, ClassLink | Single sign-on and automatic roster updates |
| Student information systems | Nightly roster sync through OneRoster |

## Privacy and security

Student data belongs to the school. The program collects only what it needs to teach: names, class enrollment, and the work students do in lessons. It never sells data or uses it for advertising, and student work is not used to train outside AI models.

The program is designed to meet the requirements of FERPA and COPPA, and the company signs each state's student data privacy agreement where one exists. All data is encrypted in transit and at rest. Districts can export or delete their data at any time, and student accounts are removed automatically 90 days after a license ends unless the district asks to keep them longer.

## Accessibility

Every screen is built to WCAG 2.1 AA. Questions and hints can be read aloud, text can be enlarged without breaking the layout, and every activity works with a keyboard and common screen readers. Teachers can turn on extended time and reduced-distraction mode for individual students to support IEP and 504 accommodations.

{{< callout title="Need a security review?" >}}
IT teams can request the full security packet, including the data flow diagram and the latest third-party audit summary, from the [licensing page](/signup/licensing/).
{{< /callout >}}
