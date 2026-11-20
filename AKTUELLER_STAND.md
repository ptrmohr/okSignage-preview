# OK Signage – AKTUELLER STAND (verbindlicher Einstieg)

**WIEDERHERGESTELLTER REFERENZSTAND: Kaffee V04.** V05 und V06 sind abgelehnte Logo-Experimente und dürfen NICHT als Basis weiterer Änderungen verwendet werden.

**V04 Vorschau:** https://ptrmohr.github.io/okSignage-preview/kaffee-v04/
**HTML:** `kaffee-v04/index.html`

**Korrekturauftrag (noch offen):** Das **originale grafische Hintergrundlogo** (nicht der Schriftzug „HBB STORE“) ausschließlich perspektivisch um etwa 30 Grad nach hinten kippen und leicht ausfaden. Kein zweites Logo hinzufügen, nicht die übrige Tafel verändern. Das Logo ist aktuell nicht als eigenständige transparente PNG im Repository nachweisbar. Vor neuer Version die Original-Logoebene wiederfinden oder sauber aus der vorhandenen Originalgrafik extrahieren. Keine erfundenen Logos oder Text-Wasserzeichen.

## Original-Logo jetzt eindeutig gefunden (20.11.2026)

- Google Drive → `HBBSignage/HBBLogosAi.zip`: https://drive.google.com/file/d/16BQPivd20cs5w6iTc_FuA1tvThE7aq_x/view
- Datei darin: `Engel-Logo_peetRoundedSorted.ai` – **vollständiges rundes BROTHERS COFFEE & SNACKS Logo mit Engelmotiv**. Alternative Variante `Engel-Logo_peetRounded.ai`; außerdem getrennte Varianten `Engel-Logo_peet_lettersOnly.ai` und `Engel-Logo_peet_noLetters.ai`.
- Die AI-Datei besitzt eine PDF-kompatible Vektorvorschau. Eine transparente PNG wurde daraus lokal erstellt; eigenständige HTML-Testvorschau (30° 3D-Kippung, Deckkraft regelbar) ist vorhanden. Das Logo wurde noch **nicht auf GitHub veröffentlicht**.
- Keine nachgebaute „HBB STORE“-Schrift mehr anstelle des Engels verwenden. Keine Doppelbelegung mit dem in älteren Kaffee-PNGs vorhandenen Wasserzeichen. Für die Freigabe echte Logoebene vor sauberem Hintergrund verwenden.

## Hintergrund und Schrift – feste Referenz
- `assets/HBB_Kaffee_Arbeitsgrundlage_v2_Titel_10Prozent.png`: freigegebene vollständige Kaffee-Originalgrafik inklusive Logo, Schrift und ursprünglichem Produktbereich.
- `assets/glow_*.png`: isolierte Schriftpixel für die Leucht-Hervorhebung.
- Beide Originalbestände **nicht überschreiben**.
- In V04 wird der ältere linke Produktbildbereich mit `assets/OKSignage_Hintergrund_Freigestellt.png` überdeckt. Übergänge/Ränder dieser Abdeckung sind visuell noch zu prüfen.

## Drei Gläser – eigene Bildebenen
- Latte: `kaffee-html/assets/latte-original.png`
- Café Crema: `kaffee-html/assets/crema-glas.png`
- Cappuccino: `kaffee-html/assets/cappuccino-glas.png`
- In V04 als separate HTML-Ebenen eingebunden; die Café-Crema-Freistellung, Proportionen und alle drei Positionen sind noch zu prüfen.

## Versionen und Status
- **V05 `kaffee-v05/index.html`: verworfener Doppel-Logo-Test, NICHT aktuell.**
- **V06 `kaffee-v06/index.html`: verworfener Text-Wasserzeichen-Test, NICHT aktuell.**
- **V04 `kaffee-v04/index.html`: wiederhergestellte Referenzfassung; künftige Änderungen nur als Kopie und erst nach Sichtprüfung.**
- `index.html`: archivierter Kaffee V02, Referenz für Originalgrafik, Schrift und Leuchten; ältere Fotos.
- `kaffee-html/index.html`: archivierter V03-Test mit drei Glasdateien, aber nachgebautem Hintergrund.
- `franzbroetchen/index.html`: unfertiger separater Entwurf; nicht aktuell als Hintergrundreferenz.
- `franzbroetchen/hintergrund-referenz.html`: reine Original-Gesamtbildreferenz.

## Verbindliche Arbeitsweise
1. Immer diesen Dateinamen **AKTUELLER_STAND.md** zuerst lesen, bevor weitergearbeitet wird.
2. Den Hintergrund/Originalschrift in einem bestätigten Stand einfrieren; Produktfotos und spätere Franzbrötchen getrennt bearbeiten.
3. Keine älteren Dateien löschen: Sie dienen als überprüfbares Archiv.
4. Neue Entwicklungsstände V05 usw. versionieren. Erst nach expliziter Sichtfreigabe hier den Status „freigegeben“ vergeben.
5. Musterpreise sind noch nicht gegen DailyPOS abgeglichen.
