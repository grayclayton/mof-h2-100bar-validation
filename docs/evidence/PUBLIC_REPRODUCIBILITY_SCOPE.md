# Public Reproducibility Scope

## Purpose

This note defines which computational evidence artifacts belong in the public package.

The goal is to make the modeled claims auditable without turning the repository into a dump of every internal working file.

## Source Bundle

When preparing the public release, use a curated pre-publication evidence bundle as the starting point.

Do not build the public evidence package directly from broader raw run trees unless a published value needs to be regenerated or audited.

## Include In The Public Package

The public package should normally include the smallest artifact set that directly supports the published modeled claims.

Recommended inclusions:

- locked candidate CIF files for the base control, V009, and V010
- compact isotherm tables that back the public summary metrics
- a cleaned replicate or restart summary table that maps to the reported uptake and release values
- a short provenance note explaining which artifacts support which public claims
- rerun input bundles only if the public release is intended to support limited computational reruns

For the current public package, the compact isotherm slice is a small 298.15 K table built from the 5 bar and 100 bar evidence points, not a full pressure sweep.

In practice, that usually means selecting from a curated bundle that contains only the published candidate structures, compact tables, and the smallest rerun-input slice needed for public auditability:

- `cifs/`
- `isotherms/`
- `tables/`
- selected `rerun-inputs/`
- selected proving documents that explain provenance and evidence boundaries

## Usually Exclude From The Public Package

The public package should usually exclude material that adds noise, leaks internal workflow clutter, or implies a stronger evidence standard than the repository actually supports.

Usually exclude:

- full raw run trees and exploratory experiment folders
- scratch variants, abandoned candidates, and intermediate files that are not tied to published claims
- machine-specific execution artifacts and environment-specific paths
- operational lab paperwork that is not needed to evaluate the modeled evidence claims
- detailed safety and execution documents if the public repository is meant to stay high level
- helper scripts or execution-context files that are not required to understand or reproduce the published metrics

## Decision Rule

Before adding a file, ask:

1. does this file directly support a claim already made in the public docs?
2. would removing it make the public numbers harder to audit?
3. does it improve clarity more than it increases noise?

If the answer to those questions is mostly no, the file probably does not belong in the public package.

## Recommended Minimum Public Evidence Set

For this repository, a disciplined minimum set is:

1. base, V009, and V010 locked CIF files
2. one compact isotherm evidence table or CSV set for the current 298.15 K, 5/100 bar public slice
3. one compact restart or replicate metrics table
4. one short provenance note connecting those artifacts to the values cited in the public evidence summary

That is enough to support transparent review without overstating experimental status.