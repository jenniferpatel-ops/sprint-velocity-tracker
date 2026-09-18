# Sprint Velocity Tracker

An AI-built, Jira-integrated tool that gives real-time visibility into sprint-commitment progress — built to catch stuck work before a sprint ends, not after.

**Live demo:** https://jenniferpatel-ops.github.io/sprint-velocity-tracker/

## Why I built this

I'd just onboarded a newly formed five-developer team onto Scrum from scratch, and sprint-commitment completion was landing around 60%. The problem wasn't effort rather that work was getting stuck (blocked tickets, stale reviews, handoff delays) and nobody found out until the sprint was already over. Retrospectives were reactive: diagnosing what went wrong after it was too late to fix it.

This wasn't an assigned project. I noticed the gap and built the fix myself.

## What it does

- **Two views, one dataset.** A manager view surfaces team-wide burndown and bottleneck flags; an individual view gives each developer their own pacing target — same data, no extra translation work.
- **Flags problems while the sprint is still live**, not after, so the team can course-correct instead of scrambling at sprint close.
- **Surfaces patterns, not just individual bottlenecks.** Beyond flagging a single stuck ticket, it revealed recurring patterns — requirement changes mid-sprint, last-minute scope rushes toward sprint end — that pointed to root causes instead of symptoms. That shifted conversations from "this ticket is stuck" to addressing the actual cause, with stakeholders and other teams, not just within our own.
- **Pacing that accounts for reality.** Burndown targets adjust for PTO and mid-sprint scope changes, so "on track" reflects actual working capacity, not a naive straight-line average.

## Result

Sprint-commitment completion rose from ~60% to 100% within three weeks of adoption, and held across the sprints that followed. Just as importantly, the pattern data changed the kind of conversations we were having — from reactive, ticket-by-ticket firefighting to addressing root causes with the stakeholders and teams actually driving them.

## Stack

Claude, Jira API, Chart.js

---
*This public version uses sample data and a genericized team name, sanitized from the original internal deployment.*
