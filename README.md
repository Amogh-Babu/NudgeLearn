# RepoLens

RepoLens is a web-based application designed to help developers onboard onto unfamiliar GitHub repositories. By pairing interactive dependency graphs with feature-centric reading recommendations, it enables newcomers to trace functional workflows—such as authentication or data ingestion—directly through relevant source files without getting lost in directory structures.
---

## Goals

* Help onboarding developers locate entry points for specific features without deciphering unfamiliar repository directory trees.
* Generate clear dependency graphs from static code analysis to visualize how relevant files and modules connect.
* Recommend a reading order for related files based on symbol definitions and import relationships.
* Deliver an interactive web tool that parses public Python repositories safely without executing untrusted code.

---

## Repository Layout

```text
├── frontend/          # Client application (React Native / Expo)
├── backend/           # API server, LLM pipeline, and database (Node / FastAPI)
├── docs/              # Living document snapshots, specifications, and architecture diagrams
├── .github/           # Issue templates, PR templates, and CI/CD workflows
└── README.md          # Project overview and developer onboarding
```

---

## Local Setup Instructions

*TBD*

---

## Living Document

* [RepoLens (Google Docs)](https://docs.google.com/document/d/1ZTgu6tfoWwx9FWWS-5DqG5CtgXJ-zucDNXEEca_Qy4s/edit?tab=t.sql8ybk4ej5d#heading=h.18mw63g8e8ay)
