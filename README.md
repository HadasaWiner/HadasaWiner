# Hadasa

**AI Solution Architect · Creator of MasterTrail**
*Expert thinking. Human decisions.*

I design AI-assisted ways of working for organizations where expertise is scarce and regulation is heavy.
Today I lead AI adoption and spec-driven development (SDD) methodology in the public sector.
Before that: ~10 years building core systems in banking, insurance and healthcare.

---

### 🧭 MasterTrail — the third partner

Most AI rollouts give people a tool and hope for the best.
MasterTrail adds a third partner to the team:

| Partner | Role |
|---|---|
| **Employee** | Thinks and decides |
| **AI** | Guides and executes |
| **Skill** | Encodes how a master practitioner thinks |

A *Skill* is the codified thought process of an expert in the field. It walks the employee through the right questions, in the right order, so the work is procedurally correct even when no senior expert is in the room.
The person who builds and maintains these skills is the **Trailwright**.

The first reference trail covers systems analysis and the SDLC — from business intake to dev-ready specs:

`Compass` (shared core) → `Trailhead` → `Waypoint` → `Lookout` → `Survey` → `Junction` → `Basecamp`

MasterTrail is not presented as a spec. It is presented as a **proof**: a controlled, reproducible comparison of the same work done with AI alone vs. AI + Skill, published with the data.

👉 [**mastertrail**](https://github.com/HadasaWiner/mastertrail)

---

### 🛠️ Projects

**[wiki-engine](https://github.com/HadasaWiner/wiki-engine)** — *A company wiki that writes itself.*
The knowledge layer of my multi-agent platform, extracted to run on its own. Facts flow in from documents, email and finished work; nothing reaches the knowledge base unchecked.
- **Injection-proof write path** — a deterministic, bilingual sanitizer (deliberately *not* an LLM) quarantines prompt injection before the model ever sees the text
- **Deterministic review policy** — a fail-closed rule matrix with exactly one auto-merge path; conflicts and external sources always go to a human
- **Hybrid retrieval** — pgvector + tsvector fused with Reciprocal Rank Fusion, clearance enforced in SQL
- **Hebrew + English first-class**, right-to-be-forgotten built in
- `npm run demo` runs the full loop offline on real Postgres (PGlite) · 235 unit tests

**Agent output-safety layer** *(coming)* — early exit on unsafe agent output, with `SHADOW` (observe) and `ENFORCE` (block) modes.

**Model training experiments** *(coming)* — my own training code and notes.

---

### 🧰 Toolbox

**AI & agents:** LLM agents · RAG · pgvector · LangChain / LangGraph · multi-agent orchestration · prompt-injection defense · Claude Code skills · spec-driven development
**Modern stack:** TypeScript · Node · Postgres · Vitest
**Enterprise:** C# / .NET Core APIs · COBOL / AS400 / RPGLE · DB2 · PL/SQL · SSIS · MQ / MFT · Control-M · Azure DevOps / TFS
**Domains:** banking · insurance · healthcare · government & regulated environments

---

### 🤝 Work with me

I help organizations bring AI into their analysis and development process — methodology, implementation, and training Trailwrights to build their own skills.
