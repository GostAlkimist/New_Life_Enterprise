# New Life Enterprise

Simulador empresarial de selección y entrenamiento laboral · Gestión Tecnológica Digital · Universidad del Valle.

Este repositorio solo publica el simulador ya compilado (`index.html`) con GitHub Pages para incrustarlo en Google Sites. El código fuente está en un repositorio privado.

Para actualizarlo: compila el proyecto (`npm run build`) y reemplaza `index.html` por `dist/new-life-enterprise.html`.

Voces: las 91 locuciones de personajes y narrador están en `audio/voces/` y el `index.html` las carga desde aquí (sin internet usa la voz del navegador). Al actualizar, copia también `audio/voces/` del repositorio fuente.

Plan B (audio por enlace): `plan-b-audio-externo.html` pesa 1,69 MB y carga la música desde `audio/` en este mismo sitio. Guía completa: `docs/publicacion/guia-google-sites.md` del repositorio fuente.
