---
title: Unidad 2
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: INSTITUTO TECNOLOGICO DE CANCUN 
   slide-data: |
     <ul style="font-size: 30px;">
       <li>NOMBRE DEL ALUMNO: ARRIAGA PECH FRANCO MARTHELY.</li>
       <li>NOMBRE DEL DOCENTE: DR. ISMAES JIMÉNEZ SÁNCHEZ.</li>
       <li>NOMBRE DE LA MATERIA: SISTEMAS PROGRAMABLES.</li>
       <li>TAREA: “REALIZAR UNA PRESENTACIÓN DE LA UNIDAD 2, CON MARKDOWN, USANDO https://slides.webjeda.com/ EN SU PROPIO REPOSITORIO DE            SLIDES”.</li>
       <li>NOMBRE DE LA CARRERA: INGENIERÍA EN SISTEMAS COMPUTACIONALES.</li>
       <li>GRADO: NOVENO SEMESTRE.</li>
     </ul>

 - title: ACTUADORES
   slide-data: |
     <h2>¿QUÉ SON LOS ACTUADORES?</h2>
     <p style="font-size: 20px;"> 
      Los actuadores son dispositivos que convierten una señal de control (normalmente eléctrica, neumática o hidráulica) en un        
      movimiento físico. Son esenciales en sistemas automáticos o controlados a distancia, ya que permiten ejecutar una acción mecánica 
      basada en una señal de comando.
     </p>
   
 - title: ACTUADORES ELECTTRICOS
   slide-data: |
      <h2>Tipos de Actuadores Eléctricos</h2>
      - **Actuadores rotativos**: Convierte la energía eléctrica en un movimiento giratorio. Se utilizan en aplicaciones como válvulas o mecanismos que requieren movimiento circular.  
  **Ejemplo**: Motores eléctricos (AC/DC).

- **Actuadores lineales**: Transforma la energía eléctrica en movimiento lineal, usados en sistemas que requieren desplazamientos en línea recta.  
  **Ejemplo**: Husillos de bolas, actuadores de pistón.

- **Actuadores paso a paso**: Permiten un control preciso de la posición mediante impulsos eléctricos. Se usan en aplicaciones que requieren movimientos discretos y controlables.  
  **Ejemplo**: Motores paso a paso.

- **Servomotores**: Combinan un motor eléctrico con un sistema de retroalimentación para controlar la posición, velocidad o par, usados en robótica y automatización.  
  **Ejemplo**: Servo de alta precisión en brazos robóticos.


 - title: Slide 3
   slide-data: This is third slide
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
