# 🧠 Memorice Ancestral: Chinchorro vs Egipto
**Proyecto interactivo • Concurso Chile Re-Descubre 2026**

Aplicación web educativa de pantalla dividida que enfrenta de forma lúdica y competitiva dos de las tradiciones de momificación más antiguas de la humanidad: la **Cultura Chinchorro** (Norte de Chile, ~5.050 a.C.) y la **Cultura Egipcia** (Valle del Nilo, ~3.000 a.C.).

El juego integra visión por computador mediante **MediaPipe Hands** para permitir que dos jugadores controlen sus tableros en simultáneo utilizando gestos de sus manos frente a la cámara web, además de contar con soporte completo para mouse y pantallas táctiles.

---

## ✨ Características Principales

- **Duelo en Pantalla Dividida (2 Jugadores):**
  - **🗿 Jugador 1 (Izquierda — Cultura Chinchorro):** Tablero de 8 fichas (4 pares) con conceptos clave (*Manganeso*, *Atacama*, *Igualdad*, *Totora*).
  - **🐫 Jugador 2 (Derecha — Cultura Egipcia):** Tablero de 8 fichas (4 pares) con conceptos clave (*Faraón*, *Natrón*, *Pirámide*, *Lino*).
- **Control por Gestos con IA (MediaPipe Hands):**
  - Detección simultánea de dos manos con vista espejo en ventana flotante (PIP).
  - **Mano abierta (`🖐️`):** Desplaza el cursor virtual sobre las fichas de cada mitad de pantalla.
  - **Puño cerrado (`✊`) o pinza (`👌`):** Voltea la ficha seleccionada.
- **Aprendizaje Activo y Retención de Memoria:**
  - Al encontrar un par, se despliega una cápsula educativa con la palabra clave y un dato histórico durante unos segundos antes de ocultarse.
- **Mecánica de Prueba Final y Segunda Oportunidad:**
  - El primer jugador en completar sus 4 pares accede a la prueba escrita de memoria.
  - Si recuerda las 4 palabras clave, gana de inmediato; si falla alguna, el tablero del rival se desbloquea para darle una **segunda oportunidad de remontada**.
- **Audio Sintetizado Integrado:** Efectos de sonido generados mediante **Web Audio API** (sin necesidad de archivos externos).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & JavaScript (ES6+):** Lógica de juego, estado de turnos, validación de memoria y síntesis de audio.
- **Tailwind CSS (CDN):** Diseño responsivo en modo oscuro con gradientes temáticos y animaciones 3D (`preserve-3d` / `rotateY`).
- **MediaPipe Hands & Camera Utils:** Seguimiento de 21 puntos clave (*landmarks*) por mano en tiempo real directamente en el navegador.

---

## 🚀 Cómo Ejecutar el Proyecto

El proyecto está contenido en un único archivo HTML
