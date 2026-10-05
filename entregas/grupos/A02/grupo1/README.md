# Plan de investigación · Grupo 1 · Ministerio de Hacienda

> **Plantilla de respuesta del grupo 1 · actividad A02.**
>
> Este archivo es el plan de investigación de tu grupo. **Se trabaja directamente sobre él** y es el documento que se entrega y se evalúa.
>
> Instrucciones de uso:
>
> 1. Mantén los encabezados y su numeración.
> 2. Sustituye cada bloque «**Qué debe contener**» por el contenido del grupo. No dejes ninguno sin sustituir.
> 3. Cita cada afirmación sobre el caso con su identificador: `(H05)`, `(F04)`.
> 4. Borra este recuadro de instrucciones antes de entregar.
>
> Enunciado completo: [A02 · Plan de investigación](../../../../actividades/A02-plan-de-investigacion/README.md)

## Ficha del plan

| Campo | Contenido |
|---|---|
| Grupo | 1 |
| Caso | Supuesta sustracción de datos de contribuyentes atribuida al Ministerio de Hacienda, febrero de 2026 |
| Material de partida | [casos/hacienda](../../../../actividades/A02-plan-de-investigacion/casos/hacienda/README.md): `H01`–`H13` y `F01`–`F06` |
| Portavoz | |
| Miembros del equipo | |

---

## 1. Resumen del plan

> **Qué debe contener:** un párrafo, escrito al final, que permita entender el plan sin leer el resto: qué se querría saber y para qué, con qué fuentes y técnicas, con qué exclusiones principales y durante cuánto tiempo.

## 2. Situación

### 2.1 Afirmaciones sobre el caso

| ID | Qué se afirma | Quién lo afirma | ¿Lo confirma alguien independiente? | Valoración |
|---|---|---|---|---|
| | | | | |

> **Qué debe contener:** todas las afirmaciones relevantes del material de partida. La valoración indica cómo debe tratarse cada una: establecida, afirmada sin confirmar, cálculo o interpretación de un tercero, contradicha por otra fuente, etc.

### 2.2 Lo que puede darse por establecido

**Existencia de una oferta de venta de datos**: _[F01, F02, F03, F04, F06]:_ El 31 de enero de 2026 se hizo visible en foros de la dark web una publicación de un actor bajo el alias **HaciendaSec**, en la que afirma haber sustraído y puesto a la venta una base de datos con información personal, bancaria y fiscal de 47,3 millones de ciudadanos. **_Por qué se considera establecido:_** Es un hecho objetivo y documentado el evento de la publicación y las afirmaciones del actor, reportado por empresas de monitorización (Hackmanac, UpGuard) y múltiples medios. (Nota: Se da por establecida la existencia del anuncio, no la veracidad de las afirmaciones del atacante).

**Inexistencia de intrusión en los sistemas propios del Ministerio**: _[F04, F05]_: Tras verificaciones internas y auditorías técnicas, el Ministerio de Hacienda no ha detectado rastros de ciberataque, accesos no autorizados ni exfiltración de información en sus sistemas oficiales. Por qué se considera establecido: Existe una declaración oficial e inequívoca de la organización afectada [F04], respaldada por el análisis de un organismo público técnico e independiente (Cibersegurida de Galicia) [F05].

### 2.3 Lo que no se sabe

| ID | Laguna | Se puede reducir mediante fuentes abiertas? | Motivo | 
| - | - | - | - |
| 01 | No se sabe si los datos que se han puesto a la venta, ni la muestra son reales o no, y, si en caso de serlo, son reales únicamnete los de la muestra | En parte | Si se puede comprobar si la muestra es real o no, pero no se pueden comprobar el resto de datos sin comprarlos |
| 02 | No se conoce ningun dato del hacker 'HaciendaSec', además, su cuenta no tiene ninguna publicación y ha sido creada hace menos de un mes, por lo que carece también de credibilidad | Si | Se conoce el nombre del atacante, por lo que se puede hacer una investigacion basada en fuentes publicas |
| 03 | Si los datos de Hacienda se han visto realmente vulnerados o no | No | No se puede saber sin tener acceso al propio sistema interno de Hacienda |

## 3. Necesidad de inteligencia

| Pregunta | Laguna de la que procede (2.3) | Quién usaría la respuesta | Para qué decisión o protección |
|---|---|---|---|
| La información publicada como muestra, ¿es cierta? | 01 | Ministerio de Hacienda y AEPD | Para confirmar la posibilidad de que el atacante tenga acceso a los datos |
| Si la información de muestra es cierta, ¿era información ya filtrada previamente o completamente nueva? | 01 | Ministerio de Hacienda y AEPD | Para saber si es necesario tomar medidas al respecto o es únicamente un intento de estafa con datos falsos |
| ¿Quién es HaciendaSec?, ¿Puede ser el responsable de/estar relacionado con los robos de datos en la Agencia Tributaria en 2025? | 02 | Grupo de delitos telemáticos (GDT) | Para tomar las acciones legales necesarias contra el atacante |
| ¿Existen vulnerabilidades en la infraestructura de Hacienda que puedan dar legitimidad a las filtraciones? | 03 | Equipo de ciberseguridad de Hacienda | Para solventarlo y evitar futuras filtraciones |

### Preguntas que no se intentarán responder
| Pregunta | Por qué |
| - | - |
| ¿Son reales todos los datos que posee el atacante? | Para contestar esta pregunta, seria necesario comprar lo que vende el atacante, que no es una fuente abierta |
| ¿Por dónde ha accedido el hacker a la bd de Hacienda? | Para saberlo sería necesario acceder a las redes internas de Hacienda, lo que no está permitido sin su autorización |
| ¿Que hay en los logs de hacienda con respecto a accesos? | No hay acceso público a estos datos | 

## 4. Legitimación y no interferencia
**Quién investiga y desde qué posición**
Nosotros, como estudiantes de la asignatura de Ciberinteligencia, estamos realizando una práctica para la asignatura sobre este caso. Por ende, al no ser la policía, el CNI o una empresa privada contratada por Hacienda, no tenemos permiso para acceder a datos personales. Nuestra posición es únicamente para aprendizaje, basándonos en un caso real e información pública que sí podemos tratar.

**Marco normativo aplicable**
Nuestra investigación se basa en recopilar información de fuentes abiertas (OSINT) desde España. Por esto debemos acatar las leyes generales y, a su vez, seguir la normativa de protección de datos (RGPD europeo y LOPDGDD española). También queremos recalcar que para la realización de esta investigación se tendrá en cuenta el Protocolo de Berkeley mencionado en clase, para cumplir con la metodología propuesta y las enseñanzas aprendidas.

**Responsable de los datos y base de licitud**
Para esta investigación, el responsable de tratamiento de datos somos los propios estudiantes. Debemos ser conscientes de qué datos disponemos y hasta dónde podemos llegar; también es importante aclarar que la propia universidad nos aporta ciertos datos como base en las instrucciones de la actividad, como el archivo Hechos.csv y el archivo Fuentes.csv.

Además, en el marco legal, nosotros proponemos un seguimiento de interés legítimo. Esto quiere decir que, en caso de encontrar datos de terceros sin disponer de su consentimiento, queremos aclarar que nuestro interés es académico y no queremos exponer a terceros. Por esto nos limitaremos a tratar únicamente la información que esté a nuestra disposición y no afecte a la integridad de otros.

**Qué NO nos corresponde y a quién sí**
En primer lugar, nosotros somos estudiantes y no tenemos autoridad legal ni operativa. Como estudiantes nos hacemos una pregunta clave para realizar la actividad: ¿cómo actuaría un equipo de investigación autorizado? Con esta pregunta podemos derivarla en otras que se haría dicho equipo y podemos responder cómo las trataríamos.

¿Podemos acceder a los servidores de Hacienda para hacer un análisis forense? No, eso le corresponde al Ministerio y al CCN-CERT.

¿Podemos detener a HaciendaSec? No, eso le corresponde a las Fuerzas y Cuerpos de Seguridad del Estado (FCSE).

¿Podemos auditar si Hacienda protegía bien los datos o sancionarles? No, eso le toca a la Agencia Española de Protección de Datos (AEPD).

¿Podemos comprarle la base de datos a HaciendaSec para ver si es real? No (estaríamos financiando un delito).

**Otras investigaciones y no interferencia**
Usando las fuentes, sabemos seguro que hay investigaciones en curso por parte del Ministerio de Hacienda (auditoría interna) y el CCN-CERT (mencionado en F06). Además, es lógico deducir que la Policía/Guardia Civil investigará la venta en la dark web, y la AEPD el posible fallo de seguridad.

¿Cómo evitamos entorpecerlas? Aquí agregamos el concepto de investigación pasiva. Queremos dejar claro que nuestro grupo NO interactuará con el atacante (nada de crear un usuario falso para chatear con HaciendaSec en el foro), NO escanearemos de forma activa los puertos o servidores del Ministerio, y NO alertaremos a las víctimas. Solo observaremos información que ya es pública.

## 5. Plan de obtención

### 5.1 Fuentes y técnicas previstas

| ID | Fuente o técnica | Pregunta a la que responde (3) | Por qué es lícita | Por qué es la menos intrusiva disponible | Qué expondría y a quién |
|---|---|---|---|---|---|
| OB1 | | | | | |

### 5.2 Evaluaciones de licitud

> **Qué debe contener:** la [plantilla de evaluación de licitud](https://github.com/hector-ae21/CIBINT/blob/main/plantillas/plantilla-evaluacion-licitud.md) completa para las dos fuentes o técnicas del plan que el grupo considere más delicadas, con la justificación de por qué son esas dos.

## 6. Reglas de actuación

### 6.1 Lo que se haría solo con condiciones

| Actuación | Condición que debería cumplirse | Quién comprobaría que se cumple |
|---|---|---|
| | | |

### 6.2 Lo que no se haría

| Exclusión propia de este caso | Por qué |
|---|---|
| | |

> **Qué debe contener:** las tentaciones concretas que este caso ofrece a quien lo investiga, descartadas de forma expresa y razonada. Copiar las normas de la asignatura no cumple este apartado.

### 6.3 Condiciones de parada

| Si ocurriera… | El equipo… | Y consultaría a… |
|---|---|---|
| | | |

## 7. Tratamiento de datos personales

| Datos que podrían aparecer aunque no se buscasen | De quién | Cómo se minimizarían | Dónde se guardarían y quién accedería | Cuándo y cómo se borrarían |
|---|---|---|---|---|
| | | | | |

## 8. Seguridad de la operación

### 8.1 OPSEC de la investigación

| Paso | En este caso |
|---|---|
| Información crítica | |
| Amenazas | |
| Vulnerabilidades | |
| Riesgo | |
| Contramedidas | |

### 8.2 Identidad de investigación

> **Qué debe contener:** con qué identidad se consultarían las fuentes, por qué es la adecuada para este caso y qué identidades se descartan.

### 8.3 Riesgos para las personas y conflictos de intereses

> **Qué debe contener:** riesgos para las personas afectadas por el incidente, para el equipo, incluido el riesgo psicológico, y cualquier conflicto de intereses de los miembros del grupo, con la medida que se aplicaría a cada uno.

## 9. Trazabilidad y custodia

> **Qué debe contener:** qué se registraría y cuándo, cómo se conservarían las evidencias, cómo se demostraría que no se han alterado y quién las custodiaría.

## 10. Manejo y difusión

| Producto | Destinatario | Canal | Etiqueta TLP | ¿Podría publicarse en este repositorio? ¿Por qué? |
|---|---|---|---|---|
| | | | | |

> **Qué debe contener:** además de la tabla, si procedería compartir algo con algún organismo, con cuál y en qué condiciones.

## 11. Alcance de la investigación

| Campo | Definición |
|---|---|
| Objetivo | |
| Finalidad | |
| Fuentes permitidas | |
| Técnicas permitidas | |
| Exclusiones específicas | |
| Canal de entrega del resultado | |
| Vigencia | |

> **Qué debe contener:** el compromiso que asumiría el equipo. Debe corresponder exactamente al resto del plan.

---

## Fuentes

| ID | Organización | Título | Fecha de consulta |
|---|---|---|---|
| | | | AAAA-MM-DD |

> **Qué debe contener:** las fuentes del material de partida que el grupo ha leído y citado.

## Equipo

### Organización del trabajo

> **Qué debe contener:** cómo se ha organizado el grupo y quién se ha encargado de qué.

### Aportación individual

> **Qué debe contener:** un apartado por miembro, escrito por la propia persona y con su nombre: qué ha hecho, qué decisión del grupo defendió o discutió y qué le resultó más difícil.

## Uso de inteligencia artificial

La declaración está en [registro-ia.md](registro-ia.md).

## Comprobación antes de entregar

- [ ] Todos los bloques «Qué debe contener» están sustituidos.
- [ ] Ninguna afirmación no confirmada se presenta como establecida.
- [ ] No se ha realizado ninguna búsqueda ni obtención de información fuera del material de partida.
- [ ] El repositorio no recibe archivos de noticias, capturas con datos personales ni material no publicable.
- [ ] `registro-ia.md` está completo, con los prompts, o declara que no se ha usado IA.
- [ ] El *pull request* solo modifica archivos de la carpeta del grupo.
