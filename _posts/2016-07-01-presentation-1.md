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
       <li>NOMBRE DEL DOCENTE: DR. ISMAEL JIMÉNEZ SÁNCHEZ.</li> 
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
     <img src="../images/aelectrico1.png" alt="Actuador Rotativo" style="width: 60px; margin: auto;">

     
 - title: 
   slide-data: |
      <h2 style="font-size: 60px;"> Actuadores Eléctricos</h2>
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
       <h2 style="font-size: 60px;"> Actuadores Mecánicos</h2>
       <h2 style="font-size: 40px;">Tipos de los actuadores mecánicos</h2>
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
     <ul style="font-size: 20px;">
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
     
 - title: 
   slide-data: |
       <h2 style="font-size: 40px;">Caracteristicas de los actuadores mecanicos</h2>
       <ul style="font-size: 20px;">
       <li><strong>Simples y robustos</strong>: Tienen diseños mecánicos que son generalmente más simples y duraderos que los actuadores 
            eléctricos o neumáticos.
       </li>
       <li><strong>Bajo mantenimiento</strong>: En muchas aplicaciones, requieren poco mantenimiento comparado con los actuadores 
              hidráulicos o eléctricos, debido a la simplicidad de sus componentes.
       </li>
       <li><strong>Almacenamiento de energía</strong>: Actuadores como los resortes pueden almacenar energía y liberarla para generar 
           movimiento en situaciones donde no hay suministro continuo de energía.
       </li>
       <li><strong>Precisión</strong>: Los actuadores mecánicos como los husillos de bolas ofrecen una alta precisión en movimientos 
            lineales y en máquinas de control numérico (CNC).
       </li>
       <li><strong>Capacidad de carga</strong>: Algunos actuadores mecánicos, como los engranajes y husillos, pueden soportar cargas 
          pesadas con mayor eficiencia que otros tipos de actuadores.
       </li>
       </ul>
 - title: 
   slide-data: |
      <h2 style="font-size: 40px;">Modo de comunicación de los actuadores mecanicos</h2>
      <p style="font-size: 20px;"> A diferencia de los actuadores eléctricos, los actuadores mecánicos en sí mismos no tienen modos de 
           comunicación directa, ya 
           que son dispositivos pasivos. Sin embargo, pueden ser integrados en sistemas de control a través de sensores o controles 
            adicionales. Algunos modos de integración son:
      </p>
      <ul style="font-size: 20px;">
      <li><strong>Señales de posición</strong>: Sensores de posición (como encoders o potenciómetros) se usan para medir la posición del 
            actuador y enviar datos al sistema de control.
      </li>
      <li><strong>Sensores de fuerza o presión</strong>: Detectan la cantidad de fuerza que se está aplicando en un sistema mecánico 
           para ajustar el movimiento o la acción.
      </li>
      <li><strong>Acoplamiento con actuadores eléctricos</strong>: En sistemas híbridos, el actuador mecánico puede estar conectado a un 
        actuador eléctrico que envía señales de control al sistema general.
      </li>
      <li><strong>Control manual</strong>: En algunos casos, los actuadores mecánicos pueden ser operados manualmente mediante palancas 
            o pedales.
      </li>
      </ul>
 - title: 
   slide-data: |
      <h2 style="font-size: 60px;"> Actuadores Hidráulicos</h2>
      <h2 style="font-size: 40px;">Tipos de los actuadores hidráulicos</h2>
      <p style="font-size: 20px;">Los actuadores hidráulicos utilizan un fluido bajo presión para generar movimiento mecánico. Los 
          principales tipos son:
      </p>
      <ul style="font-size: 20px;">
      <li><strong>Cilindros hidráulicos (actuadores lineales)</strong>: Convierte la energía hidráulica en movimiento lineal. Se 
            utilizan en aplicaciones donde se requiere empujar o tirar cargas pesadas.
      <ul>
      <li><em>Ejemplo</em>: Maquinaria de construcción (excavadoras, grúas).
      </li>
      </ul>
      </li>
      <li><strong>Motores hidráulicos (actuadores rotativos)</strong>: Convierte la energía hidráulica en movimiento rotatorio. Se 
             emplean para rotar componentes en sistemas de alto torque.
      <ul>
      <li><em>Ejemplo</em>: Sistemas de dirección asistida o maquinaria pesada que necesita rotar componentes.
      </li>
      </ul>
      </li>
      </ul>
 - title: 
   slide-data: |
      <h2 style="font-size: 40px;">Funcionamiento de los actuadores hidraulicos</h2>
      <p style="font-size: 20px;">El funcionamiento de los actuadores hidráulicos se basa en la Ley de Pascal, que establece que la 
            presión aplicada a un fluido 
              en un sistema cerrado se transmite de manera uniforme en todas las direcciones.
      </p>
      <p style="font-size: 20px;">Proceso básico: </p>
      <ul style="font-size: 20px;">
      <li><strong>Generación de presión</strong>: Una bomba hidráulica genera presión sobre un fluido (generalmente aceite), que circula 
          a través de un sistema de tuberías.
      </li>
      <li><strong>Movimiento</strong>: Este fluido a alta presión empuja un pistón dentro de un cilindro o un mecanismo rotativo en el 
        caso de los motores, generando movimiento.
      </li>
      <li><strong>Control</strong>: Válvulas y reguladores ajustan la cantidad de fluido y la presión, controlando la velocidad y fuerza 
          del actuador.
      </li>
      </ul>
 - title: 
   slide-data: |
       <h2 style="font-size: 40px;">Caracteristicas de los actuadores hidraulicos</h2>
       <ul style="font-size: 20px;">
       <li><strong>Alta fuerza y torque</strong>: Los actuadores hidráulicos pueden generar mucha más fuerza y torque que los actuadores 
           eléctricos o neumáticos del mismo tamaño.
       </li>
       <li><strong>Control preciso de velocidad y fuerza</strong>: Mediante válvulas reguladoras y otros controles, es posible ajustar 
            con precisión la velocidad y la fuerza que ejerce el actuador.
       </li>
       <li><strong>Capacidad de trabajar con grandes cargas</strong>: Los sistemas hidráulicos son ideales para mover o levantar cargas 
            pesadas. Por ejemplo, se utilizan en maquinaria industrial, equipos de construcción y aeronaves.
       </li>
       <li><strong>Compactos y potentes</strong>: Proporcionan una gran cantidad de fuerza en un espacio relativamente pequeño, lo que 
           los hace útiles en espacios reducidos.
       </li>
       <li><strong>Robustos</strong>: Tienen una buena resistencia al desgaste y una larga vida útil, incluso en condiciones difíciles o 
         entornos de trabajo extremos.
       </li>
       <li><strong>Requieren mantenimiento regular</strong>: Debido al uso de fluidos, es importante mantener los sistemas hidráulicos 
           libres de fugas y contaminantes, además de controlar la temperatura del fluido.
       </li>
       </ul>
 - title: 
   slide-data: |
       <h2 style="font-size: 40px;">Modo de comunicación de los actuadores hidraulicos</h2>
       <p style="font-size: 20px;"> Aunque los actuadores hidráulicos en sí mismos no tienen capacidad de comunicación, se utilizan 
            junto con sistemas de control 
             que permiten monitorear y ajustar su funcionamiento. Los modos más comunes son:
       </p>
       <ul style="font-size: 20px;">
       <li><strong>Señales de posición</strong>: Se usan sensores de posición como potenciómetros, encoders o transductores de 
            desplazamiento lineal para monitorear la posición del pistón en un cilindro.
       </li>
       <li><strong>Sensores de presión</strong>: Detectan la presión del fluido hidráulico para controlar la fuerza aplicada y ajustar 
          el rendimiento del sistema.
       </li>
       <li><strong>Control de flujo</strong>: Válvulas de control proporcionan ajustes precisos al flujo del fluido, regulando la 
          velocidad y la fuerza del actuador.
       </li>
       <li><strong>Protocolo CAN Bus</strong>: En sistemas industriales más avanzados, los actuadores hidráulicos pueden estar 
          conectados a una red CAN Bus (Controller Area Network), que permite la comunicación con un controlador o PLC (Controlador 
           Lógico Programable).
       </li>
       <li><strong>Sistemas de retroalimentación</strong>: Algunos actuadores hidráulicos están equipados con sistemas de 
           retroalimentación de bucle cerrado, donde la información sobre la posición y presión del actuador se envía continuamente al 
          controlador para ajustar su funcionamiento en tiempo real.
        </li>
       <li><strong>Integración con sistemas electrónicos</strong>: Los actuadores hidráulicos se combinan con sistemas electrónicos para 
         proporcionar automatización avanzada. Esto incluye la posibilidad de integrarlos en sistemas controlados por PLCs o SCADA, 
           donde se puede monitorear y ajustar el funcionamiento del actuador remotamente.
       </li>
       </ul>

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
