# DIU25
Prácticas Diseño Interfaces de Usuario (Tema: Kerarqueo artesanía ) 

[Guiones de prácticas](GuionesPracticas/)

Grupo: DIU3.OSCUROS.  Curso: 2024/25 

Actualizado: 11/03/2025

Proyecto: 

**KeroReseñas**

Descripción: 

Nuestra propuesta consiste en rediseñar la web de **Kerarqueo** integrando un espacio interactivo de reseñas y experiencias llamado **KeroReseñas**, que actúa como un blog centrado en valoraciones reales de usuarios.

Este sistema permitirá a los visitantes consultar opiniones sobre productos y talleres, compartir sus vivencias tras participar en una experiencia, y filtrar contenido por intereses. Con ello buscamos aumentar la confianza, mejorar la navegación, y potenciar la conversión en reservas y compras dentro de la plataforma.

Logotipo: 

![Logo Kerarqueo](./P3/Kerarqueo_logo.jpg)


Miembros:
 * :bust_in_silhouette:  Jesús Reyes de Toro     :octocat:     
 * :bust_in_silhouette:  Ignacio Rojas Valenzuela     :octocat:

>>> Los equipos son de 2 personas. Identifícaros con el nombre del Grupo y los enlaces a los perfiles de GitHub de cada integrante

----- 


>>> Este documento es el esqueleto del Case Study que explica el proceso de desarrollo de las 5 prácticas de DIU. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. Elimine este tipo de texto / comentarios desde la práctica 1 conforme proceda a cada paso


# Proceso de Diseño 

<br>

## Paso 1. UX User & Desk Research & Analisis 



### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

Esta es la primera vez que realizamos un análisis de usabilidad en profundidad, por lo que el objetivo principal es aprender a aplicar metodologías de investigación UX mientras evaluamos la plataforma Kerarqueo. Esta plataforma está enfocada en la venta de productos artesanales sostenibles, conectando a artesanos con compradores interesados en el consumo responsable. Pero, para mejorar su alcance y eficacia, es necesario evaluar su experiencia de usuario (UX) y detectar posibles áreas de mejora en navegación, accesibilidad y diseño.

Para comprender mejor el contexto, primero realizaremos una investigación exploratoria sobre los estándares de usabilidad en plataformas similares. Se comparará Kerarqueo con Etsy y Amazon Handmade para identificar diferencias de UX y experiencia de compra. Además, recopilaremos datos directamente de usuarios a través de observaciones y encuestas, y un análisis de comportamiento del usuario mediante herramientas de navegación.

La estrategia de investigación también incluirá pruebas de accesibilidad para garantizar que la plataforma sea funcional en distintos dispositivos y distintos tipos de usuarios. Con los resultados, podremos proponer mejoras en la estructura del sitio, optimizar el flujo de compra y reforzar la confianza del usuario, asegurando que Kerarqueo ofrezca una experiencia de usuario más intuitiva y competitiva en el sector de la artesanía sostenible.


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

Para evaluar la usabilidad y experiencia de usuario de **Kerarqueo**, se ha realizado un análisis comparativo con dos plataformas similares: **Etsy** y **Amazon Handmade**. Ambas son referentes en el sector de la venta de productos artesanales y sostenibles, lo que nos permite identificar puntos fuertes y áreas de mejora en **Kerarqueo**.

El análisis se centró en aspectos clave como el modelo de negocio, accesibilidad, funcionalidad, usabilidad y experiencia de usuario. Se identificó que:

- **Etsy** destaca por su comunidad consolidada y herramientas de personalización para vendedores, aunque sus **altas comisiones** pueden ser una barrera.  
- **Amazon Handmade** aprovecha la infraestructura de Amazon, ofreciendo **alcance global** y un **sistema de compra eficiente**, pero con menos identidad artesanal y opciones de personalización para los vendedores.  
- **Kerarqueo**, aunque con un nicho bien definido en sostenibilidad, aún presenta **áreas de mejora** en términos de **navegación, accesibilidad y optimización móvil**.  

### Justificación de la Elección de Kerarqueo  

Se ha seleccionado **Kerarqueo** como objeto de estudio debido a su enfoque en la **sostenibilidad** y el **comercio artesanal**. A pesar de sus fortalezas, presenta desafíos en **experiencia de usuario (UX)**, especialmente en la **estructura de navegación** y el proceso de compra. Comparado con Etsy y Amazon Handmade, Kerarqueo tiene la oportunidad de diferenciarse aún más si optimiza su usabilidad y accesibilidad.
Este análisis nos permitirá definir estrategias para mejorar la plataforma, optimizar la conversión de usuarios en compradores y reforzar la competitividad de Kerarqueo en el mercado digital de productos sostenibles.

 


### 1.c Personas
![Método UX](img/Persona.png) 
-----



### Persona #1: Laura Rodríguez  
![Laura Rodríguez](P1/Laura%20Persona%20Foto.jpg)  

**Descripción:**  
Laura es una emprendedora de 32 años interesada en la artesanía sostenible. Busca plataformas donde pueda adquirir productos únicos hechos a mano y, a su vez, aprender sobre técnicas artesanales. Sin embargo, su experiencia en **Kerarqueo** ha sido desafiante debido a problemas de navegación y falta de información clara sobre los productos y artesanos.

### Persona #2: Javier Martín  
![Javier Martín](P1/Javier%20Persona%20Foto.jpg)  

**Descripción:**  
Javier, de 45 años, es un diseñador de interiores que valora la exclusividad y calidad de los productos artesanales. Busca objetos decorativos hechos a mano para sus proyectos, pero ha encontrado dificultades en **Kerarqueo** debido a una mala organización de categorías y filtros de búsqueda poco precisos.



### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

## Experiencia de Usuario en Kerarqueo

Para analizar la experiencia de usuario en **Kerarqueo**, hemos creado dos perfiles distintos con objetivos diferentes en la plataforma.

### Laura Fernández (Reserva de experiencia de ecoturismo)
Laura representa a los usuarios que buscan **experiencias sostenibles**. Su Journey Map muestra las dificultades en la **búsqueda y reserva**, destacando la falta de **filtros avanzados** y **procesos de pago más claros**. La optimización de estos aspectos mejoraría la conversión de visitantes en clientes.

📄 **[Ver Journey Map de Laura](P1/Laura%20Persona%20Journey%20Map.pdf)**

### Javier Gómez (Publicación de una experiencia de turismo rural)
Javier es un vendedor que busca **promocionar sus actividades**. Su Journey Map refleja problemas en la **creación y visibilidad de ofertas**, como la falta de **orientación para nuevos vendedores** y **métricas de rendimiento**. Mejorar la experiencia de los proveedores podría atraer más ofertas de calidad a la plataforma.

📄 **[Ver Journey Map de Javier](P1/Javier%20Persona%20Journey%20Map.pdf)**

### Conclusión
El análisis muestra que **Kerarqueo** necesita mejorar tanto la experiencia de los compradores como la de los vendedores. Implementar mejoras en **accesibilidad, navegación y procesos de pago/publicación** aumentaría la **usabilidad y competitividad** de la plataforma.

 


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

>>>  El objetivo es revisar la usabilidad del competidor seleccionado. Usamos un checklist de verificación. Tras usarlo, subelo a la carpeta P1/ Ofrece aquí un parrafo para:

- **Enlace al documento**: [Ver Usability Review](https://github.com/DIU3-OSCUROS/UX_CaseStudy-DIU3.OSCUROS/blob/master/P1/Usability-review-Kerarqueo.pdf)  
- **URL y Valoración numérica obtenida**: 55/100  
- **Comentario sobre la revisión**:

En términos generales, la usabilidad de Kerarqueo es aceptable, pero presenta áreas de mejora. Entre los puntos fuertes, destaca su diseño visual limpio y su propuesta enfocada en productos artesanales sostenibles. La navegación es intuitiva en la mayoría de las secciones, y las páginas de producto ofrecen información detallada.

Sin embargo, se han identificado problemas en la accesibilidad móvil y en la falta de filtros avanzados de búsqueda, lo que dificulta la exploración eficiente de los productos. Además, el proceso de compra podría ser más fluido, ya que no siempre queda claro cuándo se ha agregado un producto al carrito. También se recomienda mejorar el feedback visual en acciones clave y optimizar la estructura de la web para una experiencia de usuario más fluida y accesible.

A pesar de estas limitaciones, con algunos ajustes en usabilidad y navegación, la plataforma tiene potencial para ofrecer una experiencia más intuitiva y competitiva.




<br>

## Paso 2. UX Design  

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----
## 2.a Reframing / IDEACIÓN: Feedback Capture Grid + Empathy Map

Para comenzar el proceso de ideación, hemos realizado un **Feedback Capture Grid**, en el que recogemos los aspectos más relevantes observados en la experiencia de usuario sobre la web actual de Kerarqueo.

Este análisis incluye puntos positivos, críticas constructivas, preguntas surgidas durante la navegación y nuevas ideas que nos ayudan a replantear el diseño. El resultado nos ha servido para concretar nuestra **propuesta de valor**, que será el eje de la solución planteada:

> **Propuesta de valor:** Transformar el blog de Kerarqueo en un espacio activo de reseñas, donde los usuarios puedan compartir experiencias, consultar opiniones reales y filtrar contenido según intereses, con el objetivo de generar mayor confianza, interacción y conversión.

### 📌 Aspectos destacados del Feedback Capture Grid:
- **Interesante:** Buena identidad visual, estética artesanal atractiva, uso de imágenes potentes.
- **Críticas:** Menú desaparece al hacer scroll, falta de navegación clara, legibilidad pobre en móvil, el blog es estático y no permite interacción.
- **Preguntas:** ¿Dónde estoy dentro de la web? ¿Puedo dejar una reseña? ¿Existe un buscador por categorías?
- **Nuevas ideas:** Blog interactivo con reseñas valoradas, etiquetas temáticas, integración de experiencias de usuarios visibles desde el catálogo.

📄 Puedes consultar el documento completo en:
[P2/Feedback Capture Grid Kerarqueo.pdf](./P2/Feedback%20Capture%20Grid%20Kerarqueo.pdf)


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----
Propuesta de valor visual representada mediante un Scope Canvas, centrada en la integración de reseñas tipo blog para mejorar la confianza, la exploración y la conversión de usuarios en la web de Kerarqueo.

📄 [Ver Scope Canvas en PDF](./P2/Scope%20Canvas%20Kerarqueo.pdf)

Vista previa:

![Scope Canvas Kerarqueo](./P2/Scope%20Canvas%20Kearqueo.png)


### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

En esta sección se han definido dos flujos de tareas clave para nuestra web:

1. **Búsqueda de productos o experiencias**  
   Se analiza el recorrido del usuario desde el inicio hasta la visualización de un producto específico. Se contemplan casos con y sin resultados disponibles.

2. **Proceso de reserva**  
   Describe cómo el usuario realiza una reserva desde que accede a la web hasta que recibe el correo de confirmación, incluyendo validaciones de campos y mensajes de error.

Puedes consultar los diagramas completos en los siguientes enlaces:

📄 [Task Flow 1: Buscar experiencia o producto](P2/Taskflow1.pdf)  
📄 [Task Flow 2: Reservar experiencia](P2/Taskflow2.pdf)


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----
Hemos diseñado la arquitectura de la información de la plataforma **Kerarqueo**, estructurando de forma clara las pantallas principales y definiendo los términos clave que guiarán el diálogo con los usuarios.

#### 🗺️ Sitemap
A continuación se muestra el diagrama con la jerarquía de navegación del sitio:

![Sitemap Kerarqueo](P2/SiteMap%20Kerarqueo.png)

#### 📄 User Map y Labelling
Incluye un análisis por perfiles de usuario (Laura y Javier), así como una tabla con los términos principales utilizados en la interfaz, evitando el spanglish y asociando iconos claros. Esto mejora la comprensión de la plataforma y la experiencia del usuario.

📎 [Ver documento completo en PDF](P2/User%20Map%20y%20labelling.pdf)

### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

En esta fase del prototipo hemos realizado una primera versión **Lo-Fi en papel** de las pantallas principales del sitio web de **Kerarqueo**, centradas en las funcionalidades clave: navegación, catálogo de productos, reservas, cursos, contacto y sistema de reseñas tipo blog.

Los wireframes propuestos permiten visualizar la estructura de la interfaz y la jerarquía de los elementos, lo que ha servido como base para el posterior diseño digital en Figma.

📄 [Ver documento completo de wireframes (PDF)](P2/WireframesDIU.pdf)

#### 📌 Pantallas incluidas en los wireframes:
- **Inicio:** navegación principal, acceso directo a catálogo, cursos y KeroBlog.
- **Catálogo:** filtros por categoría (Ibérica, Romana), ordenación por precio o nombre.
- **Ficha de producto o curso:** imagen, descripción, precio, botón de reservar o comprar.
- **Sistema de reseñas (KeroReseñas):** opiniones visibles debajo del producto o curso.
- **Formulario de contacto:** nombre, email y mensaje.
- **Carrito de compra:** listado de productos, ajustes de cantidad, botón de compra final.
- **Login / Crear cuenta:** formulario de inicio de sesión y registro para ser "KeroUsuario".

Además, por si fuera necesario, también se incluye el documento con los **primeros bocetos a mano** que fueron validados por el profesor antes de desarrollar los wireframes finales en Figma:

📝 [Bocetos iniciales a mano (versión sucia)](P2/SUCIO%20a%20mano%20Bocetos.pdf)

Estos bocetos sirvieron como punto de partida para validar la propuesta y pasar al prototipado digital.
<br>

## Paso 3. Mi UX-Case Study (diseño)



### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

Este es el moodboard para nuestro proyecto **Kerarqueo**, el cual recoge los principales aspectos visuales y estratégicos de nuestra propuesta:

- Nuestra estrategia de marca: conectar lo artesanal con lo digital mediante una experiencia de compra basada en la confianza, la historia y la estética del trabajo hecho a mano.
  
- Nuestro logotipo final: una vasija inspirada en cerámica ibérica, con un diseño minimalista y cálido.
  
- El eslogan: *“Descubre historias que se cuecen a fuego lento”*, transmitiendo calidez y cercanía, vinculando los productos con la experiencia personal de quienes los crean.
  
- Paleta de colores:
Nuestra paleta combina tonos terrosos que evocan lo natural y lo auténtico.  
El marrón arcilla (`#9C5745`) y el gris piedra (`#6E6658`) aportan calidez y sobriedad,  
mientras que el beige claro (`#D6C2A0`) y el gris neutro (`#B8B8B8`) equilibran el diseño  
con un aire limpio y contemporáneo, reflejando el espíritu artesanal de Kerarqueo.

-  `#9C5745` Marrón arcilla  
-  `#6E6658` Gris piedra  
-  `#B8B8B8` Gris neutro  
-  `#D6C2A0` Beige claro
-  `#83930E` Verde Oliva

- Tipografías:
  - **Playfair Display**, para títulos: elegante, clásica, transmite tradición.
  - **Inter**, para texto: limpia, moderna, mejora la legibilidad y contrasta con la anterior.
  - **Roboto**, para footer.
    
- Imágenes: seleccionadas para reforzar la estética cálida, artesanal y humana del proyecto, con escenas de alfarería, talleres y personas creando o disfrutando productos cerámicos.

📄 [Ver Moodboard en PDF](./P3/Kerarqueo_Moodboard25.pdf)

![Moodboard Kerarqueo](./P3/Kerarqueo_Moodboard25.png)

Estas decisiones visuales están pensadas para usarse de forma coherente en todos los elementos visuales del proyecto (redes sociales, web, branding físico, etc.), y podrían reutilizarse como cabecera de Instagram o banners de comunicación.


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

📄 [Ver Landing Page en PDF](./P3/Kerarqueo_Landingpage.pdf)

Vista previa:

![Landing Page Kerarqueo](./P3/Kerarqueo_Landingpage.jpg)

---

La Landing Page del proyecto **Kerarqueo** está diseñada para dar una primera impresión atractiva, visual y coherente con el moodboard definido previamente. Hemos aplicado la estética artesanal, cálida y natural basada en nuestra propuesta de valor: acercar la cerámica tradicional a cualquier usuario, de forma presencial o digital.

**Elementos incluidos:**

- 🧩 **Título y subtítulo** motivadores: invitan al usuario a crear sus propias piezas y disfrutar del proceso creativo.
- 🎨 **Imágenes representativas**: distribuidas en secciones clave (comunidad, conexión, tradición), transmiten la esencia del proyecto con fotografías cálidas e inspiradoras generadas específicamente.
- ✅ **Beneficios destacados**: se explican tres aspectos clave del servicio: aprender en comunidad, sentir la conexión con el barro, y reconectar con la tradición.
- 📱 **Call to Action (CTA)** claro: un botón principal que invita a descargar la app.

Este diseño servirá como referencia visual para la web o como cabecera promocional en redes sociales (por ejemplo, Instagram o newsletters).



### 3.c Guidelines
![Método UX](img/guidelines.png) 
----
📄 [Ver Kerarqueo Guidelines en PDF](./P3/Kerarqueo_Guidelines.pdf)

Este documento recoge el estudio de los **UI Guidelines** y patrones de diseño utilizados en el prototipo móvil de Kerarqueo. Se ha seguido el sistema **Google Material Design 3**, utilizando su plugin oficial en Figma, lo que nos ha permitido aplicar componentes consistentes, accesibles y visualmente acordes a nuestra identidad de marca.

En el documento se incluyen:
- Paleta de colores cálidos inspirados en materiales naturales.
- Tipografías utilizadas (Playfair Display, Inter y Roboto).
- Componentes UI implementados: onboarding, menús, carruseles, formularios, carrito, sección “about”, etc.
- Elementos adicionales: mapa, reseñas, etiquetas, chat flotante, scroll y switches.


### 3.d Mockup
![Método UX](img/mockup.png) 
----

📄 [Ver Layout Hi-Fi en PDF](./P3/LayoutHIFI.pdf)  
📎 [Descargar archivo Figma Kerarqueo](./P3/Kerarqueo.fig)

Se ha diseñado un mockup interactivo adaptado a dispositivos móviles, siguiendo los patrones de Material Design 3.  
Incluye pantallas clave como onboarding, login, menú inferior, carrousels, formularios, cards de producto y carrito.  
Los componentes fueron construidos con el plugin oficial de Material 3 en Figma, aplicando nuestra paleta de colores y tipografías.




### 3.e ¿My UX-Case Study?
![Método UX](img/caseStudy.png) 
-----

El prototipo completo y navegable puede consultarse en Figma:

🔗 [Ver prototipo interactivo en Figma](https://www.figma.com/proto/NlA3BbSNn9fqJOMWUlxC2T/Kerarqueo?node-id=0-1&t=Fb8nlqdH0l3XABAt-1) <br>
📱 [Ver bocetos de Figma (Kerarqueo)](https://www.figma.com/design/NlA3BbSNn9fqJOMWUlxC2T/Kerarqueo?node-id=0-1&t=0NahN5nC1YKJm5HH-1)

También se incluye el archivo `.fig` descargable en la carpeta `/P3`:

📎 [Descargar archivo Figma](./P3/Kerarqueo.fig)

<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




