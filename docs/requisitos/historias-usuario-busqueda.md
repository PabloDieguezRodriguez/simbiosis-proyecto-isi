# Historias de usuario de búsqueda

| Campo    | Valor              |
| -------- | ------------------ |
| Proyecto | Proyecto Simbiosis |
| Fecha    | 29/10/2026         |
| Versión  | 1.0.0              |
| Estado   | Vigente            |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario registrado, quiero seleccionar ingredientes que se van a incluír y que se van a excluír a partir de los nombres de ingredientes disponibles en el sistema, para encontrar recetas que se ajusten a la informacion provisionada.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

Las 3 historias de usuario en las que se descompuso la épica son independientes.

## US-01

**Título:** Seleccionar para incluír

Como usuario registrado, quiero seleccionar ingredientes que se van a incluír, para encontrar recetas que se ajusten a la informacion provisionada.

**Fuentes:** UR-08; UC-21; FR-086; acta, sección 2.1.

### Criterios de aceptación

- **CA-01.** Dado un usuario registrado, cuando seleccione ingredientes para incluír, entonces el sistema marcará los ingredientes como seleccionados para incluír.
- **CA-02.** Dado un usuario registrado, cuando seleccione ingredientes para incluír que ya enstan seleccionados para incluír, entonces dejarán de estar seleccionados para incluír.

## US-02

**Título:** Seleccionar para excluír

Como usuario registrado, quiero seleccionar ingredientes que se van a excluír, para encontrar recetas que se ajusten a la informacion provisionada.

**Fuentes:** UR-08; UC-21; FR-087; acta, sección 2.2.

### Criterios de aceptación

- **CA-01.** Dado un usuario registrado, cuando seleccione ingredientes para excluír, entonces el sistema marcará los ingredientes como seleccionados para excluír.
- **CA-02.** Dado un usuario registrado, cuando seleccione ingredientes para excluír que ya enstan seleccionados para excluír, entonces dejarán de estar seleccionados para excluír.

## US-03

**Título:** Seleccionar a partir de nombre

Como usuario registrado, quiero seleccionar ingredientes a partir de los nombres de ingredientes disponibles en el sistema, para encontrar recetas que se ajusten a la informacion provisionada.

**Fuentes:** UR-08; UC-21; acta, sección 2.3.

### Criterios de aceptación

- **CA-01.** Dado un usuario registrado, cuando quiera seleccionar ingredientes, entonces el sistema mostrará los ingredientes acompañados de sus nombres y permitirá buscarlos.
- **CA-02.** Dado un usuario registrado, cuando seleccione ingredientes que ya enstan seleccionados, entonces dejarán de estar seleccionados.

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio      | Pregunta de revisión                                                                                                                                              | Aplicado | Cumple | Justificación |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ------ | ------------- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | Sí       | Sí     | N/A           |
| Negociable    | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados?                      | Sí       | Sí     | N/A           |
| Valiosa       | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad?                                                             | Sí       | Sí     | N/A           |
| Estimable     | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia?                                                                         | Sí       | Sí     | N/A           |
| Pequeña       | ¿Se centra cada historia en una única capacidad de alcance manejable?                                                                                             | Sí       | Sí     | N/A           |
| Comprobable   | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto?   | Sí       | Sí     | N/A           |

## Dudas pendientes

Ninguna.
