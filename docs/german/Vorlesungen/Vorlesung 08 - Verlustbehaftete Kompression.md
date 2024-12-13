## Achter Termin


Mittwoch, 20.11.2024 in Raum L2.05a

### Ziele

- Verlustbehaftete Kompressionsmethoden kennen lernen und verstehen
	- z.B. JPEG und MPEG
- Wo kommen diese Methoden zum Einsatz?


### Drehbuch

| Was                           | Dauer  | Material                     |
| ----------------------------- | ------ | ---------------------------- |
| Vorstellung der Gruppenarbeit | 10 min | [[DAVT-Aufgabenblatt06.pdf]] |
| Arbeit in Kleingruppen        | 45 min | [[DAVT-Aufgabenblatt06.pdf]] |
| Präsentation der Ergebnisse   | 25 min |                              |
| Zusammenfassung und Ausblick  | 10 min |                              |

#### Ergebnisse aus den Gruppen

Die Themen bzw. Quellen wurden folgendermaßen zugewiesen und bearbeitet:

1. Techquickie auf YouTube: [Video Compression as Fast As Possible](https://www.youtube.com/watch?v=qbGQBT2Vwvc&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=16&pp=gAQBiAQB) und [What is a Codec as Fast As Possible](https://www.youtube.com/watch?v=GhWki9a7s18&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=17&pp=gAQBiAQB) --> Sebastian, Emil, Lukas: Ergebnis: tbd
2. B&H Photo Video Pro Audio auf YouTube: [How to Understand Codecs](https://www.youtube.com/watch?v=sisvOeZItb0&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=19) --> Uwe, Ergebnis: [[B&H Photo Video Pro Audio]]
3. Qencode auf YouTube: [Video Formats, Codecs and Containers (Explained)](https://www.youtube.com/watch?v=XvoW-bwIeyY&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=18) --> Christian, Ergebnis: [[Qencode]]
4. Theo - t3․gg auf YouTube: [Video Compression Is Magical](https://www.youtube.com/watch?v=pX2L_UAIoME&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=20&pp=gAQBiAQB) --> Lea, Melanie, Ergebnis: [[Theo]]
5. [Lossy compression](https://en.wikipedia.org/wiki/Lossy_compression) --> Ian, Franziska, Ergebnis: [[Lossy compression]]
6. [AOMedia Video 1](https://de.wikipedia.org/wiki/AOMedia_Video_1) --> Benjamin, Ergebnis: tbd
7. ChatGPT generierter Text (siehe [[Verlustbehaftete Kompression von Medieninhalten]]--> Marvin, Ergebnis: [[ChatGPT Verlustbehaftete Kompression]]

#### Tafelbilder

![[DAVT-08-Codec.JPEG]]
Der Begriff Codec wird meistens als Zusammenlegung der Wörter CoderDecoder verwendet, manchmal aber auch als CompressionDecompression.

![[DAVT-08-intra_vs_inter.JPEG]]
Man unterscheidet bei der Videokompression zwischen *intra* und *inter* frame Methoden. Also einmal innerhalb des selben Frames (intra) und auch zwischen verschiedenen Frames (inter). Es geht immer darum Bewegungen von Bildobjekten zu finden und diese als Motion Vector zu beschreiben anstatt die Pixeldaten des Objekts ein zweites Mal zu speichern. Man sucht also sich wiederholende Elemente sowohl im selben Bild (z.B. großflächig einfarbige Bereiche oder Muster) als auch in angrenzenden Frames, denn im Video von einer Szene ändert sich von Bild zu Bild in der Regel nicht viel.