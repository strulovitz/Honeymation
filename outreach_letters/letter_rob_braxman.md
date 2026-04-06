Subject: You've been warning about AI surveillance for years. I built the solution. Open source, runs locally, nothing leaves.

Rob,

You have spent years telling people the truth: that every cloud service is a surveillance pipeline, that Big Tech collects everything, that your phone is a tracking device, that de-Googling is not paranoia but common sense. You built Brax.Me because you could not trust any existing social media platform. You sell de-Googled phones because the stock ones are spyware. You invented "What the Zuck" because someone needed to say it.

And now you are warning about the next wave: AI assistants that live on your machine and report back to Microsoft, Google, and Apple. You made a video about it — the new surveillance tool on your machine. You asked the question that nobody in the mainstream is asking: "Whose assistant is it really?"

I built the answer.

I am a software developer and independent inventor. I built an open-source distributed AI system that runs entirely on local hardware, on a local network, with zero cloud dependency. No API calls. No telemetry. No phoning home. No license server. No binary blobs. Every line of code visible on GitHub. You could air-gap it and it would still work. You could run it on a de-Googled machine and it would work. You could put it behind a VPN on an isolated VLAN and it would work. It needs nothing from the outside world.

Here is how it works: you install open-weight local LLMs on your own machines using Ollama. A stronger local model acts as a coordinator. You give it any task — writing, research, analysis, coding, planning — and it decomposes it into fully independent sub-tasks, distributes each sub-task to a separate machine on your local network, each machine runs its own complete LLM instance and processes its piece with zero inter-node communication, and the coordinator aggregates the results. No shared memory. No message passing between workers. Pure task-level parallelism. Everything behind your firewall. Nothing leaves.

You understand why this matters better than anyone on YouTube. You have explained to 700,000 people that Microsoft Copilot screenshots your activity. That Google Gemini reads your emails. That Apple Intelligence processes your data on Apple servers. That every "AI assistant" is really a corporate data collection agent wearing a helpful mask.

My system is the opposite. It is AI that actually works for YOU, on YOUR hardware, and the corporation gets nothing. Not your prompts. Not your data. Not even the knowledge that you are using it.

The AI industry could have built this years ago. The technology is not new — open-weight models exist, Ollama exists, local inference exists. But building a system that distributes work across your OWN machines and keeps everything private? That kills the business model. No cloud subscription. No data harvesting. No surveillance pipeline. The reason nobody built this is the same reason they do not want you to de-Google your phone: the moment you go local, they lose control.

I built it anyway. Alone. In one week. It is free, open-source, and it works.

You are the Internet Privacy Guy. You have been building the toolkit for digital self-defense piece by piece — de-Googled phones, VPN routers, Brax.Me, HAM radio, Faraday bags. This is the next piece: AI that does not spy on you. Your audience has been waiting for this without knowing it existed.

I made two short animated videos that explain the whole system visually:

Private Mode — AI that never lets data leave your building:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 minutes and 8 seconds)

Public Mode — distributed AI across many machines:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 minutes and 23 seconds)

Full open-source code — every line visible:
https://github.com/strulovitz

Non-technical book explaining the concept:
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

I am not selling anything. This is free. I think your audience needs to know this exists, and you are the only person on YouTube with the technical credibility and the privacy mission to explain why it matters.

With respect,
Nir Strulovitz
Software developer, independent inventor, author of 17 books on science and technology breakthroughs
Email: nir.strulovitz@gmail.com
Mobile: +972-54-475-2626
GitHub: https://github.com/strulovitz
