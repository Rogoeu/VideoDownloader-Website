# Muxelio – GitHub Pages Website

## Veröffentlichung unter muxelio.de

1. Die Dateien dieses ZIPs **direkt ins Hauptverzeichnis** des vorhandenen Repositorys `Rogoeu/VideoDownloader-Website` hochladen (bestehende Dateien bei gleichem Namen ersetzen). **Nicht** einen zusätzlichen Unterordner hochladen.
2. In **Settings → Pages** muss als Custom domain `muxelio.de` eingetragen sein. Die Datei `CNAME` ist ebenfalls enthalten.
3. Bei INWX zeigen die vier A-Einträge für die Hauptdomain auf `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; `www` zeigt per CNAME auf `rogoeu.github.io`. **Die fünf Clerk-CNAME-Einträge nicht ändern.**
4. GitHub Pages stellt HTTPS aus; Zertifikat und DNS-Prüfung können dauern.
5. **Vor dem öffentlichen Betrieb:** `imprint.html` und `privacy.html` rechtlich vervollständigen. Beide Seiten enthalten ausdrücklich Platzhalter.
6. Es gibt noch keine echten Download- oder Pro-Kaufbuttons. Stripe/Clerk Production müssen vor Verkäufen getrennt getestet und rechtlich vorbereitet werden.

## Inhalt
- `index.html`: zweisprachige Landingpage
- `style.css`: vorhandenes responsives Design
- `site.js`: Sprachwechsel DE/EN
- `assets/icon.png`: bestehendes Produktsymbol (vorerst beibehalten)
- `imprint.html`, `privacy.html`: **rechtliche Entwürfe**, nicht fertig
- `CNAME`: GitHub-Pages-Domain

Die Website ist nur die Produktvorschau. Sie verbindet noch nicht automatisch Login oder Stripe-Checkout.
