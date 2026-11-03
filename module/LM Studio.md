Jetzt wird es praktisch.

Wir richten gemeinsam unsere lokale KI ein.

Sobald alles eingerichtet ist, kannst du deine eigene Ideen Schritt für Schritt in Spiele verwandeln.

**Für diesen Teil wäre es wichtig, wenn ein Elternteil oder erwachsene Person zur Unterstützung dabei ist.**

Um eine lokale KI zum laufen zu bringen, benötigen wir das Programm “LM Studio”.

#### <u>Warum brauchen wir LM Studio</u>

Damit wir Vibe Coden können, brauchen wir ein Programm, das unsere KI auf dem Computer ausführt.

Hierfür gibt es mehrere Programme, wir werden aber **LM Studio verwenden**.

LM Studio sorgt dafür, dass die lokale KI auf deinem Computer läuft und deine Prompts verarbeiten kann.

Das bedeutet: Du kannst der KI deine Ideen beschreiben und sie hilft dir dabei, daraus Programmcode zu erstellen.

#### <u>Die Einrichtung</u>

Bevor ihr etwas herunterladet, fragt eure Eltern, ob sie euch dabei bei Seite stehen, damit ihr alles richtig macht. Insgesamt benötigt ihr in etwa 22 GB oder mehr Speicherplatz für die Installation des Programms.

Als erstes gehen wir auf einen beliebigen Browser, wie Google Chrome, Microsoft Edge oder einen, den ihr auf eurem Gerät habt.  Jetzt suchen wir nach “LM Studio Download” und klicken auf den Link “Download LM Studio” mit dem blauem Logo von LM Studio.

Wir wollen LM Studio herunterladen und scrollen etwas nach unten. Hier könnt ihr auswählen, welches Betriebssystem ihr auf eurem Gerät habt. Fragt dafür am besten eure Eltern, damit ihr nicht das falsche auswählt.  Die anderen beiden Reiter lassen wir bei ihren Einstellungen. 

Jetzt klickt ihr auf die blaue Fläche und wartet bis dieses heruntergeladen wurde. Oben rechts könnt ihr mitverfolgen, wie weit euer Download ist. 

Sobald die exe Datei heruntergeladen wurde, könnt ihr direkt auf die Download-Datei draufklicken.

Dadurch wird dieses Fenster geöffnet, mit dem wir LM Studio auf euer Gerät installieren können.

Zuerst erscheint das Lizenzabkommen.  Ein Lizenzabkommen ist eine Erlaubnis, etwas zu benutzen, das jemand anderem gehört. In diesem steht drin, wer etwas nutzen darf, wie es genutzt werden darf und welche Regeln dabei gelten. Ihr könnt gemeinsam mit euren Eltern dieses durchlesen. Damit wir LM Studio benutzt können, müssen wir dieses akzeptieren. 

Als nächstes müsst ihr entscheiden, bei wem das Programm für die Nutzung installiert werden soll. Wenn man auf “alle Benutzer dieses Computers” klickt, wird sie für jeden Nutzer heruntergeladen. Wenn ihr “nur für mich” anklickst, wird es nur auf den aktuell angemeldeten Benutzer des Geräts heruntergeladen. Wählt die Option aus, die ihr für geeigneter haltet, und klickt auf weiter.

Jetzt müssen wir auswählen, wo LM Studio auf dem Gerät gespeichert werden soll. Standardgemäß wird dies in dem Ordner gemacht, bei dem alle Programme heruntergeladen werden. Wählt den Ordner aus und klickt auf installieren. Nun warten wir drauf, bis es fertig eingerichtet wird. Sobald diese Fenster erscheint, schauen wir drauf, ob die Checkbox “LM Studio ausführen” einen blauen Haken hat und klicken auf fertigstellen.

Jetzt wird LM Studio geöffnet. Wir klicken auf “Get Started”. In diesem Fenster kann man ein Modell herunterladen. Ein Modell ist das Gehirn einer KI. In diesem steckt alles, was die KI beim Lernen gelernt hat. Wenn man der KI eine Frage stellt oder ein Prompt sendet, nutzt sie dieses Wissen, um eine Antwort zu geben. Das hier vorgegebene Modell brauchen wir nicht, deswegen überspringen wir es vorerst.

Nun können wir noch spezielle Einstellungen vornehmen.  Ihr könnt den zweiten Knopf  “Start local LLM service on login” offen lassen. Dabei wird bei jeder Anmeldung auf dem Gerät die KI automatisch im Hintergrund gestartet. Wenn ihr dies nicht wollt, könnt ihr diesen mit einem Klick auf den Knopf ausschalten. Dann klicken wir auf “Continue to LM Studio”. 

In den EInstellungen könnt ihr unter General, App Language die Sprache zu Deutsch ändern. Da die Sprache jedoch noch in der Beta ist, sind noch nicht alle Übersetzungen für das Programm verfügbar. 

Damit wir einen Chat starten können, müssen wir uns zuerst ein Modell herunterladen. Dafür gehen wir auf der linken Seite zu dem Reiter Model Search. Hier können wir in der Suchleiste nach einem spezifischem Modell suchen.

Für den Kurs nutze ich unter anderem den Qwen2.5-Coder-7B-Instruct-GGUF von lmstudio-community.

Qwen2.5 steht für den generellen Modellnamen. Coder steht dafür, dass dieses Modell speziell für Programmieraufgaben entwickelt wurde und Code schreiben, erklären, verbessern und Fehler finden kann.7B steht dafür, dass das Modell insgesamt 7 Milliarden Parameter bzw. Zusammenhänge hat, die es für das Verstehen von Prompts braucht. Instruct sagt, dass das Modell darauf trainiert wurde, Anweisungen und Fragen von Nutzern gut zu befolgen. Die GGUF-Version ist so vorbereitet, dass sie direkt auf dem eigenen Computer in Programmen wie LM Studio genutzt werden kann.

Je nach dem welche Grafikkarte und Arbeitsspeicher ihr auf eurem Gerät habt, kann sich die Modellgröße ändern, da nicht jedes Modell bei jedem Gerät funktioniert. Um herauszufinden, welche Anforderungen ihr habt, müsst ihr auf eurem Gerät in die Einstellungen gehen und könnt unter System Info die Grafikkarte und den Installierten RAM also den Arbeitsspeicher sehen. Bitte recherchiert gemeinsam mit einer erwachsenen Person, welches Qwen-Modell idealerweise zu euren Anforderungen passt. Sobald ihr das passende gefunden habt,klicken wir auf Download und können rechts oben verfolgen, wie lange dieser braucht. Ein Tipp meinerseits ist es, den Download einmal anzuhalten und wieder neu zu starten, falls die Größe des Downloads unter 2 MB pro Sekunde anzeigt.

Sobald der Download durch ist klicken wir auf den Play-Button, um das Modell zu laden. Auf der linken Seite klicken wir auf Model Server, um den Fortschritt genauer zu beobachten. Sobald es geladen wurde, können wir rechts die Context Length ändern. DIe Context Length ist die Menge an Informationen die die KI im Kopf behält, wenn sie deinen Prompts beantwortet. Je höher sie gestellt ist, desto mehr Informationen kann sie im Kopf behalte. Ich lasse sie bei mir auf 8192 . Eins drunter seht ihr den GPU Offload. Der GPU Offload steht dafür, wie viel Arbeit die KI an die Grafikkarte abgibt. Wenn diese auf 0 gesetzt ist, arbeitet die KI eigenständig. Ich stelle sie auf 5. Anschließend müssen wir unten auf Reload klicken und warten, dass das Modell wieder geladen wird. 

#### <u>Was passiert jetzt?</u>

Nun können wir zum Chat wechseln. Ab jetzt ist deine KI einsatzbereit.

Als nächstes werden wir gemeinsam verschiedene Spiele entwickeln.

Dabei wirst du sehen, dass jedes Spiel auf die gleiche Weise entsteht:

Zuerst hast du eine Idee, dann schreibst du einen Prompt und die KI erstellt den ersten Code.

Anschließend testen wir das Ergebnis und verbessern es Schritt für Schritt.

#### <u>Fassen wir noch einmal zusammen</u>

Du weißt jetzt ,

- wie man LM Studio einrichtet

Außerdem hast du nun

- eine lokale KI, die einsatzbereit ist
