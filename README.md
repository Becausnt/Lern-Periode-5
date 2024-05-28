# Lern-Periode 5

23.04 bis 25.06.2024

## Grob-Planung

1. Mit meinen Noten bin ich aktuell zufrieden. Besonders gut war ich im SQL-Modul und im "Aufträge Ausführen" Modul. Ungenügend war ich in keinem Modul. Als besonders wichtig habe ich das Modul "Ausfträge Ausführen" (431) und das Modul mit den Programmiergrundlagen (319), in welchem ich auch gut war.
2. Als VBV hatte ich, dass ich meine Ziele am Anfang der LB ein wenig grober setzen sollte, so dass ich das Projekt entweder minimal (falls etwas dazwischen kommt oder viele Prüfungen angesagt werden) oder aber auch noch beliebig ausweiten kann.
4. Als geeignetes Projekte für diese LB empfinde ich: Eine Quiz-Website und {zweites Projekt}

## 23.04.2024
Heute habe ich in Figma ein grobes Design der Landing-Page meiner Website entworfen.

![Quizzes](https://github.com/Becausnt/Lern-Periode-5/assets/142886938/827bb0ca-fdf6-4e90-a3fa-b92497e7b035)

Danach habe ich dieses Teilweise umgesetzt. Dies ist in dem hier verfügbaren HTML und CSS File ersichtlich.



## 30.04.2024

- [x] Herausfinden wie ich einen spezifischen Schriftartentyp auf alles in der Website anwenden kann. (habe es schon in den body-tag gepack, aber das hat irgendwie nicht funktioniert.)
- [x] Navbar fertigstellen
- [x] links zu anderen seiten hinzufügen.
- [x] login page anfangen (noch keine funktion)

### Zusammenfassung
Heute habe ich herausgefunden das der schrift Tag den ich in body {} gepackt habe offenbar trotzdem funktioniert. Ich habe den Navbar fertiggestellt, es hat einige Links zur Startseite, da ich noch nicht viel anderes gemacht habe. Zudem hat es einen Login-Button. Dieser führt zu einem Login-Form. Das Login-Form funktioniert noch nicht. Ich hatte ein wenig Schwierigkeiten beim stylen des Forms, aber sonst gin alles gut.

## 07.05.2024
### Zusammenfassung
Heute habe ich nicht an meinen Arbeitspacketen gearbeitet, da ich für das Modul 106 noch die Portfolioarbeit machen musste. Mit dieser bin ich jetzt aber fertig geworden. Ich verschiebe deshalb die Arbeitspackete von heute auf das nächste Mal.

## 21.05.2024
- [x] Einen Footer mit links und credits hinzufügen
- [x] Contact Seite anfangen
- [x] Formspree integrieren
- [ ] falls genug zeit, einen Effekt zu den Quizkarten auf der Homepage hinzufügen

### Zusammenfassung
Heute habe ich einen Footer zu meiner website hinzugefügt. Bei diesem habe ich mich zu lange mit meinem Browser bekämpft, da ich es nicht hinbrachte eine Liste zu zentrieren. Schlussendlich hat es dann aber doch funktioniert. Aus mir unerklärlichen Gründen bewirkt all das hier:
```CSS
.footer .row {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .footer .row ul {
        display: inline-block;
        list-style-type: none;
        padding: 0;
        margin: 0;
        display: inline-block;
    }
```
nichts wenn im `.footer .row .ul ` noch ein `width: 100%;` ist.
Danach habe ich ein Kontaktformular erstellt, welches zwar dem Login ähnlich ist, aber eine `textarea` anstatt eines `input`s benutzt. Bei diesem musste ich resize deaktivieren, da die Grösse meines Formular-Containers nicht mit der Grösse der `textarea` verknüpft ist. Danach habe ich noch Formspree zum Contact-Form hinzugefügt. Bei diesem hatte ich keine Probleme, aber ein schönes feature wäre, wenn es beim submit nicht auf die Formspree-Seite weiterleiten würde.

## 28.05.2024

- [x] Seite der Quizkarten hinzufügen
- [x] Diese Seite Designen
- [ ] Lernen wie das eine Quizkartenfunktionalität mit JS hinzugefügt werden kann (Einführung JS)
- [ ] Lernen wie man mit JS Webseiteninhalte verändern kann.

### Zusammenfassung
Heute habe ich die Quiz-Seite hinzugefügt, mehr Designs von Quizlet permanent ausgeliehen und mit Herr Colic meine Webseite besprochen. Ich habe die möglichkeit hinzugefügt eine Quiz-Karte zu drehen mithilfe der `:target` _methode?_ . Ich habe nun noch nichts mit JS gemacht, aber ich denke das wäre schon noch praktisch, da das ganze mit `target` sehr mühsam werden kann.

## Nächstes mal

- [ ] Drehanimation zu Karteikarte hinzufügen
- [ ] Quiz-Seite fertig programmieren
- [ ] Grundlagen von JS lernen und ein Script einbinden
- [ ] Quizkarten mit JS programmieren


