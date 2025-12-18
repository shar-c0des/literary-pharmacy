# ☁️📖 Literary Pharmacy

> "Literature as medicine. A prescriptive engine for the human condition."

![Status](https://img.shields.io/badge/Status-Active_Development-yellow?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.11+-blue?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-High_Performance-009688?style=flat-square)

### The mechanism
Literary Pharmacy is not a blog; it is a **prescriptive engine**. It operates on the premise that specific literature acts as a pharmacological intervention for specific cognitive and emotional states.

**The main loop:**
1.  **Input:** User defines a complex emotional or cognitive state (e.g., *Ennui*, *Grief*, *Manic Ambition*).
2.  **Processing:** The engine analyzes the semantic and emotional weight of the input.
3.  **Prescription:** The system queries a strictly typed database to retrieve the precise literary match (Novel, Essay, Poem) to counterbalance or amplify that state.

### Tech architecture
This system is architected for strict type validation and efficient relational querying.

* **Core:** Python (The logic layer).
* **API:** FastAPI (Asynchronous, high-performance endpoints).
* **ORM / Data:** SQLModel (Combining Pydantic type safety with SQLAlchemy relational power).
* **Database:** [PostgreSQL/SQLite] (Structured mapping of `Symptoms` -> `Prescriptions`).


### Roadmap
I am currently building the backend core and database relations.

- [x] **System Design:** Defined the core Entity-Relationship model (Patient -> Symptom -> Cure).
- [ ] **Database Core:** Implementing `SQLModel` schemas for strict data validation.
- [ ] **API Layer:** Building the `POST /diagnose` and `GET /pharmacy/{id}` endpoints.
- [ ] **Logic Engine:** Refining the matching algorithm between user input and literary tags.

### Philosophy
> "Most people read to escape. We read to repair."

*Author: Sharleen Ngomakapile*
