# Data

This folder documents and organizes datasets used by the project. Preserve source and license information, collection dates, labeling rules, preprocessing steps, and privacy constraints. Large or confidential data should remain in approved external storage; commit only small, permitted sample data when necessary.

- `raw/` — immutable original data, subject to permission and privacy rules.
- `processed/` — derived or cleaned data that can be reproduced from documented steps.
- `external/` — pointers and metadata for approved data hosted outside this repository.

The data payload folders are ignored by Git by default; their README files remain tracked.
