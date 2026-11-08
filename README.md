# forContext Lens

Farbe, Schnitt und Ton eines Spielfilms, im Browser gelesen. Die gesamte
Laufzeit erscheint als eine Fläche, die sich bis zum einzelnen Filmbild
aufziehen lässt.

### [→ forContext Lens öffnen](https://tkreten.github.io/forContextLens/)

Ein Werkzeug des Projekts **forContext** am Institut für Digital Humanities
der Georg-August-Universität Göttingen.

## Was das Werkzeug kann

- **Der ganze Film auf einen Blick:** ein Farbbarcode der gesamten Laufzeit
  mit der Lautstärke darüber, stufenlos zoombar bis zu den einzelnen
  Filmbildern.
- **Schnitt:** erkannte Einstellungsgrenzen, durchschnittliche und mittlere
  Einstellungslänge (ASL, MSL), Standardabweichung, Schnitte pro Minute und
  der Schnittrhythmus über die Laufzeit.
- **Farbe und Bewegung:** Helligkeit, Sättigung, Kontrast und Farbtemperatur
  je Bild, die mittlere Farbe je Einstellung und die Bewegung zwischen
  aufeinanderfolgenden Bildern.
- **Annotation:** Momente und Passagen markieren, mit Notizen und Kategorien
  versehen und einzeln abspielen.
- **Exporte:** Analyseblatt als PNG und PDF, Barcode und Einzelbilder,
  Messreihen und Marken als CSV, ELAN (EAF), WebVTT, Schnittliste (EDL) und
  W3C Web Annotation. Jeder Export nennt Datei, Prüfsumme und
  Analyseparameter.
- **Sitzungen:** Eine Analyse lässt sich als Datei sichern und später wieder
  öffnen, ohne den Film erneut zu analysieren.

## Datenschutz

Der Film verlässt den eigenen Rechner nicht. Es gibt keinen Upload und keinen
Server, der Filme verarbeitet. Die gesamte Analyse läuft im Browser. Marken
und Notizen werden nur im Browser gespeichert und lassen sich im Tool
jederzeit löschen. Die Website lädt nichts von fremden Servern.

Beim Aufruf der Seite protokolliert GitHub Pages die IP-Adresse aus
Sicherheitsgründen. Näheres steht im Datenschutzhinweis im Tool.

## Voraussetzungen

- Ein aktueller Browser mit WebGL2 und WebCodecs: Chrome oder Edge, Safari
  ab Version 16.4, Firefox ab Version 130.
- Eine eigene Filmdatei, am besten MP4 mit H.264. Andere Formate wie MKV oder
  WebM werden langsamer und gröber gelesen. Die Schnittzahlen gelten dann als
  nicht belastbar und werden im Tool so gekennzeichnet.

## Erste Schritte

1. Das Tool öffnen und „Film öffnen“ wählen oder die Filmdatei ins Fenster
   ziehen.
2. Nach wenigen Sekunden steht ein erster Barcode. Die vollständige Analyse
   läuft im Hintergrund weiter, gearbeitet werden kann sofort.
3. Ziehen bewegt, Scrollen zoomt. In der Marken-Spur über dem Ton markiert
   eine aufgezogene Strecke eine Passage, die Taste M einen Moment.
4. Die Taste ? zeigt alle Tastenkürzel. „Legende“ unter dem Barcode erklärt,
   was der Streifen zeigt.
5. „Sichern“ speichert die Sitzung als Datei.

## Impressum und Datenschutz

[Impressum](https://tkreten.github.io/forContextLens/#impressum) ·
[Datenschutzhinweis](https://tkreten.github.io/forContextLens/#datenschutz)

## Über dieses Repository

Dieses Repository enthält die veröffentlichte Website von forContext Lens in
Version 1.0.0.
