# Install the supplied Northstar fallback skill

Use this only in 00-start or a Northstar checkpoint. In 01-my-recurring-task, create/adapt the neutral method for your selected task; do not install the Northstar workflow unchanged as your personal solution.

1. Confirm this project contains course-guide/skill-packages/oreilly-monday-brief/SKILL.md.
2. Copy the full prompt below into the project chat. Let Codex locate the supported personal skill directory; no terminal is required.
3. Inspect the proposed location/name. If the name already exists, choose a unique course name and update both folder and skill metadata. Preserve the existing skill.
4. Confirm the skill is listed/selectable or that Codex can identify the exact installed skill in a fresh chat in this project. If it is not discovered, check the returned path/name first, then restart the app once and retry. Record a skill-discovery blocker if still absent.
5. Invoke the verified name explicitly and inspect its saved output against the source. Installation alone is not a pass.

~~~text
Inspect course-guide/skill-packages/oreilly-monday-brief. Install this complete portable folder as a personal skill in the location supported by this app. First check for an existing skill with the same name and preserve it. If necessary, use a unique course name and update folder and metadata consistently. Include the template, examples and checks. Show the installed path, exact invocation and how to verify discovery in a fresh chat. Do not create a schedule or send any message.
~~~

The documented personal path is ~/.agents/skills/<verified-name>/. It is a location Codex can manage for you, not a command you must type. Supported locations can depend on setup. Package presence is not installation evidence.

https://learn.chatgpt.com/docs/build-skills
