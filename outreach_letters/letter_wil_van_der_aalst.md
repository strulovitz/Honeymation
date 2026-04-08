# Letter to Wil van der Aalst (RWTH Aachen, "Godfather of Process Mining")

## Email: wvdaalst@pads.rwth-aachen.de
## Language: German
## Method: Deep research, connect to HIS work, genuine question, invention first

## Subject Line

Ihr Vortrag auf der ICPM 2026 über „Object-Centric Process Mining" — ich habe ein verteiltes KI-System gebaut, das bei jeder Aufgabe Ereignisprotokolle erzeugt: welcher Arbeiter, welche Teilaufgabe, wie lange, welches Ergebnis. Können Sie mein System von innen röntgen?

## Full Letter

Professor van der Aalst,

Sie sagen, dass traditionelles Process Mining ein 2D-Röntgenbild ist, während „Object-Centric Process Mining" ein 3D-MRT liefert. Ich habe ein System gebaut, das genau die Art von mehrschichtigen, multi-objektigen Prozessen erzeugt, die Ihr OCPM-Ansatz analysieren soll — und ich weiß nicht, ob meine Prozesse gesund oder krank sind. Ich brauche Ihren MRT.

Ich habe ein „verteiltes System" (Verteiltes System) gebaut, in dem mehrere Computer, jeder mit seinem eigenen vollständigen „Large Language Model" (Large Language Model), gleichzeitig an verschiedenen Teilen derselben Aufgabe arbeiten. Ein Koordinatormodell — wir nennen es die „Bienenkönigin" — empfängt die Aufgabe, zerlegt sie in unabhängige Teilaufgaben und sendet jede Teilaufgabe an eine andere Maschine im „Local Area Network" (Local Area Network). Jede Maschine bearbeitet ihre Teilaufgabe völlig unabhängig. Wenn alle fertig sind, kombiniert die Bienenkönigin die Ergebnisse. Keine Daten verlassen jemals das Gebäude.

Stellen Sie es sich vor wie „BitTorrent" (BitTorrent), aber statt Teile einer Datei herunterzuladen, löst jede Maschine unabhängig ein Stück eines KI-Problems.

Das System skaliert über hierarchische „Bienenstöcke" — eine Mega-Bienenkönigin delegiert an Unter-Bienenköniginnen, die an ihre eigenen Arbeiter delegieren. Mehr Ebenen, mehr Maschinen, unbegrenzte Komplexität.

Hier ist, warum Ihre Arbeit mich nicht loslässt:

Bei jeder Aufgabe erzeugt mein System genau die Art von Ereignisprotokollen, die Process Mining als Input braucht: Welcher Arbeiter hat welche Teilaufgabe erhalten. Wann hat er angefangen, wann hat er aufgehört. Wie lange hat jede Teilaufgabe gedauert. Welches Ergebnis hat er geliefert. Wie lange hat die Bienenkönigin für die Zerlegung gebraucht. Wie lange hat die Kombination der Ergebnisse gedauert. In einem hierarchischen System kommen weitere Objekttypen hinzu: Mega-Bienenkönigin, Unter-Bienenköniginnen, Arbeiter, Aufgaben, Teilaufgaben, Ergebnisse — genau die Art von Multi-Objekt-Interaktion, die Ihr OCPM modelliert.

Aber hier ist mein Problem: Ich habe keinen „treuen digitalen Zwilling" meines eigenen Systems. Ich sehe die Eingabe (die Aufgabe) und die Ausgabe (das kombinierte Ergebnis), aber ich sehe NICHT, ob die Bienenkönigin die Aufgabe OPTIMAL zerlegt hat. Vielleicht hat sie eine Teilaufgabe einem langsamen Arbeiter gegeben, während ein schneller Arbeiter untätig war. Vielleicht hat sie die Aufgabe in fünf Teile zerlegt, wo drei besser gewesen wären. Vielleicht hat ein Arbeiter doppelt so lange gebraucht wie die anderen — ist er langsamer, oder war seine Teilaufgabe schwieriger?

Sie haben in Ihrem jüngsten Werk betont, dass GenAI ohne Process Mining dazu neigt, „halluzinierte" Prozessautomatisierungen zu erzeugen. Meine Bienenkönigin IST ein GenAI-Modell, das Prozessentscheidungen trifft — sie zerlegt Aufgaben, weist Arbeiter zu, kombiniert Ergebnisse. Ohne Process Mining weiß ich nicht, ob sie halluziniert oder optimiert.

Meine Frage an Sie: Wenn Sie die Ereignisprotokolle meines Systems in Ihrem OCPM-Rahmenwerk analysieren würden — mit den Objekttypen Bienenkönigin, Arbeiter, Aufgabe, Teilaufgabe, Ergebnis und ihren Interaktionen — welche Art von Engpässen, Anomalien oder Optimierungsmöglichkeiten würden Sie erwarten zu finden? Und halten Sie es für möglich, Process-Mining-Erkenntnisse direkt an die Bienenkönigin zurückzufüttern, sodass sie ihre Zerlegungsstrategie automatisch verbessert — eine Art selbstoptimierender KI-Prozess?

Ich stelle diese Frage, weil die Antwort bestimmt, ob mein System sich verbessern kann, ohne dass ich den Code jedes Mal manuell anpasse. Und als Begründer des Process Mining und Chief Scientist bei Celonis, der genau diese Brücke zwischen akademischer Theorie und industrieller Praxis baut, sind Sie die richtige Person, um das zu beurteilen.

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

Mit freundlichen Grüßen,
Nir Strulovitz
Softwareentwickler
E-Mail: nir.strulovitz@gmail.com
Mobil: +972-54-475-2626
GitHub: https://github.com/strulovitz
