# Speed — Natura vs Macchina

Esperienza web interattiva che mette a confronto la velocità massima di un **ghepardo** e di una **Bugatti Chiron** in una simulazione di corsa animata.

**Demo live:** https://luca-grella.github.io/speed-arena/

---

## Cosa fa

- Animazione CSS/JS di una pista da corsa con fisiche semplificate (accelerazione, velocità massima, attrito)
- Il ghepardo parte più veloce ma la Bugatti lo supera a velocità di punta (~420 km/h vs ~120 km/h)
- Design Apple-style: sfondo nero, tipografia Inter, carte glassmorphism, animazioni AOS scroll-driven
- Sezione statistiche comparativa (peso, potenza, 0-100, velocità massima)
- Responsive mobile-first

## Stack

- HTML/CSS/JS vanilla — zero dipendenze runtime nel bundle finale
- Tailwind CSS (CDN), Lucide Icons (CDN), AOS (CDN) — solo per sviluppo/preview
- GitHub Pages — deploy statico diretto da `index.html`

## File

| File | Descrizione |
|------|-------------|
| `index.html` | App completa (markup + stili inline + logica JS) |
