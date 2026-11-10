# Hall 2012 Review Dataset

A CoLRev repository containing bibliographic records and review-workflow metadata for the Hall 2012 dataset. It is a data/provenance resource for systematic-review work, rather than a standalone software application.

## Start here

- [data/records.bib](data/records.bib): bibliographic records.
- [data/search/](data/search/): source and search records.
- [settings.json](settings.json): review configuration and data sources.

The configuration identifies the SYNERGY source `Yu_2018/Hall_2012_ids.csv` and records Gerit Wagner as the project author. Hosting this repository does not imply authorship of the original review or dataset.

## Using the repository

This repository follows the [CoLRev](https://github.com/CoLRev-Environment/colrev) structure. With a compatible CoLRev installation:

```bash
colrev clone https://github.com/Cohen2000/Hall_2012
```

The stored configuration records CoLRev version 0.9.2; check compatibility before updating or rerunning the workflow.
