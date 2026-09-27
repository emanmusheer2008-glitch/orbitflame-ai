# Data sources

Record every dataset, API or document the project uses. Check each licence **before** using it.

| Source | What it contains | Link | Licence / terms | Used for |
|---|---|---|---|---|
| NASA Physical Sciences Informatics (PSI) | Microgravity experiment data incl. combustion science | https://psi.nasa.gov/physci/repo/ | To check on each dataset page before use | Candidate main data source |
| NASA PSI on AWS Open Data | Same data, cloud-hosted | https://registry.opendata.aws/nasa-psi/ | To check on the registry page | Candidate alternative access |
| NASA web articles (Saffire, FLEX, candle flame) | Background explanations | see `background.md` | Credit NASA; check image-use guidelines before reusing images | Background and citations |
| Official challenge resources | To be listed after reading the challenge page | – | – | – |

Notes:
- NASA data is generally free to use, but check each dataset's page for any restrictions and credit requirements.
- Do not commit large files. Add a download script or link instead.
- Never commit API keys. Put them in a `.env` file (already ignored by Git).
