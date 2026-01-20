## ADDED Requirements
### Requirement: Scope and inclusion criteria
The README MUST include a short "Scope & Inclusion Criteria" section near the
top (after the intro and before the Table of Contents) that clarifies what
qualifies for inclusion and what is out of scope.

#### Scenario: Reader checks scope before browsing
- **WHEN** a reader opens the README
- **THEN** the scope section is visible before the Table of Contents and lists
  at least 3 inclusion criteria

### Requirement: Standardized entry metadata
Each resource entry in the README MUST include metadata lines for:
Type (CLI/GUI/Service/Library), Open Source (Yes/No), and Platform
(Linux/macOS/Windows/Browser/Docker/Cloud as applicable).

#### Scenario: Reader compares tools quickly
- **WHEN** a reader scans any entry
- **THEN** the entry includes Type, Open Source, and Platform metadata lines

### Requirement: Preservation storage and replication coverage
The list MUST include a top-level "Preservation Storage & Replication" section
with entries for at least LOCKSS, iRODS, and Archivematica Storage Service.

#### Scenario: Storage-focused user browses the list
- **WHEN** a user looks for storage/replication tools
- **THEN** a dedicated section exists with those entries included

### Requirement: Policy and audit coverage
The "Preservation Planning, Risk & Policy" area MUST include a "Policy & Audit"
subsection with entries for TRAC, ISO 16363, and CoreTrustSeal.

#### Scenario: Preservation manager seeks audit guidance
- **WHEN** a user navigates to policy and planning resources
- **THEN** the policy/audit subsection lists TRAC, ISO 16363, and CoreTrustSeal

### Requirement: Fill identified tooling gaps
The list MUST add entries for the following tools in the appropriate sections:
Siegfried, FIDO, bagit-python (or `bagit`), Brozzler, Webrecorder, QCTools,
Brunnhilde, and Bulk Extractor.

#### Scenario: Practitioner searches for missing tools
- **WHEN** a user browses the relevant sections
- **THEN** each of the listed tools appears with a short description
