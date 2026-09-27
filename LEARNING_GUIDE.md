# Learning Guide: OrbitFlame AI

## 1. What does this project do?

Nothing yet, on purpose. It is the prepared home for a NASA Space Apps team project that will be built during the official hackathon.

## 2. Why does it exist?

- To prepare **without breaking hackathon rules**: learning and planning are fine before the event; building the solution is not.
- To show an organised, honest team project on your GitHub.

## 3. Where will the data come from?

Most likely from NASA's open physical-science and combustion experiment data (see `docs/data_sources.md`) and whatever the official challenge page lists. Check each source and its licence first.

## 4. Folders and files

| Path | Job |
|---|---|
| `README.md` | Public description: status, goal, team, disclaimer |
| `docs/background.md` | Your science notes with sources |
| `docs/planning.md` | Checklists, roles, decisions |
| `docs/data_sources.md` | Every data source and its licence |
| `src/` | Solution code (empty until the hackathon) |
| `data/` | Small samples only |
| `notebooks/` | Experiments during the hackathon |
| `assets/` | Screenshots and images for the README |

## 5. Concepts to learn before the hackathon

| Concept | Why it matters here |
|---|---|
| **Buoyancy and convection** | They explain why flames look different in microgravity |
| **Search vs keyword search** | "Easier to search" might mean finding documents by meaning, not exact words |
| **Embeddings** (basic idea) | A way to turn text into numbers so similar meanings are close together. Used in semantic search. |
| **Retrieval-augmented generation (RAG)** (basic idea) | An AI answers using retrieved documents and can cite them. Useful for trustworthy answers. |
| **Citing sources in an app** | Users must be able to check where an answer came from |
| **Data visualisation** | Turning experiment results into charts that non-experts understand |
| **Git teamwork** | Branches, pull requests, avoiding conflicts with teammates |

These are *possible* directions. The team decides the real approach during the hackathon.

## 6. Libraries you might meet

Decide during the hackathon. Common options: `pandas` (tables), `matplotlib`/`plotly` (charts), `streamlit` (quick web apps), `scikit-learn` (simple ML). Learn the basics of one web framework and one charting library in advance on unrelated practice data.

## 7. How it will work

To be written during the hackathon: input → processing → output.

## 8. How to run

To be written. Every project README should say how to run it in 3–5 commands.

## 9. Common mistakes to avoid

- Claiming the project is finished, or that you won, before results are announced
- Implying NASA employment or affiliation. Keep the disclaimer.
- Committing API keys (use `.env`)
- Using data without checking its licence
- Building before the hackathon starts

## 10. Questions you should be able to answer (after the hackathon)

1. What problem did your team solve, and for whom?
2. What data did you use, and where did it come from?
3. What was **your** part of the work?
4. How does the AI part work, and how do users know an answer is correct?
5. What would you improve with more time?
