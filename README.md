# Project Title

Briefly describle the project in one/two sentences.

---

## Authors

- **Researcher1:** `<Full name>`
- **Researcher2:** `<Full name>`

Add supervision as well, if necessary.

Optional:

- **ORCID:** `<ORCID>`
- **Project website:** `<URL>`
- **Repository DOI:** `<DOI, if available>`

---

## Overview

State a brief aim and background regarding the project. Explain the methods, the folder structure, and how to use the scripts/data.

## Folder structure

- **rawdata:** Original EEG files
- **derivatives:** Include derived files following preprocessing and analyzing the data.
- **scripts:** Processing and statistical analysis scripts

## Data description

- **Population**: `<brief description>`
- **Data Modalities**: 64-Channel BrainVision, sampling rate 1000Hz


## Excluded subjects
| Participant ID | Excluded | Reason | Analysis affected | Notes |
|---|---|---|---|---|
| `sub-032` | Yes | Excessive motion | Resting-state fMRI | Mean FD above threshold |
| `sub-085` | Yes | Incomplete acquisition | EEG | Task data not recorded |
| `sub-122` | Yes | Protocol deviation | Primary analysis | Included in sensitivity analysis |