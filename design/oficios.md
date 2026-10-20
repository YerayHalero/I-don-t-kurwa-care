# Serie "Honorary Polak" por oficios (v0.1)

Idea: el compañero no polaco compra la camiseta de SU trabajo, con un pictograma simple y la palabra polaca del oficio.
Composición: pictograma arriba, `HONORARY POLAK` en el centro, palabra polaca del oficio debajo en pequeño.

## Oficios (orden de prioridad provisional)
| Código | Sector | Palabra polaca | Objeto del pictograma |
|---|---|---|---|
| O1 | Construcción | BUDOWA | casco de obra + paleta de albañil |
| O2 | Transporte y logística | TRASA | cabina de camión (vista frontal) |
| O3 | Cocina | KUCHNIA | gorro de chef + cuchillo de cocinero |
| O4 | Almacén | MAGAZYN | palé + carretilla |
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
