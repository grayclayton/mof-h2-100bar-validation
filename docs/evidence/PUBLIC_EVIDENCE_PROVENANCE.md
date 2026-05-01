# Public Evidence Provenance

## Purpose

This note maps the main public modeled-evidence claims to the specific public files that support them.

The goal is to make the evidence trail inspectable without implying experimental proof.

## Read This First

All files listed here support modeled or workflow-level claims only.

They do not establish experimental synthesis success, PXRD confirmation, or measured hydrogen-storage performance.

## Claim Map

### Claim: V010 is the named lead candidate in the public package

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `artifacts/cifs/v010_scale12600_cuni12_proxy_simple.cif`

### Claim: The public package includes the base control, V009, and V010 structures

Supported by:

- `artifacts/cifs/2021[Cu][nbo]3[ASR]2_base_native.cif`
- `artifacts/cifs/v009_scale12600_proxy_simple.cif`
- `artifacts/cifs/v010_scale12600_cuni12_proxy_simple.cif`

### Claim: V010 reflects a scale-factor change plus partial Cu-to-Ni substitution

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `docs/public-briefs/V010_NONTECH_EXPLANATION.md`
- `artifacts/cifs/v010_scale12600_cuni12_proxy_simple.cif`

### Claim: The modeled ambient-temperature screening package includes low- and high-pressure uptake values for base, V009, and V010, including the 100 bar slice

Supported by:

- `artifacts/isotherms/public_h2_isotherm_points_298K.csv`
- `artifacts/tables/public_restart_replicate_metrics.csv`

The compact isotherm-points table shows the public 298.15 K restart slice as per-pressure uptake rows.

The restart metrics table is the matching replicate summary artifact for the same 5 bar and 100 bar slice.

### Claim: The public ambient-temperature, 100 bar summary for V010 is about 5.03 wt% uptake and about 94.70% mean release

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `docs/evidence/EVIDENCE_SUMMARY.md`
- `artifacts/tables/public_additional_modeled_checks.csv`

The public restart table reports mmol/g replicate values. The public modeled-checks table records the compact V010 summary values used in the evidence docs.

### Claim: V010 showed stable behavior across a 10-cycle durability rerun

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `artifacts/tables/public_additional_modeled_checks.csv`

### Claim: V010 showed stable secondary temperature-response checks from 273.15 K to 323.15 K

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `artifacts/tables/public_additional_modeled_checks.csv`

### Claim: In the public summary, hydrogen remained the dominant adsorbed component in the H2/N2 screen

Supported by:

- `docs/evidence/MODELED_RESULTS_TABLE.md`
- `artifacts/tables/public_additional_modeled_checks.csv`

### Claim: The public package includes a limited rerun configuration slice for base, V009, and V010 at 298.15 K and 5 or 100 bar

Supported by:

- `artifacts/rerun-inputs/base_native/T298_P5bar/`
- `artifacts/rerun-inputs/base_native/T298_P100bar/`
- `artifacts/rerun-inputs/v009_scale12600/T298_P5bar/`
- `artifacts/rerun-inputs/v009_scale12600/T298_P100bar/`
- `artifacts/rerun-inputs/v010_scale12600_cuni12/T298_P5bar/`
- `artifacts/rerun-inputs/v010_scale12600_cuni12/T298_P100bar/`

## Scope Boundary

This provenance note covers the current public evidence slice only.

It does not claim that every internal working artifact has been published, and it does not upgrade the evidence boundary beyond the repository's existing status language.