# OK Signage – VERBINDLICHER STARTPUNKT (20.11.2026)

## FREIGEGEBENER IST-STAND: HBB-Kaffee V12 – 20.11.2026

**Live-HTML:** https://ptrmohr.github.io/okSignage-preview/hbb-kaffee-v12/

**Kaffee-HTML:** `hbb-kaffee-v12/index.html` · **Preisdaten:** `hbb-kaffee-v12/preise.xml` · **geänderter Hintergrund, separat:** `hbb-hintergrund-v12/index.html`

V12 ist aus V11 entstanden, während der freigegebene V10-Hintergrund unangetastet erhalten bleibt. Die hintere Original-Logoebene bleibt unverändert als Logo-Asset, liegt nun bei `top:-16%;left:7%`, mit `rotateX(35deg)` statt 30°, und dreht weiterhin alle 120 Sekunden im Uhrzeigersinn. **V12 startet den automatischen Wechsel der drei vorhandenen Kaffee-Gläser und der leuchtenden Produktzeile ohne Buttons**, Intervall 5,5 Sekunden. Der sichtbare Player zeigt keine Toolbar oder Bedienknöpfe. Preise sind noch historische Musterdaten und nicht für Livebetrieb geprüft.

**Abnahme durch Nutzer am 20.11.2026:** V12 ist der verbindliche Ist-Stand. Einziger letzter Korrekturwunsch: Mouse-over-Leuchten entfernt. Der automatische Leuchteffekt auf der aktuell angezeigten Produktzeile bleibt erhalten. Kein sonstiger Eingriff in Logo, Farben, Perspektive, Gläser, Preise oder automatischen Wechsel. **V10 und V11 bleiben unverändert als gesicherte Referenzen.** Für weitere Änderungen neue Version V13 oder höher anlegen, V12 nicht überschreiben.

## FREIGEGEBEN: HBB-Hintergrund V10
**Vorschau:** https://ptrmohr.github.io/okSignage-preview/hbb-hintergrund-v10/
**HTML:** `hbb-hintergrund-v10/index.html`

Exakte Kopie der vom Nutzer ausdrücklich bestätigten Hintergrundversion V03. Gleiches originales freigestelltes rundes Engel-Logo: `hbb-hintergrund-v01/assets/coffee_brothers_original.png`. Gleiches warmes Braun-Grau, `left:7%; top:-6%; width:112%; opacity:.16`, Kippung 30° via `rotateX`, Rotation im Uhrzeigersinn 120s. **V10 niemals bei Änderungen an Produktbildern/Schrift verändern.**

## AKTUELLER KAFFEE-ENTWURF: V11 (noch nicht visuell freigegeben)
**Vorschau:** https://ptrmohr.github.io/okSignage-preview/hbb-kaffee-v11/
**HTML:** `hbb-kaffee-v11/index.html`
**Preisdaten:** `hbb-kaffee-v11/preise.xml` (historische Musterwerte!)

V11 lädt **V10 unverändert als Hintergrund-iframe**, so dass keine zweite Logo-Ebene entsteht. Darüber: Café-Crema-/Cappuccino-/Latte-Macchiato-Gläser aus `kaffee-html/assets/`, HTML-Preistafel und leuchtende Auswahl aus dem bestehenden `kaffee-html/index.html`-Entwurf. Bestehende Glas-Freistellung und Schriftoptik noch prüfen, besonders Café Crema. Die XML-Werte wurden übernommen, nicht gegen DailyPOS validiert. Erst nach Nutzersichtprüfung V11 als freigegeben markieren.

**Unverzichtbarer Workflow:** Neue Änderungen ausgehend von der freigegebenen `hbb-kaffee-v12/` ausschließlich als neue Version anlegen. V10 und V12 bleiben eingefroren. Github Pages Link direkt geben, keine neu generierten Gesamtgrafiken, keine lokalen ZIPs und keine CSS-Blöcke als Ersatz für die Browser-Vorschau. Historische Fassungen bewahren.

---
Stand: 20.11.2026

## Neue Vorschau zum Prüfen: HBB-Hintergrund V03 (20.11.2026)

**Browser-Link:** https://ptrmohr.github.io/okSignage-preview/hbb-hintergrund-v03/

**Quelle:** `hbb-hintergrund-v03/index.html`. **Status: noch NICHT visuell freigegeben.**

Von V02 ausschließlich die Position des originalen Engel-Logos um weitere 10 Prozentpunkte nach oben verschoben: `left:7%; top:-6%`. Der perspektivische Winkel von 30° auf der äußeren Ebene sowie die Uhrzeiger-Drehung der inneren Logoebene (120 Sekunden/Umdrehung) bleiben erhalten. V01 und V02 sind unverändert als Vergleich/Backup gespeichert. Das Original-Logo bleibt `hbb-hintergrund-v01/assets/coffee_brothers_original.png`.

## Vorheriger Test: HBB-Hintergrund V02 (20.11.2026)

**Browser-Link:** https://ptrmohr.github.io/okSignage-preview/hbb-hintergrund-v02/

**Quelle:** `hbb-hintergrund-v02/index.html`. **Status: noch NICHT visuell freigegeben.**

Auf Basis der freigegebenen V01: dasselbe Original-Engellogo (per relativem Asset-Pfad aus `hbb-hintergrund-v01/assets/coffee_brothers_original.png`), derselbe Farbverlauf. Die Logo-Ebene wurde von `top:24%;left:-8%` nach `top:4%;left:7%` verschoben. Das sind 20 bzw. 15 Prozentpunkte relativ zur Fläche, nicht prozentuale Verhältnisse. Zusätzlich dreht sich das runde Logo **im Uhrzeigersinn einmal in 120 Sekunden**, während es 30° perspektivisch zurückgekippt bleibt. Die Animation ist bei reduzierter Bewegung deaktiviert. Die V01 bleibt unverändert als Referenz.

**Nächster Schritt:** V02 im Browser ansehen, nur Kippung, Bewegung und Position nach Nutzerfeedback ändern. Nicht die Originalgrafik generieren oder Hintergründe austauschen. Bei Bestätigung V02 als neue freigegebene Hintergrundbasis markieren.

## 1. Aktuell bestätigte Gestaltung: HBB-Hintergrund V01

**Live-Vorschau:** https://ptrmohr.github.io/okSignage-preview/hbb-hintergrund-v01/

**HTML:** `hbb-hintergrund-v01/index.html`

**Original-Logo, transparent:** `hbb-hintergrund-v01/assets/coffee_brothers_original.png`

Dieser Hintergrund wurde vom Nutzer am 20.11. als „sehr gut“ bestätigt und anschließend in GitHub Pages veröffentlicht. Er ist die **aktuelle verbindliche Hintergrundreferenz** für künftige Signage-Tafeln (Kaffee, Franzbrötchen).

Verbindliche Optik:
- Format 1672 × 941 (16:9-nahe Vorlage), HTML/CSS-Layout.
- Originales **BROTHERS COFFEE & SNACKS Engel-Logo**, keine frei erfundenen Logos und kein Ersatztext „HBB STORE“.
- Warmer grau-brauner radialer/linearer Hintergrundverlauf.
- Logo **als separate PNG-Ebene**, nicht eingebrannt in die Hintergrundgrafik.
- CSS: `left:-8%;top:24%;width:112%;opacity:.16;transform-origin:50% 75%;transform:rotate(-26deg) rotateX(30deg);` mit Verlaufsmaskierung. Logo erscheint dadurch sehr groß und **unten abgeschnitten**, nicht vollständig im Bild.
- Nicht aus dem letzten Stand erneut eine Bildgenerierung machen. Für Änderungen **nur HTML/CSS** im GitHub-Repository ändern; Nutzer bekommt danach **nur den GitHub-Pages-Link**.
- Vor einer Logoänderung die bestätigte Referenz nicht überschreiben: Kopie als nächste Version anlegen.

## 2. Logo-Herkunft / Wiederauffinden

Die Originale liegen unter **Google Drive → HBBSignage → HBBLogosAi.zip**:
https://drive.google.com/file/d/16BQPivd20cs5w6iTc_FuA1tvThE7aq_x/view

Datei im ZIP: `Engel-Logo_peetRoundedSorted.ai`; weitere Originalvarianten `Engel-Logo_peetRounded.ai`, `Engel-Logo_peet_lettersOnly.ai`, `Engel-Logo_peet_noLetters.ai`.

Die aus dem Original erstellte transparente Logo-Datei liegt **jetzt direkt im GitHub-Repository**: `hbb-hintergrund-v01/assets/coffee_brothers_original.png`.

Eine weitere Kopie liegt auf Google Drive unter `HBBSignage/Work/CoffeeBrothers_Original_Transparent_800.png`.

**Niemals erneut nach einem anderen Logo suchen oder eine Schrift als Ersatz verwenden**, solange diese Originaldatei vorhanden ist.

## 3. Kaffee / Inhalt: getrennte Baustelle

- `kaffee-v04/index.html` ist die ältere Kaffee-Arbeitsgrundlage mit drei Gläsern, Originalschrift und Leuchteffekt. **Sie enthält noch eine PNG mit eingebautem Hintergrundlogo und darf deshalb NICHT zusätzlich direkt über das neue Logo gelegt werden.**
- `index.html` ist die frühere freigegebene Gesamtgrafik/Schriftreferenz mit älteren Produktbildern.
- `kaffee-html/index.html` ist eine weitere frühere HTML-Testfassung mit drei Gläsern, aber anderer Hintergrund-/Schriftumsetzung.
- Für eine neue Kaffee-Tafel: den bestätigten **Hintergrund V01** als unabhängige HTML-Ebene nutzen und dann nur die benötigten Glas-, Schrift- und Preis-Ebenen getrennt darüber aufbauen. Preise vor Produktion prüfen. Die drei Glasdateien sind `kaffee-html/assets/latte-original.png`, `kaffee-html/assets/crema-glas.png`, `kaffee-html/assets/cappuccino-glas.png`. Die Freistellung des Café-Crema-Glases ist noch zu kontrollieren.
- Freigegebene Leuchteffekt-Pixeldateien: `assets/glow_*.png`.

## 4. Franzbrötchen / Inhalt: getrennte Baustelle

- Historischer unfertiger Versuch: `franzbroetchen/index.html`; **nicht** als Hintergrundvorlage verwenden.
- Freigestellte Gebäcke: `franzbroetchen/assets/franzbroetchen_gruppe_freigestellt.png`.
- Gewünschte Reihenfolge: hinten Schoko, Mitte Streusel, vorne Klassisch.
- Gebäck wirkte zuletzt zu flach. Nach freigegebenem Hintergrund nur die Gebäckebene korrigieren, nicht Hintergrund/Logo.

## 5. Alte Fehlversuche / Archiv, NICHT weiterverwenden

- `kaffee-v05/index.html`: verworfener Versuch mit doppeltem Logo.
- `kaffee-v06/index.html`: verworfener Versuch mit gekipptem „HBB STORE“-Schriftzug statt dem grafischen Logo.
- Freie Bildgenerierungen einer völlig neuen Kaffee-Tafel sind keine Referenz.

## 6. Verbindlicher Workflow für alle weiteren Änderungen

1. **Zuerst dieses Dokument lesen**, dann die aktuelle GitHub-HTML und ihre tatsächlichen Asset-Pfade prüfen.
2. Auf Basis der letzten vom Nutzer **visuell bestätigten** Version arbeiten.
3. Ein Änderungsauftrag betrifft nur eine Ebene, z.B. Hintergrundlogo ODER Gläser ODER Produktbild ODER Preise. Andere Ebenen unverändert lassen.
4. Bei größeren Änderungen eine **neue versionierte HTML-Datei** anlegen. Keine Bilder neu generieren, wenn nur CSS geändert werden soll.
5. Die benötigten Dateien **vollständig auf GitHub bereitstellen**, nicht nur lokale ZIPs oder Sandbox-Dateien. Die Seite muss unmittelbar über GitHub Pages geladen werden können.
6. Prüfen, dass alle relativen Bildpfade auf im Repository vorhandene Dateien zeigen.
7. **Den GitHub-Pages-Vorschaulink** zum Anschauen geben, nicht Code, Download oder ein generiertes Mockup.
8. Erst nach visueller Bestätigung durch den Nutzer die neue Version in diesem Leitfaden als „freigegeben“ markieren.

## 7. Technischer Sicherheitsstand

Live-DailyPOS-Kasse darf durch Signage-Arbeiten nicht verändert werden. Preise sind historisch beispielhaft und müssen vor Livebetrieb anhand eines sicheren Read-only-Exports geprüft werden.
