---
title: IT Helpdesk Ticketing System
date: 2026-07-26 10:00:00 +0300
categories: [Projects, Systems]
tags: [helpdesk, support, react, nodejs, mysql]
---

A full-stack IT support ticketing system built with React, Node.js, Express, and MySQL — modeling a real support workflow from ticket creation through resolution.

## Problem

IT support teams need a way to track, prioritize, and resolve issues without losing context. This project models that workflow end-to-end: role-based access, ticket lifecycle management, and live reporting.

## Features

- JWT authentication with role-based access (Admin, Agent, User)
- Full ticket lifecycle — Open → In Progress → Resolved → Closed
- Priority levels — Low, Medium, High, Critical
- Search and filter tickets by status and priority
- Comment system on tickets
- Dashboard with live stats
- User management panel
- Dark mode UI

## Tech Stack

**Frontend:** React 18, Vite, React Router, Axios, Lucide React
**Backend:** Node.js, Express.js
**Database:** MySQL
**Auth:** JWT, bcryptjs

## What I'd Add Next

- SLA tracking with automated escalation
- Email notifications on ticket status changes
- Reporting export (CSV/PDF)

[View the full repo](https://github.com/jedasamba/helpdesk-app)
