# KlimaGarant — Klimatechnik NRW

Statische Landingpage (One-Page) für KlimaGarant Klimatechnik, Nordrhein-Westfalen.
Luxury-Design (crème/braun/messing), Deutsch, mobile-first.

## Struktur
- `index.html` — Startseite (inline CSS/JS, keine Build-Schritte)
- `impressum.html` / `datenschutz.html` / `agb.html` — Rechtsseiten (Platzhalter, siehe TODO)
- `legal-shared.css` — gemeinsames Stylesheet der Rechtsseiten
- `images/` — Fotos. `hero.jpg`/`aussen.jpg`/`raum.jpg` = alte Platzhalter (ungenutzt, nicht gelöscht). `team-montage.jpg`, `zuhause-schlafzimmer.jpg`, `zuhause-paar-jung.jpg` = aktuell im Einsatz, **Mockup/Stock — noch keine echten eigenen Projektfotos** (Tausch geplant, siehe TODO). `zuhause-frau-sofa.jpg`, `zuhause-paar-aelter.jpg` liegen bereit, aktuell ungenutzt.

## Neu in diesem Update (2026-10-19)
- Rebrand KlimaMax → **KlimaGarant** (Logo, Meta, Schema.org, Footer, Rechtsseiten)
- Hero + Zuhause-Fokus: Content-Schwerpunkt auf Privatkunden (B2B-Leistungen/Serverraum bleiben erhalten, nur nicht mehr an erster Stelle)
- Neue Sektion "Kennen Sie das?" (`#zuhause`) — Selbstidentifikations-Karten nach Raumtyp (Dachgeschoss/Schlafzimmer/Wohnzimmer/Mehrere Räume)
- Comfort-Sektion neu getextet (Loss-Aversion + Schlafverlust-Statistik 56h/Jahr, Quelle: research/b2c-psychologie-hitze-zuhause.md)
- Neue Preis-Sektion (`#preise`): 1 Raum ab 1.990€ (Haier, Standardmontage, Leitungslänge bis 3m, Festpreis) + 2/3+ Räume individuell
- Kontaktformular → **Klima-Check-Quiz** (3 Fragen + 2 Kontaktfelder, Mehrschritt-Fortschrittsanzeige) statt langem Einzelformular
- FAQ: Hinweis ergänzt, dass der Förderantrag VOR Auftragsvergabe gestellt werden muss (häufiger teurer Fehler, siehe research/voice-of-customer-zitate-de.md)
- Reale Kontaktdaten eingetragen: Tel. 0170 655 4959, E-Mail anfrage@klimagarant.de, Region Essen + Ruhrgebiet

## Deployment
Reine Statik — kein Build nötig. Vercel/Netlify erkennen `index.html` automatisch.

## TODO vor Livegang (Reihenfolge nach Priorität)
1. **Rechtlicher Blocker zuerst:** Handwerksrolle-Eintrag + Meister/Betriebsleiter + F-Gas-Unternehmenszertifizierung bestätigen. Solange das offen ist, sind die Badges "Meisterbetrieb" / "F-Gas-zertifiziert" (Hero, Warum-Sektion, Footer) **nicht beworbene Tatsachenbehauptungen, sondern ein Abmahnrisiko (UWG)** — vor Livegang entweder bestätigen oder entfernen.
2. **Echte Fotos einsetzen, sobald verfügbar** — `team-montage.jpg`/`zuhause-*.jpg` sind aktuell Mockup/Stock, kein dokumentiertes eigenes Projekt. Bildunterschriften sind bewusst neutral gehalten (keine falsche "unser Team/unser Projekt"-Behauptung) — bei echten Fotos können Bildunterschriften entsprechend konkreter werden.
3. Impressum / Datenschutz / AGB mit echten Firmendaten befüllen (Platzhalter sind markiert mit `[...]` und gelben TODO-Boxen)
4. E-Mail-Adresse `anfrage@klimagarant.de` real einrichten (Domain noch nicht registriert); WhatsApp-Nummer 0170 655 4959 für Geschäfts-WhatsApp verifizieren
5. Formular an Service anbinden (Formspree/Web3Forms) + Benachrichtigung an Team (WhatsApp/E-Mail) — **Antwortzeit <1 Min ist der wichtigste Konversionshebel**, siehe research/finale-website-strategie-zuhause.md
6. Echte Referenzen/Bewertungen einsetzen — aktuell Muster-Zitate, klar als Platzhalter markiert
7. Markenliste (Daikin/Haier/Mitsubishi/…) nur zeigen, wenn tatsächlich verbaut/Vertragshändler bestätigt
8. Cookie-Consent-Banner einbauen, sobald Analytics/Tracking hinzukommt
9. Reale Preise für 2/3+ Räume einholen (Einkaufspreise vom Partner) — aktuell nur "Auf Anfrage"-Platzhalter, kein konkreter Betrag erfunden
