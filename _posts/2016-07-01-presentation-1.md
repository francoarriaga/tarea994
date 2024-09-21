---
title: Unidad 2
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: INSTITUTO TECNOLOGICO DE CANCUN 
   slide-data: |
     <ol style="font-size: 30px;">
       <li>NOMBRE DEL ALUMNO: ARRIAGA PECH FRANCO MARTHELY.</li>
       <li>NOMBRE DEL DOCENTE: DR. ISMAES JIMÉNEZ SÁNCHEZ.</li>
       <li>NOMBRE DE LA MATERIA: SISTEMAS PROGRAMABLES.</li>
       <li>TAREA: “REALIZAR UNA PRESENTACIÓN DE LA UNIDAD 2, CON MARKDOWN, USANDO https://slides.webjeda.com/ EN SU PROPIO REPOSITORIO DE            SLIDES”.</li>
       <li>NOMBRE DE LA CARRERA: INGENIERÍA EN SISTEMAS COMPUTACIONALES.</li>
       <li>GRADO: NOVENO SEMESTRE.</li>
     </ol>
     
 - title: Slide 2
   slide-data: This iS ME

 - title: Slide 3
   slide-data: This is third slide
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
