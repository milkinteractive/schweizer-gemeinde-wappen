# Schweizer Gemeinde und Kantons Wappen

Sammlung aller Schweizer Wappen als SVG — 26 Kantone und 2'100+ Gemeinden.

## Struktur

```
cantons/          # 26 Kantonswappen, benannt nach Kürzel (ZH.svg, BE.svg, …)
municipalities/   # ~2'110 Gemeindewappen, benannt nach BFS-Nummer (261.svg, 351.svg, …)
```

### Kantone

Dateien sind nach dem offiziellen Kantonskürzel benannt:

<table>
  <tr>
    <td align="center"><img src="cantons/ZH.svg" width="48" height="48"><br><sub>ZH</sub></td>
    <td align="center"><img src="cantons/BE.svg" width="48" height="48"><br><sub>BE</sub></td>
    <td align="center"><img src="cantons/LU.svg" width="48" height="48"><br><sub>LU</sub></td>
    <td align="center"><img src="cantons/UR.svg" width="48" height="48"><br><sub>UR</sub></td>
    <td align="center"><img src="cantons/SZ.svg" width="48" height="48"><br><sub>SZ</sub></td>
    <td align="center"><img src="cantons/OW.svg" width="48" height="48"><br><sub>OW</sub></td>
    <td align="center"><img src="cantons/NW.svg" width="48" height="48"><br><sub>NW</sub></td>
    <td align="center"><img src="cantons/GL.svg" width="48" height="48"><br><sub>GL</sub></td>
    <td align="center"><img src="cantons/ZG.svg" width="48" height="48"><br><sub>ZG</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="cantons/FR.svg" width="48" height="48"><br><sub>FR</sub></td>
    <td align="center"><img src="cantons/SO.svg" width="48" height="48"><br><sub>SO</sub></td>
    <td align="center"><img src="cantons/BS.svg" width="48" height="48"><br><sub>BS</sub></td>
    <td align="center"><img src="cantons/BL.svg" width="48" height="48"><br><sub>BL</sub></td>
    <td align="center"><img src="cantons/SH.svg" width="48" height="48"><br><sub>SH</sub></td>
    <td align="center"><img src="cantons/AR.svg" width="48" height="48"><br><sub>AR</sub></td>
    <td align="center"><img src="cantons/AI.svg" width="48" height="48"><br><sub>AI</sub></td>
    <td align="center"><img src="cantons/SG.svg" width="48" height="48"><br><sub>SG</sub></td>
    <td align="center"><img src="cantons/GR.svg" width="48" height="48"><br><sub>GR</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="cantons/AG.svg" width="48" height="48"><br><sub>AG</sub></td>
    <td align="center"><img src="cantons/TG.svg" width="48" height="48"><br><sub>TG</sub></td>
    <td align="center"><img src="cantons/TI.svg" width="48" height="48"><br><sub>TI</sub></td>
    <td align="center"><img src="cantons/VD.svg" width="48" height="48"><br><sub>VD</sub></td>
    <td align="center"><img src="cantons/VS.svg" width="48" height="48"><br><sub>VS</sub></td>
    <td align="center"><img src="cantons/NE.svg" width="48" height="48"><br><sub>NE</sub></td>
    <td align="center"><img src="cantons/GE.svg" width="48" height="48"><br><sub>GE</sub></td>
    <td align="center"><img src="cantons/JU.svg" width="48" height="48"><br><sub>JU</sub></td>
    <td></td>
  </tr>
</table>

### Gemeinden

Dateien sind nach der offiziellen [BFS-Gemeindenummer](https://www.bfs.admin.ch/bfs/de/home/grundlagen/agvch.html) benannt. Beispiel: Zürich = `261.svg`, Bern = `351.svg`.

<img src="municipalities-grid.png" alt="Alle 2'110 Schweizer Gemeindewappen" width="100%">

BFS-Nummern nachschlagen: [Offizielles Gemeindeverzeichnis (BFS)](https://www.bfs.admin.ch/bfs/de/home/grundlagen/agvch.html).

## Abdeckung

| Typ | Vorhanden | Vektor | Raster-in-SVG | Abdeckung |
|-----|-----------|--------|---------------|-----------|
| Kantone | 26/26 | 26 | 0 | 100% |
| Gemeinden | ~2'110/~2'136 | ~1'800 | ~310 | ~99% |

> ~310 Gemeindewappen sind Rasterbilder (PNG/GIF) in einem SVG-Wrapper. Sie werden korrekt dargestellt, sind aber keine echten Vektorgrafiken. Beiträge zum Ersetzen durch echte Vektor-SVGs sind willkommen.

### Fehlende Gemeinden

| BFS | Name | Kanton |
|-----|------|--------|
| 2391 | Staatswald Galm | FR |
| 3234 | Diepoldsau | SG |
| 5391 | Comunanza Cadenazzo/Monteceneri | TI |
| 6119 | Turtmann-Unterems | VS |
| 6730 | Val Terbi | JU |
| 6809 | Haute-Ajoie | JU |

## Verwendung

```html
<img src="cantons/ZH.svg" alt="Wappen Zürich" width="32" height="32" />
<img src="municipalities/261.svg" alt="Wappen Stadt Zürich" width="32" height="32" />
```

## Quellen & Qualität

- Kantonswappen von offiziellen Kantonswebsites und Wikimedia Commons — alle echte Vektorgrafiken
- Gemeindewappen von offiziellen Gemeindewebsites, kantonalen Portalen und Wikimedia Commons
- ~85% der Gemeindedateien sind echte Vektor-SVGs, ~15% sind eingebettete Rasterbilder (siehe Abdeckung)

## Lizenz

Wappen sind als offizielle heraldische Insignien gemeinfrei. Die SVG-Dateien in diesem Repository stehen unter der [MIT-Lizenz](LICENSE).

**Hinweis:** Einzelne Gemeinden können Markenrechte an ihrem Wappen halten. Bei kommerzieller Nutzung im grossen Stil empfehlen wir eine Prüfung der lokalen Bestimmungen.

## Mitmachen

Pull Requests sind willkommen — besonders für fehlende Gemeinden oder bessere SVG-Qualität:

- Dateien sollten saubere Vektor-SVGs sein (keine eingebetteten Rasterbilder)
- Korrekt nach BFS-Nummer benannt
- Vernünftige Dateigrösse (< 100 KB)

---

Gepflegt von [Milk Interactive](https://milkinteractive.ch) — [hello@milkinteractive.ch](mailto:hello@milkinteractive.ch)
