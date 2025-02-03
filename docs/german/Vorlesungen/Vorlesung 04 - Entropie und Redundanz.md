## Vierter Termin

Mittwoch, 23.10.2024 in Raum L2.05a
### Ziele

- Entropie und Redundanz verstehen
- Anwendung der Informationstheorie: Kompression und Fehlerkorrektur

### Drehbuch

| Was                                                      | Dauer  | Material                                   |
| -------------------------------------------------------- | ------ | ------------------------------------------ |
| Wiederholung und Ergänzung Entropie                      | 5 min  | [[DAVT-03-Information.pdf]] Folien 12 - 15 |
| Übungsaufgaben 1 + 2                                     | 25 min | [[DAVT-Aufgabenblatt03.pdf]]               |
| Informationstheorie: Was bedeutet Redundanz? Anwendungen | 30 min | [[DAVT-03-Information.pdf]] Folien 16ff    |
| Übungsaufgaben 3 + 4                                     | 30 min | [[DAVT-Aufgabenblatt03.pdf]]               |
|                                                          |        |                                            |

### Ergebnisse

Wir haben das [Shannon-Weaver Modell](https://en.wikipedia.org/wiki/Shannon%E2%80%93Weaver_model) eingeführt und betrachten die praktischen Anwendungen im Bereich der AV-Technik im Folgenden anhand des Modells.

![[Sender-Empfänger-Modell_nach_Shannon_und_Weaver.jpg]]

Es gibt im wesentlichen zwei Herausforderungen für die Kodierung von Signalen:

| *Herausforderung* | **Kompression**                                                                                                                                                    | **Fehlerkorrektur**                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Wikipedia         | [Datenkompression](https://de.wikipedia.org/wiki/Datenkompression)                                                                                                 | [Fehlerkorrekturverfahren](https://de.wikipedia.org/wiki/Fehlerkorrekturverfahren) |
| Ziel              | Effizienz                                                                                                                                                          | Verlässlichkeit                                                                    |
| *Theorien*        | [Shannons Quellencodierungssatz](https://en.wikipedia.org/wiki/Shannon%27s_source_coding_theorem) (verlustfrei)                                                    | [Kanalcodierung](https://de.wikipedia.org/wiki/Kanalkodierung)                     |
|                   | [Rate-Distortion-Theorie](https://de.wikipedia.org/wiki/Rate-Distortion-Theorie) (verlustbehaftet)                                                                 | [Kanalkapazität](https://de.wikipedia.org/wiki/Kanalkapazit%C3%A4t)                |
| *Algorithmen*     | [Huffman-Code](https://de.wikipedia.org/wiki/Huffman-Kodierung)                                                                                                    | [Hamming Code](https://de.wikipedia.org/wiki/Hamming-Code)                         |
|                   | [Arithmetische Codierung](https://de.wikipedia.org/wiki/Arithmetisches_Kodieren), [CABAC](https://de.wikipedia.org/wiki/Context-Adaptive_Binary_Arithmetic_Coding) | [Reed-Solomon Code](https://de.wikipedia.org/wiki/Reed-Solomon-Code)               |
|                   | [Lempel-Ziv-Welch](https://de.wikipedia.org/wiki/Lempel-Ziv-Welch-Algorithmus)                                                                                     | [Turbo-Code](https://de.wikipedia.org/wiki/Turbo-Code)                             |
| *Praxis*          | Bilder: JPEG, GIF                                                                                                                                                  |                                                                                    |
|                   | Video: MPEG-AVC/H.264, H.265, AV1                                                                                                                                  | DVB                                                                                |
|                   | Audio: mp3, aac                                                                                                                                                    | GSM                                                                                |

#### Aufgabe 01 

Wurde von allen Teilnehmenden einzeln bearbeitet. 

![[DAVT-04-Aufgabe01.jpeg]]

"Es schneit in Dubai." enthält am meisten Information, da es am unwahrscheinlichsten ist. "In Los Angeles scheint die Sonne." gilt eigentlich fast immer oder zumindest häufiger als "Es regnet in Furtwangen." und ist daher auf dem letzten Platz, weil es den geringsten Informationsgehalt hat.

#### Aufgabe 02

Wurde nur von einer Person erfolgreich berechnet und dann an der Tafel vorgestellt.

![[DAVT-04-Aufgabe02.jpeg]]

Zuerst wurde die Wahrscheinlichkeit der einzelnen Zeichen anhand ihrer relativen Häufigkeit ermittelt (links). Dann die Formel mit diesen Werten berechnet. Durch Umstellen der Brüche $1/2 = 1/2^1 = 2^-1$  ergibt sich der Logarithmus sehr einfach da $log_2(2^a)=a$ gilt.
Das Ausmultiplizieren und Addieren führt dann zur Lösung 1,75 Bit.

#### Aufgabe 03

Zur Einführung wurde kurz wiederholt was ein Binärbaum ist und wie man ihn im Kontext der Binärcodierung verwendet.

![[DAVT-04-BeispieBinärbaum.jpeg]]

Der Pfad durchläuft die Knoten bis zum Blatt welches das zu codierende Zeichen enthält. Der Binärcode ergibt sich aus den Ästen (links 1, rechts 0 oder andersrum).

Nach diesem Beispiel wurde dann eine erste Lösung erzeugt:

![[DAVT-04-Aufgabe03_Lsg01.jpeg]]

Dieser balancierte Baum führt zu einer Codierung mit einheitlicher Codelänge für jedes Zeichen. Man benötigt also 2 Bit pro Zeichen.

#### Aufgabe 04

Um auf eine Lösung mit reduzierter mittlerer Codelänge zu kommen, wurde der Baum anhand der Häufigkeiten der Buchstaben umgestellt.

![[DAVT-04-Aufgabe03u04.jpeg]]

In diese Codierung wird für das A nur ein Bit verwendet. Durch seine erhöhte Häufigkeit kann die zweite Nachricht daher im Mittel mit 1,75 Bit pro Zeichen dargestellt werden und man hat damit einen optimalen Code erzeugt.

In der nächsten Vorlesung wird dann ein Algorithmus gesucht, der immer den optimalen Code erzeugt.

### Was man verstanden haben sollte
- Ich habe den Zusammenhang zwischen Informationsgehalt und Wahrscheinlichkeit des Auftretens eines Zeichens verstanden.
- Ich bin in der Lage die Entropie einer Nachricht zu berechnen.
- Ich kann eine Nachricht kodieren, weil ich verstanden habe was mit Codierung gemeint ist.