Subject: For Dr. Morea, CMIO: $0 AI system replacing Palantir — HIPAA-compliant, no patient data leaves NYC H+H

Dear Dr. Morea,

You are probably the only person in the entire NYC Health + Hospitals system who has both a computer science degree and a medical degree. That makes you the only person who will fully understand what I am about to describe — and why it matters right now.

Your system just terminated its contract with Palantir. The Chief Data and AI Officer position has been vacant since January. CEO Katz has publicly stated he wants AI for radiology and cancer screening. Someone needs to bridge the gap between what the clinicians need and what the technology can safely deliver inside a public hospital. That person is you.

You came to Harlem in 2021 and built an entire IT division from scratch. You implemented systems that improved care coordination, reduced physician burnout, and enhanced clinical decision-making. Your philosophy is "make it easy to do the right thing and hard to do the wrong thing." That is exactly what I built.

I built an open-source distributed AI system where every machine runs its own independent AI model, entirely inside the hospital, on computers the hospital already owns. No patient data ever leaves the building. Not to any cloud. Not to any company. Not to any server outside the hospital walls. Zero external data transmission.

How it works — and I am telling you the technical details because you are the one person here who will appreciate them: a stronger local LLM acts as an automated coordinator. It receives a prompt, analyzes it, decomposes it into fully independent sub-tasks, and distributes each sub-task to a separate machine on the internal network. Each machine runs its own complete local LLM instance and processes its sub-task with zero communication to any other worker. No shared memory. No inter-node messaging. No pipeline parallelism. Pure task-level parallelism with complete independence between workers. When all workers finish, the coordinator aggregates the results into a single response. The entire pipeline runs behind the hospital's firewall on commodity hardware.

You studied health informatics at Indiana. You know the difference between systems that claim to be private and systems that actually are. Most "on-premise" AI solutions still phone home for model updates, telemetry, or licensing validation. This system does none of that. It is fully open-source. You can read every line of code. There is no binary blob, no API key, no cloud dependency. It runs on Ollama with any open-weight model. You could air-gap it tomorrow and it would still work.

This is not a product. This is not a startup. This is free, built by one person in one week, and it works. I am a software developer with years of experience, an independent inventor, and the author of 17 books on breakthroughs in science and technology.

You built your career at the intersection of medicine and technology because your father was a physician and you fell in love with programming as a teenager. You believe patients achieve the best outcomes when they are well-informed and when clinicians have the right tools. Imagine giving every doctor at Harlem Hospital an AI assistant that runs entirely inside the building — analyzing notes, drafting summaries, supporting clinical decisions — without a single byte of patient data ever touching an external server. That is what this system does.

And it costs nothing. No licensing fees. No vendor lock-in. No procurement process. It runs on hardware Harlem Hospital already owns.

I have made two short animated videos explaining how the system works:

Private Mode — how hospitals run AI without any data leaving their walls:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 minutes and 8 seconds)

Public Mode — distributed AI across many machines:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 minutes and 23 seconds)

The full open-source code:
https://github.com/strulovitz

A non-technical book explaining the concept and the personal story behind it:
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

I would be honored to demonstrate this system to you. You will understand it in five minutes. And you will know exactly where it fits in your hospital.

With deep respect,
Nir Strulovitz
Software developer, independent inventor, author of 17 books on science and technology breakthroughs
Email: nir.strulovitz@gmail.com
Mobile: +972-54-475-2626
GitHub: https://github.com/strulovitz
