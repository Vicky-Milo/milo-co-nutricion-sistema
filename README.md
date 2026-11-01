# Milo & Co. Nutrición — Módulo de Gestión de Inventario y Pedidos

**Trabajo Práctico Integrador y Progresivo (TPI) — Organización Empresarial**
Tecnicatura Universitaria en Programación a Distancia (TUPAD) — Universidad Tecnológica Nacional

---

## Descripción del sistema

Este repositorio documenta el desarrollo del módulo de software propuesto para **Milo & Co. Nutrición**, un emprendimiento de venta de alimentos naturales (legumbres, frutos secos, harinas y mixes) en la zona sur del Gran Buenos Aires.

Hoy el control de stock y el armado de pedidos se manejan a mano, en una planilla de cálculo. El objetivo del módulo es reemplazar ese proceso manual por un sistema que permita:

- Registrar y consultar el stock disponible de cada producto, por kilogramo.
- Cargar los pedidos de los clientes y hacer el seguimiento de su estado.
- Descontar stock automáticamente al confirmar un pedido.
- Generar información confiable de ventas para la toma de decisiones.

Este repositorio consolida las cuatro entregas del TPI: el análisis del sistema como organización abierta, el diagnóstico FODA y la planificación temporal, la estructura formal y el diccionario de datos, y finalmente el modelado del proceso de negocio (BPMN) junto con la gestión ágil del desarrollo.

## Integrantes

- Victoria Delgado

## Estructura del repositorio

```
/docs
  /entregas    → documentos PDF de las Entregas 1 a 4
  /diagramas   → BPMN, organigrama, FODA, Gantt, diccionario de datos
```

## Historias de usuario

| # | Historia de usuario | Estado |
|---|---------------------|--------|
| 1 | Como **administradora del emprendimiento**, quiero registrar el stock de cada producto por kilogramo, para saber en todo momento cuánto queda disponible sin depender de la planilla. | Por hacer |
| 2 | Como **clienta de Milo & Co. Nutrición**, quiero hacer mi pedido a través del sistema, para no tener que coordinar todo por WhatsApp y saber en qué estado está. | Por hacer |
| 3 | Como **encargado de logística**, quiero ver los pedidos confirmados y listos para entregar, para organizar el reparto diario por zona. | Por hacer |

El seguimiento de estas historias (Por hacer / En progreso / Listo) se gestiona en el tablero del proyecto, vinculado desde la primera página de la Entrega 4.

## Flujo de trabajo (Git)

- **`main`**: rama estable, solo recibe cambios a través de Pull Requests revisados.
- **Ramas secundarias por funcionalidad** (ej. `feature/modulo-pedidos`, `feature/control-stock`).
- **Mensajes de commit descriptivos** (ej. *"Agrega validación de stock mínimo al confirmar pedido"*), evitando mensajes genéricos como "cambios" o "ajustes".
- Cada funcionalidad se integra a `main` mediante un Pull Request con al menos una revisión antes del merge.

## Declaración de uso de IA

Para este trabajo utilicé un asistente de Inteligencia Artificial con el fin de obtener una revisión previa antes de realizar la entrega. Algunas observaciones que el asistente marcó como errores preferí no modificarlas, ya que consideré que no lo eran.
