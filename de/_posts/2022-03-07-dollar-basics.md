---
title: $-Zeichen Grundlagen
tags: [Dollar-Zeichen]
---

## Ein Zellbezug erstellen

Ein Zellbezug beschreibt die Zuordnung von konkreten Werten in den entsprechenden Eingabefeldern (Zellen).
Der leichteste Zellbezug ist die 1:1 Übertragung des Wertes einer anderen Zelle.
Hier z.B. die Zelle `A4` enthält den Wert `44` und die Zelle `B4` die Formel `=A4`.
Als Ergebnis wird in `B4` auch den Wert `44` gezeigt.

![](/assets/2022/dollar-basics/101-cell-reference.png)

## Relativer Bezug

Der Standrad-Bezug ist ein sogenannter *relativer Bezug*. 
D.h. beim Kopieren/Einfügen der Zelle mit dem Formel wird die Spalte und Zeile des Bezugs entsprechend angepasst.

Hier z.B. die Zelle `G8` enthält die Formel `=A8`.
Wenn man die Zelle `G8` auf dem Bereich `G8:K12` kopiert, wird der Bezug entsprechend angepasst.
Die Zelle `K12` enthält nicht länger die Formel `=A8`, sondern `=E12`.
Die *relative* Distanz des Bezugs ist gleich geblieben: 6 Spalten nach links und gleiche Zeile. 

![](/assets/2022/dollar-basics/102-no-dollar.png)

## Gemischter Bezug

Man kann den Bezug auf die Spalte oder Zeile mit dem $-Zeichen festhalten.
Ein $-Zeichen vor der Buchstabe blockiert den Bezug auf die Spalte, ein $-Zeichen vor der Nummer blockiert den Bezug auf die Zeile.

Hier z.B. die Zelle `G16` enthält die Formel `=$A16`.
Da der $-Zeichen vor der A steht, ändert sich der Bezug auf die Spalte beim kopieren über den Bereich `G16:K20` nicht.
Da es kein $-Zeichen vor dem 16 steht, ändert sich der Bezug auf die Zeile trotzdem.    

![](/assets/2022/dollar-basics/103-dollar-column.png)

Man kann ähnlich den Bezug auf de Zeile mit dem $-Zeichen vor der Nummer festhalten.
Hier z.B. die Zelle `G24` enthält die Formel `=A$24`.
Beim Kopieren von `G24` über den Bereich `G24:K28`, bleibt jetzt die Spalte fest un die Spalte wird angepasst. 

![](/assets/2022/dollar-basics/104-dollar-row.png)

Das ist ein sogenannter *gemischter Bezug*, da die Dimension mit dem $-Zeichen nicht länger relativ ist.

## Absoluter Bezug

Man kann einen *absoluter Bezug* durch den $-Zeichen vor der Buchstabe und Nummer definieren.
So wird der Bezug immer auf die gleiche Zelle Bleiben, unabhängig wovon diese kopiert wird.

Hier z.B. die Zelle `G32` enthält die Formel `=$A$32`.
Der Bezug bleibt jetzt `=$A$32`  über den gesamten Zellen-Bereich `G32:K36`

![](/assets/2022/dollar-basics/105-dollar-column-and-row.png)

## Tastenkombination

Man kann mögliche Kombinationen des $-Zeichens beim wiederholten Drück von `F4` durchgehen.
So braucht man nicht das $-Zeichen manuell auf die richtige Stelle schreiben.

> ![](/assets/2022/dollar-basics/201-dollar-f4-1.png)
>
> `F4` ↓
>
> ![](/assets/2022/dollar-basics/202-dollar-f4-2.png)
>
> `F4` ↓
>
> ![](/assets/2022/dollar-basics/203-dollar-f4-3.png)
>
> `F4` ↓
>
> ![](/assets/2022/dollar-basics/204-dollar-f4-4.png)
>
> `F4` ↓
>
> ![](/assets/2022/dollar-basics/201-dollar-f4-1.png)

## Download

- [Beispiel](/assets/2022/dollar-basics/01-dollar-basics-example-de.xlsx)

## Verlinkungen

- [Microsoft Support - Erstellen oder Ändern eines Zellbezugs](https://support.microsoft.com/de-de/office/erstellen-oder-%C3%A4ndern-eines-zellbezugs-c7b8b95d-c594-4488-947e-c835903cebaa)
- [Microsoft Support - Wechseln zwischen relativen, absoluten und gemischten Bezügen](https://support.microsoft.com/de-de/office/wechseln-zwischen-relativen-absoluten-und-gemischten-bez%C3%BCgen-dfec08cd-ae65-4f56-839e-5f0d8d0baca9)
