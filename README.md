# BMI & Tagesbedarf

**BMI, Grundumsatz und täglicher Energiebedarf für die Pflegeausbildung — Werte einstellen, Ergebnis und Rechenweg live mitsehen**

[![Code: MIT](https://img.shields.io/badge/Code-MIT-green.svg)](LICENSE) [![Inhalte: CC BY-SA 4.0](https://img.shields.io/badge/Inhalte-CC%20BY--SA%204.0-blue.svg)](LICENSE-CONTENT.md)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue)](https://florianloyns.github.io/bmi-tagesbedarf/)
![Keine Abhängigkeiten](https://img.shields.io/badge/Abh%C3%A4ngigkeiten-keine-brightgreen)
![PWA](https://img.shields.io/badge/PWA-offline--f%C3%A4hig-teal)

Eine browser-basierte App für Pflege-Auszubildende: Body-Mass-Index, Grundumsatz und Tagesbedarf live berechnen. Slider verschieben, fertig — Ergebnis und Rechenweg erscheinen direkt darunter.

**[Jetzt rechnen](https://florianloyns.github.io/bmi-tagesbedarf/)**

## Was die App rechnet

- **BMI** = Gewicht (kg) ÷ Größe (m)² — eingeordnet auf der WHO-Skala mit beweglichem Marker und farbigen Kategorien
- **Grundumsatz** nach Mifflin-St Jeor (1990) — moderner, präziser Standard
- **Tagesbedarf** = Grundumsatz × PAL-Faktor (Physical Activity Level) nach DGE

## Didaktischer Aufbau

Drei Eingabe-Slider (Alter, Größe, Gewicht), ein PAL-Slider mit Pflegealltag-Default und ein biologisches-Geschlecht-Toggle steuern alle drei Berechnungen gleichzeitig. Die WHO-BMI-Skala bewegt sich live mit. Die Erklärungs-Box zeigt Schritt für Schritt jede Formel — mit Bedeutungs-Satz in einfacher Sprache, abstrakter Formel und konkret eingesetzten Zahlen. Ein Info-Popover an der BMI-Karte enthält die komplette WHO-Klassifikation mit allen sechs Kategorien plus Senioren-Korrektur.

## Klinischer Bezug

Der BMI ist Bestandteil der gängigen Mangelernährungs-Screenings **NRS-2002** und **MNA-SF**. Für Senioren über 65 gilt ein höherer Normalbereich (etwa 22–29 kg/m² nach DGE) — ein BMI unter 22 ist im Alter ein Warnzeichen für Mangelernährung.

## Technik

- Einzelne HTML-Datei, Vanilla JavaScript, keine Frameworks, kein Build-Tool
- Kein externes CDN, keine Abhängigkeiten zur Laufzeit
- **PWA**: installierbar auf Desktop und Smartphone, offline-fähig via Service Worker
- Mobile-First-Layout mit `safe-area-inset` für iPhone-Notch und Home-Indicator
- Inline-SVG für die BMI-Skala
- DSGVO-konform: keine Tracker, keine externen Ressourcen, keine Datenübertragung

## Impressum

Verantwortlich: Florian Loyns. Pflichtangaben nach § 5 DDG: [Impressum](https://florianloyns.com/Impressum/)

## Lizenz

[MIT](LICENSE) für den Quelltext · [CC BY-SA 4.0](LICENSE-CONTENT.md) für die didaktischen Inhalte (Fälle, Fragen, Texte, Grafiken).

Nutzen, anpassen und weitergeben ist ausdrücklich erwünscht — auch im kommerziellen Kontext. Bei den Inhalten gilt: Namensnennung und Weitergabe bearbeiteter Fassungen unter denselben Bedingungen.
