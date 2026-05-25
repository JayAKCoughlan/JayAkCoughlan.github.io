---
layout: project
title: Project
subtitle: Zephyr Sprint Setup Script
icon: fa-gear
projectNum: 6
---

I made this tool while working as a QA Automation Developer. Our processes every other week required us to mirror the tickets taken on by the development team each sprint in Zephyr. This was so we could use Zephyr to adequately track QA testing and assign new or existing tests and test plans to tickets as appropriate. This was a manual process that took hours every other week and was prone to errors.

My tool looks at the Jira kanban boards for each team copies the ticket details into new Zephyr tickets in a new sprint folder, organized per-team. It will even check previous sprints if a Jira ticket has been carried over and will move the existing Zephyr ticket, instead of creating a new one.

This tool saved the team hours of work and reduced mistakes, which allowed us to focus on testing and refining other processes.