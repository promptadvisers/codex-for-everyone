# Course runbook — one action at a time

Keep course-guide/START-HERE.md or this file open beside the chat. Copy complete prompts from course-guide/PROMPTS.md. Slides show excerpts. App controls must match the teaching-build rehearsal; ask the producer for the supported control if yours differs.

## The practice situation

You help coordinate a project to improve employee onboarding. Every Monday, the VP of Operations wants a short update: what changed, what needs a decision, and what happens next.

**Northstar** is the fictional project we use together. Its meeting notes, team messages and budget export contain inconsistencies. Ask Codex to produce the update, then check its claims against those original files. We call the document the **Monday Brief**; that is the course’s name for a weekly project update, not a Codex feature.

- **Lab 1:** draft the update from the Northstar files and check a claim
- **Lab 2:** inspect a separate, deliberately flawed sample and verify the corrections
- **Lab 3:** switch to the personal project and create a reusable skill for a task from your work
- **Scheduling:** test that personal skill through a scheduled run after its manual check passes

The class uses fixed scenario dates so everyone can examine the same evidence. Your real recurring task needs its own reporting rule and refreshed inputs.

## Readiness gate — before Lab 1
1. Sign into the desktop app and confirm access, available usage and an available course model.
2. Extract the ZIP. Open the extracted 00-start folder as a local project, not the ZIP or its parent.
3. Open PROJECT-README.md and sources/project-status.md in the app. Confirm both are visible.
4. Open course-guide/PROMPTS.md. Locate “Lab 1 — Delegate.”
5. Send the producer READY if these work. Otherwise send SETUP plus the exact blocker. Use the labeled prepared checkpoint for observation while setup is resolved; do not mark it as your completed run.

## Lab 1 — Delegate (26–38 minutes)
1. DO: stay in 00-start. Start a chat for the brief.
2. DO: paste “Lab 1 — Delegate” from PROMPTS.md. Check its two output paths, then send.
3. CHECK: wait for completion and open output/folder-review.md and output/monday-brief.md.
4. CHECK: trace one factual claim to its source filename and date/row. Check unresolved owners rather than inventing them.
5. Record the source check in course-guide/COMPLETION-CARD.md. Tell the producer DONE, RUNNING or BLOCKED.
6. Recovery: preserve your project; open checkpoints/01-first-delegation as another project and start a fresh chat. Its outputs are prepared examples. Read evidence and rerun the prompt when access works.

## Between labs — watch unless invited to act
Watch the earlier-chat reference, model choice, coordinator, planning, guidance and connector demonstrations. You do not need to recreate every specialist chat or connect a work account. Use the demo prompts later. The instructor will clearly invite any guided practice.

## Lab 2 — Audit (66–78 minutes)
1. DO: in 00-start, open prepared-review/flawed-brief.md and choose one claim to investigate before the answer reveal.
2. DO: paste “Lab 2 — Audit.” Do not paste the targeted-correction answer before examining the evidence.
3. CHECK: open output/review-audit.md and output/corrected-brief.md. Locate the source behind your chosen correction.
4. Explain claim → evidence → correction in one sentence. If necessary, use “Lab 2 — Targeted correction after your evidence check.”
5. Compare with the instructor debrief after your attempt; matching wording is not the success criterion.
6. Recovery: open checkpoints/02-guidance-and-reviewed-brief as a separate project. Compare its prepared audit with the original sources, then rerun when able.

## Lab 3 — Create and test your skill (88–100 minutes)
1. DO: switch to the separate extracted 01-my-recurring-task folder as a new project. Keep the Northstar project intact. Start a fresh chat and read its neutral AGENTS.md and PROJECT-README.md.
2. DO: choose ONE: weekly-update, meeting-actions or document-check. Use its filled card in course-guide/task-examples/ and approved fictional inputs under practice-inputs/<choice>/. Or use approved/sanitized inputs from your own job. Do not use confidential data without authorization.
3. Ask Codex to copy your chosen filled card into course-guide/TASK-CARD.md, preserve the original example, and adapt it to your audience. Check all fields, especially input path and reporting rule.
4. Paste “Lab 3 — Create and test your skill.” Let Codex inspect guidance/README/card, create a uniquely named instruction-only skill and report its installed path and invocation. It must not import Northstar conventions.
5. CHECK: start a fresh chat in this same personal project, identify the applicable guidance and invoke the verified skill name. Ask it to use course-guide/TASK-CARD.md and the single selected input folder.
6. CHECK: open the new output, trace a claim to evidence, and ask for a missing-input test using a separate test copy or nonexistent test path. Preserve original inputs. The expected behavior is to report missing evidence, not invent facts.
7. Record evidence in COMPLETION-CARD.md and fill SCHEDULE-CARD.md. A saved SKILL.md without discovery and a checked run is not complete.
8. Recovery: use course-guide/neutral-skill-template/SKILL.md as a draft to adapt to the selected task. Ask Codex to replace all placeholders from your task card, install under a unique name and verify discovery. Never treat the Northstar fallback as an unchanged personal task.

## Schedule and verify (100–114 minutes)
1. At 100–102, CHECK: your skill passed manually; the computer stays on, app runs, chosen project and input files remain accessible, and required tools have access. Name who refreshes sources and who reviews failures.
2. At 102–105, DO: use “Schedule and verify,” replacing every field from SCHEDULE-CARD.md. Read the saved project, skill, cadence, time zone, reporting window and output path. Mark CONFIGURED.
3. Record the intended recurring settings before the test. For supplied fictional practice data, temporarily use reporting period 12–16 October 2026, as of 16 October. For your own data, specify a test period actually covered by those inputs. Use the copyable test prompt below.
4. At 105–111, DO: use the scheduler test control or short first occurrence that the instructor verified on the teaching build. An ordinary chat invocation is not a scheduler test. Mark RUNNING while queued/running. Inspect the actual run status and timestamp.
5. CHECK: open the scheduled output and compare at least one claim with its source, plus missing/stale input handling. Inspect the run error if it fails. Do not declare VERIFIED just because a file exists from an earlier manual run.
6. Restore the original weekly cadence, time zone and rolling reporting window; inspect the saved settings. Pause/remove any separate temporary test schedule and verify its status. Do not leave a frequent classroom test running.
7. Mark VERIFIED only with the completed scheduler result, checked output and restored settings. Otherwise mark BLOCKED or RUNNING, record the exact issue and next action.
8. At 111–113, send one short state to the producer: CONFIGURED / RUNNING / VERIFIED / BLOCKED. Core completion takes priority over the 113–114 optional improvement demo.

### Scheduler test prompt
~~~text
Inspect the saved schedule named [exact name] for this project and read back its current cadence, time zone, reporting rule, skill and output location. Help me test that schedule through the scheduler using the supported control or short test occurrence confirmed for this app. For this test only, use reporting period [start to end] and as-of [date], matching my actual practice inputs. Do not substitute a normal chat run for a scheduler execution. Show the actual execution status and output path. After the test, restore the original recurring settings and show them. If a separate temporary test schedule was created, pause/remove it and verify its status. If any step is unavailable, identify the blocker rather than claiming completion.
~~~

## Do not lose your work
Checkpoint outputs are prepared references. Keep them labeled. Use a new project/chat for recovery and preserve your earlier work. Checkpoints 01–03 are working Northstar projects. Checkpoint 04 is a schedule recipe only, not a runnable project or execution receipt.
