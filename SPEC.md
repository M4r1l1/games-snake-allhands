# Games Snake — All Hands Julio 🎮📼

Snake tipo NOKIA para presentar los logros del equipo de Monoku Games en el All Hands de Julio.

## Cómo funciona
- Un solo archivo `index.html`, se abre en el navegador. Sin instalar nada.
- Pantalla completa, controles de teclado (flechas / WASD). Pensado para proyectar.
- Estilo NOKIA (LCD verde) con toque submarino: la "snake" es un submarino.
- 6 niveles. En cada nivel primero comes varias **burbujas** (3 + nº de nivel) para que
  aparezca el **item especial** (📼). Al comerlo aparece una **tarjeta con el logro**
  del equipo (con polaroids detrás), y luego pasas al siguiente nivel.
- Hay **obstáculos** que debes esquivar: cada uno es un **cúmulo de ladrillos** (dominó, L,
  línea o 2×2) que forma un bloque más grande. La cantidad de cúmulos escala con el nivel.
  Al chocar se consume una **vida** (3 corazones pixel, visibles en el HUD y las pantallas).
  Mientras queden vidas, la culebra **parpadea en el lugar** y reaparece sola (rápido, sin
  pantalla), conservando el avance (burbujas, casete, obstáculos y puntaje). Solo al gastar
  la **última vida** aparece la pantalla **"GAME OVER"**: **SÍ** reinicia el juego (vidas a 3,
  desde el nivel 1), **NO** vuelve al inicio.
- Cada nivel es un poco más rápido.
- Al chocar (pared o a sí mismo) se reintenta el nivel actual (no se pierde el progreso).
- Al terminar los 6 niveles: pantalla de victoria con **reconocimientos** (Yeison, Lina, Ale)
  y los **retos que vienen**.

## Los 6 niveles (logros, del Notion)
1. 🧭 Un norte y primer plan de desarrollo del área de Games
2. 📖 Versión robusta con nuevas mecánicas narrativas (Yeison)
3. 🎨 Misiones de personaje con arte propio (Elias & Mira, Draxa, Nadia)
4. 🤖 IA enemiga adaptativa que aprende al jugador
5. 🃏 Expansión del sistema de cartas + sinergias de armas
6. ⚡ Salto de rendimiento y pulido visual (~69 → ~178 FPS)

Fuente: Notion "All hands (Julio)".
