# Letter to Bernhard Schölkopf (MPI-IS Tübingen, #1 AI researcher in Germany)

## Email: bernhard.schoelkopf@tuebingen.mpg.de
## Language: German
## Method: Deep research, connect to HIS work, genuine question, invention first
## Angle: Worker trust evaluation — WHY does a worker disagree? Causal inference for Byzantine Generals.

## Subject Line

Das „Problem der byzantinischen Generäle" (Byzantine fault) in meinem verteilten KI-System — wenn ein Arbeiter anders antwortet als die anderen, ist er defekt, bösartig, oder tatsächlich der Klügste? Ihre kausale Inferenz könnte die Antwort sein.

## Full Letter

Professor Schölkopf,

Sie sagen oft, dass KI aufhören muss, Kurven anzupassen, und anfangen muss, kausale Mechanismen zu verstehen. Ich habe ein konkretes technisches Problem, bei dem genau diese Einsicht den Unterschied ausmacht — und ich weiß nicht, wie ich es ohne Ihren Ansatz lösen kann.

Ich habe ein „verteiltes System" (Verteiltes System) gebaut, in dem mehrere Computer, jeder mit seinem eigenen vollständigen „Large Language Model" (Large Language Model), gleichzeitig an verschiedenen Teilen derselben Aufgabe arbeiten. Ein Koordinatormodell — wir nennen es die „Bienenkönigin" — empfängt die Aufgabe, zerlegt sie in unabhängige Teilaufgaben und sendet jede Teilaufgabe an eine andere Maschine im „Local Area Network" (Local Area Network). Jede Maschine bearbeitet ihre Teilaufgabe völlig unabhängig. Null Kommunikation zwischen den Maschinen. Wenn alle fertig sind, kombiniert der Koordinator die Ergebnisse. Keine Daten verlassen jemals das Gebäude.

Dies ist ein echtes „Multiagentensystem" (Multiagentensystem) — nicht CrewAI oder AutoGen, wo Agenten auf einer einzigen Maschine abwechselnd laufen. Stellen Sie es sich vor wie „BitTorrent" (BitTorrent), aber statt Teile einer Datei herunterzuladen, löst jede Maschine unabhängig ein Stück eines KI-Problems.

Das System funktioniert. Es ist „Open-Source-Software" (Open-Source-Software), vollständig dokumentiert, und auf GitHub verfügbar. In Kapitel 5 meines Buches und im Quellcode (queen_bee.py) beschreibe ich ein konkretes ungelöstes Problem — ein geplantes zukünftiges Feature —, bei dem ich Ihren Rat brauche.

Hier ist das Problem:

In einem öffentlichen Netzwerk, wo fremde Maschinen als Arbeiter beitreten können, muss die Bienenkönigin automatisch erkennen, ob ein Arbeiter vertrauenswürdig ist. Ein Ansatz ist das „Problem der byzantinischen Generäle" (Byzantine fault): Die Bienenkönigin gibt dieselbe kleine Aufgabe an drei Arbeiter. Wenn zwei die gleiche Antwort geben und der dritte eine andere, wird der dritte als defekt oder bösartig eingestuft und ausgeschlossen.

Aber das ist naiv. Und hier kommt Ihre Arbeit ins Spiel.

Stellen Sie sich vor: Zwei Arbeiter laufen mit einem älteren Modell und antworten „Paris ist die Hauptstadt von Frankreich." Der dritte Arbeiter hat ein neueres, besseres Modell und antwortet: „Paris ist die Hauptstadt, aber seit der Verwaltungsreform 2025 werden zunehmend Funktionen nach Lyon und Marseille dezentralisiert." Die naive byzantinische Logik sagt: Zwei stimmen überein, einer weicht ab — der dritte ist schlecht. Aber in Wirklichkeit ist er der BESTE. Er hat neuere Informationen. Ihn auszuschließen wäre ein schwerer Fehler.

Das Problem: Abweichung hat mehrere mögliche URSACHEN.
- Ursache A: Der Arbeiter ist defekt oder bösartig → ausschließen.
- Ursache B: Der Arbeiter hat ein neueres oder besseres Modell → behalten, er ist möglicherweise der wertvollste.
- Ursache C: Der Arbeiter hat die Frage anders interpretiert → nicht defekt, nur eine andere Perspektive.

Ein dummes System sieht den EFFEKT (Abweichung) und bestraft den Ausreißer. Genau das, was Sie Ihr ganzes Berufsleben lang kritisieren — Kurvenanpassung statt kausales Verständnis. Die nasse Straße korreliert mit Regenschirmen, aber die nasse Straße VERURSACHT keine Regenschirme.

Ihre Hypothese des „Sparse Mechanism Shift" — dass Veränderungen typischerweise nur wenige lokale kausale Mechanismen betreffen — scheint direkt anwendbar: Die Abweichung des dritten Arbeiters betrifft nur EINEN Mechanismus (neuere Trainingsdaten), während alle anderen Mechanismen (Sprachverständnis, Logik, Formatierung) identisch funktionieren. Ein kausales Modell könnte die URSACHE der Abweichung isolieren, anstatt nur die Abweichung selbst zu bestrafen.

Meine Frage an Sie: Könnte Ihr Rahmenwerk der kausalen Repräsentationslernung — insbesondere die Methoden aus Ihrem Papier über „Causal Foundation Models" — dazu verwendet werden, der Bienenkönigin beizubringen, nicht nur ZU ERKENNEN, dass ein Arbeiter abweicht, sondern WARUM er abweicht? Und wenn ja — wie würden Sie die kausalen Variablen definieren, die die Bienenkönigin untersuchen sollte, um zwischen einem defekten Arbeiter, einem bösartigen Arbeiter und einem besseren Arbeiter zu unterscheiden?

Ich stelle diese Frage, weil ich ehrlich nicht weiß, ob kausale Inferenz der richtige Ansatz für dieses Problem ist, oder ob es einen besseren gibt. Und als Gründer von Cyber Valley und wissenschaftlicher Direktor des ELLIS-Instituts Tübingen sind Sie einer der wenigen Menschen weltweit, die sowohl die theoretische Tiefe in kausaler Inferenz als auch die praktische Erfahrung mit großen ML-Systemen haben, um das zu beurteilen.

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
