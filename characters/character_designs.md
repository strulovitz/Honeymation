# Character Designs — Lego Minifigures

## Overview

All characters are **Lego minifigures** in a 3D-rendered Lego world. The video uses the visual language of Lego — snap-on/snap-off parts, modular construction, bright colors — to explain complex technical concepts.

The construction metaphor maps to distributed AI roles:
- **Architect** brings the plan (the client/beekeeper — what needs to be done)
- **Foreman** splits the plan into tasks and coordinates (the queen)
- **Workers** do the actual building, each on their own section (the worker nodes)

---

## The Architect (= Beekeeper in BeehiveOfAI)

**Role:** The client. Brings the project. Receives the finished result.

**Lego Design:**
- Yellow safety helmet
- Suit and tie (printed torso) with safety vest over it
- Holds a large rolled-up blueprint in BOTH hands
- Dress shoes (not boots)
- Distinguished, professional expression (Lego printed face)

**AI prompt keywords:** Lego minifigure, architect, yellow hard hat, suit and tie, safety vest, holding rolled blueprint paper both hands, professional expression, 3D rendered Lego style

---

## The Foreman (= Queen in BeehiveOfAI)

**Role:** Receives the full job from the Architect. Splits it into independent subtasks. Assigns one to each Worker. Monitors progress. Combines all results.

**Lego Design:**
- Yellow safety helmet
- Orange safety vest (high visibility — she's the one everyone reports to)
- Walkie-talkie in one hand
- Clipboard in the other hand
- Professional work pants
- Confident, organized expression

**AI prompt keywords:** Lego minifigure, construction foreman, yellow hard hat, orange safety vest, walkie-talkie, clipboard, confident expression, female, 3D rendered Lego style

---

## The Workers (= Workers in BeehiveOfAI)

**Role:** Each receives one subtask, works on it independently, returns the result.

**Lego Design:**
- Yellow safety helmet (GREEN in the "good way" scenes, RED in "bad way 2")
- Jeans overalls (classic construction worker)
- Tool belt around waist
- Each worker holds a DIFFERENT tool to make them visually distinct:
  - Worker 1: Hammer
  - Worker 2: Saw
  - Worker 3: Axe
- Sturdy work boots
- Cheerful, hardworking expression

**AI prompt keywords:** Lego minifigure, construction worker, yellow hard hat, jeans overalls, tool belt, [hammer/saw/axe], cheerful expression, 3D rendered Lego style

---

## The Businessman (Scene 1 only)

**Role:** Represents the viewer's company. Hook character — shows money being lost.

**Lego Design:**
- No helmet — slicked-back hair piece
- Dark suit and tie (printed torso)
- Briefcase in one hand
- Worried/stressed expression
- Dress shoes

**AI prompt keywords:** Lego minifigure, businessman, dark suit, briefcase, worried expression, slicked back hair, 3D rendered Lego style

---

## The Giant AI (Scene 3)

**Role:** Represents frontier AI models (ChatGPT, Google AI, etc.) — powerful but dangerous for sensitive data.

**Lego Design:**
- ONE big Lego minifigure, the height of several regular minifigures
- Sleek, modern look — maybe a futuristic visor or glowing eyes
- Friendly smile at first, then frown when arrows turn red
- Should look impressive and powerful but NOT evil

**AI prompt keywords:** giant Lego minifigure, tall, futuristic, glowing eyes, friendly smile, towering over small minifigure, 3D rendered Lego style

---

## The Hospital Worker (Scenes 4-5)

**Role:** Performs the anonymization. Represents organizations that strip data before sending to AI.

**Lego Design:**
- White lab coat or medical scrubs (printed torso)
- Stethoscope around neck (or just the print)
- Initially proud/smiling, then shocked when de-anonymization happens
- Standard Lego minifigure size

**AI prompt keywords:** Lego minifigure, doctor, white lab coat, stethoscope, 3D rendered Lego style

---

## The Five Patients (Scenes 4-5)

**Role:** Represent sensitive data that gets anonymized and then de-anonymized.

**Lego Design — Before Anonymization (each unique):**
1. Red hair piece + glasses accessory + name tag "SARAH"
2. Beard face print + baseball cap + name tag "DAVID"
3. Blonde pigtails hair piece + name tag "EMMA"
4. Top hat + mustache face print + name tag "JAMES"
5. Ponytail hair piece + earring accessories + name tag "LISA"

**Lego Design — After Anonymization (all identical):**
- Blank yellow head (no face print, no features)
- No hair piece, no accessories
- No name tags
- Generic body — all five look exactly the same

**Key animation:** The snap-on/snap-off of Lego parts IS the anonymization/de-anonymization process. Removing hair, accessories, and face = anonymization. Snapping them back on = de-anonymization. Every viewer who played with Lego understands this instinctively.

**AI prompt keywords:** five identical Lego minifigures, blank yellow heads, no hair, no accessories, generic, 3D rendered Lego style

---

## The Attacker (Scene 5)

**Role:** Represents bad actors who can reverse anonymization using public records.

**Lego Design:**
- Dark hood or black beanie
- Dark clothing
- Holds a magnifying glass
- Sinister/sneaky expression (Lego style — not truly scary, just mischievous)
- Has a large book labeled "PUBLIC RECORDS" or a screen/tablet showing data

**AI prompt keywords:** Lego minifigure, hacker, dark hood, magnifying glass, sneaky expression, 3D rendered Lego style

---

## The Head-Sharing Mechanic (Scenes 7-8)

This is the most important visual concept in the video.

### Scene 7 (Bad Way 1 — CrewAI etc.):
- 5 Lego figures but only ONE head with a GREEN helmet
- 4 figures have empty neck pegs (no head at all)
- They pass the single head from one to the next
- A Lego head popping on and off a neck peg is a natural, non-threatening action
- All figures are crammed inside a small drawn box on the ground (= one computer)

### Scene 8 (Bad Way 2 — Petals/Exo):
- 5 Lego figures, each HAS a head
- But only ONE helmet is GREEN at a time, rest are RED
- They swap the GREEN helmet (not the whole head) — representing the active computation token
- Workers are spread out in different corners but must walk to each other to swap
- Walking = network latency, waiting = idle compute

### Scene 9 (Good Way — BeehiveOfAI):
- 5 Lego figures, each has their own head with a GREEN helmet
- Nobody passes anything, nobody walks to anyone
- Everyone works independently and simultaneously

---

## Visual Hierarchy

When the full crew is in a scene together:
1. **Architect** — tallest or most forward, holding the blueprint
2. **Foreman** — center, with clipboard and walkie-talkie, directing
3. **Workers** (3) — spread out, each working on their own section of the cabin

---

## The Cabin (The Project)

The cabin represents the viewer's project — the work their company needs to get done.

**Lego Design:**
- Wooden cabin / log cabin style (all Lego bricks, brown/tan colors)
- Small, simple structure: 4 walls, roof, door, windows, chimney
- When complete: smoke from chimney, welcome mat, Lego birds on roof
- When incomplete (Bad Ways): just a door standing alone, or scattered wall fragments

**Three states:**
1. **Bad Way 1 result:** Just a lonely door frame standing in an empty field
2. **Bad Way 2 result:** Scattered pieces — a window here, a door there, some planks — nothing connects
3. **Good Way result:** Complete beautiful cabin with chimney smoke and birds
