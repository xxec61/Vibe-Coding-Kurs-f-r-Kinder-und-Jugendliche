Ein Labyrinth-Spiel fordert die Orientierung und Problemlösefähigkeit eines Spielers. Man muss durch verzweigte Wege navigieren, den Ausgang finden oder bestimmte Aufgaben innerhalb des Labyrinths lösen.

Für ein Labyrinth brauchen wir:

- Eine Figur, die sich mit dem Pfeiltasten bewegen kann
- Ein Labyrinth mit einem Start und einem Ziel
- Sowie Einen Timer, um ein Zeitlimit zu haben

### <u>Umsetzung</u>

Dann versuchen wir des mal umzusetzen. Als Model werde ich ab jetzt den Qwen3-Coder-30b-a3b-instruct verwenden:

**Kannst du ein Labyrinth mit verzweigten Wegen erstellen, bei dem ich mit einer Figur vom Anfang zum Ziel navigieren muss.**

Ich führe den Code aus und sehe ein braun-grünes Labyrinth. Wenn ich runter scrolle kann ich die Steuerung und das Ziel lesen. Wenn ich die Figur nach oben oder unten navigiere, bewegt sich auch die Seite mit. Das kann man beheben. Wenn man gegen die Wände kommt, kann man nicht hindurch. 

Die gelben Knöpfe mit den Richtungen funktionieren einwandfrei. Wenn ich am Ziel ankomme, erscheint unten ein Glückwunsch.

Dann schauen wir mal in die Checkliste durch:

- Kann sich die Figur mit den Pfeiltasten bewegen - Ja, aber das will ich ändern
- Hat das Labyrinth einen Anfang und ein Ziel - Ja
- Und ist ein Timer zu sehen - Noch nicht

Zuerst möchte ich die Steuerung anpassen. Neben den Pfeiltasten werden auch die Tasten WASD zum Steuern einer Figur in Spielen verwendet. Das werde ich prompten:

**Statt den Pfeiltasten sollen die Tasten A W S D zum steuern verwendet werden.**

Und genau das hat die KI umgesetzt. Die Pfeiltasten kann man zur Steuerung nicht mehr verwenden. Sehr schön. Was mich etwas stört ist, dass der Glückwunsch-Text unten vom Labyrinth spielt. Den möchte ich gerne oben haben.

Also schreibe ich:

**Kannst du den Text, bei dem man lesen kann, ob man das Ziel erreicht hat, über das Labyrinth stellen.**

Hier sehen wir ein Beispiel, wie ein ungenauer Prompt zu einem fehlerhaften Umsetzung der KI kommt. Mit dem Teil “über das Labyrinth stellen”, war nicht gemeint, dass der Text auf dem Labyrinth sein soll, sondern über dem Labyrinth. 

Deswegen schreib ich der KI:

**Der Text liegt genau auf dem Labyrinth. Kannst du diesen bitte aus dem Labyrinth raus und direkt unter den Titel schreiben.**

Hier ist es zum ersten Mal passiert, dass beim umsetzen des Codes die KI mittendrin abgebrochen hat. Das führt dazu, dass nichts auf der Spielseite zusehen ist.

Das müssen wir korrigieren:

**Du hast den Code abgebrochen, bitte generiere es wieder.**

Dieses mal hat die KI nichts abgebrochen und den Text nach oben gestellt. Super. Dann kommt als letzter Schritt der Timer:

**Kannst du einen 20 Sekunden Timer einfügen. Wenn man es nicht in den 20 Sekunden schafft im Ziel zu sein, soll Verloren erscheinen**

Ich führe den Code aus und sehe den Timer. Ich lasse diesen mal auf 0 gehen, um zu schauen, ob ein Verloren erscheint. Und es erscheint. Sehr schön!

Man könnte das Labyrinth etwas größer machen oder Objekte hinzufügen, um den Schwierigkeitsgrad etwas zu erhöhen.
