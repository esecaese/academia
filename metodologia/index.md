# Implementación de la inteligencia artificial en la liquidación de aranceles consulares

**Pregunta de investigación:** ¿Cómo se implementa la inteligencia artificial en la liquidación de aranceles consulares?

---

## Objetivo general

Evaluar la implementación de la inteligencia artificial en la liquidación de aranceles consulares, mediante la integración de un asistente virtual con el portal de apostilla y la automatización de la normativa vigente ([Ley N° 1.030/97](https://www.bacn.gov.py/leyes-paraguayas/2245/ley-n-1030-que-modifica-y-amplia-la-ley-n-133-93-y-deroga-el-decreto-ley-n-46-72-actualizando-las-tasas-por-servicios-de-legalizacion) y [Ley N° 4.033/10](https://www.bacn.gov.py/leyes-paraguayas/513/ley-n-4033-del-arancel-consular)) para optimizar la gestión consular, garantizar la exactitud en las tasas y facilitar el acceso descentralizado al servicio.

## Objetivos específicos

1. Identificar los procesos normativos para la liquidación de los aranceles consulares según la [Ley N° 1.030/97](https://www.bacn.gov.py/leyes-paraguayas/2245/ley-n-1030-que-modifica-y-amplia-la-ley-n-133-93-y-deroga-el-decreto-ley-n-46-72-actualizando-las-tasas-por-servicios-de-legalizacion) (tasas de legalización) y la [Ley N° 4.033/10](https://www.bacn.gov.py/leyes-paraguayas/513/ley-n-4033-del-arancel-consular) (aranceles consulares en el exterior).
2. Sistematizar los criterios de automatización de la normativa arancelaria en la plataforma.
3. Proponer un modelo de gestión consular "Cero Papel" que reduzca los costos de traslado y tiempos de espera para los ciudadanos ubicados en zonas remotas o en el extranjero.

| Verbo | Que | Como | Para que |
| :---- | :---- | :---- | :---- |
| Evaluar | La implementación de la inteligencia artificial en la liquidación de aranceles consulares. | Mediante la integración de un asistente virtual con el portal de apostilla y la automatización de la normativa vigente | Para optimizar la gestión consular, garantizar la exactitud en las tasas y facilitar el acceso descentralizado al servicio |
| Identificar | Los procesos normativos para la liquidación de los aranceles consulares según la Ley N° 1.030/97 y la Ley N° 4.033/10. |  |  |
| Sistematizar | Los criterios de automatización de la normativa arancelaria en la plataforma. |  |  |
| Proponer | Un modelo de gestión consular "Cero Papel" que reduzca los costos de traslado y tiempos de espera para los ciudadanos ubicados en zonas remotas o en el extranjero. |  |  |

## Justificación

La investigación ayudará a mejorar la prestación de servicios en el Ministerio de Relaciones Exteriores, atendiendo a que se detecta una fuerte dependencia de la presencialidad que perjudica al ciudadano. La actual concentración de trámites de apostilla en la capital impone gastos de viaje y demoras excesivas a los connacionales. Para ilustrarlo, considérese el caso de un ciudadano residente en **Encarnación** (a 350 km de Asunción) que necesita apostillar un título universitario. Debe:
- Trasladarse a la capital (pasaje ida y vuelta: 120.000 guaraníes),
- Hospedarse si no puede hacer el trámite en el día (80.000 guaraníes),
- Perder dos días laborales (costo de oportunidad estimado: 200.000 guaraníes),
- Pagar la tasa de apostilla (2,23 jornales × 100.000 guaraníes = 223.000 guaraníes).
El costo total supera los **600.000 guaraníes** sin considerar el desgaste físico. Con el modelo “Cero Papel” + IA, el mismo trámite costaría solo la tasa (223.000 guaraníes) y se realizaría en 10 minutos desde su casa. Como señala el Banco Interamericano de Desarrollo (2020), la digitalización de los trámites públicos puede reducir hasta en un 80% los costos de transacción para los ciudadanos.

Asimismo, la liquidación de aranceles en el exterior sigue procesos manuales basados en dos cuerpos legales diferentes, lo que añade complejidad y riesgo de error. Los resultados del estudio benefician a los paraguayos que viven lejos de la capital, a las comunidades en el exterior y a la propia institución en su meta de innovación. Al descentralizar la gestión consular, se eliminan barreras económicas reales como transporte y hospedaje. La Organización para la Cooperación y el Desarrollo Económicos (OCDE, 2019) destaca que el gobierno digital no solo mejora la eficiencia, sino que también promueve la equidad territorial. Esta investigación propone mecanismos de inteligencia artificial conversacional conectados al portal de apostilla, facilitando un flujo "Cero Papel" que garantice precisión en los cobros y mayor rapidez, cumpliendo efectivamente con la asistencia consular paraguaya.

---

# Marco Teórico

## 1. Inteligencia artificial aplicada a la gestión pública

La inteligencia artificial (IA) se define como la capacidad de las máquinas para realizar tareas que normalmente requieren inteligencia humana, como el razonamiento, el aprendizaje y la toma de decisiones (Russell & Norvig, 2021). En el ámbito público, la IA se ha clasificado en tres niveles: asistencia (apoyo a tareas rutinarias), aumento (mejora de la capacidad humana) y automatización (sustitución de procesos enteros) (Misuraca & Viscusi, 2015). Los modelos conversacionales o _chatbots_ son una de las aplicaciones más difundidas, ya que permiten interactuar con los ciudadanos en lenguaje natural, resolver consultas y ejecutar transacciones simples (Androutsopoulou et al., 2019).

Para el caso de la liquidación de aranceles, se requiere un **sistema experto**, un tipo de IA que utiliza reglas de negocio derivadas de la legislación para calcular montos de forma automática (Giarratano & Riley, 2005). Estos sistemas son particularmente útiles cuando las normas son estables y pueden representarse mediante condiciones lógicas (si-entonces). La Ley N° 4.033/10 y la Ley N° 1.030/97 cumplen con ese requisito, ya que definen aranceles fijos o fórmulas basadas en jornales mínimos.

## 2. Gobierno electrónico y transformación digital del Estado

El gobierno electrónico (e-gobierno) se refiere al uso de tecnologías de la información y comunicación (TIC) para mejorar la prestación de servicios públicos, fortalecer la transparencia y fomentar la participación ciudadana (UNESCO, 2016). Según el modelo de madurez de Layne y Lee (2001), los gobiernos evolucionan desde la presencia informativa (páginas web estáticas) hasta la integración horizontal y vertical (sistemas interoperables) y, finalmente, la transformación política. Paraguay ha avanzado en los primeros niveles, pero aún existen servicios concentrados en papel.

La transformación digital del Estado va más allá de digitalizar formularios; implica repensar los procesos administrativos desde una lógica centrada en el ciudadano (Janowski, 2015). En ese sentido, la liquidación automática de aranceles consulares es un caso típico de **automatización de procesos** (RPA, por sus siglas en inglés), donde tareas repetitivas basadas en reglas son ejecutadas por software (van der Aalst et al., 2018). Esto libera tiempo para que los funcionarios se dediquen a casos complejos y mejora la experiencia del usuario.

## 3. Experiencias comparadas en América Latina

La implementación de chatbots y automatización en el sector público no es ajena a la región. **Uruguay**, a través de su **Agencia de Gobierno Electrónico y Sociedad de la Información (AGESIC)** , ha desarrollado el asistente virtual “Iris” para consultas sobre trámites ciudadanos, reduciendo en un 40% el tiempo de respuesta (AGESIC, 2022). **Chile**, con su **Portal del Estado**, ha automatizado el cálculo de tasas notariales y aranceles judiciales, logrando que el 70% de los pagos se realicen en línea (Gobierno de Chile, 2021). **Colombia**, mediante la estrategia **“Cero Papel”** del Ministerio de Tecnologías de la Información (MINTIC), ha eliminado la presentación física de documentos en más de 150 trámites, con ahorros estimados en 15 millones de dólares anuales (MINTIC, 2023). Estos casos demuestran que la liquidación automática de aranceles consulares es técnica y políticamente viable en Paraguay, siempre que se adapte a su marco normativo y se implemente de manera gradual.

## 4. Modelo “Cero Papel” y simplificación administrativa

El concepto “Cero Papel” (o _paperless office_) se popularizó en la década de 1970, pero solo con la madurez de las TIC se ha vuelto alcanzable (Sellen & Harper, 2002). Implica la eliminación progresiva del soporte físico en los procesos internos y en la relación con los ciudadanos. Sus ventajas incluyen reducción de costos de almacenamiento, menor impacto ambiental y agilización de los tiempos de respuesta. En el sector público, el “Cero Papel” es un componente central de las políticas de simplificación administrativa (CEPAL, 2018).

Para la gestión consular, un modelo “Cero Papel” requiere: (a) digitalización de documentos ingresados por el ciudadano (con firma electrónica o autenticación), (b) expedientes electrónicos que se tramiten en línea, (c) sistemas de pago electrónico integrados y (d) resguardos de seguridad y conservación digital. La implementación de este modelo, combinado con IA, permite no solo prescindir del papel, sino también automatizar la verificación de requisitos y el cálculo de tasas.

## 5. Automatización de procesos en el sector público

La automatización de procesos mediante software (RPA) ha sido ampliamente adoptada por gobiernos para tareas como conciliaciones tributarias, emisión de certificados y gestión de recursos humanos (Wanner et al., 2019). Sin embargo, la automatización tradicional se limita a imitar la interacción humana con interfaces de usuario. Un nivel superior es la **automatización inteligente**, que incorpora IA para manejar datos no estructurados, tomar decisiones condicionales y aprender de los resultados (Willcocks et al., 2017).

En el caso de la liquidación de aranceles consulares, la automatización inteligente puede aplicarse para:
- Interpretar la consulta del ciudadano (procesamiento de lenguaje natural).
- Seleccionar el código arancelario correspondiente.
- Calcular el monto según las reglas de la ley (incluyendo actualización del jornal mínimo).
- Emitir un comprobante de pago electrónico.

La supervisión humana sigue siendo necesaria para casos excepcionales (exenciones no previstas, errores en el reconocimiento de documentos), lo que configura un sistema de **aumento** más que de sustitución total (Misuraca & Viscusi, 2015).

---

# Metodología de la investigación

## Tipo de investigación

La investigación es de tipo **aplicada** (o práctica), ya que busca resolver un problema concreto de la administración pública: la liquidación manual y centralizada de aranceles consulares. Su carácter es **descriptivo-propositivo**, porque describe el marco normativo y los procedimientos actuales, y luego propone un modelo alternativo basado en inteligencia artificial (Hernández Sampieri et al., 2018).

## Enfoque

Se adopta un **enfoque mixto** (cualitativo y cuantitativo). La parte cualitativa consiste en el análisis documental de leyes, reglamentos y literatura académica sobre gobierno digital e IA. La parte cuantitativa se manifiesta en la estimación de la reducción de tiempos y costos que podría generar el modelo propuesto, con base en datos oficiales de trámites (cantidad de apostillas, distancia geográfica de los usuarios, etc.).

## Diseño de la investigación

El diseño es **documental y proyectivo** (Hurtado de Barrera, 2010). Se realiza una revisión sistemática de fuentes primarias (leyes paraguayas, decretos, resoluciones) y secundarias (artículos científicos, informes de organismos internacionales). Con base en esa revisión, se formula un modelo conceptual de asistente virtual con IA, incluyendo reglas de negocio, flujo de trabajo y consideraciones de implementación gradual.

## Fuentes de información

- **Primarias**: Textos completos de la Ley N° 1.030/97, Ley N° 4.033/10, Ley N° 5.254/2014, Ley N° 7.196/2023 y Ley N° 1.635/2001, disponibles en la Biblioteca y Archivo Central del Congreso de la Nación. También se utiliza el portal oficial del Ministerio de Relaciones Exteriores y comunicaciones de la Dirección de Legalizaciones.
- **Secundarias**: Artículos académicos indexados en Scopus y Google Scholar (2015-2024) sobre inteligencia artificial en gobierno, automatización de procesos, y modelo Cero Papel; informes del BID, OCDE, CEPAL y Naciones Unidas sobre gobierno digital.

## Técnicas de análisis

- **Análisis de contenido normativo**: Se extraen las variables relevantes de cada ley (códigos arancelarios, montos, jornales mínimos, exenciones) para convertirlas en reglas de negocio.
- **Ingeniería de requisitos**: Se identifican las funcionalidades que debe tener el asistente virtual (reconocimiento de intenciones, cálculo, generación de comprobante, supervisión humana).
- **Análisis de brechas** (_gap analysis_): Se compara la situación actual (presencial, manual) con la situación objetivo (digital, automatizada) para determinar los cambios necesarios en tecnología, normativa y capacitación.

---

# CAPÍTULO I. Procesos normativos y evolución de la función consular

## 1.1 Organización institucional y antecedentes de la gestión administrativa

En las últimas décadas, la estructura del Ministerio de Relaciones Exteriores de Paraguay ha sido muy centralizada. La [Ley N° 1.635/2001](https://www.bacn.gov.py/leyes-paraguayas/1715/leyes-paraguayas) creó este ministerio y definió sus funciones, estableciendo que la mayoría de los trámites consulares dependen de la Dirección General de Asuntos Consulares. Dentro de esta dirección, la Dirección de Legalizaciones es la encargada de verificar y apostillar documentos. Sin embargo, esta oficina funciona exclusivamente en Asunción. Cualquier ciudadano que necesite legalizar un documento debe trasladarse a la capital, lo que implica gastos de viaje, tiempo perdido y, en muchos casos, la imposibilidad de realizar el trámite (Roa, 2023). En la práctica, el servicio sigue siendo totalmente presencial, a pesar de que existen herramientas tecnológicas que permitirían hacerlo de forma remota.

Históricamente, la gestión consular en Paraguay ha dependido casi por completo del papel. Las tasas por legalización se rigen por la [Ley N° 1.030/97](https://www.bacn.gov.py/leyes-paraguayas/2245/ley-n-1030-que-modifica-y-amplia-la-ley-n-133-93-y-deroga-el-decreto-ley-n-46-72-actualizando-las-tasas-por-servicios-de-legalizacion), que actualizó el régimen anterior (Decreto-Ley N° 46/72) estableciendo valores referenciados al jornal mínimo diario. Por otro lado, la [Ley N° 4.033/10](https://www.bacn.gov.py/leyes-paraguayas/513/ley-n-4033-del-arancel-consular) unificó el arancel consular para actuaciones en el exterior, enumerando 84 conceptos arancelarios en su artículo 11, lo que demuestra la complejidad del sistema. La [Ley N° 5.254/2014](https://www.bacn.gov.py/leyes-paraguayas/2997/ley-n-5254-modifica-los-art-culos-3-6-12-y-14-de-la-ley-n-4-033-10-del-arancel-consular-br) autorizó al Ministerio a percibir derechos consulares “a través de medios informáticos” (art. 6°). Sin embargo, los avances se han limitado a digitalizar planillas, sin automatizar el cálculo con reglas lógicas integrando ambas leyes.

## 1.2 Rol de la Dirección de Informática en la modernización institucional

Dentro de la estructura del Ministerio, la Dirección de Informática es la unidad responsable de la administración de los recursos tecnológicos, garantizando soporte técnico, mantenimiento de sistemas y seguridad de la infraestructura informática. En el marco de la modernización del Estado, esta Dirección ha sentado las bases para la prestación de servicios digitales, incluyendo soporte a plataformas de trámites en línea y la conexión de la oficina central con consulados en el exterior. La [Ley N° 5.254/2014](https://www.bacn.gov.py/leyes-paraguayas/2997/ley-n-5254-modifica-los-art-culos-3-6-12-y-14-de-la-ley-n-4-033-10-del-arancel-consular-br) posicionó a la Dirección de Informática como un actor estratégico para avanzar hacia la automatización real, incluyendo la liquidación automática de tasas conforme a la Ley N° 1.030/97. Así, la implementación de un asistente con IA representa una oportunidad para que esta Dirección lidere un salto cualitativo: pasar del soporte técnico al desarrollo de soluciones inteligentes que automaticen la lógica normativa de ambas leyes, calculando montos de forma precisa y permitiendo un acceso descentralizado.

---

# CAPÍTULO II. Marco jurídico de la liquidación de aranceles

## 2.1 Tasas por servicios de legalización y apostilla (Ley N° 1.030/97)

La Ley N° 1.030/97 actualizó las tasas de la Dirección de Legalizaciones estableciendo un régimen referenciado al **jornal mínimo diario**. Sus características son:
- Tasas en guaraníes calculadas como: *cantidad de jornales* × *valor del jornal mínimo vigente*.
- Actualización implícita cada vez que el Poder Ejecutivo modifica el salario mínimo.
- Aplicación exclusiva en la sede central de Asunción.

Para efectos de automatización, se requiere programar la lógica que consulte el valor vigente del jornal mínimo y aplique la cantidad de jornales según el tipo de documento (apostilla, legalización de copia, etc.).

## 2.2 Aranceles por actuaciones consulares en el exterior (Ley N° 4.033/10 y modificaciones)

La Ley N° 4.033/10 establece los derechos arancelarios en **dólares estadounidenses** para consulados. Su artículo 11 enumera originalmente 84 códigos, agrupados en rubros como estado civil, pasaportes, poderes y legalizaciones. La [Ley N° 5.254/2014](https://www.bacn.gov.py/leyes-paraguayas/2997/ley-n-5254-modifica-los-art-culos-3-6-12-y-14-de-la-ley-n-4-033-10-del-arancel-consular-br) introdujo modificaciones y, más recientemente, la [Ley N° 7.196/2023](https://www.bacn.gov.py/leyes-paraguayas/12025/ley-n-7196-que-deroga-varios-art-culos-de-la-ley-n-4033-2010-del-arancel-consular) derogó más de 50 aranceles de carácter comercial (navegación, aeronavegación, importaciones). Por lo tanto, el arancel consular vigente se concentra en servicios a ciudadanos y actos jurídicos esenciales. La liquidación automática requiere identificar el tipo de actuación, aplicar la tarifa en dólares, verificar exenciones y generar comprobante.

## 2.3 Comparación y necesidad de un modelo unificado

Ambas leyes presentan lógicas diferentes (guaraníes indexados a jornales vs. dólares fijos). Sin embargo, desde la perspectiva del ciudadano, el objetivo es el mismo: pagar el monto correcto por la legalización de un documento, ya sea en la capital o en un consulado. Un asistente virtual con IA debe: (a) preguntar si el trámite se realiza en Paraguay o en el exterior; (b) aplicar la ley correspondiente; (c) calcular el total (consultando el jornal mínimo en tiempo real); (d) emitir un comprobante digital.

---

# CAPÍTULO III. Fundamentos de inteligencia artificial

## 3.1 Aplicación de modelos conversacionales en la gestión pública

Los modelos conversacionales (chatbots) son programas que simulan una conversación humana mediante procesamiento de lenguaje natural (NLP). En el sector público, se han utilizado para responder preguntas frecuentes, guiar a los ciudadanos en la cumplimentación de formularios y realizar transacciones simples (Androutsopoulou et al., 2019). Estos sistemas pueden basarse en reglas (diálogos predefinidos) o en aprendizaje automático (redes neuronales entrenadas con grandes volúmenes de conversaciones). Para la liquidación de aranceles, un sistema híbrido es adecuado: reglas para el cálculo (porque la normativa es precisa) y NLP para interpretar las intenciones del usuario (“quiero apostillar un título”, “pasaporte de urgencia”).

La implementación de chatbots en gobiernos locales y nacionales ha demostrado reducir los tiempos de espera y descongestionar las líneas telefónicas (Margetts & Dorobantu, 2019). Por ejemplo, el chatbot “Clara” del gobierno de Bogotá resuelve más de 200.000 consultas mensuales sobre trámites. No obstante, se recomienda mantener un mecanismo de derivación a un funcionario humano para casos no previstos o de alta complejidad.

## 3.2 Aplicación de asistencia virtual para trámites ciudadanos

Un asistente virtual para trámites ciudadanos debe integrarse con los sistemas de gestión interna (como el portal de apostilla) y con pasarelas de pago electrónico. Sus funcionalidades mínimas son:
- **Reconocimiento de intenciones**: identifica qué tipo de servicio necesita el usuario (apostilla, pasaporte, poder, etc.).
- **Extracción de entidades**: captura datos relevantes (tipo de documento, urgencia, edad del solicitante para determinar exenciones).
- **Ejecución de reglas de negocio**: consulta la base de conocimiento (aranceles) y aplica la fórmula de cálculo.
- **Respuesta omnicanal**: puede operar vía web, WhatsApp o Telegram.

En el caso específico de Paraguay, el asistente deberá estar disponible en español y guaraní (al menos en su interfaz inicial). Además, debe cumplir con la [Ley N° 6.534/2020 de Protección de Datos Personales](https://www.bacn.gov.py/leyes-paraguayas/10031/ley-n-6534-de-proteccion-de-datos-personales) y ofrecer información clara sobre el monto a pagar antes de redirigir al portal de pagos.

---

# CAPÍTULO IV. Criterios de automatización arancelaria

## 4.1 Definición de reglas de negocio para la liquidación automática

Una regla de negocio es una declaración que define o restringe algún aspecto del negocio (Giarratano & Riley, 2005). Para nuestro caso, se derivan directamente de los artículos de la Ley N° 1.030/97 y la Ley N° 4.033/10. A continuación se presenta una tabla ampliada con las reglas más representativas:

| Ley | Regla de negocio (si-entonces) | Ejemplo de aplicación |
|------|-------------------------------|------------------------|
| 1.030/97 | Si **tipo_documento** es “apostilla_firma_privada” → **tasa = 2,23 × jornal_minimo** | Jornal=100.000 Gs. → 223.000 Gs. |
| 1.030/97 | Si **tipo_documento** es “legalizacion_copia” → **tasa = 1,50 × jornal_minimo** | → 150.000 Gs. |
| 1.030/97 | Si **tipo_documento** es “certificado_antecedentes” → **tasa = 1,00 × jornal_minimo** | → 100.000 Gs. |
| 1.030/97 | Si **tipo_documento** es “legalizacion_titulo” → **tasa = 1,80 × jornal_minimo** | → 180.000 Gs. |
| 4.033/10 | Si **servicio** = “pasaporte_ordinario” (código A01) → **monto = 85 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “pasaporte_urgencia” (código A02) → **monto = 150 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “inscripcion_nacimiento” (código B01) → **monto = 20 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “inscripcion_matrimonio” (código B02) → **monto = 50 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “poder_general” (código P01) → **monto = 60 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “poder_especial” (código P02) → **monto = 35 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “legalizacion_firma” (código D01) → **monto = 25 USD** | Fijo. |
| 4.033/10 | Si **servicio** = “visado_pasaporte_extranjero” (código D02) → **monto = 60 USD** | Fijo. |
| 4.033/10 | Si **servicio** está en lista derogada por Ley 7.196/2023 (códigos 01 a 30, 40 a 53, etc.) → **respuesta** = “Este arancel ya no está vigente” | Evita errores. |
| Ambas | Si **tiene_exencion** = true y usuario acredita condición (personas de escasos recursos, repatriados, etc.) → **monto_final = 0** | Exención total. |

Para implementar estas reglas, el sistema necesita una base de conocimiento (por ejemplo, un archivo JSON) que contenga todos los códigos vigentes con sus montos y condiciones. La actualización de la base debe realizarse cada vez que el Poder Ejecutivo modifique el jornal mínimo o que el Congreso apruebe una nueva ley arancelaria.

## 4.2 Sistematización de la lógica normativa en la plataforma digital

La sistematización implica traducir las reglas de negocio a un lenguaje que el software pueda ejecutar. Se propone una arquitectura simple:
1. **Módulo de entrada**: recibe la solicitud del ciudadano (vía chat o formulario).
2. **Motor de reglas**: evalúa las condiciones (si-entonces) utilizando la base de aranceles.
3. **Calculador**: realiza las operaciones aritméticas (multiplicaciones, sumas) y aplica exenciones.
4. **Generador de comprobante**: produce un recibo digital con los desgloses y un número de transacción.

La plataforma digital debe ser desarrollada con un lenguaje de programación que permita mantener el motor de reglas fácilmente actualizable (por ejemplo, PHP, Python o JavaScript). Se recomienda almacenar las reglas en un archivo de configuración (JSON o YAML) para que los funcionarios legales puedan modificarlo sin necesidad de reprogramar.

---

# CAPÍTULO V. Modelo de gestión consular bajo el “Cero Papel”

## 5.1 Digitalización de los flujos de trabajo administrativos

El modelo “Cero Papel” para la liquidación de aranceles consulares implica la siguiente secuencia (reemplazando el proceso actual):
- **Recepción digital**: El ciudadano accede al portal web del Ministerio o al chat, se autentica (mediante identificación electrónica o credenciales básicas) y carga los documentos necesarios en formato digital.
- **Validación automática**: El sistema verifica la integridad de los documentos (formato, tamaño) y utiliza IA para extraer datos relevantes (por ejemplo, tipo de documento, fecha de emisión).
- **Cálculo automático**: Con base en las reglas de negocio, se determina el arancel. El sistema muestra el monto y las opciones de pago (tarjeta, transferencia, pago en línea).
- **Pago electrónico**: Se integra con una pasarela de pagos (Visa, Mastercard, bancos locales). Al confirmarse el pago, se genera un comprobante digital y se envía al ciudadano por correo electrónico.
- **Expediente electrónico**: Todos los documentos y el comprobante quedan almacenados en un repositorio seguro (nube institucional o servidor del MRE). Se asigna un número de expediente único.

De esta manera, se elimina el papel en cada una de las etapas, se reduce la intervención manual y se acelera el tiempo de respuesta.

## 5.2 Estrategias de reducción de costos y tiempos de respuesta

La digitalización y automatización generan ahorros tanto para el Estado como para los ciudadanos. Para el Estado, se reducen costos de impresión, almacenamiento físico, transporte interno y horas de funcionarios dedicadas al cálculo manual. Para los ciudadanos, se eliminan los gastos de traslado a Asunción (pasaje, comida, hospedaje) y el costo de oportunidad del tiempo perdido. Según un estudio del Banco Mundial (2021), cada hora de espera en trámites gubernamentales representa un costo equivalente al 0,5% del salario mensual mínimo en promedio.

Estrategias específicas:
- **Ventanillas virtuales**: Habilitar turnos programados en línea y atención asincrónica.
- **Notificaciones automáticas**: Enviar recordatorios y comprobantes por SMS o WhatsApp.
- **Interoperabilidad con registros públicos**: Acceder a bases de datos de nacimiento, defunción o antecedentes (con autorización del ciudadano) para precargar información y evitar documentos duplicados.
- **Capacitación digital**: Ofrecer tutoriales y asistencia en línea para ciudadanos con baja alfabetización digital.

---

# CAPÍTULO VI. Alcance del modelo, descentralización y beneficio ciudadano

## 6.1 Acceso equitativo para ciudadanos en zonas remotas y en el extranjero

El modelo propuesto permite que cualquier persona con conexión a internet pueda liquidar aranceles y apostillar documentos sin importar su ubicación geográfica. Para los compatriotas en el exterior, el asistente virtual estará disponible 24/7, evitando tener que llamar o enviar correos electrónicos al consulado y esperar días por una respuesta. Además, se prevé una versión del chat optimizada para dispositivos móviles (dado que el acceso a computadoras puede ser limitado en zonas rurales). En casos de desconexión, se podría usar SMS o un servicio de respuesta por mensaje de texto, aunque con funcionalidad reducida.

## 6.2 Riesgos, limitaciones y supervisión humana

Ningún sistema automatizado está exento de riesgos. Los principales a considerar son:

- **Brecha digital**: Una parte de la población (especialmente adultos mayores, personas de bajos ingresos o zonas sin cobertura de internet) podría quedar excluida. Para mitigarlo, se debe mantener una atención presencial mínima (por ejemplo, en municipios del interior) y diseñar una interfaz muy sencilla, con opción de asistencia telefónica.
- **Seguridad de los datos**: El tratamiento de documentos personales (cédulas, títulos, certificados de nacimiento) exige el cumplimiento de la [Ley N° 6.534/2020 de Protección de Datos Personales](https://www.bacn.gov.py/leyes-paraguayas/10031/ley-n-6534-de-proteccion-de-datos-personales). Se deben implementar cifrado extremo a extremo, autenticación de dos factores y registros de auditoría.
- **Errores del sistema**: El reconocimiento de documentos o la interpretación de la intención puede fallar. Por ello, se recomienda un **mecanismo de supervisión humana** detallado:
  - Si el usuario escribe “no entiendo” o “quiero hablar con un funcionario”, se activa una solicitud de chat en vivo con un agente consular (en horario hábil).
  - Si el sistema detecta que el monto a pagar supera los 500 USD (por ejemplo, visados múltiples o poderes generales), automáticamente sugiere confirmación humana antes de proceder al pago.
  - Si la intención del usuario no alcanza un umbral mínimo de confianza (por ejemplo, menos del 60% de coincidencia con las reglas definidas), se guarda el log y se envía un correo al área de informática para su revisión periódica.
  - Se establece un registro de errores (_error log_) para mejorar el modelo iterativamente.
- **Resistencia al cambio**: Tanto funcionarios como ciudadanos pueden mostrarse reacios. Se requiere un plan de comunicación y capacitación, así como incentivos para la adopción (por ejemplo, descuentos en el primer trámite digital).

## 6.3 Implementación gradual: propuesta de proyecto piloto

Se sugiere una implementación por fases:

- **Fase 0 (preparación)**: Actualizar las bases de datos de aranceles, definir estándares de interoperabilidad, capacitar a un equipo técnico.
- **Fase 1 (piloto)**: Poner en marcha el asistente virtual solo para el trámite de “apostilla de firma” en la Dirección de Legalizaciones, con un grupo reducido de ciudadanos (por ejemplo, residentes en Gran Asunción). Evaluar usabilidad, precisión del cálculo y satisfacción.
- **Fase 2 (expansión)**: Incluir los demás tipos de documentos de la Ley 1.030/97 y conectar con al menos dos consulados (Buenos Aires y Madrid) para trámites de pasaportes y poderes.
- **Fase 3 (generalización)**: Cubrir todos los aranceles vigentes de la Ley 4.033/10 (los no derogados) y todas las oficinas consulares. Integrar pagos electrónicos.
- **Fase 4 (evaluación y mejora continua)**: Analizar métricas (tiempo promedio, cantidad de errores, ahorro estimado) y ajustar el modelo cada seis meses.

## 6.4 Conexión con la modernización del Estado

La propuesta se alinea con los objetivos de la **Agenda Digital del Paraguay 2025** y las directrices de la **SENATICs** (Secretaría Nacional de Tecnologías de la Información y Comunicación). La modernización del Estado paraguayo busca “un Estado ágil, eficiente y transparente, orientado al ciudadano” (SENATICs, 2021). La automatización de la liquidación de aranceles consulares es un ejemplo concreto de cómo la inteligencia artificial puede reducir la burocracia, combatir la corrupción (al eliminar la discrecionalidad en el cobro) y mejorar la equidad territorial. Además, el modelo puede ser replicado en otros ministerios (por ejemplo, tasas de servicios en el Ministerio de Justicia o registro de marcas en DINAPI). Por tanto, la investigación no solo aporta una solución técnica puntual, sino que contribuye a la estrategia nacional de transformación digital del Estado.

---

# REFERENCIAS

AGESIC. (2022). *Asistente virtual Iris: Resultados y métricas*. Agencia de Gobierno Electrónico y Sociedad de la Información, Uruguay. https://www.agesic.gub.uy

Androutsopoulou, A., Karacapilidis, N., Loukis, E., & Charalabidis, Y. (2019). Transforming the communication between citizens and government through AI-guided chatbots. *Government Information Quarterly*, 36(2), 358-367.

Banco Interamericano de Desarrollo (BID). (2020). *El costo de los trámites: Medición del tiempo y el dinero que los ciudadanos gastan en servicios públicos*. BID.

Banco Mundial. (2021). *Digital Government Readiness Assessment Toolkit*. World Bank.

CEPAL. (2018). *Gobierno digital y simplificación administrativa en América Latina*. Naciones Unidas.

Giarratano, J., & Riley, G. (2005). *Expert Systems: Principles and Programming* (4th ed.). Thomson.

Gobierno de Chile. (2021). *Portal del Estado: Automatización de tasas notariales*. Ministerio de Hacienda, Chile. https://www.chileatiende.cl

Hernández Sampieri, R., Fernández Collado, C., & Baptista Lucio, P. (2018). *Metodología de la investigación* (6ª ed.). McGraw-Hill.

Hurtado de Barrera, J. (2010). *Metodología de la investigación: guía para una comprensión holística*. Quirón.

Janowski, T. (2015). Digital government evolution: From transformation to contextualization. *Government Information Quarterly*, 32(3), 221-236.

Layne, K., & Lee, J. (2001). Developing fully functional E-government: A four stage model. *Government Information Quarterly*, 18(2), 122-136.

Margetts, H., & Dorobantu, C. (2019). Rethink government with AI. *Nature*, 568(7751), 163-165.

MINTIC. (2023). *Estrategia Cero Papel: Resultados y ahorros*. Ministerio de Tecnologías de la Información y Comunicaciones, Colombia. https://www.mintic.gov.co

Misuraca, G., & Viscusi, G. (2015). Shaping the future of public sector innovation. *Communications of the ACM*, 58(6), 48-50.

OCDE. (2019). *Estudio de la OCDE sobre gobierno digital en Paraguay*. OECD Publishing.

Roa, C. (2023). Análisis de la liquidación de aranceles consulares en el marco de la Ley 4033/10. *Memorias del Congreso de Modernización del Estado*, 88-94.

Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.

Sellen, A. J., & Harper, R. H. R. (2002). *The Myth of the Paperless Office*. MIT Press.

SENATICs. (2021). *Agenda Digital del Paraguay 2025*. Secretaría Nacional de Tecnologías de la Información y Comunicación.

UNESCO. (2016). *World Social Science Report 2016: Challenging Inequalities*. UNESCO Publishing.

van der Aalst, W. M. P., Bichler, M., & Heinzl, A. (2018). Robotic process automation. *Business & Information Systems Engineering*, 60(4), 269-272.

Wanner, J., Hofmann, A., & Fischer, M. (2019). Process automation in the public sector. *Proceedings of the 52nd Hawaii International Conference on System Sciences*, 1-10.

Willcocks, L., Lacity, M., & Craig, A. (2017). Robotic process automation: Strategic and operational benefits. *The Outsourcing Unit Working Paper*, London School of Economics.

## Referencias legales

Congreso de la Nación Paraguaya. (1997). [*Ley N° 1.030: Que modifica y amplía la Ley Nº 133/93 y deroga el Decreto Ley Nº 46/72*](https://www.bacn.gov.py/leyes-paraguayas/2245/ley-n-1030-que-modifica-y-amplia-la-ley-n-133-93-y-deroga-el-decreto-ley-n-46-72-actualizando-las-tasas-por-servicios-de-legalizacion). BACN.

Congreso de la Nación Paraguaya. (2001). [*Ley N° 1.635: Orgánica del Ministerio de Relaciones Exteriores*](https://www.bacn.gov.py/leyes-paraguayas/1715/leyes-paraguayas). BACN.

Congreso de la Nación Paraguaya. (2010). [*Ley N° 4.033: Del Arancel Consular*](https://www.bacn.gov.py/leyes-paraguayas/513/ley-n-4033-del-arancel-consular). BACN.

Congreso de la Nación Paraguaya. (2014). [*Ley N° 5.254: Modifica los artículos 3°, 6°, 12 y 14 de la Ley N° 4.033/10*](https://www.bacn.gov.py/leyes-paraguayas/2997/ley-n-5254-modifica-los-art-culos-3-6-12-y-14-de-la-ley-n-4-033-10-del-arancel-consular-br). BACN.

Congreso de la Nación Paraguaya. (2020). [*Ley N° 6.534: De protección de datos personales*](https://www.bacn.gov.py/leyes-paraguayas/10031/ley-n-6534-de-proteccion-de-datos-personales). BACN.

Congreso de la Nación Paraguaya. (2023). [*Ley N° 7.196: Deroga varios artículos de la Ley N° 4.033/2010*](https://www.bacn.gov.py/leyes-paraguayas/12025/ley-n-7196-que-deroga-varios-art-culos-de-la-ley-n-4033-2010-del-arancel-consular). BACN.

Ministerio de Relaciones Exteriores. (s.f.). [*Dirección General de Asuntos Consulares*](https://www.mre.gov.py/direccion-general-de-asuntos-consulares-dgac/). MRE.
