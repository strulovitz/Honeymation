Subject: You are "Rethinking Multi-Agent Systems in the Era of LLMs." I already built one. It works. Open source. No data leaves the network.

Professor Wooldridge,

You have spent 30 years defining the field of multi-agent systems. You wrote the textbook — literally. An Introduction to MultiAgent Systems is the standard reference in the field. You received the ACM Autonomous Agents Research Award, the Lovelace Medal, and you have been President of IJCAI, EurAI, and IFAAMAS. You are the person who made multi-agent systems a serious discipline.

And right now, in 2026, you are running a project at Oxford called "Rethinking Multi-Agent Systems in the Era of LLMs." You hired two postdocs for it. You organized a workshop at Oxford in September 2025. You gave a colloquium talk on it in January 2026. Your research question is: how can LLMs be used to realize the classic vision of multi-agent systems?

I built a working answer to that question. And it has a property that changes everything: no data ever leaves the local network.

I am a software developer with years of experience, an independent inventor, and the author of 17 books on breakthroughs in science and technology. I built an open-source distributed AI system where a stronger local LLM acts as a coordinator agent. It receives a task, decomposes it into fully independent sub-tasks, and distributes each sub-task to separate worker agents — each running its own complete LLM instance on a separate machine on the local network. Each worker processes its sub-task with zero inter-agent communication. No shared memory. No message passing between workers. Pure task-level parallelism with complete agent independence. When all workers complete, the coordinator aggregates the results.

In multi-agent systems terms: the coordinator is a rational agent that performs task decomposition and allocation. The workers are autonomous agents with full local reasoning capability and no inter-agent communication channel. The system achieves coordination without cooperation — each agent acts independently on its assigned sub-task, and the coordination emerges from the decomposition strategy of the coordinator, not from runtime interaction between workers.

This is not CrewAI or AutoGen or LangGraph, where "agents" share a single machine and pass messages back and forth. Those are pipelines pretending to be multi-agent systems. This is actual distributed multi-agent AI: separate machines, separate models, separate tasks, true parallelism, zero communication.

But here is why this matters beyond computer science.

Your Prime Minister said "This is not our war" and refused to follow America into Iran. President Trump responded by threatening to abandon Britain. The alliance between the United Kingdom and the United States is under the greatest strain in decades.

And yet — while Britain asserts its political independence — every British university, every British hospital, every British government department that uses ChatGPT, Google Gemini, or Microsoft Copilot is sending the raw content of British intellectual work through American corporate servers. American servers controlled by American companies with American government contracts, operating under American jurisdiction, subject to American intelligence frameworks. Every research query. Every document analysis. Every strategic question. Flowing through infrastructure controlled by a country whose president just threatened your country.

My system eliminates this dependency entirely. It runs on local hardware, behind a local firewall, with zero external data transmission. A British university can run world-class AI on its own computers without a single byte touching an American server.

This is what your 30 years of multi-agent systems research looks like when it meets the real world: distributed AI that is not just technically superior but strategically necessary.

I have made two short animated videos explaining the system:

Private Mode — AI that never lets data leave your building:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 minutes and 8 seconds)

Public Mode — distributed AI across many machines:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 minutes and 23 seconds)

Full open-source code:
https://github.com/strulovitz

Non-technical book explaining the concept and the personal story behind it:
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

I am actively seeking paid collaboration — as a consultant or external contractor — with any institution interested in developing improvements or new applications based on this architecture. I work remotely and am available immediately.

With deep respect for three decades of foundational work,
Nir Strulovitz
Software developer, independent inventor, author of 17 books on science and technology breakthroughs
Email: nir.strulovitz@gmail.com
Mobile: +972-54-475-2626
GitHub: https://github.com/strulovitz
