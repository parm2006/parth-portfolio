# General and Research Resume System

## Goal

Maintain two one-page resumes from one verified evidence bank:

- **General:** targets software engineering, ML engineering, AI product, and systems roles.
- **Research:** targets ML systems, optimization, AI-agent, and undergraduate research roles.

Both resumes must show systems and infrastructure depth. Both must retain Eagle Scout in the header.

## Content strategy

The General resume leads with broad engineering execution. It emphasizes ArchLab, NeuralNetworksRust, Conduit, Orator.ai, and selected full-stack work. Its systems evidence includes Rust, CUDA, networking, concurrency, testing, and release engineering.

The Research resume leads with zeroth-order optimization, controlled experiments, numerical stability, and model evaluation. NeuralNetworksRust supplies the low-level tensor and autograd foundation; Conduit supplies infrastructure and reliability evidence; Orator.ai supplies agent-like, multi-stage AI-system experience.

Coursework may remain in the master evidence bank but will not occupy project space in either one-page resume.

## Source of truth

`tmp/resume-update/MASTER-CV-neuralnetworksrust.md` is the current evidence bank. The refresh process may promote new claims only when supported by conversation history, inspected repository content, authored Git history, or user confirmation. Unverified metrics stay in the fact-check queue.

## Outputs

Create a dated folder under `resumes/general/` containing editable LaTeX and compiled PDF for:

1. `Parth_Mohnot_General_Technical`
2. `Parth_Mohnot_Research_ML_Systems`

Each PDF must remain one page, use selectable text, preserve working links, and pass visual inspection.

The Microsoft Research resume is separate, but its header must also restore Eagle Scout.

## Biweekly refresh

Every two weeks, a thread-attached Codex task will:

1. Review relevant conversation history, the master evidence bank, the fact-check queue, workspace Git history, and accessible verified GitHub changes.
2. Record new supported facts in the evidence bank before editing resumes.
3. Rebuild only the General and Research base resumes when evidence materially changes them.
4. Compile, extract text, confirm one-page layout, inspect rendered pages, and report changed claims with their evidence.
5. Leave tailored company resumes unchanged.
6. Stay quiet when no meaningful update exists; notify on completed changes, failed verification, or required user confirmation.

## Safety and correctness

- Never invent metrics, dates, roles, publications, deployment claims, or performance improvements.
- Never treat activation sparsity as measured memory, FLOP, or parameter reduction.
- Preserve user-owned edits and avoid broad regeneration of unrelated resume packages.
- Keep prior dated versions; create a new dated snapshot instead of deleting history.
