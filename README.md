# Yash Krishna Divate

I build full-stack products where the interesting part is the data model — a graph database that picks your code reviewers, an anomaly-detection backend for public-works audits, a routing engine that knows where the city floods.

- 🔭 Currently building **Keystone**, a graph-based pull-request reviewer recommender on FalkorDB
- 🧪 I care about the unglamorous half: schema mapping, data-quality flags, auditable scoring rules, tests that pin down behaviour
- 🌱 Sharpening Python and TypeScript, one NeetCode problem at a time
- 📫 Reach me at **yashsejuro.ys@gmail.com**

## Selected work

| Project | What it does | Stack | Demo |
|---|---|---|---|
| **[Keystone](https://github.com/yashsejuro/Keystone-Falkor-db)** | Recommends PR reviewers from a FalkorDB graph of files, authors, reviews and co-changes — and shows the graph path behind every suggestion | Python · FalkorDB · FastMCP · React | [Live](https://keystone-falkor-db.vercel.app) |
| **[ClimatePulse AI](https://github.com/yashsejuro/ClimatePulse-AI-)** | Puts the fastest route next to a flood-aware safer one, so a driver can see the minutes saved versus the risk taken | TypeScript · AWS Lambda · Amazon Bedrock · DynamoDB | [Live](https://climate-pulse-ai.vercel.app) |
| **[MPLAD Audit Intelligence](https://github.com/yashsejuro/MPLAD)** | Uploads MPLADS public-works data, detects anomalies with an Isolation Forest, and triages audit risk with fixed, auditable rules | FastAPI · scikit-learn · SQLAlchemy · React | — |
| **[Careerly](https://github.com/yashsejuro/careerly)** | AI career navigator for students: personalised roadmaps, skill-gap analysis and resume-worthy project suggestions | Next.js · MongoDB · Gemini | [Live](https://careerly-pi.vercel.app) |
| **[Hygenious](https://github.com/yashsejuro/Hygenious)** | Turns a phone photo of a kitchen, restroom or dining area into an objective hygiene score with visual evidence | Next.js · Node · Firebase | [Live](https://hygenious-henna.vercel.app) |
| **[AlgoTales](https://github.com/yashsejuro/AlgoTales)** | Data structures and algorithms told as animated stories, with step timelines and line-synced code | React 19 · Vite · Tailwind CSS · Motion | [Live](https://algo-tales.vercel.app) |

## Tools I reach for

**Languages** — Python, TypeScript, JavaScript, SQL
**Backend** — FastAPI, Node.js, SQLAlchemy, Supabase, FalkorDB
**Data & ML** — pandas, scikit-learn, Isolation Forest, feature engineering
**Frontend** — React, Next.js, Vite, Tailwind CSS, TanStack Router
**Cloud** — AWS (Lambda, Bedrock, DynamoDB), Vercel, Netlify
**Practices** — pytest, vitest, GitHub Actions, schema-first API design

## Beyond the code

I like problems where the data is messy and the answer has to be defensible — government works data with `₹1,00,000` in a string column, hazard reports that arrive without coordinates, review history that only makes sense as a graph. Most of what is here started as a competition build or a "this should exist" itch.
