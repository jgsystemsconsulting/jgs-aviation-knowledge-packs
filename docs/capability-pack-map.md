# Capability to Knowledge-Pack Map

Working artifact mapping sector technical capabilities to the pack chapters that provide
reference depth for each capability. Live catalogue: faa-8110-49 (10 chapters + glossary + cheatsheet).

Rules of construction:
- Every chapter in every pack under `packs/<slug>/chapters/` is assigned to exactly one capability cluster (best fit).
- Signpost packs contain no chapters and are not mapped.
- Machine-readable version: `docs/capability-pack-map.json`.
- Machine-readable classification rules: `docs/classification-rules.json`.
- Changelog (v0.1.0): faa-8110-49 live map across three aviation clusters.

## Summary

| Cluster | Entries |
|---|---|
| 1. Certification Liaison & Oversight | 6 |
| 2. Software Development Assurance | 2 |
| 3. Airborne Electronic Hardware | 4 |
| **Total** | **12** |

## 1. Certification Liaison & Oversight

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch01-airborne-approval-map.md | Which FAA document answers which airborne software or AEH question; AC-to-RTCA/EUROCAE recognition chain |
| faa-8110-49 | ch02-software-review-process.md | Certification liaison, desk versus on-site software review, review planning, and review-process objectives |
| faa-8110-49 | ch03-level-of-faa-involvement.md | LOI criteria and Appendix A worksheet scoring for sizing FAA software involvement |
| faa-8110-49 | ch04-software-conformity-inspection.md | Software part and installation conformity, ASE/ASI tasks, and Form 8120-10 |
| faa-8110-49 | glossary.md (support file) | Shared FAA airborne software and AEH terms used across the pack |
| faa-8110-49 | cheatsheet.md (support file) | Cross-chapter decision checklists for software review, LOI, conformity, and AEH questions |

## 2. Software Development Assurance

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch05-do-178c-recognition-and-transition.md | AC 20-115D recognition of ED-12C/DO-178C, process reuse, life-cycle data, and tool-qualification transition |
| faa-8110-49 | ch06-legacy-software-fls-ums.md | Supplements, field-loadable and user-modifiable software, and legacy software modification flow |

## 3. Airborne Electronic Hardware

| Pack | Chapter | Why it fits / one-line value |
|---|---|---|
| faa-8110-49 | ch07-aeh-custom-devices.md | AC 20-152A custom-device assurance: simple versus complex devices and DO-254 applicability |
| faa-8110-49 | ch08-aeh-verification-tools-reuse.md | AEH robustness, HDL coverage, tool assessment, previously developed hardware, and Appendix A clarifications |
| faa-8110-49 | ch09-aeh-cots-ip.md | COTS IP selection, provider data, planning, verification, and Appendix B considerations |
| faa-8110-49 | ch10-cots-devices-and-cbas.md | COTS device complexity assessment and circuit board assembly development assurance |
