---
name: canva-video-creator
description: >
  Úsame cuando el usuario quiera crear videos en Canva Pro para un álbum, canción,
  proyecto educativo, contenido musical o cualquier video con audio + imágenes + texto.
  Activa esta skill siempre que el usuario mencione: "crear video", "video en Canva",
  "hacer un lyric video", "video para la canción", "video educativo", "video del álbum",
  "animación en Canva", "video con la letra", o quiera combinar música + imágenes + texto
  en Canva. También activa cuando el usuario tenga canciones generadas (MP3 de Suno/Udio)
  y quiera convertirlas en videos para YouTube, Instagram, TikTok o uso educativo.
---

# Canva Video Creator — Skill para Álbum Educativo

Skill especializada para producir videos educativos / musicales en **Canva Pro**,
combinando audio (MP3 de Suno/Udio), imágenes de personajes e IA, texto animado
(letras de canciones), y efectos visuales. Orientada al álbum de Luka & Dana pero
aplicable a cualquier proyecto similar.

---

## Flujo general

```
1. PREPARAR assets (audio, imágenes, letra)
2. ELEGIR plantilla en Canva
3. CONSTRUIR el video (slides + animaciones + texto)
4. SINCRONIZAR audio con las secciones
5. EXPORTAR (MP4 1080p)
6. PUBLICAR o compartir
```

Antes de comenzar, pregunta al usuario:
- ¿Ya tiene el MP3 de la canción descargado?
- ¿Tiene imágenes de los personajes o necesita generarlas?
- ¿Para qué plataforma es el video? (YouTube 16:9 / Instagram 9:16 / TikTok 9:16)
- ¿Quiere lyric video (letra en pantalla) o video con imágenes/animaciones?

---

## PASO 1 — Preparar los assets

### Audio (MP3)
- Descarga el MP3 desde Suno: **"…" → Download → Audio**
- Nómbralo: `01_el_portal_del_barrio.mp3`
- Guarda todos los MP3 en una carpeta: `Album_Luka_Dana/Audio/`

### Imágenes de personajes
Genera las imágenes ANTES de abrir Canva. Opciones gratuitas:

| Personaje | Prompt sugerido para generador de imágenes |
|-----------|-------------------------------------------|
| Luka | `cartoon boy explorer, purple hoodie, bright eyes, friendly smile, Gorillaz art style, colorful, kids illustration` |
| Dana | `cartoon girl adventurer, orange outfit, confident smile, Gorillaz art style, colorful, kids illustration` |
| Rex | `blue friendly dinosaur, cute T-rex, cartoon style, no scary features, bright colors, kids illustration` |
| Dafne | `purple dragon girl, friendly, wings, Gorillaz cartoon style, kids illustration` |
| Baby Gon | `small baby dragon, green, cute, cartoon style, kids illustration` |
| Milo | `brown puppy cartoon, happy, fluffy, kids illustration, Gorillaz style` |
| Itzel | `wise cat cartoon, silver/grey, big eyes, smart expression, kids illustration` |

**Dónde generarlas (gratis):**
- **Adobe Firefly** → firefly.adobe.com (mejor calidad)
- **Ideogram** → ideogram.ai (muy fiel al estilo)
- **Leonardo AI** → leonardo.ai (gratis con cuenta)

Descarga en PNG con fondo transparente si es posible.

---

## PASO 2 — Abrir Canva Pro y elegir plantilla

### Formato según plataforma:
| Destino | Formato Canva | Dimensiones |
|---------|--------------|-------------|
| YouTube | Presentación / Video | 1920×1080 (16:9) |
| Instagram Reels / TikTok | Video móvil | 1080×1920 (9:16) |
| Uso educativo general | Presentación | 1920×1080 |

### En Canva:
1. Ir a **canva.com** → **Crear un diseño**
2. Buscar: `"video musical"` o `"lyric video"` en plantillas
3. Elegir una plantilla oscura/colorida → **Personalizar**
4. O empezar en blanco: **Crear diseño → Video (1920×1080)**

---

## PASO 3 — Estructura de slides por canción

Cada canción = ~8–12 slides en Canva. Estructura recomendada:

```
[Slide 1] — Portada (título + personaje principal)
[Slide 2] — Intro (2–4 líneas de letra)
[Slide 3] — Verso 1 (personaje + letra)
[Slide 4] — Verso 1 cont.
[Slide 5] — Pre-coro (transición visual)
[Slide 6] — CORO (texto grande + colores vibrantes)
[Slide 7] — CORO cont.
[Slide 8] — Verso 2 (otro personaje)
[Slide 9] — Bridge (momento especial / mantra)
[Slide 10] — Coro final
[Slide 11] — Outro (fade, todos los personajes)
[Slide 12] — Créditos / Logo
```

### Timing por slide:
- Intro/Portada: 5–8 segundos
- Versos: 10–15 segundos por slide
- Coros: 12–18 segundos
- Outro: 5–8 segundos
- **Total objetivo: 2:30 – 3:00 minutos**

---

## PASO 4 — Diseño visual en Canva

### Paleta de colores del álbum Luka & Dana:
```
Fondo principal:   #0A0A1A  (azul muy oscuro / cosmos)
Acento morado:     #7C3AED
Acento cyan:       #06B6D4
Acento rosa:       #EC4899
Dorado:            #F59E0B
Verde lima:        #84CC16
Blanco texto:      #F1F0FF
```

### Tipografía recomendada en Canva:
- **Títulos/Letras principales:** Fredoka One, Nunito ExtraBold, o Baloo 2
- **Texto secundario:** Nunito Regular
- **Tamaño mínimo:** 48pt para letras de canciones (legible en pantalla)

### Animaciones de texto en Canva:
Para las letras de canciones, usa:
- **Aparición:** "Fade" o "Pop" (suave, no distrae)
- **Salida:** "Fade out"
- **Para el CORO:** "Scale" o "Bounce" (más energía)
- **Para mantras:** "Typewriter" (aparece letra por letra)

### Fondos por canción:
| Canción | Fondo sugerido |
|---------|---------------|
| 01 El Portal del Barrio | Portal de luz, galaxia, destellos |
| 02 Ruge con Swing | Selva/ciudad con colores neón |
| 03 Las Vocales del Clan | Letras gigantes flotando, colorido |
| 04 Burbujas en el Clan | Baño con burbujas, azul y blanco |
| 05 Counting on the Crew | Paisaje urbano, equipo unido |
| 06 El Barrio en el Espacio | Espacio exterior, planetas, estrellas |
| 07 Two Blue Shoes | Mañana soleada, colores cálidos |
| 08 Numbers in the Bone | Parque, tierra, huesos animados |
| 09 T-Rex Rosa en el Asfalto | Calle urbana colorida, asfalto |
| 10 Fin del Teatro | Teatro con cortinas, escenario |
| 11 Dragon Park Groove | Parque mágico, dragones bailando |
| 12 El Clan Cierra el Portal | Noche estrellada, luna, cálido |

**En Canva Pro:** busca fondos en "Elementos → Videos" o usa
la función **"Fondo con IA"** (Magic Media) para generar fondos personalizados.

---

## PASO 5 — Subir y sincronizar el audio

### Subir el MP3:
1. Panel izquierdo → **"Subidas"** (Uploads)
2. **"Subir archivos"** → selecciona el MP3 de la canción
3. Espera a que cargue completamente

### Agregar audio al video:
1. Haz clic en el MP3 subido → se agrega al timeline
2. En el **timeline** (barra inferior) verás la onda de audio
3. Arrastra el audio para que empiece en el slide 1

### Sincronizar letra con música (método manual):
1. Reproduce el video en Canva (▶️)
2. Pausa donde empieza cada sección de letra
3. Ajusta la duración de cada slide arrastrando en el timeline
4. Regla práctica:
   - Si la canción dura 2:30 min = 150 segundos
   - Con 12 slides = promedio 12.5 seg por slide
   - Ajusta más tiempo a los coros, menos a las transiciones

### Sincronización automática (Canva Pro — Beat Sync):
1. Selecciona todos los slides
2. Clic derecho → **"Sincronizar con música"** o busca **"Beat Sync"**
3. Canva ajusta automáticamente los cortes al ritmo
4. ⚠️ Revisa manualmente que la letra coincida

---

## PASO 6 — Elementos extra en Canva Pro

### Usar Magic Media (IA de Canva):
- Panel izquierdo → **"Apps"** → **"Magic Media"**
- Genera imágenes de personajes directamente en Canva:
  ```
  Prompt: "Luka, cartoon boy explorer, purple hoodie,
  Gorillaz art style, transparent background, kids illustration"
  ```

### Stickers y elementos animados:
- Busca en Elementos: `"stars animated"`, `"sparkle"`, `"cartoon dragon"`
- Filtra por **"Animado"** para elementos que se muevan solos

### Transiciones entre slides:
- Clic en la línea entre dos slides → **"Transición"**
- Recomendadas: **"Fade"**, **"Slide"**, o **"Dissolve"**
- Evita transiciones muy llamativas que distraigan de la letra

---

## PASO 7 — Exportar el video

### Configuración de exportación:
1. Botón **"Compartir"** (arriba derecha) → **"Descargar"**
2. Formato: **MP4**
3. Calidad: **1080p** (Canva Pro lo permite)
4. ✅ Activar: **"Incluir audio"**
5. Páginas: **"Todas las páginas"**
6. Clic **"Descargar"**

### Tiempo estimado de exportación:
- Video de 2:30 min → 2–5 minutos de renderizado
- Canva Pro tiene renderizado prioritario

### Nombres de archivo recomendados:
```
01_El_Portal_del_Barrio_VIDEO.mp4
02_Ruge_con_Swing_VIDEO.mp4
... etc.
```

---

## PASO 8 — Workflow completo para las 12 canciones

### Orden recomendado de producción:
1. **Haz una plantilla maestra** con el diseño del Track 01
2. Usa **"Duplicar diseño"** para cada canción nueva
3. Solo cambia: fondo, colores del texto, letra, imagen de personaje, audio
4. Esto te ahorra 80% del tiempo

### Crear la plantilla maestra:
1. Diseña Track 01 completamente
2. Clic en **"⋯"** del diseño → **"Duplicar"**
3. Renombra: `"Track 02 — Ruge con Swing"`
4. Cambia solo los elementos específicos de esa canción

### Tiempo estimado por canción (con plantilla):
- Canción 1 (plantilla): 45–60 minutos
- Canciones 2–12 (con plantilla): 15–20 minutos cada una
- **Total álbum completo: ~5–6 horas**

---

## Referencia rápida de comandos Canva

| Acción | Cómo hacerlo |
|--------|-------------|
| Subir audio | Subidas → Subir archivos → MP3 |
| Ver timeline | Parte inferior de la pantalla |
| Ajustar duración slide | Arrastra el borde del slide en el timeline |
| Animar texto | Selecciona texto → "Animar" en barra superior |
| Fondo con IA | Apps → Magic Media → Imagen |
| Beat Sync | Seleccionar todo → clic derecho → Sincronizar música |
| Exportar MP4 | Compartir → Descargar → MP4 → 1080p |
| Duplicar diseño | ⋯ en el diseño → Duplicar |
| Transparencia elemento | Seleccionar → icono de tablero de ajedrez |

---

## Leer también

- `references/paleta-personajes.md` — Colores y estilos visuales de cada personaje
- `references/letras-formateadas.md` — Las 12 letras listas para copiar slide por slide
- `references/prompts-imagenes.md` — Prompts de IA para generar cada personaje

---

## Notas importantes

- **Canva Pro** incluye: videos en MP4 1080p, Beat Sync, Magic Media IA,
  biblioteca premium de elementos animados, y acceso a millones de fotos/videos.
- El audio en Canva tiene un **límite de 30 minutos** por diseño — más que suficiente.
- Si el video final tiene cortes de audio, cierra y vuelve a abrir Canva antes de exportar.
- Para YouTube: agrega subtítulos/captions subiendo el video y usando YouTube Studio
  (auto-genera subtítulos en español e inglés).
