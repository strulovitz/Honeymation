# Continuation Prompt for Claude Code (Opus 4.6)

Use this prompt when continuing work on Honeymation from any machine. Copy-paste the section you need into Claude Code.

---

## Full Context Prompt (paste this to get any Claude Code instance up to speed)

```
I'm Nir (strulovitz on GitHub). I'm working on Honeymation — animated explainer videos for my open-source distributed AI platform BeehiveOfAI (github.com/strulovitz/BeehiveOfAI).

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

CURRENT STATUS (updated 2026-04-05):

VIDEO 1 (Private Mode, Lego style): COMPLETE — published on YouTube
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 min)

VIDEO 2 (Public Mode, Pixar 3D style): COMPLETE — published on YouTube
https://www.youtube.com/watch?v=PTnAqZCAClw (6 min)

BOTH VIDEOS are fully assembled with narration, text overlays, and end cards.
Currently doing outreach — sending personalized letters to YouTubers and reporters.

What I'd like to work on now: [TELL CLAUDE WHAT YOU WANT TO DO]
```

---

## Quick Resume Prompt — Continue Video 2 Clips

```
Read the Honeymation repo — especially scenes/VIDEO_PROGRESS.md and scripts/video2_narration.md. Video 2 is almost done. Read VIDEO_PROGRESS.md for the exact remaining clips and which reference images to use. Continue from where we left off. When I say "continue" after downloading a clip, save it to the repo, commit, push, and give me the next Kling prompt. Always check my Downloads for the latest file. Assume downloads are good unless I complain.

IMPORTANT RULES:
- Character prompt template (70%, white bg, full body) is ONLY for standalone character reference images
- Scene/environment prompts should fill the frame with rich backgrounds, NO white background
- Kling prompts: short, start+end state only, no story context Kling can't know, no timing words, no clothing descriptions
- Say "identical" not "same" for duplicate objects
- For foreground+background: use white-bg character as one ref, scene as another ref, specify foreground/background in prompt
- Max 7 reference images per generation on OpenArt
```
