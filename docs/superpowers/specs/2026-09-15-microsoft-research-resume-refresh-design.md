# Microsoft Research Resume Refresh Design

Date: 2026-09-15

## Objective

Replace the September 11 Microsoft Research Undergraduate Research Internship resume with a stronger one-page version built from the latest master CV. The resume should use nearly all available page space while remaining readable, ATS-compatible, and factually traceable.

## Target

- Employer: Microsoft Research
- Role: Undergraduate Research Internship — Computing
- Primary emphasis: AI agents and multi-agent systems; algorithms, theory, and mathematical foundations; information retrieval, search, and recommendations
- Supporting approaches: machine learning and generative AI; algorithms and theoretical analysis; optimization, control, and reinforcement learning

## Content Strategy

Use a research-first narrative with systems depth:

1. Lead with UCSB ArchLab research. Use four or five complementary bullets covering the research problem, model and systems implementation, reproducibility and numerical safeguards, controlled experiments, and a carefully scoped result.
2. Present NeuralNetworksRust first among projects. Use two or three bullets to connect tensor representation, reverse-mode autograd, optimization, and numerical validation to hardware-aware ML systems research.
3. Include Conduit as evidence of systems and infrastructure engineering: networking, concurrency, security, failure recovery, and measured file-transfer performance.
4. Include Orator.ai as evidence of agent-like interaction and end-to-end generative-AI system building.
5. Keep The Coder School only if it fits without displacing stronger research evidence; one concise bullet may support communication and mentorship.
6. Retain Eagle Scout in the header.
7. Omit coursework and unrelated projects.

## Factual Boundaries

- Preserve the distinction between measured activation sparsity and memory, FLOP, latency, or parameter reduction.
- Present full-split WER figures as baseline evaluation results, not training improvements.
- Do not claim that the 23-configuration isolation matrix was fully executed.
- Do not use disputed or unverified results from the September research report.
- Do not claim hardware profiling, production deployment, publication, or formal multi-agent research without evidence.
- Trace every claim to the master CV or the existing verified Microsoft application materials.

## Layout

- Replace the existing September 11 `.tex` and `.pdf` files in place.
- Keep a single-column, ATS-safe LaTeX layout with no tables, graphics, sidebars, or text boxes.
- Use Education, Research Experience, Selected Projects, and Technical Skills.
- Target one page with approximately 90–97% vertical utilization: no second page, clipped text, overlap, or visibly empty lower quarter.
- Maintain clear section rules, aligned dates and locations, compact bullets, and readable type.
- Keep project links concise and right aligned.

## Verification

1. Compile the LaTeX source successfully.
2. Confirm the PDF has exactly one page.
3. Extract text to confirm expected sections, links, and no lost content.
4. Render the page to an image and inspect spacing, alignment, density, clipping, and overflow.
5. Check the LaTeX log for overfull or underfull boxes and warnings.
6. Run a final factual comparison against the master CV and existing Microsoft application review.

## Deliverables

- Updated Microsoft Research resume source at the existing September 11 path.
- Recompiled one-page PDF at the matching existing path.
- No changes to the master CV, research-interest statement, application answers, or other tailored resumes unless required to correct a directly conflicting resume fact.
