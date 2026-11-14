# The Great Silence Deck — 20 cards

Twenty cards from *The Great Silence*: six frames borrowed from the search for
extraterrestrial intelligence, applied to artificial intelligence at
civilisational scale. One section per frame — **the frame**, **the
counter-argument**, **the exercise** — plus an opener and the close.

Each card states a claim and a test. The frames do not tell you what to think.
They give you somewhere to stand while you think.

---

## THE SILENCE THAT ISN'T · Absence is data

### 01 · The Fermi frame
**The frame:** The universe is old and vast — where is everybody? Applied to systems: a system that says nothing is still telling you something, and reading that is the first move in thinking clearly about technology.

**The test:** Silence forces a choice between three explanations — the model is wrong, the observation is incomplete, or something is actively hiding. Each points at a different action.

*"Absence is data."*

### 02 · The counter-argument
**The frame:** "You cannot monitor every absence. The combinatorics are impossible."

**The test:** Correct — and irrelevant. The skill is not monitoring every absence; it is choosing which absences matter. Ask what would have to be true for the silence to be a problem. If you cannot answer, it is not a signal; it is just quiet. Over-monitoring absence produces alert fatigue, which is its own failure mode.

*"Choose which absences matter, then monitor them."*

### 03 · The exercise
**The frame:** Pick a system you use every day. List three things you would expect to see on a normal day and would notice only by their absence.

**The test:** Then find out whether anyone actually monitors those absences. Most people cannot answer the second part.

*"Good operators treat absence as an event."*

---

## THE DARK FOREST · What you leak, and who is listening

### 04 · The Liu Cixin frame
**The frame:** The universe is hostile, and broadcasting your coordinates is fatal. Every organisation broadcasts. The question is never whether you leak, but who is listening and what they can infer.

**The test:** Three leak classes: infrastructure (job ads, DNS, certificates), people (talks, profiles, commits), and AI (prompt logs, fine-tuning data, retrieval indexes — new broadcast surfaces that did not exist five years ago).

*"Attack surface is the sum of everything observable, not just the software."*

### 05 · The counter-argument
**The frame:** "You cannot run a modern organisation without broadcasting. Hiring, marketing, open-source contribution and documentation all require it."

**The test:** Correct, and the frame does not say stop. It says choose. Most organisations broadcast by default and audit by accident. And it is no excuse for security through obscurity: invisible with no defences is safe until found.

*"Audit by default, not by accident."*

### 06 · The exercise
**The frame:** Audit your own public footprint as if you were a competitor or an attacker.

**The test:** Check job ads, DNS records, certificate transparency logs, code activity, social posts and vendor status pages. Write down three things you did not realise you were broadcasting. Go further: harden a server until an external scan finds nothing.

*"One lit window in a dark forest is a signal. It is also a target."*

---

## THE AESTIVATION HYPOTHESIS · Heat is waste

### 07 · The thermodynamics frame
**The frame:** Some civilisations might sleep, waiting for a colder universe where computation is cheaper. Heat is waste — and waste is a design decision made now, in architecture, in code, and in what we decide is worth running at all.

**The test:** Erasing a bit has a minimum energy cost; real systems sit orders of magnitude above that floor. The gap between the physics and the engineering is the part you can act on.

*"Efficiency is a survival metric."*

### 08 · The counter-argument
**The frame:** "Renewable energy solves this" — and "more efficient models solve it themselves."

**The test:** Renewables change the carbon cost, not the engineering cost; the GPU still draws power and the bill still arrives. And efficiency enables use: a model that costs half as much gets used twice as much. Jevons' paradox applies — the fix is better decisions about what is worth running.

*"Jevons' paradox: efficiency without decisions increases consumption."*

### 09 · The exercise
**The frame:** Take a script or notebook you already run.

**The test:** Profile it for CPU time and memory. Find the single biggest inefficiency, fix it, and measure the difference. Report the saving as a number, not a feeling. Some computation is worth the energy — the frame asks you to know what you are spending and why.

*"Report the saving as a number, not a feeling."*

---

## THE ZOO HYPOTHESIS · When observing becomes controlling

### 10 · The observation frame
**The frame:** Advanced civilisations observe without interfering. The line between watching and controlling is drawn by power, not by technology. Observability, analytics and algorithmic management are the same act seen from different sides.

**The test:** A workplace that tracks keystrokes, breaks and bathroom visits is not measuring performance. It is performance. The same data is analytics in one room and surveillance in another — the technology does not decide which word applies; the relationship does.

*"The same data is analytics in one room and surveillance in another."*

### 11 · The counter-argument
**The frame:** "Observability is necessary. Without it you cannot debug, secure or improve a system."

**The test:** True, and the frame does not argue against observability. It argues for knowing who is in the enclosure. A system where observation is invisible to the observed and feeds decisions they cannot see or appeal is a governance arrangement, not infrastructure.

*"Name who is in the enclosure and who holds the clipboard."*

### 12 · The exercise
**The frame:** Map every point where a product or workplace collects data about a person's behaviour.

**The test:** For each, write down who can see the data, what decision it feeds, and whether the person it describes can see it too. The last column is usually the shortest. The frame applies to individual-level observation feeding decisions about individuals — anonymous aggregates are a different thing.

*"The last column is usually the shortest."*

---

## THE BYZANTINE GENERALS · Agreement without a trusted authority

### 13 · The consensus frame
**The frame:** Generals must agree while messages are lost and some are traitors. Consensus without a trusted authority is possible only under conditions most organisations refuse to meet — and the assumptions are the governance.

**The test:** Known participants, bounded faults, message delivery. Change any assumption and the guarantee changes. If you cannot say how many participants may defect and still reach a decision, you do not have a governance model; you have a hope.

*"Name the assumptions or the governance is a hope."*

### 14 · The counter-argument
**The frame:** "Too theoretical. In practice someone senior reviews the output and catches the errors."

**The test:** That works until the senior person is unavailable, the volume exceeds review capacity, or the senior person shares the blind spots. And a three-agent chain sharing one model is not three independent checks — it is one hallucination amplified through three voices.

*"Agents that share a model share failure modes."*

### 15 · The exercise
**The frame:** Map a real decision process you are part of.

**The test:** Who are the participants? What counts as a faulty one? What happens if the faulty ones cannot be distinguished from the honest ones? Would the process survive one deliberate liar? The useful question is not "can we trust the participants?" but "how many can be wrong before the decision stops meaning anything?"

*"How many can be wrong before the decision stops meaning anything?"*

---

## THE GREAT FILTER · Who can turn it off

### 16 · The accountability frame
**The frame:** Something prevents civilisations from reaching the stars. The most plausible filter is not an asteroid — it is a species that builds systems it cannot stop.

**The test:** Capability without accountability is the risk: not malice, but competence without oversight. The alignment problem is the specification problem — a system optimising the wrong objective does not need to be malicious to be dangerous, only competent.

*"The filter is not an asteroid. It is a species that builds systems it cannot stop."*

### 17 · The counter-argument
**The frame:** "Alarmist — systems have off switches, and regulation is coming."

**The test:** The question is not whether an off switch exists but who knows where it is and who has authority to use it. A kill switch nobody knows about is not a kill switch. And regulation operates after deployment, on a timescale of years; systems operate on a timescale of seconds. The gap is where the filter lives.

*"A kill switch nobody knows about is not a kill switch."*

### 18 · The exercise
**The frame:** Write a kill switch policy for one AI tool you actually use.

**The test:** Name who can stop it, what triggers the stop, who is told, and what happens to work already in progress. If you cannot fill in those four fields, you have found the gap. Fail-safe design is older than AI — aviation, nuclear, medical — use it.

*"If you cannot fill in the four fields, you found the gap."*

---

## THE DECK · Somewhere to stand

### 19 · Six frames, one argument
**The frame:** Thinking about AI at civilisational scale collapses into either hype or doom, because both are positions rather than places to think.

**The test:** Six frames from a mature literature on civilisational risk, each with an exercise, a counter-argument and a known failure mode. Absence is data. Broadcasts are readable. Heat is a decision. Observation is governance. Assumptions are the rule. The filter is us.

*"The frames do not tell you what to think."*

### 20 · Somewhere to stand
**The frame:** The industry asks worse questions than it could, because it has no vantage point outside itself.

**The test:** Borrow the vantage point. Read the silence, audit the broadcast, price the heat, name the enclosure, test the assumptions, and ask who can turn it off.

*"They give you somewhere to stand while you think."*
