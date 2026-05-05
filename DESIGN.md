---
version: alpha
name: Worst Case Weather
description: Meteorological worst-case intelligence for serious travelers. Dark radar-screen aesthetic with amber warnings. Data-forward, no fluff.
colors:
  background: "#0D0F14"
  surface: "#161A23"
  surface-raised: "#1E2330"
  primary: "#F59E0B"
  primary-muted: "#B45309"
  secondary: "#3B82F6"
  danger: "#EF4444"
  text-primary: "#F1F5F9"
  text-secondary: "#94A3B8"
  text-muted: "#475569"
  border: "#2D3548"
  rain-blue: "#60A5FA"
  sun-yellow: "#FCD34D"
typography:
  display:
    fontFamily: Outfit
    fontSize: 2.5rem
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  h1:
    fontFamily: Outfit
    fontSize: 1.75rem
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  h2:
    fontFamily: Outfit
    fontSize: 1.125rem
    fontWeight: 600
    lineHeight: 1.3
  body:
    fontFamily: DM Sans
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: DM Sans
    fontSize: 0.75rem
    fontWeight: 500
    letterSpacing: "0.08em"
    textTransform: uppercase
  data:
    fontFamily: JetBrains Mono
    fontSize: 0.9rem
    fontWeight: 400
    lineHeight: 1.4
rounded:
  sm: 4px
  md: 8px
  lg: 16px
  xl: 24px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
components:
  card:
    backgroundColor: "{colors.surface}"
    borderColor: "{colors.border}"
    borderWidth: 1px
    rounded: "{rounded.lg}"
    padding: 20px
  card-raised:
    backgroundColor: "{colors.surface-raised}"
    borderColor: "{colors.border}"
    borderWidth: 1px
    rounded: "{rounded.lg}"
    padding: 20px
  input-field:
    backgroundColor: "{colors.surface}"
    borderColor: "{colors.border}"
    borderWidth: 1px
    borderRadius: "{rounded.md}"
    textColor: "{colors.text-primary}"
    padding: 12px 16px
    fontFamily: DM Sans
    fontSize: 1rem
  input-field-focus:
    borderColor: "{colors.primary}"
    boxShadow: "0 0 0 3px rgba(245, 158, 11, 0.15)"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#0D0F14"
    fontFamily: Outfit
    fontWeight: 600
    fontSize: 0.9rem
    rounded: "{rounded.md}"
    padding: 12px 24px
    cursor: pointer
    border: none
  button-primary-hover:
    backgroundColor: "{colors.primary-muted}"
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.text-secondary}"
    borderColor: "{colors.border}"
    borderWidth: 1px
    borderRadius: "{rounded.md}"
    padding: 10px 20px
  button-ghost-hover:
    backgroundColor: "{colors.surface-raised}"
    textColor: "{colors.text-primary}"
  chip-rain:
    backgroundColor: "rgba(96, 165, 250, 0.15)"
    textColor: "{colors.rain-blue}"
    borderRadius: "{rounded.sm}"
    padding: 4px 10px
    fontFamily: DM Sans
    fontSize: 0.8rem
    fontWeight: 500
  chip-sun:
    backgroundColor: "rgba(252, 211, 77, 0.15)"
    textColor: "{colors.sun-yellow}"
    borderRadius: "{rounded.sm}"
    padding: 4px 10px
    fontFamily: DM Sans
    fontSize: 0.8rem
    fontWeight: 500
  chip-warning:
    backgroundColor: "rgba(239, 68, 68, 0.12)"
    textColor: "{colors.danger}"
    borderRadius: "{rounded.sm}"
    padding: 4px 10px
    fontFamily: DM Sans
    fontSize: 0.8rem
    fontWeight: 500
  divider:
    backgroundColor: "{colors.border}"
    height: 1px
    width: 100%
  data-row:
    backgroundColor: transparent
    borderBottom: "1px solid {colors.border}"
    padding: 12px 0
  stat-block:
    backgroundColor: "{colors.surface-raised}"
    rounded: "{rounded.md}"
    padding: 16px
  icon-rain:
    color: "{colors.rain-blue}"
  icon-sun:
    color: "{colors.sun-yellow}"
  icon-warning:
    color: "{colors.danger}"
  progress-bar:
    backgroundColor: "{colors.surface-raised}"
    rounded: "{rounded.sm}"
    height: 6px
  progress-bar-fill:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.sm}"
---

## Overview

Worst Case Weather es una app de inteligencia climática para viajeros que planifican con seriedad. No vende esperanza — entrega datos. La pregunta no es "¿qué tiempo hará?" sino "¿qué podría salir mal?"

El tono es el de un briefing meteorológico militar: preciso, denso en datos, sin adornos. La interfaz parece una pantalla de radar climatológico — oscura, funcional, con acentos de advertencia en ámbar cuando algo puede salir mal.

La emoción que transmite: **control sobre lo impredecible**.

## Colors

- **Background (#0D0F14):** Pantalla de radar. Negro azulado profundo. Nunca blanco.
- **Surface (#161A23):** Tarjetas base. Un paso más claro que el fondo.
- **Surface Raised (#1E2330):** Elementos elevados, chips, barras de progreso.
- **Primary (#F59E0B):** Ámbar — el color de las advertencias serias. Para CTAs, highlights, scores.
- **Primary Muted (#B45309):** Ámbar profundo para hover states.
- **Secondary (#3B82F6):** Azul frío para todo lo relacionado con precipitación y agua.
- **Danger (#EF4444):** Rojo para alertas críticas y máxima precaución.
- **Text Primary (#F1F5F9):** Blanco suave para títulos y datos principales.
- **Text Secondary (#94A3B8):** Gris azulado para descripciones y contexto.
- **Text Muted (#475569):** Para labels pequeños y metadata.
- **Border (#2D3548):** Líneas de tarjetas y divisores.
- **Rain Blue (#60A5FA):** Chips y badges de lluvia.
- **Sun Yellow (#FCD34D):** Chips de buen tiempo.

## Typography

**Outfit** para display y headings — geométrica, moderna, con carácter. **DM Sans** para cuerpo — legible, neutral, profesional. **JetBrains Mono** para datos numéricos — los números se ven mejor en monospace, más técnicos.

- **Display:** 2.5rem / 700 — el nombre de la ciudad en resultados.
- **H1:** 1.75rem / 600 — títulos de sección (Histórico, Forecast, Index).
- **H2:** 1.125rem / 600 — subtítulos de bloque.
- **Body:** 1rem / 400 — descripciones, contexto.
- **Label:** 0.75rem / 500 / uppercase / 0.08em tracking — tags, labels de categoría.
- **Data:** JetBrains Mono 0.9rem — temperaturas, porcentajes, milímetros.

## Layout & Spacing

**Página única (single page app):** sin navegación. Todo el flujo ocurre en una vista.

```
┌─────────────────────────────────────────────────┐
│  HEADER: Logo + tagline                          │
├─────────────────────────────────────────────────┤
│  SEARCH BAR: Ciudad [____] + Fecha inicio [→]  │
│             Fecha fin [____] [Consultar]        │
├─────────────────────────────────────────────────┤
│  DESTINATION HERO: Ciudad, país, coordenadas   │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐       │
│  │ LAT/LON  │ │ HEMISFERIO│ │ ZONA HOR │       │
│  └──────────┘ └──────────┘ └──────────┘       │
├─────────────────────────────────────────────────┤
│  ┌───────────────────┐ ┌───────────────────┐   │
│  │  📡 PRONÓSTICO    │ │  ⚠️ PEOR CASO     │   │
│  │  (forecast real)  │ │  (30 años hist)   │   │
│  │                   │ │                   │   │
│  │  tabla día/día    │ │  tabla día/día    │   │
│  │  con iconos       │ │  con badges rain  │   │
│  └───────────────────┘ └───────────────────┘   │
├─────────────────────────────────────────────────┤
│  🔥 INDEX DE FRUSTRACIÓN                        │
│  Barra de riesgo 0-100% + veredicto texto       │
│  "¿Cuántos días de lluvia esperar?"             │
├─────────────────────────────────────────────────┤
│  💡 RECOMENDACIONES                            │
│  Cards: Plan B indoor, qué empacar, tips       │
├─────────────────────────────────────────────────┤
│  FOOTER: Datos de Open-Meteo, créditos        │
└─────────────────────────────────────────────────┘
```

**Responsive:** En móvil, las dos tarjetas de Pronóstico y Peor Caso se apilan verticalmente. El layout es una columna única con spacing generoso (24-32px entre secciones).

## Elevation & Depth

Sin sombras dramáticas. El hierarchy viene del color de fondo, no de elevación 3D.

- **Cards:** `surface` + `border: 1px solid {border}`. Nada de box-shadow.
- **Hover states:** background sube un nivel (surface → surface-raised).
- **Focus:** ring de 3px en primary con 15% opacidad.
- **Badges/chips:** semi-transparentes (15% opacidad de color base).

## Shapes

- **Radio base:** 8px para inputs, botones, chips. 16px para cards. 24px para containers mayores.
- **Sin círculos completos** — la app es angular, técnica, no amigable-cute.
- **Divisores horizontales** de 1px entre secciones.
- **Iconos:** Lucide Icons — estilo consistente con stroke width 1.5.

## Components

### Search Block
El centro de la UI. Ciudad como input principal (autocomplete con geocoding de Open-Meteo), fechas como date pickers nativos. Botón de submit prominente en primary.

Estados: default → loading (spinner en botón, inputs deshabilitados) → results → error (mensaje inline en rojo).

### Destination Hero
Aparece tras la búsqueda. Ciudad en display grande, país debajo en text-secondary. Tres stat-blocks en row: lat/lon, hemisferio, zona horaria. Iconos pequeños de Lucide.

### Comparison Cards
Dos cards lado a lado (stack en mobile).

**Card Pronóstico:** fondo surface. Título "📡 PRONÓSTICO" en label uppercase. Tabla día-a-día: fecha | icono | temp max/min | precipitación. Iconos: ☀️🌤️⛅🌦️🌧️⛈️.

**Card Peor Caso:** fondo surface-raised (levemente distinta para énfasis). Título "⚠️ PEOR CASO HISTÓRICO" en label uppercase con chip-warning. Tabla con los mismos campos. Para cada día, badge de probabilidad de lluvia si >50%.

### Frustration Index
Barra de progreso horizontal 0-100%. El fill usa gradiente: verde (#22C55E) → amarillo (#F59E0B) → rojo (#EF4444) según el valor.

Debajo: veredicto en texto. 0-30%: "Buena suerte. Histórico favorable." 31-60%: "Empaca un paraguas de repuesto." 61-100%: "Revisa tu seguro de viaje."

### Recommendation Cards
Grid de 3 cards. Contenido: "🏠 Plan B Indoor", "🎒 Qué empacar", "📅 Vale la pena?" Cada una con icono, título y 1-2 líneas de texto específico según los datos del destino.

### Loading State
Durante el fetch: el botón muestra un spinner (emoji ⏳ o spinner SVG). Las cards muestran skeleton placeholders (rectángulos con shimmer animation en surface-raised).

### Empty State
Antes de buscar: mensaje centrado "¿A dónde viajas?" con icono de globoy. Copy: "Introduce un destino y fechas para conocer el peor escenario histórico."

### Error State
Si falla la API o no encuentra ciudad: mensaje inline bajo el input con chip-warning. Copy: "No encontré esa ciudad. Revisa la ortografía."

## Do's and Don'ts

**Do:**
- Usar datos reales de Open-Meteo sin inventar números
- Respetar el tono serio — sin emojis exagerados, sin "¡Qué tiempo tan bonito!"
- Mostrar siempre ambos paneles (pronóstico + histórico) — nunca uno solo
- El Frustration Index debe ser prominente, no un detalle pequeño
- Mobile-first — la app debe funcionar perfectamente en una mano

**Don't:**
- Usar fondo claro o blanco — rompe completamente la estética radar
- Poner más de 3 opciones de navegación — es single-purpose
- Inventar datos de ejemplo cuando no hay results — mostrar estado vacío claro
- Usar gradientes llamativos o colores neón — la paleta es disciplinada
- Ocultar la fuente de datos — Open-Meteo attribution visible en footer
