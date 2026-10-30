# Pass percentages of Indian professional exams: CA, CS and CMA (2016 onwards)

Every pass percentage published by the three Indian professional accounting and secretarial institutes, collected in one place, with a link to the official source for each row.

- **CA** (The Institute of Chartered Accountants of India, ICAI): Foundation, Intermediate (and the older IPCC), Final
- **CS** (The Institute of Company Secretaries of India, ICSI): CSEET, Executive, Professional
- **CMA** (The Institute of Cost Accountants of India, ICMAI): Foundation, Intermediate, Final

Maintained by **Gradehunt** (https://gradehunt.com), an online test series and answer-sheet evaluation platform for CA, CS and CMA students. Gradehunt is not affiliated with ICAI, ICSI or ICMAI.

Live, updated tables and charts: https://gradehunt.com/pass-percentage

## Files

| File | Rows | Coverage |
|---|---|---|
| `data/ca-foundation.csv` | 19 | CA Foundation, May 2018 onwards |
| `data/ca-inter.csv` | 91 | CA Intermediate / IPCC, 2016 onwards, by group |
| `data/ca-final.csv` | 87 | CA Final, 2016 onwards, by group, with new CAs qualified where ICAI states it |
| `data/cs.csv` | 135 | CSEET, CS Executive and CS Professional, by module/group |
| `data/cma.csv` | 89 | CMA Foundation, Intermediate and Final, by group |

## Columns

| Column | Meaning |
|---|---|
| `course` | Course and level (CS and CMA files only; the CA files are one level each) |
| `session` | Exam session as named by the institute, e.g. "May 2026" |
| `session_date` | First day of the session month (YYYY-MM-DD), for sorting |
| `group` | Group, module or "Both groups" / "Overall" as published |
| `scheme` | Syllabus or scheme the result belongs to (e.g. "2023 scheme") |
| `appeared` | Candidates who appeared (blank where the institute published only a percentage) |
| `passed` | Candidates who passed (blank where not published) |
| `pass_percent` | Pass percentage as published by the institute |
| `new_cas_qualified` | CA Final only: number of new Chartered Accountants, where ICAI stated it |
| `source_url` | The official press release or announcement the row comes from |
| `note` | Any caveat for that row (e.g. merged sessions during COVID-19) |

## Method

Figures are copied from the institutes' own result announcements and press releases; nothing is estimated. Where both counts and a percentage are published, the percentage is checked against passed / appeared. CS publishes percentages only, so its counts are blank. Each row links to its source so it can be verified.

## Updates

The live tables at https://gradehunt.com/pass-percentage are updated after each result. Snapshot: 30 October 2026.

## Licence and citation

Licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**. You can use, share and adapt the data, including commercially, as long as you credit Gradehunt with a link:

> Source: Gradehunt, "Pass percentages of Indian professional exams: CA, CS and CMA", https://gradehunt.com/pass-percentage (CC BY 4.0)

Questions or corrections: info@gradehunt.com
