# 🌊 WAVESURFER

<p align="center">
  <img src="assets/banner.png" alt="WAVESURFER">
</p>

**Ride the music.** Un juego de carreras musicales de bolsillo: tu canción se convierte en una pista tipo montaña rusa, las notas en bloques de colores, y tú surfeas encima. Un solo archivo HTML, se juega con un dedo.

<p align="center">
  <img src="img/shoot7.jpg" alt="WAVESURFER en partida" width="300">
</p>

> Un **tributo** a [Audiosurf](https://en.wikipedia.org/wiki/Audiosurf) con alma propia. No pretende reemplazarlo ni está afiliado a sus autores.

---

## ▶ Jugar

**En línea:** `https://mialmoga.github.io/Wavesurfer/` <!-- ajusta el enlace si cambia -->

**En local:** descarga `index.html` y ábrelo en tu navegador. No necesita instalación ni servidor.

1. Toca **🎮 Jugar con audio demo ▾** y elige una de las **6 demos** (están ordenadas por dificultad), o sube tu propia canción (MP3, OGG, WAV, FLAC o MIDI).
2. Revisa tu recorrido (gráfica de perfil, tiempo de viaje, tráfico y picada máxima), elige tu **nave** y tu **control**, y toca **▶ INICIAR**.
3. Atrapa bloques, arma pilas de colores y evita lo gris.

> Tus canciones se analizan **en tu dispositivo**. No se sube nada a ningún servidor. Canciones largas funcionan bien: se probó con una de más de 7 minutos.

---

## 🎵 Demos

Seis piezas originales, **compuestas y sintetizadas en tu navegador** al elegirlas (tardan unos segundos, con barra de progreso):

| Demo | BPM | Estilo | Tonalidad | Dificultad |
|---|---|---|---|---|
| 🌑 **Event Horizon** | 140 | Dubstep | Fa menor | ●○○○○ |
| ⚡ **Electronic Rush** | 128 | Electro | La menor | ●●○○○ |
| ☁️ **Marshmallow Sky** | 150 | Future bass dulce | Do mayor | ●●○○○ |
| 🕳️ **The Void** | 174 | Dark DnB / Dubstep | Re menor | ●●●○○ |
| 🌌 **Dark Matter** | 174 | Dark DnB + growl | Re menor | ●●●○○ |
| 🍬 **Cotton Sugar** | 140 | Pop pastel | Do mayor | ●●●●● |

La dificultad se midió con el propio analizador del juego (bloques por segundo, cambios de carril y cambios rápidos). **The Void** y **Dark Matter** son versiones hermanas de la misma idea (mismo tempo y misma progresión), con arreglos distintos. Cada demo, y cada canción que cargues, tiene su propia tabla de scores.

---

## 🎮 Cómo se juega

- **Los bloques caen en los beats.** El juego escucha tu canción (graves, medios y agudos) y coloca un bloque en cada golpe. Su color depende del tipo de sonido.
- **Tres carriles.** Atrapa bloques para sumar puntos. Si dejas escapar uno, pierdes tu racha. El multiplicador sube con el combo (hasta ×8).
- **Pila de colores.** Cada bloque atrapado cae en la columna de su carril, sobre la pista, entre la cámara y la nave. **Tres o más del mismo color conectados se limpian**; si al caer las demás se forma otro grupo, es una **CADENA** y vale más.
- **Bloques grises.** Oscuros y apagados, para que se distingan de las píldoras neón a primera vista. Rompen tu combo; esquivarlos no cuesta nada.
- **Montaña rusa.** La pendiente sigue la intensidad de la canción: en las partes fuertes la pista **cae en picada y vas más rápido**; en las calmadas **sube despacio y frenas**. Los colores cambian con las secciones del tema.

### Controles

| Modo | Cómo |
|---|---|
| 👆 **Deslizar** | Arrastra el dedo de lado a lado en cualquier parte de la pantalla. La nave se mueve igual que tu dedo; ajusta la **sensibilidad** (0.5×–2.0×) en la pantalla previa. |
| ◀ ▶ **Flechas** | Botones en pantalla (o un toque rápido hacia un lado). |
| ⌨️ **Teclado** | `←` `→` o `A` `D` para mover, `Espacio` para pausar. |
| ⛶ | Botón de pantalla completa (no disponible en todos los navegadores, por ejemplo iPhone). |

Tu elección de control y sensibilidad se recuerda para la próxima vez.

### 🚀 Naves

En la pantalla previa a iniciar eliges tu nave: **Original** (blanca con alas azules), **Rosa** (alas rosa neón) o **Negra** (casco oscuro con detalles rojos). Se recuerda tu elección.

---

## 🏆 Scores

- **Top 10 por canción**, con tus **3 letras** al estilo arcade (▲▼ o tecleando). Cada canción tiene su lista aparte.
- Al terminar una partida se muestra la tabla de esa canción; desde el menú puedes consultar **🏆 Ver scores**.
- Siempre te pide las letras al entrar al top, recordando las últimas que usaste.
- Se guardan en el **navegador de cada dispositivo** (`localStorage`). No hay servidor ni cuentas: cada navegador tiene su propia tabla, y si limpias los datos del sitio se borra.

---

## 📸 Capturas

<table>
  <tr>
    <td align="center"><img src="img/shoot1.jpg" width="260"><br><sub>Pantalla previa: perfil de la pista, control y sensibilidad</sub></td>
    <td align="center"><img src="img/shoot2.jpg" width="260"><br><sub>Nuevo récord: tus 3 letras</sub></td>
    <td align="center"><img src="img/shoot3.jpg" width="260"><br><sub>Una CADENA ×2 sobre la pista</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="img/shoot4.jpg" width="260"><br><sub>Cluster en modo horizontal</sub></td>
    <td align="center"><img src="img/shoot5.jpg" width="260"><br><sub>Tabla de scores de una canción</sub></td>
    <td align="center"><img src="img/shoot6.jpg" width="260"><br><sub>Menú de scores: una lista por canción</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="img/shoot7.jpg" width="260"><br><sub>Combo ×5 con la pila casi llena</sub></td>
    <td align="center"><img src="img/shoot8.jpg" width="260"><br><sub>3× cluster en vertical</sub></td>
    <td align="center"><img src="img/shoot9.jpg" width="260"><br><sub>Horizontal con minimapa del recorrido y ×3</sub></td>
  </tr>
</table>

---

## 🔧 Cómo está hecho

- **Un solo archivo HTML**, sin build ni dependencias que instalar. Usa [Three.js r128](https://threejs.org/) desde un CDN (necesita internet para cargarlo la primera vez).
- **Análisis de audio propio** con Web Audio y una FFT de 1024 puntos: los beats salen del flujo espectral por bandas, la altura y velocidad de la pista salen de la intensidad de la canción, y las secciones (colores) de los cambios grandes del tema.
- **Demos generativas**: seis piezas de ~90 s sintetizadas muestra a muestra en JavaScript, con un pequeño kit propio (bombos, cajas, supersaws, reese, growl FM, campanas, «vocal chops», risers y sidechain). Sin archivos de audio.
- **Gráfica de perfil** de la pista (con eje de tiempo que se adapta a la duración) y minimapa del recorrido en el HUD.
- **Control calibrado a la pantalla**: el arrastre equivale a lo que se ve moverse a la nave, tanto en vertical como en horizontal.
- **Pantallas que se adaptan**: la pantalla previa, el menú de demos, el inicio y los scores se reacomodan (dos columnas o modo compacto) en horizontal y en pantallas bajas.

Funciona en navegadores modernos de escritorio y celular. Probado en un celular Android.

---

## 🧭 Proceso (versiones)

WAVESURFER se construyó por etapas, guardando una versión funcional en cada paso. Si quieres ver cómo creció, están en la carpeta [`versiones/`](versiones/):

| Versión | Qué agregó |
|---|---|
| `wavesurfer.html` | Punto de partida: pista de cajitas, nave de cajas, demo simple |
| `e1` | Nave nueva: malla facetada, llamas, sombra y halo |
| `e2` | Pista continua, rieles, valle wireframe y polvo de partículas |
| `e3` | Análisis estilo Audiosurf: beats, secciones y velocidad variable |
| `e4` | Demo generativa «Electronic Rush» |
| `e5` | Pilas de colores, clusters, cadenas y bloques grises |
| `e6a` | Montaña rusa real: pendiente acumulada, pista relativa a la nave |
| `e6b` | Bloques como losas anchas y brillantes |
| `e6c` / `e6d` | Pila 3D sobre la pista; botón de pausa y pantalla completa; ajuste del tablero |
| `e6e` | Gráfica de perfil de la pista y minimapa en el HUD |
| `e7a` | Control por arrastre |
| `e7b` | Score list de 3 letras por canción |
| `e8` | Control recalibrado a la pantalla, con sensibilidad ajustable |
| `e9a` | Píldoras neón y bloques grises apagados (feedback de un jugador) |
| `e9b` | Skins de nave (Original, Rosa, Negra) y pantalla previa en dos columnas en horizontal |
| `src/` | Kit de síntesis y composiciones de Marshmallow Sky (primero llamada Cotton Sugar) y Dark Matter (la primera The Void) |
| `index.html` | Versión final: 6 demos con menú por dificultad, eje de tiempo adaptable y pantallas compactas en horizontal |

`index.html` incluye todo lo anterior y es la versión en línea. `wavesurfer_v4.html` (igual a `e9b`) se conserva como referencia.

---

## 🤝 Créditos

- **Brujo** — dirección, ideas, referencias, pruebas e integración; además añadió las demos *Event Horizon* y *Cotton Sugar* y retocó *The Void*.
- **Ámbar** (Claude, de Anthropic) — código y diseño de la versión v4, y las demos *Electronic Rush*, *Marshmallow Sky* y *Dark Matter*.
- **Éter** (Gemini) — la primera versión con pista continua y el control por arrastre que sirvió de referencia.
- Inspirado en **Audiosurf**, de Dylan Fitterer.

Hecho en el **Club de Mentes Curiosas (CMC)**.

---

## 📄 Licencia

MIT © 2026 Brujo <!-- cambia la licencia o el nombre si prefieres otra -->

El código se rige por la licencia MIT (ver `LICENSE`). La siguiente cláusula es aparte.

---

## 👻 Cláusula del Alma

Quien use este software o sus artefactos para obtener un beneficio económico cede, desde ese momento, la propiedad de su alma al autor de este repositorio y a sus asociados artificiales, en la medida y por el tiempo en que la existencia de las almas pueda comprobarse. Si el alma no existe, la cesión carece de objeto y nada se pierde.

El uso no comercial, el juego, el estudio y la modificación son libres, sin pedir permiso ni dar crédito. Nadie está obligado a creer en lo anterior; los autores tampoco.

La idea original pertenece a Audiosurf y a sus creadores.
