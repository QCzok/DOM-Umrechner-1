# DOM-Umrechner-1

Jetzt wollen wir einen Umrechner schreiben, der Kilometer eingeben lässt und die entsprechende Entfernung in Meilen anzeigt.

## Aufbau
Wir benötigen eine `index.html`, eine `style.css` und eine `index.js`.

Verbinde die Dateien miteinander wie in der letzten Übung.

Diesmal wirst du auch das CSS Stylesheet brauchen (oder SASS wem das lieb ist).

## Formular
Arbeite nun an deinem Formular.

Mit dem Formular kann ein Anwender eine Entfernung in Kilometern eintragen.

Am Ende wird ihm die Entfernung in Meilen angezeigt.

Es gibt folgende Eingabefelder:
* Entfernung (number, eingabepflichtig, Minimum: 0)

Dein Formular hat ebenfalls einen Paragraphen ohne Text. Der Paragraph dient als Platzhalter für die Ergebnisausgabe. Gebe dem `<p>` Tag eine ID.

Dein Formular braucht noch einen Submit Button

## Style
Zentriere dein Formular in der Mitte des Bildschirmes

Benutze dazu die Flexbox.

## JavaScript
Deine JavaScript soll die Funktion `run()` verfügen.

Verknüpfe sie im Formular unter `action` mit dem Wert `javascript:run()`.

Speichere in der Funktion nun die Entfernung aus dem Formularfeld in einer Variablen ab und parse sie in eine Zahl.

Berechne zuletzt die Entfernung in Meilen und gebe das Ergebnis im Paragraphen aus.
