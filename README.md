# Arvin Zargaran

Honours BSc Computer Science (Co-op) at York University, Lassonde — Toronto, expected 2029.
I build systems that can show their work: tools that cite where an answer came from and say
plainly when they don't know.

Currently looking for a **Software Engineering co-op in Toronto for Summer 2027**.

---

## What I'm building

### [Acadvo](https://github.com/arvinzargaran/acadvo) · Python, React, FastAPI, PostgreSQL

An AI academic and career advisor for Canadian university students. It plans degrees,
tracks GPA on each school's own scale, runs a co-op application pipeline, and answers
questions with an advisor that takes real actions instead of only chatting.

The part I care most about is the sourcing. Course catalogs are ingested from each
university's own public API — York's Kuali catalog, U of T's calendar JSON:API, SFU's
course-outlines API, Waterloo's Open Data. An adapter never invents a course, and a
prerequisite is only ever a code the university itself published. Schools without a
catalog degrade honestly rather than guessing. Sources considered and rejected are
written down with the reason.

Full-stack: FastAPI with async SQLAlchemy 2.0 and Alembic migrations, React 19 on Vite,
JWT auth with refresh rotation, an installable PWA, structured JSON logging with
per-request tracing, Docker Compose for local dev, and CI on every push.

### [UFC Fight Predictor](https://github.com/arvinzargaran/ufc-predictor) · Python

Predicts UFC bout outcomes from historical fighter statistics. The published version
scores fighters across performance metrics from four CSV datasets and reports a winner
with a confidence percentage. A probabilistic model evaluated against a holdout set is
in progress locally and not yet pushed.

### [LeetCode Solutions](https://github.com/arvinzargaran/leetcode-solutions) · Java

Data structures and algorithms practice, worked through in Java rather than copied.

### Backpacker · Swift, SwiftUI

An iOS focus timer built as world travel. Focus time moves you between real destinations,
and unlock cost is proportional to actual great-circle distance, so the map rewards
sustained work the way geography does. Fog of war lifts as the world opens up.
Not public yet.

---

## Tools

| | |
|---|---|
| **Languages** | Python · Java · JavaScript · Swift · SQL |
| **Backend** | FastAPI · SQLAlchemy · Alembic · PostgreSQL · Docker |
| **Frontend** | React · Vite · Tailwind CSS |
| **Practice** | Git · GitHub Actions · pytest · Vitest |

---

## Focus right now

Data structures and algorithms, systems fundamentals, and shipping projects that
hold up when someone reads the source. Interested in fintech, data pipelines,
and the product side of engineering.

---

## Contact

[LinkedIn](https://www.linkedin.com/in/arvinzargaran) · [GitHub](https://github.com/arvinzargaran)
