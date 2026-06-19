# Auditoria de Publicacion: aprendizaje/01-pseudocodigo

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-001 |
| Version | 1.0 |
| Estado | Alineado para GitHub; requiere adaptacion para web |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/01-pseudocodigo`, incluyendo:

- `README.md`
- `glosario.md`
- `checklist-avance.md`
- `pseint/README.md`
- 52 archivos `.psc` organizados por estructuras logicas.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | Riesgo medio |
| Datos personales de terceros | No detectado |
| Imagenes, marcas, logos o personajes de terceros | No aplica |
| Credenciales, tokens o rutas sensibles | No detectado |
| Fuentes externas pendientes | Contexto UTP declarado |
| Uso de IA declarado | Si, en documentacion |
| Enfoque comunitario | Si |
| Alineacion con politicas de Chilete DevPath | Alineado para GitHub; requiere adaptacion editorial para web |

## 3. Hallazgo principal

El modulo esta bien organizado y tiene valor formativo, pero varios archivos `.psc` incluyen comentarios iniciales con estructura de enunciado completo.

Como los ejercicios provienen de practicas del curso Principios de Algoritmos de UTP, para una web publica conviene evitar copiar o destacar enunciados completos. La version web debe usar explicaciones propias, resumenes del problema o nuevos enunciados redactados por Chilete DevPath.

La documentacion del modulo ya incluye criterio de marca, uso de datos ficticios, nota de fuente, uso responsable de IA y bienestar en el aprendizaje.

## 4. Decision

`aprendizaje/01-pseudocodigo` no debe pasar completo a la web tal como esta.

Puede usarse para la web si antes se aplica uno de estos criterios:

- reescribir los enunciados con palabras propias;
- publicar solo el objetivo tecnico del ejercicio;
- mostrar el codigo como evidencia, sin reproducir el enunciado completo;
- agrupar ejercicios por habilidad, no por copia literal del planteamiento;
- mantener una nota clara de contexto academico y autoria.

## 5. Contenido que puede publicarse

- README del modulo, con contexto academico claro.
- Glosario de pseudocodigo.
- Checklist de avance.
- Ruta sugerida de practica.
- Lista de temas: secuenciales, condicionales, `Segun`, `Para`, `Mientras`, `Repetir` y practica integrada.

## 6. Contenido que requiere ajuste antes de web

- Comentarios de enunciado dentro de los archivos `.psc`.
- Ejercicios que conserven narrativas completas trabajadas en clase.
- Referencias a evaluaciones, examenes o profesores, aunque sean genericas, si se usan como contenido destacado.

## 7. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | No completo |
| Requiere ajustes previos | Si |
| Mantener solo en GitHub | Si, mientras no se adapten enunciados |
| No publicar | No |

## 8. Ajuste aplicado

Se reforzo la documentacion del modulo con:

- criterio de marca para nombres y mensajes ficticios;
- ejemplos seguros como `Usuario Chilete`, `Aprendiz DevPath` y `Bienvenido a Chilete DevPath`;
- aclaracion de que el contenido academico no representa material oficial de UTP;
- regla para adaptar enunciados con palabras propias antes de llevarlos a la web.
