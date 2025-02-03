#### Termin

Mittwoch, 15.01.2025 in Raum L2.05a

### Ziele

- Umgang mit Lagrange Polynomen verstehen

- Grundverständnis für die Funktionsweise von Reed-Solomon Codes


### Drehbuch

| Was                                  | Dauer  | Material                                                                                                                              |
| ------------------------------------ | ------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| Einstieg/Motivation                  | 3 min  | [Reed Solomon Encoding - Computerphile](https://www.youtube.com/watch?v=fBRMaEAFLE0&list=PLY8Upfcg86WQ5OtjhHkPchJdZbE1xbxnV&index=24) |
| Fehlerkorrektur (Teil 2)             | 27 min | [[DAVT-09-Fehlerkorrektur2.pdf]] (bis Folie 15 Ende Lagrange)                                                                         |
| Praktische Vertiefung                | 30 min | [[DAVT-Aufgabenblatt09.pdf]]                                                                                                          |
| Fortsetzung Fehlerkorrektur (Teil 2) | 30 min | [[DAVT-09-Fehlerkorrektur2.pdf]]                                                                                                      |



#### Ergebnisse 

Lösung für Aufgabe 1 des [[DAVT-Aufgabenblatt09.pdf]] siehe [SciPy Doku Lagrange](https://docs.scipy.org/doc/scipy/reference/generated/scipy.interpolate.lagrange.html) 

Notwendige Änderungen im Code um Aufgabe 2 des [[DAVT-Aufgabenblatt09.pdf]] zu lösen:
```python
# test data

data = [0,1,8]

support = [0,1,2]

test_support = np.array([3])

...

print(xx,yy) # print the test_support values
```

#### Tafelbilder

![[DAVT-09-Nullstellen.JPEG]]
Allgemeines Schema, wie man von den Nullstellen zum Polynom kommt.
![[DAVT-A09-LagrangePolynom.JPEG]]
Beginn der Lösung der Aufgabe 1 auf [[DAVT-Aufgabenblatt09.pdf]]
#### Terminplanung

22.1. GenAI (GAN, StableDiffusion, text2video)

05.02. ab 14 Uhr Klausurvorbereitung im i0.15

### Was man verstanden haben sollte
- Ich kenne Anwendungen, die Reed-Solomon Codes verwenden.
- Ich habe das Prinzip von Reed-Solomon Codes verstanden und weiß was sie mit Galois-Körpern zu tun haben.
- Ich weiß wie man anhand der Nullstellen ein Polynom definieren kann.
- Wenn ich die Formel habe, kann ich Lagrange-Polynome aufstellen und damit rechnen.
