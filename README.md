=Blooc

Finish the book together.

Blooc is a social reading app for friend groups. Pick a book with your friends, set a finish date, log your progress, and stay on pace with a weekly nudge and a spoiler-free discussion prompt.

Status: In development. This project is being built in public as a portfolio piece. Features marked "Planned" are not live yet.


Most of us have started books we never finished, and reading is usually a solo activity. Blooc makes it easy for a group of friends to read the same book at the same time, see how everyone is doing, and talk about it without spoiling the ending.

Who it's for

Friend groups of 3 to 8 people who want to read together, such as college friends, roommates, or an informal book club.

Features
Feature	Status
Create a reading group and pick a book	Planned (MVP)
Log your reading progress	Planned (MVP)
See the group's progress, with no spoilers	Planned (MVP)
Weekly nudge and discussion prompt	Planned
Invite friends with a link	Planned
"Finish party" scheduler	Planned
How it works
Sign up and create a group.
Pick a book and set a finish date together.
Log your progress as you read.
Get a gentle weekly nudge and a discussion prompt.
Finish the book and celebrate.
Tech stack
App: Next.js (React) with TypeScript
Database and login: Supabase (PostgreSQL)
Hosting: Vercel
Book data: Open Library API
Analytics: PostHog
Data analysis: Snowflake, dbt, and a Tableau Public / Looker Studio dashboard
Planning and design: Jira, Figma, Userdoc
Getting started

Setup instructions will be added once the app has its first working version.

bash


Roadmap
 User interviews and a one-page product brief
 Figma prototype, tested with real users
 MVP: groups, books, and progress tracking
 Event tracking and a data warehouse
 Analytics dashboard
 Launch with real reading groups and run an experiment
 Case study write-up
How success is measured

The main metric is the percentage of groups that finish their book by their target date. One planned experiment compares groups that receive weekly nudges with groups that don't.

Privacy and security

Reading data is personal. The app will collect only what it needs, use authenticated access to group data, and give users a way to delete their account and data. Details will be documented as features are built.