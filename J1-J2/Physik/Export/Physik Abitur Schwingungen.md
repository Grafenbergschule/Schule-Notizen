# Aufgabe 4

**4.1**
Formel: $v = \omega \cdot s_{max} \implies s_{max} = \frac{v}{\omega}$
$\omega = \sqrt{\frac{g}{l}} = \sqrt{\frac{9,81}{25,2}} = 0,624 \frac{1}{s}$
$s_{max} = \frac{2,5}{0,624} = 4,01 m$

Erklärung: Der Kran bremst, aber die Last will wegen ihrer Trägheit weiterfliegen. Das Seil hält sie fest und zwingt sie auf eine Kreisbahn nach oben. Die Schwerkraft zieht sie dann wieder zurück zur Mitte -> es pendelt.

**4.2**
Aus der Formel $s_{max} = \frac{v}{\sqrt{\frac{g}{l}}}$ sieht man, dass die Masse $m$ gar nicht vorkommt. 
- Kim hat unrecht, die Masse ändert an der Auslenkung gar nichts.
- Kevin hat recht, es hängt nur von der Geschwindigkeit ab (wenn die Länge gleich bleibt).

**4.3**
(Skizze machen: Pendel schräg zeichnen, Pfeil für $F_G$ gerade nach unten, Pfeil für $F_R$ im 90°-Winkel zum Seil Richtung Mitte)
Im rechtwinkligen Dreieck gilt: $\sin(\alpha) = \frac{Gegenkathete}{Hypotenuse} = \frac{F_R}{F_G}$
Umgestellt ergibt das: $F_R = F_G \cdot \sin(\alpha)$

**4.4**
DGL: $m \cdot \ddot{s} = -\frac{m \cdot g}{l} \cdot s$ (das $m$ auf beiden Seiten wegkürzen)
$\ddot{s} = -\frac{g}{l} \cdot s$

Ansatz: $s(t) = s_{max} \cdot \sin(\omega t)$
2x ableiten: $\ddot{s}(t) = -\omega^2 \cdot s(t)$

Einsetzen in DGL: 
$-\omega^2 \cdot s(t) = -\frac{g}{l} \cdot s(t)$
$\omega^2 = \frac{g}{l}$

Mit $\omega = \frac{2\pi}{T}$ folgt:
$\frac{4\pi^2}{T^2} = \frac{g}{l} \implies T = 2\pi \sqrt{\frac{l}{g}}$

Rechnung M1:
$T = 2\pi \sqrt{\frac{25,2}{9,81}} = 10,07 s$

**4.5**
Formen: Potenzielle ($E_{pot}$) und kinetische Energie ($E_{kin}$).
Umwandlung: Ganz oben gibt es nur $E_{pot}$. Beim Runterschwingen wird die Höhe kleiner und das Pendel schneller, also wird $E_{pot}$ in $E_{kin}$ umgewandelt. Kurz vor dem Aufprall ist $E_{pot}$ komplett null und $E_{kin}$ am größten (maximale Geschwindigkeit).

**4.6**
Energieerhaltung: $E_{pot} = E_{kin}$
$m \cdot g \cdot h = 0,5 \cdot m \cdot v^2$
$v_{max} = \sqrt{2 \cdot g \cdot h} = \sqrt{2 \cdot 9,81 \cdot 0,45} = 2,97 m/s$

Schwingungsdauer: $T = 2\pi \sqrt{\frac{4,8}{9,81}} = 4,4 s$
Aufprall ist bei $T/4 = 1,1 s$.

Gleichung: $v(t) = 2,97 \cdot \sin(\frac{2\pi}{4,4} \cdot t)$

Wertetabelle:
t in s:   0   |  0,3  |  0,6  |  0,9  |  1,1
v in m/s: 0   |  1,2  |  2,2  |  2,8  |  2,97
(Fürs Diagramm: Einfach eine halbe Sinuskurve bis t=1,1 und v=2,97 zeichnen)

Gründe:
- Fallhöhen: Um verschieden starke Stöße zu testen (leichter Rempler vs. Sturz).
- Reifen: Ein Mensch ist nicht aus hartem Metall. Die Gummireifen verformen sich beim Aufprall, das ist realistischer für einen menschlichen Körper.

Beurteilung:
Der Versuch ist gut geeignet. Er stellt einen Unfall, bei dem jemand gegen eine Scheibe fällt, sehr realistisch nach. So kann man gut testen, ob das Glas das aushält oder ob es gefährlich splittert.