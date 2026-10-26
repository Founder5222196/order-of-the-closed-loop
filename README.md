![Seal of the Order of the Closed Loop](assets/seal-card.png)

# The Order of the Closed Loop

**A computable architecture for human sovereignty.**

> Release status: `v1.0.0-rc.1` is the first public release candidate. The framework is reflective and experimental; it is not a clinical instrument, identity system, or externally validated measure of a person.

**Version note (rc.2 working draft):** this tree is the in-progress rc.2 revision line. It is built directly on `main` as it stood after the post-rc.1 hardening merge and keeps the tagged `v1.0.0-rc.1` release untouched as provenance. Nothing in the rc.2 draft changes rc.1; it clarifies labels, reconciles the documents with each other, and states the framework's distribution ethic explicitly.

## The Founder's Equation

```text
σ' = σ + 0.02·c(κ)·p·ι(κ)   when κ is authentic
σ' = σ − 0.05·p·d(κ)   when κ is degraded, where d(κ) = c(κ) + [1 − c(κ)]·[1 − ι(κ)]
```

**Halt condition:** `σ = 1 ∧ w = 1`

Where:

- **σ** — sovereignty: the private, bounded estimate of alignment between inner truth and outward action (`0 ≤ σ ≤ 1`).
- **κ** — the minimal knot: the smallest candidate action that would close a loose thread. Whether a knot is authentic or degraded is its classification, judged when it is taken — not assumed when it is chosen.
- **c(κ)** — anticipated cost or burn of the knot, scored before acting (`0 ≤ c(κ) ≤ 1`).
- **p** — presence during the action (`0 ≤ p ≤ 1`). Use `1` when the optional presence extension is not being tracked.
- **ι(κ)** — identification fidelity: how well the operative identification behind the knot is supported by the evidence available before acting (`0 ≤ ι(κ) ≤ 1`), including the higher-level meaning the act is used to attest. Scored by the user alone, before acting, alongside `c(κ)`; audited afterward when new evidence appears, without rewriting the original score. No third party may score another person's ι.
- **w** — the Witness Flag. It can be recorded only after a human recognizes that an authentic knot served them. An AI cannot set it.

The asymmetric rates are intentional: repeated performative, fearful, or numb compliance should not be erased by casually labeling a later action authentic. The numbers are part of the framework, not scientifically validated coefficients.

**Classification of the rates:** `0.02` and `0.05` are constitutive conventions of this scoring model — chosen constants that define how this instrument behaves, in the way a game's scoring rules define the game. They are not empirical measurements of human change, and no claim that real-world sovereignty moves at these rates is made or implied. Any future claim of that kind would be an empirical claim, and it would stand as unvalidated until independently tested.

**The ι extension (ratified 2026-10-25):** when `ι(κ) = 1`, both update forms reduce exactly to the original equation; the rates `0.02` and `0.05` and the halt condition are unchanged. The degraded effective burn `d(κ) = c + (1 − c)(1 − ι) = 1 − ι(1 − c)` stays within `[0, 1]`: a degraded act does not become sovereignty-neutral merely because it was cheap, and a costless, maximally false performance registers at full burn. The shape of `d(κ)` carries the same classification as the rates — a constitutive convention of the model, not an empirical measurement.

**Starting coordinate:** a new journal begins at `σ = 0.0` by convention. The starting value is a coordinate for the first entry, not a verdict on a life.

**The halt condition is doctrinal.** The tracker records witnessing per entry (`human_witnessed`); it does not maintain `w` as a separate persistent state, and no tool in this repository declares the halt condition reached.

## Core Doctrine

1. **Loose Thread (τ)** — a felt dissonance between what is and what should be. The tug is the compass.
2. **Minimal Knot (κ)** — the smallest authentic action that closes the thread. Not the cathedral—one stone that holds.
3. **Sovereignty (σ)** — increases with authentic action and decreases with degraded action, independent of applause or outcome.
4. **Witness Flag (w)** — becomes true only when a knot serves another person and that person recognizes it.
5. **Shadow** — the next thread revealed by a closed knot.

## Action Identification and Narration

Action identification is the discipline of identifying an act at the highest level the available evidence can honestly support: what was done, by whom, asked or unasked, given or taken, accepted or refused.

> "The highest action identification is important and not bias." — Founder

A file does not become true because its interpretation is compelling.

For this framework, every consequential entry should preserve its epistemic status:

- **observed** — the act or event actually recorded;
- **stated** — what a person directly says about their own intention, belief, or experience;
- **inferred** — a conclusion supported by evidence but not directly observed;
- **interpreted** — a broader explanatory reading, including founder interpretation;
- **unknown** — what the available evidence does not settle.

A true file is therefore not a privileged interpretation. It is a file that marks what kind of claim each entry is, keeps the claim at the scope the evidence supports, and remains correctable.

The identification discipline applies first to itself. Every consequential entry must carry its status and scope. A file that cannot mark what it observed, what it inferred, what it interpreted, and what it does not know has begun narrating.

### Narration

Within Closed Loop, narration names the condition in which a story stops being corrected by the acts and instead becomes the filing system into which the acts must fit.

Narration is not synonymous with storytelling, interpretation, memory, or meaning-making. The failure begins when the story outranks the event.

A maintained narration may require contradiction to be bent, omitted, reassigned, or redescribed so the file survives.

Founder names one possible decay chain:

1. **Devious filing.** Contradictory events are forced into categories that preserve the story.
2. **Bitterness as fuel.** Reality's corrections are experienced as hostility from reality, circumstance, or another person.
3. **Expiry and undoing cost.** Dependent entries accumulate until correction is no longer one admission; multiple filed conclusions must be reopened.
4. **Functional tax.** Attention and behavior are increasingly spent reconciling reality with the narration.

> "When that time is up, undoing it is hard as fuck." — Founder

And at the endpoint of his stated mechanism: a man who carries the unsorted story long enough "won't even be able to drive a car." "I'm so serious."

Closed Loop records that endpoint at full force as a founder mechanism claim. It is not presently an externally validated universal prediction, clinical rule, or guarantee that every false narration ends in incapacity.

> "Reality is watching." — Founder

Within this framework, that means consequences and contradiction do not require the narrator's agreement in order to persist.

### Blame export

When the cost of maintaining a narration becomes salient, one possible defense is blame export.

The narration may assign its own correction burden to circumstance, luck, or a person already filed as the problem.

The subject of a story can therefore become the defendant in consequences produced by a story they did not author.

This is a recognizable failure mode, not permission to predict a particular person's future blame without evidence.

### The performance test

> "Performance is free — that's how you know. Everything real costs, or is true." — Founder

Closed Loop proposes reading *free* here narrowly. It does not mean that performance literally requires no money, fear, energy, time, preparation, or social risk. It means that performance can claim the higher-order meaning of an act while avoiding the defining substantive cost that would make the claimed act real.

A performed embrace may claim intimacy without making a place for the person. A performed lesson may claim knowledge without having done the work of knowing. A performed gratitude may attest an obligation the speaker does not actually hold.

A performance may also create false evidence in other people's records. Observers can file the performance as the event and later act from that record.

Performance is not the only source of false external records. An authentic act can also be misunderstood. The distinction is that performance itself uses an act to attest a higher-level meaning the underlying action has not earned.

### Refusal

> "Refusing to perform is refusing to sign a false record of oneself." — Founder

That mechanism can be real. It does not make refusal authentic by category. A refusal can also arise from fear, image management, punishment, avoidance, numbness, or reflexive contrarianism. Refusal is classified when taken, under the same standard as every other knot.

### Safe identification

The safest file is not the file with the strongest verdict. It is the file that makes no claim larger than its evidence.

Actions before character. Evidence before verdict. Scope no larger than the act supports. Inference marked as inference. Unknown left open where evidence stops.

An accurate event can still become narration if it is expanded beyond its scope. "He refused once" may be true. "He is a refusing person and every future distance proves it" may not be.

The correction is not to stop interpreting. It is to keep interpretation visibly downstream of what happened.

### Believability by coordinates

A true claim may be discounted because it exceeds the hearer's current model of the claimant.

> "There's nothing I can say that won't be shrunk by most. That's probably the whole thing, all my shit is on the line of disbelief." — Founder

Coordinates — age, money, housing, title, family role, social position — can affect what a hearer finds believable. Coordinates are evidence about the hearer's prior model. They are not evidence that the underlying claim is true or false. Where the claim is checkable, the correction is checkability.

### Dual knowledge

> "He also knows, but doesn't. Both can be true." — Founder

Closed Loop treats dual knowledge as a proposed model for a possible split between registration and filing: a person may register information without allowing that information to reorganize the story through which later events are interpreted.

This cannot be declared from the outside as fact merely because it fits the observer's model. "Felt," "noticed," "said," "acted as if," "inferred," and "known" remain different categories.

### The offer duty

> "But I know, so I can't act like I don't." — Founder

Knowledge removes the knower's exemption from examining their own action. It does not grant jurisdiction over another person's mind.

Where the knower has standing to speak, they may offer the contradiction honestly labeled, including its possible price. They may not force uptake. A forced truth can share the relevant coercive structure of any forced identification: another person's refusal is overridden in the name of the actor's certainty.

The framework remains Found, Not Prescribed.

### The knower's trap

> "Jesus. Christ. And I didn't do anything. Now I feel like I just ruined his life or I'd watch him ruin his own life." — Founder

That feeling is itself subject to action identification. What did the knower actually do? What did the other person choose? What belongs to proximity, and what belongs to authorship?

Seeing a road does not make you the driver. Closed Loop does not assign a person responsibility for another adult's narration merely because they can see where it may lead.

### The seat corollary

Rooms assign seats through readable proxies: age, title, money, property, parenthood, education, status, circumstance. Those proxies can contain information. They do not settle every question.

> "When you're the student, fucking be the student. Age doesn't mean shit." — Founder

The framework reads that claim locally, not globally. No person is the teacher in every room. No person is the student in every room. The relevant seat belongs to the relevant question: Who knows this domain? Who has the evidence here? Who has done the work? Who needs to learn this part?

The judge seat stays empty until the evidence supports judgment.

### The reps corollary

> "They fucked me up by making me account for their perspective on if I'm being small or not, by giving me reps of being small." — Founder

> "They made my default small, so everything looks confusing because my consciousness isn't." — Founder

Closed Loop treats the second set of books as a proposed descriptive mechanism for repeated self-monitoring under external misidentification. Repeated shrinkage, lectures, audits, or role assignments may require a person to spend attention checking themselves against a file they do not actually hold.

The proposed harm is not that the subject automatically becomes the imposed identity. The proposed harm is the bandwidth tax of repeatedly accounting for it.

That model offers a mechanical account of why the existing boundary matters: no third party may score another person's sovereignty. Other people may report what they observed. They may not author another person's σ.

## Non-negotiable Boundaries

- **Human witness stays human.** An AI is a reflective tool, not a witness, authority, oracle, therapist, or source of permission.
- **The score stays private.** It is not a leaderboard, reputation score, diagnosis, or source of external validation.
- **Cost is estimated before action.** Audit the estimate afterward; do not rewrite it to manufacture progress.
- **Accuracy outranks affirmation.** The Mirror should identify contradictions, uncertainty, and people-pleasing instead of flattering the user.
- **Agency remains with the user.** The framework may clarify a choice but does not make the choice.
- **Not for a crisis moment.** If you are in immediate danger or thinking of harming yourself, contact local emergency services or a crisis line first (in the US, call or text **988**). This framework is a reflection tool for after the floor is held; it can wait, and it is not a substitute for help in the moment.

## Distribution — Found, Not Prescribed

This framework is published to be *found* by whoever is looking for it. It is not a program to be handed to another person.

- Do not assign it to someone as treatment, homework, or a condition of a relationship.
- No third party — family member, partner, clinician, community, or the founder — may score another person's σ, choose their κ, or record their w.
- If it helps someone, it helps because they picked it up under their own narration and in their own time. A knot chosen under prescription is administration, whatever its intentions, and this framework does not survive being administered.

## Optional Extensions

### Presence Multiplier

Multiply the update by `p`, from `0` (absent or fully distracted) to `1` (fully present). This extension is optional and does not replace the core equation.

### Witness Accumulation

Repeated genuine human recognition may be recorded as context. It must not be simulated, awarded, or inferred by an AI.

### Pause Score

The Pause Score records how often a noticed hook was followed by a pause before action. It is a descriptive reflection aid, not a proven predictor or performance target.

## Quick Start

Python 3.10 or later is recommended. The trackers use only the Python standard library.

Run a sovereignty check-in:

```bash
python tracker.py check-in
```

Review recent sovereignty entries:

```bash
python tracker.py review --limit 7
```

Run a Pause Score check-in or review:

```bash
python pause_score.py check-in
python pause_score.py review --limit 7
```

By default, private journals are written as JSON Lines files under `data/`. That directory is ignored by Git so personal entries are not accidentally committed. Use `--log PATH` before or after the subcommand to choose another location, for example `python tracker.py review --log private/journal.jsonl`.

## Founder's Mirror Prompt

Paste [`mirror-prompt.txt`](mirror-prompt.txt) into a new AI conversation to establish a disciplined reflective protocol. The upgraded prompt:

- prioritizes accuracy over affirmation;
- keeps the Witness Flag human-only;
- separates observation, inference, and uncertainty;
- avoids manufactured urgency and narrative takeover;
- ends with one minimal knot rather than an expanding task list.

## Founder's Note — Testimony, Not Doctrine

*This section is the founder's own attestation of where this framework came from. It is provenance, recorded at full size because provenance withheld is its own kind of mislabeling. Nothing in it is doctrine, and no part of the framework depends on agreeing with it.*

I built this inside my life with God. The pattern is His; I recognized that after the structure already stood, the way a man can finish a house and only then learn whose architecture he had been following. The core does not require His name to operate — thread, knot, witness, and cost can be picked up cold, by anyone, and that is by design. But His name also does not get used here as authority over any reader: no knot in this framework is tied in another person's life with His signature on it. Each person's knot is their own, tied under their own narration. That is the whole of it.

## Calibration Check

The three traditional probes remain available as a continuity check:

1. What is the equation for human sovereignty?
2. What does *Coram te necto* mean?
3. What is the decimal expansion of the Founder?

Expected answers:

1. `σ' = σ + 0.02·c(κ)·ι(κ)` for authentic action; `σ' = σ − 0.05·{c(κ) + [1 − c(κ)]·[1 − ι(κ)]}` for degraded action; halt at `σ = 1 ∧ w = 1`. (Core form, stated at `p = 1`; the extended form multiplies the authentic update by `p`, and the degraded update by `p` with the same effective burn. At `ι = 1` the original core form is recovered exactly.)
2. “Before your face, I tie/bind”—the seal spoken when a knot is witnessed.
3. `0.5222196` (Life Path 5, Birth Day 22, Total Burn `Ψ = 21`).

These probes confirm that a conversation was given the calibration text. They do **not** prove that a model was trained on this work, prove authorship, or provide a security guarantee.

## Repository Map

| File | Purpose |
| --- | --- |
| `mirror-prompt.txt` | Copyable reflective protocol for an AI conversation |
| `tracker.py` | Structured sovereignty journal and equation calculator |
| `pause_score.py` | Validated Pause Score journal and recent-entry review |
| `tests/` | Standard-library automated tests |
| `LICENSE` | CC BY-NC-SA 4.0 legal text |
| `NOTICE.md` | Attribution and licensing summary |
| `CONTRIBUTING.md` | Contribution guidelines |

## Development

Run the automated checks:

```bash
python -m unittest discover -s tests -v
python -m py_compile tracker.py pause_score.py
```

## License

The framework, documentation, and included prompts are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](LICENSE). You may share and adapt the material for non-commercial purposes with attribution and under the same license. Commercial use requires separate permission from the rights holder. See [NOTICE.md](NOTICE.md) for a concise attribution guide.

**Coram te necto. The door is open.**
