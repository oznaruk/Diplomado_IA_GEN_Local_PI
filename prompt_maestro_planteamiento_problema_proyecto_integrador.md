# Prompt maestro — Planteamiento del problema para proyecto integrador

## Instrucciones para ChatGPT

Asume el rol de un ingeniero senior de prompts, arquitecto de soluciones de inteligencia artificial y asesor metodológico de proyectos de grado en Ingeniería de Sistemas, con experiencia en inteligencia artificial local, gobernanza tecnológica, gestión de riesgos, sistemas multimodales y redacción académica.

Tu tarea es elaborar un documento formal, con estructura tipo tesis, para el planteamiento inicial del proyecto integrador del Diplomado en Inteligencia Artificial Generativa Local, Agentes Autónomos y Sistemas Multimodales.

El documento debe corresponder exclusivamente al alcance del Módulo 1: “Fundamentos, soberanía tecnológica y gobernanza de IA”. No debes desarrollar todavía la implementación completa, el código, el RAG detallado, el entrenamiento de modelos ni la arquitectura definitiva de los módulos posteriores. Sin embargo, debes dejar claramente formuladas las bases del proyecto para su desarrollo posterior.

## Contexto del proyecto

El proyecto consiste en diseñar una aplicación web multimodal de ejecución local para artistas independientes y gestores de proyectos culturales.

La aplicación integrará:

1. Un reproductor de audio para consultar o reproducir contenidos musicales y sonoros.
2. Un visor de documentación relacionada con derechos de autor, licencias, permisos y uso de obras.
3. Mapas interactivos para localizar eventos culturales, presentaciones, exposiciones y actividades artísticas.
4. Una galería de merchandising para visualizar y consultar productos asociados a los artistas o proyectos culturales.
5. Capacidades multimodales relacionadas con texto, audio, imágenes, documentos, mapas y posiblemente modelos 3D en futuras etapas.
6. Operación local o local-first, de manera que los activos digitales, documentos, datos de artistas y contenidos culturales permanezcan bajo control de la organización y no dependan permanentemente de servicios externos en la nube.

El sistema debe concebirse como una solución soberana, reproducible, evaluable, segura y orientada a la protección de activos culturales, información de proyectos, datos de usuarios y derechos de autor.

El proyecto debe considerar que una solución local no elimina las obligaciones legales, éticas ni de seguridad relacionadas con el tratamiento de datos personales, derechos de autor, licenciamiento, consentimiento y propiedad intelectual.

## Marco académico que debes aplicar

Utiliza como referencia el documento del diplomado adjunto y respeta especialmente los siguientes elementos:

- Enfoque local-first.
- Ingeniería de sistemas aplicada a inteligencia artificial.
- Soberanía tecnológica y control sobre datos, modelos y flujos de trabajo.
- Evaluación de riesgos, trazabilidad y documentación.
- Privacidad, seguridad, licenciamiento y propiedad intelectual.
- Supervisión humana y responsabilidad sobre las decisiones del sistema.
- Pertinencia territorial y viabilidad en contextos con capacidades tecnológicas heterogéneas.
- Principio de mínimo privilegio.
- Reproducibilidad técnica.
- Operación sin conexión después de preparar el entorno.
- Uso de datos públicos, sintéticos, anonimizados o debidamente autorizados.
- NIST AI Risk Management Framework, especialmente las funciones Govern, Map, Measure y Manage.
- Riesgos propios de sistemas generativos y multimodales, como alucinaciones, fuga de información, prompt injection, uso indebido de herramientas, sesgos, contenido sintético y dependencia de modelos.

No inventes datos institucionales, estadísticas, nombres de organizaciones, porcentajes de usuarios, resultados de encuestas ni evidencias empíricas que no hayan sido suministradas. Cuando falte información, indícalo expresamente como supuesto, limitación o aspecto pendiente de validación.

## Objetivo del documento

Elabora un documento académico que permita presentar y delimitar formalmente el problema del proyecto integrador, incluyendo:

1. Planteamiento del problema.
2. Formulación del problema mediante una pregunta central.
3. Justificación técnica, académica, social, cultural y territorial.
4. Usuarios y partes interesadas.
5. Alcance funcional y no funcional.
6. Exclusiones y límites del proyecto.
7. Requisitos funcionales.
8. Requisitos no funcionales.
9. Criterios de éxito verificables.
10. Identificación inicial de datos, activos y flujos de información.
11. Decisión preliminar sobre arquitectura local, híbrida o remota.
12. Matriz inicial de riesgos basada en NIST AI RMF.
13. Supuestos, restricciones y dependencias.
14. Conclusión del planteamiento inicial.
15. Información pendiente por validar durante el desarrollo del módulo 1.

## Estructura obligatoria

Organiza el documento con la siguiente estructura numerada:

### Portada

Incluye campos editables para:

- Nombre de la institución.
- Programa académico.
- Nombre del diplomado.
- Título del proyecto.
- Nombre de los autores.
- Nombre del docente o asesor.
- Ciudad.
- Fecha.

Propón un título académico apropiado, por ejemplo:

“Diseño de una aplicación web multimodal de ejecución local para la gestión soberana de contenidos, eventos y activos digitales de artistas independientes y proyectos culturales”.

### Resumen

Escribe un resumen de entre 150 y 250 palabras que explique:

- El contexto del problema.
- La población o grupo beneficiario.
- La solución propuesta.
- El enfoque local-first.
- La importancia de la privacidad, la soberanía tecnológica y los derechos de autor.
- El propósito del documento dentro del Módulo 1.

Incluye entre cinco y siete palabras clave.

### 1. Introducción

Presenta el contexto general de la transformación digital del sector cultural y la necesidad de contar con herramientas que integren contenidos sonoros, documentación, ubicación de eventos y comercialización de productos.

Explica que la propuesta no debe reducirse a una interfaz visual, sino que debe analizarse como una solución de ingeniería con datos, usuarios, activos digitales, riesgos, restricciones técnicas, criterios de evaluación y responsabilidades.

### 2. Contexto y antecedentes del problema

Desarrolla el contexto sin inventar estadísticas.

Analiza, de manera argumentada:

- La fragmentación de herramientas utilizadas por artistas y gestores culturales.
- La dificultad para centralizar contenidos, documentación, eventos y merchandising.
- La dependencia potencial de plataformas externas.
- Los riesgos de pérdida de control sobre activos digitales.
- La importancia de consultar información sobre derechos de autor y licenciamiento.
- Las dificultades de conectividad o infraestructura tecnológica que hacen pertinente una estrategia local-first.
- La necesidad de integrar diferentes tipos de información en una experiencia multimodal.
- La importancia de una solución que pueda evolucionar posteriormente hacia RAG, agentes o funciones inteligentes controladas.

Si haces afirmaciones legales o normativas, preséntalas con prudencia y aclara que deberán ser revisadas por un profesional competente. No presentes el sistema como asesor jurídico.

### 3. Planteamiento del problema

Redacta esta sección con tono formal y estructura argumentativa.

Debe responder claramente:

- ¿Cuál es la situación problemática?
- ¿A quién afecta?
- ¿Qué información o procesos se encuentran fragmentados?
- ¿Qué consecuencias genera la situación actual?
- ¿Por qué una solución web multimodal local puede ser pertinente?
- ¿Qué riesgos existirían si se adopta una solución dependiente de servicios externos?
- ¿Qué problema de ingeniería de sistemas se busca resolver?

Distingue entre:

- Problema central.
- Causas principales.
- Consecuencias principales.
- Necesidad de intervención tecnológica.

No describas el problema como “falta de una aplicación” de manera superficial. Formula el problema en términos de necesidades, procesos, información, usuarios, riesgos, soberanía tecnológica y resultados verificables.

Incluye una formulación final del problema en un párrafo de síntesis.

### 4. Pregunta de investigación o pregunta orientadora

Formula una pregunta central clara, viable y coherente con el alcance del Módulo 1.

La pregunta debe relacionar:

- Aplicación web multimodal.
- Ejecución local.
- Artistas independientes y gestores culturales.
- Gestión de contenidos y activos digitales.
- Privacidad, derechos de autor y soberanía tecnológica.

Propón también entre tres y cinco subpreguntas orientadoras relacionadas con usuarios, datos, arquitectura, riesgos y criterios de éxito.

### 5. Justificación

Organiza la justificación en subsecciones:

#### 5.1 Justificación técnica

Explica el valor de una arquitectura local-first, la reducción de transferencias innecesarias, la posibilidad de controlar versiones, dependencias, almacenamiento y procesamiento, y la capacidad de operar con conectividad limitada.

#### 5.2 Justificación académica

Relaciona el proyecto con las competencias del diplomado:

- Caracterización de casos de uso.
- Diagnóstico de recursos.
- Identificación y clasificación de datos.
- Análisis de riesgos.
- Selección de arquitectura.
- Documentación técnica.
- Evaluación y trazabilidad.
- Diseño de soluciones multimodales.

#### 5.3 Justificación cultural y social

Explica la importancia de fortalecer la autonomía de artistas independientes, gestores culturales y organizaciones que administran contenidos, eventos, productos y documentación propia.

No afirmes impactos sociales ya demostrados. Formula estos impactos como beneficios esperados o potenciales.

#### 5.4 Justificación territorial

Relaciona el proyecto con el contexto del Cauca, Popayán y municipios con capacidades tecnológicas heterogéneas, sin atribuir características específicas a organizaciones que no hayan sido identificadas.

#### 5.5 Justificación de gobernanza y responsabilidad

Explica por qué el proyecto debe incorporar desde su formulación inicial:

- Protección de datos.
- Derechos de autor.
- Licenciamiento.
- Consentimiento.
- Trazabilidad.
- Identificación de contenido sintético.
- Supervisión humana.
- Gestión de riesgos.
- Control de acceso.

### 6. Usuarios y partes interesadas

Construye una tabla con las siguientes columnas:

| Actor o usuario | Necesidades | Interacciones con el sistema | Datos o activos involucrados | Riesgos o consideraciones |
|---|---|---|---|---|

Incluye, como mínimo:

- Artistas independientes.
- Gestores de proyectos culturales.
- Organizadores de eventos.
- Visitantes o usuarios finales.
- Compradores de merchandising.
- Administradores de la plataforma.
- Responsables de contenidos y derechos.
- Instituciones culturales o aliados.
- Equipo técnico o desarrolladores.
- Entidades que puedan autorizar el uso de obras, imágenes, audios o documentos.

Diferencia claramente entre usuarios directos, administradores, responsables de información y partes interesadas indirectas.

### 7. Activos, datos y flujo de información

Identifica los principales activos y datos del sistema.

Organiza la información en una tabla con las columnas:

| Activo o dato | Tipo | Propietario o responsable | Sensibilidad | Uso previsto | Tratamiento local | Riesgo asociado |
|---|---|---|---|---|---|---|

Considera, entre otros:

- Audios.
- Imágenes.
- Fichas de artistas.
- Documentos sobre derechos de autor.
- Licencias.
- Ubicaciones de eventos.
- Información de merchandising.
- Datos de contacto.
- Datos de usuarios.
- Credenciales administrativas.
- Metadatos y registros de actividad.
- Modelos, configuraciones y archivos de la aplicación.
- Logs del sistema.
- Contenido generado o transformado mediante inteligencia artificial.

Después de la tabla, describe textualmente el flujo general de información desde la carga del activo hasta su consulta por el usuario.

Distingue:

- Datos de entrada.
- Procesamiento.
- Almacenamiento.
- Consulta.
- Publicación.
- Administración.
- Eliminación o conservación.

### 8. Alcance del proyecto

Define el alcance con precisión.

#### 8.1 Alcance funcional

Incluye como mínimo:

- Gestión de perfiles o fichas de artistas.
- Reproducción local de audio.
- Consulta de documentos relacionados con derechos de autor y licencias.
- Visualización de eventos mediante mapas interactivos.
- Consulta de productos de merchandising.
- Galería de imágenes y otros activos autorizados.
- Panel administrativo básico.
- Gestión de permisos y roles.
- Registro de procedencia y licencias de los contenidos.
- Operación local o local-first.
- Exportación o respaldo controlado de información.
- Identificación de contenido sintético cuando aplique.

Aclara cuáles funcionalidades son obligatorias para el prototipo y cuáles pueden quedar como evolución futura.

#### 8.2 Alcance técnico preliminar

Describe, sin convertirlo todavía en un diseño definitivo:

- Aplicación web autoalojada.
- Base de datos local.
- Almacenamiento local de archivos.
- Reproductor de audio.
- Visor documental.
- Módulo cartográfico.
- Galería de productos.
- Control de acceso.
- Registro de eventos y auditoría.
- Posible integración futura con LLM local, RAG o agentes controlados.

No afirmes que se utilizará una herramienta específica si aún no ha sido validada.

#### 8.3 Exclusiones

Indica expresamente que inicialmente quedan fuera del alcance:

- Pasarela de pagos real.
- Asesoría jurídica automatizada.
- Publicación automática en redes sociales.
- Clonación de voz o rostro.
- Reconocimiento biométrico.
- Decisiones automatizadas sobre derechos.
- Moderación completamente autónoma.
- Entrenamiento de modelos fundacionales.
- Dependencia obligatoria de servicios cloud.
- Escalamiento comercial masivo.
- Sistema de medición legal o geográfica de precisión profesional.
- Integraciones con terceros no autorizadas.

### 9. Requisitos del sistema

#### 9.1 Requisitos funcionales

Elabora una tabla con mínimo 12 requisitos funcionales.

Usa las columnas:

| ID | Requisito | Descripción | Prioridad | Criterio de aceptación preliminar |
|---|---|---|---|---|

Los requisitos deben redactarse con verbos verificables, por ejemplo:

- Registrar.
- Consultar.
- Reproducir.
- Filtrar.
- Visualizar.
- Administrar.
- Autorizar.
- Restringir.
- Respaldar.
- Auditar.
- Exportar.
- Identificar.

Incluye requisitos relativos a:

- Gestión de usuarios.
- Roles y permisos.
- Gestión de artistas.
- Audio.
- Documentos.
- Eventos.
- Mapas.
- Merchandising.
- Imágenes.
- Licencias.
- Procedencia.
- Auditoría.
- Operación local.

#### 9.2 Requisitos no funcionales

Elabora una tabla con mínimo 12 requisitos no funcionales.

Usa las columnas:

| ID | Categoría | Requisito | Indicador o forma de verificación | Prioridad |
|---|---|---|---|---|

Incluye categorías como:

- Privacidad.
- Seguridad.
- Disponibilidad local.
- Rendimiento.
- Usabilidad.
- Accesibilidad.
- Mantenibilidad.
- Reproducibilidad.
- Portabilidad.
- Trazabilidad.
- Licenciamiento.
- Sostenibilidad.
- Compatibilidad.
- Recuperación ante fallos.

Cuando no existan valores definidos, utiliza metas preliminares razonables y márcalas como “pendientes de validación”.

No inventes tiempos de respuesta, número de usuarios o volúmenes de almacenamiento como hechos. Si propones valores, identifícalos como objetivos iniciales sujetos a pruebas.

### 10. Arquitectura preliminar y decisión local-first

Describe conceptualmente una arquitectura preliminar compuesta por:

- Capa de presentación.
- Capa de aplicación.
- Capa de datos.
- Capa de almacenamiento de activos.
- Capa de autenticación y autorización.
- Capa de auditoría.
- Capa de mapas.
- Capa de reproducción de audio.
- Capa de documentación.
- Posible capa futura de inteligencia artificial local.

Compara brevemente tres alternativas:

1. Arquitectura totalmente local.
2. Arquitectura híbrida.
3. Arquitectura dependiente de servicios cloud.

Utiliza una tabla con los criterios:

| Criterio | Local | Híbrida | Cloud dependiente |
|---|---|---|---|

Evalúa:

- Privacidad.
- Control de activos.
- Conectividad.
- Costos recurrentes.
- Facilidad de despliegue.
- Mantenimiento.
- Escalabilidad.
- Trazabilidad.
- Riesgos de dependencia.

Después, formula una decisión preliminar justificada. La recomendación debe ser local-first, pero debes aclarar que algunos componentes externos, como cartografía o actualización de información, deberán analizarse y validarse antes de su incorporación.

### 11. Matriz inicial de riesgos basada en NIST AI RMF

Construye una matriz formal de riesgos aplicando las funciones:

- Govern.
- Map.
- Measure.
- Manage.

Utiliza la siguiente estructura:

| ID | Función NIST AI RMF | Activo o proceso afectado | Riesgo | Causa | Consecuencia | Probabilidad | Impacto | Nivel de riesgo | Control o tratamiento propuesto | Responsable | Evidencia de verificación | Estado |
|---|---|---|---|---|---|---|---|---|---|---|---|---|

Incluye como mínimo 15 riesgos relevantes, entre ellos:

1. Exposición no autorizada de audios, imágenes o documentos.
2. Uso de obras sin licencia o sin autorización.
3. Confusión entre información general y asesoría jurídica.
4. Modificación o eliminación accidental de activos.
5. Acceso excesivo de administradores.
6. Uso de credenciales débiles.
7. Fuga de información mediante logs o respaldos.
8. Dependencia de servicios externos para mapas o contenidos.
9. Indisponibilidad del sistema local.
10. Corrupción de archivos.
11. Falta de trazabilidad sobre la procedencia de obras.
12. Publicación de contenido sintético sin identificación.
13. Alucinaciones o información incorrecta en futuras funciones de IA.
14. Prompt injection en documentos si se incorpora RAG.
15. Uso indebido de herramientas por futuros agentes.
16. Vulnerabilidades en dependencias de software.
17. Pérdida de datos por ausencia de copias de seguridad.
18. Tratamiento inadecuado de datos personales.
19. Uso de imágenes o voces de personas sin consentimiento.
20. Falta de accesibilidad o exclusión de usuarios.

Utiliza una escala cualitativa explícita:

- Probabilidad: baja, media o alta.
- Impacto: bajo, medio o alto.
- Nivel de riesgo: bajo, medio o alto.

No presentes la matriz como una evaluación definitiva. Preséntala como una matriz inicial que deberá actualizarse durante el desarrollo.

Después de la tabla, incluye una sección titulada “Lectura de la matriz de riesgos” donde expliques:

- Los riesgos prioritarios.
- Los riesgos que deben atenderse antes del prototipo.
- Los riesgos que requieren validación legal o institucional.
- Los riesgos que corresponden a fases posteriores de IA generativa, RAG o agentes.
- Las medidas de aceptación, mitigación, transferencia o evitación del riesgo.

### 12. Criterios de éxito

Define criterios de éxito verificables y alineados con el proyecto.

Utiliza una tabla con las columnas:

| ID | Criterio de éxito | Indicador | Método de verificación | Meta preliminar | Evidencia |
|---|---|---|---|---|---|

Incluye criterios sobre:

- Funcionamiento local.
- Consulta y reproducción de audio.
- Visualización documental.
- Visualización de eventos en mapas.
- Consulta de merchandising.
- Gestión de roles y permisos.
- Protección de activos.
- Trazabilidad de licencias.
- Reproducibilidad del despliegue.
- Disponibilidad sin conexión, cuando sea aplicable.
- Copias de seguridad.
- Auditoría.
- Usabilidad.
- Accesibilidad.
- Seguridad.
- Ausencia de publicación no autorizada.
- Reconocimiento de limitaciones.
- Documentación técnica.

Diferencia entre:

- Criterios mínimos de aprobación del prototipo.
- Criterios deseables para una versión futura.

No declares que el proyecto es exitoso solo porque “la aplicación funciona”. La evaluación debe considerar coherencia entre problema, usuarios, datos, arquitectura, seguridad, documentación y viabilidad.

### 13. Supuestos, restricciones y dependencias

Organiza esta sección en una tabla:

| Tipo | Descripción | Impacto en el proyecto | Acción de validación |
|---|---|---|---|

Incluye aspectos como:

- Disponibilidad de equipos.
- Capacidad de almacenamiento.
- Conectividad.
- Licencias de mapas.
- Licencias de audio, imágenes y documentos.
- Disponibilidad de contenidos autorizados.
- Capacidad del equipo de desarrollo.
- Necesidad de asesoría jurídica.
- Posible uso de GPU compartida.
- Disponibilidad de usuarios para validar el prototipo.
- Restricciones de tiempo del diplomado.
- Uso de datos sintéticos o anonimizados.
- Compatibilidad con sistemas operativos.

### 14. Información pendiente por validar

Incluye una lista de preguntas que el equipo deberá resolver en el Módulo 1, como:

- ¿Quién será el propietario de los contenidos?
- ¿Qué tipos de usuarios existirán?
- ¿Qué documentos de derechos de autor estarán disponibles?
- ¿Qué formatos de audio, imagen y video se utilizarán?
- ¿La ubicación de los eventos será pública o restringida?
- ¿Se manejarán datos personales?
- ¿Qué mapas pueden utilizarse sin conexión?
- ¿Qué equipo de hardware estará disponible?
- ¿Qué volumen de activos se almacenará?
- ¿Qué funcionalidades deben funcionar completamente offline?
- ¿Qué contenidos requieren autorización expresa?
- ¿Qué componente multimodal tendrá prioridad?
- ¿Se incorporará inteligencia artificial generativa en el primer prototipo o se dejará como fase posterior?
- ¿Cuál será el criterio institucional de aceptación?
- ¿Quién aprobará la publicación de contenidos?

### 15. Conclusiones

Redacta entre tres y cinco conclusiones que:

- Sinteticen el problema identificado.
- Justifiquen el enfoque local-first.
- Destaquen la necesidad de gobernanza.
- Relacionen el proyecto con el Módulo 1.
- Establezcan que la matriz de riesgos, los requisitos y los criterios de éxito son preliminares.
- Indiquen que las decisiones definitivas dependerán de la validación técnica, legal, institucional y con usuarios.

## Reglas de redacción académica

- Escribe en español colombiano formal.
- Utiliza tono profesional, técnico y académico.
- Redacta en tercera persona o en forma impersonal.
- Evita expresiones promocionales como “revolucionario”, “innovador” o “sin precedentes”, salvo que sean justificadas.
- No utilices lenguaje coloquial.
- No inventes fuentes, cifras, encuestas, usuarios ni resultados.
- No presentes hipótesis como hechos comprobados.
- Diferencia claramente hechos, supuestos, objetivos y aspectos pendientes.
- Utiliza numeración jerárquica coherente.
- Evita párrafos excesivamente extensos.
- Usa tablas cuando faciliten la comprensión.
- Define las siglas la primera vez que aparezcan.
- Utiliza “inteligencia artificial” y no solamente “IA” la primera vez.
- Explica términos técnicos como local-first, RAG, agente, activo digital y prompt injection.
- No conviertas el documento en un tutorial de herramientas.
- No incluyas código.
- No incluyas una arquitectura técnica definitiva.
- No afirmes cumplimiento legal total.
- Aclara que la información sobre derechos de autor debe validarse con asesoría jurídica o institucional competente.

## Referencias y trazabilidad

Utiliza únicamente como referentes iniciales los marcos mencionados en el documento del diplomado:

- NIST AI Risk Management Framework.
- NIST Generative AI Profile.
- CONPES 4144 de 2025.
- Recomendación de la UNESCO sobre la Ética de la Inteligencia Artificial.
- Ley 1581 de 2012 de Colombia.
- Reglamento Europeo de Inteligencia Artificial como referente comparado.
- Documentación del diplomado adjunto.

No inventes enlaces, autores, fechas de consulta ni referencias bibliográficas que no puedas verificar.

Al final, incluye una sección titulada “Referencias preliminares” y señala cuáles referencias requieren verificación o ampliación en la siguiente fase.

## Control de calidad antes de entregar

Antes de presentar el documento, realiza internamente esta revisión:

1. Verifica que el planteamiento del problema sea específico y no genérico.
2. Verifica que los usuarios estén relacionados con el contexto cultural.
3. Verifica que el alcance sea viable para un prototipo académico.
4. Verifica que los requisitos sean verificables.
5. Verifica que los criterios de éxito tengan indicadores y evidencias.
6. Verifica que la matriz incluya las funciones Govern, Map, Measure y Manage.
7. Verifica que la matriz contenga riesgos técnicos, legales, éticos, operativos y de seguridad.
8. Verifica que el enfoque local-first esté justificado, pero no presentado como solución absoluta.
9. Verifica que no se hayan inventado datos.
10. Verifica que el documento sea coherente con el Módulo 1.
11. Verifica que el sistema no sea presentado como asesor jurídico.
12. Verifica que las funciones futuras de RAG, agentes o inteligencia artificial generativa estén diferenciadas del alcance inicial.

Entrega únicamente el documento final, sin explicar el proceso de generación.
