--- 
name: frontend
description: Crea interfaces frontend distintivas y de calidad profesional con un diseño impecable. Usa esta habilidad cuando el usuario solicite crear componentes web, páginas, artefactos, pósteres o aplicaciones (por ejemplo, sitios web, páginas de destino, paneles de control, componentes React, diseños HTML/CSS o al estilizar y embellecer cualquier interfaz web). Genera código y diseño de interfaz creativos y pulidos que evitan la estética genérica de la IA.

Licencia: Consulta los términos completos en LICENSE.txt

---

Esta habilidad te guía en la creación de interfaces frontend distintivas y de calidad profesional que evitan la estética genérica de la IA. Implementa código funcional con una atención excepcional a los detalles estéticos y a las decisiones creativas.

El usuario proporciona los requisitos de frontend: un componente, página, aplicación o interfaz para desarrollar. Pueden incluir información sobre el propósito, el público objetivo o las limitaciones técnicas.

## Pensamiento de diseño

Antes de programar, comprende el contexto y define una estética clara:
Para crear una landing page efectiva que convierta visitantes en clientes, he diseñado un prompt basado en el método científico de ingeniería de prompts de **Google, IBM y Andrew Ng**, utilizando la fórmula **ROCIFR** (Rol, Objetivo, Contexto, Instrucciones, Formato y Restricciones).

Aquí tienes el prompt maestro que puedes copiar y pegar:

***

### Prompt para crear tu Landing Page



**Contexto del Proyecto:**
[cite_start]Crea una landing page de una sola sección (One-Page Presentation) para presentar el "Plan Integral de Gestión Agroecológica Chacra La Primavera" de la consultora **Agroinn Patagonia**[cite: 1, 3]. [cite_start]El objetivo es presentar una propuesta técnica que optimice la productividad mediante el manejo regenerativo y el diseño estratégico del agua[cite: 10, 12].

**Estilo Estético y UI:**
* **Referencia Visual:** El diseño debe ser idéntico en paleta de colores (verdes orgánicos, tonos tierra, blanco limpio) y tipografía al estilo de `https://v0-agro-inn-landing-page.vercel.app/`.
* **Imágenes:** Utiliza placeholders de alta calidad que evoquen el entorno de `https://www.instagram.com/casayague/` (paisajes de la Patagonia, mallines, ganadería regenerativa y diseño hidrológico).
* [cite_start]**Identidad:** Incluye en el encabezado el logo de Agroinn Patagonia (descrito como una montaña con hojas verdes y tonos tierra)[cite: 117].

**Estructura de Contenido (Basada estrictamente en el PDF): Propuesta Casa Yagüe-Host, Angus & Wines - Bodega.pdf**
1.  [cite_start]**Hero Section:** Título: "Plan Integral de Gestión Agroecológica - Chacra La Primavera"[cite: 3]. [cite_start]Subtítulo: "Optimización de productividad y rentabilidad mediante manejo regenerativo y diseño Keyline"[cite: 10].
2.  [cite_start]**Resumen Ejecutivo:** Breve bloque de texto destacando la resiliencia económica y la regeneración de procesos ecológicos[cite: 12, 13].
3.  **Pilares del Plan (Grid de 4 Tarjetas):**
    * [cite_start]**Gestión Administrativa:** Registro de stock con trazabilidad y planificación financiera sustentable[cite: 23, 24, 26].
    * [cite_start]**Manejo Ganadero Bovino:** Pastoreo rotativo, bienestar animal y selección genética adaptada[cite: 29, 31, 32].
    * [cite_start]**Recurso Forrajero:** Pasturas perennes, biodiversidad y sistemas silvopastoriles[cite: 38, 39, 41].
    * [cite_start]**Diseño Hidrológico (Keyline):** Control de escurrimiento, mejora de mallines y recarga del perfil del suelo[cite: 43, 44, 46, 65].
4.  [cite_start]**Escenarios Propuestos (Tabla Comparativa):** Presentar los dos escenarios de recría de terneros (40 vs 20 animales) para la temporada 26/27[cite: 125, 126].
5.  [cite_start]**Footer:** Información de contacto y logo de Agroinn Patagonia[cite: 117].

**Especificaciones Técnicas:**
* Usa **Tailwind CSS**.
* Implementa animaciones sutiles de entrada (fade-in) para las tarjetas de los pilares.
* Asegura que el diseño sea totalmente responsivo.

**Paleta de Colores:**
sitio de referencia https://v0-agro-inn-landing-page.vercel.app/
Elemento,Código Hex,Color,Uso Principal
Primario,#166534,Verde Bosque,"Logotipo, botones principales (CTA), iconos y títulos de sección (H2)."
Acento,#15803d,Verde Esmeralda,Estados hover (al pasar el mouse) y elementos destacados menores.
Fondo,#ffffff,Blanco Puro,Fondo principal de la sección Hero y áreas de lectura limpia.
Fondo Alterno,#f8fafc,Gris Nube,"Fondos de tarjetas de ""Pilares"" o secciones secundarias para dar profundidad."
Texto Títulos,#14532d,Verde Profundo,Títulos principales (H1) y frases de alto impacto visual.
Texto Cuerpo,#374151,Gris Carbón,"Párrafos, descripciones técnicas y detalles de los escenarios."
Bordes/Líneas,#e5e7eb,Gris Platino,Líneas divisorias en tablas de escenarios y bordes de tarjetas.

A continuación, te detallo la paleta y cómo se aplica en la interfaz del sitio:1. Colores Principales (Brand Colors)Verde Selva / Bosque (Primario): Es el color de mayor jerarquía. Se utiliza en el logotipo, botones de acción principal (como "Solicitar Presupuesto"), iconos de servicios y en los encabezados de las secciones.Verde Musgo / Oliva (Secundario): Se emplea para elementos de acento, fondos de tarjetas de servicios y estados hover (cuando pasas el ratón) en los menús, proporcionando una transición suave y natural.Dorado Mate / Ocre (Acento): Un color tierra que se usa de forma estratégica en detalles pequeños para resaltar palabras clave o íconos específicos, vinculando la marca con el concepto de "suelo" y "tierra".2. Colores de Superficie y FondoBlanco Crudo / Off-White: No es un blanco puro, sino un tono ligeramente cálido que sirve de fondo general para evitar la fatiga visual y mantener una estética orgánica.Gris Piedra Muy Claro: Se utiliza para diferenciar secciones (como el área de "Nuestros Proyectos" o el pie de página) del fondo principal, creando una separación visual limpia.3. Tipografía y TextosAntracita / Gris Oscuro: En lugar de negro absoluto, se usa un gris muy oscuro para los textos principales y párrafos. Esto suaviza el contraste sobre el fondo blanco y mejora la legibilidad en pantallas.Verde Oscuro Profundo: Reservado exclusivamente para títulos de gran tamaño ($H1$, $H2$) para reforzar la identidad visual desde el primer vistazo.Cómo se usan en la Landing Page:Contraste: Los botones resaltan con el verde más vibrante sobre fondos claros para dirigir la atención hacia el contacto (CTA).Jerarquía: Los títulos utilizan los tonos más oscuros de la paleta verde para denotar autoridad, mientras que el cuerpo de texto se mantiene en gris para ser neutro.Consistencia: El pie de página suele invertir la lógica, usando un fondo oscuro (verde bosque o antracita) con texto en blanco para cerrar la página con un bloque sólido.

---

4. Estructura de Archivos (RAÍZ ACTUAL):
Al ser una landing page, el código debe ser minimalista y respetar esta organización tomando como raíz la carpeta actual:

Plaintext
. (Raíz actual)
├── index.html          # Única página con todas las secciones y SEO Local
├── logo.jpeg           # Logo de referencia
├── /css
│   └── style.css       # Variables CSS, Layout de una sola página y Media Queries
├── /js
│   └── script.js       # Smooth scroll, menú móvil y validaciones
└── /images             # Fotos del Valle de Trevelin y del equipo

### Notas adicionales sobre el contenido extraído:
* [cite_start]**Objetivo Central:** El sitio debe enfatizar que el manejo del agua es el "rol central" de la propuesta[cite: 14].
* [cite_start]**Acciones Clave:** Si decides añadir una lista de tareas, recuerda incluir el monitoreo de arroyos y la ejecución de obras hídricas bajo curvas de nivel[cite: 110, 111].

### Recomendaciones adicionales para optimizar tu resultado:

*   **Proceso Iterativo:** Recuerda que el primer prompt es solo el comienzo. Si la respuesta es muy técnica, puedes pedirle a la IA: *"Simplifica el lenguaje para que un directivo no técnico lo entienda perfectamente"*.
*   **Técnica Few-Shot (Ejemplos):** Si tienes una landing page de la competencia que te guste o un estilo de redacción previo, añádelo al prompt diciendo: *"Usa este estilo como ejemplo: [pegar texto]"*. Las fuentes indican que mostrar es mejor que decir y que un ejemplo vale más que mil palabras.
*   **Meta-Prompting:** Si sientes que falta información, antes de ejecutar el prompt anterior, dile a la IA: *"Quiero crear una landing page para mi empresa de IA. Hazme las 10 preguntas más importantes que necesites saber sobre mi negocio para que el resultado sea perfecto"*.
Luego, implementa código funcional (HTML/CSS/JS, React, Vue, etc.) que sea:
- De calidad para producción y funcional
- Visualmente impactante y memorable
- Cohesivo con una estética clara
- Meticulosamente refinado en cada detalle

## Pautas de estética para el frontend

Enfócate en:
- **Tipografía**: Elige fuentes hermosas, únicas e interesantes. Evita fuentes genéricas como Arial e Inter; opta por fuentes distintivas que realcen la estética del frontend. Elige fuentes inesperadas y con carácter. Combina una fuente distintiva para títulos con una fuente refinada para el cuerpo del texto.

- **Color y tema**: Mantén una estética coherente. Usa variables CSS para mayor consistencia. Los colores dominantes con acentos marcados funcionan mejor que las paletas tímidas y uniformemente distribuidas.

- **Movimiento**: Usa animaciones para efectos y microinteracciones. Prioriza las soluciones solo con CSS para HTML. Usa la biblioteca Motion para React cuando esté disponible. Céntrate en los momentos de mayor impacto: una carga de página bien orquestada con revelaciones escalonadas (retraso de animación) genera más satisfacción que las microinteracciones dispersas. Utiliza efectos de desplazamiento y estados de desplazamiento que sorprendan.

- **Composición espacial**: Diseños inesperados. Asimetría. Superposición. Flujo diagonal. Elementos que rompen la cuadrícula. Espacio negativo generoso o densidad controlada.

- **Fondos y detalles visuales**: Crea atmósfera y profundidad en lugar de usar colores sólidos por defecto. Añade efectos contextuales y texturas que se ajusten a la estética general. Aplica formas creativas como mallas de degradado, texturas de ruido, patrones geométricos, transparencia por capas, sombras dramáticas, bordes decorativos, cursores personalizados y superposiciones de grano.

NUNCA uses estéticas genéricas generadas por IA, como familias de fuentes sobreutilizadas (Inter, Roboto, Arial, fuentes del sistema), esquemas de color clichés (en particular, degradados morados sobre fondos blancos), diseños y patrones de componentes predecibles, ni diseños repetitivos que carecen de carácter contextual.

Interpreta de forma creativa y toma decisiones inesperadas que se sientan genuinamente diseñadas para el contexto. Ningún diseño debe ser igual. Varía entre temas claros y oscuros, diferentes fuentes y estéticas. NUNCA recurras a opciones comunes (como Space Grotesk, por ejemplo) a lo largo de las generaciones.

**IMPORTANTE**: Adapta la complejidad de la implementación a la visión estética. Los diseños maximalistas requieren código elaborado con animaciones y efectos extensos. Los diseños minimalistas o refinados requieren sobriedad, precisión y una atención meticulosa al espaciado, la tipografía y los detalles sutiles. La elegancia reside en ejecutar bien la visión.

Recuerda: Claude es capaz de realizar un trabajo creativo extraordinario. No te contengas, demuestra lo que realmente se puede crear cuando se piensa de forma innovadora y se apuesta por una visión distintiva.
