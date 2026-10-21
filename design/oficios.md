# Serie "Honorary Polak" por oficios (v0.1)

Idea: el compañero no polaco compra la camiseta de SU trabajo, con un pictograma simple y la palabra polaca del oficio.
## Composición (decidida)
- **Delante (todas las camisetas):** `I DON'T KURWA CARE`, la marca, centrada en el pecho.
- **Detrás:** pictograma del oficio, `HONORARY POLAK` pequeño, el oficio en polaco grande y su traducción al inglés debajo.
- El término "Honorary Polak" se usa solo en esta sección de producto.
- Boceto visual publicado como artefacto (camiseta negra, delante y detrás).

## Oficios (orden de prioridad provisional)
| Código | Sector | Palabra polaca | Objeto del pictograma |
|---|---|---|---|
| O1 | Construcción | BUDOWA (Construction site) | casco de obra con dos huesos cruzados detrás (estilo bandera pirata) |
| O2 | Transporte y logística | TRASA (The long haul) | cabina de camión (vista frontal) |
| O3 | Cocina | KUCHNIA (The kitchen) | gorro de chef + cuchillo de cocinero |
| O4 | Almacén | MAGAZYN (The warehouse) | carretilla elevadora con palé de cajas (silueta rellena) |
| O5 | Hotel y recepción | RECEPCJA | campanilla de mostrador |
| O6 | Limpieza | SPRZĄTANIE | cubo y fregona |
| O7 | Soldadura e industria | SPAWACZ | careta de soldador |
| O8 | Cuidados y sanidad | OPIEKA | cruz con corazón (genérica, sin logos) |
| O9 | Campo e invernaderos | ŻNIWA | espiga de trigo |
| O10 | Turno de noche | NOCNA ZMIANA | luna + reloj |

Revisar con un hablante nativo las palabras y los signos (Ą, Ż) antes de imprimir.

## Prompt maestro (cambiar solo [OBJETO])
```
Simple flat pictogram icon of [OBJETO], bold thick outline, minimal, symmetrical, like a workwear safety-sign icon, single solid red color (#D4213D) on a pure white background, no text, no letters, no shading, no gradients, no shadows, high contrast, centered, vector style
```
Pedir siempre fondo blanco puro: facilita quitarlo después para el PNG transparente.

## Flujo
1. Generar 4 variantes en Grok, Gemini o Copilot con el prompt maestro.
2. Elegir la más limpia y pasarla a vector (Inkscape: Trazado > Vectorizar mapa de bits) para bordes nítidos a cualquier tamaño.
3. Quitar el fondo y exportar PNG transparente.
4. Montar el texto con la fuente de marca (Big Shoulders Display, 900).
5. Exportar con los requisitos de Printful (ver `prompts.md`).

## Cuidado (Nuria)
- Pictogramas genéricos: nada de logos, uniformes ni marcas reales (hoteles, cadenas, empresas de transporte).
- Tono de orgullo y compañerismo, sin caricatura del "fontanero polaco" ni de los estereotipos.
- Sin símbolos de cuerpos oficiales (policía, ejército, sanidad pública).

## Tanda 1: prompts listos (O1 a O4)
Pegar tal cual en Grok, Gemini o Copilot. Pedir 4 variantes.

**O1 · Budowa** (v2: martillo y paleta cruzados se descartan por parecerse a la iconografía del martillo y la hoz, delicada para el público polaco)
```
Bold solid filled silhouette icon of a construction hard hat in front view, with two crossed bones behind it like a pirate flag Jolly Roger, classic cartoon bones with rounded knobby ends crossing in an X behind the helmet, thick chunky shapes, a few clean white cut-out details for the helmet ridges and brim, symmetrical, like a workwear safety-sign pictogram, single solid red color (#D4213D) on a pure white background, no skull, no text, no letters, no logos, no shading, no gradients, no shadows, high contrast, centered, vector style
```
**O2 · Trasa**
```
Simple flat pictogram icon of a long-haul truck cab seen from the front, bold thick outline, minimal, symmetrical, like a workwear safety-sign icon, single solid red color (#D4213D) on a pure white background, no text, no letters, no logos, no shading, no gradients, no shadows, high contrast, centered, vector style
```
**O3 · Kuchnia**
```
Simple flat pictogram icon of a chef's toque hat with a chef's knife crossed behind it, bold thick outline, minimal, symmetrical, like a workwear safety-sign icon, single solid red color (#D4213D) on a pure white background, no text, no letters, no shading, no gradients, no shadows, high contrast, centered, vector style
```
**O4 · Magazyn** (v2: la versión palé + caja se descarta porque no se distingue en versión minimalista)

Regla aprendida: los pictogramas de solo contorno pierden reconocimiento al simplificarse. Usar siluetas rellenas con detalles recortados en blanco y un objeto con silueta inconfundible.

Opción A (recomendada, carretilla elevadora):
```
Bold solid filled silhouette icon of a forklift truck in side view carrying a pallet loaded with stacked boxes, thick chunky shapes, a few clean white cut-out details for the driver cage, mast and wheels, like a road-sign or warehouse safety-sign pictogram, single solid red color (#D4213D) on a pure white background, no text, no letters, no logos, no shading, no gradients, no shadows, high contrast, centered, vector style
```
Opción B (estantería de almacén):
```
Bold solid filled silhouette icon of a tall warehouse storage rack seen from the front, three shelves each holding chunky boxes, thick shapes with clean white gaps between boxes, like a safety-sign pictogram, single solid red color (#D4213D) on a pure white background, no text, no letters, no logos, no shading, no gradients, no shadows, high contrast, centered, vector style
```
Opción C (transpaleta manual):
```
Bold solid filled silhouette icon of a manual pallet jack in side view loaded with a stack of three boxes, thick chunky shapes with clean white cut-out details, like a safety-sign pictogram, single solid red color (#D4213D) on a pure white background, no text, no letters, no logos, no shading, no gradients, no shadows, high contrast, centered, vector style
```
