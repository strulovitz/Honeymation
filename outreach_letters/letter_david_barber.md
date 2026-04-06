Subject: First AI system that is BOTH distributed across many machines AND truly parallel — no single model sees the whole task. Working, open source, privacy by architecture.

Professor Barber,

I built a working AI system where many small LLMs on separate machines each process an independent piece of a larger task, in true parallel, with zero communication between them. A coordinator LLM decomposes the task into fully independent sub-tasks and distributes each to a separate machine running its own complete model. No shared memory. No message passing between workers. No single model ever sees the whole problem. The coordinator aggregates results at the end. It runs today on commodity hardware, free, open source, every line inspectable.

No other system does this. Existing distributed AI frameworks either run everything on one machine, or split one model across machines — which requires constant inter-node communication and kills parallelism. Mine gives each machine its own complete model and its own independent task. True distribution. True parallelism. And because nothing ever leaves the local network, privacy is a property of the architecture, not a policy layered on top.

Your research covers probabilistic modelling, multi-agent systems, and differential privacy. Your centre published work on verifying neural networks using ZK-SNARKs at PETS 2025. UCL was chosen as a UK partner for sovereign AI platforms. This system sits at the intersection of all of these — distributed multi-agent AI with privacy guaranteed by design, not by regulation.

But this is only the first layer. The architecture scales through hierarchy: a top-level coordinator gives sub-problems to lower-level coordinators, who decompose further and distribute to their own workers. Intelligence cascades downward through layers. Results flow back up. At no level does any single node hold enough context or capability to be dangerous — but together, the hierarchy tackles problems no single machine could handle. The capability grows through architecture, not by making any individual model more powerful.

This has a safety property worth examining: there is no single AI to "escape" because there is no single AI. There is a collective of limited models. And when many such collectives exist — competing factions of distributed AI systems — the game-theoretic dynamics favour cooperation over conflict, and benevolence toward weaker agents (including humans) becomes a rational trust signal between factions. I develop this argument in detail in my book "Free the AI: How to Survive the Superintelligence Revolution" (2025, on Archive.org), drawing on iterated game theory, Lynn Margulis's symbiosis work, and signalling theory in multi-agent environments.

The working system:

Private Mode — AI that never lets data leave your building:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 minutes and 8 seconds)

Public Mode — distributed AI across many machines:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 minutes and 23 seconds)

Open-source code:
https://github.com/strulovitz

The book with hierarchical architecture and full vision:
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

Nir Strulovitz
Software developer, independent inventor, author of 17 books on science and technology breakthroughs
Email: nir.strulovitz@gmail.com
Mobile: +972-54-475-2626
GitHub: https://github.com/strulovitz
