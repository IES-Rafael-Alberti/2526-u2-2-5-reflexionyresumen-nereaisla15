# RESPUESTAS — Reflexión y Resumen (Plantilla genérica)

> **Actividad / ID:**  
> **Unidad / Tema:**  
> **Alumno/a:**  
> **Fecha:**  

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?
La verdad es que los temas que hemos visto me han parecido súper interesantes, pero lo que más me llamó la atención fue la parte de OSINT. Me encantó verlo en acción en la charla de Córdoba y entender paso a paso cómo, a partir de un nombre, una imagen o cualquier pequeño dato, se puede ir tirando del hilo hasta encontrar mucha más información.

Me hizo darme cuenta de lo fácil que es sacar datos personales de algo que a veces compartimos sin pensarlo demasiado. Sobre todo me ha hecho reflexionar sobre todo lo que implica subir una simple foto y la poca conciencia que tenemos, muchas veces, de la huella digital que vamos dejando.

También el como funciona un soc en una empresa y hacer una práctica del siem para ver su funcionamiento es interesante, ver como funciona todo por detrás, aprender a crear alertas y los diferentes roles que existen en una empresa. Sobre todo estoy aprendiendo a documentar mejor y estructurar bien los documentos. La parte de exponer también me ha ayudado mucho a no entrar en pánico, porque yo lo pasaba muy mal y esto me está ayudando a gestionarlo.

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?
Para mi esta siendo útil todo. Cuando yo entré aquí, no sabía absolutamente nada, he aprendido a usar varias herramientas para diferentes situaciones, también a documentar mejor y expresarme, ser más técnica a la hora de redactar los documentos y sobre todo a expresarme mejor con las exposiciones, es algo que agradezco mucho tener que exponer tantas veces que me hace mejorar en cada exposición.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?
Realmente no conocía mucho de la ciberseguridad y en concreto en la parte de incidentes no tenía ni idea. En esta asignatura he visto el funcionamiento de un departamento de IT o de ciberseguridad, donde se dedican a gestionar los incidentes o preparar los planes antes de que pasen. Sobre todo la gran documentación que hay, que en cada paso que se de tiene que estar bien documentado porque es lo más esencial de todo.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué?
Me llamó mucho lo del OSINT y fue gracias a verlo en acción en la presentación de Córdoba, me parece muy interesante y me gustaría trabajar de algo así. Poder encontrar información donde nadie cree que hay y resolver casos.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.
Recortar no recortaría nada, me parece todo importante en esta unidad, vimos como clasificar los tipos de incidentes, todo lo del OSINT, como documentar bien un informe y el SIEM. Al final todo esto es importante es el resumen de como funciona una empresa, si acaso recortaria lo del SIEM ya que ha sido complicado montarlo para la práctica y hubiera hecho uno en clase todos juntos y verlo en acción mandandole ataques y alertas.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.
Me hubiera gustado hacer más cosas sobre OSINT o algún taller interesante de como aprender bien a investigar, es algo que me llama mucho la atención y que no sabía que existia.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?
Aplicaría sobre todo una buena organización y documentación de los incidentes, aunque no hubiera muchas herramientas. Tener claro qué ha pasado, qué impacto tiene y qué se ha hecho para solucionarlo ya marca la diferencia.

También revisaría los logs básicos de sistemas y equipos para detectar comportamientos raros, aunque sea de forma manual. No hace falta un SIEM muy avanzado para empezar a controlar lo más crítico.

Y, muy importante, haría concienciación al equipo sobre los riesgos de la información que compartimos, aplicando lo aprendido en OSINT. Muchas veces, con pocos recursos, la prevención y la formación son lo que más protege.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?
Pues bueno me gustaría ver mejor como montar un SIEM en clase pero que lo vaya haciendo el profesor y que todos los veamos en vivo y podamos probarlo y hacer una simulación con los roles que hay en un soc para ver como se trabaja en una empresa. También pues sobre la línea delgada entre OSINT activo y pasiva.


## 2) Resumen esquematizado (obligatorio)

| Sección | Contenido | Prácticas / Ejemplos |
|---------|-----------|--------------------|
| **2.1 Taxonomía de incidentes** | Clasificación de incidentes: accesos no autorizados, malware, fuerza bruta, phishing, DoS. Permite priorizar y estandarizar la respuesta. | Práctica 2.1: Clasificación de incidentes según tipología e impacto |
| **2.2 SOC – Servicios y herramientas** | Monitorización continua, gestión de incidentes, roles: analistas N1, N2, N3, responsables de seguridad | - |
| **2.2.2 SIEM** | **Qué es:** Sistema de gestión de eventos y logs, correlaciona eventos y genera alertas. <br> **Casos de uso:** Detección de fuerza bruta, accesos fuera de horario, actividad anómala. <br> **Implantación:** Instalación, integración de logs, reglas de correlación, alertas. <br> **Evolución:** Integración con SOAR, IA, análisis avanzado. | Práctica 2.2: SIEM (ELK) e IDS (Snort) – instalación, envío de logs, creación de alertas |
| **2.3 Fuentes Abiertas – OSINT** | Obtención de información de fuentes públicas. Investigación desde nombres, imágenes, usuarios. Riesgos de exposición digital. Uso en análisis de amenazas. | Ejemplos prácticos vistos en la charla de Córdoba |
| **2.4 Documentación** | **Documentación de incidentes:** registro de acciones, evidencias, trazabilidad, importancia legal. <br> **Informes técnicos:** lenguaje claro, estructura formal, datos objetivos, conclusiones justificadas. | - |


### 2.1) Mapa/índice de la unidad (visión global)
- **2.1 Taxonomía de incidentes**
  - Clasificación de incidentes
  - Tipos: accesos no autorizados, malware, fuerza bruta, phishing, DoS
  - Práctica 2.1: Taxonomía

- **2.2 SOC – Servicios y herramientas**
  - Función del SOC
  - Roles: Analistas N1, N2, N3, Responsable de seguridad

  - **2.2.2 SIEM**
    - 2.2.2.1 Qué es un SIEM
    - 2.2.2.2 Casos de uso
    - 2.2.3 Implantación de un SIEM
    - 2.2.4 Evolución del SIEM
    - Práctica 2.2: SIEM (ELK) e IDS (Snort)

- **2.3 Fuentes Abiertas – OSINT**
  - Concepto y utilidad
  - Riesgos y exposición digital
  - Aplicaciones prácticas

- **2.4 Documentación**
  - 2.4.1 Documentación de incidentes
  - 2.4.2 Cómo escribir informes técnicos


### 2.2) Conceptos clave (lista breve)
- **Incidente de seguridad:** Evento que compromete la confidencialidad, integridad o disponibilidad.  
- **Taxonomía de incidentes:** Clasificación y priorización según tipo e impacto.  
- **SOC (Security Operations Center):** Centro de operaciones que monitoriza y responde ante incidentes.  
- **Roles SOC:** Analista N1, N2, N3, responsable de seguridad/CISO.  
- **SIEM (Security Information and Event Management):** Sistema que recopila, correlaciona y analiza logs, generando alertas ante eventos sospechosos.  
- **Casos de uso SIEM:** Detección de fuerza bruta, accesos anómalos, actividad fuera de horario.  
- **Implantación SIEM:** Instalación, integración de logs, creación de reglas y alertas.  
- **Evolución SIEM:** Integración con SOAR, IA y análisis avanzado.  
- **OSINT (Open Source Intelligence):** Investigación a partir de fuentes abiertas, riesgo de exposición digital.  
- **Documentación de incidentes:** Registro de acciones, evidencias y trazabilidad.  
- **Informes técnicos:** Lenguaje claro, estructura formal, datos objetivos y conclusiones justificadas.


### 2.3) Procesos / procedimientos (pasos o checklist)
#### 1. Gestión de incidentes
1. **Detección:** Identificar eventos sospechosos mediante logs, alertas o usuarios.  
2. **Notificación:** Avisar al equipo responsable o SOC.  
3. **Clasificación:** Determinar tipo de incidente y prioridad según impacto.  
4. **Análisis:** Investigar causa, alcance y posibles afectados.  
5. **Contención:** Evitar que el incidente se propague.  
6. **Erradicación:** Eliminar la amenaza o vulnerabilidad.  
7. **Recuperación:** Restaurar servicios y sistemas afectados.  
8. **Lecciones aprendidas:** Documentar todo y mejorar procedimientos.

#### 2. Uso de un SIEM
1. Instalar y configurar la plataforma.  
2. Integrar fuentes de logs (servidores, firewall, endpoints).  
3. Normalizar y correlacionar eventos.  
4. Definir reglas y alertas según escenarios de riesgo.  
5. Monitorizar y analizar alertas.  
6. Ajustar reglas y procesos según resultados y evolución.

#### 3. Investigación OSINT
1. Identificar objetivo o información a investigar.  
2. Buscar fuentes abiertas relevantes (redes sociales, motores de búsqueda, registros públicos).  
3. Analizar y correlacionar información encontrada.  
4. Evaluar riesgos de exposición digital.  
5. Documentar hallazgos y posibles acciones preventivas.

#### 4. Documentación de incidentes e informes
1. Registrar cada paso realizado.  
2. Adjuntar evidencias y capturas si procede.  
3. Redactar informe técnico claro y estructurado.  
4. Incluir análisis de impacto y recomendaciones.  
5. Revisar y archivar para referencia futura.

### 2.4) Herramientas / técnicas (si aplica)
- **SIEM (ELK Stack):**  
  - Elasticsearch: almacenamiento y búsqueda de logs.  
  - Logstash: ingestión y transformación de datos.  
  - Kibana: visualización de eventos y creación de dashboards.  

- **IDS (Snort):**  
  - Detección de intrusiones en la red.  
  - Análisis de tráfico y alertas ante actividad sospechosa.  

- **OSINT:**  
  - Buscadores avanzados (Google, DuckDuckGo, Shodan).  
  - Redes sociales y análisis de perfiles públicos.  
  - Metadatos de imágenes y documentos.  
  - Herramientas de agregación y correlación de información (theHarvester, Maltego).  

- **Documentación e informes:**  
  - Plantillas estructuradas para incidentes.  
  - Capturas de logs y evidencias.  
  - Checklists de procedimientos.  

- **Técnicas clave:**  
  - Correlación de eventos.  
  - Clasificación y priorización de incidentes.  
  - Monitorización continua.  
  - Análisis forense básico de logs y archivos.

### 2.5) Buenas prácticas y errores típicos
**Buenas prácticas:**  
- Documentar todos los incidentes con detalle, incluyendo evidencias y acciones tomadas.  
- Clasificar y priorizar incidentes según impacto y criticidad.  
- Mantener el SOC y las herramientas SIEM actualizadas y configuradas correctamente.  
- Revisar periódicamente logs y alertas, incluso con recursos limitados.  
- Aplicar principios de OSINT de forma ética y responsable.  
- Redactar informes claros, estructurados y con conclusiones justificadas.  
- Concienciar al equipo sobre riesgos de exposición digital y seguridad básica.  

**Errores típicos:**  
- Ignorar la documentación o dejarla incompleta.  
- Subestimar pequeños incidentes que pueden escalar.  
- Configurar alertas de forma genérica, generando ruido y falsas alarmas.  
- No revisar periódicamente los sistemas y logs.  
- Compartir información sensible sin control ni análisis previo.  
- Confundir OSINT pasivo con actividades intrusivas ilegales.  
- Informes técnicos poco claros, sin datos objetivos ni evidencia.

### 2.6) Glosario mínimo (términos y definiciones cortas)
- **Incidente de seguridad:** Evento que compromete la confidencialidad, integridad o disponibilidad.  
- **Taxonomía de incidentes:** Clasificación estructurada de incidentes según tipo e impacto.  
- **SOC (Security Operations Center):** Centro encargado de monitorizar y responder ante incidentes.  
- **SIEM (Security Information and Event Management):** Sistema que recopila, correlaciona y analiza logs, generando alertas.  
- **IDS (Intrusion Detection System):** Sistema que detecta actividad sospechosa o intrusiones en la red.  
- **OSINT (Open Source Intelligence):** Recopilación de información a partir de fuentes públicas.  
- **Evidencia digital:** Información recogida que sirve para analizar y documentar un incidente.  
- **Informe técnico:** Documento estructurado que describe un incidente, análisis y acciones tomadas.  
- **Fuerza bruta:** Intentos repetidos de acceder a un sistema probando múltiples contraseñas.  
- **Phishing:** Técnica de engaño para obtener información confidencial mediante suplantación.


## 3) (Opcional) Evidencias y recursos usados

### Evidencia 1
- Archivos: [evidencias](/evidencias/siemprueba.PNG) [evidencias](/evidencias/siemprueba.PNG)

- Qué demuestra: La correcta clasificación y priorización de distintos tipos de incidentes según su impacto y criticidad.
- Qué he aprendido: Cómo estructurar la información de los incidentes para facilitar la gestión y toma de decisiones, y la importancia de la taxonomía para estandarizar procesos en un SOC.

### Evidencia 2
- Archivo: `evidencias/02_siem_elk_snort.md`
- Qué demuestra: La instalación y configuración de un SIEM (ELK) y un IDS (Snort), así como la creación de alertas y la monitorización de eventos.
- Qué he aprendido: Cómo recopilar y analizar logs, correlacionar eventos y generar alertas útiles; además, la práctica me permitió entender mejor el flujo de trabajo dentro de un SOC y la relevancia de la documentación en cada paso.



## 4) Conclusión (cierre)
- 
