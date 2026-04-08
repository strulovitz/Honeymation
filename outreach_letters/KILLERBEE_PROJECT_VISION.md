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

### Concept name: KillerBee
- After the Africanized Honey Bee (A. m. scutellata hybrid)
- Known as the "killer bee" — takes over hives of normal bees
- Fits the threat narrative: killer bees can kill humans, bad actors kill humans too
- The system "takes over" regular hives by commanding them from above

### Software repo name: GiantHoneyBee
- The Giant Honey Bee is physically the BIGGEST bee species
- She makes "mad honey" — intoxicating, makes people feel drunk
- Users of this system will be "drunk with power" from the computational capability
- Fun, memorable, fits the bee theme

## Architecture (initial thinking)

- The Mega-Queen is just a Queen Bee whose "workers" are other Queen Bees
- Each level is the same code, just nested
- Communication: Mega-Queen → Queen → Workers → Queen → Mega-Queen
- The existing HoneycombOfAI code stays UNTOUCHED — it's Level 1
- GiantHoneyBee is a NEW layer on top that orchestrates multiple Level 1 hives

## Repositories (on github.com/strulovitz)

- **GiantHoneyBee** — the new software (hierarchical orchestration layer)
- A new book repo (name TBD) — documenting the entire project

## Development approach

- Plan: Claude Opus 4.6
- Code: Claude Sonnet 4.6 (or latest fast model)
- Document: New book, parallel to "The Distributed AI Revolution"
- Process: Same vibe coding approach as the original project

## Book name ideas (TBD — need to decide)

(see discussion below)

## Key design principle

The existing bees (HoneycombOfAI) don't change. They don't know they're being orchestrated. The GiantHoneyBee layer sits ON TOP and treats regular Queen Bees as its workers. Like a general commanding colonels who command soldiers — the soldiers don't need to know about the general.

## Connection to threats / hail mary letter

The hail mary letter says hierarchical hives can "scale to match frontier models' output capacity." KillerBee is the PROOF. Building it makes the threat REAL, not theoretical.
