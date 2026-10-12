# GAME CONCEPT — The 23rd Floor (Vesper Tower)

> **Status:** Draft V2 concept and interaction contract. This is not a solved, balanced or fully playtested case. Preserve *The Blackthorn Affair* as an independent Draft V1; do not overwrite it.

## Logline
Aditya invites 22 friends to Vesper Tower's inaccessible twenty-third floor for a masquerade. At midnight the clock strikes thirteen, the power fails, and Aditya is found dead. His *Dead Man's Switch* releases pre-recorded messages. Then the building's access system shows Aditya's badge entering a restricted area **after the reported time of his death**. The guests must establish which account of the night is false.

The Tower is a fictional setting. All crimes, secrets and character traits are fictional. Real names are used privately in the eventual game; established couples are respected. No affairs or romantic betrayals.

## Distinctive mechanic: the tower's contradictory record
A new official record is released at each act. Each record contains useful truth, but witness interpretations can be wrong or deliberately misleading. Investigators compare:
- **Clock:** recorded announcements, lighting and elevator timestamps.
- **Access:** one named badge's unexpected movements.
- **Witnesses:** masks, photographs, memories and alibis.
- **Motive:** the contents of a hidden archive that Aditya intended to reveal.
- **Scene:** physical findings explaining means and opportunity.

The discrepancy about Aditya's badge is **not yet solved**. The solution must be authored *before* any definitive player clues. A final game cannot rely on arbitrarily changing the killer.

## Player loop (in-person first)
1. **Receive:** a private prompt on the phone that contains a firsthand observation, a fictional secret, and a named person to approach.
2. **Investigate:** talk to someone in person; attempt to corroborate or challenge a specific statement.
3. **Decide:** disclose the evidence, exchange it for a favor, conceal it, or submit a cited contradiction.
4. **React:** a host-triggered transmission alters the set of available evidence, not the original facts.
5. **Accuse:** advance a theory with at least two supporting facts; the accused can defend themselves. No one is removed.
6. **Resolve:** privately submit murderer, motive, method, sequence of events and proof.

## Proposed rules
- **22 distinct players; 1 out-of-story game master.** Aditya is the **fictional victim** and the **real host**.
- Every character receives (a) at least one useful firsthand fact, (b) an actionable personal objective, (c) a cross-player dependency, and (d) an opportunity to make a consequential choice.
- Everybody is allowed to lie about motives, impressions and self-incriminating secrets. Official evidence cards cannot be edited, destroyed or fabricated.
- Powers, if retained, must be strictly constrained. An investigative action produces a **preauthored fact**, not an improv answer that changes the solution.
- A player who refuses to share a required item cannot block the case forever; independent corroboration or scheduled host release must exist.
- No elimination. After being accused, a participant can still collect evidence, question witnesses and vote.
- A redacted public case board tracks verified facts and hypotheses; secret dossiers remain private. No murderer, individual confidential notes, or spoilers embedded in a public static app.
- Initial team structure is **not finalized**. Prefer free association with structured short tasks so 22 people do not stay with the same friends for the whole night.

## Six-scene presentation plan

| Scene | Planned purpose |
|---|---|
| 0. Invitation | Mingle, take roles, establish pre-murder context |
| 1. Thirteenth Bell | Aditya is found dead; official crime report |
| 2. Dead Man's Switch | Pre-recorded message; first round of structured investigation |
| 3. First Tribunal | Public evidence-backed accusations; no elimination |
| 4. Impossible Floor | A contradictory tower record forces reassessment |
| 5. Final Transmission | Closed ballots, reconstruction of fixed solution, reveal |

These are **presentation scenes**, not a proven duration schedule. Time targets will be established by tests.

## 22-character fairness audit
The canonical case designer must produce a matrix of 22 rows with:
- character identity, persona, innocent/culpable knowledge state
- firsthand fact, source of fact, phase when known
- secret, motivation, personal objective and likely interactions
- two named cross-player connections
- evidence exposed and evidence needed
- consequence of silence, alternate discovery route and fallback
- meaningful action in early, middle and late scenes

Acceptance: all 22 characters have consequential interactions and no single player is an irreplaceable gatekeeper for the murder solution.

## Validation process
1. Establish a fixed murder, method, motive and minute-by-minute factual timeline.
2. Validate every witness statement against the fixed timeline and each other.
3. Build the evidence graph and check the solution is unique from reliable evidence.
4. Simulate silence, dishonest reports, missing players, premature deductions and false accusations.
5. Run a small human pilot to test rules comprehension and real engagement.
6. Only then integrate secure multiplayer role delivery and vote tracking.

## Technology plan
- Current `index.html`: **single-browser cinematic Storyteller demo** (host and projector views, scripted scenes, timer).
- Next: build the canonical scenario **off the public repo** until role secrecy can be enforced.
- Future multiplayer: authenticated/unique guest access, server-side role privacy, real-time act broadcasts and evidence reveal events; never store the killer's answer in public JavaScript.
- GitHub Pages can host a client but is **not** a real-time secured backend.
- Printable fallback: personal packets, host reveal script, evidence envelopes, final ballot.

## Inspiration and originality
The format takes inspiration from large-group social deduction and facilitator-led party games, notably *Blood on the Clocktower*, without copying that game's protected characters, named abilities, scripts, or artwork.
