---
title: Tabellen Grundlagen
tags: [Tabellen, Namen]
---

## Eine Tabelle erstellen

*Tabelle* ist ein allgemeiner Begriff, der ist aber auch der Name einer spezifischen Funktionalität in Excel.
Die folgende Berechnungen könnten zum Beispiel Tabelle genannt werden, die sind aber noch nicht eine *Tabelle* im Sinne von Excel 

![]({{ site.baseurl }}/assets/2022/tables-basics/101-example-cell-range-de.png)

Um eine Tabelle zu erstellen selektiert man den entsprechenden Zellen-Bereich und klickt auf `Start` > `Als Tabelle formatieren`.

![]({{ site.baseurl }}/assets/2022/tables-basics/102-table-button-on-ribbon-de.png)

Man kann eine beliebige Tabellenformatvorlage auswählen.
Alle bieten die gleiche Funktionalitäten an und können nachträglich geändert werden.

![]({{ site.baseurl }}/assets/2022/tables-basics/103-table-template-menu-de.png)

Der Zellen-Bereich kann nach Bedarf noch angepasst werden.
Wenn man den korrekten Bereich schon selektiert hatte, kann man direkt `OK` klicken.

![]({{ site.baseurl }}/assets/2022/tables-basics/104-confirm-range-de.png)

## Haupt-Vorteile von Tabellen 

### Vereinfachte Formel-Erstellung

Die Überschiften werden mit einer Tabelle automatisch übernommen und können in Formeln direkt verwendet werden.
Die so erstellten Formeln sind somit leichter nachzuvollziehen. 

> Formel mit Tabelle
> ![]({{ site.baseurl }}/assets/2022/tables-basics/201-formula-with-table-de.png)

> Formel ohne Tabelle
> ![]({{ site.baseurl }}/assets/2022/tables-basics/202-formula-without-table-de.png)

### Automatische Filter und Sortierung

Mit einer Tabelle wird automatisch einen *Filter* für jede Spalte erstellt.

![]({{ site.baseurl }}/assets/2022/tables-basics/301-sort-filter-table-de.png)

Das ist der gleiche Filter, der man über `Start` > `Sortieren und Filtern` > `Filtern` erstellen kann. 
Es ist zu empfehlen, sobald Filter gesetzt werden, aus den entsprechenden Daten Tabellen zu generieren.
Somit bekommt man alle Vorteile der Tabelle direkt mit.

## Der Tabellenentwurf-Reiter

Nachdem eine Tabelle erstellt wurde und man eine Zelle dieser selektiert, erscheint im Menu der Reiter `Tabellenentwurf`.

![]({{ site.baseurl }}/assets/2022/tables-basics/401-ribbon-table-de.png)

### Der Tabelle-Name

Jede Tabelle bekommt automatisch einen Name, der im Namens-Manager mit anderen Zellen-Namen auftaucht.
Im Vergleich mit anderen Namen kann man das Feld `Bezieht sich auf` nicht bearbeiten, da dies mit der Tabelle verbunden ist.

![]({{ site.baseurl }}/assets/2022/tables-basics/501-table-in-name-manager-de.png)

Der Tabelle-Name kann unten `Tabellenentwurf` > `Eigenschaften` geändert werden.

![]({{ site.baseurl }}/assets/2022/tables-basics/502-ribbon-table-properties-de.png)

### Die Ergebniszeile

Man kann eine Ergebniszeile unten `Tabellenentwurf` > `Tabellenformatoptionen` erstellen.

![]({{ site.baseurl }}/assets/2022/tables-basics/601-checkbox-total-row-de.png)

Hiermit kann für jede Spalte separat eine Berechnung erfolgen z.B. Summe, Mittelwert, Maximum. 

![]({{ site.baseurl }}/assets/2022/tables-basics/603-total-operation-drop-down-de.png)

Sind Filter für eine oder mehrere Spalten dieser Tabelle gesetzt, werden nur Zahlen in der Berechnung zur Ergebnisspalte berücksichtigt, die dem Filter entsprechen.
Hier ist ein Beispiel mit dem Mittelwert des Einheitspreises und die Summe des Gesamtspreises.

> Alle Zeilen
> ![]({{ site.baseurl }}/assets/2022/tables-basics/604-subtotal-without-filter-de.png)

> Nach 2022 gefiltert
> ![]({{ site.baseurl }}/assets/2022/tables-basics/605-subtotal-with-filter-de.png)

## Download

- [Beispiel]({{ site.baseurl }}/assets/2022/tables-basics/01-tables-basics-example-de.xlsx)
