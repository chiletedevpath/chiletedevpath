# Auditoria de Publicacion: aprendizaje/02-programacion-basica

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-002 |
| Version | 1.0 |
| Estado | Saneado con ajustes editoriales pendientes |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/02-programacion-basica`, incluyendo:

- README principal;
- subcarpetas `variables`, `tipos-datos`, `condicionales`, `bucles`, `funciones`, `cadenas` y `arreglos`;
- 67 archivos Java;
- README internos disponibles.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | No confirmado, requiere contexto |
| Datos personales de terceros | No detectado |
| Imagenes, marcas, logos o personajes de terceros | Riesgo bajo por marcas usadas como ejemplos |
| Credenciales, tokens o rutas sensibles | Riesgo bajo por claves de practica |
| Fuentes externas pendientes | Requiere declaracion de origen |
| Uso de IA declarado | No aplica en codigo; falta nota general si se documenta para web |
| Enfoque comunitario | Parcial |
| Alineacion con politicas de Chilete DevPath | Requiere ajustes |

## 3. Hallazgos

La seccion tiene valor tecnico porque cubre fundamentos reales de Java: variables, tipos, condicionales, bucles, funciones, cadenas y arreglos.

Antes de llevarla a la web, se deben atender estos puntos:

- el README principal es muy breve para funcionar como recurso comunitario;
- algunos paquetes usan `edu.pe.utp`, lo que sugiere origen academico y debe explicarse;
- hay ejercicios con DNI como dato de ejemplo;
- hay claves de practica como `java123` o `P@55w0rd`;
- hay marcas reales usadas como ejemplo en encuestas;
- algunos ejercicios pueden venir de clase y deben documentarse como practica propia o adaptada, no como material oficial.

## 4. Decision

`aprendizaje/02-programacion-basica` puede mantenerse en GitHub como evidencia de practica.

Para la futura web no debe publicarse como bloque final hasta limpiar y contextualizar el contenido.

## 5. Contenido que puede publicarse

- Ruta de temas de programacion basica.
- Explicaciones propias de variables, tipos, condicionales, bucles, funciones, cadenas y arreglos.
- Ejercicios Java seleccionados y revisados.
- Ejemplos sin datos personales ni marcas reales.

## 6. Contenido que requiere ajuste antes de web

- README principal y README de subcarpetas.
- Ejercicios que pidan DNI o simulen credenciales.
- Ejercicios con marcas reales como opciones de encuesta.
- Paquetes `edu.pe.utp`, si se decide presentar el contenido como recurso general de Chilete DevPath.
- Comentarios o enunciados que provengan de clase y no esten redactados con palabras propias.

## 7. Saneamiento aplicado

Se neutralizaron los puntos de riesgo detectados en archivos actuales:

- claves de practica reemplazadas por valores genericos;
- DNI de ejemplo reemplazados por identificadores ficticios;
- marcas reales usadas en encuestas reemplazadas por opciones neutrales.

La seccion aun requiere mejoras de README y contexto antes de transformarse en contenido web comunitario.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | No completo |
| Requiere ajustes previos | Si |
| Mantener solo en GitHub | Si, mientras no se limpie editorialmente |
| No publicar | No |
