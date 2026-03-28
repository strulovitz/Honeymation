# Video 1: Private Mode — Script

## Overview
- **Duration:** ~3 minutes
- **Style:** Cute 3D Pixar-style animation
- **Theme:** How organizations use BeehiveOfAI inside their building
- **Three-animal metaphor:** Grasshoppers (cloud AI), Ants (model splitting), Bees (task splitting)

---

## ACT 1 — The Human Problem (30 seconds)

A cute cartoon military officer has 1,000 files on his desk. Urgent triage needed. He picks up the phone to call the cloud AI company (show a grasshopper in a suit on the other end). But his security advisor slaps the phone out of his hand — "Those files are CLASSIFIED! You can't send them outside the building!" The grasshopper on the other end of the line morphs into a swarm of locusts eating a field. The officer gulps.

**Key message:** Cloud AI (OpenAI, Google) is powerful but dangerous for sensitive data.

---

## ACT 2 — The Wrong Way: Ants (45 seconds)

Someone suggests: "Let's use our own computers!" We see ants trying to carry one giant crumb together across a desk. They have to stay in a line, passing tiny bits of information back and forth constantly. One ant stumbles (network lag) and the whole chain breaks. The crumb falls. Everyone starts over.

Text on screen: "This is model splitting. It looks smart. It isn't."

**Key message:** Model parallelism (tensor/pipeline) requires constant inter-node communication and fails with network latency.

---

## ACT 3 — The Right Way: Bees (90 seconds)

Now we see the Queen Bee. She looks at the big task. She does her waggle dance — and in that one dance, each Worker Bee learns EVERYTHING she needs to know. The Queen tears the job into pieces. Each Worker Bee takes her piece, flies out alone, does her work alone, comes back alone. No trail to follow. No chain to break. One Worker gets lost? The others don't even notice — they finish their work anyway. The Queen assembles all the pieces back together. Done.

**CRITICAL INSERT — The Differentiation Scene:**
Show a split screen:
- LEFT SIDE: "Other tools" — 5 tiny agents sitting inside ONE computer box, sharing one brain, bumping into each other
- RIGHT SIDE: "BeehiveOfAI" — 5 separate computers in 5 separate rooms, each with their own brain, connected by simple arrows

Text on screen: "This is not another multi-agent framework. This is actual distributed computing. Different machines. Different GPUs. Different buildings."

**Key message:** Task parallelism with PHYSICALLY SEPARATE machines. Each worker is independent. This is what makes BeehiveOfAI different from CrewAI, Swarms, LangGraph, etc.

---

## ACT 4 — Back to Humans (30 seconds)

The officer gets the results. All 1,000 files analyzed. All data stayed inside the building. He calls his wife: "Honey... I'm coming home early." His phone buzzes — his general is calling: "That hive thing you set up just saved us 90% on AI. You're getting promoted." He smiles. A little bee winks at the camera.

**Key message:** Real cost savings, real privacy, real results.

---

## END CARD

BeehiveOfAI — github.com/strulovitz

"Not another multi-agent framework. Actual distributed AI."
