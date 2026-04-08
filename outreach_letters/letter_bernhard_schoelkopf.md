# Letter to Bernhard Schölkopf (MPI-IS Tübingen, #1 AI researcher in Germany)

## Email: bernhard.schoelkopf@tuebingen.mpg.de
## Language: German
## Method: Deep research, connect to HIS work, genuine question, invention first

## Subject Line

Ihr NeurIPS-2025-Papier über kausales Denken in „Large Language Models" (Large Language Models) — ich habe ein verteiltes System gebaut, in dem mehrere LLMs parallel arbeiten. Die Aufgabenzerlegung IST ein kausales Inferenzproblem. Ich brauche Ihre Hilfe.

## Full Letter

Professor Schölkopf,

Ihr Lebenswerk lässt sich in einem Satz zusammenfassen, den Sie selbst oft wiederholen: KI muss aufhören, Kurven anzupassen, und anfangen, kausale Mechanismen zu verstehen. Ihr NeurIPS-2025-Papier „Causal Discovery and Inference through Next-Token Prediction" hat gezeigt, dass „Large Language Models" tatsächlich interne kausale Repräsentationen entwickeln können. Was mich seither nicht loslässt, ist eine Frage, die sich direkt aus diesem Ergebnis ergibt — eine Frage, die ich alleine nicht beantworten kann.

Ich habe ein „verteiltes System" (Verteiltes System) gebaut, in dem mehrere Computer, jeder mit seinem eigenen vollständigen „Large Language Model", gleichzeitig an verschiedenen Teilen derselben Aufgabe arbeiten — in echtem „Aufgabenparallelismus" (Aufgabenparallelismus). Ein leistungsstärkeres Koordinatormodell empfängt die Aufgabe, zerlegt sie in völlig unabhängige Teilaufgaben und sendet jede Teilaufgabe an eine andere Maschine im „Local Area Network" (Local Area Network). Jede Maschine bearbeitet ihre Teilaufgabe völlig unabhängig. Null Kommunikation zwischen den Maschinen. Wenn alle fertig sind, kombiniert der Koordinator die Ergebnisse. Keine Daten verlassen jemals das Gebäude.

Dies ist ein echtes „Multiagentensystem" (Multiagentensystem) mit echtem „verteiltem Rechnen" (Verteiltes System) — nicht CrewAI oder AutoGen, wo Agenten auf einer einzigen Maschine abwechselnd laufen. Stellen Sie es sich vor wie „BitTorrent" (BitTorrent), aber statt Teile einer Datei herunterzuladen, löst jede Maschine unabhängig ein Stück eines KI-Problems.

Hier ist mein Problem — und hier kommt Ihre Arbeit ins Spiel.

Die kritischste Entscheidung im gesamten System ist die Aufgabenzerlegung: Welche Teilaufgaben sind wirklich unabhängig voneinander und können sicher parallel ausgeführt werden? Welche haben kausale Abhängigkeiten und müssen sequentiell ablaufen? Wenn der Koordinator eine Aufgabe fälschlicherweise in Teilaufgaben zerlegt, die in Wirklichkeit kausal voneinander abhängen, sind die kombinierten Ergebnisse inkonsistent oder falsch.

Das IST ein kausales Inferenzproblem. Genau Ihr Gebiet.

Ihre Hypothese des „Sparse Mechanism Shift" — dass Veränderungen in der Umgebung typischerweise nur wenige lokale kausale Mechanismen betreffen — könnte direkt auf die Aufgabenzerlegung anwendbar sein: Wenn die meisten Teilaufgaben kausal unabhängig sind und nur wenige kausale Verbindungen haben, dann kann der Koordinator die wenigen Abhängigkeiten identifizieren und den Rest sicher parallelisieren. Aber wie formalisiert man das?

Meine Frage an Sie: Könnte Ihr Rahmenwerk der kausalen Repräsentationslernung — insbesondere die Methoden aus Ihrem Papier über „Causal Foundation Models", in dem Sie lernbare Biases in Aufmerksamkeitsmechanismen injizieren — dazu verwendet werden, dem Koordinator-LLM beizubringen, die kausale Struktur einer Aufgabe zu erkennen, BEVOR es sie zerlegt? Und halten Sie es für möglich, dass verteiltes kausales Denken — mehrere LLMs, die jeweils einen anderen kausalen Pfad untersuchen und ihre Schlussfolgerungen zusammenführen — bessere kausale Entdeckungen liefern könnte als ein einzelnes Modell, das alleine arbeitet?

Ich stelle diese Frage, weil ich ehrlich nicht weiß, ob die Antwort ja oder nein ist. Und als Gründer von Cyber Valley und wissenschaftlicher Direktor des ELLIS-Instituts Tübingen sind Sie einer der wenigen Menschen weltweit, die sowohl die theoretische Tiefe in kausaler Inferenz als auch die praktische Erfahrung mit großen ML-Systemen haben, um diese Frage zu beurteilen.

Zwei kurze Animationsvideos, die das System erklären:

Privater Modus — die KI, deren Daten niemals Ihr Gebäude verlassen:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 Minuten und 8 Sekunden)

Öffentlicher Modus — die KI, verteilt auf viele Maschinen:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 Minuten und 23 Sekunden)

Vollständiger offener Quellcode:
https://github.com/strulovitz

Nicht-technisches Buch über das Konzept und zukünftige Richtungen:
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

Ich bin für Beratung oder Zusammenarbeit verfügbar.

Respectfully,
Nir Strulovitz
Softwareentwickler
E-Mail: nir.strulovitz@gmail.com
Mobil: +972-54-475-2626
GitHub: https://github.com/strulovitz
