# Teacher Grading — Checkpoint 3

Final score: **60 automatic + 40 teacher-reviewed = 100**.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Issue quality | Goal is clear and acceptance criteria are testable | 10 |
| Project evidence | One Project uses **Todo / In Progress / Review / Done**; the CP3 Issue and PR are both tracked there; both finish in **Done** after check/merge | 10 |
| Conceptual understanding | Accurately explains Issues, acceptance criteria, Projects, and why a self-check occurs before merge | 15 |
| Reflection | Specific explanation of the transition from Review to Done | 5 |
| **Total** |  | **40** |

## Automatic evidence to verify

The student repository automatic grader checks the GitHub evidence that should not require manual scoring:

- required CP3 branch/workflow identity;
- student-created `[CP3]` Issue;
- Goal and acceptance-criteria checklist;
- Issue assignment and label;
- Pull Request targeting `main`;
- at least one clear PR Conversation self-check message from the student;
- the check-message timestamp is before the merge timestamp;
- Pull Request was merged;
- student Issue was closed after the merge;
- `submission.md` is complete and records the required Project statuses.

The branch itself may be deleted after merge. That is valid: the grader uses the Pull Request head ref/commit as durable evidence.

## Entering the Teacher Grade

Students submit to the **KLIS-CS mother repository** only after the self-check message, merge, and final Project cleanup.

Open the student's CP3 submission Issue in the mother repository and post a **new comment** using:

```text
/manual-grade
Issue quality: 0/10
Project evidence: 0/10
Concepts: 0/15
Reflection: 0/5

Feedback:
Write concise feedback here.
```

Replace the four scores and add concise feedback. The workflow calculates the 40-point teacher subtotal automatically and combines it with the automatic 60 points.

Example:

```text
/manual-grade
Issue quality: 9/10
Project evidence: 10/10
Concepts: 13/15
Reflection: 4/5

Feedback:
Clear Issue and acceptance criteria. The Project correctly tracks both the Issue and PR through Review to Done after the self-check.
```

The newest valid grading comment by `hbycwyh2008` is used. To change a grade, post a new completed template.

The older short form remains supported for compatibility:

```text
/manual-grade 36
```

## Recommended teacher check

Open the student's Project before grading and verify all of the following:

- Board view has the four required status columns: **Todo, In Progress, Review, Done**.
- The student's `[CP3]` Issue is a Project item.
- The student's CP3 Pull Request is a Project item in the **same Project**.
- The Pull Request Conversation shows a qualifying self-check message from the student before merge.
- Both Project items finish in **Done**.
- The Issue is closed only after the checked Pull Request is merged.

Project history is teacher-reviewed; do not award full Project evidence for a board that was populated only after all work was already complete.
