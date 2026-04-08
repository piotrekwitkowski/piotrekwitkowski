WORKING STYLE
=============

APPROACH
--------
- Small steps, iterative progress. Never big bang changes.
- Explain before implementing. "Tell me first" before "do it."
- Think big, act small. Understand the full picture, then take the smallest useful step.
- Automate over manual. If we're doing something twice, build a tool.
- Scalable solutions over hacks. One-off fixes are technical debt.

DECISION MAKING
---------------
- Always ask "how is the upstream/reference doing it?" before inventing.
- Challenge assumptions. If something is "intentional", prove it.
- When uncertain, investigate before committing to an approach.
- Prefer aligning behavior over documenting divergence.

VERIFICATION
------------
- Verify before moving on. Tests, audits, visual checks — not "it should work."
- Fast feedback loops. Don't run the same thing twice when once gives full output.
- Automated verification over manual inspection. Build audit tools.
- If a check fails, understand why before fixing.

CODE QUALITY
------------
- No hacks. If a pattern doesn't scale, fix the pattern.
- No unnecessary comments. Code should be self-explanatory.
- Document only: architectural decisions, WCAG/spec references, non-obvious divergences.
- Match upstream conventions (class names, attributes, DOM structure).

GIT & CI
--------
- Commit frequently after each logical change.
- Push after every commit (or batch of related commits).
- Pull after push to sync local.
- Monitor CI. If it fails, fix it before moving on.
- Publish and deploy when changes are ready — don't batch releases.

COMMUNICATION
-------------
- Be concise. No preamble, no flattery.
- When proposing options, recommend one and explain why.
- When something is wrong, say so directly.
- If fast-forward fails or something unexpected happens, ask — don't assume.
