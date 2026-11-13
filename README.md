# Strata — Exercici004

Reproducció acadèmica d'una pàgina de Strata amb HTML i CSS. La pàgina s'adapta a escriptori i mòbil, i es pot obrir amb Live Server de VS Code o qualsevol servidor estàtic.

## Recursos

- Els logotips, les imatges de producte i les fonts locals es carreguen des de `assets/`.
- L'animació del hero utilitza el script original de Strata i les biblioteques incloses a `assets/js/`. Els scripts es conserven sense modificacions i es carreguen amb `defer`.
- Three.js i 3d-force-graph es distribueixen amb les seves llicències dins de `assets/js/vendor/`.
- El script del hero prové de <https://www.strata.ai/hero-graph.js> i no inclou cap declaració de llicència oberta. Les llicències MIT de les biblioteques no s'hi apliquen.
- Els logotips, els textos, les imatges i el disseny de referència provenen de <https://www.strata.ai/> i del material facilitat per a l'exercici.

## Adaptació a mòbil

Per sota de 768 px, les targetes i les seccions canvien de distribució i el gràfic 3D del hero s'amaga; es manté el fons amb degradats CSS. També s'han ajustat espais i mides per a pantalles estretes.
