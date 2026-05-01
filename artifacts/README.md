# Public Artifacts Bundle

## Purpose

This folder contains the small computational artifact subset that supports the public modeled-evidence claims.

It is intentionally narrower than the internal working tree.

## Source Of Truth

These public artifacts were selected from a curated pre-publication evidence bundle.

They were not assembled from the broader raw run trees.

## Included Here

### Locked Candidate CIFs

- `cifs/2021[Cu][nbo]3[ASR]2_base_native.cif`
- `cifs/v009_scale12600_proxy_simple.cif`
- `cifs/v010_scale12600_cuni12_proxy_simple.cif`

### Compact Public Isotherm Points

- `isotherms/public_h2_isotherm_points_298K.csv`

This compact table flattens the public 298.15 K, 5 bar, and 100 bar restart slice into per-pressure isotherm points for the base control, V009, and V010.

It removes internal filesystem paths while keeping the public run labels, candidate IDs, pressures, and uptake values.

### Clean Public Metrics Table

- `tables/public_restart_replicate_metrics.csv`
- `tables/public_additional_modeled_checks.csv`

This cleaned table is derived from a pre-publication replicate extract and removes internal filesystem paths while preserving the public candidate, pressure, and uptake values.

The additional modeled-checks table records compact public summary values for durability, temperature checks, H2/N2 screening, and the mass-transfer review without copying internal working-tree clutter.

### Limited Rerun Inputs

- `rerun-inputs/base_native/T298_P5bar/`
- `rerun-inputs/base_native/T298_P100bar/`
- `rerun-inputs/v009_scale12600/T298_P5bar/`
- `rerun-inputs/v009_scale12600/T298_P100bar/`
- `rerun-inputs/v010_scale12600_cuni12/T298_P5bar/`
- `rerun-inputs/v010_scale12600_cuni12/T298_P100bar/`

Each rerun folder is limited to the minimal text-based input set used for a compact reproducibility slice:

- `simulation.json`
- `simulation.input`
- `force_field.json`
- `H2.json`
- candidate CIF

## Intentionally Excluded

The public bundle excludes:

- raw output folders
- restart binaries
- bias-factor folders
- machine-specific path references
- exploratory and non-public run-tree clutter

## How To Read This Bundle

Use the CIF files, compact isotherm-points table, and cleaned metrics tables as the primary public evidence artifacts.

Use the limited rerun-input folders only as a compact configuration reference for the published 298.15 K, 5 bar, and 100 bar cases.

These artifacts support modeled claims only. They do not constitute experimental validation.