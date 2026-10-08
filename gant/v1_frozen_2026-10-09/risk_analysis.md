# Risk Analysis

Frozen as of 2026-10-09. See [`gantt_v1.md`](gantt_v1.md) for the corrected Gantt these risks refer to.

## Scoring criteria

Risk = Likelihood (L) x Impact (I), each rated from 1 to 3.
Risk level: 1-2 = Low, 3-5 = Medium, 6-9 = High.

| Value | Likelihood | Impact |
|---|---|---|
| 1 | Low: unlikely to happen | Minor: solved easily, no delay |
| 2 | Medium: may happen | Moderate: delays a task or work package |
| 3 | High: likely to happen | Severe: puts a milestone or the final deliverable at risk |

## Risk register

L x I was recomputed for every row below; all seven match the level originally stated, so no mismatches were found. R4's affected scope was filled in as WP3 + task 4.1 (the cross-explanation session named in its statement) per your instruction - it was blank in the source document.

| ID | Risk | Cause | Affected WP | L | I | Score | Level |
|---|---|---|---|---|---|---|---|
| R1 | A team member is unavailable for several days | Exams, illness or overlapping deadlines | All | 2 | 2 | 4 | Medium |
| R2 | Lack of suitable data (example: no PDB structure for the variant, database unavailable...) | Dependence on UniProt, InterPro, OMIM... | WP2, WP3 | 2 | 3 | 6 | High |
| R3 | Overload of one team member | A member owns a lot of tasks and hasn't enough time | All | 2 | 2 | 4 | Medium |
| R4 | Errors in alignments or biological interpretation | Team is still learning the tools and integrating data sources | WP3, 4.1 | 2 | 2 | 4 | Medium |
| R5 | Inconsistent style or references in the report | Each section is written by a different person | WP4 | 2 | 1 | 2 | Low |
| R6 | Delay in the bioinformatic analysis | Underestimated task or unexpected problems with data or tools | WP3 | 2 | 3 | 6 | High |
| R7 | Failure in the final submission | Last-minute problems with GitHub, Moodle or file formats | WP4 | 1 | 3 | 3 | Medium |

## Risk statements

**R1** - Our identified risk is that a team member is unavailable for several days, we have realized because of illness, exams or overlapping deadlines from other subjects; our contingency plan consists of assigning a backup person to every task, keeping the Project Status document updated so anyone can take over, and redistributing the affected tasks in a team meeting within 24 hours.

**R2** - Our identified risk is the lack of suitable data for the analysis, we have realized it because the project depends on external databases (UniProt, PDB, OMIM and InterPro) and a structure of the variant protein may not exist or the services may be temporarily unavailable; our contingency plan consists of downloading and saving all the data in the GitHub repository as soon as it is retrieved, using a homology model or an alternative variant if no experimental structure is available, and justifying in the report any topic excluded from the scope.

**R3** - Our identified risk is the overload of one or more team members, we have realized it because several tasks of WP2 (2.1 to 2.7) run in parallel between 01/10 and 13/10 and some members own more than one of them at the same time; our contingency plan consists of monitoring the workload of each member in the Project Status document, transferring tasks to other members with a lighter workload when needed, and reviewing the distribution of tasks in the weekly meeting.

**R4** - Our identified risk is errors in the alignments or in the biological interpretation, we have realized because the team is still learning the tools and the analysis requires integrating several data sources; our contingency plan consists of cross-checking the results between two members during the cross-explanation session (task 4.1), documenting all the parameters used, and consulting the instructor in case of doubt.

**R5** - Our identified risk is inconsistent style or references in the report, we have realized because each section is written by a different person; our contingency plan consists of agreeing in advance on a common citation style, format and template for all sections, and carrying out a joint review (task 4.8) before submission.

**R6** - Our identified risk is a delay in the bioinformatic analysis (WP3), we have realized it because the tasks may take longer than planned due to underestimated effort or unexpected problems with data or tools; our contingency plan consists of leaving a margin of 2 working days before the report writing starts, sharing partial results with the report writers as soon as they are available, and reassigning a member with free capacity to the delayed task.

**R7** - Our identified risk is a failure in the final submission, we have realized it because the submission takes place close to the deadline and problems with Moodle, GitHub or file formats may appear; our contingency plan consists of finishing the joint review (task 4.8) at least one working day before the deadline, submitting early, and keeping a verified copy of the repository and the report.

## Typo fixes applied

Only the following were changed from the source document; everything else (including informal phrasing like "hasn't enough time") was kept exactly as written:

- "IntrePro" -> "InterPro" (register, R2 cause)
- "exemple" -> "example" (register, R2 risk)
- "overplanning deadlines" -> "overlapping deadlines" (register, R1 cause - matches the R1 statement, which already had it right)
- "Github" -> "GitHub" (register, R7 cause - the R7 statement already used "GitHub")
- "joint view" -> "joint review" (R5 statement - matches task 4.8's actual name, "Joint review")

R3's and R7's references to task numbers/dates ("WP2 (2.1 to 2.7)... between 01/10 and 13/10", "task 4.8", "task 4.1") did not need updating - they already matched the corrected Gantt, so the statements are reproduced exactly as in the source document.
