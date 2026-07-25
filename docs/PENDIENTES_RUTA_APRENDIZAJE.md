# Pendientes de la ruta de aprendizaje

Este documento registra brechas confirmadas entre la estructura prevista de Chilete DevPath y el contenido que ya fue recibido, revisado y validado.

## Sección 06: bases de datos

**Estado general:** reorganización iniciada; cobertura tecnológica incompleta.

| Prioridad | Tecnología | Pendiente | Condición de cierre |
|---|---|---|---|
| Alta | SQL Server | cerrar la revisión editorial del origen de los ejercicios | scripts 01 a 04 y limpieza verificados en SQL Server 16.0.1190.2 el 25/07/2026 |
| Alta | PostgreSQL | incorporar comandos, ejercicios resueltos, retos y laboratorio propios | sintaxis validada en PostgreSQL, versión documentada y datos ficticios |
| Alta | Oracle Database | incorporar comandos, ejercicios resueltos, retos y laboratorio propios | sintaxis validada en Oracle, versión documentada y datos ficticios |
| Alta | MongoDB | incorporar diseño documental, CRUD, agregaciones, índices y laboratorio | importación y consultas verificadas; decisión entre embebido y referencias explicada |
| Media | Apache Cassandra | incorporar CQL y modelado orientado a patrones de consulta | keyspace y tablas ejecutables; partición y clustering justificados |
| Media | Modelado | contrastar diagramas y modelos lógicos con sus enunciados permitidos | cardinalidades revisadas y diagramas exportados a un formato visual accesible |
| Media | Comparativa | crear una práctica que compare decisiones entre motores | selección de tecnología argumentada sin afirmar que SQL y NoSQL son equivalentes |

## Regla editorial

Mientras una fila no cumpla su condición de cierre, el contenido correspondiente debe presentarse como:

> Pendiente de recepción, validación técnica y evaluación editorial.

No se deben crear prácticas ficticias para aparentar cobertura. El material se incorporará cuando exista evidencia que Adrian Pisco pueda ejecutar, explicar y defender.

## Alcance de publicación

Antes de publicar cada bloque se debe confirmar:

- autoría y fuentes;
- ausencia de credenciales, respaldos o datos personales;
- motor, versión y contexto de ejecución;
- instrucciones destructivas aisladas y advertidas;
- ejercicios resueltos, retos y laboratorio coherentes;
- resultados reproducibles.
