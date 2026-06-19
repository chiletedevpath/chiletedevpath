# Auditoria de Publicacion: aprendizaje/09-backend

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-009 |
| Version | 1.0 |
| Estado | Saneado en archivos actuales; requiere control de historial |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/09-backend`, incluyendo:

- README principal;
- seccion `spring-boot`;
- proyectos `api-bd`, `api-crud`, `api-rest`, `apis-externas`, `hexagonal`, `seguridad` y `testing`;
- archivos `application.properties`;
- busqueda de carpetas generadas y posibles secretos.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | No detectado en auditoria inicial |
| Datos personales de terceros | Riesgo bajo por modelos con email, telefono, direccion y DNI |
| Imagenes, marcas, logos o personajes de terceros | No aplica |
| Credenciales, tokens o rutas sensibles | Riesgo alto |
| Fuentes externas pendientes | No evaluado por prioridad de seguridad |
| Uso de IA declarado | No aplica en codigo; falta nota general si se documenta para web |
| Enfoque comunitario | Parcial |
| Alineacion con politicas de Chilete DevPath | No cumple hasta sanitizar secretos |

## 3. Hallazgos criticos

La carpeta tiene valor tecnico porque contiene practicas reales de backend con Spring Boot, APIs, arquitectura hexagonal, seguridad, testing y consumo de APIs externas.

Sin embargo, no debe usarse para la web ni destacarse publicamente hasta corregir:

- tokens con formato real en archivos `application.properties`;
- contrasenas locales como `spring.datasource.password=admin`;
- configuraciones que deberian usar variables de entorno;
- posibles claves comentadas que tambien deben eliminarse si representan valores reales;
- README breve sin advertencias de seguridad ni guia de entorno.

No se registran los valores sensibles en este documento.

## 4. Decision

`aprendizaje/09-backend` queda como no publicable por ahora.

Antes de usarlo en la web o destacarlo, se debe ejecutar una fase de saneamiento:

- retirar tokens y claves del repositorio;
- reemplazar valores por variables de entorno;
- crear archivos `.example`;
- revisar historial si esos secretos ya fueron versionados;
- rotar o revocar tokens reales;
- documentar configuracion local segura.

## 5. Contenido que puede publicarse despues de saneamiento

- Explicacion de conceptos backend.
- Estructura de proyectos Spring Boot.
- Ejemplos de API REST, seguridad, testing y arquitectura hexagonal.
- Guias de ejecucion con variables de entorno.

## 6. Contenido que requiere ajuste antes de web

- Todos los `application.properties` con valores sensibles.
- README principal y README de Spring Boot.
- Proyectos que consumen APIs externas.
- Modulos de seguridad y JWT.

## 7. Saneamiento aplicado

Se reemplazaron valores sensibles detectados en archivos actuales por variables de entorno:

- credenciales de base de datos;
- tokens de APIs externas;
- token de Sonar;
- clave de firma JWT.

Importante: si alguno de los valores anteriores fue real y ya estuvo versionado, debe revocarse o rotarse. El saneamiento del archivo actual no elimina exposicion en historial Git ni en remotos.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | No por ahora |
| Requiere ajustes previos | Si, criticos |
| Mantener solo en GitHub | Solo si los secretos ya fueron saneados o son placeholders seguros |
| No publicar | Configuraciones con tokens, claves o credenciales |
