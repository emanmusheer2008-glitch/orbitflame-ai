# OrbitFlame AI

> **Status: team formation / planning.** This is a team project for the **NASA International Space Apps Challenge 2026**, challenge **"Flame in Freefall: AI-Powered Fire Safety Insights from Microgravity Combustion Data"**. No solution has been built yet. Challenge development will happen during the official hackathon period, following the event rules.

## The idea

Fire behaves very differently in microgravity. Without gravity-driven convection, flames can become rounder, weaker and slower, and a fire on a spacecraft is one of the most serious risks for astronauts. Decades of microgravity combustion experiments exist, but the results are spread across many papers, datasets and formats.

**Our goal:** explore AI-powered ways to make microgravity combustion and fire research **easier to search, understand and visualise**, for students, researchers and mission planners.

## Questions we want to explore

These are questions for the hackathon, not finished features:

- How can someone find the right experiment or dataset by asking in plain language?
- How can results from different experiments be summarised and compared clearly?
- What visualisations help a non-expert understand how flames behave without gravity?
- How do we show where information comes from, so users can check it?

## Resources we plan to review

To be confirmed against the official challenge page once it is published:

- [NASA Physical Sciences Informatics (PSI)](https://psi.nasa.gov/physci/repo/): NASA's repository of physical-science experiment data, including combustion
- [NASA PSI on the Registry of Open Data on AWS](https://registry.opendata.aws/nasa-psi/)
- Official data and resources linked from the Space Apps challenge page

## Team

| Name | Role | GitHub |
|---|---|---|
| Eman Musheer | Team Lead | [@emanmusheer2008-glitch](https://github.com/emanmusheer2008-glitch) |
| _TODO: add teammates only with their permission_ | | |

## Timeline

| Phase | Status |
|---|---|
| Team formation and registration | In progress |
| Background reading (see `docs/background.md`) | In progress |
| Hackathon: build the solution | _Official dates: check spaceappschallenge.org_ |
| Submission and demo video | _Not started_ |

## Repository structure

```
orbitflame-ai/
├── README.md
├── LEARNING_GUIDE.md
├── docs/
│   ├── background.md       # what we learned about microgravity combustion (with sources)
│   ├── planning.md         # questions, roles, decisions
│   └── data_sources.md     # every dataset/API we use + its licence
├── src/                    # solution code: added DURING the hackathon
├── data/                   # small sample data only (large data not committed)
├── notebooks/
└── assets/                 # images for README, demo screenshots
```

## Disclaimer

This is an independent team project created for the NASA International Space Apps Challenge. It is **not** an official NASA product, and the team members are not NASA employees or affiliates. NASA data, where used, is credited to its sources.
