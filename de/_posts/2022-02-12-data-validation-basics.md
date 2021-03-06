---
title: Datenüberprüfung Grundlagen
tags: [Datenüberprüfung]
last_update: 2022-06-25
---

`Daten` > `Datenüberprüfung`

![]({{ site.baseurl }}/assets/2022/data-validation/ribbon-data-validation-de.png)

## Erstellen von Dropdown-Listen (häufige Anwendung)


Hiermit können Elemente aus einer vordefinierten Liste ausgewählt werden.

![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-fruits-de.png)

Um diese zu erstellen, klickt man auf `Daten` > `Datenüberprüfung` > `Zulassen` > `Liste` und definiert die Werte im Feld `Quelle`.

![]({{ site.baseurl }}/assets/2022/data-validation/data-validation-settings-list-de.png)

Es gibt zwei Möglichkeiten, Werte einzugeben.

- Man definiert die Werte explizit mittels der *;*-Trennung.
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-explicit-de.png)
- Man wählt einen Zellen-Bereich mit der gewünschten Werten aus.
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-source-1-de.png)
![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-list-source-2-de.png)

Wenn man einen Wert einträgt, der nicht zur Liste gehört, wird eine Fehlermeldung gezeigt.

![]({{ site.baseurl }}/assets/2022/data-validation/dropdown-pineapple-error-de.png)
 

## Andere Arten Daten zulassen (keine Liste)

Die Dropdown-Liste erfüllt 95 % der Anwendungen der Datenüberprüfung-Funktion, aber die Funktion heißt Datenüberprüfung, nicht Dropdown-Liste. 
Man kann andere Arten Datenüberprüfungen definieren, die keine Liste sind und kein Dropdown zeigen. 

### Ganze Zahl zulassen

Man kann z.B. nur ganze Zahlen zwischen *0* und *20* eintragen lassen.
Wenn man eine negative (z.B. *-1*) oder Dezimalzahl einträgt (z.B. *3,7*), dann wird die Fehlermeldung gezeigt.

![]({{ site.baseurl }}/assets/2022/data-validation/whole-number-0-20-de.png)

### Wert zwischen 0 % und 100 % zulassen

Ein Prozent wird von Excel als Nummer interpretiert, z.B. *21 % = 0,21*. 
Man kann deswegen indirekt ein Prozent-Eingabefeld definieren mit der Datenüberprüfung zwischen *0 % = 0*, *100 % = 1* und Zellenformatierung als Prozent.

![]({{ site.baseurl }}/assets/2022/data-validation/percent-0-100-validation-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/percent-0-100-format-de.png)

## Eingabemeldung (nützlich auch ohne Dateneinschränkung)

Wenn man Werte zulässt, die nicht durch eine Liste definiert sind, gibt es i.A. keine Indikation von welchen Werte erlaubt sind.
Man kann eine entsprechende Eingabemeldung unter `Eingabemeldung` definieren.
Diese wird nur gezeigt, wenn man die Zelle selektiert.

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-definition-1-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-example-1-de.png)

Es ist möglich eine Eingabemeldung zu definieren, auch wenn `Jeden Wert` zugelassen wird.
Das ist nützlich um Kommentare über den Inhalt der Zelle einzufügen.

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-definition-2-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/input-message-example-2-de.png)

## Fehlermeldungen

Wenn man einen nicht zugelassenen Wert einträgt, wird eine Standard-Fehlermeldung gezeigt.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-standard-de.png)

Diese kann unten `Fehlermeldung` personalisiert werden, um aussagekräftiger zu sein.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-custom-def-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-custom-msg-de.png)

Man kann andere Arten Fehlermeldung nutzen. 
Diese werden mit `Typ` ausgewählt.
- Stopp
- Warnung
- Informationen

![]({{ site.baseurl }}/assets/2022/data-validation/error-kind-dropdown-de.png)

### Stopp

`Stopp` ist die Standard-Fehlermeldung.

![]({{ site.baseurl }}/assets/2022/data-validation/error-stop-standard-de.png)

- Mit `Wiederholen` wird die Zelle erneut markiert, um Änderungen vorzunehmen. 
- Mit `Abbrechen` wird der aktuelle Eintrag entfernt.
- Mit `Hilfe` wird die [entsprechende Dokumentation](https://support.microsoft.com/de-de/office/anwenden-von-daten%C3%BCberpr%C3%BCfung-auf-zellen-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249) geöffnet.

### Warnung

Mit `Warnung` kann man nach Bestätigung den Wert dennoch eintragen.
Z.B. in der Regel will man ein Datum in der Vergangenheit, aber manchmal wünscht man auch zukünftige Daten.

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-standard-de.png)

- Mit `Ja` bleibt der Eintrag unberührt, auch wenn er die Daten-Zulassung nicht entspricht.
- Mit `Nein` wird die Zelle und dessen derzeitiger Eintrag zur erneuten Bearbeitung markiert. 
- Mit `Abbrechen` wird der aktuelle Eintrag entfernt.
- Mit `Hilfe` wird die [entsprechende Dokumentation](https://support.microsoft.com/de-de/office/anwenden-von-daten%C3%BCberpr%C3%BCfung-auf-zellen-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249) geöffnet.

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-custom-def-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-warning-custom-msg-de.png)

### Informationen

Mit `Informationen` bekommt man nur die Meldung und der Wert wird ohne Bestätigung eingetragen.

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-standard-de.png)

- Mit `OK` wird der aktuelle Eintrag angenommen.
- Mit `Abbrechen` wird der aktuelle Eintrag entfernt.
- Mit `Hilfe` wird die [entsprechende Dokumentation](https://support.microsoft.com/de-de/office/anwenden-von-daten%C3%BCberpr%C3%BCfung-auf-zellen-29fecbcc-d1b9-42c1-9d76-eff3ce5f7249) geöffnet.

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-custom-def-de.png)

![]({{ site.baseurl }}/assets/2022/data-validation/error-information-custom-msg-de.png)

### Fehlermeldung deaktivieren

Man kann entscheiden keine Fehlermeldung anzuzeigen, in meisten Fällen ist dann wie ob es keine Daten-Dateneinschränkung gäbe.

![]({{ site.baseurl }}/assets/2022/data-validation/error-no-message-de.png)

Es ist nützlich um Standard-Optionen als Dropdown-Liste zu zeigen und um trotzdem personalisierte Werte zu ermöglichen.

![]({{ site.baseurl }}/assets/2022/data-validation/error-no-message-example-de.png)

## Download

- [Beispiel]({{ site.baseurl }}/assets/2022/data-validation/01-data-validation-example-de.xlsx)
- [Übung]({{ site.baseurl }}/assets/2022/data-validation/02-data-validation-exercise-de.xlsx)
- [Lösung]({{ site.baseurl }}/assets/2022/data-validation/03-data-validation-solution-de.xlsx)
