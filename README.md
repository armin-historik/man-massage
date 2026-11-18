# MAN-MASSAGE – neue GitHub-Webseite (Testversion)

## Enthalten
- Startseite mit zwei Massage-Bereichen
- Gay Massage: eigene Unterseiten Winterthur und Zürich
- Team, Kontakt, Impressum, Datenschutz
- Blog mit 10 Beiträgen
- Responsives Layout, Navigation, SEO-Metadaten

## WICHTIG vor Livegang
1. Testseiten sind absichtlich mit `noindex,nofollow` markiert, robots.txt sperrt Crawler. Erst beim Domainwechsel nach URL-Migration und Weiterleitungen anpassen.
2. Originale Wix-URLs exportieren und 301-Weiterleitungen planen. GitHub Pages bietet keine frei konfigurierbaren serverseitigen 301-Weiterleitungen; bei Bedarf DNS/CDN/Redirect-Service verwenden.
3. Buchungsbutton führt vorläufig zur bestehenden Startseite https://www.man-massage.ch/; den echten Buchungslink einsetzen und testen.
4. Originalfotos von Vali und Armin und ggf. neue KI-Massagebilder ergänzen. Grafische Hero-Fläche ist absichtlich nur ein Platzhalter.
5. Impressum und Datenschutz vervollständigen. Google Fonts bei Bedarf lokal einbinden.
6. Preise und Leistungsbeschreibung mit den tatsächlichen Angeboten abgleichen.
7. Google Search Console, Canonicals, Sitemap und Analytics erst zum Livegang korrekt konfigurieren.
8. GitHub-Testadresse: https://armin-historik.github.io/man-massage/

Dateien direkt ins Root des Repositorys hochladen, den Ordner `blog` mit hochladen. Wix und Domain bis zum Wechsel unverändert lassen.
