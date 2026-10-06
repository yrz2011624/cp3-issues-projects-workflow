# Checkpoint 3 — Issues & Project Management

## Goal

Show that you can plan work with an Issue, track the work in a Kanban-style GitHub Project, record a self-check message before merging, and close the work only after the check/merge workflow is complete.

## Start the exercise

[![Copy Exercise](https://img.shields.io/badge/COPY%20EXERCISE-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=GitHub-Issues-Projects-Workflow&owner=%40me&name=cp3-issues-projects-workflow&description=Checkpoint+3:+Issues+%26+Project+Management&visibility=public)

Keep the copied repository **Public** so the KLIS-CS mother repository can read the trusted automatic grader output.

After the copy is created:

1. Wait a few seconds for GitHub to create the **Exercise Issue automatically**.
2. Open **Issues** and read **Exercise: Checkpoint 3 — Issues & Project Management**.
3. Find your exact required branch name in that Issue.
4. Clone the copied repository and complete the checkpoint locally.

You do **not** need to open **Actions** or manually run a workflow.

## Required branch

```text
cp3-YOUR-GITHUB-USERNAME
```

## Challenge

Your feature request is:

> Add a dark-mode button to the website.

Complete the work using the workflow below.

### 1. Create the Project board first

Create **one GitHub Project** and use a **Board** view with these four status columns:

```text
Todo → In Progress → Review → Done
```

Use these exact status names. This Project is the single place where you track both the Issue and the Pull Request.

### 2. Create and track the Issue

Create a student work Issue whose title begins with `[CP3]`.

The Issue must include:

- a clear **Goal**;
- at least two acceptance-criteria checkboxes using `- [ ]`;
- at least one label;
- yourself as an assignee.

Add the Issue to your Project.

Move the Issue through the workflow as the work changes:

```text
Todo → In Progress → Review → Done
```

Start it in **Todo**. Move it to **In Progress** when you begin the work.

### 3. Complete the branch work

Complete `submission.md` on the required `cp3-YOUR-GITHUB-USERNAME` branch, commit, and push.

Record the **Project URL** and the four required statuses in `submission.md`.

You do **not** need to type an Issue number or Pull Request number into `submission.md`. The grader detects them automatically.

### 4. Open the Pull Request and enter Review

Open a Pull Request from your required CP3 branch to `main`.

Then:

1. Add the Pull Request to the **same GitHub Project** as the Issue.
2. Move both the Issue and Pull Request to **Review**.
3. Before merging, inspect your own Pull Request and leave a clear **self-check message** in the PR Conversation, such as `Self-check complete: files, Issue link, and submission verified. Ready to merge.`

Do **not** merge before your self-check message is posted.

### 5. Merge and finish the workflow

After you have completed and recorded the self-check:

1. Merge the Pull Request into `main`.
2. Move both the Issue and Pull Request to **Done** in the Project.
3. Close the Issue after the merge if it did not close automatically.

The automatic grader verifies that a qualifying student self-check message was posted **before** the merge. A message added after the merge does not satisfy the requirement.

GitHub Project board evidence remains teacher-reviewed because repository Actions do not reliably have access to user/organization Projects.

## Scoring

- **60 points** — automatic Git/GitHub evidence, including branch workflow, Issue structure, pre-merge self-check message, merge order, Issue closure, and submission
- **40 points** — teacher review of Issue quality, Project/Kanban evidence, concepts, and reflection

For full Project evidence, the teacher checks that:

- the board has **Todo / In Progress / Review / Done**;
- the CP3 Issue and CP3 Pull Request are both tracked in the same Project;
- both items finish in **Done**;
- the workflow reflects a sensible progression rather than a final-state-only setup.

Your copied repository uses the original **Exercise Issue** as the student-facing status page. The automatic grader updates the score table in that same Issue; it does not create separate Progress or Score Issues.

## Submit for teacher grading

Submit only after the Pull Request has a self-check message, has been merged, and the Project is in its final state.

[![Submit CP3](https://img.shields.io/badge/SUBMIT%20CP3-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow/issues/new?template=cp3-submission.yml)

The teacher grades from the **KLIS-CS mother repository** using:

```text
/manual-grade
Issue quality: 0/10
Project evidence: 0/10
Concepts: 0/15
Reflection: 0/5

Feedback:
Write concise feedback here.
```

After the teacher grade is published, the `/40` teacher score and feedback are synchronized into the student's original **Exercise Issue**.

```text
Student repository
→ automatic /60
→ student self-check message in PR
→ merge
→ Issue + PR finish in Done
→ Submit CP3
→ mother repository /manual-grade /40
→ student's original Exercise Issue updates
→ Final score /100
```

The score sync updates automatically after grading and also checks about once per hour. Students do **not** need to run anything from **Actions**.

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| CP2 | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| **CP3 — You are here** | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
