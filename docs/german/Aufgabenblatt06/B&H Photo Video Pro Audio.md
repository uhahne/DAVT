B&H Photo Video Pro Audio auf YouTube: [How to Understand Codecs](https://www.youtube.com/watch?v=sisvOeZItb0&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=19)

Ergebnis von Uwe Hahne:

### Aufgaben

#### Summarize the video

- Processing chain from video capture with a camera via editing to watching

![alt text](DAVT-A06-overview.png)

- Each step needs different codecs

- Codec as Compressor, Decompressor

- Capture: Max quality

- Bit depth: get as many colors as possible

- Chroma sub-sampling

- Edit codecs

- Intraframe vs interframe

- Intraframe: subdivide into sections

- Interframe: save only differences between frames --> Problem with interframe, when searching for single frames

- Huge files: use proxies with lower resolution for editing

- Watch codecs

- Choose appropriate BitRate depending on the application

- single pass vs multi-pass

  

##### About the authors

  

B&H is not a big box store, or a faceless chain... or a personality-free zone. B&H is a group of people who are passionate about the things you're passionate about—from photography, film, music and audio to art and technology, creating and imagining. We love what we do. We are both professional and avid photographers, filmmakers, and audio professionals. We enjoy getting out to explore the world as creators and teachers. On our channel, you’ll see videos, podcasts, and tutorials showing this passion for craft, as well as other artists that love what they do as much as we do. (from www.bhphotovideo.com resp their YouTube channel description)

  

They want to sell cameras etc.

  

#### Aufgabe 1: Grundlagen der verlustbehafteten Kompression

  

1. Wie wurde in ihrer Quelle verlustbehaftete Kompression definiert? Wie unterscheidet sie sich von verlustfreier Kompression?

- Es wurde nur auf die Qualität des Videos eingegangen und unterschiedliche Anwendungen im Verarbeitungsprozess betrachtet: Aufnahme, Bearbeitung, Anschauen

- Jeder dieser Schritte hat unterschiedliche Anforderungen, aber alle benötigen eine Reduktion der Datenmenge

2. Benennen Sie die in der Quelle genannten Anwendungsbereiche und warum verlustbehaftete Kompression in diesen Bereichen häufig genutzt wird.

- Es geht nur um Video und es wird auch nur die Kompression der Bilder angesprochen. Audio wird nicht erwähnt. Vermutlich, weil die Datenmenge für Rohbilder deutlich größer ist, als für Audiodaten und daher dort die Kompression wichtiger ist.

  

---

  

#### Aufgabe 2: Techniken und Prinzipien

  

1. Welche grundlegenden Techniken (die aus der bisherigen Vorlesung bekannt sind) nennt ihre Quelle, die bei der verlustbehafteten Kompression eingesetzt werden?

- eigentlich keine, nur dass man mit mehr Bits, mehr Farben speichern kann

- Anmerkung: wenn ich es richtig erkenne, kann man im YouTube Video keinen Unterschied zwischen 12 Bit und 8 Bit Farbe sehen, weil man ja ein komprimiertes YouTube Video sieht.

2. Nennen Sie weitere wichtige, genannte Begriffe aus dem Kontext der Kompression.

- Bit depth + Bit rate

- Intraframe vs interframe

  

---

  

#### Aufgabe 3: Auswirkungen auf die Medienqualität

  

1. Welche Auswirkungen hat verlustbehaftete Kompression auf die Qualität?

- im Idealfall keine. Aber man ist beim Streaming von Videos in der Bandbreite (BitRate) begrenzt und muss daher zwischen Datenmenge und Qualität anhand der BitRate balancieren.

2. Welche Beispiele für Artefakte, die durch Kompression entstehen können, werden in der Quelle genannt?

- keine.

  

---

  

#### Aufgabe 4: Vor- und Nachteile

  

1. Welche Vor- und Nachteile der verlustbehafteten Kompression werden in der Quelle genannt?

- man sollte je nach Anwendung, einen passenden Codec auswählen

2. Diskutieren Sie diese Vor- und Nachteile in Bezug auf ihre Relevanz und unterschiedliche Einsatzgebiete.

- es ist sehr wichtig, den Codec an die Tätigkeit anzupassen. Beim Speichern von Differenzbildern kann man nicht einfach von einem Frame zum anderen hin und her wechseln, sondern muss immer erst zum letzten Keyframe zurück und von dort über die Differenzen zum gewünschten Frame.

  

---

  

#### Aufgabe 5: Reflexion und Transfer

  

1. Reflektieren Sie: In welchen Szenarien ist ein Qualitätsverlust akzeptabel? In welchen nicht?

- bei der Aufnahme sollte keine Qualität verloren gehen, beim Editieren ist man durch die Rechenkapazität und den Speicher eingeschränkt.

- beim Anschauen hängt es vom Abspielgerät ab (Streaming: Bandbreite)

2. Überlegen Sie, wie zukünftige Technologien den Balanceakt zwischen Qualität und Kompressionsrate verbessern könnten.

- Man könnte unter Umständen KI Modelle trainieren, die es ermöglichen die optimale Bitrate oder Kompressionsrate vorherzusagen, da sie auf Basis von sehr vielen Videos trainiert wurden. Aber ein solches Modell müsste dann immer kleiner sein, als das eigentliche Video.

3. Bewerten Sie inwiefern ihre Quelle bei der Beantwortung dieser Fragen hilfreich ist.

- nur bedingt, aber es wird sehr gut der Aspekt der unterschiedlichen Anwendungen: Aufnahme, Bearbeitung, Wiedergabe dargestellt und es werden die damit einhergehenden Anforderungen erläutert.

- man muss in Betracht ziehen, dass es ein Unternehmen ist, welches Kameras verkaufen möchte. Daher geht es nicht so sehr in die Tiefe, sondern es wird sich auf die Sicht des Anwenders konzentriert.