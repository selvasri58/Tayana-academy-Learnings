Exercises 9–12: Markdown Files, Prompt Library, Versioning \&

Documentation

Based on: How to Build Your Own Project GPT — A Generic Framework



Exercise 9 Steps 3-8 — Markdown File

Build a Complete Markdown Instruction File

Steps 3-8 — Markdown File

REAL-WORLD SCENARIO

You manage customer success at a SaaS company. You want a GPT that handles Tier 1

support tickets by drafting responses, tagging ticket types, and escalating when needed.

INSTRUCTIONS

1\. Create a full Markdown file with all 9 sections: Role, Purpose, Scope, Input Rules, Output

Rules, Decision Logic, Do/Don't, Examples, Error Handling.

2\. Include at least 3 'If... then...' rules in the Decision Logic section.

3\. Write 2 complete input to output examples in the Examples section.

4\. Add a Mode section with 'Mode: Quick reply' vs 'Mode: Detailed response' that the user can

activate in chat.

EXPECTED OUTCOME

A .md file that could be handed to any team member and allow them to operate the GPT

identically. The Mode section should clearly change the output: Quick reply = 2-3 sentences,

Detailed response = full structured reply with root cause, steps, and follow-up.



Exercise 10 Step 11 — Reusable Prompts



Build a Reusable Prompt Library

Step 11 — Reusable Prompts

REAL-WORLD SCENARIO

You are a content strategist with a GPT that helps with content creation. Now create a library

of task-specific prompts that activate different modes of your GPT.

INSTRUCTIONS

1\. Create at least 5 reusable prompts: Analyze, Generate, Improve, Summarize, and one custom

prompt.

2\. For each prompt, write: the trigger command, what the GPT will do, and the expected output

format.

3\. Test each prompt against the same piece of content and compare outputs.

4\. Document which prompt pairs work well together (e.g., Analyze then Improve).

EXPECTED OUTCOME

Example library: 'Analyze this:' returns structured breakdown with gaps and strengths.

'Improve this:' returns revised version with change log. 'Summarize this:' returns 3-bullet

executive summary. Pairing Analyze then Improve creates a powerful two-step quality

workflow.



Exercise 11 Step 10 — Versioning

Iterate and Version Your GPT

Step 10 — Versioning

REAL-WORLD SCENARIO

After 2 weeks of using your Project GPT for client proposal writing, you have collected 10

examples of outputs that missed the mark. Now use those failures to improve.

INSTRUCTIONS

1\. Review your 10 bad outputs and group them into failure categories.

2\. Write a v1 to v2 change log listing exactly what changed and why.

3\. Save both versions with clear names (project-gpt-v1.md and v2.md).

4\. Run the same 3 test inputs through both versions side by side — document the improvement.

EXPECTED OUTCOME



A clear change log: v1 to v2 changes: (1) Added rule: never suggest pricing without client

budget confirmation. (2) Strengthened output format: added Executive Summary section. (3)

Replaced generic role statement with industry-specific identity. Side-by-side tests should show

measurable improvement.



Exercise 12 Step 12 — Documentation

Document Your GPT for Team Handoff

Step 12 — Documentation

REAL-WORLD SCENARIO

You have built a Project GPT that your entire sales team will use for lead qualification. You

need to write documentation so anyone on the team can use it without your help.

INSTRUCTIONS

1\. Write a one-page GPT documentation with: what it does, how to use it, input examples, output

examples, known limitations, and version history.

2\. Include a 'quick start' section — 3 steps a new user takes to get their first output.

3\. List at least 3 known limitations honestly.

4\. Write an FAQ with 5 questions a new user might ask.

EXPECTED OUTCOME

Documentation usable by someone who has never heard of Project GPTs. Known limitations

example: 'This GPT cannot verify live data — do not use for real-time pricing.' FAQ example:

'What if the output looks wrong? Add more detail to your input and retry. If it fails twice, tag the

team lead.'

