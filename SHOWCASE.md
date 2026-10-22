---
fraktion: Ginnungagap
status: Siegel bricht
bedrohung: 9
ort: "[[Ginnungagap]]"
---
Alle Elemente des Themes **Ginnungagap Rift** auf einer Seite. Jeder Abschnitt zeigt zuerst das Ergebnis, dann das Markdown dazu. Am besten in der Leseansicht öffnen.

> [!info] Theme-Einstellungen
> Pol (Ginnungagap / Muspelheim / Niflheim), Buch-Überschriften, Sternenfeld, Runen und Glitch lassen sich mit dem Plugin **Style Settings** umschalten.

---

## Überschriften

# Fraktion (H1)
## Abschnitt (H2)
### Unterabschnitt (H3)
#### Eintrag (H4)
##### Telemetrie (H5)
###### Fußnote der Sensoren (H6)

---

## Text und Links

Interne Links glühen wie Glut: [[Ginnungagap]]. Externe Links sind kalt wie Eis: [Lancer RPG](https://massifpress.com/lancer). Links zu Notizen, die es noch nicht gibt, wirken ausradiert.

**Fett ist Knochenweiß**, *kursiv bleibt ruhig*, `inline code` glimmt und ==Markierungen== brennen leicht.

> *"Aus der Leere kam der Ruf. Und das Fleisch aus Silizium und Code antwortete."*

---

## Tags

#Faction #niflheim #muspelheim #ymir #hel #surtr #fenrir

`#niflheim #frost #eis #hel` werden zu Eis, `#muspelheim #feuer #glut #surtr` zu Glut, `#ymir #ginnungagap #leere #fenrir` zu Leere. Alle anderen Tags sind Glut-Plaketten.

---

## Listen und Aufgaben

- Erste Ebene glüht
	- Zweite Ebene ist Reif
		- Dritte Ebene glüht wieder
1. Korvette entern
2. Daten sichern

- [ ] Offen
- [x] Erledigt
- [!] Dringend
- [?] Offene Frage
- [-] Ausradiert

```md
- [!] Dringend
- [?] Offene Frage
- [-] Ausradiert
```

---

## Callouts

> [!frost] Niflheim
> Entropische Kälte. Systeme frieren ein.

> [!fire] Muspelheim
> Hitze flutet das Schlachtfeld.

> [!void] Telemetrie: NULL
> Keine Masse. Keine Strahlung. Keine Krümmung. Die Sonde existiert in keinem Modell der Raumzeit mehr.

> [!ymir] Der Ruf
> Kehrt heim, Fragmente. Kehrt heim in das formlose Ganze.

> [!transmission] RA-Axiom
> Wir helfen euch nicht, euer Überleben zu sichern. Aber wir gestatten euch, um euer Dasein zu kämpfen.

> [!saga] Völuspá
> Einst war das Zeitalter, da nichts war: nicht Sand noch See, noch kühle Wogen. Erde gab es nicht, noch Himmel oben, nur gähnende Kluft, doch Gras nirgends.

```md
> [!frost] / [!ice] / [!eis] / [!niflheim]
> [!fire] / [!ember] / [!feuer] / [!glut] / [!muspelheim]
> [!void] / [!null] / [!leere]
> [!ymir] / [!monist] / [!paracausal]
> [!transmission] / [!ra] / [!axiom]
> [!saga] / [!lore] / [!skald] / [!rune]
```

### Die Asen-Bosse

> [!surtr] Surtr — Der Weltenbrand
> Energie- und feuerfressender Titan. Ernährt sich von explodierenden Reaktoren.

> [!fenrir] Fenrir — Der Sternenfresser
> Teleportiert durch Omninet-Datenströme und bricht NHP-Caskets heraus.

> [!hel] Hel — Die Herrin des Stillstands
> Friert Systeme ein und reanimiert Wracks als führerlose Geistermaschinen.

> [!gm] Spielleiter-Wissen
> Ginnungagap ist das uralte Gefängnis der Monist-Wesenheit YMIR.

```md
> [!surtr] / [!fenrir] / [!hel]
> [!gm] / [!secret]
```

Die Standard-Callouts passen sich an:

> [!warning] Warnung
> Glut.

> [!danger] Gefahr
> Blut.

> [!tip] Tipp
> Bernstein.

---

## Tabelle und Code

| Asen-Boss | Domäne | Lizenzstufe |
| --- | --- | --- |
| Surtr | Feuer | LL3 |
| Fenrir | Leere | LL5 |
| Hel | Stillstand | LL7 |

```js
// Euklid-Interferometer
function scan(sector) {
  const reading = sector.telemetry ?? null;
  return reading === null ? "NULL" : `${reading} AU`;
}
```
