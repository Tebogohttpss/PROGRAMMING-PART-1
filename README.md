# RaceDay — Part 1: System Planning and Database

## Repository Structure

```
/docs
    ERD.png                     <- exported image of the ERD (draw from docs/ERD.md's Mermaid diagram)
    ERD.md                      <- ERD entities, attributes, keys, relationships, Mermaid source
    API-Endpoint-Plan.md        <- full API endpoint planning table
    RaceDay-Database.sql        <- complete SQL Server script (schema + sample data + validation queries)

.github/
    workflows/
        validate.yml            <- CI check that the /docs folder and required files exist

README.md                       <- this file
```

## System Description

RaceDay is a web-based event management system for the South African road running,
walking and cycling community. Organisers create and manage events, categories and
results; participants browse events, enter categories, track their performance
history, and check route information ahead of race day.

## Roles

1. **Event Organiser** — creates and manages events and categories, views
   enrolments, and captures results for their own events.
2. **Participant** — browses events, enrols in categories, views their personal
   enrolment/result history, and views route information.

## CI/CD

A GitHub Actions workflow (`.github/workflows/validate.yml`) runs on every push and
pull request to `main` and checks that the `/docs` folder and all required Part 1
documents exist.

**[Insert screenshot of a successful green build here before submission]**

## Video Walkthrough

**[Insert unlisted YouTube link here]** — walks through the planning documents, ERD
decisions, endpoint plan choices, and runs the SQL script live in SSMS.
