# KillerBee / GiantHoneyBee — The Next Project

> Written: 2026-04-08
> This is the VISION document. Save EVERYTHING here. Every decision, every idea.

## The Concept: Hierarchical Hives

What we built so far is ONE BLOCK — one Queen Bee, multiple Worker Bees. This is Level 1.

**KillerBee** is Level 2+:

- A **Mega-Queen** receives a harder task
- She does NOT have ordinary workers
- Instead, her "workers" are REGULAR Queen Bees (each with their own hive of workers)
- The Mega-Queen splits the hard task into pieces
- Each regular Queen Bee receives one piece and splits it FURTHER into subtasks for her workers
- Workers do the work, send results back to their Queen
- Each Queen combines her workers' results into one answer
- Each Queen sends her answer back to the Mega-Queen
- The Mega-Queen combines ALL queens' answers into one MEGA-ANSWER

**Modular:** Must support ANY number of levels — 2, 3, 10, unlimited. The only limit is available hardware, NEVER our software.

## Naming

### The top-level coordinator: RajaBee
- Named after **Megachile pluto**, also known as **Wallace's Giant Bee** or **Raja Ofu** (lit. "king of the bees")
- The LARGEST bee species in the world — found in Indonesia
- Was thought EXTINCT and then REDISCOVERED in 2019 — a comeback story
- Named after **Alfred Russel Wallace** — co-discoverer of evolution with Darwin, but overshadowed by him. Just like local AI is overshadowed by Big Tech. Both were there first but nobody noticed.
- "Raja" means king — instinctively sounds majestic (Maharaja association)
- Hierarchy: **Worker Bee → Queen Bee → Raja Bee** — each level sounds progressively more powerful
- Clean in code: `RajaBee` class
- The naming story (Wallace, extinction, rediscovery, biggest bee) goes in the book

### Website/server repo: KillerBee
- After the Africanized Honey Bee (A. m. scutellata hybrid)
- Known as the "killer bee" — takes over hives of normal bees
- Fits the threat narrative: killer bees can kill humans, bad actors kill humans too
- The system "takes over" regular hives by commanding them from above

### Client software repo: GiantHoneyBee
- The Giant Honey Bee is physically one of the biggest bee species
- She makes "mad honey" — intoxicating, makes people feel drunk
- Users of this system will be "drunk with power" from the computational capability
- Fun, memorable, fits the bee theme

## Architecture (initial thinking)

- The RajaBee is just a Queen Bee whose "workers" are other Queen Bees
- Each level is the same code, just nested
- Communication: RajaBee → Queen → Workers → Queen → RajaBee
- The existing HoneycombOfAI code stays UNTOUCHED — it's Level 1
- GiantHoneyBee is a NEW layer on top that orchestrates multiple Level 1 hives
- Regular Queens don't need to know they're being orchestrated by a RajaBee — like soldiers don't need to know about the general

## Testing Phases (agreed 2026-04-08)

### Phase 1: Everything on Laptop, localhost, different ports — test the LOGIC
- Port 5000: Regular Queen 1 + workers (small model, e.g. qwen2.5:1.5b)
- Port 5001: Regular Queen 2 + workers (small model)
- Port 5002: RajaBee (slightly bigger model, e.g. llama3.2:3b)
- All on same machine, no VMs, no networking headaches
- RTX 5090 (24GB VRAM) can handle multiple small models easily

### Phase 2: RajaBee on Laptop, regular Queens on Desktop — test REAL networking
- Tests real LAN communication between machines
- Same as original HoneycombOfAI testing approach

### Phase 3: Add lightweight Linux VMs for more Queens — test SCALE
- Linux host on both machines (Debian 13 on Laptop, Linux Mint 22.2 on Desktop)
- Alpine Linux or Debian minimal VMs — no GUI, 512MB RAM each
- Avoids Windows Defender issues from macOS VM disaster
- CPU-only models in VMs, GPU models on host

### Key decisions:
- Design for N levels, test on 2 levels
- Small models for testing (tinyllama, qwen2.5:1.5b, llama3.2:3b)
- Linux-first development to avoid Windows networking issues
- The limit should always be HARDWARE, never our SOFTWARE

## Repositories (on github.com/strulovitz) — PARALLEL STRUCTURE

### Original project:
| Role | Name | Description |
|------|------|-------------|
| Client software | HoneycombOfAI | Installed on machines — Queen Bee + Worker Bees |
| Website/server | BeehiveOfAI | Marketplace, user management, payments |
| Book | TheDistributedAIRevolution | Documents the entire Level 1 project |

### New project (one level up):
| Role | Name | Description |
|------|------|-------------|
| Client software | **GiantHoneyBee** | Hierarchical orchestration layer — Mega-Queen commands regular Queens |
| Website/server | **KillerBee** | Manages mega-queens, hierarchy, multi-level coordination |
| Book | **MadHoney** | "Mad Honey: How Hierarchical AI Swarms Will Change Everything" |

## Development approach

- Plan: Claude Opus 4.6
- Code: Claude Sonnet 4.6 (or latest fast model)
- Document: "Mad Honey" book, parallel to "The Distributed AI Revolution"
- Process: Same vibe coding approach as the original project

## Book: "Mad Honey: How Hierarchical AI Swarms Will Change Everything"

### The naming story (MUST be in the book):
The RajaBee is named after Megachile pluto — Wallace's Giant Bee — the largest bee species in the world. It was discovered by Alfred Russel Wallace, the man who independently conceived the theory of evolution at the same time as Charles Darwin, but was overshadowed by him. Wallace sent his paper to Darwin, who realized someone else had reached the same conclusion. Darwin got the fame. Wallace got a footnote.

Wallace's Giant Bee was thought extinct for over a century. Then in 2019, it was rediscovered in the forests of Indonesia — alive, unchanged, the biggest bee on Earth, quietly existing while the world forgot about it.

The parallel is exact. Local distributed AI has been possible for years. But the world was too busy worshipping the Darwins of AI — the giant corporations, the billion-dollar models, the cloud empires — to notice that a simpler, more resilient approach was quietly waiting to be rediscovered. Like Wallace's bee, it was always there. It just needed someone to look.

The "mad honey" in the title refers to the Giant Honey Bee (Apis dorsata laboriosa), which produces honey with naturally intoxicating properties — grayanotoxins from rhododendron nectar that cause euphoria and hallucination. The power of hierarchical AI swarms is similarly intoxicating. Once you taste what unlimited scaling on free hardware can do, there is no going back to paying for cloud AI.

## Key design principle

The existing bees (HoneycombOfAI) don't change. They don't know they're being orchestrated. The GiantHoneyBee layer sits ON TOP and treats regular Queen Bees as its workers. Like a general commanding colonels who command soldiers — the soldiers don't need to know about the general.

## Connection to threats / hail mary letter

The hail mary letter says hierarchical hives can "scale to match frontier models' output capacity." KillerBee is the PROOF. Building it makes the threat REAL, not theoretical.
