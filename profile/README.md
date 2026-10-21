<p align="center">
  <img src="pump-logo.png" alt="PUMP" width="260">
</p>

<h1 align="center">PUMP Consortium</h1>

<p align="center">A multi-institution collaboration on machine perfusion of donor livers: a shared registry, shared tooling and shared analyses.</p>

## What lives here

Code, documentation and frozen model definitions produced by PUMP members. Per-case registry data, feature tables and per-liver scores are **not** stored in these repositories; they live on the governed data share and are available to entitled members through the registry's data steward.

| Repository | What it holds |
| --- | --- |
| `nmp-performance-index` | The NMP Performance Index: feature pipeline, scoring rule (versioned anchors and domain weights), validation experiments, figures |
| `pump-qc-pipeline` | Quality-control rules for registry entries, shared by the QC web app |
| `pump-qc-webapp` | The registry QC web application |
| `pump-data-dictionary` | The PUMP variable schema and cross-centre mapping specifications |

## Member institutions

- Icahn School of Medicine at Mount Sinai, New York
- Cleveland Clinic, Cleveland

## Working in this organisation

- Repositories are private to members. Ask the organisation owners for access.
- Every analysis that produces a number used in a paper has a numbered script and a written output in its repository, so results can be reproduced from the registry export it names.
- Model rules are frozen and versioned (for example `nmp_index_rule_v3_median`); a rule is never edited in place.
- Do not commit registry data. Each repository's `.gitignore` excludes its `data/` folder; if a data file is committed by mistake, tell an owner before anything else, because Git history keeps it.

## Contact

Organisation owners are listed on the People page. For data access, contact the registry's data steward.
