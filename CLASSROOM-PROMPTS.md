# Copy these prompts during the labs

These prompts match the projected slides. Open the named project before pasting. Wait for each result before moving to its check.

## Slide 19: A request for a sourced weekly update

Project: 00-start

```text
Goal: Prepare a concise project update for the VP.
Context: Use sources/ and the reporting period in PROJECT-README.md.
Constraints: Summarize this folder. Flag stale, conflicting or unconfirmed information. Do not invent owners, dates or figures. Keep source files unchanged.
Done when: Save output/folder-review.md and output/monday-brief.md. Cover changes, decisions, risks and actions. Cite the source filename and date or row for each factual claim. List unresolved questions.
```

## Slide 38: Audit the prepared Northstar update

Project: 00-start · use the supplied flawed sample

```text
Audit prepared-review/flawed-brief.md against sources/.

For each disputed claim, show the claim, supporting or conflicting evidence, and proposed correction. Check dates, ownership and the budget total.

Save output/review-audit.md and output/corrected-brief.md.
```

## Slide 39: Check the corrections against their sources

Same chat in 00-start · send after the audit finishes

```text
Open output/review-audit.md and output/corrected-brief.md.

For the launch date, checklist owner and budget total, show the corrected claim and the exact source filename, date or row that supports it.

If a claim is unsupported or a correction is missing, revise only that claim using sources/. Preserve uncertainty and keep the original source files unchanged.
```

## Slide 49: Choose and save your task card

New project: 01-my-recurring-task · start a fresh chat

```text
Read PROJECT-README.md and AGENTS.md.

Show the three examples in course-guide/task-examples/ and ask which one I want to use or adapt. Wait for my choice.

Then copy that example into course-guide/TASK-CARD.md. Confirm the audience, approved input path, reporting window, output and quality check with me. Keep the practice inputs unchanged.
```

## Slide 50: Create your task’s Codex skill

Project: 01-my-recurring-task · finish the task card first

```text
$skill-creator

In this personal-task project, read PROJECT-README.md, AGENTS.md and course-guide/TASK-CARD.md. Confirm the chosen task, audience, approved input path, reporting window, output and quality check. Flag missing fields or conflicting project guidance before building. Create an instruction-only skill for that task with a unique name and clear trigger. Handle missing or conflicting inputs. Show where it is saved and how to invoke it. Preserve existing skills and source files. Do not import the Northstar audience, dates or budget rules unless this task explicitly requires them.

Record the final skill name and invocation in course-guide/TASK-CARD.md.
```

## Slide 51: Run your skill and verify its result

Project: 01-my-recurring-task · use the skill just created

```text
Read the skill name and invocation in course-guide/TASK-CARD.md. Invoke that installed skill for the selected inputs and reporting window.

Open the saved result. Show one factual claim beside its original source passage, and report whether the quality check passed.

Then use a separate test copy with one required input missing. Run the skill there and show how it handles the gap. Preserve the original inputs. Record both results in course-guide/COMPLETION-CARD.md.
```
