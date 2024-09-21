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
       <li>TAREA: “REALIZAR UNA PRESENTACIÓN DE LA UNIDAD 2, CON MARKDOWN, USANDO https://slides.webjeda.com/ EN SU PROPIO REPOSITORIO 
            DE SLIDES”.
       </li>
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
   
 - title: 
   slide-data: |
      <h3 style="font-size: 40px;" >Tipos de Actuadores Eléctricos</h3>
      <ul style="font-size: 20px;">
      <li>
      <strong>
              Actuadores rotativos
      </strong>
              : Convierte la energía eléctrica en un movimiento giratorio. Se utilizan en aplicaciones    
              como válvulas o mecanismos que requieren movimiento circular.
      <ul>
      <li><em>Ejemplo</em>: Motores eléctricos (AC/DC).</li>
      </ul>
      </li>
      <li>
      <strong>Actuadores lineales</strong>: Transforma la energía eléctrica en movimiento lineal, usados en sistemas que requieren 
      desplazamientos en línea recta.
      <ul>
      <li><em>Ejemplo</em>: Husillos de bolas, actuadores de pistón.</li>
      </ul>
      </li>
      <li>
      <strong>Actuadores paso a paso</strong>: Permiten un control preciso de la posición mediante impulsos eléctricos. Se usan en 
      aplicaciones que requieren movimientos discretos y controlables.
      <ul>
      <li><em>Ejemplo</em>: Motores paso a paso.</li>
      </ul>
      </li>
      <li>
      <strong>Servomotores</strong>: Combinan un motor eléctrico con un sistema de retroalimentación para controlar la posición, 
      velocidad o par, usados en robótica y automatización.
      <ul>
      <li><em>Ejemplo</em>: Servo de alta precisión en brazos robóticos.</li>
      </ul>
      </li>
      </ul>



 - title: 
   slide-data: |
     <h2 style="font-size: 40px;">Funcionamiento de los actuadores electricos</h2>
     <p style="font-size: 20px;">Los actuadores eléctricos convierten energía eléctrica en energía mecánica. El principio básico es:</p>
     <ul style="font-size: 20px;">
     <li>Corriente eléctrica fluye a través de un componente conductor (bobina o motor).
     </li>
     <li>El campo magnético genera una fuerza sobre el conductor, resultando en un movimiento.
     </li>
     <li>Dependiendo del tipo, este movimiento puede ser rotacional (motor) o lineal (actuador lineal).
     </li>
     </ul>
     <p style="font-size: 20px;">El control del actuador se realiza variando la magnitud de la corriente o la dirección, lo que cambia 
          el 
        sentido y la velocidad 
        del movimiento.
     </p>
     
 - title: 
   slide-data: |
       <h2 style="font-size: 40px;">Características de los actuadores electricos</h2>
       <ul style="font-size: 20px;">
       <li><strong>Precisión y control</strong>: Algunos modelos (como los servomotores y motores paso a paso) permiten un control 
           preciso sobre la posición y velocidad.
       </li>
       <li><strong>Fuerza o par</strong>: Varia dependiendo del tamaño y tipo. Los actuadores rotativos se evalúan en términos de torque 
             y los lineales en términos de fuerza de empuje.
       </li>
       <li><strong>Velocidad</strong>: Dependiendo del tipo de motor o actuador, algunos ofrecen velocidades muy altas (motores de 
               corriente continua) y otros más controladas (paso a paso).
       </li>
       <li><strong>Eficiencia</strong>: Suelen tener un consumo eficiente de energía, aunque depende de la aplicación y el control.
       </li>
       <li><strong>Durabilidad</strong>: Son robustos y tienen una larga vida útil, con bajo mantenimiento.
       </li>
       </ul>
 - title: 
   slide-data: |
      <h2 style="font-size: 40px;">Modo de comunicación de los actuadores electricos</h2>
      <p  style="font-size: 20px;">Los actuadores eléctricos pueden integrarse en sistemas de control mediante diferentes métodos de 
             comunicación:
      </p>
      <ul style="font-size: 20px;">
      <li><strong>Señales analógicas</strong>: 0-10V o 4-20mA para controlar la velocidad, posición o fuerza. Es común en sistemas de 
          control más simples.
      </li>
      <li><strong>Modbus</strong>: Un protocolo de comunicación industrial estándar que permite la comunicación en tiempo real entre el 
                actuador y el sistema de control.
      </li>
      <li><strong>CAN Bus (Controller Area Network)</strong>: Muy usado en la industria automotriz y robótica, es un protocolo robusto 
               para la transmisión de datos entre los actuadores y controladores.
      </li>
      <li><strong>Protocolo Ethernet/IP</strong>: Permite la comunicación a través de redes locales o industriales, facilitando la 
              integración de actuadores en sistemas de automatización complejos.
      </li>
      <li><strong>Control por pulsos</strong>: Motores paso a paso y servomotores se controlan mediante señales PWM (modulación por 
          ancho de pulso) para ajustes finos.
      </li>
      </ul>
      
 - title: 
   slide-data: |
       <h2 style="font-size: 40px;">Tipos de los actuadores mecanicos</h2>
       <ul style="font-size: 20px;">
       <li><strong>Resortes</strong>: Utilizan energía almacenada en la deformación de un resorte. Al liberar la energía, se genera 
           movimiento.
       <ul>
       <li><em>Ejemplo</em>: Actuadores de retorno por resorte en válvulas.
       </li>
       </ul>
       </li>
       <li><strong>Engranajes</strong>: Usan un sistema de ruedas dentadas para transmitir o amplificar el movimiento mecánico.
       <ul>
       <li><em>Ejemplo</em>: Sistemas de dirección asistida.
       </li>
       </ul>
       </li>
       <li><strong>Levas y cigüeñales</strong>: Transforman el movimiento rotativo en lineal, o viceversa.
       <ul>
       <li><em>Ejemplo</em>: Motores de combustión interna (cigüeñales para mover pistones).
       </li>
       </ul>
       </li>
       <li><strong>Poleas y correas</strong>: Transmiten movimiento entre dos ejes a través de una cinta o correa.
       <ul>
       <li><em>Ejemplo</em>: Sistemas de transmisión en motores.
       </li>
       </ul>
       </li>
       <li><strong>Husillos de bolas</strong>: Utilizan rodamientos de bolas para convertir el movimiento rotatorio en lineal con alta 
           precisión.
       <ul>
       <li><em>Ejemplo</em>: Máquinas CNC.
       </li>
       </ul>
       </li>
       </ul>
       
 - title: 
   slide-data: |
     <h2 style="font-size: 40px;">Funcionamiento de los actuadores mecanicos</h2>
     <p style="font-size: 20px;"> El funcionamiento de los actuadores mecánicos se basa en la transferencia y conversión de fuerzas a 
          través de sistemas mecánicos. 
          Esto puede implicar:
     </p>
     <ul>
     <li><strong>Compresión o tensión</strong>: En actuadores basados en resortes, la energía se almacena mediante la compresión o 
        extensión, y luego se libera para realizar un trabajo.
     </li>
     <li><strong>Rotación o deslizamiento</strong>: En sistemas de engranajes o levas, un eje rotativo genera un movimiento lineal o 
         controlado, transmitiendo fuerza a otras partes del sistema.</li>
     <li><strong>Desplazamiento lineal</strong>: En husillos de bolas, el movimiento giratorio del eje se convierte en un desplazamiento 
        lineal con gran precisión.
     </li>
     </ul>
     <p style="font-size: 20px;"> El sistema mecánico actúa de manera pasiva o reactiva a fuerzas físicas que se le aplican, y algunos 
        pueden almacenar energía (como los resortes) para liberarla en el momento adecuado.
     </p>
   
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
