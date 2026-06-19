# Checklist de Publicacion Segura

| Campo | Detalle |
|---|---|
| Codigo | CDP-CHK-001 |
| Version | 1.1 |
| Estado | Vigente |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Ambito | Contenido que pueda publicarse en GitHub, web, portafolio o recursos para comunidad |
| Fecha de emision | 19/06/2026 |
| Proxima revision | 19/12/2026 |

## 1. Objetivo

Definir una revision practica antes de publicar contenido de Chilete DevPath, para reducir riesgos de autoria, propiedad intelectual, privacidad, seguridad, confusion academica o uso indebido de marcas.

## 2. Alcance

Este checklist aplica a:

- ejercicios de aprendizaje;
- proyectos academicos;
- proyectos personales;
- colaboraciones;
- README, glosarios, guias y fichas tecnicas;
- imagenes, capturas, documentos y recursos visuales;
- contenido que pueda alimentar la futura web de Chilete DevPath.

## 3. Criterios de decision

| Estado | Significado | Accion |
|---|---|---|
| Publicable | Contenido propio, claro y sin riesgos relevantes. | Puede pasar a la web o mantenerse publico. |
| Publicable con ajustes | Contenido util, pero requiere editar nombres, fuentes, imagenes, enunciados o avisos. | Ajustar antes de publicar o destacar. |
| Solo GitHub | Puede mantenerse como evidencia tecnica, pero no debe formar parte de la web principal por ahora. | Mantener con contexto y sin promocion publica destacada. |
| No publicar | Contiene material privado, marcas ajenas, datos personales, credenciales o contenido de terceros sin permiso. | Retirar, reemplazar o dejar local. |

## 4. Checklist obligatorio

Antes de publicar o destacar un contenido, responder:

| Pregunta | Si | No | Accion si la respuesta genera riesgo |
|---|---|---|---|
| El contenido fue creado por Adrian Pisco o Chilete DevPath? |  |  | Citar fuente, pedir autorizacion o crear version propia. |
| Usa material de UTP, Tecsup, docente, curso o evaluacion? |  |  | No publicar enunciados, rubricas ni material interno; redactar aprendizajes propios. |
| Contiene nombres, fotos, correos o datos de companeros, docentes o terceros? |  |  | Eliminar, anonimizar o publicar solo con autorizacion. |
| Usa marcas, logos, personajes, productos o imagenes de terceros? |  |  | Reemplazar por recursos propios, libres o debidamente autorizados. |
| Si usa assets propios, estan guardados y documentados como recursos de Chilete DevPath? |  |  | Registrar autoría, uso recomendado y restricciones antes de reutilizarlos. |
| Incluye credenciales, tokens, claves, rutas privadas o datos reales? |  |  | Eliminar y usar variables de entorno o archivos `.example`. |
| El README explica el contexto real del proyecto? |  |  | Aclarar si es aprendizaje, evaluacion, colaboracion o proyecto personal. |
| El contenido evita presentarse como oficial de una institucion o empresa? |  |  | Agregar aviso de no afiliacion o retirar la referencia. |
| Las fuentes externas estan citadas? |  |  | Agregar seccion `Fuentes` o `Referencias`. |
| El contenido puede explicarse con palabras propias? |  |  | Revisar antes de publicarlo como recurso educativo. |
| La licencia o uso permitido esta claro? |  |  | Definir licencia o restringir reutilizacion del recurso. |

## 5. Avisos recomendados

### Material academico

```md
Este repositorio documenta una practica academica desarrollada por Adrian Pisco como parte de su proceso formativo. No representa una publicacion oficial de la institucion educativa ni incluye material privado del curso, enunciados oficiales completos o rubricas internas.
```

### Contenido adaptado

```md
Contenido adaptado con explicaciones propias para Chilete DevPath. Las fuentes consultadas se indican en la seccion correspondiente.
```

### Colaboracion

```md
Este contenido corresponde a una participacion academica o colaborativa. Chilete DevPath documenta su aporte sin atribuirse la autoria completa del proyecto ni representar oficialmente a marcas, empresas o terceros mencionados.
```

### Assets propios

```md
Los recursos visuales usados en este contenido pertenecen a Chilete DevPath o cuentan con autorizacion directa de Adrian Pisco para su uso dentro del ecosistema de marca.
```

## 6. Regla de cierre

Si existe duda razonable sobre la publicacion de un recurso, no se publica en la web hasta que tenga una version propia, anonimizada, citada o autorizada.

## 7. Control de versiones

| Version | Fecha | Cambio | Responsable |
|---|---|---|---|
| 1.0 | 19/06/2026 | Emision inicial del checklist de publicacion segura. | Adrian Pisco |
| 1.1 | 19/06/2026 | Agrega criterio de assets propios y aviso de uso autorizado. | Adrian Pisco |
