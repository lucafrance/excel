---
title: Zahlenformate Grundlagen
tags: [Zahlenformate]
---

## Was sind Zahlenformate?

Wenn man `0,5`, `50%`, `12:00` Uhr, `€0,50` in Excel summiert, bekommt man `2`.
Warum?
Für Excel sind die alle der gleiche Wert.

![]({{ site.baseurl }}/assets/2022/number-format-basics/101-sum-one-half-de.png)

Excel kennt nur zwei Arten Daten: Text und Nummern.
Text ist Text, alles der Rest sind Nummern.
- Eine Zahl ist eine Nummer.
- Eine Währung ist eine Nummer.
- Ein Datum ist eine Nummer.
- Eine Uhrzeit ist eine Nummer.
- Ein Prozent ist eine Nummer.

Excel speichert, liest und berechnet Nummern.
Die Darstellungsart der Nummer (Zahlenformat) ist eine separate Eigenschaft der Zelle.
Ähnlich zur Farbe der Zelle, hat das Zahlenformat wenig mit dem entsprechenden Wert zu tun.

| Wert | Art | Mögliche Darstellung mit Zahlenformat |
| --- | --- | --- |
| abcdefg | Text | abcdefg |
| abc123 | Text | abc123 |
| 44628,61624 | Nummer | 08.03.2022 14:51 |
| 0,121099472 | Nummer | 12% |
| 4827,611261 | Nummer | 4.827,61 |
| 29,91 | Nummer | 29,91 € |

## Zahlenformate anpassen

Es gibt zwei Wege ein Zahlenformat anzupassen.
1. Über `Start` > `Zahl`.
![]({{ site.baseurl }}/assets/2022/number-format-basics/201-ribbon-number-de.png)
1. Über das `Zellen formatieren` Fenster mit `Rechter Mausklick` > `Zellen formatieren...` oder Tastenkombination `Strg` + `1`.
![]({{ site.baseurl }}/assets/2022/number-format-basics/202-context-menu-number-de.png)

Über `Start` > `Zahl` sind meistens der Kategorien Verfügbar, aber nicht alle Optionen des `Zellen formatieren`-Fenster.

![]({{ site.baseurl }}/assets/2022/number-format-basics/203-format-categories-ribbon-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/204-cell-format-window-de.png)

## Grund-Zahlenformate

### Standard-Zahlenformat

Das ist das standard Format.
Es gibt keine Optionen.

![]({{ site.baseurl }}/assets/2022/number-format-basics/301-dropdown-standard-category-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/302-window-standard-category-de.png)

### Zahl-Zahlenformat

![]({{ site.baseurl }}/assets/2022/number-format-basics/401-dropdown-number-category-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/402-window-number-category-de.png)

Mit diesem Zahlenformat kann man Tausender-Trennzeichen und Dezimalstellen definieren.

**1000er-Trennzeichen verwenden**

![]({{ site.baseurl }}/assets/2022/number-format-basics/403-ribbon-thousands-separator-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/404-window-thousands-separator-de.png)

**Dezimalstellen hinzufügen oder entfernen**

![]({{ site.baseurl }}/assets/2022/number-format-basics/405-ribbon-decimal-places-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/406-window-decimal-places-de.png)

### Währung- und Buchhaltungs-Zahlenformat

In der Praxis ähnlich zur Zahl-Zahlenformat, mit Währungssymbol vorne.
Generell empfehle ich das Buchhaltungsformat statt Währung anzuwenden.

![]({{ site.baseurl }}/assets/2022/number-format-basics/501-ribbon-accounting-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/502-dropdown-accounting-de.png)

Man definiert die Dezimalstellen wie mit dem Zahl-Zahlenformat und das Währung-Symbol.

![]({{ site.baseurl }}/assets/2022/number-format-basics/503-window-accounting-de.png)

Die Währungsart spielt keine Rolle für Excel, man kann Währungen beliebig mischen.
Hier z.B. wird Euro mit Pfund Sterling, US-Dollar und Bitcoin summiert.

![]({{ site.baseurl }}/assets/2022/number-format-basics/504-sum-different-currencies-de.png)

### Prozent-Zahlenformat

Das %-Symbol bedeutet "durch 100 geteilt".
Für Excel ein Prozent ist eine normale Nummer mit der Dezimalstelle zweimal nach rechts verschoben.

| Prozent | Nummer |
| --- | --- |
| 20%	| 0,2 | 
| 9%	| 0,09 | 
| 30%	| 0,3 | 
| 38%	| 0,38 | 
| 52%	| 0,52 | 
| 2%	| 0,02 | 
| 63%	| 0,63 | 
| 16%	| 0,16 | 
| 26%	| 0,26 | 
| 84%	| 0,84 | 
| 26%	| 0,26 | 
 
Wenn man ein wert direkt mit dem Prozent-Symbol eingibt, wird das Prozent-Format direkt angewandt.

![]({{ site.baseurl }}/assets/2022/number-format-basics/601-percent-input-cell-de.png)

Alternativ kann man das Prozent-Format für eine existiere Nummer definieren.

![]({{ site.baseurl }}/assets/2022/number-format-basics/602-ribbon-percentage-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/603-dropdown-percentage-de.png)

![]({{ site.baseurl }}/assets/2022/number-format-basics/604-window-percentage-de.png)

## Download

- [Beispiel]({{ site.baseurl }}/assets/2022/number-format-basics/01-number-format-basics-example-de.xlsx)

## Verlinkungen

- [Microsoft Support - Verfügbare Zahlenformate in Excel](https://support.microsoft.com/de-de/office/verf%C3%BCgbare-zahlenformate-in-excel-0afe8f52-97db-41f1-b972-4b46e9f1e8d2)
