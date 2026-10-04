<!--
  Showcase README for the public repo arman-mahabad/meds.krd.
  The code lives in a private repo. This repo holds only this page and its pictures.
-->

<sub><a href="https://byarman.site">Made by Arman ↗</a></sub>

# Meds.krd

**A study platform for medical students in Kurdistan: their own lectures, a plan for today, and practice that remembers what each student gets wrong.**

[Open meds.krd ↗](https://www.meds.krd) &nbsp;·&nbsp; Live &nbsp;·&nbsp; The code is private. This page shows the product.

<img src="assets/divider.svg" width="100%" alt="">

## What a student sees

**Today.** One card says what to study today, how long it takes, and when it counts as done. It follows the student's own class timetable, and the reviews wait under it with the minutes they need.

**Recall.** The student answers from memory first. Then the app shows what the answer should have covered, and the student rates how much of it they had. What they got wrong comes back later in review.

**The source, one tap away.** Each part links to the page of the lecture it came from. A student who doubts a line can open the slide and check it, or press "Report a problem".

## The Lecture Machine

Inside Meds.krd, a pipeline turns a lecture into readable parts and practice questions. Several AI models, from different companies, share the work, and none of them checks its own writing. Anything that fails twice waits for a person.

## How it's built

**More than 5,000 automated tests,** unit and browser. The browser tests also compare key screens against approved pictures, so an unplanned layout change fails the run.

**An evidence log.** I keep one for Meds.krd: each claim, the date it was checked, how, and what the check does not prove. It has more than 400 dated entries.

**Database changes only move forward.** Once a migration runs on the live database, nobody touches it again. Each file has a pinned fingerprint, so any edit shows.

`React` `TypeScript` `Vite` `Supabase` `Postgres` `Vitest` `Playwright` `Sentry` `LLM APIs`

<img src="assets/divider.svg" width="100%" alt="">

I can walk you through the code on a call: [arman@byarman.site](mailto:arman@byarman.site)

More of my work: [byarman.site](https://byarman.site) &nbsp;·&nbsp; [github.com/arman-mahabad](https://github.com/arman-mahabad)

<img src="assets/rosette.svg" width="18" alt="">
