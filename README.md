# Data science & analytics

I build projects that connect data, models, and usable applications. My portfolio spans applied audio ML, SQL-backed dashboards, and reproducible simulation. I am interested in data science and analytics opportunities.

## Start here

| Project | Focus | What to explore |
| --- | --- | --- |
| **[SongBox](https://github.com/aashwatSingh/songbox)** | Applied machine learning · Python | Audio separation, transcription, word alignment, and pitch tracking in a FastAPI pipeline. Includes evaluation tooling and documented accuracy limits. |
| **[Wavepress](https://github.com/aashwatSingh/wavepress)** | Simulation · Revenue analytics | Deterministic streaming data, royalty dashboards, CSV statements, and integer-based revenue allocation. Distribution tests compare simulated market shares with configured weights. |
| **[TaxShoeBox](https://github.com/aashwatSingh/TaxShoeBox)** | SQL · Dashboard design | PostgreSQL aggregation for yearly financial summaries, indexed search, row-level access controls, and a browser demo with sample data. |

## Explore the evidence

- **ML evaluation:** [SongBox alignment evaluator](https://github.com/aashwatSingh/songbox/blob/master/services/api/scripts/eval_alignment.py) and [status notes](https://github.com/aashwatSingh/songbox/blob/master/docs/STATUS.md). The documented English alignment result is 68.2 ms median error; the 50 ms target remains unmet.
- **Simulation validation:** [Wavepress distribution tests](https://github.com/aashwatSingh/wavepress/blob/master/tests/streams.test.ts) examine 20,000 track-days. Streams, store delivery, and payouts are simulated.
- **SQL analytics:** [TaxShoeBox schema](https://github.com/aashwatSingh/TaxShoeBox/blob/main/supabase/schema.sql) includes the `get_tax_summary` function for per-user, per-year totals.

## Supporting engineering projects

| Project | Technical focus |
| --- | --- |
| [Deepwater Nights](https://github.com/aashwatSingh/deepwater-nights) | Seeded simulation, headless game-state tests, and procedural graphics/audio. |
| [StreamForge](https://github.com/aashwatSingh/streamforge) | Video data modeling, engagement queries, and a feed ranking heuristic based on popularity and freshness. |
| [NLE Engine](https://github.com/aashwatSingh/nle-engine) | Rust media processing, GPU compositing, timeline editing, and documented performance investigations. |

**Tools used across these projects:** Python · SQL / PostgreSQL · FastAPI · PyTorch-based audio models · TypeScript · React · Prisma · Rust · Docker.

Each repository links to its implementation, setup instructions, and project-specific limitations.
