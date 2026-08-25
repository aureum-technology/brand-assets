# Aureum Technology GmbH · Brand Assets

`FORMBLATT AT-B01 · MARKENELEMENTE` `REV. 2026-B` `STAND 25.08.2026`

Logos, Farbwerte und Schriften der Aureum Technology GmbH.
Gedacht für Presse, Partner, Verzeichnisse und alle, die uns korrekt darstellen wollen.

**Kurz für Eilige:** Druckerei bekommt die SVG aus `/logo/`. Profilbild bei
Google oder LinkedIn: das PNG aus `/profil/`. Farbwerte stehen unter 02.

---

## 00 / Unternehmen

| | |
|---|---|
| Firma | Aureum Technology GmbH |
| Sitz | Straße der Jugend 5, 08228 Rodewisch |
| Register | Amtsgericht Chemnitz, HRB 35602 |
| USt-ID | DE362284348 |
| Web | https://aureum-tech.com |
| Telefon | +49 3744 4399760 |

IT-Betreuung für Betriebe, Praxen und Vereine im Vogtland. Netzwerke, Server,
Arbeitsplätze und Datensicherung. Dazu Computerhilfe für Privatkunden.

Die Telefonnummer bitte genau in dieser Schreibweise übernehmen. In
Verzeichnissen zählt jede Abweichung als eigene Angabe.

---

## 01 / Schreibweise

Richtig ist **Aureum Technology GmbH**. Im Fließtext kurz **Aureum Technology**.

Nicht: AUREUM TECHNOLOGY, Aureum-Technology, Aureum Tech, aureum technology.

---

## 02 / Farben

| Farbe | Hex | RGB | CMYK | Pantone | Verwendung |
|---|---|---|---|---|---|
| Dunkel | `#0D141F` | 13, 20, 31 | 85 / 70 / 50 / 60 | 5255 C | Schrift, Logo, Rahmen |
| Gold | `#C9A227` | 201, 162, 39 | 20 / 33 / 100 / 5 | 7555 C | Akzent am Kontaktpunkt |
| Papier | `#F1F4F7` | 241, 244, 247 | — | — | Flächen, Hintergrund |
| Grau | `#5C646E` | 92, 100, 110 | — | — | Sekundärtext, Beschriftungen |

Gold ist ein Akzent, keine Flächenfarbe. Es markiert einen Punkt, nie einen
Hintergrund.

**CMYK und Pantone sind umgerechnet, nicht gemessen.** Muss die Farbe exakt
sitzen, etwa bei Textil oder größerer Auflage, lassen Sie einen Andruck oder
einen Fächerabgleich machen. Gold verschiebt sich auf Stoff.

Zum Einlesen: `farben/aureum.gpl` für Inkscape, GIMP und Krita,
`farben/farben.css` fürs Web, `farben/farben.json` für alles andere.

---

## 03 / Schriften

| Rolle | Schrift | Bezug |
|---|---|---|
| Überschriften | Archivo (640) | Google Fonts, SIL Open Font License |
| Fließtext | Archivo (400, 500) | Google Fonts, SIL Open Font License |
| Technische Beschriftungen | IBM Plex Mono (400, 500) | Google Fonts, SIL Open Font License |

**Für die Logodateien wird keine Schrift gebraucht:** Der Schriftzug ist in
Vektorpfade umgewandelt. Näheres in `schriften/LIESMICH.md`.

---

## 04 / Logo

Die Marke besteht aus dem Quadrat mit Goldpunkt und dem Schriftzug.
Beides gehört zusammen. Das Quadrat allein ist nur als Bildmarke zulässig,
etwa als Profilbild oder Favicon.

**Schutzraum:** rundherum mindestens die Höhe des Goldpunkts freilassen.

**Mindestbreite:** 60 mm für die Querform. Darunter läuft die Unterzeile
„TECHNOLOGY GMBH · RODEWISCH" auf Stoff zu — dann die gestapelte Form oder die
Bildmarke allein nehmen.

**Nicht erlaubt:** Farben ändern, verzerren, drehen, Schatten oder Rahmen
hinzufügen, auf unruhigen Hintergründen platzieren, den Schriftzug nachbauen
oder ersetzen.

Auf dunklem Grund die helle Variante verwenden, auf hellem Grund die dunkle.

### Gold auf dunklem Grund

Die Variante `…-weissgold` ist zweifarbig: alles weiß, nur der Kontaktpunkt
gold. Der Druckerei zwei Dinge mitgeben:

1. **Weiße Unterlage unter das Gold.** Ohne sie zieht der dunkle Stoff die
   Farbe an und das Gold wird stumpfbraun statt metallisch. Bei DTF- und
   Transferdruck geschieht das von selbst, im Siebdruck ist es ein eigener
   Druckgang und muss angesagt werden.
2. **Zwei Farben statt einer** kosten im Siebdruck etwas mehr Einrichtung. Bei
   kleiner Auflage oder Digitaldruck fällt das nicht ins Gewicht.

Bei Stick statt Druck: die SVG geben und die Unterzeile weglassen. Mono-Schrift
lässt sich in dieser Größe nicht sauber sticken.

---

## 05 / Dateien

```
/logo/         Querform, gestapelt, Wortmarke, Bildmarke — je SVG und PNG
/profil/       Profilbilder, Kacheln, runde Bildmarke — für Plattformen
/favicon/      Icons für Web und Anwendungen
/farben/       Farbwerte als Palette (GPL, CSS, JSON)
/schriften/    Bezugsquellen und Gewichte
```

**SVG ist das Ausgangsformat.** PNG nur nehmen, wenn SVG nicht geht — die PNG
liegen 3000 px breit (Logo, Bildmarke, Wortmarke) und 1000 px (rund, Profil).

### Welche Datei wofür

| Wenn … | dann |
|---|---|
| die Druckerei nach dem Logo fragt | **SVG** aus `/logo/`, immer |
| ein Portal nur PNG annimmt | `…-3000px.png` |
| heller Grund | `…-farbig` oder `…-schwarz` |
| dunkler Grund, Gold soll dabei sein | `…-weissgold` |
| dunkler Grund, einfarbig | `…-weiss` |
| Siebdruck mit einer Farbe | `…-schwarz` bzw. `…-weiss`, spart einen Druckgang |
| schmale Fläche, Brustdruck | `aureum-logo-gestapelt-…` |
| breite Fläche, Banner | `aureum-logo-quer-…` |
| Kappe, Aufkleber, Ärmel | `aureum-bildmarke-…` |
| Profil bei Google, LinkedIn, Facebook | `profil/aureum-profilbild-hell` oder `-dunkel`, als PNG |
| nur der Schriftzug | `aureum-wortmarke-…` |

**Bildmarke oder Profilbild?** Die Bildmarke ist transparent und gehört auf
Aufdrucke, weil der Untergrund durchscheinen soll. Für Profile taugt sie nicht:
Dort landet das Zeichen auf dem zufälligen Hintergrund der Plattform. Das
Profilbild ist ein rundes Motiv auf quadratischer Vollfläche, weil die
Plattformen selbst rund beschneiden.

---

## 06 / Nutzung

Logo und Name dürfen verwendet werden, um auf die Aureum Technology GmbH
hinzuweisen, etwa in Presseartikeln, Verzeichnissen, Partnerübersichten
oder Referenzlisten.

Nicht erlaubt ist eine Verwendung, die den Eindruck erweckt, ein Angebot
stamme von uns oder sei von uns geprüft, freigegeben oder unterstützt.

Die Marken- und Urheberrechte bleiben bei der Aureum Technology GmbH.
Im Zweifel kurz fragen: info@aureum-tech.com

---

`AUREUM TECHNOLOGY GMBH · RODEWISCH IM VOGTLAND`
