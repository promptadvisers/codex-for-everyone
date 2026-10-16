# Scheduler execution and verification

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
