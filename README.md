# Aashwat Singh

I build backend systems around PostgreSQL, from data models to the policies that decide who can read or change a row. I also build ML pipelines that extract fields from scanned documents and align lyrics to audio. I’m a CS junior at The University of Texas at Dallas, based in Frisco, TX, graduating in May 2028 and seeking a Summer 2027 backend, full-stack, or AI/ML internship.

## Featured Work

| Project | What It Solves | Key Engineering Detail / Metric | Stack |
| --- | --- | --- | --- |
| [TaxShoeBox](https://github.com/aashwatSingh/TaxShoeBox) | Keeps a freelancer’s expenses and receipts together for Schedule C | Solo build. PostgreSQL calculates yearly totals and enforces per-user access. [Schema and policies](https://github.com/aashwatSingh/TaxShoeBox/blob/main/supabase/schema.sql) | JavaScript, React, Supabase, PostgreSQL |
| [ProjectForge-Personal](https://github.com/aashwatSingh/ProjectForge-Personal) | Coordinates tasks and membership across engineering teams | I owned tasks, membership, and collaboration. Two concurrent demotions must leave one owner. [Database tests](https://github.com/aashwatSingh/ProjectForge-Personal/blob/main/backend/tests/test_supabase_rls.py) | Python, PostgreSQL, Supabase, React |
| [Walkthru-HackUTD](https://github.com/aashwatSingh/Walkthru-HackUTD) | Gives students a photo record for housing deposit disputes | Room QR codes route inspections. SHA-256 fingerprints let reviewers check whether the photo bytes changed. | JavaScript, React, PostgreSQL |
| [songbox](https://github.com/aashwatSingh/songbox) | Turns a song into a karaoke track with timed lyrics | Separates vocals before word alignment and pitch tracking. [Word-timing evaluator](https://github.com/aashwatSingh/songbox/blob/master/services/api/scripts/eval_alignment.py) | Python, PyTorch, PostgreSQL, Pytest |
| [nle-engine](https://github.com/aashwatSingh/nle-engine) | Previews and exports edits from a video timeline | GPU compositing and audio playback share a timeline. [Export crash investigation](https://github.com/aashwatSingh/nle-engine/blob/master/docs/evidence/2026-08-19-export-access-violation.md) | Rust |
| [streamforge](https://github.com/aashwatSingh/streamforge) | Helps viewers find and play videos | Ranks a feed by engagement and freshness, then streams the selected video over HLS. | TypeScript, Next.js, Prisma, SQLite |

## Core Stack

```text
Languages    Python, SQL, TypeScript, JavaScript, Rust
Backend      PostgreSQL, Supabase, Node.js, SQLite
AI/ML        PyTorch, OpenCV, PyMuPDF, LlamaIndex
Frontend     React, Next.js
Tooling      Git, Pytest, PowerShell
```

## Applied ML Experience

At Outamation, my mortgage PDF pipeline reached 95% field-extraction accuracy and cut manual review time by 75%. At the Computing Research Association, I reduced character error rate by 18% on noisy scans.

## Currently Focused On

- Automating repeat setup and validation steps with PowerShell and Python.
- Tracing a request from PostgreSQL to the model to see where caching can cut LLM spend and response time.
