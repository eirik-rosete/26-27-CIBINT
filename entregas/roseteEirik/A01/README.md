# A01 · Del dato a la inteligencia

> **Cómo usas esta plantilla**
>
> Cópiala a `entregas/apellidoNombre/A01/README.md` y trabaja **sobre esa copia, dentro de tu carpeta**. No edites este archivo ni la carpeta de nadie más.
>
> Rellena los apartados sin cambiar su orden ni su numeración. Si algo no te aplica, explica por qué en lugar de borrarlo. Borra estas instrucciones antes de entregar.
>
> Recuerda: debes acompañar cada afirmación con el identificador del que sale — `(C05)`, `(C07, C08)`, `(F01)`. Resuelves los pasos 1 a 4 solo con la cronología inicial.
>
> Enunciado completo: [A01 · Del dato a la inteligencia](../../../actividades/A01-del-dato-a-la-inteligencia/README.md)

## Estudiante

- Nombre: Eirik Alberto Rosete León
- Carpeta personal: entregas/roseteEirik

---

## 1. Ordena lo que sabes

### 1.1 Clasificación de las frases

| Frase | Categoría | Justificación |
|---|---|---|
| A | Dato | Es un suceso reportado con una fecha, sin relación con algún otro dato o contexto (C03) |
| B | Dato | El dato expone únicamente que se desconoce que responsable o agente fueron los que realizaron el ataque (C13) |
| C | Inteligencia | Esto es inteligencia debido a que hace uso de datos (C05, C08) entrelazados en un mismo contexto (el ciberataque) y la necesidad concreta es la de identificar qué plataformas se vieron realmente afectadas (S06), que fueron meramente internas (C06), permitiendo notificar el alcance del ataque. |
| D | Información | Estamos brindándole contexto de nuestra situación como empresa a un dato brindado por el reporte de Hugging Face (C07) |
| E | Ninguno | A pesar de brindar acciones de emergencia, no estamos brindando las justificaciones necesarias ni haciendo referencia a los datos brindados por el reporte de Hugging Face, que en su caso deberían ser: C06, C08 |



### 1.2 Dato, información e inteligencia propios

| Capa | Formulación | Filas usadas | Qué limitación tiene |
|---|---|---|---|
| Dato | La actividad escaló hasta acceso a nivel de nodo, recolección de credenciales de nube y de clúster, y movimiento lateral por varios clústeres internos a lo largo de un fin de semana. | C06 | ¿hay cuentas o recursos de organizaciones asociadas de algún modo con las credenciales internas? |
| Información | Las credenciales internas de los servicios se vieron vulneradas, obteniendo credenciales y conjuntos de datos internos y afectando los clústeres y nodos de producción un fin de semana completo | C03, C04, C06, S06, S10 | ¿con qué certidumbre podemos afirmar que la información vulnerada no está almacenada en algún otro sitio? |
| Inteligencia | Tomando en cuenta la extracción de conjuntos de datos y posible asociación de credenciales internas con productos o tokens de organizaciones y usuarios, siendo que puedan haber sido almacenadas en un ambiente independiente al ciberataque, es factible hacer una rotación de credenciales | C04, S06, S07 | ¿con qué frecuencia? |

---

## 2. Completa el requerimiento

### 2.1 Revisión de los componentes de la petición

> «He visto lo de la brecha de Hugging Face. Mira a ver todo lo que haya y dime si nos afecta.»

| Componente | ¿Está? | Qué dice, o qué falta |
|---|---|---|
| Destinatario | Parcial | Es impreciso, puede inferirse que es mi responsable porque menciona la palabra "*Dime*" |
| Decisión | No | Únicamente esta preguntando si nos afecta, no está solicitando una decisión ni acciones/medidas que implementar. |
| Objeto | Sí | Nos comunica lo de la brecha a Hugging Face, pero desconocemos que elementos y servicios manejamos nosotros o con qué es que estamos relacionados con el incidente; está delegando todo el trabajo para que "mire todo lo que haya" |
| Horizonte | No | No hay una solicitud expresa de tiempo o urgencia en la petición del responsable |
| Alcance | No | La información acerca de la cronología inicial y los hechos son datos públicos, no nos fueron brindados. No tenemos datos de qué "nos afecta", es decir, no hay perímetro interno delimitado para investigar |
| Exclusiones | No | No limita ni prohibe acciones a realizar |
| Producto | No | Dice "*Dime*", pero no específica el formato de entrega |

### 2.2 Componentes completados

<!-- Contenido de los componentes que faltaban o que estaban sin concretar. -->

| Componente | Daro faltante o sin concretar |
|---|---|
| Destinatario | El rol que tiene mi responsable, quien seguramente sea el responasble de seguridad del equipo de ciberinteligencia |
| Decisión | |
| Objeto | |
| Horizonte | Antes de las 13:00, con una recomendación |
| Alcance | |
| Exclusiones | |
| Producto | |

### 2.3 Requerimiento en una frase

>

### 2.4 Preguntas de inteligencia

| Prioridad | Pregunta | Te ayuda a decidir |
|---:|---|---|
| 1 | | |
| 2 | | |

---

## 3. Planifica el ciclo

### 3.1 Recorrido por las fases

| Fase | Entrada utilizada | Decisión o tarea | Salida | Siguiente fase |
|---|---|---|---|---|
| Dirección y planificación | | | | |
| Obtención | | | | |
| Procesamiento | | | | |
| Análisis y producción | | | | |
| Difusión | | | | |
| Retroalimentación | | | | |

---

## 4. Responde

### 4.1 Nota para el comité

**Qué puedes afirmar el 20 de julio**

<!-- Con sus identificadores. -->

**Nivel de confianza y justificación**

<!-- Baja, media o alta, y qué la sostiene en ese nivel y no en otro. -->

**Recomendación al comité**

| Opción | ¿La activas? | Por qué, y por qué es proporcionada |
|---|---|---|
| | | |

**Limitación**

<!-- Qué te falta saber y cómo condiciona lo anterior. -->

### 4.2 Hechos, inferencias y supuestos

| Afirmación de tu nota | ¿Hecho, inferencia o supuesto? | Por qué |
|---|---|---|
| | | |
| | | |
| | | |

---

## 5. Revisa

### 5.1 Revisión de conclusiones

| Conclusión previa | ¿Cambia o se confirma? | Hecho que lo provoca | Nueva formulación |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

### 5.2 Efecto sobre la recomendación

<!-- ¿Cambiarías tu recomendación al comité? Sí o no, y por qué. -->

### 5.3 Conclusión sobre la retroalimentación

<!-- Una frase. -->

---

## Fuentes

| Identificador | Fuente | URL | Fecha de consulta |
|---|---|---|---|
| F01 | | | AAAA-MM-DD |

<!-- Solo las que hayas usado de verdad. Si añades fuentes propias, numéralas F13, F14… -->

## Decisiones y limitaciones

<!-- Cualquier decisión de método o límite que quieras dejar por escrito. -->

## Colaboración

<!-- Si trabajaste algún aspecto con otra persona, indica qué parte fue individual. -->

## Uso de inteligencia artificial

> **Apartado obligatorio.** Si no lo completas, tu entrega está incompleta y no se califica.

| | |
|---|---|
| **Herramienta utilizada** | <!-- Nombre, o «No se ha utilizado ninguna» --> |
| **Para qué la usaste** | <!-- Corrección de texto, búsqueda de ideas, generación de código, redacción… --> |
| **En qué fase intervino** | <!-- Paso 1, paso 3, revisión final… --> |

## Comprobación

- [ ] He trabajado sobre una copia de la plantilla, dentro de `entregas/apellidoNombre/A01/`.
- [ ] He resuelto los pasos 1 a 4 solo con la cronología inicial.
- [ ] Cada afirmación lleva su identificador y he comprobado que dice lo que le atribuyo.
- [ ] No he interactuado con ninguna infraestructura ni servicio del caso.
- [ ] No incluyo exploits, credenciales, indicadores operativos ni datos personales.
- [ ] He incluido el apartado de uso de inteligencia artificial con los tres puntos.
- [ ] Solo he modificado `entregas/apellidoNombre/A01/`.
