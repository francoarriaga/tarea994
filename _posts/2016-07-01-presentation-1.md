---
title: Unidad 2
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: INSTITUTO TECNOLÓGICO DE CANCÚN
   slide-data: |
     NOMBRE DEL ALUMNO: ARRIAGA PECH FRANCO MARTHELY.  
     NOMBRE DEL DOCENTE: DR. ISMAES JIMÉNEZ SÁNCHEZ.  
     NOMBRE DE LA MATERIA: SISTEMAS PROGRAMABLES.  
     TAREA: "REALIZAR UNA PRESENTACIÓN DE LA UNIDAD 2, CON MARKDOWN, USANDO https://slides.webjeda.com/ EN SU PROPIO REPOSITORIO DE SLIDES".  
     NOMBRE DE LA CARRERA: INGENIERÍA EN SISTEMAS COMPUTACIONALES.  
     GRADO: NOVENO SEMESTRE.
     
 - title: Slide 2
   slide-data: This is second slide

 - title: Slide 3
   slide-data: This is third slide
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}

