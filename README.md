# VÉLORA — Premium Property Care

Mehrseitige, responsive Website für VÉLORA. Die Seite ist statisch und kann direkt auf GitHub Pages, Vercel oder einem klassischen Webhosting veröffentlicht werden.

## Seiten
- index.html — Startseite
- leistungen.html — Leistungsübersicht
- mitgliedschaft.html — Mitgliedschaft, Preisstaffeln und interaktiver Rechner
- ablauf.html — Prozess und Zusammenarbeit
- ueber-uns.html — Markenprofil
- kontakt.html — Anfrageprototyp
- impressum.html und datenschutz.html — rechtliche Platzhalter

## Funktionen
- Responsive Desktop- und Mobile-Navigation
- Hell-/Dunkelmodus mit lokal gespeicherter Präferenz
- Preisrechner nach Anzahl Wohneinheiten inkl. Jahresstunden
- Keine Analytics- oder Marketing-Tracker eingebunden
- Kontaktformular kopiert die Anfrage lokal; es wird nichts an einen Server übertragen

## Vor dem Livegang
1. Die Preisstaffeln und enthaltenen Jahresstunden kaufmännisch validieren. Die dargestellten Preise sind unverbindliche Konzeptwerte.
2. Vertraglich festlegen: Einsatzgebiet, Leistungsumfang, enthaltene Arbeitszeit, Übertragbarkeit, Anfahrt/Wegezeiten, Material, Zusatzstunden, Reaktionszeiten und ausgeschlossene Gewerke.
3. Rechtliche Pflichtangaben im Impressum vervollständigen.
4. Datenschutzhinweise anhand des tatsächlichen Hostings und der extern eingebundenen Schriftarten vervollständigen.
5. Prüfen, ob die externen Google Fonts lokal gehostet werden sollen.
6. Eine echte Geschäftsadresse und einen sicheren Kontaktweg einrichten, bevor Anfragen produktiv verarbeitet werden.
7. Marken- und Domainverfügbarkeit für VÉLORA prüfen. Das ®-Symbol wird bewusst nicht verwendet, solange keine Registrierung bestätigt ist.

## Lokal testen
Einfach index.html öffnen oder einen lokalen Server starten:

    python3 -m http.server 8000
