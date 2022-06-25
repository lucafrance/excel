---
title: SUMME und MITTELWERT Funktionen
tags: [SUMME, MITTELWERT, Tabellen]
last_update: 2022-06-25
---

## Funktion SUMME

Die `SUMME`-Funktion kann einen Zell-Bereich als Argument benutzen.

![]({{ site.baseurl }}/assets/2022/sum-average/101-sum-one-range-de.png)

Durch die Abtrennung mittels Semikolon können auch mehrere Bereiche unterschiedlicher Größen verwendet werden.

![]({{ site.baseurl }}/assets/2022/sum-average/102-sum-more-ranges-de.png)


## SUMME mit Tabellen

Mit Tabellen kann man man leicht eine gesamte Spalte als Argument angeben.

> Schreib `=SUMME(`.
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/201-sum-table-step1-de.png)
>
> Selektiere eine Zelle aus der zu summierenden Spalte.
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/202-sum-table-step2-de.png)
> 
> Druck `Strg` + `Leertaste`, die gesamte Spalte wird selektiert.
> 
> ![]({{ site.baseurl }}/assets/2022/sum-average/203-sum-table-step3-de.png)
>
> Fertig
>
> ![]({{ site.baseurl }}/assets/2022/sum-average/204-sum-table-step4-de.png)

Bei neuen oder gelöschten Zeilen der Tabelle bleibt die Formel dennoch gleich und gültig.
Das wäre ohne Tabelle in der Regel nicht der Fall.

![]({{ site.baseurl }}/assets/2022/sum-average/301-sum-table-few-row-de.png)
![]({{ site.baseurl }}/assets/2022/sum-average/302-sum-table-many-rows-de.png)

## Funktion MITTELWERT

`MITTELWERT` funktioniert ähnlich zur `SUMME`.

**`MITTELWERT` auf einem Bereich**

![]({{ site.baseurl }}/assets/2022/sum-average/401-average-one-range-de.png)

**`MITTELWERT` auf mehreren Bereiche**

![]({{ site.baseurl }}/assets/2022/sum-average/402-average-more-ranges-de.png)

**`MITTELWERT` auf eine Tabelle**

![]({{ site.baseurl }}/assets/2022/sum-average/403-average-table-de.png)

## Download

- [Beispiel]({{ site.baseurl }}/assets/2022/sum-average/01-sum-average-example-de.xlsx)
- [Übung]({{ site.baseurl }}/assets/2022/sum-average/02-sum-average-exercise-de.xlsx)
- [Lösung]({{ site.baseurl }}/assets/2022/sum-average/03-sum-average-solution-de.xlsx)

## Verlinkungen

- [Microsoft Support - SUMME (Funktion)](https://support.microsoft.com/de-de/office/summe-funktion-043e1c7d-7726-4e80-8f32-07b23e057f89)
- [Microsoft Support - MITTELWERT (Funktion)](https://support.microsoft.com/de-de/office/mittelwert-funktion-047bac88-d466-426c-a32b-8f33eb960cf6)
