# 🎬 CineNet

**Endevina la banda sonora** — El joc musical de cinema i sèries de televisió.

🌐 **Juga ara:** [kinblay.github.io/CineNet](https://kinblay.github.io/CineNet/)

---

## Què és CineNet?

CineNet és un joc web PWA on has d'endevinar pel·lícules i sèries de televisió escoltant fragments de les seves bandes sonores. Inspirat en Wordle i Heardle, combina 10 nivells de dificultat creixent amb una component social i de descobriment musical.

**Modes de joc:**
- 🎬 **Pel·lícula del dia** — Una BSO diferent cada dia, rànquing global
- 📺 **Sèrie del dia** — Un tema de sèrie diferent cada dia
- 🎮 **Partida lliure** — Barreja de pel·lícules i sèries, sense límit
- 🎬 **Director d'Autor** — Bandes sonores de directors i compositors icònics
- ⚔️ **Repte** — Desafia un amic i compara puntuacions

---

## Característiques

- 🎵 **200+ bandes sonores** de pel·lícules i sèries
- 📱 **PWA instal·lable** — funciona com una app al mòbil
- 🌍 **4 idiomes** — Català, Espanyol, Europeu, Internacional
- 🏆 **Sistema de rangs** — De Espectador a Immortal 🦁
- 🔥 **Streak diari** — Mantén la ratxa de dies consecutius
- 📤 **Compartir resultats** — Targeta estil Wordle
- 🎬 **Intro cinematogràfica** — Comptador 3-2-1 a l'inici

---

## Tecnologia

| Capa | Tecnologia |
|------|-----------|
| Frontend | HTML5 / CSS3 / JavaScript pur |
| Backend | Supabase (PostgreSQL + RLS) |
| Àudio | Deezer API (previews 30s) |
| Hosting | GitHub Pages |
| PWA | Service Worker + Web Manifest |

---

## Catàleg

| Idioma | Pel·lícules | Sèries |
|--------|-------------|--------|
| 🌐 Internacional | 29 | 82 |
| 🌍 Europeu | 16 | 23 |
| 🎸 Espanyol | 6 | 29 |
| 🎵 Català | 3 | 17 |

---

## Estructura del repositori

```
CineNet/
├── index.html          # Joc complet (tot en un fitxer)
├── manifest.json       # PWA manifest
├── sw.js               # Service Worker
├── icon-192.png        # Icona PWA
├── icon-512.png        # Icona PWA gran
└── README.md           # Aquest fitxer
```

---

## Instal·lació local

Simplement obre `index.html` en un servidor local:

```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .
```

Accedeix a `http://localhost:8000`

> ⚠️ L'àudio Deezer no funciona obrint el fitxer directament (`file://`), cal un servidor local o GitHub Pages.

---

## Relacionat

- 🎵 [CançoNet](https://kinblay.github.io/CancoNet/) — El joc de la música catalana

---

## Llicència

Projecte personal. Les bandes sonores s'utilitzen via l'API pública de Deezer (previews de 30 segons). Tots els drets musicals pertanyen als seus respectius titulars.
