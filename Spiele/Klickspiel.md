Unter einem Klickspiel kann man verschiedene Spiele meinen. Beispielsweise kann es darum gehen mit der Maus alle Objekte auf einem Spielfeld anzuklicken, oder auch nur bestimme Objekte. Es kann sich auch um ein Spiel handeln, bei dem man in einer bestimmten Sekunde die Maustaste klicken muss. 

In diesem Video werde ich ein Klickspiel machen, bei dem man bestimmte Objekte anklicken muss, um zu gewinnen.

Wir benötigen für das Klickspiel:

- einen sichtbaren Mauszeiger, der sich im Spielfeld bewegt
- Objekte, die auf dem Spielfeld liegen
- Eine Aktion zwischen der Maus und dem Objekt, damit das Objekt verschwindet
- ein Punktestand der hochgeht, sobald ein Objekt gesammelt wird
- und ein Gewonnen-Fenster

Ich möchte zusätzlich noch als Thema “Früchte” haben.

Dann können wir übergehen zur lokalen KI.

### <u>Umsetzung</u>

Nun schreiben wir wieder unsere Voraussetzung für das Spiel in einen Prompt. Dieser kann so aussehen: 

**Erstelle ein Klickspiel, bei dem man mit der Maus zwischen verschiedenen Früchten, die auf dem gesamten Spielfeld verteilt sind, 10 Äpfel sammeln muss, um zu gewinnen.**

Und jetzt schicken wir den Prompt ab. Hier habe ich ein Klickspiel. Bei diesem erscheinen immer wieder rote Äpfel auf roten Kreisen auf dem Feld, die man anklicken kann. Sobald ich 10 gesammelt hab, hab ich gewonnen.

Nun gehe ich meine Checkliste einmal durch, ob wirklich alles umgesetzt worden ist.

- [ ]  Ist der Mauszeiger sichtbar - Check
- [ ]  Reagiert der Mauszeiger auf das Klicken von Objekten - Check
- [ ]  Liegen auf dem Spielfeld Objekte - Check
- [ ]  Geht der Punktestand hoch - Check
- [ ]  Erscheint ein Gewonnen-Fenster - Check

Grundlegend hat die KI das umgesetzt was ich mir gewünscht habe. 

In der Vibe Coding Kurs UI könnt ihr im unteren Bereich, bei der die KI ihre Lösung ausgibt, eine kleine Beschreibung lesen, was dieser umgesetzt hat.

Bei mir steht drinnen: Sobald man einen Apfel anklickt, verschwindet dieses und man erhält einen Punkt. Wenn 10 Äpfel gesammelt wurden, erscheint “Gewonnen”.

Einen Punkt, die die KI etwas anders umgesetzt hat, ist das erscheinen der Früchte. Ich hatte angegeben gehabt, dass verschiedene Früchte zusehen sein sollen. Umgesetzt wurde aber nur der Apfel. Also schreibe ich:

**Kannst du zusätzlich zu den Äpfeln auch Bananen und Orangen erscheinen lassen. Zum Gewinnen soll man aber weiterhin nur die Äpfel anklicken.**

Ich sende den Prompt ab und nach paar Minuten erscheint der vollständige Code. Ich klick auf ausführen. Und wir sehen verschiedene Früchte, die erscheinen. Sobald ich eine Banane anklicke, verschwindet diese nur. Sehr schön. Aber..Die KI hat statt Orangen Kirschen umgesetzt. Außerdem erscheint hinter der Frucht immer eine Form, wodurch man das Symbol nicht wirklich sieht.

Also sag ich der KI:

**Bitte entferne die Formen, die du hinter die Früchte einfügst. Dafür kannst du die Früchte etwas größer stellen, um sie besser zu sehen.**

Und wir sehen, dass die KI nicht meinen Wunsch umgesetzt hat wie ich es wollte.

Wenn ich zurück in die Beschreibung gehe, lese ich heraus, dass verschieden gefärbte Divs umgesetzt wurden. Das ist eine Referenz auf die großen roten und gelben Kreise. Das die KI Fehler macht, ist normal, da sie nicht fehlerfreie Antworten gibt.

Deswegen korrigiere ich diesen nochmal:

**Du hast die Emojis von den Früchten statt die gefärbten Divs entfernt. Bitte füge wieder die Emojis von dem Apfel, der Banane und der Kirsche hinzu.**

Wenn ich jetzt auf Ausführen klicke, sehe ich, dass er den Prompt richtig umgesetzt hat. Klasse! 

Falls ihr parallel mit gecodet habt, werdet ihr feststellen, dass das Ergebnis bei euch sehr warscheinlich anders aussieht, als es bei mir der Fall ist. Das ist völlig normal, da die generative KI beim Erstellen von Inhalten immer verschieden vorgeht, wodurch verschiedene Ergebnisse rauskommen. 

Das kannst du ausprobieren, in dem du auf “Neues Projekt” klickst, und die Schritte nochmal durchgehst.
