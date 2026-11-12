# Ajedrez

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![MIT](https://img.shields.io/badge/Licencia-MIT-green)](LICENSE)

[Español](#español) · [English](#english)

---

## Español

### Índice

- [Descripción](#descripción)
- [Demo](#demo)
- [Requisitos](#requisitos)
- [Cómo jugar](#cómo-jugar)
- [Controles](#controles)
- [Alcance](#alcance)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Licencia](#licencia)

### Descripción

Ajedrez jugable en el navegador con **HTML, CSS y JavaScript** puros: sin frameworks, sin compilación y sin dependencias. Tablero marrón y blanco (sin textura de madera), animaciones suaves al mover, resaltado de movimientos y capturas, y una barra lateral para cambiar la perspectiva o reiniciar la partida.

### Demo

**Juega ahora:** <https://alberto2005-coder.github.io/Ajedrez/>

### Requisitos

- Un navegador moderno (Chrome, Edge, Firefox o Safari).
- Nada más: no hay `npm install` ni proceso de build.

Para ejecutarlo en local, sirve la carpeta por HTTP:

```bash
git clone https://github.com/alberto2005-coder/Ajedrez.git
cd Ajedrez
python -m http.server 8000
```

Y abre <http://localhost:8000>. Abrir `index.html` con doble clic también funciona en la mayoría de navegadores.

### Cómo jugar

1. Haz clic en una pieza: se resaltan sus movimientos posibles.
2. Haz clic en una casilla válida para moverla.
3. Las capturas y los últimos movimientos quedan resaltados.
4. Usa la barra lateral para ver el tablero desde el lado de las blancas o de las negras.
5. Reinicia la partida desde la misma barra cuando quieras.

### Controles

| Control | Acción |
|---|---|
| Clic en una pieza | Seleccionarla y ver sus movimientos |
| Clic en una casilla válida | Mover la pieza seleccionada |
| Clic en la misma pieza | Deseleccionarla |
| Barra lateral | Cambiar perspectiva, reiniciar, mostrar u ocultar movimientos |

### Alcance

Implementa movimiento legal por pieza, **enroque**, **captura al paso**, **jaque** y **ahogado**, con resaltado de movimientos y capturas. No incluye promoción de peón ni motor de inteligencia artificial: es un tablero para jugar entre dos personas.

### Estructura del proyecto

```text
Ajedrez/
├── index.html    # Tablero, barra lateral y estructura de la interfaz
├── styles.css    # Tema marrón/blanco, animaciones y diseño responsive
├── main.js       # Reglas de movimiento, selección y render del tablero
├── logo.png
├── LICENSE
└── README.md
```

### Licencia

**MIT** — puedes usar, modificar y distribuir el proyecto, incluso con fines comerciales, conservando el aviso de copyright. Consulta [LICENSE](LICENSE).

---

## English

### Table of contents

- [Overview](#overview)
- [Demo](#demo)
- [Requirements](#requirements)
- [How to play](#how-to-play)
- [Controls](#controls)
- [Scope](#scope)
- [Project structure](#project-structure)
- [License](#license)

### Overview

A playable browser chess game built with plain **HTML, CSS and JavaScript**: no frameworks, no build step, no dependencies. Brown-and-white board (no wood texture), smooth move animations, move and capture highlighting, and a sidebar to flip the board or restart the game.

### Demo

**Play now:** <https://alberto2005-coder.github.io/Ajedrez/>

### Requirements

- A modern browser (Chrome, Edge, Firefox or Safari).
- Nothing else: no `npm install`, no build pipeline.

To run it locally, serve the folder over HTTP:

```bash
git clone https://github.com/alberto2005-coder/Ajedrez.git
cd Ajedrez
python -m http.server 8000
```

Then open <http://localhost:8000>. Double-clicking `index.html` also works in most browsers.

### How to play

1. Click a piece: its legal moves are highlighted.
2. Click a valid square to move it.
3. Captures and the latest moves stay highlighted.
4. Use the sidebar to view the board from White's or Black's side.
5. Restart the game from the same sidebar whenever you want.

### Controls

| Control | Action |
|---|---|
| Click a piece | Select it and show its moves |
| Click a valid square | Move the selected piece |
| Click the same piece | Deselect it |
| Sidebar | Flip perspective, restart, show or hide moves |

### Scope

It implements legal piece movement, **castling**, **en passant**, **check** and **stalemate**, with move and capture highlighting. Pawn promotion and an AI engine are out of scope: this is a two-player board.

### Project structure

```text
Ajedrez/
├── index.html    # Board, sidebar and interface markup
├── styles.css    # Brown/white theme, animations and responsive layout
├── main.js       # Move rules, selection and board rendering
├── logo.png
├── LICENSE
└── README.md
```

### License

**MIT** — you may use, modify and distribute the project, including commercially, as long as the copyright notice is kept. See [LICENSE](LICENSE).
