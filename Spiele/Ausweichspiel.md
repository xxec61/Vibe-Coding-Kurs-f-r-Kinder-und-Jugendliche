Unter einem Ausweichspiel versteht man ein Spiel, bei dem man eine Figur spielt, die herumfliegenden oder liegenden Objekten ausweichen muss, um nicht zu verlieren. Ziel ist es, möglichst lange zu überleben oder ein bestimmtes Ziel zu erreichen, ohne getroffen zu werden.

Beispiele hierfür sind Spiele wie Subway Surfers, Geometry Dash oder Asteroids.

Für ein Ausweichspiel brauchen wir:

- Eine Figur, die sich bewegen kann
- Objekte, die umher fliegen
- Wenn man von einem Objekt getroffen wird, verliert man
- Es soll ein Game Over Fenster erscheinen

Später wollen wir noch ein Timer hinzufügen, damit man sieht, wie lange man überlebt.

Ich möchte als Thema “Weltall” umsetzen. Deswegen will ich als Figur eine Rakete und als Objekt Sterne.

### <u>Umsetzung</u>

Wir wechseln zur Vibe Coding Kurs Seite.

Als Startprompt gebe ich ein:

**Kannst du mir ein Ausweichspiel programmieren, bei dem ich eine Rakete steuere, die von Sternen ausweichen muss.**

Nun generiert es mir das Spiel. Ich klicke auf ausführen, und sehe ein weißes Rechteck, die die Rakete sein soll. Von oben kommen gelbe Punkte runter, die die Sterne sein sollen. Wenn ich mich von einer treffen lasse, dann erscheint da Game-Over Fenster.

Gehen wir die Checkliste durch:

- Kann sich die Figur bewegen - Ja
- Fliegen Objekte herum - Ja
- Führt eine Kollidieren von Figur und Objekt zu einem Ende - Ja
- Erscheint das Game Over Fenster - Ja

Was kann ich verbessern? Was die KI nicht ganz richtig umgesetzt hat, ist die Rakete und die Sterne. Also werde ich prompten, dass es diese umsetzt. Im letzten Video haben wir bereits gesehen, dass die KI auf Emojis zurückgreift, wenn man explizit dies schreibt.

Zuerst mach ich des für die Sterne.

Also schreibe ich:

**Die Sterne werden als gelbe Kreise angezeigt. Kannst du diese zu einem Stern Emoji ändern.**

Und die KI setzt dieses um. Wir können uns merken, dass wir prompten können, welche Emojis die KI nutzen soll, um bspw. die Figur umzusetzen, die man möchte.

Dann machen wir dasselbe mit der Rakete:

**Die Rakete ist gerade ein weißes Rechteck. Kannst du statt dem Rechteck ein Raketen Emoji reinpacken.**

Und zack hat die KI auch das umgesetzt. Sehr schön.

Zuvor hab ich bereits erwähnt gehabt, dass ich gerne noch einen Timer hätte, damit ich sehen kann, wie lange ich überlebe. Das werde ich nun der KI prompten:

**Kannst du einen Timer einfügen, damit ich sehen kann, wie lange ich überlebe.**

In der Beschreibung lese ich heraus, dass das Element div eingefügt wurde, um den Timer anzuzeigen. Klicke ich auf ausführen, sehen wir oben einen Timer, der funktioniert. Wenn ich mich treffen lasse, sehen wir auf dem Game-Over Fenster die Zeit, die ich überlebt habe. 

Super, die KI hat diesesmal auf Anhieb das umgesetzt, was ich wollte. Das ist nicht immer der Fall, da die KI dazu neigt, wie wir es in den letzten beiden Videos gesehen haben, oft Fehler zu machen und etwas anders umzusetzen, als man es möchte.
