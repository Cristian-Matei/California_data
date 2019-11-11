# Häuser in Kalifornia

In diesem Labor werdet ihr als Data-Analytiker arbeiten. 
Ihr sollt euren Kunden wertvolle informationen über die Preise, Ort,
Wert der Häuser aus Kalifornien liefern und viel mehr!
 

Die Daten
-----
Sie erhalten von den Kunden eine große Datei, namens **housing.csv**.
Diese kann hier gefunden werden:  

Die Datei ist die Darstellung einer Tabelle.
Einige Erklärungen darüber:


* Auf den ersten Zeile findet ihr die Namen der Spalten der Tabelle:
    *  longitude
    *  latitude 
    *  housing_median_age
    *  total_rooms
    *  total_bedrooms
    *  population 
    *  households 
    *  median_income 
    *  median_house_value
    *  ocean_proximity

* In den nächsten Zeilen findet ihr die Werte für die entsprechenden Spalten,
durch Komma getrennt

* Eine Zeile gibt euch die entsprechenden Informationen über ein Distrikt aus Kalifornien an

TODOs
-----

Eure erste Aufgabe is die folgende: eine entsprechende Klasse erstellen die ein Eintrag in
der Tabelle modelliert (aufgepasst bei den Datentypen). Danach sollt ihr die Datei dementsprechen parsen
und eine Liste von Objekte von dem von euch erstellten Typ bauen.

Danach will der Kunde folgendes:
* Findet den Distrikt mit der größten, bzw kleinster Bevölkerung
* Findet den durchschnittlichen Alter und durschnittlichen Einnahmen der Einwohner
* Die Spalte ocean_proximity ist ein kategorischer Attribut. Auf dieser Spalte erscheinen nämlich
nur 5 verschiedene Werte. Identifiziert diese und die Anzahl von Distrikte aus jeder Kategorie
* Report erstellen: sie erhalten von den Kunden ein Intervall für **latitude, longitude** und **median_house_value**. Erstellt in einer 
anderen Textdatei ein Report mit allen Distrikte die dieser Kriterien entsprechen. Gibt eine Fehlermeldung an falls es keine Distrikte gibt die de angegebenen Kriterien entsprechen. Die Werte sollen durch ein Leerzeichen getrennt werden.



Anforderungen
-------------

In diesem Labor sind normale _for_-Schleifen nicht erlaubt. Keine Sorge! List comprehensions und
Funktionen wie _map, filter, reduce_ stehen euch zur Verfügung!

Was damit gemeint wird:
```
 #nicht erlaubt

 numbers = [1, 2, 3, 4]
 quadrate = []
 for i in numbers:
     numbers.append(i**2)

 #viel besser

 numbers = [1, 2, 3, 4]
 quadrate = [i**2 for i in numbers]
```

