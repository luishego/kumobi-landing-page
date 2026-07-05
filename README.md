# KUMOBI — Landing Sector 03

Landing page del dark kitchen KUMOBI (Mixcoac, CDMX), construida con [Astro](https://astro.build).

## Estructura

```
src/
  layouts/Layout.astro     — head, meta tags, fuentes
  components/
    Hero.astro             — secuencia de arranque + título + CTA
    Lore.astro             — transmisión interceptada (lore de marca)
    Menu.astro              — Cyber-Burgers, Cyber-Wings, Data Chips
    Location.astro          — coordenadas, horario, Rappi
    Footer.astro
  pages/index.astro         — ensambla todas las secciones
  styles/global.css         — tokens de color, tipografía, componentes base
```

## Desarrollo local

```bash
npm install
npm run dev
```

Abre `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```


## Paleta y tipografía

| Token | Valor | Uso |
|---|---|---|
| `--negro-asfalto` | `#0D0D0D` | Fondo |
| `--fuego-serpiente` | `#FF3E1E` | Primario / CTAs |
| `--oro-neon` | `#FFB800` | Detalles, precios de add-ons |
| `--verde-glitch` | `#39FF14` | Alertas, indicador "en vivo" |

Tipografías: **Chakra Petch** (display), **JetBrains Mono** (cuerpo/UI), **Noto Serif JP** (acento japonés).
