SEW | ADV | JavaScript Functions

## User Story 1
*As a sales person I want to easily check, if a given EAN/GTIN code is valid.*

### Acceptance Criteria
- 

Handelsartikel werden durch EAN/GTIN-Codes identifiziert. Jede solche Artikelnummer ist mit einer Prüfziffer fehlergesichert. 
Schreibe eine Funktion istEan(artNum), um eine Artikelnummer (die als Zahl oder String vorliegt) zu überprüfen. Für korrekte Artikelnummern liefert die Funktion true, in allen anderen Fällen false. 
Teste die Funktion an Hand von EAN-Codes aus deiner Umgebung.


Gewünscht ist eine Funktion staerke(pw) zum Abschätzen der „Stärke“ eines Passworts im Verhältnis zur Stärke anderer Passworte. Als Maß für die Stärke liefert die Funktion eine positive Zahl. 
Ein Passwort ist umso stärker,
je länger es ist,
je mehr verschiedene Arten von Zeichen (Klein-, Großbuchstaben, Ziffern, Sonderzeichen) darin vorkommen,
je weniger „vorhersehbar“ die Zeichenfolge ist.


Schreibe eine Funktion rot13(text), die den übergebenen String ROT13-„verschlüsselt“. Groß- und Kleinschreibung sollen beibehalten werden.
Ist das Argument kein String, so wird es vor der Umkehrung in einen String konvertiert.
Versuche, mehrere Implementierungsvarianten zu finden.


Schreibe eine Funktion testen(fu, arg, erwartet) zum Testen einer Funktion fu. 
testen soll die Funktion fu mit dem Argument arg aufrufen und ihren Rückgabewert mit dem erwarteten Ergebnis erwartet vergleichen. Stimmen die beiden Werte nicht überein, so sollen sie mit einer entsprechenden Meldung auf der Konsole ausgegeben werden.


Der Funktion erzeugen(op) wird eine Grundrechenart op als String übergeben ('+', '-', '*' oder '/'). 
erzeugen() soll eine neue Funktion liefern, die man mit zwei Zahlen aufrufen kann. Die Funktion soll die Grundrechenart auf die beiden Zahlen anwenden und das Ergebnis liefern. 
Beispiel:
    const mult = erzeugen('*')
    console.log(mult(3, 4))   // gibt auf der Konsole 12 aus
    
    
#### Links
- https://en.wikipedia.org/wiki/International_Article_Number
- https://my.skilldisplay.eu/en/skillset/592
