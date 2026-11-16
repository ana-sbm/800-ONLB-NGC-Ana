# SP800Project architecture review draft

Owner: A. Crone. Filename prefix: DevFTDI245R. Draft version: 0.3.
Template package: dsnArchitectureDesignTemplate-2.33, architecture version 2.33.
Reusable template is retained separately from ArchitectureProject-2.33.

Main source: DevFTDI245RManual.tex. Output: DevFTDI245RManual.pdf.
Scope: host application qualifies and publishes sensor data; hardware, driver,
and consumer are external. Embedded Systems profile: Applicable, confirmed by
A. Crone on November 14, 2026. Owner review of the resulting draft is pending.

## Build

Required tools: pdflatex, bibtex, makeglossaries, makeindex, latexmk, and Perl.
Run `./DevFTDI245RBuild.ps1 -Action pdf` from PowerShell with the tools on PATH.
Local tool location, versions, actual commands, and check results are recorded
in DevFTDI245RBuildReport.md after execution.

## Review boundaries

The initial chapters contain confirmed facts and owned open questions. Later
chapters retain clearly marked template examples with their original IDs and
reciprocal mappings; none establish SP800Project requirements or passing results.
The target platform, hardware revisions, encoding, timing limits,
and course publication policy remain open. See the Development Plan.
No product implementation, hardware tests, or stakeholder validation occurred.

New project files use DevFTDI245R. AGENTS.md, CLAUDE.md, and SKILL.md are
tool-mandated discovery exceptions. Unmodified upstream cornell/IEEE class
and bibliography-style files retain their original names as external assets.
Git publication and baseline acceptance await owner review. Reviewed PDF
delivery policy remains undecided; a review copy is provided locally.

## Corrected review copy

Draft 0.3 was compiled and checked on November 15, 2026 in this writable
review copy. The original F: project was not modified by this correction.
See DevFTDI245RBuildReport.md for the full build and review evidence.

Current project name: SP800Project. Organization: Stephens University, 2026F SPE 800-ONLB-NGC.
