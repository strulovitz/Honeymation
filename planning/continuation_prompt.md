# Continuation Prompt for Claude Code (Opus 4.6)

Use this prompt when continuing work on Honeymation from any machine. Copy-paste the section you need into Claude Code.

---

## Full Context Prompt (paste this to get any Claude Code instance up to speed)

```
I'm Nir (strulovitz on GitHub). I'm working on Honeymation — an animated explainer video for my open-source distributed AI platform BeehiveOfAI (github.com/strulovitz/BeehiveOfAI).

Please read these files from the Honeymation repo to get full context:
1. scripts/video1_private_mode.md — the complete 12-scene script
2. characters/character_designs.md — all character designs with AI prompt keywords
3. planning/competitive_differentiation.md — the 3 categories of competition and how we visualize each
4. planning/anonymization_research.md — the Palantir/hospital research and de-anonymization statistics

KEY DECISIONS ALREADY MADE (do not revisit these):

- STYLE: Everything is Lego animation (like Lego Movie). No insects. No bees, ants, or grasshoppers. All characters are Lego minifigures in a 3D Lego world.

- CORE VISUAL METAPHOR: Lego head-sharing. Competitors' workers share ONE head (pass it around = time-sharing). Our workers each have their own head with a GREEN helmet. This is THE key image of the video.

- COLOR SYSTEM: GREEN = good/safe/working. RED = bad/danger/idle. Established in Scene 3 (arrows), used throughout.

- ANONYMIZATION SCENE: Lego parts (hair, glasses, name tags) get popped OFF to "anonymize" patient data. A shadowy attacker snaps them back ON using public records = de-anonymization. "If you can take Lego apart, someone can put it back together."

- THREE ATTEMPTS (fairy tale structure):
  - Bad Way 1 (Scene 7): CrewAI etc — 5 workers, ONE head, crammed in one box. Result: just a door.
  - Bad Way 2 (Scene 8): Petals/Exo — workers in corners, ONE green helmet walks between them. Result: scattered fragments.
  - Good Way (Scene 9): BeehiveOfAI — ALL green helmets, all working simultaneously. Result: complete cabin.

- ENDING (Scenes 10-12): Boardroom scene (3 quick cuts: hospital/business/military — good for org) → Phone call scene (3 quick cuts: same sectors — personal promotion for Bob) → Thumbs up + end card.

- CONSTRUCTION THEME: The project = building a wooden cabin. Crew = architect, foreman, 3 workers (hammer, saw, axe).

- VIDEO LENGTH: ~2 min 43 sec, 12 scenes total.

- TOOL: OpenArt AI (I have a subscription) for image and video generation (Kling, Seedance, Sora, Wan, LTX, Hailuo).

CURRENT STATUS: The complete script and character designs are written. No visual assets have been generated yet.

What I'd like to work on now: [TELL CLAUDE WHAT YOU WANT TO DO]
```

---

## Quick Resume Prompts (for specific tasks)

### To start generating character images:
```
Read the Honeymation repo (scripts/video1_private_mode.md and characters/character_designs.md). The script and designs are complete. I want to start generating character reference images using OpenArt AI. Help me craft the best prompts for each character, starting with the construction crew (Architect, Foreman, 3 Workers) since they appear in the most scenes. Remember: everything is Lego minifigure style, 3D rendered.
```

### To start generating scene-by-scene clips:
```
Read the Honeymation repo (scripts/video1_private_mode.md and characters/character_designs.md). I have character reference images ready. Now I want to generate short video clips scene by scene using OpenArt AI. Help me craft video generation prompts for each scene, starting with Scene 1 (businessman dropping cash). Remember: everything is Lego animation style.
```

### To work on the ending scenes:
```
Read the Honeymation repo, especially Scenes 10-12 in scripts/video1_private_mode.md and the Alice/Bob character designs. I want to refine the ending scenes — the boardroom (Scene 10), the phone call (Scene 11), and the end card (Scene 12). These are the emotional payoff of the whole video.
```

### To refine the script or add narration timing:
```
Read scripts/video1_private_mode.md from the Honeymation repo. The 12-scene script is complete. I want to [add exact narration text / adjust timing / add transition details / write the voiceover script]. Help me refine it.
```
