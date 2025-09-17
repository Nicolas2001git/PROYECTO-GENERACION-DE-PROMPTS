# 🧘 ZenPal — Fast Prompting en Acción

ZenPal es un proyecto académico desarrollado como entrega final del curso **Generación de Prompts con Inteligencia Artificial** en Coderhouse.  
Su objetivo es demostrar cómo el **Fast Prompting** puede aplicarse para crear un asistente digital que brinde **mensajes motivacionales** y **recordatorios de bienestar** de manera rápida, clara y accesible.  

> ⚠️ **Aviso importante:** ZenPal es un trabajo académico y demostrativo.  
> No reemplaza la ayuda psicológica real ni la atención profesional en salud mental.

---

## 🎯 Objetivos del Proyecto

- Demostrar el funcionamiento de **Fast Prompting** en una notebook interactiva.
- Generar **microintervenciones** (Texto → Texto) útiles para aliviar ansiedad, estrés o bloqueo.
- Crear **pósters motivacionales minimalistas** (Texto → Imagen) para refuerzo positivo.
- Optimizar el uso de prompts (claros, breves y con roles definidos) para reducir iteraciones y consumo de tokens.

---

## 🧩 El Problema

El estrés, la ansiedad y la falta de motivación afectan a muchas personas en su vida diaria.  
El acceso a apoyo profesional inmediato suele ser limitado, especialmente en contextos de estudio o trabajo remoto.  

ZenPal propone un **acompañamiento digital básico** que ofrece consejos simples y mensajes motivacionales como apoyo complementario y rápido.

---

## 💡 La Propuesta de Solución

### 🗨️ Texto → Texto (Microintervenciones)
- **Qué hace:** Brinda respuestas breves, empáticas y accionables (exactamente 2 pasos concretos).
- **Qué resuelve:** Ansiedad previa a exámenes, parálisis por análisis, bloqueos mentales.
- **Ejemplo de Prompt Usado:**
No puedo dormir porque mañana presento un informe importante. ¿Qué hago?

- **Resultado:**
Respira y prepara el terreno
Paso 1: Haz 5 respiraciones profundas, inhalando por la nariz y exhalando lentamente.
Paso 2: Deja todo preparado para mañana (ropa, materiales, despertador) para liberar tu mente y poder dormir tranquila. 🌙


- **Ejemplo de Prompt Usado:**
No sé qué puedo hacer porque rindo mañana y estoy muy estresado.

- **Resultado:**
Paso 1: Haz una pausa de 10 minutos lejos de la pantalla. Camina o estírate para soltar tensión física.
Paso 2: Repasa solo un tema clave y luego cierra los apuntes. Descansar te ayudará a recordar mejor mañana


- **Ejemplo de Prompt Usado:**
Me siento muy triste.
- **Resultado:**
Paso 1: Escribe en pocas palabras cómo te sientes y qué pudo causarlo.
Paso 2: Haz algo pequeño que te reconforte —escucha tu canción favorita, toma algo caliente o habla con alguien de confianza.


🎨 Texto → Imagen (Pósters Motivacionales)
Qué hace: Genera imágenes motivacionales minimalistas para refuerzo positivo y recordatorios visuales.

Qué resuelve: Baja adherencia a hábitos y falta de motivación sostenida.

Ejemplo de Prompt Usado: 

Póster motivacional minimalista con la frase "Un paso a la vez",
tipografía estilo manuscrito, colores pastel suaves (crema, durazno, celeste claro),
diseño centrado, fondo limpio, aspecto estético y moderno, sin objetos extra.

Imagen Generada: En archivo "imagenes"

⚡ Fast Prompting en Acción
Uso de roles (system, user) para delimitar el tono y la longitud de las respuestas.
Prompts cortos y claros, fáciles de versionar y ajustar.
Iteración rápida: optimización de tokens para reducir costo y tiempo de prueba.

⚙️ Herramientas y Tecnologías
Lenguaje: Python 3
Entorno: Jupyter Notebook / Google Colab
Modelos OpenAI: gpt-4o / gpt-4o-mini (texto) y gpt-image-1 (imágenes)
Bibliotecas: openai, IPython.display, json, base64

📂 Contenido del Repositorio
notebook/ZenPal_Demo_Clientes.ipynb → Notebook principal con la demo.
assets/images/ → Resultados visuales generados.
README.md → Este archivo.

