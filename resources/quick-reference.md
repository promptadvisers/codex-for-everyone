# Quick reference

## Give Codex a task
Say what you need, who it is for, which sources to use and what a finished result should include. If you dictate the request, check the transcription before sending it.

Use Plan mode when the workflow still needs discussion. Codex can inspect available context while planning. Agree on the decisions, then leave Plan mode before asking it to save or implement the plan.

## Keep the useful instructions
Put conventions that apply across tasks in AGENTS.md. Start a fresh chat to check that Codex can find them. Keep dates and other details specific to one request in that request.

Open the saved output beside its source. Check the passage behind a citation. For budget rows, count identical duplicates once and flag conflicting amounts. Suggested owners stay unconfirmed until the evidence shows acceptance. The /review command is for Git/code review; ask directly for a document audit.

## Reuse the method
Use $skill-creator to package a workflow you have tested. Inspect the saved skill, verify its name and run it in a fresh chat. Check its output and try a missing-input case before scheduling it.

## Check a scheduled run
Read back the saved project, timing, time zone, reporting period and output path. Run a scheduler test, open the resulting file and check it against the input. Restore the intended weekly settings afterwards. A saved schedule or successful manual run does not prove that the scheduler ran.

## Carry context into a new chat
On builds that support it, drag an earlier chat into a new chat's composer. Otherwise use the available chat-reference control. Ask Codex to restate the decisions it should reuse, then check them. The exact gesture can vary by app build.

## Split work across chats
Give each chat a distinct job and output file. You can choose a different available model family, such as Luna, Sol or Astra, for each chat. Start with the available default; judge the results against the sources rather than a fixed model ranking.

Ask a coordinating chat to follow the named chats, send follow-up instructions for that work and combine the completed results. A shared folder does not isolate edits, so keep file ownership explicit. Pin the coordinator and check remaining usage before starting several runs.

## Next week
Run the same task with new inputs. Fix instructions when you find a repeatable problem. Share the workflow or add another task once it is reliable. If your classroom run is unfinished, resolve that step first.
