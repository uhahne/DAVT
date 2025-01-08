## Zehnter Termin


Mittwoch, 18.12.2024 in Raum L2.05a

### Ziele

- Videocodecs in der Praxis mit Python und FFmpeg


### Drehbuch

| Was                                            | Dauer  | Material                                            |
| ---------------------------------------------- | ------ | --------------------------------------------------- |
| Übungsaufgabe 7: Video Encodings in der Praxis | 90 min | [[DAVT-Aufgabenblatt07.pdf]]                        |


#### Ergebnisse 

Alle Teilnehmenden waren in der Lage eines der Videos zu komprimieren und auf das Smartphone zu übertragen. Es gab die folgenden Erkenntnisse:
- Bei der Verwendung von AV1 als Codec kann man dieser Anleitung folgen: https://trac.ffmpeg.org/wiki/Encode/AV1 - Man muss allerdings beachten, dass es mit der `libaom-av1` Bibliothek nur sehr langsam (ca. 0.1 fps auf einem MacBook Pro M2) geht. Verwendet man die Bibliothek `libsvtav1`, geht es viel schneller.
- Das [StarCraft YUV Video](https://dash-large-files.akamaized.net/WAVE/3GPP/5GVideo/ReferenceSequences/StarCraft/) nutzt keinen gängigen Container. Daher muss man dies bei der Konvertierung beachten und beispielsweise folgenden Befehl verwenden:
	- `ffmpeg -f rawvideo -vcodec rawvideo -s 1920x1080 -r 60 -pix_fmt yuv420p -i StarCraft.yuv -c:v libsvtav1 output.avi `

#### Tafelbilder

Fehlanzeige