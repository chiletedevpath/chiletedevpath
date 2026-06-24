# Matriz de Contenido para la Web

Esta matriz registra el criterio inicial para decidir que contenido del ecosistema Chilete DevPath puede alimentar la futura web de marca.

## Criterio general

La web debe priorizar contenido propio, educativo, claro y seguro. Los proyectos con marcas ajenas, colaboraciones sensibles, evaluaciones academicas o recursos visuales sin fuente deben revisarse antes de publicarse o destacarse.

## Regla visual para proyectos

Todo proyecto que aspire a mostrarse en la web de Chilete DevPath debe tener una imagen de presentacion propia o autorizada. Esta imagen funciona como portada visual del proyecto, no como evidencia academica.

### Criterios obligatorios

- No usar logos de instituciones educativas, empresas, restaurantes, comercios o terceros sin autorizacion.
- No usar fotografias de companeros, docentes, clientes, pacientes, usuarios o terceros.
- No mostrar datos personales, correos reales, DNI, telefonos, rutas locales, tokens, claves, capturas de Postman con respuestas sensibles ni paneles privados.
- No presentar el proyecto como oficial de UTP, Tecsup, una empresa o una marca ajena.
- Mantener una estetica propia de Chilete DevPath: educativa, tecnica, profesional y coherente con la identidad visual de la web.
- Registrar la imagen en el proyecto solo cuando este aprobada y tenga un nombre descriptivo.

### Prompt base para generar portadas

```txt
Crear una imagen horizontal profesional para la portada de un proyecto academico de software llamado "[NOMBRE DEL PROYECTO]". Debe representar [DOMINIO DEL PROYECTO] con enfoque tecnico en [TECNOLOGIAS O CONCEPTOS]. Estilo moderno, limpio, educativo y serio, alineado a una marca de aprendizaje Full Stack llamada Chilete DevPath. Usar una paleta inspirada en azul profundo, verde tecnico y acento dorado suave. No incluir logos de universidades, empresas, marcas reales, personas, documentos, capturas de pantalla ni texto pequeno ilegible. Composicion tipo banner para GitHub y web, con espacio visual para titulo.
```

### Ejemplo para `utp-ferreteria-sys-patrones`

```txt
Crear una imagen horizontal profesional para la portada de un proyecto academico de software llamado "FerreSys Patrones". Debe representar un sistema de ventas e inventario para ferreteria con enfoque tecnico en patrones de diseno, arquitectura Java, ventas, stock y comprobantes. Estilo moderno, limpio, educativo y serio, alineado a una marca de aprendizaje Full Stack llamada Chilete DevPath. Usar una paleta inspirada en azul profundo, verde tecnico y acento dorado suave. No incluir logos de universidades, empresas, marcas reales, personas, documentos, capturas de pantalla ni texto pequeno ilegible. Composicion tipo banner para GitHub y web, con espacio visual para titulo.
```

## Repositorios principales

| Contenido | Estado inicial | Decision para web | Motivo |
|---|---|---|---|
| `chiletedevpath` | Publicable | Si | Es la base de marca, politicas, identidad y futura documentacion web. |
| `aprendizaje` | Publicable con ajustes | Si, por secciones revisadas | Es la ruta educativa principal, pero cada carpeta debe pasar por el checklist antes de convertirse en recurso web. |
| `academia` | Publicable con ajustes | Si, como indice y seccion academica | Debe mostrar proyectos academicos con contexto, sin material privado ni datos personales innecesarios. |
| `portafolio` | En espera | No todavia | Aun no se han elegido proyectos finales de portafolio. |

## Proyectos UTP

| Contenido | Estado inicial | Decision para web | Motivo |
|---|---|---|---|
| `utp-clinica-salud-vital` | En proceso | No destacar por ahora | Proyecto academico propio con valor tecnico; continua en desarrollo y debe mantenerse sin documentos privados ni datos sensibles. |
| `academia/utp/ciclo-04/base-de-datos-i/ferreteria-soto-db` | Agrupado en academia | No destacar por ahora | Proyecto academico ya entregado; conservar como evidencia tecnica, sin tratarlo como repo independiente ni como proyecto bandera. |
| `utp-ferreteria-sys-patrones` | En proceso | No destacar por ahora | Proyecto academico con potencial tecnico; continua en desarrollo y aun no debe tratarse como proyecto bandera ni portafolio final. |
| `utp-la-lucha-bd-backend` | En espera | No por ahora | Proyecto academico vinculado al mismo contexto sensible de La Lucha; debe revisarse junto con frontend antes de evaluar su publicacion web. |
| `utp-colab-la-lucha-frontend` | No publicar por ahora | No | Tiene riesgo por nombre, imagenes, marca y caracter colaborativo. Requiere ajustes de identidad, recursos visuales y disclaimers antes de evaluarlo para web. |

## Proyectos Tecsup

| Contenido | Estado inicial | Decision para web | Motivo |
|---|---|---|---|
| `academia/tecsup/cursos/fullstack-con-java/proyectos/backend-final-exam` | Agrupado en academia | No destacar por ahora | Es una evaluacion final ya entregada; publicar solo codigo propio y contexto general, sin enunciado oficial ni rubrica. |
| `academia/tecsup/cursos/fullstack-con-java/proyectos/crud-react-productos` | Agrupado en academia | No destacar por ahora | Practica tecnica entregada; puede servir como evidencia academica, pero no debe pasar a web sin revision visual, fuentes y contexto. |
| `academia/tecsup/cursos/fullstack-con-java/proyectos/sunat-consulta` | Agrupado en academia | No destacar por ahora | Proyecto tecnico con integracion externa; se retiraron evidencias sensibles y solo debe usarse como referencia academica hasta generar ejemplos seguros. |

## Secciones de aprendizaje

| Contenido | Estado inicial | Decision para web | Motivo |
|---|---|---|---|
| `00-fundamentos` | Publicable auditado | Si | Seccion base alineada a Chilete DevPath, sin archivos privados, imagenes, marcas ajenas ni fuentes externas pendientes. |
| `01-pseudocodigo` | Publicable con ajustes | Si, despues de adaptar enunciados | Contenido valioso de aprendizaje UTP, pero varios `.psc` conservan comentarios tipo enunciado que deben reescribirse o resumirse antes de llevarlos a la web. |
| `02-programacion-basica` | Saneado con ajustes editoriales pendientes | Si, despues de mejorar README | Se neutralizaron claves, DNI de ejemplo y marcas reales detectadas. Falta contexto comunitario y revision de paquetes `edu.pe.utp`. |
| `03-poo` | Saneado con ajustes editoriales pendientes | Si, por partes revisadas | Se retiraron imagenes sin fuente, HTML generado y datos personales de ejemplo. Falta mejorar README y explicar origen academico de practicas. |
| `04-estructuras-datos` | Publicable con ajustes menores | Si, despues de mejorar documentacion | No se detectaron archivos privados, imagenes ni datos personales; requiere README mas completo y contexto para comunidad. |
| `05-algoritmos` | Saneado con ajustes editoriales pendientes | Si, despues de mejorar contexto | Se neutralizaron nombres y direcciones de ejemplo en archivos indexados. Falta README mas completo y nota de datos ficticios. |
| `06-bases-de-datos` | Saneado con ajustes editoriales pendientes | Si, despues de mejorar contexto | Se neutralizaron correos, telefonos y nombres de ejemplo detectados. Falta declarar datos ficticios y contextualizar practicas de clase. |
| `07-desarrollo-web` | Saneado con ajustes editoriales pendientes | Si, por partes revisadas | Incluye practicas base, PHP y `frontend-retos`; revisar imagenes, fuentes y enunciados antes de web. |
| `08-patrones` | Saneado parcial; no publicar evaluaciones como bloque | Si, solo conceptos adaptados | Se corrigio README principal y se neutralizaron correos/nombres/marcas detectadas. Las evaluaciones y enunciados aun requieren adaptacion antes de web. |
| `09-backend` | Saneado en archivos actuales; requiere control de historial | No destacar aun | Se reemplazaron secretos por variables de entorno. Si los valores previos fueron reales, deben revocarse y revisarse en historial Git antes de publicacion web. |
| `10-frontend` | En espera | Si, como ruta futura | No presenta riesgos detectados, pero aun no tiene contenido suficiente para funcionar como modulo web completo. |

## Regla para La Lucha y colaboraciones

Los proyectos vinculados a La Lucha y los proyectos colaborativos no deben formar parte de la web principal ni tener repositorio propio de marca hasta revisar:

- autoria real;
- permisos del equipo;
- uso de marcas o nombres comerciales;
- imagenes y recursos visuales;
- datos personales;
- contexto academico;
- posibilidad de reemplazar marca, imagenes y textos por una version neutral.

## Proxima revision sugerida

Iniciar por `aprendizaje`, carpeta por carpeta, porque sera la base educativa de la futura web. Luego revisar `academia` como indice publico y, finalmente, evaluar proyectos destacados para portafolio.
