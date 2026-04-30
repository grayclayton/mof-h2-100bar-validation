# mof-h2-100bar-validation

Apache-2.0 licensed public package for staged validation of a hydrogen-storage MOF candidate, with particular interest in whether the modeled signal remains compelling at ambient temperature and 100 bar.

## What This Is

This repository is meant to be a clean public front door for the project.

It documents:

- the current lead candidate, V010
- the ambient-temperature and 100 bar validation hook that makes the candidate interesting to test
- the boundary between modeled evidence and physical proof
- the staged validation plan
- the staged funding logic for external testing
- the public recognition and visibility strategy for the validation effort

## What This Is Not

This is not a claim of experimental validation.

The current status is:

- computationally supported
- method-documented
- externally unvalidated

See [PROJECT_STATUS.md](PROJECT_STATUS.md) for the exact evidence boundary.

## Why This Project Exists

The practical question is narrow:

Can a computationally selected hydrogen-storage candidate with interesting modeled behavior at ambient temperature and 100 bar justify a small, disciplined external validation step?

That is the right question for this stage. The project is not asking anyone to assume the material is already proven.

The public hook is not just that a candidate exists. It is that the current modeled package suggests a result worth trying to falsify in the lab under ambient-temperature, 100 bar conditions that could matter for hydrogen storage decisions.

## Repository Guide

- [PROJECT_STATUS.md](PROJECT_STATUS.md): what is and is not currently supported
- [DISCLAIMER.md](DISCLAIMER.md): safety and evidence boundaries
- [docs/public-briefs/V010_ONE_PAGE_EXTERNAL_BRIEF.md](docs/public-briefs/V010_ONE_PAGE_EXTERNAL_BRIEF.md): short external summary
- [docs/public-briefs/V010_NONTECH_EXPLANATION.md](docs/public-briefs/V010_NONTECH_EXPLANATION.md): plain-language candidate explanation
- [docs/FAQ.md](docs/FAQ.md): short answers to common reviewer questions
- [docs/evidence/EVIDENCE_SUMMARY.md](docs/evidence/EVIDENCE_SUMMARY.md): curated public evidence summary
- [docs/evidence/MODELED_RESULTS_TABLE.md](docs/evidence/MODELED_RESULTS_TABLE.md): compact modeled results table
- [docs/evidence/PUBLIC_EVIDENCE_PROVENANCE.md](docs/evidence/PUBLIC_EVIDENCE_PROVENANCE.md): file-level map from public claims to public evidence files
- [docs/evidence/PUBLIC_REPRODUCIBILITY_SCOPE.md](docs/evidence/PUBLIC_REPRODUCIBILITY_SCOPE.md): what computational artifacts to include in the public package
- [artifacts/README.md](artifacts/README.md): curated public CIF and rerun-input bundle
- [docs/validation/STAGED_VALIDATION_PLAN.md](docs/validation/STAGED_VALIDATION_PLAN.md): validation sequence and gates
- [docs/funding/STAGED_FUNDING_PLAN.md](docs/funding/STAGED_FUNDING_PLAN.md): milestone-based funding structure
- [docs/visibility/RECOGNITION_AND_VISIBILITY_PLAN.md](docs/visibility/RECOGNITION_AND_VISIBILITY_PLAN.md): how to build visibility without losing attribution
- [docs/workflows/WORKFLOW_OVERVIEW.md](docs/workflows/WORKFLOW_OVERVIEW.md): public workflow overview

## Why The Staged Structure Matters

The first hard gate is simple: obtain a real synthesis quote and determine whether the candidate can be made as a real material.

Only after that does it make sense to spend money on PXRD, activation, or hydrogen uptake testing.

## Good First Outcomes

At this stage, the most useful next outcomes are:

1. one real synthesis quote
2. one qualified lab or collaborator willing to review the candidate
3. one public release of the candidate and evidence package
4. one external validation result, whether positive or negative

## Publication Standard

This project should publish negative or mixed results as well as positive ones. That is part of what makes the workflow scientifically useful.

## Recognition And Citation

If this package is published publicly, recognition should be built through a durable citation trail rather than informal visibility alone.

The preferred order is:

1. publish the repository
2. create a tagged public release
3. archive that release with a DOI service such as Zenodo
4. use the same public repository as the canonical reference in outreach and review conversations

See [docs/visibility/RECOGNITION_AND_VISIBILITY_PLAN.md](docs/visibility/RECOGNITION_AND_VISIBILITY_PLAN.md) for the concrete strategy.

## Before Publishing More Material

Review [PUBLIC_PRIVATE_BOUNDARY.md](PUBLIC_PRIVATE_BOUNDARY.md) and [PUBLIC_RELEASE_CHECKLIST.md](PUBLIC_RELEASE_CHECKLIST.md) so private outreach operations and unsupported claims do not leak into the public repository.
