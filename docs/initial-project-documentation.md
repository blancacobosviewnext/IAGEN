# Plataforma de Gestión de Solicitudes Internas

## Índice
1. Evaluación de Calidad de Requisitos
2. Análisis Inicial
3. Flujos de Negocio
4. Opciones de Arquitectura
5. Riesgos Iniciales
6. Backlog Inicial
7. Trazabilidad y Fecha de Generación

---

## 1. Evaluación de Calidad de Requisitos
## Evaluación global de calidad
- **Cobertura funcional:** Media-alta. Se describen bien las capacidades núcleo (crear, consultar, asignar, aprobar/rechazar/cerrar, comentarios, filtros, administración, notificaciones, trazabilidad).
- **Claridad:** Media. Algunos términos abiertos permiten interpretaciones distintas (“reglas”, “roles”, “actualizada”, “trazabilidad completa”).
- **Completitud:** Media-baja. Faltan definiciones clave para diseñar flujo, permisos y notificaciones sin suposiciones.
- **Testabilidad:** Media-baja. Algunos requisitos no son verificables tal como están.
- **Riesgo de alcance:** Medio-alto. El alcance difuso de “otras peticiones operativas básicas” y posibles dobles aprobaciones puede crecer rápido.

### Ambigüedades
- Modelo de roles/permisos y visibilidad.
- Definición de estados y transiciones.
- Significado de “actualizada” en notificaciones.
- Gestión de adjuntos (tipos, tamaño, seguridad).
- Criterios de asignación.

### Huecos detectados
- Estados y transiciones.
- Matriz de roles y permisos.
- Canal de notificaciones.
- Política de adjuntos.
- SLA y métricas de rendimiento.

### Preguntas de refinamiento
1. Roles iniciales y acciones permitidas.
2. Alcance de visibilidad por rol.
3. Estados mínimos y transiciones.
4. Diferencia entre cerrar y rechazar.
5. Tipos de solicitud que requieren aprobación.
6. Canal definitivo de notificaciones.
7. Tipos y límites de adjuntos.
8. Operaciones comunes para medir rendimiento.

### Recomendaciones
1. Cerrar puntos abiertos antes de diseño.
2. Definir glosario de términos.
3. Hacer requisitos verificables.
4. Documentar permisos y reglas.

---

## 2. Análisis Inicial
**Falta contenido** — Documento pendiente de elaboración.

---

## 3. Flujos de Negocio
**Falta contenido** — Documento pendiente de elaboración.

---

## 4. Opciones de Arquitectura
**Falta contenido** — Documento pendiente de elaboración.

---

## 5. Riesgos Iniciales
**Falta contenido** — Documento pendiente de elaboración.

---

## 6. Backlog Inicial
**Falta contenido** — Documento pendiente de elaboración.

---

## 7. Trazabilidad y Fecha de Generación
- Documentos incluidos: DOC00_REQUIREMENTS_QUALITY, DOC1_INITIAL_ANALYSIS, DOC3_BUSINESS_FLOWS, DOC5_ARCH_OPTIONS, DOC7_RISKS, DOC9_BACKLOG.
- Fecha de generación: 2026-05-13
- Generado por: LLM
- Estado: Publicación inicial en GitHub para explotación posterior en Jira.