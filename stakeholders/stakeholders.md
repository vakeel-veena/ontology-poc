# Stakeholders

The stakeholder map for this POC has a sharp asymmetry. The VP is the most important stakeholder I have, and the one I have the least direct contact with. Plan accordingly.

## Tier 1: Primary stakeholder (indirect)

| Stakeholder | Role | What they care about | What I track |
|------------|------|---------------------|--------------|
| **VP of Enterprise Data & AI, Boeing IT** | Strategic sponsor of the internal-capability bet | Was the bet vindicated? Is internal capability defensible for next budget cycle? Did this avoid Palantir conflict? | What the VP last *heard* (not what I last said). Update via sponsor. |

**Rules for this tier:**
- I do not contact them directly unless explicitly invited.
- Every artifact that reaches them goes through my sponsor.
- Format that lands at this altitude: 1 line of context, 1 line of result, 1 line of next step. Anything longer is for someone else.

## Tier 2: Direct sponsors (engaged regularly)

| Stakeholder | Role | What they care about | What they fear | Cadence | Last touched |
|------------|------|---------------------|----------------|---------|--------------|
| [Boeing IT SLT sponsor — name] | Operational sponsor; reports to VP | POC delivers; their bet with VP holds | Surprises that embarrass them upward | Weekly written, bi-weekly sync | YYYY-MM-DD |
| Sachin | SWE skip-level | SWE delivery credibility, productivity narrative | Headcount cuts without a defense; team being invisible in Boeing IT win | Bi-weekly written | YYYY-MM-DD |
| Krishna | SWE director | Strategic positioning, India execution credibility | Optics with US peers; SWE chain not getting credit | Monthly skip-level | YYYY-MM-DD |

**Rules for this tier:**
- Sponsor (Boeing IT) and Sachin (SWE) are the two channels through which signal reaches altitude. Both must be fed equally.
- Never let one have a more recent or more accurate picture than the other. That asymmetry creates political friction I don't need.
- The question to ask before every update: *can this person brief their boss with what I just gave them?* If no, the update is wrong.

## Tier 3: Working-level / influence

| Stakeholder | Role | What they care about | Cadence | Last touched |
|------------|------|---------------------|---------|--------------|
| Tech lead (TBD, Week 1) | Internal team lead | Clarity of scope, room to deliver, not being micromanaged | Daily | — |
| [Domain stakeholder for chosen use case] | Owns the data/problem the POC addresses | Their use case getting a credible result | Weekly during POC | — |
| [Architecture/governance review, if required] | Process gatekeeping | Compliance with internal standards | As required | — |

## Tier 4: Watch-only (do not engage, do track)

| Stakeholder | Why on the list | What I watch for |
|------------|----------------|------------------|
| Palantir-side actors at Boeing | Their existing scope must not be encroached. Their reaction to internal capability is unknown. | Any signal that the POC use case overlaps theirs. Any "offer to help" — that's a takeover, not help. Any expansion of their scope that would make the POC redundant. |
| Anyone above Sachin on the SWE side I haven't named | They influence my chain's narrative even if I don't see them | What signal reaches them about this POC, and from whom |

**Rules for this tier:**
- I do not engage. I watch.
- If something concerning surfaces, escalate to Sachin or sponsor. Not my level to act on.

## Notes for me

- **The VP-surprise risk is the single biggest political risk in this POC.** Everything in the roadmap's "visibility moments" is in service of preventing it.
- **The credit-balancing problem is real but not mine to solve directly.** Sachin and the Boeing IT sponsor will work it out between themselves. My job is to give both chains something accurate to point at.
- **The "find the Palantir champion" thread is downgraded.** Not my level. If a landmine exists, it surfaces through my chain, not through my detective work.
- **First action:** find out who, on my sponsor's side, briefs the VP and how often. That cadence is what I plan around.