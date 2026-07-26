---
title: M365 Support & Onboarding Runbook — MAF
date: 2026-07-26 10:00:00 +0300
categories: [Projects, M365]
tags: [microsoft365, admin, support, remote-teams]
---

Documentation of the Microsoft 365 administration and first-line support work I perform as Technology & Digital Systems Support at Malcolms Anatomy Foundation (MAF), a remote-first international health nonprofit.

## Purpose

This runbook captures the standard process I follow for user onboarding and initial support triage on MAF's M365 tenant, based on tasks actually performed since joining the team.

## User Onboarding

**Trigger:** Request from team lead for a new staff/volunteer account.

**Process:**
1. Create the user account in Microsoft 365 Admin Center
2. Assign the appropriate license
3. Verify account details are correct
4. Send onboarding email via Outlook with login details
5. Confirm completion with the requesting team lead

I've handled this process independently on multiple occasions, including under time pressure when requests came in as urgent. One improvement I've identified: building a simple onboarding checklist to keep the process consistent regardless of urgency.

## First-Line Support: Troubleshooting Example

**Issue:** A user reported a Microsoft Teams sign-in problem.

**Steps taken:**
- Reviewed the user's account settings in the Admin Center
- Verified license assignment and account status
- Gathered details on the specific error the user experienced

**Outcome:** Initial diagnostics ruled out license and account-status issues. Deeper investigation required Microsoft Entra sign-in logs, which I didn't have access to at the time — I escalated with my findings so far rather than guessing at a fix.

**Takeaway:** Not every issue resolves at first-line level, and knowing when to escalate with clear documentation is part of doing the job properly. I've since started documenting troubleshooting steps as I go, to make future investigations faster.

## Other Digital Systems Support

Alongside core M365 admin, I support MAF's broader digital operations:
- Distributing internal training materials via Microsoft Teams as part of recurring knowledge-sharing sessions
- Maintaining team member profile information on the organization's website
- Completed training on the foundation's digital measurement infrastructure (Google Analytics, Google Tag Manager, Search Console) to support future site performance monitoring

## What I'd Build Next

- A standardized onboarding checklist to reduce variance across urgent vs. routine requests
- Formal documentation template for troubleshooting steps, captured in real time rather than after the fact
- Request expanded access to Entra sign-in logs to close the gap on the Teams sign-in investigation

[Back to Projects](/)
