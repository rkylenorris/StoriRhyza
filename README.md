# **StoriRhyza: A Mycelium-Contextual Database & BI Engine**

StoriRhyza is an **open-source narrative data platform** designed to bridge the gap between quantitative metrics and qualitative human context. It operates on the **"Qualitative Mandate,"** asserting that data without narrative context—the "why," the "who," and the "feeling"—is incomplete noise.

By mimicking a **Common Mycelial Network (CMN)**, StoriRhyza facilitates tangential and narrative discovery, moving beyond rigid hierarchical databases to travel across the threads that connect financial metrics to personal journal entries or historical events.

---

## **TL;DR**

StoriRhyza is a mycelium-inspired narrative database engine using F\# and Neo4j to ensure quantitative data is always paired with qualitative human context through compiler-enforced DSLs (.stm, .stl, .stv).

---

## **Core Philosophy**

* **The Qualitative Mandate:** Data without narrative is not data. StoriRhyza "sutures" qualitative metadata to quantitative metrics.

* **Rhizomic Discovery:** Rather than querying "down" into tables, users navigate data "rhyzomically," tracing metrics through linked qualitative notes and external events.

* **Type-Driven Reality:** Built with **F\#**, the system uses functional programming to ensure that impossible states are unrepresentable. If a metric lacks a narrative root, the code makes it physically impossible to build the model.

* **The StoriBook:** The final output is a living document where the line between "Report" and "Literature" disappears, providing radical transparency into the lives and events behind the numbers.

---

## **System Architecture (The Substrate)**

StoriRhyza leverages a functional-first, multi-model approach to manage complex semantic integrity.

| Component | Technology | Functionality |
| :---- | :---- | :---- |
| **The Substrate** | **Neo4j (Graph DB)** | Manages the "root system" of interconnected metrics, people, and events.  |
| **The Hyphae** | **F\# Core (.NET 8\)** | Functional engine for parsing DSLs and translating them into target code (SQL, DAX, M).  |
| **Semantic Layer** | **Vector Embeddings** | Enables "fuzzy" search and links qualitative notes based on semantic meaning.  |
| **Interface Layer** | **C\# / .NET Web API** | Handles high-concurrency requests and authentication.  |
| **The Sporocarp** | **T3 Stack (Next.js/TS)** | The "StoriBook" web interface for constructing and visualizing narratives.  |

---

## **The Stori DSLs**

The data ecosystem is governed by three human-readable Domain Specific Languages (DSLs) with compiler-enforced integrity:

* **.stm (stori modeling):** Used to "plant" data and suture notes to metrics. It enforces a **"Malnourishment Check"**; if a model lacks human narrative roots, the build fails.

* **.stl (stori logistics):** Focused on standard ETL functions—ingestion, cleaning, and transformation. It prioritizes immutable transformations and traceable data lineage.

* **.stv (stori visualization):** Defines report layout and narrative framing, ensuring text and data share equal visual weight via "Narrative Sidebars".

GUI versions of these languages are available within the web app for non-technical users via drag-and-drop functionality.

---

## **Key Implementation Features**

* **The Person Module:** A mandatory component that appends the "why" to the "what".

* **Natural Language Mirror:** An F\#-implemented NLP library that translates complex logic into plain-English prose.

* **Integrated Orchestration:** A Podman/Docker-native setup for one-command deployment of the Graph DB, API, and Web Editor.

* **Schema-Aware Versioning:** Tracks both business logic (via Git) and the physical shape of source data to detect "drift".

---

## **Directory Structure**

* core/: F\# engine containing the parser (.stm, .stv, .stl), translators, and the NLP Mirror.

* api/: C\# ASP.NET Core project serving as the gateway.

* web/: T3 Stack visual editor and dashboard builder.

* shared/: Common schemas and example files for the Stori DSLs.

---

## **Roadmap**

The current development focus is on perfecting the core F\# engine (using .NET 8\) and implementing the DSL grammars using **FParsec** for high-performance data transformation pipelines.

> **"There is no Truth without Context."**  
