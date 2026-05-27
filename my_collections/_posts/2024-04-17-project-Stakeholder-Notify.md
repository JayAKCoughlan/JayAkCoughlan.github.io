---
layout: project
title: Project
subtitle: Stakeholder Notify Script
icon: fa-gear
date: 2024-04-17
category: project
projectNum: 8
---

This is a tool I made to automatically reach out to customers who had reported a bug when that bug had been resolved. Our process at Checkfront when a bug was reported by customers was to verify it's validity, then either create a new ticket or find an existing ticket in Jira and attach the Zendesk ticket to it using the existing plugin. This same plugin offered a feature to do this, however there were some issues with it's implementation. The first was that the connection was set up using an employee's Jira account, so the automated message would always be from that person, even though they were no longer at the company. Second, was that there was no option to only re-open a ticket, it would always reach out directly to the customer. Third, this automated response would re-open every single ticket, even if multiple were from the same customer or company. And Fourth, it wasn't able to re-open tickets that were closed and assigned to Zendesk Agents who had been removed from the system.

My solution connects to Jira over the API to find recently closed tickets based on an existing Jira filter. It then pulls the list of connected Zendesk tickets, and would re-open the tickets with an internal note. This script keeps a track of the organizations that have been responded to per-Jira ticket, so only one of them would be re-opened if multiple were attached. If the agent was removed from the system, the script would re-open the ticket and assign it to the Technical Analyst team as a default, so it could be triaged properly.

This solution saved the Technical Analyst team hours of manual work re-opening tickets every week so that we could focus on more complex user issues and escalations.