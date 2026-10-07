# Estrategia anti-canibalización: "barras de horquilla"

- **URL objetivo (debe posicionar):** https://www.motosmanu.com/barras-de-horquilla-29238/
- **URL que se mantiene (no debe competir):** https://www.motosmanu.com/blog/126_todo-lo-que-tienes-que-saber-sobre-las-barras.html
- **Condición:** mantener el artículo publicado (sin 301).

## 1. Diagnóstico (DinoRANK, GSC hasta 29/09/2026)

| Keyword | Categoría | Blog 126 |
|---|---|---|
| barra de horquilla (escritorio) | Pos. 4 | Pos. 8,67 |
| barras de horquilla | Sin canibalización detectada | — |

Artículo actual: febrero 2023, unas 500 palabras, sin H2. El H1 incluye la keyword exacta ("Todo lo que tienes que saber sobre las barras de horquilla"). Repite la intención de la categoría (qué es, tipos, mantenimiento). Ya enlaza a la categoría con el ancla "barras de horquilla".

## 2. Principio

Una keyword, una URL y una intención:

| URL | Intención | Keywords |
|---|---|---|
| Categoría | Transaccional: comprar | barras de horquilla, barra de horquilla, tubo de horquilla, barras de horquilla moto |
| Blog 126 | Informacional: diagnosticar y reparar | reparar barras horquilla moto (20), pulir barras horquilla moto (20), cromar barras horquilla (20), anodizar barras horquilla (20), quitar óxido horquilla moto (30), enderezar horquilla moto (30), horquilla doblada moto (20), barra horquilla rayada (10), recubrimiento barras horquilla (10), lubricante para barras de horquilla (10) |

Las keywords del blog suman unas 190 búsquedas al mes que hoy no captura ninguna URL, así que el artículo gana tráfico propio sin competir.

## 3. Acciones en el artículo

### 3.1 Desoptimizar la keyword exacta
- **Title:** `Barras de la horquilla rayadas u oxidadas: ¿reparar, pulir o cambiar? | Motos Manu`
- **H1:** `¿Reparar, pulir o cambiar las barras de la horquilla de tu moto?`
- **Meta description:** `Aprende a revisar las barras de la horquilla de tu moto: cuándo se pueden pulir, recromar o enderezar y cuándo es más seguro cambiarlas.`
- La forma exacta "barras de horquilla" o "barra de horquilla" solo puede aparecer en el texto de los enlaces a la categoría. En el resto, usa "barras de la horquilla", "barras", "tubos" o "barras cromadas".
- **URL:** se mantiene para no perder su antigüedad ni sus enlaces.

### 3.2 Reescribir con la nueva intención (unas 900 palabras)
1. **Intro de unas 60 palabras.** Incluye, dentro de las primeras 100 palabras, el enlace a la categoría con el ancla `barras de horquilla`.
2. **Cómo revisar las barras en 5 minutos:** prueba de la uña, reloj comparador, fugas en el retén.
3. **Rayas y picaduras:** cuándo sirve pulir y cuándo no.
4. **Óxido:** cómo quitarlo y cuándo deja daños permanentes.
5. **Recromado y recubrimientos:** cromo duro, nitruro de titanio, DLC. Por qué no se anodizan.
6. **Barra doblada:** cuándo se puede enderezar y por qué normalmente se cambia.
7. **Tabla de decisión** daño → pulir / recromar / enderezar / sustituir.
8. **Mantenimiento** para alargar su vida: limpieza, grasa en el retén, protectores.
9. **CTA final:** "¿Toca cambiarlas? Encuentra la medida exacta en nuestra sección de [barras de horquilla para moto](categoría)".

Elimina las secciones "qué es una horquilla" y "tipos de horquilla". Si hacen falta, déjalas en una línea con enlace a la categoría.

### 3.3 Datos estructurados
- `BlogPosting` con `dateModified` actualizado, `author` (equipo técnico de Motos Manu) y `about` (barra de horquilla).
- Sin FAQPage con las mismas preguntas que la categoría.

### 3.4 No usar
- **Canonical a la categoría:** los contenidos son distintos y Google lo ignoraría.
- **Noindex:** perdería las keywords de reparación.

## 4. Acciones en la categoría (ya aplicadas en `contenido-maquetado.html`)
- Se elimina la FAQ "¿Se pueden pulir o anodizar…?" (texto visible y JSON-LD). Pasa al artículo.
- La FAQ "¿Se pueden reparar…?" queda como respuesta corta, con enlace al artículo:
  - Ancla: `cuándo reparar, pulir o cambiar las barras` (informacional, no la keyword exacta).
  - title: `Guía para saber si reparar, pulir o cambiar las barras de la horquilla`.

## 5. Enlazado interno (todo apunta a la categoría)

| Origen | Destino | Ancla |
|---|---|---|
| Blog 126 (intro) | Categoría | barras de horquilla |
| Blog 126 (CTA final) | Categoría | barras de horquilla para moto |
| Blog 133 (retenes) | Categoría | barras de horquilla |
| Blog 133 (retenes) | Blog 126 | cómo saber si las barras están dañadas |
| /chasis-moto-29320/ | Categoría | Barras de horquilla (menú o descripción) |
| /retenes-horquilla-moto-29228/ | Categoría | barras de horquilla |
| Categoría | Blog 126 | cuándo reparar, pulir o cambiar las barras |

Reglas:
- Ningún enlace interno con el ancla "barras de horquilla" o "barra de horquilla" debe apuntar al blog.
- Busca en el sitio, con `site:motosmanu.com "barras de horquilla"` y con el rastreo de DinoRANK, otros enlaces al blog 126 y cambia su ancla por una informacional.

## 6. Calendario y control

| Semana | Acción |
|---|---|
| 0 | Publicar la categoría nueva y reescribir el artículo. Solicitar indexación de ambas URL en GSC |
| 0 | Actualizar enlaces internos (tabla 5) |
| 4 | DinoRANK → Canibalizaciones: comprobar "barra de horquilla" |
| 8 | GSC → Rendimiento → filtro de consulta "horquilla", comparando páginas |

**Criterio de éxito:** a las 8 semanas, "barra(s) de horquilla" solo tiene impresiones en la categoría, y el blog aparece por consultas de reparar, pulir, óxido o rayada.

**Plan B:** si a las 12 semanas el blog sigue recibiendo impresiones por "barra(s) de horquilla" en el top 20, revisar los anclas externas que apuntan al artículo. Si persiste, plantear de nuevo el 301.
