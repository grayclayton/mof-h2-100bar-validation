# Public Release Checklist

Use this checklist before turning this package into a public GitHub repository.

## Repository Readiness

- choose the exact public repository name
- add a short, plain-language description
- decide whether issues and discussions will be enabled
- choose a license before publication
- add citation metadata
- set `repository-code` in `CITATION.cff` after the final public repository URL exists
- create a tagged public release once the public package is stable
- archive that release with a DOI service if formal citation and attribution matter

## Content Review

- remove personal phone numbers and personal email addresses unless you want them public
- remove private outreach routing notes and contact lists
- remove files that are only useful for cold outreach operations
- confirm that public summaries do not imply physical validation has already happened
- confirm that every public scientific claim is supportable from the repo materials

## Safety Review

- keep safety and hydrogen-handling language high level in public docs
- avoid posting context-free instructions that could be misused
- keep qualified-lab language explicit
- confirm that a private security-reporting path is enabled and tested

## Technical Review

- remove environment-specific junk files
- remove scratch scripts that are not part of the public workflow
- remove stale outputs that do not help explain the project
- verify that example commands and paths are still correct
- if publishing CIF or simulation evidence, build the public subset from the curated evidence bundle rather than the full raw run trees

## Credibility Review

- include a clear project status statement
- include a narrow next-step ask
- state that negative results will also be published
- keep claims disciplined and specific
- make sure the public package points to one canonical citation path

## Final Check

- ask whether a skeptical reviewer could understand the project in under five minutes
- ask whether a lab or sponsor could see exactly what the next funded milestone would buy
- ask whether anything private, unsafe, or overstated is still visible
