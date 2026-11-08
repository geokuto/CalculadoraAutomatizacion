# Automatizar u optimizar

*Automatitzar o optimitzar · Automate or optimise*

**Herramienta web para decidir si merece la pena automatizar una tarea repetitiva, cuánto tiempo se ahorraría y cómo mejorar el procedimiento antes.**

Se basa en **D-MAP (Diagnóstico y Mejora Aplicada de Procesos)**, un marco de análisis propio, desarrollado para «Automatizar u optimizar», que combina principios de Lean, Six Sigma y análisis de riesgos para evaluar y mejorar procesos antes de automatizarlos.

> La mejor automatización no siempre es la que ahorra más tiempo. A veces, la mejor decisión consiste en dejar de hacer algo que nunca fue necesario.

---

## Índice

1. [Qué es y para qué sirve](#1-qué-es-y-para-qué-sirve)
2. [Principios](#2-principios)
3. [Cómo se usa: los cinco pasos](#3-cómo-se-usa-los-cinco-pasos)
4. [El marco D-MAP](#4-el-marco-d-map)
5. [Cómo funciona por dentro](#5-cómo-funciona-por-dentro)
6. [Privacidad](#6-privacidad)
7. [Idiomas, diseño y accesibilidad](#7-idiomas-diseño-y-accesibilidad)
8. [Estructura técnica](#8-estructura-técnica)
9. [Pruebas](#9-pruebas)
10. [Personalización](#10-personalización)
11. [Limitaciones y fases posteriores](#11-limitaciones-y-fases-posteriores)
12. [Autoría y créditos](#12-autoría-y-créditos)

---

## 1. Qué es y para qué sirve

«Automatizar u optimizar» es una página web de un solo archivo que funciona en el navegador, sin registro ni servidor. A partir de la descripción de una tarea y de unas pocas preguntas, responde a tres cuestiones:

1. **¿Merece la pena automatizar esta tarea?**
2. **¿Cuánto tiempo se ahorraría?**
3. **¿Qué conviene mejorar del procedimiento antes, o en lugar de automatizar?**

La idea que la diferencia de una simple calculadora es que **cuestiona el procedimiento**. Automatizar un proceso mal diseñado solo hace más rápido un mal proceso, así que la herramienta sigue un orden deliberado:

1. Comprobar si la tarea es necesaria.
2. Eliminar duplicidades y simplificar.
3. Automatizar lo que queda.

Está pensada para cualquier persona que haga tareas administrativas repetitivas, sin necesidad de conocimientos técnicos, y también para responsables de operaciones, equipos de gestión y profesionales de mejora continua.

---

## 2. Principios

- **Sin datos inventados.** Ninguna cifra que influya en el resultado se rellena con valores genéricos. Si falta un dato, la herramienta lo dice y no lo supone.
- **Transparencia.** Cada conclusión indica en qué respuestas se basa. Se distingue siempre entre datos introducidos, datos calculados, hipótesis y recomendaciones.
- **Reglas explícitas, no inteligencia artificial.** El diagnóstico y los cálculos son deterministas: con las mismas respuestas, siempre el mismo resultado.
- **La IA solo cuando hace falta.** La herramienta no recomienda IA cuando bastan una plantilla, una regla o una mejora organizativa.
- **Prudencia.** Si faltan respuestas, el resultado se presenta como provisional y no da una recomendación que dependa de lo que falta.
- **Privacidad.** Nada de lo que se escribe sale del navegador.

---

## 3. Cómo se usa: los cinco pasos

### Paso 1 · Tarea

Se describe la tarea con palabras propias, por ejemplo: «Cada semana descargo un Excel, reviso los expedientes pendientes y envío correos a las personas responsables. Me lleva 2 horas, de las que 30 minutos se van en copiar datos».

Al pulsar **Analizar mi tarea**, un analizador por reglas lee la descripción y **propone** respuestas: frecuencia, tiempo, herramientas, si se copian datos, si hay esperas o aprobaciones, minutos perdidos en pasos sin valor… Las propuestas aparecen marcadas como «Propuesta», junto con la frase en la que se basan, y siempre se pueden cambiar. Si no se escribe nada, se puede continuar igualmente.

### Paso 2 · Datos

- **Lo esencial:** el tiempo de trabajo activo y si se indica por persona o para todo el equipo, la frecuencia, el número de personas y seis preguntas clave sobre cómo funciona la tarea. Con esto ya se obtiene una primera evaluación.
- **Afinar el diagnóstico (opcional):** el resto de preguntas, las herramientas que se usan y las restricciones (confidencialidad y posibilidad de cambiar el procedimiento).
- **Tiempo en pasos que no aportan valor (opcional):** solo aparecen las preguntas de las pérdidas que el diagnóstico detecta, como copiar datos, buscar información o reclamar datos, más «Otros».
- **Coste, corrección de errores y calendario (opcional):** coste por hora, tiempo dedicado a corregir errores, días laborables, meses activos y duración de la jornada.

Si no se conoce el tiempo, se puede **continuar sin datos de tiempo** y obtener un diagnóstico cualitativo. Las preguntas sin responder no bloquean nada: el resultado será provisional.

### Paso 3 · Diagnóstico

- **Recomendación principal**, con su explicación.
- **Tarjetas de resumen:** horas al año, coste anual si se ha indicado, horas que se ahorrarían y confianza del diagnóstico.
- **Matriz** de diseño del proceso frente a viabilidad técnica, con la tarea situada.
- **Puntos críticos:** cada ineficiencia con su evidencia, consecuencia, causa probable, qué podría hacerse y nivel de confianza.
- **Viabilidad técnica y factores críticos.**
- **Información que falta.**

Si la tarea podría no ser necesaria, el primer mensaje que aparece es: «Antes de nada, comprueba si esta tarea es necesaria».

### Paso 4 · Qué conviene hacer

- **Seis estrategias** (mantener, eliminar, simplificar, estandarizar, automatizar e incorporar IA), cada una con su estado y sus motivos, y la **combinación propuesta** en orden.
- **Qué tipo de solución encaja:** orientación sobre el tipo de intervención, sin nombrar productos.
- **Cuánto tiempo ahorrarías:** comparación de optimizar, automatizar y ambas cosas en tres escenarios editables, con el margen de tiempo que se podría dedicar a mejorar la tarea y recuperarlo.
- **Índice de potencial de automatización**, en un desplegable.

### Paso 5 · Plan

- **Acciones ordenadas** en mejoras rápidas, mejoras estructurales y automatizaciones. Cada una indica por qué se propone, su prioridad, de qué depende y un indicador para medirla.
- **Supuestos y limitaciones.**
- **Exportación:** informe para imprimir o guardar en PDF, archivo JSON y resumen copiable.

---

## 4. El marco D-MAP

**D-MAP (Diagnóstico y Mejora Aplicada de Procesos)** es un marco de análisis propio, desarrollado para «Automatizar u optimizar», que combina principios de Lean, Six Sigma y análisis de riesgos para evaluar y mejorar procesos antes de automatizarlos.

**No es una metodología certificada.** Traduce ideas de herramientas reconocidas de gestión y mejora de procesos a preguntas y reglas que cualquier persona puede entender.

### En qué se inspira y qué aplica esta versión

| Herramienta | Idea que aporta | Cómo se aplica en la versión actual |
|---|---|---|
| **Lean** | Identificar actividades que no aportan valor | Detección de 9 tipos de desperdicio y cálculo del tiempo que se va en ellos |
| **Six Sigma** | Analizar errores y variabilidad | Preguntas sobre errores, excepciones, pasos variables y estructura de los datos |
| **DMAIC** | Definir, Medir, Analizar, Mejorar, Controlar | Orden de las pantallas: describir (definir), datos de tiempo (medir), diagnóstico (analizar), estrategias y plan (mejorar), indicadores de cada acción (controlar) |
| **BPM** | Gestionar el proceso de principio a fin | Diagnóstico del diseño del proceso, separado de su viabilidad técnica |
| **5 porqués** | Buscar la causa raíz | Cada punto crítico muestra una *causa probable*, presentada como hipótesis, no como causa demostrada |
| **PDCA** | Mejora continua | Indicadores para medir antes de fijar objetivos y volver a evaluar |
| **SIPOC, BPMN, Pareto, AMFE, SMART** | Delimitar el proceso, representarlo, priorizar con datos, evaluar riesgos de fallo, fijar objetivos | Previstos para fases posteriores. En esta versión, el riesgo de cada alternativa es una valoración orientativa y el plan propone indicadores, no objetivos SMART |

### Las ideas centrales

1. **Primero, la necesidad.** Si no está claro que alguien use el resultado, lo primero es comprobarlo: dejar de hacer la tarea recupera el 100 % del tiempo.
2. **Dos preguntas distintas.** «¿Se puede automatizar?» (viabilidad técnica) y «¿Está bien diseñado el proceso?» (calidad del diseño) se evalúan por separado. Una tarea puede ser muy automatizable y estar mal diseñada, y entonces automatizarla primero sería un error.
3. **El orden de la mejora.** Eliminar, después simplificar y estandarizar, y al final automatizar.
4. **El tiempo como medida.** El beneficio se expresa en horas de trabajo. El valor en euros solo aparece si se indica el coste por hora, y siempre con la advertencia de que liberar horas no equivale necesariamente a ahorrar presupuesto.

---

## 5. Cómo funciona por dentro

### 5.1 Analizador de la descripción (sin IA)

Lee el texto frase a frase y busca patrones en castellano, catalán e inglés, sin distinguir mayúsculas ni tildes:

- **Frecuencia:** «cada lunes», «mensualmente», «every week», «cada dia»…
- **Tiempo total:** el primer tiempo que aparece, por ejemplo «2 horas» o «30 minutos».
- **Herramientas:** Excel, correo, documentos, formularios, ERP, CRM, aplicaciones internas…
- **Respuestas a las preguntas:** «copio» → se copian datos; «espero» o «reclamo» → hay esperas; «papel» o «escaneo» → datos solo en parte digitales; «aprobación» → necesita aprobación, etc.
- **Minutos sin valor:** un segundo tiempo que va en la misma frase que un verbo de pérdida se propone como pérdida de ese tipo. Así, «…de los que 30 minutos se van en copiar datos» propone 30 minutos en duplicación. El primer tiempo nunca se toma como pérdida.
- **Negaciones:** frases como «no copio datos» no generan propuestas.
- **Reanálisis:** al analizar otra descripción se retiran las propuestas anteriores que ya no se apoyan en el texto. Lo elegido o escrito a mano se conserva.

### 5.2 Horas de trabajo

Valores de partida, editables en «Calendario»: **220 días laborables** al año, **44 semanas activas** (220 ÷ 5), **12 meses** y una **jornada de 7,5 horas**.

| Frecuencia | Ejecuciones al año (E) |
|---|---|
| Varias veces al día | n × 220 |
| Diariamente | 220 |
| Varias veces por semana | n × 44 |
| Semanalmente | 44 |
| Mensualmente | 12 |
| Trimestralmente | 4 |
| Anualmente | 1 |
| Ocasionalmente | n veces al año |
| Personalizada | n por día, semana, mes o año |

```
Horas de ejecución = minutos × E × personas / 60        (tiempo por persona)
                   = minutos totales × E / 60            (tiempo total del equipo)
Horas de corrección = minutos × E × personas / 60        (por ejecución y persona)
                    = minutos × 44 / 60  o  × 12 / 60    (total del equipo por semana o por mes)
Horas al año = horas de ejecución + horas de corrección
```

El tiempo de espera, si se indica, no se cuenta como trabajo: alarga el plazo, pero no ocupa tiempo activo.

### 5.3 Diagnóstico

**Filtro previo.** Si no está claro que alguien use el resultado, aparece primero la recomendación de comprobar si la tarea es necesaria.

**Eje A · Viabilidad técnica.** Factores desfavorables: pasos que cambian a menudo, datos sin estructura fija, decisiones de criterio, muchas excepciones y datos solo en parte digitales. Los datos en papel son un factor **bloqueante**.

- Baja: hay un factor bloqueante o 2 o más factores.
- Media: 1 factor.
- Alta: ninguno.

**Eje B · Diseño del proceso.** Cada respuesta puede generar una señal **fuerte** (por ejemplo, datos duplicados, no haber una fuente oficial, buena parte del tiempo en esperas, retrabajo o un proceso no estandarizado) o **leve** (duplicidad ocasional, transformar formatos, algunas esperas, errores frecuentes, muchas excepciones, aprobación en todos los casos, muchas herramientas o la principal dificultad declarada).

- Deficiente: 2 o más señales fuertes.
- Mejorable: 1 fuerte, o 2 o más leves.
- Sólido: el resto.

**Matriz de recomendación**

| Proceso \ Viabilidad | Alta | Media | Baja |
|---|---|---|---|
| **Sólido** | Conviene automatizar | Automatizar en parte | Apoyar, no automatizar |
| **Mejorable** | Optimizar, luego automatizar | Optimizar, luego automatizar | Simplificar antes de automatizar |
| **Deficiente** | Optimizar, luego automatizar | Simplificar antes de automatizar | Rediseñar el proceso |

**Tareas poco frecuentes.** Si la tarea se hace menos de una vez al mes, no compensa una automatización costosa. La recomendación pasa a «No parece rentable intervenir en este momento» si no hay problemas, o a «La mejora organizativa ofrece más que la automatización» si los hay.

**Resultado provisional.** Si quedan preguntas sin responder, se calcula el diagnóstico en el **mejor caso** (respuestas pendientes en su opción más favorable) y en el **peor caso** (en la más desfavorable):

- Si la recomendación coincide en los dos, se muestra como provisional pero firme.
- Si no coincide, se marca como **pendiente**, con el rango posible y la lista de preguntas que faltan. Las estrategias que dependen de esas preguntas aparecen como «Pendiente».

**Factores críticos.** Si hay información confidencial o restricciones para cambiar el procedimiento, se avisa de revisarlas antes de elegir una solución. Si el resultado necesita aprobación siempre, se recuerda que cualquier solución debe mantener una revisión humana. Ninguno de los dos cambia la recomendación.

**Confianza del diagnóstico**

- Baja: faltan los datos de tiempo, hay 3 o más respuestas «No lo sé», o la recomendación depende de preguntas pendientes.
- Media: hay alguna respuesta «No lo sé», datos deducidos de la descripción o preguntas pendientes que no cambian el resultado.
- Alta: todo son respuestas directas.

### 5.4 Los nueve desperdicios

Sobreprocesamiento, esperas, retrabajo, duplicación, transferencias, búsquedas, exceso de controles, conocimiento no documentado y carga cognitiva. Para cada uno se muestran:

- la evidencia: qué respuestas lo detectan;
- la consecuencia;
- la causa probable;
- qué podría hacerse;
- la confianza: alta si es una respuesta directa, media si se ha deducido de la descripción y baja si se basa en un «No lo sé».

### 5.5 Las seis estrategias

| Estrategia | Cuándo se recomienda o se considera aplicable |
|---|---|
| Mantener | La tarea funciona y no hay problemas, o es poco frecuente |
| Eliminar | No está claro que el resultado se use, o hay datos duplicados o retrabajo |
| Simplificar | Hay esperas, demasiadas aprobaciones o comprobaciones, o muchas herramientas |
| Estandarizar | No hay fuente oficial, se transforman formatos, hay errores o casos especiales, o el proceso no está estandarizado |
| Automatizar | La viabilidad es alta o media y la tarea se hace al menos una vez al mes |
| Incorporar IA | Hay que interpretar información o los datos llegan sin estructura; siempre con revisión humana |

### 5.6 Qué tipo de solución encaja

Solo aparece si «Automatizar» o «Incorporar IA» son recomendadas o aplicables, o si los datos están en papel. Cada tipo muestra las respuestas que lo activan.

| Tipo | Se propone cuando… |
|---|---|
| Conectar las aplicaciones | Se copian datos y las herramientas permiten exportar o conectar |
| Plantillas de exportación e importación | Se copian datos y las herramientas no se pueden conectar |
| Flujo automático con reglas | Los pasos son estables, las reglas claras y hay pocas excepciones |
| Formularios con validaciones en origen | Los datos llegan sin estructura fija, hay errores frecuentes o retrabajo |
| Hojas de cálculo con fórmulas o macros | Se trabaja con Excel y con pocas aplicaciones |
| Automatización de pantalla (último recurso) | Las reglas son claras, pero no hay forma de conectar las herramientas |
| Digitalizar primero | Hay papel o datos solo en parte digitales |
| IA de apoyo, con revisión humana | Hay que interpretar o los datos no tienen estructura |

No se nombran productos ni se estima el esfuerzo de implantación.

### 5.7 Ahorro de tiempo

- **Reducción si automatizas:** hipótesis editables de **40 %, 70 % y 90 %** para los escenarios conservador, intermedio y optimista.
- **Reducción si optimizas:** no tiene valor genérico. Se **calcula con tus datos**:

  ```
  (horas al año en pasos sin valor + horas de corrección de errores) / horas al año totales
  ```

  El supuesto, que se muestra junto al resultado, es que optimizar elimina ese tiempo por completo. Si escribes tu propio porcentaje, prevalece; si lo borras, vuelve el calculado.
- **Optimizar y automatizar a la vez:** la automatización se aplica sobre lo que queda después de optimizar, sin sumar los porcentajes:

  ```
  1 − (1 − optimizar) × (1 − automatizar)
  ```

- **Mantenimiento de la automatización** (horas al año, opcional): se descuenta del ahorro de las alternativas que automatizan.
- **Margen de inversión:** horas que se podrían dedicar a mejorar la tarea y recuperarlas en 1, 3 y 5 años.

  ```
  horas ahorradas al año × número de años
  ```

- **Valor del tiempo ahorrado:** solo aparece si se indica el coste por hora, y siempre con la advertencia de que no equivale necesariamente a un ahorro presupuestario.
- **Comparación incompleta:** si falta el dato de alguna alternativa, se avisa de que la comparación está incompleta, para no favorecer la automatización solo porque tiene valores por defecto.

### 5.8 Índice de potencial de automatización (0–100)

Es un indicador orientativo de idoneidad técnica, no de rentabilidad. Sus ponderaciones son heurísticas iniciales, no un modelo validado estadísticamente.

| Criterio | Peso | Según |
|---|---|---|
| Repetitividad | 20 % | ¿Sigue siempre los mismos pasos? |
| Claridad de reglas | 20 % | ¿Hay que tomar decisiones? |
| Frecuencia | 15 % | Semanal o más: 1 · mensual o más: 0,5 · menos de una vez al mes: 0 |
| Disponibilidad de datos | 15 % | ¿Los datos están en formato digital? |
| Estabilidad de los datos de entrada | 10 % | ¿Llegan siempre con la misma estructura? |
| Viabilidad de integración | 10 % | ¿Las herramientas permiten exportar o conectar? |
| Pocas excepciones | 10 % | ¿Aparecen casos fuera de lo habitual? |

Los criterios sin dato se excluyen del cálculo, y la herramienta lo indica.

### 5.9 Plan de mejora

Las acciones se ordenan así:

1. Responder las preguntas pendientes, si las hay.
2. Comprobar si la tarea es necesaria.
3. Revisar las restricciones.
4. Eliminar.
5. Simplificar y estandarizar.
6. Automatizar.

Cada acción se clasifica como mejora rápida, estructural o automatización, y lleva su justificación, su prioridad, sus dependencias y un indicador. La herramienta no asigna responsables ni fechas.

---

## 6. Privacidad

- Todos los cálculos se hacen en el navegador. **No se guarda ni se envía nada de lo que se escribe**: no hay analítica, ni formularios que envíen datos, ni almacenamiento local.
- El estado se pierde al cerrar la página.
- La página solo hace una petición externa: carga las tipografías desde Google Fonts. Esa petición no incluye nada de lo que se escribe.

---

## 7. Idiomas, diseño y accesibilidad

- **Idiomas:** catalán (idioma principal, el que se abre por defecto), castellano e inglés, con un selector en el menú. Al cambiar de idioma no se pierde nada de lo introducido. Todos los textos están en el objeto `textos` (`ca`, `es`, `en`). Los metadatos para compartir en redes están en catalán.
- **Diseño:** paleta basada en los colores corporativos de AQU Catalunya:

  | Tipo | Colores |
  |---|---|
  | Principales | #00364a, #2dccb9, #8dca4c, #d0e24d |
  | Complementarios | #ccd7db, #d9f5ef, #ecf3b8 |

  El rojo #B4442F se reserva para errores y alertas. Las tipografías son Rubik y Space Grotesk.
- **Accesibilidad:**
  - Todos los textos cumplen el contraste WCAG AA.
  - Se puede usar con teclado, con el foco siempre visible.
  - Todos los campos tienen etiqueta.
  - Respeta la preferencia de movimiento reducido.
  - Está diseñada primero para móvil.

---

## 8. Estructura técnica

| Archivo | Contenido |
|---|---|
| `automatitzar-o-optimitzar.html` | Toda la aplicación: HTML, CSS y JavaScript, sin dependencias de código |
| `pruebas.html` | Pruebas automáticas de las funciones de cálculo |
| `README.md` | Este documento |

Dentro del HTML, el código está separado en bloques comentados:

| Bloque | Función |
|---|---|
| `CONFIG` | Valores por defecto editables: calendario, escenarios, ponderaciones, límites, contacto e idioma inicial |
| `ESTIMACION` | Modelo de estimación del esfuerzo de implantación, construido pero desactivado (`publicar: false`) |
| `PREGUNTAS` | Preguntas, opciones, condiciones de aparición, preguntas esenciales y respuestas extremas |
| `DESPERDICIOS`, `SENALES`, `REGLAS` | Tipos de desperdicio, señales que genera cada respuesta, umbrales, matriz y riesgo |
| `ANALIZADOR` | Patrones del analizador de la descripción |
| `TIPOS_INTERVENCION` | Reglas de la orientación sobre el tipo de solución |
| `calculo` | Funciones puras, sin acceso a la página: horas, ahorro, diagnóstico, estrategias, índice, formato de cifras |
| `textos` | Todos los textos de la interfaz en los tres idiomas |
| Interfaz | Pantallas, eventos, gráficos, exportación e informe de impresión |

Para probarla basta con abrir `automatitzar-o-optimitzar.html` en un navegador.

---

## 9. Pruebas

`pruebas.html` contiene **65 pruebas** con valores esperados calculados a mano. Cubren:

- los 12 casos de la especificación original;
- las 12 pruebas obligatorias de D-MAP (frecuencias, horas, doble contabilización, ROI, recuperación de la inversión, beneficios negativos, datos incompletos, restricciones…);
- los casos de uso A a G;
- el resultado provisional;
- el índice;
- la reducción por optimizar;
- la orientación sobre el tipo de solución;
- el analizador en los tres idiomas;
- que el catalán y el inglés tengan los mismos textos que el castellano.

Para ejecutarlas hay que servir la carpeta con un servidor local, porque el navegador bloquea el acceso entre páginas abiertas como archivo. Por ejemplo:

```bash
python -m http.server 8765
```

y abrir `http://localhost:8765/pruebas.html`.

---

## 10. Personalización

Todo lo editable está en `CONFIG`, al principio del script:

| Parámetro | Para qué sirve |
|---|---|
| `calendario` | Días laborables, meses activos y horas por jornada |
| `reduccionAutomatizar` | Hipótesis de los tres escenarios de automatización |
| `indice.pesos` | Ponderaciones del índice de potencial de automatización |
| `contacto` | Enlace `https://` o `mailto:`. Si tiene valor, aparece al final un bloque con el botón «Solicitar un análisis»; con `null` (valor actual), el bloque no se muestra |
| `idiomaInicial` | Idioma con el que se abre la página (actualmente `ca`, catalán) |
| `idiomas` | Idiomas disponibles y su orden en el selector (actualmente catalán, castellano e inglés) |

---

## 11. Limitaciones y fases posteriores

**Limitaciones de la versión actual**

- El analizador de la descripción usa reglas, no IA. Acierta con descripciones habituales, pero puede fallar con formas de expresarse que no tiene previstas. Por eso todo lo que propone se puede revisar y cambiar.
- Las causas que muestra son probables, no demostradas.
- Los escenarios son supuestos para comparar, no predicciones.
- El ahorro se calcula en horas de trabajo y no incluye costes de licencias, desarrollo ni servicios externos.
- La **estimación del esfuerzo de implantación** está construida pero desactivada hasta calibrarla con proyectos reales.

**Previsto para fases posteriores**

- Mapa visual del proceso y desglose por actividades.
- AMFE simplificado, priorización de Pareto y objetivos SMART.
- Interpretación de la descripción con IA, con consentimiento expreso. Requeriría un servidor que proteja la clave de acceso y cambiar el aviso de privacidad.
- Compartir resultados mediante un enlace, si se dispone de una infraestructura segura.

---

## 12. Autoría y créditos

- **Concepto, marco D-MAP y especificaciones:** [nombre de la autora o del autor — pendiente de completar]
- **Desarrollo:** implementado con la ayuda de Claude (Anthropic), a partir de las especificaciones anteriores.
- **Licencia:** [pendiente de definir]
