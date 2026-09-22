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

Predicts UFC bout outcomes from historical fighter statistics. An ensemble of logistic
regression, random forest and hist gradient boosting over 65 matchup differentials
(striking, grappling, Elo, experience), plus a blend with the betting market where a
line exists. It scrapes its own dataset and betting lines,
predicts full upcoming cards, and logs every pick to a ledger so the live record can be
graded after the event.

Evaluated on the most recent 1,300 fights, trained only on earlier ones: 65.1% accuracy
stats-only, 69.7% blended with the market. The README reports these next to the market's
own 70.0% baseline, because the honest finding is that the market is the stronger
predictor and the blend buys a small improvement in calibration rather than in accuracy.
I would rather publish that than a flattering number.

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
