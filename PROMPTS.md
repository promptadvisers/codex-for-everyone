# Full copyable prompts

Open the project named in RUNBOOK.md. Labs 1–2 use 00-start; Lab 3 and your schedule use 01-my-recurring-task. Demo prompts are for watching/reuse later. See SYNTAX-KEY.md.

## Lab 1 — Delegate

Prepare the VP’s weekly update from the fictional Northstar files. The prompt saves a source review and the update itself. Check one factual claim against the original source before marking this exercise done.

~~~text
Goal: Prepare a concise project update for the VP.
Context: Use sources/ and the reporting period in PROJECT-README.md.
Constraints: Summarize this folder. Flag stale, conflicting or unconfirmed information. Do not invent owners, dates or figures. Keep source files unchanged.
Done when: Save output/folder-review.md and output/monday-brief.md. Cover changes, decisions, risks and actions. Cite the source filename and date or row for each factual claim. List unresolved questions.
~~~

## Demo — Reuse an earlier chat

The instructor has prepared a planning chat with the audience and reporting decisions. Add that chat as context before using this prompt; it does not refer to a chat you were expected to create in Lab 1.

~~~text
Use the referenced Monday Brief planning chat for the agreed audience, reporting period and output requirements. Summarize those decisions first, then draft this week's brief from current source files. Flag conflicts between earlier decisions and new evidence.
~~~

## Demo — Plan recurring work

Type `/plan` in the composer and select it before this prompt. Toggle it off before the later save request.

~~~text
I want this project update to run every Monday. Inspect the sample folder and propose the smallest reliable workflow. Identify inputs, output, reporting window, checks and missing decisions. Ask only questions that materially change the plan. Investigate without editing files or creating a schedule.
~~~

## Demo — Save the agreed plan

~~~text
Save the agreed plan as workflow-plan.md. Do not create the schedule yet.
~~~

## Demo — Create project guidance

~~~text
Create a concise AGENTS.md for this project. Include the audience, output location, reporting-period rule, citation requirements, how to handle conflicting sources, how to check totals and how to label unconfirmed owners. Keep it focused on conventions that apply across tasks.
~~~

## Demo — Check guidance in a fresh chat

~~~text
Identify the project guidance that applies in this chat. Then prepare the Monday Brief for the reporting period in PROJECT-README.md. Save output/monday-brief.md and show the checks you completed.
~~~

## Demo — Improve one rule

~~~text
The prepared weekly update counted the same budget item twice. Compare it with sources/budget.csv and propose a small AGENTS.md change that prevents identical duplicate rows from being counted twice. Explain how to handle the same item ID with conflicting amounts and what else the change may affect. Wait for my acceptance before editing the guidance, then rerun the budget check. Preserve the original source files.
~~~

## Demo — Retrieve a connected source

The instructor’s prepared Drive document is titled “O’Reilly Codex Demo - Northstar Update.” It is a fictional extra source for the same project. An addendum is a separate note of supported changes and unresolved conflicts.

~~~text
Find the document named O'Reilly Codex Demo - Northstar Update in the connected Google Drive account. Confirm its title, source link and update date. Compare it with this project's status notes and save a local addendum in output/. Include only supported changes and flag conflicts.
~~~

## Lab 2 — Audit

Stay in Northstar, but open the supplied prepared-review/flawed-brief.md. It intentionally contains mistakes. This exercise uses that sample, not the brief generated in Lab 1.

~~~text
Audit prepared-review/flawed-brief.md against sources/.

For each disputed claim, show the claim, supporting or conflicting evidence, and proposed correction. Check dates, ownership and the budget total.

Save output/review-audit.md and output/corrected-brief.md.
~~~

## Lab 2 — Targeted correction after your evidence check

~~~text
Open output/review-audit.md and output/corrected-brief.md.

For the launch date, checklist owner and budget total, show the corrected claim and the exact source filename, date or row that supports it.

If a claim is unsupported or a correction is missing, revise only that claim using sources/. Preserve uncertainty and keep the original source files unchanged.
~~~

## Demo — Create the Northstar skill

~~~text
$skill-creator

Create an instruction-only skill named oreilly-monday-brief from our tested workflow. Use sources/ and PROJECT-README.md, and write a dated brief under output/. Include the brief template, source citations, conflicting-date handling, unconfirmed owners and duplicate budget IDs. Ask for a reporting period if none is provided. Show where the skill will be saved and how to invoke it. Do not overwrite an existing skill with that name.
~~~

## Demo — Run the Northstar skill

~~~text
$oreilly-monday-brief

Prepare the Northstar brief using the reporting period in PROJECT-README.md. Show the saved file and the checks for dates, ownership and duplicate budget items.
~~~

## Lab 3 — Create and test your skill

~~~text
$skill-creator

In this personal-task project, read PROJECT-README.md, AGENTS.md and course-guide/TASK-CARD.md. Confirm the chosen task, audience, approved input path, reporting window, output and quality check. Flag missing fields or conflicting project guidance before building. Create an instruction-only skill for that task with a unique name and clear trigger. Handle missing or conflicting inputs. Show where it is saved and how to invoke it. Preserve existing skills and source files. Do not import the Northstar audience, dates or budget rules unless this task explicitly requires them.

Record the final skill name and invocation in course-guide/TASK-CARD.md.
~~~

## Demo — Schedule the Northstar brief

~~~text
Create a standalone recurring scheduled task for this project. Run $oreilly-monday-brief every Monday at 9:00 a.m. America/Toronto. Use sources/ for the previous Monday through Friday. Save a dated brief under output/. Report missing inputs, stale evidence and failed checks. Each run starts a fresh chat. Show the saved project, cadence, time zone and instructions.
~~~

## Schedule and verify

~~~text
Read course-guide/SCHEDULE-CARD.md in this personal-task project. Confirm its verified skill name, input path, reporting window, cadence, IANA time zone, output path and missing-input behavior. If a required field is missing, ask before creating anything. Create the specified standalone recurring task, with a fresh chat per run. Show the saved project, schedule and instructions for me to check.
~~~

## Optional demo — Improve a failed run

~~~text
Review the sanitized run logs in this course project. Identify one recurring failure in the skill. Propose one focused change and a case that would demonstrate improvement. Show the diff for review before applying it. After I accept the change, rerun that case and one previously passing case.
~~~

## Demo — Coordinate existing chats

~~~text
Coordinate these existing course chats: Extract project facts, Draft Monday Brief, and Review disputed claims. You may read their progress and results and send them follow-up instructions for this Monday Brief. Keep each chat responsible for its assigned output. Ask the drafting chat to wait for the facts it needs. Ask the review chat to check original evidence. Show what is complete, blocked or disputed. Once the needed results are available, reconcile them into output/final-brief.md with sources and unresolved decisions. Do not invent missing results.
~~~

## Demo specialist — Extract facts

~~~text
Read sources/ for the reporting period in PROJECT-README.md. Extract dates, owners, actions and budget items with source references into output/facts.md. Flag uncertainty. Own only output/facts.md.
~~~

## Demo specialist — Draft the brief

~~~text
Wait until output/facts.md is ready. Use it and the original sources to draft output/draft.md for the VP. Follow templates/weekly-brief.md. Own only output/draft.md.
~~~

## Demo specialist — Review claims

~~~text
Check the project's sources and, when available, output/draft.md. Investigate dates, ownership, arithmetic and unsupported claims. Write output/review.md. Own only that file.
~~~

## Lab 3 — Set up your task card

~~~text
Read PROJECT-README.md and AGENTS.md.

Show the three examples in course-guide/task-examples/ and ask which one I want to use or adapt. Wait for my choice.

Then copy that example into course-guide/TASK-CARD.md. Confirm the audience, approved input path, reporting window, output and quality check with me. Keep the practice inputs unchanged.
~~~

## Lab 3 — Run and verify

~~~text
Read the skill name and invocation in course-guide/TASK-CARD.md. Invoke that installed skill for the selected inputs and reporting window.

Open the saved result. Show one factual claim beside its original source passage, and report whether the quality check passed.

Then use a separate test copy with one required input missing. Run the skill there and show how it handles the gap. Preserve the original inputs. Record both results in course-guide/COMPLETION-CARD.md.
~~~
