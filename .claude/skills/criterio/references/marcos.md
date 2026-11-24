# Los cuatro marcos — detalle operativo

Material de consulta para criticar con precisión. No se recita: se usa para
nombrar el hallazgo con el término correcto.

---

## 1. Teoría del color

### Roles (toda paleta funcional los tiene)
- **Dominante** — 60-70% de la superficie. Suele ser el fondo.
- **Secundario** — 20-30%. Estructura y soporte.
- **Acento** — 5-10%. Solo para lo que debe mirarse primero.

Fallo típico: usar el acento en más de un sitio. Si todo resalta, nada resalta.

### Armonías
- **Complementaria** (opuestos) — máxima vibración. Azul/naranja, el caso BeFIT.
- **Análoga** (adyacentes) — calma, poco contraste. Rojo junto a naranja NO
  contrasta: se ensucia.
- **Triádica** — equilibrada pero difícil; exige que una domine claramente.
- **Monocromática** — elegante, depende enteramente del valor tonal.

### Contraste WCAG — cifras, no impresiones
- Texto normal: **4.5:1** mínimo (AA)
- Texto grande (≥24px o ≥19px bold): **3:1** mínimo
- Elementos de interfaz y gráficos: **3:1**

Trampa frecuente: **blanco sobre naranja ronda 2.9:1 y falla**. Texto oscuro
sobre naranja llega a ~8:1. El naranja es un color de fondo para texto oscuro,
no para texto blanco.

### Temperatura y símbolo
Cálidos avanzan, fríos retroceden — útil para construir profundidad sin
desenfoque. La carga simbólica es cultural y contextual: verifícala en el
mercado real de la pieza, no por manual.

---

## 2. Principios del diseño

| Principio | Pregunta de diagnóstico |
|---|---|
| Jerarquía | ¿Qué se lee primero, segundo, tercero? ¿Es el orden que quiero? |
| Contraste | ¿Los elementos distintos son *claramente* distintos, o solo un poco? |
| Equilibrio | ¿El peso visual se reparte, o la pieza se cae hacia un lado? |
| Repetición | ¿Qué se repite y crea sistema? ¿Hay excepciones sin motivo? |
| Proximidad | ¿Lo que está junto pertenece junto? |
| Alineación | ¿Cada elemento se alinea con algo, o flota? |
| Espacio negativo | ¿Respira? ¿El vacío es decisión o sobra? |
| Ritmo | ¿La repetición tiene cadencia, o es monótona? |
| Escala | ¿Los saltos de tamaño son evidentes o tímidos? |

**Un solo nivel 1.** Si hay dos, hay cero: el ojo rebota en vez de recorrer.
Lo demás baja de peso con escala, desaturación, desenfoque u opacidad.

**Saltos de escala tímidos.** Si dos textos difieren un 15%, se lee como error,
no como jerarquía. Trabaja en ratios: 1.5x, 2x, 3x.

**El espacio negativo es lo que más separa amateur de profesional.** El reflejo
del principiante es llenar; el del profesional, quitar.

---

## 3. Teoría de la Gestalt

- **Figura-fondo** — ¿se separa limpiamente el protagonista del fondo? Si el
  fondo tiene el mismo valor tonal que la figura, no hay pieza.
- **Proximidad** — elementos cercanos se leen como grupo, aunque no lo sean.
  Causa de errores invisibles: un adorno demasiado cerca del texto se agrupa
  con el texto.
- **Similitud** — lo que comparte forma, color o tamaño se lee como familia.
  Úsalo para marcar categorías sin etiquetarlas.
- **Cierre** — el cerebro completa formas incompletas. Es el recurso más
  potente y el más barato: un árbol hecho de discos de pesas.
- **Continuidad** — el ojo sigue líneas y curvas. Una diagonal dominante es un
  carril de lectura; úsala o rómpela a propósito.
- **Destino común** — lo que se mueve o apunta en la misma dirección se agrupa.
- **Región común** — un recuadro o fondo compartido agrupa con más fuerza que
  la proximidad. Cuidado: un recuadro del mismo tono que el fondo no agrupa
  nada, solo añade ruido.

---

## 4. Psicología de la forma

- **Ángulos agudos y diagonales** — tensión, energía, velocidad, agresión.
  Deporte, acción, urgencia.
- **Curvas y círculos** — cercanía, seguridad, suavidad, comunidad.
  Salud, infancia, cuidado.
- **Rectángulos y horizontales** — estabilidad, orden, confianza, institución.
- **Triángulo apoyado en la base** — estable. **Invertido** — inestable, alerta.
- **Peso visual** — lo oscuro, denso, saturado y grande pesa más. El equilibrio
  no es simetría: un elemento pequeño muy saturado equilibra uno grande y apagado.
- **Dirección** — toda forma apunta. Las que apuntan fuera del encuadre expulsan
  la mirada; es el error silencioso más común.

**Romper el sistema marca intención.** En una pieza íntegramente diagonal, el
único elemento recto es el que más llama. Por eso un botón sin inclinación en
una composición inclinada se lee como zona clicable.

---

## Preflight — antes de dar por cerrada una pieza

- [ ] Ratio WCAG calculado para cada par texto/fondo, no estimado
- [ ] Un único nivel 1, verificado entrecerrando los ojos
- [ ] El acento cromático aparece en un solo sitio
- [ ] Cada elemento se alinea con algo
- [ ] Safe area que sobreviva a los recortes del canal (1:1, 9:16, 16:9)
- [ ] El nivel 1 se lee en 0.8 s a tamaño miniatura
- [ ] Hay CTA o cierre, según sea pieza promocional o de marca
- [ ] Nada apunta hacia fuera del encuadre
