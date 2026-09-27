# Capability to Knowledge-Pack Map

Working artifact mapping sector technical capabilities to the pack chapters that provide
reference depth for each capability. Live catalogue: faa-8110-49 (13 chapters + glossary + cheatsheet) and easa-rules (7 chapters + glossary + cheatsheet), 24 entries.

Rules of construction:
- Every chapter in every pack under `packs/<slug>/chapters/` is assigned to exactly one capability cluster (best fit).
- Signpost packs contain no chapters and are not mapped.
- Machine-readable version: `docs/capability-pack-map.json`.
- Machine-readable classification rules: `docs/classification-rules.json`.
- Changelog (v0.1.0): faa-8110-49 live map across three aviation clusters.

## Summary

| Cluster | Entries |
|---|---|
| 1. Certification Liaison & Oversight | 10 |
| 2. Software Development Assurance | 8 |
| 3. Airborne Electronic Hardware | 6 |
| **Total** | **24** |

## 1. Certification Liaison & Oversight

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch01-airborne-approval-map.md | Which FAA document answers which airborne software or AEH question; AC-to-RTCA/EUROCAE recognition chain |
| faa-8110-49 | ch02-software-review-process.md | Certification liaison, desk versus on-site software review, review planning, and review-process objectives |
| faa-8110-49 | ch03-level-of-faa-involvement.md | LOI criteria and Appendix A worksheet scoring for sizing FAA software involvement |
| faa-8110-49 | ch04-software-conformity-inspection.md | Software part and installation conformity, ASE/ASI tasks, and Form 8120-10 |
| faa-8110-49 | glossary.md (support file) | Shared FAA airborne software and AEH terms used across the pack |
| faa-8110-49 | cheatsheet.md (support file) | Cross-chapter decision checklists for software review, LOI, conformity, and AEH questions |
| easa-rules | ch01-moc-map.md | Where the means of compliance lives: EASA AMC-20, the paywalled RTCA/EUROCAE text, and the FAA AC twin |
| easa-rules | ch07-joint-sw-aeh-workflow.md | Joint software and AEH certification workflow; AMC 20-189 named, not fetched |
| easa-rules | glossary.md (support file) | EASA software and AEH terms used across the easa-rules chapters |
| easa-rules | cheatsheet.md (support file) | Decision tree routing software, AEH, and multi-core questions to the right easa-rules chapter |

## 2. Software Development Assurance

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch05-do-178c-recognition-and-transition.md | AC 20-115D recognition of ED-12C/DO-178C, process reuse, life-cycle data, and tool-qualification transition |
| faa-8110-49 | ch06-legacy-software-fls-ums.md | Supplements, field-loadable and user-modifiable software, and legacy software modification flow |
| faa-8110-49 | ch11-software-change-impact-analysis.md | CIA best-practice checklist from AC 00-69 section 3.1: what a change impact analysis identifies and which change classes it addresses |
| faa-8110-49 | ch12-data-and-control-coupling-practices.md | Data coupling and control coupling are distinct and both required; design-phase interface and dependency specification supports the verification objective |
| faa-8110-49 | ch13-design-level-error-handling.md | Design-level error handling: foreseeable error sources, mitigation in requirements, runtime protection named for levels A and B |
| easa-rules | ch02-amc-20-115d-scope.md | AMC 20-115D applicability: product certification, ETSO software, and what replacing AMC 20-115C changed |
| easa-rules | ch03-software-assurance-115d.md | Software assurance as AMC 20-115D frames it, without a DO-178C objective dump |
| easa-rules | ch04-transition-tools-gm.md | GM1 to GM3 (CIA, coupling, error handling) and the tool-qualification pointer, name-only |

## 3. Airborne Electronic Hardware

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch07-aeh-custom-devices.md | AC 20-152A custom-device assurance: simple versus complex devices and DO-254 applicability |
| faa-8110-49 | ch08-aeh-verification-tools-reuse.md | AEH robustness, HDL coverage, tool assessment, previously developed hardware, and Appendix A clarifications |
| faa-8110-49 | ch09-aeh-cots-ip.md | COTS IP selection, provider data, planning, verification, and Appendix B considerations |
| faa-8110-49 | ch10-cots-devices-and-cbas.md | COTS device complexity assessment and circuit board assembly development assurance |
| easa-rules | ch05-amc-20-152a-scope.md | AMC 20-152A applicability: AEH at DAL A, B, and C, and what the AMC adds beyond ED-80/DO-254 |
| easa-rules | ch06-aeh-objectives.md | Custom devices, COTS IP, COTS devices, and CBAs, as original summaries of the AMC objectives |
