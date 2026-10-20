# IDKC · Biblioteca de diseños y prompts (v0.1)

## Método (importante)
Las IA de imagen escriben mal el texto y casi siempre estropean los signos polacos (ę, ł, ś, ż). Por eso:
1. **La IA genera solo el gráfico**, sin texto.
2. **El texto se pone a mano** en Canva, Figma o Photopea con la fuente de marca (Big Shoulders Display, 900) y los signos correctos.
3. Se exporta según las reglas de Printful (abajo).

## Ficha técnica Printful (camisetas, sudaderas, DTG)
- PNG con fondo transparente, sRGB.
- 150 a 300 DPI al tamaño real de impresión (no ampliar imágenes pequeñas).
- Sin degradados semitransparentes, sombras suaves ni bordes difusos.
- Nombre de archivo sin dos puntos seguidos antes de la extensión.
- Gorras y bordados: pocos colores, líneas gruesas, sin detalle fino. Usar la ficha de bordado de Printful.
- Los colores muy saturados salen más apagados en prenda que en pantalla.

## Paleta (HEX)
Negro carbón `#0E0E0E` · Rojo `#D4213D` · Carmesí `#A3122A` · Hueso `#ECE6DA` · Blanco `#FFFFFF` · Latón `#B08D57` (solo bordado y detalles)

---

## A. Diseños de texto (hacer primero)
Se montan solo con tipografía. No necesitan IA.

| Código | Texto | Prenda | Notas |
|---|---|---|---|
| T1 | WE BUILT HALF OF EUROPE. WE DON'T NEED PERMISSION TO BE PROUD OF IT. | Sudadera (espalda) | "WE DON'T NEED PERMISSION" en rojo |
| T2 | FLUENT IN KURWA + [ˈkur.va] | Camiseta | Pronunciación pequeña debajo |
| T3 | DAMY RADĘ | Sudadera, gorra | Revisar la Ę |
| T4 | ROBIMY SWOJE | Camiseta | Rojo sobre negro |
| T5 | HONORARY POLAK | Pegatina, camiseta | Para el público no polaco |
| T6 | SPOKOJNIE | Pulsera, gorra | Versión elegante |
| T7 | IDKC (monograma) | Gorra bordada | Latón sobre negro |
| T8 | POLISH LESSON #1: KURWA | Camiseta | Entrada de diccionario con definición |

## B. Diseños con gráfico (prompts para IA de imagen)
Todos terminan con la cláusula de salida. Pega la cláusula al final de cada prompt.

**Cláusula de salida:** `isolated on a plain flat background, no text, no letters, no watermark, no border, high contrast, clean edges, limited flat color palette, vector-style, centered composition`

**G1 · Alas abstractas (sin copiar el símbolo de la husaria)**
`Abstract bold graphic of a pair of angular feathered wings, geometric and stylized, sharp symmetrical shapes, red and bone white on black, screen-print poster style, strong silhouette, underground streetwear aesthetic, ` + cláusula

**G2 · Rayo de la bandera**
`Sharp horizontal split design, white upper half and deep red lower half, torn paper edge along the seam, rough halftone texture, punk gig poster style, limited palette of red, white and black, ` + cláusula

**G3 · Puño de obrero (homenaje al trabajador polaco)**
`Illustration of a gloved fist holding a hammer raised overhead, constructivist propaganda poster style, bold flat shapes, thick outlines, red and bone-white on black, 1930s industrial worker poster meets hardcore band merch, ` + cláusula

**G4 · Pierogi con actitud (mascota, para pegatinas)**
`Humorous streetwear mascot: a pierogi dumpling with angry eyes and a clenched fist, thick black outlines, cel-shaded, red and white accents, sticker design, die-cut sticker style, ` + cláusula

**G5 · Mapa de la diáspora**
`Minimalist outline map of Europe with the territory of Poland filled solid red, thin dotted lines radiating outward from Poland to major cities across the continent, blueprint style, bone-white linework on black, ` + cláusula

**G6 · Sello de aprobación**
`Circular rubber stamp emblem, distressed ink texture, concentric rings, central star burst, industrial quality-control stamp look, red ink, no readable text, ` + cláusula

**G7 · Patrón para bandana, calcetines o forro de gorra**
`Seamless repeating pattern of tiny crossed hammers, small stylized wings and stars, red and bone-white on black, dense tileable pattern, ` + cláusula (aquí quitar "centered composition")

**G8 · Fondo texturizado para póster y banner**
`Dark concrete wall texture with red paint splatter and torn white paper strips, grunge, high detail, no objects, no text, suitable as background, 1:1 square`

---

## Qué evitar (Nuria)
- Ni águila blanca ni escudo oficial ni bandera oficial junto a la palabra "kurwa".
- No copiar alas de húsar, ancla del Estado Subterráneo (Kotwica) ni otros símbolos que ya usan marcas polacas. Abstraerlos.
- No usar blackletter ni iconografía con lecturas ultraderechistas.
- Comprobar que las frases no están registradas por otra marca antes de producir.
- Revisar que lo que genere la IA no se parezca a una marca o personaje existente antes de subirlo a Printful.

## Qué falta
- Pruebas de muestra en Printful (calidad de impresión en negro y rojo).
- Dirección de los mockups (camiseta negra, sudadera negra, gorra negra).
- Decidir el orden del primer drop.
