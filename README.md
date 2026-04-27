# Ontology POC — EM Planning Layer

This is **my** planning and tracking layer for the Ontology Platform POC.
It is not the team's working repo. The team uses Jira for tracking and Boeing GitLab for code artifacts.

## The political shape (read this first, every time)

**Primary stakeholder:** VP of Enterprise Data and AI, Boeing IT.
**Strategic bet:** Build internal ontology capability alongside Palantir for use cases where internal fits. The POC is evidence for or against this bet.

**Two reporting/sponsorship chains:**
1. **Boeing IT chain** — sponsoring. The VP sits above the named SLT executive sponsor.
2. **SWE chain** — Sachin → Krishna. Executing.

## The asymmetry I will not forget

The VP is *my* stakeholder. I am not theirs.

- They will likely never meet me. They form their judgment from artifacts and from what my sponsor tells them.
- They skim. Anything that reaches them must land in 30 seconds.
- They evaluate strategic narrative, not technical merit. The schema is invisible at their altitude.
- I do not email them. My sponsor does. My job is to make sure my sponsor has what they need.

## What I'm actually trying to control

Three things, in order of importance:

1. **The VP is never surprised.** Not by scope, slip, demo content, or what the demo doesn't show. Surprises at this level damage my sponsor.
2. **Continuous accurate signal up the chain.** What the VP hears between now and demo day matters more than demo day itself. Distorted third-hand signal = lost narrative.
3. **The artifact at the end is shaped for VP-level consumption.** A working demo is necessary but not sufficient. The 1-pager and 3-slide deck are the deliverables that reach altitude.

## The POC fails if
- The VP is surprised by anything material at the demo.
- The framing drifts to "replacing Palantir" — that's not the bet they made.
- The use case overlaps with Palantir's existing Boeing scope (creates needless conflict).
- Joint sponsorship erodes — Boeing IT claims the win, SWE chain becomes invisible (or vice versa).

## What lives here
- `roadmap/` — the 7-week plan
- `meetings/` — meeting notes
- `decisions/` — decision log
- `risks/` — risk register
- `stakeholders/` — stakeholder map, with VP at top
- `weekly/` — Monday review

## What does NOT live here
- Team task tracking → Jira
- Code/schemas → Boeing GitLab
- Anything sensitive that shouldn't be on personal infra

## The framing rules I will not break
- Never say "replace Palantir" in writing or meetings. The frame is "internal capability for use cases where internal fits."
- Never communicate directly to the VP unless explicitly invited by my sponsor.
- Every visibility moment in the roadmap is "what my sponsor can credibly tell the VP at this point" — not "what I want to say."
- If I'm asked comparative questions ("better than Palantir?"), I answer with scope and fit, never with a verdict.

## Discipline note
This repo works only if it's where I think out loud. The moment it becomes a chore, archive it. The Monday review is the load-bearing ritual. If that dies, the repo dies.
