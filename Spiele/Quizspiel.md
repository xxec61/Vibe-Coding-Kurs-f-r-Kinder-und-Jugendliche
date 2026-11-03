Bei Quiz- und Rätselspielen lösen die Spieler Wissensfragen, Logik- oder Denksportaufgaben. Der Schwerpunkt liegt auf Wissen, Kreativität und Problemlösung.

Beispiele hierfür wären Wer wird Millionär oder Trivia

Für ein Quizspiel brauchen wir:

- Fragen zu einem Thema
- Eine Anzeige, die die Anzahl an richtig beantworteten Fragen anzeigt.
- Ein Timer zum Beantworten der Fragen

Die Fragen möchte ich gerne zum Thema Tiere gestellt bekommen.

### <u>Umsetzung</u>

Der Anfangsprompt kann so aussehen:

**Erstelle mir ein Quizspiel zu dem Thema “Tiere”.**

In der Beschreibung steht drin, dass zwei Fragen erstellt wurden. Das ist meiner Meinung nach zu wenig, aber erstmal ok. Wenn ich den Code ausführe, sehen wir die Fragen untereinander. Ich beantworte diese und klicke auf Antworten prüfen. Es erscheint “Du hast  0 von 2 Fragen richtig beantwortet!” Ich kann meine Antworten nochmal korrigieren und prüfen lassen. Jetzt hab ich alle beiden Fragen richtig beantworten.

Gehen wir die Checkliste durch:

- Werden Fragen zum Thema gestellt? - Ja
- Gibt es eine Anzeige, die die richtig beantworteten Fragen zeigt. - Ja
- und sieht man einen Timer? - Noch nicht.

Bevor ich den Timer umsetzen lasse, möchte ich noch mehr Fragen, am besten 8 weitere. Also prompte ich:

**Kannst du acht weitere Fragen hinzufügen.**

Und wir sehen, dass die KI dies umgesetzt hat.

Mir fällt auf, dass die Fragen aufeinmal und nicht nach und nach wie bei einem Quizspiel erscheinen. Also schreibe ich:

**Kannst du die Fragen so stellen, dass immer eine Frage zusehen ist. Sobald man die beantwortet hat, erscheint die nächste.**

Sobald die KI die Lösung ausgibt, führen wir wieder den Code aus. Und nun sehen wir immer nur eine Frage. Sehr schön.

Dann fehlt nur noch der Timer:

**Kannst du einen Timer von einer Minute einfügen. Man soll innerhalb des Zeitlimits alle Fragen beantworten, ansonsten erscheint ein Game Over Fenster.**

Und der Timer steht. Ich lasse einmal die eine Minute ablaufen, um zu sehen, ob das Game Over Fenster erscheint.

Damit habe ich alles umgesetzt, was auf der Checkliste steht.
