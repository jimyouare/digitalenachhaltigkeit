# digi vortrag.md

Guten Tag
Herzlich wilkommen
Wir Paco Eggimann Flavio Gerber und ich Tobias Brunner werden heute kurz zum Thema Sicherheit bei Open Source Projekten sprechen. 

Unser Input ist in 3 Teile geglieder:
- Was sagt die Wissenschaft
- Wie sieht dies in der Realität aus anhand von Puzzle ICT
- und zum abschluss unser Fazit


Ich glaube das Folgende Zitat ist in dieser Vorlesung auch schon vorgekommen, trotzdem nochmal als Einstieg
Given enough eyeballs, all bugs are shallow
- von Eric S. Raymond (Amerikanischer software developer, open-source software advocate)

Auf der anderen Seite des Spektrums die Realität

Heartbleed Bug in OpenSSL eine schwerwiegende Sicherheitslücke (Entschlüsselung von Daten, VoIP etc) die 27 Monate existierte (2014 behoben)

oder auch die Shellshock Sicherheitslücke (Variable welche nach der Auswertung ungeprüft Programmcode ausgeführt)

Auf der einen Seite haben wir edle Grundsätze und auf der anderen Seite auch die harte realität. 
Damit sind wir miten im Thema 
-> next


With great power comes great responsibility
OpenSource ist super kann oft gratis eingesetzt werden und ist deswegen auch atraktiv. 
Deshalb sind sicherheitstechnische Aspekte sehr wichtig.

Offener Code ist offen. Angreiffer können gezielt nach Fehlern in den Programmen suchen

Es ist wichtig Open Source Projekte so zu führen, dass dabei eine robuste Applikation entstehen kann. Wichtig ist dabei Sicherheitstechnische Apsekte zu allen Phasen der Entwicklung in Betracht zu ziehen, insbesondere die verteilte Entwicklung führt zu einer hohen soziotechnischen komplexität welche auch ein Risiko darstellt.

Ich hatte zu begin Heartbleed und auch Shellshock erwähnt. Es ist nicht so, dass es nur katastrophale Fehler bei OpenSource Software gibt. Siehe z. B. Ariane 5 

Anwenden von Sicherheitsstandards und Best Practises haben die beste Chance für eine robsute Applikation zu Garantieren. 

Vielen Dank fürs zuhören.