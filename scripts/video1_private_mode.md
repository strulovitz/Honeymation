# Video 1: Private Mode — Script (Lego Animation)

## Overview
- **Duration:** ~2 minutes 10 seconds
- **Style:** Lego animation (3D rendered, everything is Lego)
- **Theme:** Why companies need BeehiveOfAI — anonymization is broken, existing local AI solutions are flawed, BeehiveOfAI is the real answer
- **Structure:** Hook, Problem, False Solution (anonymization), Bad Way 1 (CrewAI), Bad Way 2 (Petals/Exo), Good Way (BeehiveOfAI), Ending
- **Color system:** GREEN = good/safe, RED = bad/danger (established early, reused throughout)

---

## SCENE 1 — The Hook (5 seconds)

**Visual:** A Lego businessman in a suit walks from left to right across the screen. With every step he takes, a bundle of cash dollars falls on the floor behind him, piling up.

**Narrator:** "Right now, your company is losing money."

**Purpose:** Pattern-interrupt. Grabs attention in the first 2 seconds.

---

## SCENE 2 — The Project (5 seconds)

**Visual:** A Lego architect (yellow helmet, suit and tie, holding a rolled-up blueprint) stands watching as a Lego wooden cabin (representing "the project") is built in fast-forward from scratch — foundation, walls, roof — in just a few seconds.

**Narrator:** "Your company wants to make a project."

**Purpose:** Establish that the cabin = the viewer's project/work.

---

## SCENE 3 — The Big AI Problem (15 seconds)

**Visual:** The architect (normal-sized Lego minifigure) stands next to a GIANT Lego figure (the height of several minifigures stacked). The giant represents a frontier AI model like ChatGPT.

Three GREEN arrows go from the small person to the giant:
- Top arrow: small icon of paper documents
- Middle arrow: small icon of a database cylinder
- Bottom arrow: small icon of code brackets `</>`

Both figures are smiling (Lego smile — mouth curved up).

**Narrator:** "You want to use your information with big AI..."

**Transition:** Each arrow turns RED, one by one. The icons change to red X (forbidden) symbols. Labels appear:
- Arrow 1: "Privacy / Confidentiality"
- Arrow 2: "Trade Secrets"
- Arrow 3: "Security / Classified"

Both figures' smiles flip to frowns (mouth curved down).

**Narrator:** "...but you're not allowed to."

**Purpose:** Establish the core problem AND the green=good / red=bad color system used throughout the rest of the video.

---

## SCENE 4 — The Anonymization Illusion: "What Companies Do Today" (15 seconds)

**Visual:** A hospital desk. Five Lego patient figures, each unique and recognizable:
- One has red hair + glasses + name tag "SARAH"
- One has a beard + baseball cap + name tag "DAVID"
- One has blonde pigtails + name tag "EMMA"
- One has a top hat + mustache + name tag "JAMES"
- One has a ponytail + earrings + name tag "LISA"

A Lego hospital worker "anonymizes" them for sending to the Giant AI. One by one:
- **POP** — removes the hair piece (snap sound effect)
- **POP** — removes the glasses/hat/accessories
- **POP** — peels off the name tag
- The face on the head SPINS from a detailed face to a blank yellow surface

Now we see 5 identical blank yellow Lego figures. No hair, no accessories, no names, no faces. Just blank heads on generic bodies.

The hospital worker smiles proudly, gives a thumbs up. A GREEN checkmark appears on screen: "Anonymized! Safe to send!"

The 5 blank figures travel on a conveyor belt over a wall to the Giant AI Lego-man on the other side.

**Narrator:** "So companies strip the names off the data and send it anyway. They call it 'anonymization.' They think it's safe."

**Purpose:** Show what organizations actually do today — they don't avoid big AI, they anonymize and send. Set up the false sense of security.

---

## SCENE 5 — De-Anonymization: "But It Doesn't Work" (15 seconds)

**Visual:** A shadowy Lego figure appears (dark hood, magnifying glass). The attacker.

He pulls out a BIG BOOK labeled "PUBLIC RECORDS" (could also show a screen with social media logos / voter registry).

He looks at Blank Figure #1. Looks at the book. Then:
- **SNAP** — red hair snapped back on
- **SNAP** — glasses snapped back on
- **SLAP** — name tag "SARAH" pressed back on
- Face SPINS from blank back to Sarah's face

He does this rapidly for each figure. POP, POP, POP — one by one they all get their identities back. All five are fully recognizable again.

The hospital worker's GREEN checkmark TURNS into a RED X. His proud smile flips to shock/horror.

**Text on screen:** "87% of people can be identified from just zip code, gender, and birth date."

**Narrator:** "With today's technology, putting the names back is easy. Anonymization is an illusion."

**Purpose:** The critical insight — Lego pieces that come apart can be put back together. Everyone who ever played with Lego understands this instinctively. This is the Palantir/hospital reality: anonymization doesn't actually protect anyone.

**Source:** Latanya Sweeney's research — re-identified a governor's medical records from a $20 voter database. Netflix users identified from just 2 movie ratings. 95% of cellphone users identified from 4 location points.

---

## SCENE 6 — "So Let's Run AI Locally" (5 seconds)

**Visual:** The architect has an idea — lightbulb above his head. He looks at the cabin building site.

**Narrator:** "So let's run AI inside our own building instead! But how?"

**Purpose:** Transition from "the problem" to "the solutions." The viewer now understands WHY local AI matters. Now we show three attempts.

---

## SCENE 7 — Bad Way 1: Multi-Agent Frameworks (20 seconds)
**(CrewAI, Swarms, LangGraph, BeeAI, Claude Flow)**

**Visual:** The construction crew: 1 architect, 1 foreman (orange vest, clipboard), and 3 workers (hammer, saw, axe). They are at the cabin building site.

BUT: there is only ONE head with a GREEN helmet. The other 4 figures have no heads at all — just empty neck pegs.

The one figure with the head tries to do his work (sawing wood). After a few seconds, he pops his own head off and passes it to the next worker. Now THAT worker can think — he hammers a nail. Then he pops the head off and passes it to the next one. And so on.

All workers are standing in the SAME SPOT, crowded together inside a tiny box/room drawn on the ground (= one computer). They bump elbows.

A timer/stopwatch runs in the corner of the screen.

When the timer runs out: only a door stands alone in an empty field. The rest of the cabin is not built. Pathetic.

**Text on screen:** "CrewAI, Swarms, LangGraph — multiple agents, ONE computer, ONE brain. They take turns."

**Narrator:** "Existing AI frameworks put all their workers in one room with one brain. They take turns thinking. It's slow."

**Purpose:** Show that multi-agent frameworks share one machine = one brain passed around = painfully slow. The cramped box makes it visual.

---

## SCENE 8 — Bad Way 2: Model Splitting (20 seconds)
**(Petals, Exo, distributed-llama)**

**Visual:** Same crew, same cabin site. Now each worker stands in his own corner of the building site, spread apart. Each worker HAS a head — but all helmets are RED except one which is GREEN.

The one GREEN-helmet worker does a few seconds of work in his corner. Then he slowly walks to the next worker. They swap heads — now the second worker's helmet turns GREEN and the first one's turns RED. The second worker does a few seconds of work. Then walks to the next one. Swap. And so on.

The key visual: lots of WALKING between corners, lots of WAITING. Workers with RED helmets stand idle, frozen, doing nothing until it's their turn.

Timer runs in the corner.

When the timer runs out: scattered incomplete pieces. A window frame here, a door frame there, some planks in another corner. Nothing connects. No complete cabin.

**Text on screen:** "Petals, Exo — the model is split across machines. Each machine does a tiny piece, then waits."

**Narrator:** "Model splitting spreads the work across machines — but each machine only does a small piece and then waits for the next. Still slow."

**Purpose:** Show that pipeline/tensor parallelism has physical separation (good) but sequential dependency (bad). The walking = network latency. The red helmets = idle machines.

---

## SCENE 9 — The Good Way: BeehiveOfAI (20 seconds)

**Visual:** Same crew, same cabin site. Now EVERY worker has a head with a GREEN helmet. Each worker stands in his own corner.

They ALL work simultaneously. Hammer, saw, axe — everyone building their own section at the same time. Nobody walks to anyone. Nobody waits. Nobody passes anything.

The foreman (orange vest) stands in the center with her clipboard, checking off tasks as workers complete their sections.

Timer runs in the corner — same duration as before.

When the timer runs out: a COMPLETE beautiful wooden cabin. Smoke curling from the chimney. A welcome mat at the door. Birds (Lego birds) perched on the roof. Perfect.

**Text on screen:** "BeehiveOfAI — every machine has its own brain. They all work at the same time."

**Narrator:** "BeehiveOfAI gives every machine its own brain. They all work independently, at the same time. The project finishes on time."

**Purpose:** The fairy tale payoff — third time's the charm. The viewer has been waiting for this. All green helmets = all machines thinking independently = the project gets done.

---

## SCENE 10 — Ending / Call to Action (15 seconds)

*TBD — to be designed in a future session. Ideas:*
- *The architect admires the completed cabin*
- *Return to the businessman from Scene 1 — now picking UP the money instead of dropping it*
- *End card with BeehiveOfAI logo and GitHub link*
- *Tagline: "Not another multi-agent framework. Actual distributed AI."*

---

## Production Notes

### Color System
- **GREEN** = good, safe, working, independent
- **RED** = bad, danger, broken, dependent
- Established in Scene 3 (arrows), reinforced in Scene 5 (checkmark to X), used throughout Scenes 7-9 (helmets)

### Timer/Stopwatch
- Appears in Scenes 7, 8, and 9
- Same duration each time — the visual punchline is the RESULT after the same amount of time
- Bad Way 1: just a door (pathetic)
- Bad Way 2: scattered fragments (fragmented)
- Good Way: complete cabin with chimney smoke (perfect)

### Sound Design
- Lego snap/pop sounds for anonymization and de-anonymization scenes
- Construction sounds (hammering, sawing) for building scenes
- Timer ticking sound during the three attempts
- Cheerful resolution music for the Good Way scene

### Fairy Tale Structure
The three attempts (Bad 1, Bad 2, Good) follow the classic fairy tale pattern where the first two attempts fail and the third succeeds. This is psychologically satisfying — by the third attempt, the viewer is rooting for success.
