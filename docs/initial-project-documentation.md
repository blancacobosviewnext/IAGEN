# Plataforma de Gestión de Solicitudes Internas

## Índice
1. Evaluación de Calidad de Requisitos
2. Análisis Inicial del Proyecto
3. Flujos de Negocio
4. Opciones de Arquitectura
5. Riesgos Iniciales
6. Backlog Inicial
7. Trazabilidad y Fecha de Generación

---

## 1. Evaluación de Calidad de Requisitos
## Evaluación Global de Calidad

**Fortalezas**
- Objetivo y problema bien definidos.
- Alcance inicial acotado y claro.
- Cobertura funcional del ciclo básico de solicitud.
- Identificación de NFR clave.

**Debilidades / Huecos**
- Matriz de roles y permisos no definida.
- Estados y transiciones abiertos.
- Canal de notificaciones sin confirmar.
- Política de adjuntos no definida.
- Falta de criterios verificables para rendimiento y auditoría.

**Ambigüedades**
- "Trazabilidad completa" vs "auditoría de acciones relevantes".
- "Cerrar" solicitud: significado exacto.
- Alcance de "reglas" en panel de administración.

**Preguntas de Refinamiento**
1. Roles mínimos del MVP.
2. Visibilidad por equipo/área.
3. Estados exactos y transiciones.
4. Tipos de solicitud con aprobación.
5. Canal de notificaciones.
6. Política de adjuntos.
7. Operaciones comunes para rendimiento.
8. Eventos exactos a auditar.

**Recomendaciones**
- Definir MVP con estados y roles cerrados.
- Convertir requisitos en criterios medibles.
- Crear diccionario de términos.
- Delimitar alcance de "reglas".
- Cerrar política de adjuntos.
- Alinear notificaciones con canal corporativo.
- Preparar trazabilidad para Jira/GitHub.

---

## 2. Análisis Inicial del Proyecto
## Resumen Ejecutivo
La plataforma busca centralizar la gestión de solicitudes internas, mejorando trazabilidad, tiempos de respuesta y visibilidad del estado. El alcance inicial incluye solicitudes de material IT, accesos, soporte administrativo y otras peticiones operativas básicas.

**Objetivos clave**
- Registro y seguimiento de solicitudes.
- Control por roles.
- Panel de administración.
- Notificaciones.

**Situación actual**
- Procesos dispersos en correo, Teams y hojas de cálculo.
- Falta de trazabilidad y tiempos irregulares.

**Beneficios esperados**
- Mayor eficiencia.
- Mejor visibilidad.
- Reducción de tiempos.

---

## 3. Flujos de Negocio
**Flujo básico de solicitud**
1. Creación por empleado.
2. Asignación a equipo responsable.
3. Decisión (aprobar/rechazar/reasignar).
4. Cierre.

**Flujos complementarios**
- Comentarios internos y externos.
- Búsqueda y filtrado.
- Gestión de tipos, estados y prioridades.

---

## 4. Opciones de Arquitectura
**Alternativas consideradas**
- Arquitectura monolítica web responsive.
- Integración con autenticación corporativa.
- Despliegue en infraestructura interna.

**Criterios de selección**
- Bajo coste operativo.
- Mantenibilidad.
- Extensibilidad.

---

## 5. Riesgos Iniciales
- Definición incompleta de roles y estados.
- Canal de notificaciones no confirmado.
- Política de adjuntos pendiente.
- Posible ambigüedad en requisitos.
- Volumen de solicitudes diario no definido.

---

## 6. Backlog Inicial
**Epics**
- Gestión de solicitudes.
- Panel de administración.
- Notificaciones.

**Historias de usuario**
- Crear solicitud.
- Consultar solicitudes.
- Ver detalle e histórico.
- Aprobar/rechazar.
- Añadir comentarios.
- Filtrar y buscar.

---

## 7. Trazabilidad y Fecha de Generación
**Documentos incluidos**
- DOC00_REQUIREMENTS_QUALITY
- DOC1_INITIAL_ANALYSIS
- DOC3_BUSINESS_FLOWS
- DOC5_ARCH_OPTIONS
- DOC7_RISKS
- DOC9_BACKLOG

**Fecha de generación**: 2026-05-13
**Generado por**: LLM
**Formato**: Markdown