# Auditoria de Publicacion: aprendizaje/07-desarrollo-web

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-007 |
| Version | 1.0 |
| Estado | Saneado con ajustes editoriales pendientes |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/07-desarrollo-web`, incluyendo:

- README principal;
- secciones `html`, `css`, `javascript`, `php` y `practica-ui`;
- archivos HTML, CSS, PHP e imagenes.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | Riesgo bajo/medio en PHP por origen academico |
| Datos personales de terceros | No detectado; contiene datos personales propios en CV |
| Imagenes, marcas, logos o personajes de terceros | Riesgo alto por `goku.png` e imagenes sin fuente |
| Credenciales, tokens o rutas sensibles | No detectado |
| Fuentes externas pendientes | Si, para imagenes y recursos visuales |
| Uso de IA declarado | Si en PHP; falta criterio general para el resto |
| Enfoque comunitario | Parcial |
| Alineacion con politicas de Chilete DevPath | Requiere ajustes fuertes |

## 3. Hallazgos

La seccion tiene valor porque ordena fundamentos web: HTML, CSS, JavaScript, PHP y practica de interfaz.

No debe pasar a la web como bloque completo por ahora porque:

- `css/aplicacion-css3/img/goku.png` usa un personaje protegido y debe reemplazarse o retirarse;
- `html/cv-web` contiene foto, correo, LinkedIn y datos personales de una version antigua de CV;
- `practica-ui` contiene imagenes grandes sin fuente documentada;
- algunas practicas visuales pueden necesitar reemplazo de assets;
- PHP esta mejor documentado, pero debe revisarse ejercicio por ejercicio antes de convertirlo en recurso publico.

## 4. Decision

`aprendizaje/07-desarrollo-web` puede mantenerse en GitHub como evidencia de aprendizaje.

Para la futura web solo debe usarse por partes, despues de limpiar recursos visuales, datos personales y origen de ejercicios.

## 5. Contenido que puede publicarse despues de ajuste

- Explicacion de diferencia entre desarrollo web base y frontend moderno.
- PHP como modulo de aprendizaje inicial, con contexto UTP claro.
- Ejercicios HTML/CSS/JS seleccionados sin recursos de terceros.
- Practicas UI con imagenes propias, libres o generadas para Chilete DevPath.

## 6. Contenido que requiere ajuste antes de web

- `goku.png` y referencias a Goku.
- `html/cv-web`, por contener informacion personal y marca de CV antiguo.
- Imagenes de `practica-ui`.
- README de HTML, CSS, JavaScript y practica UI.
- Enunciados o practicas PHP si provienen de clase y no estan redactados con palabras propias.

## 7. Saneamiento aplicado

Se neutralizaron los riesgos principales en archivos actuales:

- se retiro la imagen de personaje protegido y se reemplazo por una figura CSS;
- se reemplazo el CV web con datos personales por una plantilla neutral;
- se retiraron imagenes de practica UI sin fuente documentada y se reemplazaron por figuras CSS;
- se eliminaron carpetas de imagenes que quedaron vacias.

La seccion puede avanzar por partes, pero PHP y los README de modulos aun deben revisarse ejercicio por ejercicio antes de publicacion web.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | No como bloque completo |
| Requiere ajustes previos | Si |
| Mantener solo en GitHub | Si, por ahora |
| No publicar | No completo, pero algunos recursos visuales no deben usarse sin reemplazo |
