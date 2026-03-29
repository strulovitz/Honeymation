# The Anonymization Illusion — Research Notes

## Context

Discovered via Israeli newspaper article (2026-03-29) about Palantir and New York hospitals. BDS activists pressured hospitals to drop Palantir (which also helps Israel). Hospitals will switch to internal solutions by October 2026. But the key discovery: hospitals ARE using external AI with patient data — they just anonymize it first. And anonymization is broken.

## Why This Changes Our Video's Premise

**Old premise:** "Organizations with sensitive data CAN'T use big AI, so they need us."

**New premise (better):** "Organizations with sensitive data ARE ALREADY using big AI. They strip the names off and pretend it's safe. It's NOT safe. We are the real solution."

This is stronger because:
1. It's TRUE — hospitals, governments, corporations all do this today
2. It creates URGENCY — the danger isn't hypothetical, it's happening right now
3. It positions BeehiveOfAI as "the better way" not "the only way"

## Key Statistics (from academic research)

- **87%** of Americans can be uniquely identified from just zip code + gender + birth date (Latanya Sweeney, 1997)
- **95%** of cellphone users identified from just 4 location data points (MIT researchers)
- **68%** re-identification success from knowing just 2 movie ratings (Netflix Prize attack)
- **84%** re-identification of anonymized Swiss court cases
- **43%** match rate using hospital + voting records in Washington State (2011)
- A governor's medical records were re-identified from a **$20** voter database

## How De-Anonymization Works

Attackers combine anonymized datasets with publicly available information:
- Cross-referencing with public databases (voter registries, property records)
- Combining indirect identifiers (zip codes, birth dates, gender)
- Linking multiple datasets together
- Analyzing behavioral patterns (location data, search histories)

Key insight: "seemingly anonymized" data can be matched with auxiliary sources through basic methods. Technical expertise is sometimes not even needed.

## The Lego Visualization

Lego is the PERFECT medium for this because Lego minifigures are literally designed with modular snap-on/snap-off parts:

**Anonymization = removing Lego parts:**
- POP off the hair piece
- POP off the glasses/hat/accessories
- Peel off the name tag
- Spin the face from detailed to blank

**De-anonymization = snapping Lego parts back on:**
- SNAP the hair back
- SNAP the glasses back
- SLAP the name tag back
- Spin the face from blank to detailed

The instinctive understanding: if you can take Lego apart, someone else can put it back together. Every kid knows this.

## Legal Reality

- HIPAA allows data release if "de-identified" — but cannot prevent re-identification through external datasets
- GDPR requires anonymization but sets an extremely high bar that is rarely truly met
- Pharmacies sell de-identified patient data to mining companies
- Federal courts have struck down state-level protections on medical data mining
- The law turns a blind eye because there was no alternative — until now

## Relevant Regulations
- **HIPAA** (US healthcare)
- **GDPR** (EU data protection)
- Various state and national privacy laws

## Sources
- Wikipedia: Data anonymization — https://en.wikipedia.org/wiki/Data_anonymization
- Wikipedia: Data re-identification — https://en.wikipedia.org/wiki/Data_re-identification
- Latanya Sweeney's foundational research on re-identification
- Netflix Prize de-anonymization attack (2006-2007)
- AOL search query identification (2006)
- MIT location data research
