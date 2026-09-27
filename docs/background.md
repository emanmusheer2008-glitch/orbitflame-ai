# Background notes: microgravity combustion

This is our research log before the hackathon. **Every fact has a source link.** Reading and learning before the event is allowed; building the solution is not.

## Key facts (checked September 2026)

| Topic | What the source says | Source |
|---|---|---|
| Why flames look different in space | On Earth, "gravity-driven buoyant convection causes a candle flame to be teardrop-shaped and carries soot to the flame's tip, which makes it yellow." In microgravity, "where convective flows are absent, the flame is spherical, soot-free and blue." | [NASA: Candle Flame, 1g vs Microgravity](https://www.nasa.gov/image-article/candle-flame-1g-vs-microgravity/) |
| Spacecraft fire experiments | Saffire is "a series of experiments developed by the Spacecraft Fire Safety Demonstration Project". Saffire-V (the fifth) was conducted in January 2021 inside Northrop Grumman's Cygnus after it left the ISS. | [NASA: Saffire Ignites New Discoveries in Space](https://www.nasa.gov/humans-in-space/saffire-ignites-new-discoveries-in-space/) |
| What Saffire observed | Fires in microgravity "typically grow and burn faster on the thinner" materials than on thicker samples. Elevated oxygen produced "more energetic flames, which would have a larger impact on the vehicle". This informs fire detection and safety for Artemis missions. | same as above |
| Extinguishing fires in space | FLEX was "designed to assess and quantify the effectiveness of inert-gas suppressants in microgravity and obtain the most conservative estimate of the limiting oxygen index for steady combustion." It ran on the ISS in the Multi-user Droplet Combustion Apparatus. | [NASA Glenn: FLEX](https://gipoc.grc.nasa.gov/wp/fcf-cir/flex/) |
| Where the data lives | NASA's Physical Sciences Informatics (PSI) covers six fields including **Combustion Science** (spacecraft fire safety, droplets, gaseous flames, supercritical reacting fluids, solid fuels). "The PSI system is accessible and open to the public." | [NASA PSI Research Areas](https://www.nasa.gov/physical-sciences-informatics-psi/physical-sciences-informatics-research-areas/) · [PSI Data Repository](https://psi.nasa.gov/physci/repo/) |

## What this means for our project (our interpretation)

- Useful knowledge exists, but it is spread across experiments, reports and data files in different formats. That is the gap our challenge is about.
- Any tool we build must **cite its sources**, because fire safety is a high-stakes topic and users need to verify answers.
- Visual explanations (e.g. Earth vs microgravity flames) could help non-experts quickly understand why space fire is different.

## Still to read

- [ ] The official *Flame in Freefall* challenge description and its listed resources
- [ ] Which PSI combustion datasets are downloadable, and in what formats
- [ ] Saffire mission summaries (earlier missions I–IV)
- [ ] Space Apps rules on data use and on what can be prepared in advance

## Reading log

| Date | What I read | Key takeaway |
|---|---|---|
| 2026-09-27 | NASA candle-flame, Saffire, FLEX and PSI pages | Microgravity flames are spherical and soot-free; Saffire studied flame spread on spacecraft materials; PSI makes combustion data public |
