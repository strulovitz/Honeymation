# Character Designs — Construction Theme

## Overview

All bee characters share the same cute 3D Pixar-style base design. They are differentiated by their construction-themed costumes. All three wear yellow safety helmets, unifying them visually while costumes differentiate their roles.

The construction metaphor maps perfectly to the distributed AI roles:
- Architect brings the plan (what needs to be done)
- Foreman splits the plan into tasks and coordinates workers
- Construction workers do the actual physical building, each on their own section

---

## Worker Bee (= Worker in BeehiveOfAI)

**Role:** Does the actual processing. Receives one subtask, processes it independently, returns the result.

**Costume:**
- Yellow safety helmet
- Jeans overalls (classic construction worker look)
- Tool belt around waist
- Holds a hammer in one hand
- Holds a wrench in the other hand
- Sturdy work boots

**Personality:** Cheerful, hardworking, focused on the task. Doesn't need to talk to other workers — just does the job and comes back.

**AI prompt keywords:** cute 3D Pixar cartoon bee, construction worker, yellow hard hat, jeans overalls, tool belt, hammer, wrench, cheerful expression

---

## Queen Bee (= Queen in BeehiveOfAI)

**Role:** Receives the full job from the Architect/Beekeeper. Splits it into independent subtasks. Assigns one to each Worker. Monitors progress. Combines all results into the final deliverable.

**Costume:**
- Yellow safety helmet
- Orange safety vest (high visibility — she's the one everyone reports to)
- Holds a walkie-talkie in one hand (communication/coordination)
- Holds a clipboard in the other hand (planning, logistics, tracking which subtask is done)
- Professional work pants

**Personality:** Confident, organized, calm under pressure. The manager who makes sure everything comes together on time.

**AI prompt keywords:** cute 3D Pixar cartoon bee, construction foreman, yellow hard hat, orange safety vest, walkie-talkie, clipboard, confident expression, female

---

## Beekeeper Bee (= Beekeeper in BeehiveOfAI)

**Role:** The client. Brings the job (the architectural plan). Receives the finished result. In the macro (human) scale, this is the lawyer/doctor/officer. In the micro (bee) scale, this is the architect.

**Costume:**
- Yellow safety helmet
- Suit and tie under a safety vest (the "boss" — more corporate than the others)
- Holds a large rolled-up blueprint/tracing paper in BOTH hands (the plan, the vision)
- Looks slightly more important/distinguished than the others
- Dress shoes instead of work boots

**Personality:** Professional, visionary, trusts the foreman to handle execution. Brings the big picture.

**AI prompt keywords:** cute 3D Pixar cartoon bee, architect, yellow hard hat, suit and tie, safety vest, holding rolled blueprint paper both hands, distinguished expression, professional

---

## Visual Hierarchy

When all three are in the same scene, the visual hierarchy should be clear:
1. **Beekeeper/Architect** — tallest or most forward, holding the blueprint
2. **Queen/Foreman** — center, with clipboard and walkie-talkie, directing
3. **Workers** — multiple (3-5), spread out, each working on their own section

---

## The Chain Visual (Ants vs Bees — Independence)

**Ants (model parallelism):**
- 5 ants literally CHAINED together
- Trying to carry one giant object together
- One ant trips — they ALL fall
- Represents: constant inter-node communication, one failure breaks everything

**Bees (task parallelism):**
- 5 bees flying freely, NO chains
- Each carries their own small piece independently
- One bee gets lost in a cloud — the other four don't even notice
- They deliver their pieces successfully
- Represents: independent processing, fault tolerance, no synchronization needed
