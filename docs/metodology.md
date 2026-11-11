# Metodología
 
Este documento describe cómo se organiza el proyecto: el modelo de desarrollo, sus fases y cómo se gestionan las tareas.
 
## Modelo de desarrollo
 
El proyecto sigue una metodología **iterativa e incremental**, con la gestión de tareas en un tablero **Kanban**.
 
- **Iterativa:** el desarrollo se organiza en ciclos que terminan con una versión de la aplicación que funciona y se puede validar.
- **Incremental:** cada versión añade funcionalidad sobre la anterior.
- **Kanban:** las tareas avanzan por un flujo continuo de estados, sin sprints de duración fija.
Se elige este modelo porque el proyecto cuenta con una usuaria real, la propietaria del alojamiento, que puede probar cada versión y ayudar a afinar los requisitos. La justificación completa está en [decisions.md](decisions.md) (D-01).
 
## Fases
 
| Fase | Duración estimada | Resultado |
| --- | --- | --- |
| 1 — Definición y análisis | 3 semanas | Objetivos, funcionalidades, análisis y decisiones tecnológicas |
| 2 — Configuración técnica | 2 semanas | Proyecto base con pruebas, Docker e integración continua |
| 3 — Versión básica | 4 semanas | v0.1.0 |
| 4 — Versión intermedia | 4 semanas | v0.2.0 |
| 5 — Versión avanzada | 4 semanas | v1.0.0 |
| Margen | 1 semana | Absorber retrasos |
| 6 — Memoria | 3 semanas | Memoria completa |
| 7 — Defensa | 1 semana | Presentación |
 
Las fases 3, 4 y 5 son las iteraciones del proyecto: en cada una se revisan los requisitos, se diseña, se implementa, se prueba y se valida la versión con la propietaria y el tutor. La memoria se redacta en paralelo, con un borrador al cerrar cada fase.
 
## Diagrama de Gantt
 
> Pendiente — se añadirá cuando se fijen las fechas de entrega.
 
## Gestión de tareas
 
Las tareas se gestionan con **GitHub Projects**:
 
- Cada tarea es un **issue** con una breve descripción y los criterios que indican cuándo está terminada.
- Cada fase tiene un **milestone** que agrupa sus tareas y muestra su avance.
- Las **etiquetas** clasifican las tareas por tipo de trabajo (investigación, diseño, documentación, desarrollo…).
- El tablero muestra el estado de cada tarea, desde que se identifica hasta que se termina.
## Priorización
 
Las funcionalidades se priorizan con el método **MoSCoW** (*Must*, *Should*, *Could*, *Won't*). La priorización se hace en la Fase 1 y se revisa al inicio de cada iteración con la propietaria; los cambios quedan registrados en [features.md](features.md).
 
## Registros del proyecto
 
Durante todo el proyecto se mantienen dos registros:
 
- [decisions.md](decisions.md): las decisiones importantes, con sus alternativas y su justificación.
- [AI_USAGE.md](AI_USAGE.md): el uso de herramientas de inteligencia artificial.
---
 
[Volver al README](../README.md)
 
