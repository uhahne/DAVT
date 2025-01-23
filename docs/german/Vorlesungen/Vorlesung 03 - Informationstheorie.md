#### Termin

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

