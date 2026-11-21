# Schriften (lokal gehostet)

Bewusst **nicht** über Google Fonts per CDN: die CSP (`font-src 'self'`) blockt
fremde Font-Hosts, und ein CDN-Abruf überträgt die IP jedes Besuchers an Google
(DSGVO, vgl. LG München I, 3 O 17493/20). Nur das Latin-Subset (inkl. Umlaute).

| Datei | Schrift | Einsatz | Lizenz |
|---|---|---|---|
| `anton-latin.woff2` | Anton 400 | Headlines, HUD-Zahlen | SIL OFL 1.1 (`OFL-anton.txt`) |
| `inter-latin-var.woff2` | Inter 400–800 (variabel) | Fließtext, Buttons, HUD-Labels | SIL OFL 1.1 (`OFL-inter.txt`) |
| `yellowtail-latin.woff2` | Yellowtail 400 | Neon-Schreibschrift, nur Deko | Apache 2.0 (`LICENSE-yellowtail-Apache-2.0.txt`) |
