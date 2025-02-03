## Grundlagen der verlustbehafteten Kompression – Fragen und Antworten

## Verwendete Quelle  

4.Theo - t3․gg auf YouTube: [Video Compression Is Magical](https://www.youtube.com/watch?v=pX2L_UAIoME&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=20&pp=gAQBiAQB)

## Was ist h264?

h264 ist ein Video-Kompressions-Codec-Standard. Es ist allgegenwärtig: Internetvideos, Blu-rays, Telefone, Sicherheitskameras, Drohnen, alles verwendet h264. h264 ist das Ergebnis von über 30 Jahren Arbeit mit einem einzigen Ziel: Die Bandbreite zu reduzieren, die für die Übertragung von Bewegtbildern benötigt wird.

## Warum Kompression notwendig ist

Ein unkomprimiertes Video mit einer Auflösung von 1920 x 1080 Pixeln bei 60 FPS benötigt 370 Megabyte pro Sekunde. Das ist eine Bandbreite, die weit über den meisten Internetverbindungen liegt.

## Wie funktioniert h264?

1. **Weglassen von Details**

- h264 verwirft gezielt Detailinformationen, um Daten effizienter zu speichern. Beispielsweise werden Farbdetails reduziert, weil das menschliche Auge diese weniger wahrnimmt.  

2. **Frequenzbereiche und Transformation**

- Daten werden in einen Frequenzbereich transformiert, bei dem feinere Details (hohe Frequenzen) oft entfernt werden, um Platz zu sparen. Dies geschieht verlustfrei, solange der Fokus auf niedrigen Frequenzen bleibt.  

3. **Temporale Kompression**

- h264 nutzt Bewegungs-Kompensation. Statt jedes Frame komplett zu speichern, werden nur Änderungen zwischen Frames (Bewegungsvektoren) kodiert.

- Es gibt I-Frames (vollständig gespeichert), P-Frames (basierend auf vorherigen Frames) und B-Frames (Änderungen basierend auf vorherigen und folgenden Frames).

- [Beispiel aus dem Video](https://youtu.be/pX2L_UAIoME?si=7y6WclCEFtkN32ug&t=1693)


## Dekodierung von h264
 

Die Dekodierung von h264 erfordert oft Hardware-Beschleunigung, da jedes Frame durch komplexe Berechnungen aus den I-, P- und B-Frames zusammengesetzt wird.

## Technologien in h264


1. **Lossy Compression**:

- Details werden entfernt, um Platz zu sparen (z.B. feine Strukturen).

2. **Quantisierung**:

- Frequenzkomponenten (hochfrequente Details) werden reduziert.

3. **Chroma Subsampling**:

- Farbinformation wird teils verworfen, da das menschliche Auge Farbdetails schlechter wahrnimmt.

- Y = Helligkeit, Cb und Cr = Farbe

4. **Motion Compensation**:

- Reduktion redundanter Bilddaten zwischen Frames (I-, P-, B-Frames).

  

Lea Hergert, Melanie Müller