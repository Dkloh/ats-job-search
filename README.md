# ATS Job Search Generator

A Google dork query generator for finding jobs directly on ATS platforms and company career pages — bypassing LinkedIn and Indeed.

**Live:** https://ats-job-search.vercel.app

## What it does
- Generates precise search queries for 18 ATS platforms (Greenhouse, Lever, Workday, Ashby, and more)
- Splits combined searches into batches to avoid Google's query length limit
- Searches company career pages via `inurl:careers` and `inurl:jobs`
- Supports keyword, location, exclude terms, and date filters
- Copy, search, or export all queries

## Why I built it
I built this during my own job search to find openings posted directly on company sites before they hit the big job boards.

## Tech
Vanilla JavaScript, HTML, CSS — no frameworks, no dependencies, no build step.

## Author
Derek Kloh — [Portfolio](https://dkloh.github.io/portfolio) · [GitHub](https://github.com/Dkloh)