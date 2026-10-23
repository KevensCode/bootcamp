# Bootcamp practice

Everything I work on in the Career Bootcamp Curriculum is saved here, so I can review it, re-solve it, and see my progress.

## Where things go

| Folder | What goes in it | File naming |
| --- | --- | --- |
| `leetcode/<NN-pattern>/` | Every LeetCode attempt in C# | `<problem-slug>/<YYYY-MM-DD>.cs`; re-solves add `-resolve` (for example `two-sum/2026-10-29-resolve.cs`) |
| `sql/sqlbolt/`, `sql/tsql-path/` | Queries from each lesson or module | `lesson-01.sql`, `module-1.sql` |
| `sql/sql50/<section>/` | Every LeetCode SQL 50 attempt | `<problem-slug>/<YYYY-MM-DD>.sql` |
| `labs/` | APIs and troubleshooting labs | `week-NN-<topic>/` with `notes.md` plus anything the lab produced (Postman collections, logs, CSVs) |
| `drills/` | Bug squashes and take-homes | `<YYYY-MM-DD>-<name>/notes.md`; cloned repos go in a `repo/` subfolder, which Git ignores |
| `notes/patterns/` | Concept-day notes and the pattern template | `<pattern>.md` |
| `notes/books/` | Reading notes and quiz misses | `<book>-chNN.md` (for example `price-ch03.md`) |
| `notes/mocks/` | Mock interview feedback | `<YYYY-MM-DD>-<round>.md` |
| `exercism/` | Exercism C# workspace | Set with `exercism configure --workspace ~/Projects/bootcamp/exercism` |
| `anki-imports/` | Card files from each end session | `<YYYY-MM-DD>.txt` |

Every solution file starts with a header comment: the problem link, the date, solo or with help, minutes taken, and time and space complexity.

The capstone lives in `~/Projects/triage-desk` and the video platform in `~/Projects/ministry-video-platform`, each in its own repo.
