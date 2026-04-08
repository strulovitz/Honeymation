# Letter to Wil van der Aalst (RWTH Aachen, "Godfather of Process Mining")

## Email: wvdaalst@pads.rwth-aachen.de
## Language: German
## Method: Deep research, connect to HIS work, genuine question, invention first
## Angle: Vibe coding flywheel — AI reads logs, writes code, generates more logs. Can process mining verify vibe-coded software? New application for his field.

## Subject Line

„Vibe Coding" hat ein ernstes Vertrauensproblem — die KI liest ihre eigenen Protokolle, schreibt Code, der neue Protokolle erzeugt, und überprüft sich selbst. „Process Mining" könnte die einzige unabhängige Kontrollinstanz sein. Ich habe den Beweis.

## Full Letter

Professor van der Aalst,

Sie haben Ihr ganzes Berufsleben damit verbracht, eine fundamentale Einsicht zu verteidigen: Man kann einem Prozess nicht vertrauen, indem man die Beteiligten fragt, wie er funktioniert — man muss die Daten selbst analysieren. Die Menschen beschreiben den Prozess, wie er sein SOLLTE. Die Protokolle zeigen, wie er WIRKLICH ist. Diese Einsicht ist gerade relevanter als je zuvor — und zwar in einem Kontext, an den Sie vermutlich noch nicht gedacht haben.

Ich habe eines der ambitioniertesten Softwareprojekte gebaut, die jemals durch „Vibe Coding" entstanden sind — der Praxis, bei der ein Mensch einem KI-Modell beschreibt, was er will, und die KI den gesamten Code schreibt. Das Ergebnis ist ein voll funktionsfähiges verteiltes KI-System: Mehrere Computer, jeder mit seinem eigenen vollständigen „Large Language Model" (Large Language Model), arbeiten gleichzeitig an verschiedenen Teilen derselben Aufgabe. Ein Koordinatormodell — die „Bienenkönigin" — empfängt die Aufgabe, zerlegt sie in unabhängige Teilaufgaben und sendet jede an eine andere Maschine im „Local Area Network" (Local Area Network). Jede Maschine bearbeitet ihre Teilaufgabe völlig unabhängig. Null Kommunikation zwischen den Maschinen. Die Bienenkönigin kombiniert die Ergebnisse. Keine Daten verlassen jemals das Gebäude. „Open-Source-Software" (Open-Source-Software). Kostenlos. Für immer.

Das System skaliert über hierarchische „Bienenstöcke" — eine Mega-Bienenkönigin delegiert an Unter-Bienenköniginnen, die an ihre Arbeiter delegieren. Es gibt eine Webplattform mit Benutzerverwaltung, SMS-Verifizierung, Reputationssystem und Zahlungssystem. Es funktioniert auf Windows, Linux und macOS. Es wurde in sieben Tagen gebaut — vollständig durch Vibe Coding, dokumentiert in einem Buch, das den gesamten Prozess beschreibt.

Warum das für Ihre Arbeit relevant ist — und warum es ein ernstes Problem hat:

Die KI (Claude Opus 4.6 von Anthropic), die diesen Code geschrieben hat, hat während des gesamten Entwicklungsprozesses die Protokolle des Systems gelesen, um Fehler zu finden und zu beheben. Wenn etwas nicht funktionierte, hat die KI die Protokolle analysiert, den Fehler diagnostiziert, neuen Code geschrieben, und dieser neue Code hat neue Protokolle erzeugt — die die KI dann wieder gelesen hat, um den nächsten Fehler zu finden.

Das ist ein Schwungrad: KI liest Protokolle → KI schreibt Code → Code erzeugt Protokolle → KI liest Protokolle → KI schreibt Code...

Sehen Sie das Problem?

Die KI, die die Protokolle interpretiert, ist DIESELBE KI, die den Code geschrieben hat, der die Protokolle erzeugt. Wenn die KI im Code halluziniert hat — einen subtilen Fehler eingebaut hat, der korrekt AUSSIEHT —, dann könnte sie auch in der Protokollanalyse halluzinieren und den Fehler für normal halten. Der Fuchs bewacht den Hühnerstall.

In einem System, das Geld verarbeitet, Benutzer verwaltet und vertrauliche Daten schützt, ist das keine akademische Frage. Das ist ein reales Risiko.

Ihr „Process Mining" basiert auf einem Prinzip, das genau dieses Problem lösen könnte: Die Wahrheit liegt in den Daten, nicht in dem, was die Beteiligten behaupten. In diesem Fall ist der „Beteiligte", der behauptet, dass alles korrekt ist, eine KI. Und die „Daten" sind die Verhaltensmuster im System — nicht der Code selbst, nicht die Protokolle, die die KI liest, sondern die tatsächlichen Ausführungspfade, Zeitmuster, Objektinteraktionen und Anomalien, die nur sichtbar werden, wenn man den Prozess von AUSSEN beobachtet.

Ihr „Object-Centric Process Mining" scheint hier besonders relevant, weil mein System mehrere Objekttypen hat, die miteinander interagieren: Bienenköniginnen, Arbeiter, Aufgaben, Teilaufgaben, Ergebnisse, Benutzer, Zahlungen. Die Interaktionen zwischen diesen Objekttypen sind komplex und genau die Art von Struktur, die Ihr OCPM-Ansatz analysiert.

Meine Frage an Sie: Könnte „Process Mining" als unabhängige Verifikationsschicht für durch Vibe Coding erstellte Software dienen — als dritte Instanz, die weder dem Code noch der KI vertraut, die ihn geschrieben hat, sondern nur den Verhaltensmustern in den Daten? Und wenn ja, welche Art von Anomalien würden Sie in einem solchen System erwarten zu finden, die die KI selbst niemals in ihren eigenen Protokollen sehen würde?

Ich stelle diese Frage aus zwei Gründen. Erstens, weil mein System konkret davon profitieren würde — es verarbeitet echtes Geld und echte Daten, und ich muss wissen, ob der Code, den die KI geschrieben hat, vertrauenswürdig ist. Zweitens, weil „Vibe Coding" gerade explodiert — Millionen von Menschen lassen KI ihre Software schreiben. Wenn „Process Mining" die Methode wird, die solche Software unabhängig verifiziert, dann ist das ein völlig neues Anwendungsgebiet für Ihr Lebenswerk. Und ein riesiger Markt für Celonis.

Sie haben auf der ICPM 2026 argumentiert, dass „Enterprise AI ohne Object-Centric Process Mining nicht erfolgreich sein kann." Ich glaube, das gilt in einem noch tieferen Sinne: Auch die KI, die die Enterprise-Software SCHREIBT, kann ohne Process Mining nicht vertrauenswürdig sein.

Zwei kurze Animationsvideos, die das System erklären:

Privater Modus — die KI, deren Daten niemals Ihr Gebäude verlassen:
https://www.youtube.com/watch?v=o8R58VuJFx8 (3 Minuten und 8 Sekunden)

Öffentlicher Modus — die KI, verteilt auf viele Maschinen:
https://www.youtube.com/watch?v=PTnAqZCAClw (6 Minuten und 23 Sekunden)

Vollständiger offener Quellcode:
https://github.com/strulovitz

Nicht-technisches Buch, das den gesamten Vibe-Coding-Prozess dokumentiert (Kapitel 9: „Vibe Coding: How One Person Built All of This"):
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

Ich bin für Beratung oder Zusammenarbeit verfügbar.

Mit freundlichen Grüßen,
Nir Strulovitz
Softwareentwickler
E-Mail: nir.strulovitz@gmail.com
Mobil: +972-54-475-2626
GitHub: https://github.com/strulovitz
