# solveit-workflows

Example workflows built from [SOLVE-IT](https://solveit-df.org/) techniques, held as JSON
files that the [SOLVE-IT Workflow Builder](https://workflows.hargs.co.uk/) can open and
render as a diagram.

Each entry below has an **Open** link that loads the file straight into the builder, so a
workflow can be looked at without downloading anything.

## Drafts

Linear workflows describing a process from start to finish. These are working versions and
are expected to change.

| Workflow | What it covers | |
|---|---|---|
| [`find_files_by_hash.json`](drafts/find_files_by_hash.json) | Seized media through to a tag-based automated report, with hash-based identification of the relevant files. | [Open](https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/drafts/find_files_by_hash.json) |

## Illustrations

These are not linear workflows and make use of the Workflow Builder to create diagrams of
bigger systems.

| Workflow | What it covers | |
|---|---|---|
| [`recreation-of-abstract-forensic-tool-figure-1.json`](illustrations/recreation-of-abstract-forensic-tool-figure-1.json) | Figure 1 of Hargreaves, Nelson and Casey (2024), redrawn using SOLVE-IT techniques. | [Open](https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/illustrations/recreation-of-abstract-forensic-tool-figure-1.json) |
| [`modern-forensic-tool-architectures.json`](illustrations/modern-forensic-tool-architectures.json) | The processing a current tool suite performs on a disk image or mobile extraction, in regions covering operating system artefacts, application artefacts, artefact aggregation and dynamic search. | [Open](https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/illustrations/modern-forensic-tool-architectures.json) |
| [`use-an-ai-based-prompt-for-interrogating-case-data.json`](illustrations/use-an-ai-based-prompt-for-interrogating-case-data.json) | The same architecture with an AI layer added on top, showing which underlying techniques an AI-driven query of the case data depends on. | [Open](https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/illustrations/use-an-ai-based-prompt-for-interrogating-case-data.json) |



## Demonstrators

| Workflow | What it covers | |
|---|---|---|
| [`simplified_imaging_demo.json`](simplified_imaging_demo.json) | Removing a disk from a device, choosing between a hardware and a software write blocker, and storing the result in a forensic container format. | [Open](https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/simplified_imaging_demo.json) |

`legacy/simplified_imaging_demo.json` is an earlier version of the same workflow, kept in
the older file format (short keys such as `tt`, `n` and `e`). The builder still imports it
and converts it the first time it is saved.

## Opening a workflow

The **Open** links use the builder's `#fetch=` form, which takes the address of a workflow
file and loads it:

```
https://workflows.hargs.co.uk/#fetch=https://raw.githubusercontent.com/chrishargreaves/solveit-workflows/main/<path>.json
```

The workflow opens as an unsaved session, so use **Save to library** in the builder to keep
any edits. Alternatively, download the `.json` file and use **Import** on the welcome
screen, or paste a GitHub file address into **Load from URL…**, which converts it to the
raw address for you.

## Proposing a change

Open the workflow in the builder, edit it, then use **Export workflow ▾ → JSON**. Submit the
updated file through GitHub in the usual way, by editing the file in the repository and
choosing **Propose changes** to open a pull request.

## Licence

Apache License 2.0. See [LICENSE](LICENSE).
