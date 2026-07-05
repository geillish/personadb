# Sample Data

This directory contains small, non-personal datasets used during development.

These files are intended to:

- Develop and test importers.
- Validate parsing and normalization logic.
- Provide stable datasets for debugging and regression testing.

The samples mirror the structure of the `data/raw/` directory wherever possible so that importers can operate on either location with minimal or no configuration changes.

## Personal Data

Personal exports are **not** stored in this repository.

Real data should be placed in the corresponding directories under `data/raw/`, which are excluded from source control.

## Directory Structure

```text
samples/
├── letterboxd/
│   └── watched.csv
└── ...
```

As support for additional services is added, representative sample datasets may be included here.