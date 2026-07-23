# Carrete: Sample Reels Production Plan (Weekend Build)

Goal: 3 finished 9:16 sample reels (restaurante, hotel, gimnasio), 15-20s each, 1080p, no watermark, commercially clean. These are the calling card that replaces free videos: they must look expensive.

**Stack:** Kling Standard (~8 €/mes, licencia comercial) + Pexels/Pixabay (footage real gratis) + CapCut desktop (montaje, gratis).

**Budget check:** each 5s Kling generation costs roughly 20-35 credits depending on model/mode. Standard gives ~660/mes. Plan: ~2 AI shots per reel x 3 reels x 3 attempts each = ~18 generations. Fits with room to spare.

---

## 0. One-time setup (30 min)

1. Create the Kling account, subscribe Standard, set output to **9:16**.
2. Install **CapCut desktop** (not mobile: desktop exports 1080p without watermark).
3. Create Drive folder `Carrete/Samples/` with subfolders `restaurante/`, `hotel/`, `gym/`, each containing `stills/`, `ai-clips/`, `stock/`, `final/`.
4. Download the stock clips listed per reel below into `stock/` before opening Kling. Cut from real footage first; AI only for the 1-2 wow moments.

**Kling settings for every generation:** Image-to-Video where possible (matches the future client workflow: their photos in, video out), 5s, 9:16, highest quality model your plan allows, motion strength medium-low for food/interiors (high motion = AI artifacts).

**Iteration rule:** generate 2-3 variants per shot, pick the best, move on. Do not chase perfection on one prompt; artifacts hide badly in food close-ups and hands. If a shot fails 3 times, replace it with stock.

---

## 1. Reel Restaurante: "El plato estrella" (~18s)

The flagship sample. Nail this one first; it is the vertical you will pitch first.

**Structure (cuts on the beat):**

| Segundos | Shot | Fuente |
|---|---|---|
| 0-3 | Extreme close-up del plato, steam, slow push-in. Texto: "El plato del que todo el barrio habla 👀" | **Kling AI** (shot A) |
| 3-7 | 2-3 cortes rápidos de otros platos / manos emplatando | Pexels stock |
| 7-11 | Ambiente: mesa con gente brindando / camarero sirviendo | Pexels stock |
| 11-15 | Barra o fachada acogedora de noche, luz cálida | Pexels stock o Kling (shot B) |
| 15-18 | Cierre: still del plato + logo Carrete + "📍 Madrid · Reserva en bio" | CapCut (imagen + texto) |

**Kling shot A (image-to-video).** Busca en Pexels *photos*: "gourmet dish closeup steam" o "ramen bowl steam". Sube la foto y usa este prompt:
> Cinematic slow dolly push-in on the dish, gentle steam rising, warm golden restaurant lighting, shallow depth of field, subtle parallax, photorealistic, no people, no hands, 9:16 vertical.

**Kling shot B (opcional, text-to-video):**
> Cozy Spanish restaurant exterior at dusk, warm light spilling from windows, people silhouetted inside, slow cinematic pan, Madrid street ambience, photorealistic, 9:16 vertical.

**Pexels searches (vídeo, filtra Vertical):** "chef plating food", "restaurant food closeup", "friends dinner toast", "waiter serving", "tapas".

**Música:** en CapCut, filtra la librería por tema "Food/Upbeat" y marca solo pistas con licencia comercial. Ritmo 90-110 BPM.

---

## 2. Reel Hotel: "Despiértate aquí" (~18s)

**Structure:**

| Segundos | Shot | Fuente |
|---|---|---|
| 0-3 | Luz de mañana entrando por cortinas, cama deshecha bonita. Texto: "Imagina despertarte aquí mañana ☀️" | **Kling AI** (shot A) |
| 3-8 | Pan lento de la habitación + detalle (café, albornoz, balcón) | Pexels stock |
| 8-13 | Piscina/rooftop/desayuno con vistas | Pexels stock |
| 13-16 | Atardecer desde la terraza | Pexels stock o Kling (shot B) |
| 16-18 | Cierre: "Reserva directa, sin comisiones" + logo | CapCut |

**Kling shot A (image-to-video).** Foto de Pexels: "hotel room morning light curtains". Prompt:
> Soft morning sunlight sweeping slowly across a cozy boutique hotel room, sheer curtains moving gently in the breeze, warm inviting tones, slow cinematic camera drift, photorealistic, no people, 9:16 vertical.

**Kling shot B (text-to-video):**
> Golden hour view from a Madrid rooftop terrace, city skyline, warm sunset light, gentle slow pan, cinematic and calm, photorealistic, 9:16 vertical.

**Pexels searches:** "hotel room luxury", "hotel breakfast view", "rooftop pool", "hotel balcony sunset", "boutique hotel interior".

**Música:** chill/lounge, 70-90 BPM, calmada. El vibe es escapada, no fiesta.

---

## 3. Reel Gimnasio: "Energía" (~15s)

**Structure:**

| Segundos | Shot | Fuente |
|---|---|---|
| 0-2 | Golpe visual: atleta en acción (barbell, salto al cajón). Texto: "Tu gimnasio no tiene por qué ser aburrido 🔥" | Pexels stock |
| 2-8 | Cortes rápidos al beat: pesas, cuerdas, clase, sprint en cinta | Pexels stock |
| 8-12 | Momento wow: cámara dinámica barriendo la sala | **Kling AI** (shot A) |
| 12-15 | Comunidad: choque de manos, sonrisas + "1ª clase gratis esta semana 💪" | Pexels stock + CapCut |

**Kling shot A (text-to-video):**
> Dynamic gym b-roll, dramatic side lighting with haze, fast energetic camera sweep across modern equipment, motivational mood, high contrast, photorealistic, 9:16 vertical.

Nota: el reel de gym es el más fácil de resolver solo con stock (Pexels está lleno de material fitness espectacular). Si los créditos van justos, este reel puede ser 100% stock.

**Pexels searches:** "gym workout vertical", "crossfit battle ropes", "barbell squat", "fitness class group", "high five gym".

**Música:** enérgica, 120-140 BPM. Aquí los cortes al beat lo son todo: corta cada 1-2 segundos.

---

## 4. CapCut assembly (same recipe x3)

1. Nuevo proyecto → ratio **9:16**.
2. Arrastra los clips en orden de la tabla. Recorta cada uno a su ventana.
3. Añade la música primero y activa marcadores de beat (auto beat detection); ajusta cada corte a un beat.
4. Textos: fuente bold sans (Montserrat/Archivo Black), hook grande en segundo 0-1, entra con animación "pop" o "typewriter", máximo 2 líneas.
5. Subtítulos automáticos solo si hay voz; para estos samples no hay voz: texto manual.
6. Color: aplica el mismo filtro suave a todos los clips del reel para unificar stock + AI (calidez +5, contraste +5, saturación +3).
7. Transiciones: corte seco al beat en el 90% de los casos; máximo una transición "flash/zoom" por reel.
8. Cierre con placa de marca: fondo oscuro, logo/nombre Carrete, CTA. 2s.
9. Export: **1080p, 30fps, MP4, bitrate alto**. Nombre: `carrete-sample-restaurante-v1.mp4` etc.
10. Sube a `final/` en Drive y genera enlace compartible (es lo que se manda en el outreach).

**Etiquetado IA:** al publicar los samples en el IG de Carrete, marca "creado con IA" donde la plataforma lo pida. En el pitch, lo contamos como ventaja: "mezclamos tu material real con planos generados por IA de última generación".

---

## 5. Definition of done

- [ ] 3 MP4 1080p verticales en Drive con enlace compartible
- [ ] Ningún watermark, música con licencia comercial, stock de Pexels/Pixabay
- [ ] Cada reel abre con hook de texto en el segundo 0-1 y corta al beat
- [ ] Vistos en un móvil real antes de darlos por buenos (el 100% de los prospectos los verán en móvil)
- [ ] Subidos también al IG de Carrete como primeros posts (el perfil no puede estar vacío cuando lleguen los leads)

Time budget: setup 30 min + ~2h por reel (generación AI en paralelo mientras montas) = una tarde larga o dos cortas.
