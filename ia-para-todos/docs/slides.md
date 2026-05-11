# Slides de presentación de la deploy talk *IA para todos*

En este archivo vas a encontrar el contenido que va haber en las diapositivas que se van a presentar en la deploy talk de IA Para Todos, una charla que busca ayudar a profesionales NO tech a crear un criterio en el uso de la IA, aprender algunas herramientas de IA, las limitaciones de la misma y como poder integrarlas en sus flujos de trabajo actuales.

A continuación te voy a dar una estructura de diapositiva de la siguiente manera

```
# Titulo de la diapositiva
Textos secundarios que acompañan la diapositiva, que tambien pueden ser una lista
- Elemento de lista 1
- Elemento de lista 2
- ...
```
> Comentarios: que deben ir en las diapositivas, que el publico no vera, pero que serviran de guía para la personas que presenta
> Notas IA: Estas notas son aclaratorias por diapositivas y que debe utilizar la IA para diagramar, diseñar la diapositiva en especifico.


## Diapositivas

### Diapositiva 1: Inicio
```
Deploy Talk - The Tribu
# IA para todos: herramientas reales para tu trabajo
Construye criterio y empieza a utilizar IA desde el Lunes.
Jorge Olarte
```

### Diapositiva 2: Intro
```
# Jorge Olarte
- Master en Ingeniería de Software, Universidad Pontificia de Salamanca, Madrid - España
- AI Engineering Specialization, ByteByteGo
- Docente en educación secundaria y universitaria — traduce lo complejo en algo accionable
- Fundador de The Tribu, la primera comunidad tech de la ciudad
```
> Notas IA: Aquí quiero que la diapositiva se enfoque la solidez en conocimientos técnicos del tutor, pero sobre todo, en que ha sido profesor en educación secundaria y universitaria, lo cual lo capacita para saber como traducir conceptos complejos en vainas faciles de entender.

### Diapositiva 3: Agenda
```
# ¿Qué veremos hoy?
01. Cómo funciona la IA
02. Limitaciones y riesgos que debes conocer
03. Herramientas disponibles y sus diferencias
04. Prompting efectivo - la habilidad que te diferencia
05. Técnicas avanzadas y errores comunes
06. Demo en vivo
07. El regalo
```
> Notas IA: en el punto 07, quiero que le pongas un emoji, y se vea diferencte, en ese punto es el lanzamiento del curso, es decir que alli es donde hare la venta a profundidad del curso.

### Diapositiva 4: Contexto
```
# Cómo probablemente te sientes ahora mismo
- Ves cómo la IA está cambiando al mundo MUY RÁPIDO
- Te preocupa tu futuro como profesional - ¿Me va a reemplazar la IA?
- Ves a colegas usando IA y no sabes por dónde empezar
- Mucho ruido y poca información clara
- ¡Por eso estás aquí y es el lugar correcto!
```
> Notas IA: En esta diapositiva el ultimo elemento de la lista debe verse diferente y que llame la atención

### Diapositiva 5: Contexto
```
# ¿Qué te vas a llevar hoy?
- Criterio profesional: Entiendes lo básico de la IA para tomar decisiones informadas
- Cómo funciona por dentro: Dejarás de creer que es magia, y empezaras a sacarle mejor provecho
- Tu punto de partida: Saldrás con herramientas concretas para integrar IA en tu trabajo HOY mismo
```

### Diapositiva 6: Fundamentos
```
# ¿Cómo funciona la IA realmente?
- Es como un loro muy sofisticado: predice la siguiente palabra a partir del contexto
- No es magia, ni "inteligencia" real - no puede pensar, ni sentir, ni entender
- No entiende la vida real, las emociones ni las situaciones humanas
- Problema de memoria a corto plazo: Los LLM/IA solo "recuerdan" lo que está en la conversación activa
```
> Comentarios: En esta diapositiva van haber dos momentos en los cuales se saldra de la presentación y nos moveremos a mostrar dos cosas: Se hara una demo de como la IA predice una palabra, ejemplo: Bogotá capital de Colombia, Madrid capital de España, Buenos Aires capital de..." y luego se mostrara la nube de etiquetas https://projector.tensorflow.org/. Tambien deja en las notas el link al tokenizer https://tiktokenizer.vercel.app/?model=cl100k_base en caso que se quiera explicar que es un token.
> Nota IA: Mirar la mandera de que el link a tensorflow quede disponible desde la diapositiva para que no olvidemos mostrar como se ve destras de escena.

### Diapositiva 7: Fundamentos
```
# Limitaciones que debes conocer
- No es una fuente de verdad, puede equivocarse con total CONFIANZA
- Fecha de corte: Después de cierto momento no sabe qué pasó en el mundo
- Alucinaciones: Si carece de información, INVENTA y lo hace con total seguridad
- No tiene memoria: Cada conversación empieza desde CERO.
- Pierde el hilo cuando hay documentos o conversaciones MUY EXTENSAS
```
> Notas IA: Mira la manera de incluir que su principal fortaleza a la vez es su mayor debilidad, es decir estan entrenadas para responder preguntas, no importa la manera. Lo que provoca alucinaciones

### Diapositiva 8: Fundamentos
```
# Seguridad e información privada
- Nunca compartas información sensible como contraseñas, datos de cliente, información confidencial de la empresa
- Dependiendo del plan y del proveedor, lo que envías puede usarse para entrenar nuevos modelos
- Tu empresa puede tener politicas especificas sobre el uso de la IA 
- Regla de oro: Si no lo publicarías en redes, no lo pongas en un prompt
```
> Notas IA: El ultimo item de la lista debe ser resaltado de alguna manera porque es el aprendizaje de la diapositiva

### Diapositiva 9: Herramientas
```
# Para los gustos, los colores
- ChatGPT: Muy bueno generando textos. Ampliamente adoptado, aunque todo en redes ya suena igual.
- Claude: Fuerte en razonamiento, análisis y código. Tiene funciones avanzadas como Claude Cowork, Claude Design, Claude Code.
- Gemini/Perplexity: Excelentes para busquedas en tiempo real y sintesis de información actualizada.
- Notebook LM: Ideal para investigar a profundidad. Crea tu propio contexto de conocimiento
Recomendación: empieza con 2 o máximo 3, úsalas con casos reales y aprende sus diferencias con tu propio criterio
```
> Notas IA: La recomendación debe ser mas pequeña y no tan importante como las herramientas que se estan mencionando en la diapositiva

### Diapositiva 10: Herramientas
```
Demo en vivo
# Explorando herramientas
- Similitudes y diferencias entre ChatGPT, Claude, Gemini
- Generar imagenes, cambiar entre modelos, buscar en la web
```
> Notas IA: La palabra Demo en vivo debe ser una pill encima del titulo de la diapositiva

### Diapositiva 11: Prompting
```
# ¿Qué hace la diferencia?
- Prompt vago: "Ayudame con un contrato"
- Prompt efectivo: "Actúa como abogado especializado en derecho comercial colombiano. Necesito revisar una cláusula de confidencialidad en un contrato de prestación de servicios. Identifica riesgos legales y sugiere mejoras manteniendo un lenguaje claro"
```
> Notas IA: Ambos prompts deben estar ubicados uno en frente del otro, es decir en dos columnas, el prompt vago debe ir en rojo indicando que es incorrecto y el promt efectivo en verde para indicar que es correcto.

### Diapositiva 12: Prompting
```
# Anatomía de un buen prompt
- Rol: ¿Quién quieres que sea la IA? "Actua como [experto X]"
- Contexto: ¿Qué necesita saber? "Estoy trabajando en [describe la situación]..."
- Tarea: ¿Qué debe hacer exactamente? "Necesito que [acción especifica]..."
- Formato: ¿Cómo quieres la respuesta? "Presenta los resultados [tabla - lista - resumen de X palabras]..."
- Límites: ¿Qué NO debe hacer? "No uses tecnicismos, máximo 200 palabras..."
```
> Notas IA: Presenta esta información de manera ordenada y entiende que son 3 cosas por cada item, el nombre, la pregunta y el ejemplo.

### Diapositiva 13: Prompting 
```
# Ejemplo: Sector tributario
- Antes: "Explica esta norma tributaria"
- Después: "Actúa como contador público especializado en impuestos colombianos. Explica el articulo 235-2 del Estatuto Tributario sobre la deducción de gastos, dame 3 ejemplos prácticos en empresas de servicios, e identifica errores comunes que generan glosas de la DIAN"
```
> Notas IA: Ambos prompts deben estar ubicados uno en frente del otro, es decir en dos columnas, el prompt vago debe ir en rojo indicando que es incorrecto y el promt efectivo en verde para indicar que es correcto.

### Diapositiva 14: Prompting 
```
# Ejemplo: Consultoría estratégica
- Antes: "Haz un analisis DOFA"
- Después: "Actua como consultor empresarial. Tengo una empresa de logística en Cartago con 25 empleados. Basándote en estos datos [adjuntar], crea un análisis DOFA enfocado en expansión regional. Prioriza factores de impacto y sugiere 3 acciones inmediatas para cada cuadrante"
```
> Notas IA: Ambos prompts deben estar ubicados uno en frente del otro, es decir en dos columnas, el prompt vago debe ir en rojo indicando que es incorrecto y el promt efectivo en verde para indicar que es correcto.

### Diapositiva 15: Técnicas avanzadas
```
# Ingeniería inversa del prompt
> ¿Qué prompt hubiera necesitado para generar está respuesta?
- Cuando encuentres un resultado excelente, pégaselo a la IA y hazle la pregunta
- La IA te mostrará la estructura exacta del prompt que habría generado ese resultado
- Resultado: Tienes un template replicable para ese tipo de tarea - sin empezar desde cero
```
> Notas IA: La pregunta debe ser manejada como una quote y debe resaltar sobre los otros elementos de la diapositiva

### Diapositiva 16: Técnicas avanzadas
```
# Errores más comunes
- Ser demasiado vago: "Ayudame con marketing" - sin contexto ni dirección
- Asumir que la IA conoce tu contexto: "Revisa el documento" - ¿cuál? ¿qué busco?
- No especificar el formato: recibes parrafos cuando esperabas una tabla
- Preguntas multiples en un solo prompt: Analiza + crea + sugiere -> una tarea a la vez
Aquí prima el criterio PROFESIONAL y eso la IA te va a seguir necesitando a ti
```
> Notas IA: Todos los textos de la diapositiva son importantes, sin embargo el aprendizaje sobre el criterio profesional es muy importante enmarcarlo o resaltarlo aqui.

### Diapositiva 17: Técnicas avanzadas
```
# Modo "razonamiento"
- Normalmente la IA adivina directo. En modo razonamiento se "habla a sí misma" paso a paso antes de responder — como mostrar el proceso en un examen
- ¿Cuando usarlo? 
-- Cuando no estes seguro del resultado que esperas
-- Lluvia de ideas
- Es más lento, pero produce respuestas mas cuidadas en tareas de razonamiento completo
```
> Nota IA: Agregar una imagen que pueda explicar algo del Chain-of-thought

### Diapositiva 18: Técnicas avanzadas
```
Demo en vivo
# NotebookLM
- Tu fuente de verdad: Carga documentos, PDF y articulos. Construye un contexto de conocimiento propio sobre cualquier tema
- Pregunta con profundidad: Haz preguntas especificas y obtén respuestas basadas únicamente en tus fuentes - sin alucinaciones
```
> Notas IA: La palabra Demo en vivo debe ser una pill encima del titulo de la diapositiva

### Diapositiva 19: Decisiones
```
# ¿Vale la pena pagar?
```
> Notas IA: En esta diapositiva intenta incluir de una manera organizada y simple la siguiente informacion que encuentras en la tabla

| Feature | ChatGPT Free | ChatGPT Go ($8) | Claude Free | Claude Pro ($17–20) | Gemini Free | Gemini AI Plus ($7.99) |
|---|---|---|---|---|---|---|
| **Modelo** | GPT-5.3 *(limitado)* | GPT-5.5 completo | Sonnet *(limitado)* | Sonnet + Opus | 3 Flash + var. 3.1 Pro | 3.1 Pro *(mayor acceso)* |
| **Chat básico** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Búsqueda web** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Carga de archivos** | ⚠️ pocos/día | ✅ más límite | ⚠️ pocos/día | ✅ más límite | ⚠️ pocos/día | ✅ más límite |
| **Generación de imágenes** | ⚠️ pocas/día | ✅ más límite | ❌ | ❌ | ⚠️ pocas/día | ✅ Nano Banana Pro |
| **Deep Research** | ❌ | ❌ | ❌ | ✅ | ⚠️ muy limitado | ✅ mayor acceso |
| **Integraciones apps** | GPT Store | GPT Store | ❌ | Excel, PPT, Word, Slack | ❌ | Gmail, Docs, Chrome |
| **Límite de mensajes** | ⚠️ baja en horas pico | ✅ más estable | ⚠️ límite diario | ✅ más límite | ⚠️ límite diario | ✅ más límite |

### Diapositiva 20: Demo
```
Demo en vivo
# La IA que trabaja contigo
- Como funciona Claude Cowork
```
> Notas IA: La palabra Demo en vivo debe ser una pill encima del titulo de la diapositiva

### Diapositiva 21: Transición
```
# Esto fue solo la superficie
- Lo que viste hoy
-- Cómo funciona la IA por dentro
-- Sus limites reales
-- Prompts que realmente funcionan
-- Flujos de trabajo con IA
- Lo que viene en el curso
-- Prompting avanzado para tu profesión
-- Uso eficiente de tokens
-- Stack de herramientas
-- Proyecto final aplicado a tu trabajo
```
> Notas IA: En dos columnas donde se vea la diferencia entre lo aprendido hoy y lo que van a aprender en el curso

### Diapositiva 22: Temario
```
# 4 semanas, 4 transformaciones
- Semana 1 · 30 mayo: Cómo funciona la IA y sus límites reales
- Semana 2 · 6 junio: Prompting avanzado para tu profesión
- Semana 3 · 13 junio: Flujos de trabajo con herramientas reales
- Semana 4 · 20 junio: Tu proyecto final aplicado a tu trabajo
```
> Nota IA: Cada semana debe verse como un bloque independiente con la fecha visible. Diseño limpio y progresivo, que transmita que hay un camino claro de principio a fin.

### Diapositiva 23: Beneficios
```
# El curso completo para profesionales no técnicos
- 4 sábados consecutivos
- 100% presencial · Universidad Cotecnova, Cartago
- 12 horas de práctica aplicada 
- Sin tareas obligatorias — todo se trabaja en clase
- 12 estudiantes maximo para mayor personalización del curso
- Certificado 
- Acceso a Claude Pro incluido
- Grupo privado en WhatsApp
- Materiales de por vida
- Networking con otros profesionales
```
> Nota IA: Pon aqui los beneficios de unirse al curso

### Diapositiva 24: Público objetivo
```
# ¿Es este curso para ti?
- Sí es para ti si...
-- Usas tu computadora todos los días en tu trabajo
-- Eres abogado, contador, administrador de empresas, emprendedor, etc.
-- Quieres ahorrar horas en tareas repetitivas
-- Quieres construir un criterio SOLIDO para decidir cuando usar la IA
- No es para ti si...
-- Ya programas o trabajas en desarrollo de software
-- Buscas un curso de machine learning o Python
-- Quieres solo teoría sin aplicación inmediata
-- No usas computadora regularmente en tu trabajo
```
> Nota IA: Dos columnas que se muestren las diferencias entre ambas columnas, y ademas eres libre de agregar algunos otros conceptos que ayuden a tomar la decisión a los asistentes a la charla

### Diapositiva 25: Precio
```
# Precio - Primera cohorte
🔥 Pioneros — $350.000 · 4 cupos · ahorras $250.000
💡 Early Bird — $425.000 · 5 cupos · ahorras $175.000
💼 Community — $490.000 · 3 cupos · ahorras $110.000
📋 Precio regular — $600.000

El precio sube automáticamente cada vez que se llena un nivel.
Primera clase: 30 de mayo — quedan X días para inscribirse.
¿No es lo que esperabas? Te devolvemos el 75% tras la primera clase.
```
> Nota IA: Mostrar los 4 niveles de precio de manera visual y clara. El nivel Pioneros debe destacar visualmente sobre los demás. La frase del precio escalonado y la fecha deben verse como un recordatorio de urgencia, no como presión. La garantía de devolución debe verse pequeña pero visible, como un mensaje de tranquilidad al pie de la diapositiva. La X en "quedan X días" debe actualizarse manualmente antes de cada charla.

### Diapositiva 26: Inscripción
```
# ¿Cómo inscribirse?
- Fechas de clase:
-- Clase 1: 30 de mayo
-- Clase 2: 6 de junio
-- Clase 3: 13 de junio
-- Clase 4: 20 de junio
Sábados de 9:00 AM a 12:00 PM
- Métodos de pago
-- Efectivo
-- Transferencia BreB 3052666114
-- Tarjeta de crédito con link de pago por Bold
```
> Nota IA: En esta diapositiva mirar como incluir el link para registrase al curso https://luma.com/fqs9rvj9

### Diapositiva 27: Cierre
```
# La IA no te va a reemplazar
Te va a reemplazar alguien que sí sabe usarla.
¿Listo para el siguiente nivel?
Inscríbete hoy en nuestro curso
Primera cohorte, Mayo - Junio 2026
12 cupos únicamente
```