# Auditoría SEO On Page + GEO — Bendix de arranque

- **URL objetivo:** https://www.motosmanu.com/bendix-de-arranque-29329/
- **URL que canibaliza:** https://www.motosmanu.com/blog/182_motor-de-arranque-Bendix.html
- **Keyword principal:** bendix motor de arranque (cluster con "motor de arranque bendix" y "bendix de arranque")
- **Fecha:** 19/10/2026
- **Fuentes:** DinoRANK (keyword research ES, canibalizaciones, Search Console jul–sep 2026), rank tracker facilitado por el cliente, rastreo de ambas URL.

---

## 1. Situación actual

### Search Console (01/07–01/10/2026)
| URL | Impresiones | Clics | Posición media | Keywords |
|---|---|---|---|---|
| Categoría bendix | 368 | 2 | 7,7 | 67 |
| Blog 182 | 1.164 | 4 | 11,8 | 104 |

### Rank tracker (19/10/2026)
| Keyword | Vol. | Posición | URL que posiciona |
|---|---|---|---|
| bendix motor de arranque | 590 | 7 (mejor 3) | Categoría ✅ |
| motor de arranque bendix | 590 | 10 (mejor 3), bajando 4 puestos | **Blog 182** ❌ |
| bendix de arranque | 90 | 6 (mejor 4) | **Blog 182** ❌ |

### Canibalizaciones detectadas (DinoRANK)
| Keyword | Categoría | Blog 182 |
|---|---|---|
| bendix de arranque (escritorio) | Pos. 7 | Pos. 8,7 |
| bendix moto (móvil) | Pos. 10,5 | **Pos. 3,7** |

**Diagnóstico:** Google alterna entre las dos URL. El blog gana en 3 de las 4 variantes porque tiene más contenido y autoridad, aunque la intención de compra corresponde a la categoría.

### SERP de "bendix motor de arranque"
Amazon, motoscamacho.es (categoría), Wikipedia, hrmotor.com, sportkart.es (producto), motociclismo.es y helloauto.com. La intención es **mixta** (6 informacionales y 4 transaccionales). Hay sitio para las dos URL si cada una responde a una intención distinta.

### Catálogo
- **3 productos:** Tecnium MT741-OT046, Top Performance RL00040 y Tecnium MT741-OT049.
- **Precios:** de 13,65 a 20,12 €.
- **Los 3 aparecen como agotados.** Es el principal freno para posicionar y vender: una categoría sin stock aporta poco valor, tanto a Google como al usuario.

---

## 2. Estudio de palabras clave (volumen mensual en España, DinoRANK)

### 2.1 Categoría: intención de compra
| Keyword | Vol. | Comp. | Uso |
|---|---|---|---|
| bendix motor de arranque | 590 | 0,00 | Title, H1 |
| motor de arranque bendix | 590 | 0,76 | Intro, meta description |
| bendix de arranque | 90* | — | H2, cuerpo |
| bendix moto | 70 | 0,62 | Title, intro |
| bendix motor de arranque precio | 70 | 0,73 | Meta description ("precio") |
| bendix motor arranque | 30 | 0,72 | Variante |
| piñón bendix | 30 | 0,19 | Sinónimo en el cuerpo |
| bendix de arranque moto | 20 | 1,00 | H1 / cuerpo |
| bendix motor de arranque moto | 10 | 0,75 | Cuerpo |

\* Volumen del rank tracker del cliente.

### 2.2 Blog 182: intención informativa
| Keyword | Vol. |
|---|---|
| qué es el bendix de una moto | 40 |
| qué es el bendix del motor de arranque | 30 |
| bendix qué es | 30 |
| fallo bendix motor arranque | 30 |
| el bendix del motor de arranque se queda pegado | 20 |
| cambiar bendix de motor de arranque | 20 |
| cómo funciona el bendix | 10 |
| partes del motor de arranque bendix | 10 |
| reparar bendix motor de arranque | 10 |

### 2.3 Entidades relacionadas (para enlazar, no para atacar aquí)
| Keyword | Vol. | Destino |
|---|---|---|
| relé motor de arranque | 390 | /reles-de-arranque-29374/ |
| motor de arranque esquema | 320 | Blog 170 (motores de arranque) |
| solenoide motor de arranque | 260 | Relés / motor de arranque |

> ⚠️ **"bendix" (6.600) y "bendix palma" (1.600)** son búsquedas de navegación hacia otro negocio (Bendix, en Palma de Mallorca). No conviene atacarlas.

---

## 3. Auditoría On Page de la categoría

| # | Elemento | Estado actual | Problema | Recomendación | Prioridad |
|---|---|---|---|---|---|
| 1 | Stock | 3 productos, todos agotados | Sin oferta real | Reponer y ampliar referencias (scooter 50–125 cc, Minarelli, Piaggio, GY6) | **Crítica** |
| 2 | Title | Bendix de Arranque Moto \| Motor de Arranque Bendix | Aceptable, pero no empieza por la keyword principal | `Bendix Motor de Arranque para Moto y Scooter \| Motos Manu` | Alta |
| 3 | H1 | BENDIX ARRANQUE | Sin "de", sin "motor" y en mayúsculas | `Bendix motor de arranque para moto y scooter` | Alta |
| 4 | Meta description | No visible | — | Ver contenido 5.1 | Alta |
| 5 | Encabezados | 4 H2 incoherentes ("revolucionando el mercado"); "¿Cúales…" con tilde errónea | Tono comercial vacío y falta de ortografía | Estructura nueva (5.3) | Alta |
| 6 | Enfoque del texto | Explica "partes del motor de arranque" (interruptor, batería…) | Es contenido informativo: compite con el blog y no ayuda a comprar | Centrar en elegir, compatibilidad, síntomas → compra | Alta |
| 7 | Errores | "Vicent Hugo Bendix" (es Vincent Hugo Bendix), "fuera" por "fuerza", "Benix", "coaxil"; dice que el bendix "también se denomina corona dentada", lo cual es falso | Restan E-E-A-T y confunden a la IA | Eliminar o corregir | Alta |
| 8 | Enlaces | A marcadores/sensores y mandos/cables con `target="_blank"` | Sin relación temática | Enlazar a motor de arranque, relés, baterías y blog 182 | Media |
| 9 | Imagen | `height="NaN"`, ruta con espacio y tilde, alt genérico | HTML inválido | Quitar height="NaN", alt descriptivo, lazy | Media |
| 10 | JSON-LD | FAQPage con `// <![CDATA[` y saltos "nn" | JSON inválido | Sustituir (5.4) | Alta |
| 11 | Plantilla | H3 en los productos y H3 "¿Te llamamos?" | Diluye encabezados | Cambiar a `<p>`/`<span>` en el tema | Media |
| 12 | Nombres de producto | "BENDIX ARRANQUE TECNIUM MT741-OT046" | Sin modelos ni nº de dientes | `Bendix motor de arranque Tecnium MT741-OT046 – [modelos]` | Media |

---

## 4. Auditoría GEO

| Señal | Estado | Acción |
|---|---|---|
| Definición breve y citable | No | Párrafo de 40–60 palabras: qué es y dónde va |
| Datos concretos | No | Explicar el engrane con el volante o con la semipolea fija del variador en scooters; diferencia con la rueda libre |
| Tabla de diagnóstico | No | Síntoma → causa → pieza (bendix, relé, batería) |
| Pasos numerados | No | Cómo elegir el bendix correcto |
| Errores factuales | Sí | Corregir (ver fila 7) |
| Autoría y fecha | No | "Equipo técnico de Motos Manu" + fecha |

---

## 5. Estrategia anti-canibalización

| URL | Intención | Keywords |
|---|---|---|
| Categoría | Comprar | bendix motor de arranque, motor de arranque bendix, bendix de arranque, bendix moto, precio |
| Blog 182 | Entender / diagnosticar | qué es el bendix, fallo, se queda pegado, cómo funciona, cambiar |

### Cambios en el blog 182
- **H1 y title:** pasar de "Conoce el motor de arranque Bendix" a `¿Qué es el bendix de una moto y cómo saber si falla?`
- **Keywords exactas:** "bendix de arranque", "motor de arranque bendix" y "bendix motor de arranque" solo en los enlaces a la categoría (1 al inicio y 1 en el CTA). En el resto del texto, usar "el bendix", "el piñón de arranque" o "el sistema Bendix".
- **Estructura:** convertir los subtítulos en negrita en H2 reales con enfoque de diagnóstico.
- **Tags:** quitar cualquier etiqueta "bendix de arranque" (las páginas de tag pueden competir).
- **Datos estructurados:** BlogPosting con dateModified.

### Cambios en la categoría
- Contenido de compra (5.3), con enlace al blog usando un ancla informativa: "qué es el bendix y cómo saber si falla".
- Quitar el bloque "partes del motor de arranque", que pasa al blog.

### Enlazado interno hacia la categoría
| Origen | Ancla |
|---|---|
| Blog 182 (intro + CTA) | bendix motor de arranque / bendix de arranque |
| Blog 170 (motores de arranque, 1.557 impr.) | bendix de arranque |
| /motor-arranque-moto-18687/ | bendix motor de arranque |
| /reles-de-arranque-29374/ | bendix de arranque |
| Fichas de motores de arranque | piñón bendix |

**Control:** revisar el rank tracker a 4 y 8 semanas. Las 3 keywords deberían devolver la categoría. Si el blog sigue apareciendo, reforzar la desoptimización y, como último recurso, aplicar un 301 de la sección del blog.
