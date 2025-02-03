
## Grundlagen der verlustbehafteten Kompression – Fragen und Antworten

## Verwendete Quelle  

5. [Lossy compression](https://en.wikipedia.org/wiki/Lossy_compression)

### **Aufgabe 1: Grundlagen der verlustbehafteten Kompression**

1. **Definition und Unterschied zu verlustfreier Kompression:**

- Daten werden reduziert, allerdings irreversible -> geringere Datenmenge, hoher Qualitätsverlust. Anders als verlustfreier Kompression, bei der die Originaldaten vollständig wiederhergestellt werden können, ohne Informationsverlust.

2. **Anwendungsbereiche und Gründe für die Nutzung:**

- audiovisuelle Medien (Bilder, Videos, Audio). Bsp: JPEG für Bilder, MP3 für Audio und H.264 für Video. Wird oft verwendet, da Menschen nicht in der Lage sind geringe Verluste in der Qualität zu sehen.


---

### **Aufgabe 2: Techniken und Prinzipien**

1. **Grundlegende Techniken (von bisheriger Vorlesung):**

- Transformationen (z. B. diskrete Kosinustransformation, DCT)

- Quantisierung

- Entropiekodierung

  

2. **Weitere wichtige Begriffe:**

- _Perceptual Coding:_ Ein Ansatz, der auf den Wahrnehmungsgrenzen des menschlichen Auges oder Ohres basiert, um unwichtige Informationen gezielt zu eliminieren.

- _Bitrate:_ Ein Maß für die Datenmenge pro Sekunde, das bei komprimierten Dateien oft reduziert wird.

- _Lossy Formats:_ Beispiele wie JPEG, MP3 oder MPEG.

  

---

### **Aufgabe 3: Auswirkungen auf die Medienqualität**  

1. **Qualitätsauswirkungen:**

- Es hat immer eine Qualitätsauswirkung, aber sie ist oft nicht für Menschen spürbar. Bei sehr hoher Kompression sieht man aber eine deutliche Verschlechterung

2. **Beispiele für Artefakte:**

- Man sieht in einem Bild Block Artefakte, aber sonst werden keine wirklich genannt.

  

---

### **Aufgabe 4: Vor- und Nachteile**
  
1. **Vor- und Nachteile:**

- **Vorteile:**

- Deutliche Reduzierung der Dateigröße -> mehr Speicherplatz und höhere Übertragungsgeschwindigkeit.

- Effizienzsteigerung in Streaming-Diensten.

- **Nachteile:**

- Der Qualitätsverlust ist irreversibel, und bei starker Kompression können sichtbare Artefakte auftreten.

- Nicht wirklich geeignet für Anwendungen die Präzision oder hohe Qualität erfordern, z. B. medizinische Bildgebung.

2. **Diskussion:**

- In Bereichen wie Musik-Streaming oder Videoübertragung über das Internet ist der Kompromiss zwischen Qualität und Dateigröße entscheidend. Die Vorteile wiegen die Nachteile oft auf, solange die Qualität für den Nutzer akzeptabel bleibt. In der Archivierung, bei Dateien mit hoher Präzision oder bei rechtlich sensiblen Daten ist verlustfreie Kompression jedoch vorzuziehen.

  
---

### **Aufgabe 5: Reflexion und Transfer**

1. **Szenarien für akzeptablen Qualitätsverlust:**

- Akzeptable: wenn Speicherplatz oder Bandbreite begrenzt sind und die Inhalte trotzdem „gut genug“ wahrgenommen werden, z. B. bei Musik-Streaming oder sozialen Medien.

- Unakzeptabel: in der Medizin oder in wissenschaftlichen Anwendungen, bei denen Genauigkeit entscheidend ist.

  

2. **Zukünftige Technologien:**

- KI-basierte Algorithmen, die erkennen können, welche Daten für die Wahrnehmung wichtig sind.

  

3. **Bewertung der Quelle:**

- Die Quelle ist hilfreich für die Grundlagen, Techniken und Vor- und Nachteile der verlustbehafteten Kompression zu verstehen. Allerdings bietet sie keine genauere Informationen und verweist über Links auf andere Seiten.

