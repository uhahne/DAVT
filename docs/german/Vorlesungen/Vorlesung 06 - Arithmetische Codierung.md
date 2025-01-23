#### Termin

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

#### Tafelbilder

Encoding 
![[DAVT-06-encode.jpeg]]

Einschub binäre Kommazahlen
![[DAVT-06-binary_floats.jpeg]]

Dekodierung
![[DAVT-06-decode.jpeg]]
#### Erarbeiteter Quellcode
Code mit absoluten Häufigkeiten und End-of-message Zeichen:
[arithmeticCoding.py](../../code/arithmeticCoding.py)

Code mit relativen Häufigkeiten und angegebener Nachrichtenlänge:
[arithmeticCodingProb.py](../../code/arithmeticCodingProb.py)
### Empfehlenswerte Quellen
- [# (IC 5.2) Arithmetic coding - Example #1](https://www.youtube.com/watch?v=7vfqhoJVwuc&list=PLE125425EC837021F&index=43) von [mathematicalmonk](https://www.youtube.com/@mathematicalmonk)
- [Blogartikel und Code von Ahmet Gad, Neptune.ai](https://neptune.ai/blog/lossless-data-compression-using-arithmetic-encoding-in-python-and-its-applications-in-deep-learning)
