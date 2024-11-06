## Erster Termin

Mittwoch, 02.10.2024 in Raum L2.05a
### Ziele

- Übersicht bekommen, was die Themen des Kurses sind.
- Klarheit, wie im Kurs gearbeitet werden soll.

### Drehbuch

| Was                         | Dauer  | Material                     |
| --------------------------- | ------ | ---------------------------- |
| Begrüßung und Vorstellung   | 15 min | [[DAVT-01-Introduction.pdf]] |
| Inhaltsübersicht            | 5 min  | [[DAVT-01-Introduction.pdf]] |
| Aufgabenblatt 01 - Mind map | 70 min | [[DAVT-Aufgabenblatt01.pdf]] |

### Ergebnisse
#### Mindmaps
![[DAVT-01-Mindmaps01.jpeg]]
![[DAVT-01-Mindmaps02.jpeg]]
![[DAVT-01-Mindmaps03.jpeg]]
![[DAVT-01-Mindmaps04.jpeg]]
#### Interessantesten Themen
Mehrfach genannt:

- Streaming von Audio und Video (Spotify, Netflix)

- KI (Künstliche Intelligenz) z.B. Spracherkennung, generative KI Modelle

- XR (Xtended Reality, also VR und AR, auch wie VR Brillen funktionieren)

- VFX/SFX (also Special Effects in Video und Audio)

- Zusammenhang/Grundlagen der Kommunikation, Codecs, Signale, Schnittstellen usw.

	- Kompression und Datenübertragung

Einzelnennungen:

- Kameras, Lautsprecher, Adapter, Spiele, Akustik, Social Media, 

#### Fazit
Es sind Grundkenntnisse aus den Video- und Audiotechnik Vorlesungen vorhanden, die weniger wiederholt, sondern mehr vertieft werden sollen. Streaminganwendungen finden ein großes Interesse und auch die Methoden der künstlichen Intelligenz, sowie XR Technologien.
Special effects (VFX/SFX) sind weniger Teil dieser Vorlesung, aber Interesse ist da und mögliche Verbindungen werden aufgezeigt.

## Zweiter Termin

Mittwoch, 09.10.2024 in Raum L2.05a
### Ziele

- Historische Übersicht zur Digitaltechnologie
- Grundbegriffe klären: [[system]], [[signal]], Kommunikation, Nachricht, Codierung, ...

### Drehbuch

| Was                          | Dauer  | Material                                                                                                                                                          |
| ---------------------------- | ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Impulsvortrag zu Systemen    | 20 min | [[DAVT-02-SignaleSysteme.pdf]]                                                                                                                                    |
| Höraufgabe                   | 20 min | Es wird eine [Tonaufnahme](https://einstein-website.de/tondokument/) abgespielt und wir versuchen den Informationsfluss so detailliert wie möglich aufzuzeichnen. |
| Impulsvortrag zu Signalen    | 20 min | [[DAVT-02-SignaleSysteme.pdf]]                                                                                                                                    |
| Textaufgabe                  | 20 min | [[DAVT-Aufgabenblatt02.pdf]]                                                                                                                                      |
| Signalfunktionen und Wrap-Up | 10 min | [[DAVT-02-SignaleSysteme.pdf]]                                                                                                                                    |

### Ergebnisse

nur bis zur Textaufgabe gekommen...

#### Tafelbild zur Höraufgabe

![[DAVT-02-SystemEinstein.jpeg]]
Von Einsteins Sprache über ein Mikrofon zur Tonbandaufnahme

Spätere Rundfunkaustrahlung entweder terrestrisch (T), per Kabel (C) oder per Satellit (S).

#### Tafelbild Signale

Eine Funktion:

![[DAVT-02-Function.jpeg]]

Ein diskretes Signal als Schaubild:

![[DAVT-02-DiskretesSignal.jpeg]]

*Immer darauf achten, dass die Zwischenwerte Sinn ergeben. In diesem Beispiel tun sie es nicht!*

#### Ergebnisse vom Aufgabenblatt 02

Unbekannte Begriffe:

- [ ] multiplexing

	- muss noch genauer geklärt werden, wenn es zum Thema Modulation kommt.

- [x] digital filtering

	- Digitale Filter sind aus GDV bekannt, wir gehen aber auch nochmals drauf ein.

- [x] speech synthesis

	- Sprachsynthese, also das Erzeugen von künstlicher Sprache (Bsp. Siri, Alexa, Bahnhofsansagen, ...)

- [x] Fast Fourier Transform algorithm

	- ein sehr schneller Algorithmus zur Berechnung einer Fouriertransformation, kommt auch später nochmal im Detail und wo er eingesetzt wird.

Schätzungen zum Erscheinungsjahr des Texts:

![[DAVT-02-YearGuesses.jpeg]]

Im Schnitt ungefähr 2002 --> Ursprung des Texts: [Alan Oppenheim (MIT) Lecture on digital signal processing from 1975](https://youtu.be/rkvEM5Y3N60?feature=shared&t=59)

## Dritter Termin

Mittwoch, 16.10.2024 in Raum L2.05a
### Ziele

- Signale als Funktionen
- Informationstheorie: Was ist ein Bit?

### Drehbuch

| Was                                    | Dauer  | Material                                                                                                                |
| -------------------------------------- | ------ | ----------------------------------------------------------------------------------------------------------------------- |
| Signale als Funktionen                 | 10 min | [[DAVT-02-SignaleSysteme.pdf]]                                                                                          |
| Hörbeispiel                            | 10 min | [MIT lecture](https://ocw.mit.edu/courses/6-003-signals-and-systems-fall-2011/resources/lecture-1-signals-and-systems/) |
| Informationstheorie: Was ist ein Bit?  | 60 min | [[DAVT-03-Information.pdf]] bis Folie 10                                                                                |
| Informationstheorie: Was ist Entropie? | 10 min | [[DAVT-03-Information.pdf]] Folien 11-15                                                                                |

### Ergebnisse

#### Signale als Funktionen
![[DAVT-03-signalFunction.jpeg]]

Zur Erinnerung: Audiosignale sind Wellenfunktionen, die eine Amplitude und eine Frequenz haben. Die Amplitude entspricht der Lautstärke, die Frequenz der Tonhöhe. Daher klingen schneller abgespielte Töne höher.

#### Hörbeispiel aus MIT Vorlesung
Start bei Minute 33:00. Es wird den Studierenden immer 30 Sekunden Zeit gelassen zu diskutieren und zu überlegen. 
Ergebnisse bei uns mit obigem Tafelbild erklärt.

#### Informationstheorie
Als Beispiel das folgende Szenario:
Man möchte eine Bahnreise unternehmen und weiß nicht wann und wo der Zug fährt. Es gibt 8 Gleise und 8 Zeitslots (Stunden) in denen der Zug abfahren könnte. Wie viele Bit an Informationen benötige ich um das richtige Gleis zur richtigen Zeit zu finden?

![[DAVT-03-bitsTrain.jpeg]]

Links die geratenen Werte der Teilnehmenden
Rechts die Herleitung durch geschickte Fragestellungen, die den Lösungsraum jeweils halbieren.
Links von der Mitte noch ein Beispiel mit 10 Möglichkeiten und der Diskussion ob 3 oder 4 Bits notwendig sind.

##### Herleitung der Formel
![[DAVT-03-calculateBit.jpeg]]
Der Informationsgehalt eines einzelnen Zeichens ergibt sich aus dem negativen, dualen Logarithmus der Wahrscheinlichkeit seines Auftretens.

#### Entropie
Vergleich zur Thermodynamik angesprochen, Details siehe [hier](https://de.wikipedia.org/wiki/Zweiter_Hauptsatz_der_Thermodynamik#Entropie)

Code zur Berechnung der Entropie einer Nachricht:

> [!NOTE] entropy.py
> ```python
> 	import math
> 	
> 	# the message
> 	message = 'AAAAAAAA' # compute the proportion of each sign in the message
> 	
> 	def get_prop(message, sign ):
> 		return message.count(sign) / len(message)
> 		
> 	# get the proportion of each sign in the message
> 	pA = get_prop(message, 'A')
> 	pB = get_prop(message, 'B')
> 	pC = get_prop(message, 'C')
> 	pD = get_prop(message, 'D')
> 	
> 	print() # empty line
> 	print('Probabilities:')
> 	print(pA, pB, pC, pD)
> 	print() # empty line
> 	
> 	# compute the entropy
> 	H = -pA * math.log2(pA) - pB * math.log2(pB) - pC * math.log2(pC) - pD * math.log2(pD)
> 	
> 	print() # empty line
> 	print('Entropy:')
> 	print(H)
> 	print() # empty lineContents
> ```
> 



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

## Fünfter Termin

Mittwoch, 30.10.2024 in Raum L2.05a
### Ziele

- Algorithmus zur Erzeugung optimaler Binärcodes


### Drehbuch

| Was                                          | Dauer  | Material                               |
| -------------------------------------------- | ------ | -------------------------------------- |
| Fano-Shannon Algorithmus mit Implementierung | 30 min | [[DAVT-04-Codierung.pdf]] bis Folie 16 |
| Huffman Code mit Implementierung             | 25 min | [[DAVT-04-Codierung.pdf]] Folien 17-23 |
| Encoding und Decoding                        | 10 min | [[DAVT-04-Codierung.pdf]] Folie 24-28  |
| Codierung des Huffman Baums                  | 10 min | [[DAVT-04-Codierung.pdf]] ab Folie 29  |
| Üben des Gelernten                           | 15 min | [[DAVT-Aufgabenblatt04.pdf]]           |

#### Erarbeiteter Quellcode

Shannon-Fano Coding:
[fano.py](../../code/fano.py)

Huffman Coding:
[huffman.py](../../code/huffman.py)


## Sechster Termin

Mittwoch, 6.11.2024 in Raum L2.05a
### Ziele

- Arithmetische Codierung verstehen


### Drehbuch
| Was                                                              | Dauer  | Material                                                    |
| ---------------------------------------------------------------- | ------ | ----------------------------------------------------------- |
| Arithmetische Codierung - Grundprinzip und Beispiel für Encoding | 30 min | [[DAVT-05-ArithmetischeCodierung.pdf]] bis Folie 16         |
| Einschub binäre Bruchzahlen                                      | 5 min  | ![[decimal_binary.png]]                                     |
| Arithmetische Codierung - Decoding                               | 20 min | [[DAVT-05-ArithmetischeCodierung.pdf]] bis Folie 21         |
| Arithmetische Codierung - Implementierung                        | 20 min | [[DAVT-05-ArithmetischeCodierung.pdf]] bis Ende, sowie Code |
| Üben des Gelernten                                               | 15 min | [[DAVT-Aufgabenblatt05.pdf]]                                |

#### Erarbeiteter Quellcode
Code mit absoluten Häufigkeiten und End-of-message Zeichen:
[arithmeticCoding.py](../../code/arithmeticCoding.py)

Code mit relativen Häufigkeiten und angegebener Nachrichtenlänge:
[arithmeticCodingProb.py](../../code/arithmeticCodingProb.py)
### Empfehlenswerte Quellen
- [# (IC 5.2) Arithmetic coding - Example #1](https://www.youtube.com/watch?v=7vfqhoJVwuc&list=PLE125425EC837021F&index=43) von [mathematicalmonk](https://www.youtube.com/@mathematicalmonk)
- [Blogartikel und Code von Ahmet Gad, Neptune.ai](https://neptune.ai/blog/lossless-data-compression-using-arithmetic-encoding-in-python-and-its-applications-in-deep-learning)