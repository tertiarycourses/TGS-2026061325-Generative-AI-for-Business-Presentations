# Courseware QA Report — v2.0

**Course:** Generative AI for Business Presentations  
**Course code:** TGS-2026061325  
**QA date:** 13 August 2026  
**Status:** PASS — ready for controlled publication

## Courseware gate

| Check | Result | Evidence |
|---|---|---|
| Current WSQ admin slides | PASS | Two trainer profiles, LMS download visual, assessment-flow visual, practice-exam link, versioned cover and assessment briefing are present. |
| Deck design | PASS | 132 slides; visual cards, chevron flows, scorecards, process maps, before/after examples, data visuals and four original learning-unit hero images. |
| No procedural slide walls | PASS | Detailed software steps are confined to the Learner Guide and activity instructions. |
| Business-presentation principles | PASS | Objective, audience, structure, visual evidence, delivery, Q&A, negotiation, review, do/don'ts and examples are covered. |
| PPTX structural validation | PASS | Main deck and all eight activity PPTX files passed Office Open XML validation. |
| Visual QA | PASS | Full contact sheets plus targeted renders reviewed; title, citation, connector, clipping and source-page defects corrected and re-rendered. |
| Learner Guide | PASS | 26-page DOCX/PDF with detailed numbered procedures, prompt guidance, tool controls and eight aligned activities. |
| Lesson Plan | PASS | 9-page DOCX/PDF; 480 minutes per day, 16 hours total, two-hour assessment block, and exact current activity slide mappings. |
| Activity packs | PASS | Eight individual folders; each contains `INSTRUCTIONS.md`, `CHECKLIST.md` and an editable sample PPTX. |

## Assessment gate

| Mapping | Instrument evidence | Result |
|---|---|---|
| K1 | Written Examination (WA/WE) Q1 | PASS |
| K2 | Written Examination (WA/WE) Q2 | PASS |
| K3 | Written Examination (WA/WE) Q3–Q4 | PASS |
| A1 | Case Study Task 1; Activity 1–2 workflow | PASS |
| A2 | Case Study Task 2; Activity 3–5 workflow | PASS |
| A3 | Case Study Task 3; Activity 6–7 workflow | PASS |
| A4 | Case Study Task 4; Activity 8 workflow | PASS |

- Original structure preserved: Written Examination (published under the current WA convention; legacy name WE) plus Case Study; 60 minutes each.
- Original item counts preserved: four WE questions and four CS tasks.
- Candidate papers and answer keys are three pages each and include WSQ covers.
- Candidate papers contain clickable LMS links.
- Instruments are open-ended; no multiple-choice questions were introduced.
- Answer keys are trainer-only and excluded from GitHub and learner-visible TMS fields.

## Release boundary

Public GitHub scope is limited to final courseware, activities, source coverage, QA report, preview and README. `.env`, references, assessments, answer keys, QA renders, generated image source assets and build tooling are excluded.

## Post-rename verification

On 13 August 2026, the repository root was renamed from `labs/` to `activities/`. The exact current package was rechecked after the rename:

- `activities/` contains eight direct activity folders, eight instruction files, eight checklists and eight editable sample PPTX files; no `labs/` path remains.
- Main deck: 132 slides; OOXML validation passed; zero step-by-step procedure markers.
- All eight activity PPTX files and all six DOCX courseware/assessment files passed OOXML validation.
- Activity-tree SHA-256: `f6095e0d20ef272e0bd04fc275c8e9e9b7acdc66c102217611f72f6da61e4f3e`.
- The six published courseware files are byte-identical to the previously approved, rendered and visually inspected release.
