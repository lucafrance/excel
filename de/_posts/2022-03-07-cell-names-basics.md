---
title: Zell-Namen Grundlagen
tags: [Namen]
---

Durch die Verwendung von Namen können Formeln viel einfacher verstanden und verwaltet werden.
Namen können für Zellbereiche, Funktionen, Konstanten oder Tabellen festgelegt werden. 
Sobald ein Name festgelegt wurde, ist dieser für die ganze Arbeitsmappe gültig und kann jederzeit aktualisiert und umbenannt werden.

Hier ist ein Beispiel einer Formel mit und ohne Namen.
Mit Namen werden konkrete Beschreibungen der Werte gezeigt, statt abstrakte Adressen der Zellen.

> ![]({{ site.baseurl }}/assets/2022/cell-names-basics/101-formula-no-names-de.png)
> Formel ohne Namen

> ![]({{ site.baseurl }}/assets/2022/cell-names-basics/102-formula-with-names-de.png)
> Formel mit Namen
​​​​​​​

## Benennen einer Zelle

1. Wähle die Zelle aus, der ein Name gegeben werden soll.
1. Gib der Zelle im Namenfeld einen Namen, dann mit der Eingabetaste bestätigen.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/201-define-name-de.png)

Man kann keine Leerzeichen für Zellen-Namen verwenden.
Alternativ kann man ein Unterstrich (z.B. `Anzahl_verkaufte_mangos`) oder die Binnenmajuskel verwenden (z.B. `AnzahlVerkaufteMangos`).

## Verwenden von Namen in Formeln​​​​​​​

Um eine Name in eine Formel zu verwenden braucht man nur diese einzutippen.
Mit der ersten Buschstaben werden mögliche Vorschläge gezeigt, diese können durch `Tab` oder Klicken bestätigt werden.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/301-name-in-formulas-1-de.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/302-name-in-formulas-2-de.png)

## Verwalten von Namen

Namen sind mit dem *Namens-Manager* zu verwalten.
Man kann den über `Formeln` > `Namens-Manager` oder mit der Tasten-Kombination `Strg` + `F3`.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/401-name-manager-on-ribbon-de.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/402-name-manager-de.png)

Mit `Bearbeiten` kann eine Name (Feld `Name:`) und der entsprechende Zellen-Bezug (Feld `Bezieht sich auf:`) geändert werden.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/403-edit-button-de.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/404-edit-window-de.png)

Mit `Löschen` kann man die Name löschen.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/405-delete-buton-de.png)

Sollte man die Name schon in einer Formel verwendet haben, so wird ein `#NAME?`-Fehler gezeigt.
Um diesen zu entfernen muss man die Name neu definieren oder in der Formel ersetzen.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/406-name-error-de.png)

## Spalten-Namen und die Bedeutung des @-Zeichens

Durchs selektieren einer Spalte ist es möglich die Name auch für diese so bei einer einzigen Zelle zu definieren.

![]({{ site.baseurl }}/assets/2022/cell-names-basics/501-define-column-name-de.png)

Durch Verwendung des @-Zeichens in Verbindung mit einem Spaltennamen, zieht Excel das Ergebnis aus dieser Spalte und der Zeile, in der sich die Formel befindet.

​​​​​​​
![]({{ site.baseurl }}/assets/2022/cell-names-basics/502-at-column-name-1-de.png)

![]({{ site.baseurl }}/assets/2022/cell-names-basics/503-at-column-name-2-de.png)

**Hinweis** Die Verwendung des @-Zeichens gilt ab Office 2019. 
Für älteren Office-Versionen funktioniert der Befehl ohne @-Zeichen identisch. ​​​​​​​

## Download

- [Beispiel]({{ site.baseurl }}/assets/2022/cell-names-basics/01-cell-names-basics-example-de.xlsx)

## Verlinkungen

- [Microsoft Support - Definieren und Verwenden von Namen in Formeln](https://support.microsoft.com/de-de/office/definieren-und-verwenden-von-namen-in-formeln-4d0f13ac-53b7-422e-afd2-abd7ff379c64)
