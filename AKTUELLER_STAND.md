# OK Signage – AKTUELLER STAND (verbindlicher Einstieg)

**Aktuell: Kaffee V04 – Arbeitsstand; visuelle Freigabe ausstehend.**

**Vorschau:** https://ptrmohr.github.io/okSignage-preview/kaffee-v04/
**Quellcode:** `kaffee-v04/index.html`

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
- **V04 `kaffee-v04/index.html`: aktueller Arbeitsstand, nicht visuell freigegeben.**
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
