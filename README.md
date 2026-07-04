# Element Passport Generator

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21190991.svg)](https://doi.org/10.5281/zenodo.21190991)

An interactive single-file passport tool built from the Prime Elementology Decay Shadow Atlas.

## Metadata

- **Author:** Phan Thành Trung
- **ORCID:** [0009-0000-7520-6781](https://orcid.org/0009-0000-7520-6781)
- **DOI:** [10.5281/zenodo.21190991](https://doi.org/10.5281/zenodo.21190991)

## What It Is

Element Passport Generator turns each atlas record into a readable identity card. Instead of asking users to understand the whole decay-shadow map at once, the app lets them inspect one nuclide, element, or atlas record as a compact "passport".

The app is designed as a public-facing companion to the larger atlas: easier to scan, easier to explain, and useful for turning dense rule-path data into individual element profiles.

## Atlas Signal

**51,772 configurations · 383,320 decay-shadow relations · 435,092 total mapped entities**

## Main Features

- Self-contained `element-passport-generator.html` file.
- No server, build step, API, or external data file required.
- English/Vietnamese language toggle in the header.
- Search by nuclide, element, record ID, family, or band.
- Filters for shadow family and grid zone.
- Random scan mode.
- Large passport card for the selected nuclide.
- Z/N/A coordinate tiles.
- Decay-shadow path matrix.
- Element fingerprint by shadow-family distribution.
- Element-level stats: record count, mass range, dominant family, observed share.
- Copy passport summary.
- Download selected record as JSON.
- Half-life Watchlist tab for Te-128 and nearby stable anchors.

## Half-life Watchlist Note

The watchlist uses Te-128 as the ultra-long radioactive benchmark. Te-128 is known for its extremely long double-beta decay half-life, on the order of `10^24` years.

Other entries such as Xe-128, Te-126, Xe-130, Sn-124, and Ba-132 are included as stable or observationally silent anchors around the same atlas corridor. They are not presented as newly discovered isotopes, and the app does not claim measured half-lives longer than Te-128.

In short:

- Te-128 is a proven radioactive sleeper.
- The other entries are quiet reference anchors.
- The invitation is to keep searching for the next candidate, not to overstate the known ones.

## Data Interpretation

This app visualizes simulated rule paths only. It does not imply empirical decay evidence, half-life, branching probability, or physical decay certainty.

The passport fields should be read as atlas relations, not evaluated nuclear data.

## How To Use

1. Open `element-passport-generator.html` in a modern browser.
2. Search for a nuclide such as `Te-128`, `Xe-128`, or `Sn-124`.
3. Select a result from the scanner.
4. Inspect the passport, path matrix, and element fingerprint.
5. Use Copy or JSON export when needed.

## Deployment

Upload `element-passport-generator.html` directly to a repository or static host. The full dataset is embedded inside the file.

## Relationship To The Main Atlas

The main Prime Elementology Decay Shadow Atlas is a full map-level explorer. Element Passport Generator is the record-level companion: it turns the same atlas universe into readable individual profiles.
