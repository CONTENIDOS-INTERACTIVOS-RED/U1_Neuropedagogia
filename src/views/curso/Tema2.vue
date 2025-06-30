<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Áreas motoras, áreas del lenguaje, áreas de la visión, áreas de escritura, áreas cerebrales'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-5 A continuación, realizaremos un recorrido por diferentes áreas.

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Áreas motoras
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5
        .row.mb-5
          .col-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/1.svg", data-aos="zoom-in")
          .col-lg-10
            p(data-aos="fade-left") Para Velayos y Diéguez (2015), el sistema motor es el conjunto de estructuras del sistema nervioso, encargadas de coordinar y ejecutar los movimientos del cuerpo. Este sistema permite desde acciones voluntarias como caminar y escribir, hasta funciones automáticas como la respiración y los reflejos.
            P El sistema motor se divide en dos partes principales:
      
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-6.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/2.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Sistema motor voluntario
                p.mb-0 Está controlado por el cerebro y permite movimientos precisos y coordinados. Involucra la corteza motora, el cerebelo y los ganglios basales, que trabajan juntos para planificar y ejecutar los movimientos.
          .col-lg-6.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/3.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Sistema motor involuntario
                p.mb-0 Se encarga de funciones automáticas como el latido del corazón y la digestión. Incluye el sistema nervioso autónomo, que regula respuestas involuntarias del cuerpo, sin necesidad de un control consciente.
    
    .row.mb-5
      .col-lg-5.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/4.png", data-aos="zoom-in")
      .col-lg-7.order-lg-1
        .bg-color-2.p-4.mb-3(data-aos="fade-left")
          p.mb-0 Para que el sistema motor funcione correctamente, las señales nerviosas deben viajar desde el cerebro y la médula espinal, hasta los músculos. Este proceso ocurre a través de vías motoras, que pueden ser descendentes (del cerebro a los músculos) o ascendentes (de los músculos al cerebro para recibir información sensorial).
        p(data-aos="fade-left") El sistema motor también involucra diferentes tipos de neuronas:
    
    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/5.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Neuronas motoras superiores
              p.mb-0 Ubicadas en la corteza cerebral, que envían señales a la médula espinal.

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/6.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Neuronas motoras inferiores
              p.mb-0 Que conectan la médula espinal con los músculos y ejecutan el movimiento.
    
    p.mb-5 Además, el cerebelo y los ganglios basales, desempeñan un papel clave en la coordinación y ajuste de los movimientos, asegurando que sean fluidos y precisos. Las alteraciones en el sistema motor pueden provocar trastornos como el Parkinson, la esclerosis múltiple o la parálisis cerebral, afectando la movilidad y la coordinación.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-5.tarjeta.p-4.h-100(data-aos="fade-left")
          p(data-aos="fade-left") Como lo pudimos observar, el sistema motor es el conjunto de estructuras del sistema nervioso, encargadas de coordinar y ejecutar los movimientos del cuerpo; mientras que las áreas motoras del cerebro son regiones específicas de la corteza cerebral que controlan estos movimientos.
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/7.png" data-aos="zoom-in")
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-8.tarjeta.p-4.h-100(data-aos="fade-left")
          p(data-aos="fade-left") La corteza cerebral, es la capa externa y altamente desarrollada del cerebro en los humanos y otros mamíferos. Es la estructura más grande del cerebro y se localiza en su superficie. La corteza cerebral es fundamental para diversas funciones cognitivas complejas, como la percepción sensorial, la atención, la conciencia, la memoria, el pensamiento, el lenguaje y la toma de decisiones.
    
    p.mb-5 Se divide en cuatro lóbulos principales: frontal, parietal, temporal y occipital. Cada lóbulo tiene funciones específicas, conozcamos las de los lóbulos frontal y temporal:

    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/8.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Lóbulo frontal
              p.mb-0 Está relacionado con el pensamiento abstracto, la planificación y la toma de decisiones.

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-1.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Lóbulo temporal
              p.mb-0 Se enfoca en la percepción auditiva y la memoria a largo plazo.
    
    .row.justify-content-center.align-items-center.bg-color-2.bordes.p-4.py-lg-0.px-lg-4.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-10(data-aos="fade-left").mb-3.mb-lg-0
            p En conjunto, la corteza cerebral regula la mayoría de las funciones cognitivas del cerebro.
            p.mb-0 Está compuesta por seis capas diferentes de tejido neuronal, cada una con especializaciones funcionales y orígenes evolutivos diferentes. Estas capas son: molecular, granular externa, piramidal externa, granular interna, piramidal interna y multiforme.

          .col-lg-2(data-aos="zoom-in")
            img.img-fluid(src='@/assets/curso/tema2/10.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/11.png", data-aos="zoom-in")
      .col-lg-7
        .bg-color-11.p-5(data-aos="fade-left").text-white
          p La corteza motora abarca todas las áreas de la corteza cerebral, que participan en la planificación, control y ejecución de los movimientos corporales.
          p.mb-0 Incluye la corteza motora primaria, que controla directamente los movimientos voluntarios, así como otras regiones que ayudan en la organización y control de la acción motora, como la corteza premotora, la corteza suplementaria motora y la corteza parietal posterior.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/12.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") Colabora estrechamente con otras áreas del cerebro, como el cerebelo, los ganglios basales y la médula espinal, para coordinar y controlar los movimientos.
    
        .bg-color-12.bordes.p-4(data-aos="fade-left")
          p.mb-0 Las vías nerviosas que conectan la corteza motora con estas regiones, son esenciales para el funcionamiento motor, y cualquier interrupción en estas conexiones puede llevar a trastornos del movimiento.
        .bg-color-5.p-4(data-aos="fade-left")
          p Se localiza en la parte posterior del lóbulo frontal, justo delante de la corteza somatosensorial y, en cada hemisferio se pueden identificar las siguientes partes:
          ul.lista-ul--color
            li.mb-0.d-flex
              i.far.fa-arrow-alt-circle-right
              p.mb-0 <b>Área motora</b>: equivalente a un área sensorial primaria.
            li.mb-0.d-flex
              i.far.fa-arrow-alt-circle-right
              p.mb-0 <b>Áreas premotoras</b>: equivalente a un área de asociación unimodal, que incluye dos zonas: el área premotora y el área motora suplementaria.
    
    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.order-2
            h2.mb-4(data-aos="flip-up") Área motora primaria y áreas premotoras
            p.mb-4(data-aos="fade-right") En el PDF <b>Área motora primaria y áreas premotoras</b>, se describe el papel de estas regiones corticales en la coordinación precisa de nuestras acciones, desde tareas simples hasta secuencias complejas que integran la percepción y la motricidad. Este estudio permite analizar cómo el cerebro estructura los comandos motores y cómo las alteraciones en estas zonas afectan las habilidades adquiridas.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_4.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Área motora primaria y áreas premotoras.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/13.png', alt='')
    
    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] Áreas del lenguaje
    
    p.mb-5 Los procesos en el cerebro, desempeñan un papel esencial en la regulación de nuestras actividades diarias. Existen diversas regiones cerebrales que organizan las habilidades y actividades lingüísticas necesarias para la comunicación.

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/14.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-8.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/15.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El lenguaje es una capacidad esencial en los seres humanos y se cree que está vinculado a varias áreas del cerebro. Esta función está muy lateralizada: en la mayoría de las personas diestras y alrededor del 85 % de las zurdas, las áreas responsables del lenguaje se localizan en el hemisferio izquierdo, conocido como el hemisferio dominante.
        p(data-aos="fade-left") Las áreas del cerebro que procesan y producen el lenguaje, se dividen en dos categorías principales: áreas de producción y áreas de comprensión del lenguaje.
        p Las áreas encargadas de generar el habla, permiten la articulación de palabras y la coordinación de los movimientos necesarios para expresarse verbalmente. Las principales son: 
    
    h2(data-aos="fade-left") Área de Broca

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/16.png")
            .col-lg-7
              p Ubicada en el lóbulo frontal, esta región es esencial para la producción del habla. Se encarga de organizar los fonemas y estructurar las palabras en frases coherentes. Su daño puede provocar afasia de Broca, una condición en la que la persona tiene dificultades para hablar, aunque su comprensión del lenguaje permanece intacta.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/17.png")
            .col-lg-7
              p Parte del sistema instrumental del lenguaje, el Área de Broca está relacionada con la capacidad de organizar fonemas para formar palabras y oraciones. Está vinculada al uso de verbos y otras palabras necesarias para la interacción. Daños en esta área, pueden resultar en dificultades sintácticas.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/18.png")
            .col-lg-7
              p La zona recibe su nombre de Paul Broca, quien en 1861 estudió el cerebro de una persona con problemas significativos para expresarse verbalmente, aunque su comprensión del lenguaje era funcional. Descubrió un tumor en el hemisferio izquierdo, lo que llevó a que esta zona se relaciona con trastornos en la expresión verbal, como la “afasia de Broca”.
    
    h2(data-aos="fade-left") Área motora del lenguaje
    p.mb-5 Situada detrás del área de Broca, coordina los músculos involucrados en la articulación del habla, como los de la boca, lengua y laringe. Su correcto funcionamiento es clave para la fluidez verbal y la pronunciación precisa.
    
    h2(data-aos="fade-left") Áreas de comprensión del lenguaje
    p.mb-5 Estas áreas permiten interpretar el significado de las palabras y procesar la información lingüística, tanto oral como escrita:

    .row.align-items-center.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/19.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        LineaTiempoD.color-primario.large-2(data-aos="fade-left")
          div(numero="1" titulo="Área de Wernicke") 
            p Localizada en el lóbulo temporal, ubicada en el hemisferio izquierdo, alrededor de la cisura de Silvio (o surco lateral); esta área se ha estudiado desde mediados del siglo XIX y fue nombrada en honor al neurólogo Carl Wernicke. Es responsable de la comprensión del lenguaje hablado y escrito. Su daño puede causar afasia de Wernicke, en la que la persona puede hablar fluidamente, pero con frases sin sentido, puesto que pierde la capacidad de entender el significado de las palabras.
            p También como parte del sistema instrumental del lenguaje, el Área de Wernicke ayuda a evocar y vocalizar conceptos, así como a procesar sonidos para formar unidades significativas. Aunque no regula directamente la actividad semántica, su daño puede afectar la discriminación y procesamiento de sonidos, impactando el significado.
          p(numero="2" titulo="Área visual del lenguaje") Se encuentra en la parte posterior del cerebro y está involucrada en la interpretación del lenguaje escrito. Permite reconocer letras y palabras, facilitando la lectura y la escritura.
    
    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/20.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Estas áreas trabajan en conjunto para garantizar una comunicación efectiva. Además, están conectadas por el fascículo arqueado, una vía neural que permite la interacción entre la producción y la comprensión del lenguaje. Su correcto funcionamiento es esencial para la fluidez verbal y la capacidad de responder de manera coherente en una conversación.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/21.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") Estas áreas colaboran para facilitar la comunicación verbal y escrita. Lesiones en estas áreas pueden provocar trastornos del lenguaje, como la afasia, que afectan la capacidad de una persona para hablar, leer, escribir o comprender el lenguaje. La neurociencia sigue investigando el funcionamiento de estas áreas y su relación con el lenguaje para mejorar nuestra comprensión y tratamiento de los trastornos lingüísticos.
    
        .bg-color-9.p-5(data-aos="fade-left")
          p.mb-0 Las tres áreas del cerebro más investigadas en relación con el lenguaje son el Área de Broca, el Área de Wernicke, que ya ha sido explicada, y la circunvolución angular, cuya función se analizará a continuación.
    
    .bg-color-5.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/22.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") La circunvolución angular, también conocida como giro angular, es una estructura clave en el lóbulo parietal del cerebro. Su ubicación estratégica en la intersección de los lóbulos temporal, parietal y occipital, le permite desempeñar un papel fundamental en diversas funciones cognitivas, especialmente en el procesamiento del lenguaje, la memoria y la percepción visual.
    
    p.mb-5 Sus principales funciones son: 

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/23.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Regulación del lenguaje
              p Esta región cerebral está estrechamente relacionada con el Área de Wernicke, lo que la convierte en un componente esencial para la comprensión del lenguaje hablado y escrito. Su actividad permite interpretar palabras y frases, facilitando la comunicación efectiva.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/24.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Memoria episódica y semántica
              p La circunvolución angular participa en la recuperación de recuerdos personales (memoria episódica) y en el almacenamiento de conocimientos generales sobre el mundo (memoria semántica). Su correcto funcionamiento es crucial para la asociación de conceptos y la construcción del significado de las palabras.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/25.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Habilidades matemáticas y lectoescritura
              p Esta estructura cerebral está involucrada en el procesamiento numérico y en la capacidad de realizar cálculos matemáticos. También juega un papel importante en la lectura y escritura, ayudando a reconocer letras y palabras, así como a traducirlas en sonidos y significados.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/26.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Atención espacial y percepción visual
              p La circunvolución angular contribuye a la orientación espacial y a la interpretación de estímulos visuales. Permite reconocer objetos, rostros y formas, facilitando la navegación en el entorno y la comprensión de la información visual.
    
    .row.justify-content-center.align-items-center.bg-color-2.p-4.py-lg-0.px-lg-4.mb-5.bordes
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
            h5 Lesiones y trastornos asociados
            p Las alteraciones en la circunvolución angular pueden provocar afasia semántica, un trastorno en el que la persona pierde la capacidad de comprender el significado de las palabras, aunque pueda pronunciarlas correctamente. También se ha relacionado con dificultades en la lectura (alexia) y en la escritura (agrafia), así como con problemas en el procesamiento matemático.
            p.mb-0 Muchos científicos consideran que la circunvolución angular es una extensión del Área de Wernicke, debido a su implicación en la comprensión y comunicación del lenguaje. Su conexión con otras áreas cerebrales permite integrar información de diferentes modalidades sensoriales, facilitando el aprendizaje y la interpretación del mundo.
          .col-lg-3(data-aos="zoom-in").order-lg-1
            img.img-fluid(src='@/assets/curso/tema2/27.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    #t_2_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.3] Áreas de la visión
    
    p.mb-5 La percepción visual es un proceso complejo que va más allá de la simple captación de imágenes; requiere una coordinación precisa entre diversas áreas del cerebro que interpretan, organizan y responden a los estímulos visuales del entorno.

    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Áreas de la visión
            p.mb-4(data-aos="fade-right") En el PDF <b>Áreas de la visión</b>, se estudian las principales regiones cerebrales involucradas en el procesamiento visual, incluyendo la corteza visual primaria, las áreas visuales secundarias y las vías ventral y dorsal. Este análisis permite comprender cómo el cerebro transforma la información recibida por los ojos en percepciones significativas, así como las posibles alteraciones que pueden surgir por lesiones en estas áreas.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_5.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Áreas de la visión.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/28.png', alt='')
    
    #t_2_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.4] Áreas de escritura
    
    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/29.png", data-aos="zoom-in")
      .col-lg-7
        .bg-color-9.p-5.mb-3(data-aos="fade-left")
          p.mb-0 Los seres humanos venimos al mundo con un cerebro predispuesto para el habla. Aprendemos nuestro idioma nativo de forma natural, sin necesidad de clases formales. No recibimos instrucción en gramática, y a la edad de cinco años, ya hablamos con fluidez. La simple exposición a una sociedad permite que se formen los circuitos neuronales en nuestro cerebro que facilitan el lenguaje. Sin embargo, no nacemos con una predisposición inherente para leer y escribir; este es un proceso que requiere aprendizaje. Es esencial recibir instrucción a través de métodos adecuados. El aprendizaje de la lectura y la escritura implica desarrollar un sistema altamente eficiente de conexiones entre las áreas visuales y las áreas del lenguaje en el cerebro, ambas presentes desde el primer año de vida.
        p(data-aos="fade-left") En el proceso de aprendizaje de la lectura, podemos identificar tres etapas:
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5

        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/30.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Etapa pictórica
                p.mb-0 En la que los niños reconocen algunas palabras.
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/31.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Etapa fonológica
                p.mb-0 En la que aprenden a asociar letras (grafemas) con sonidos (fonemas).
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/32.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Etapa ortográfica o léxica
                p.mb-0 Donde identifican palabras y acceden a sus significados rápidamente.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/33.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") Durante el aprendizaje de la lectura y la escritura, se producen cambios en las áreas del cerebro y se forman nuevas redes neuronales. Los estudios de pacientes que, debido a lesiones cerebrales, pierden la capacidad de leer o escribir, ofrecen información sobre las áreas cerebrales involucradas en estas habilidades. Sin embargo, los conocimientos más significativos sobre la neurociencia de la lectoescritura provienen de investigaciones realizadas con tecnologías de neuroimagen.
    
        .bg-color-8.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/34.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Aprender a leer implica la conexión eficiente de dos sistemas cerebrales ya existentes: el sistema visual y el sistema lingüístico. Los niños tienen la infraestructura cerebral necesaria para esta tarea, gracias a su programación genética y a la estimulación del entorno, lo que les permite reconocer tanto objetos como el lenguaje. Estas interconexiones neuronales entre el sistema lingüístico y el visual alteran la estructura y el funcionamiento del cerebro, especialmente en la región temporo-occipital izquierda, que Dehaene (2014), citado por Lebrero, Fernández y García (2015), llama “caja de letras y buzón de palabras”.
    
    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/35.png", data-aos="zoom-in")
      .col-lg-9
        p(data-aos="fade-left") La escritura es una actividad muy compleja que involucra una variedad de procesos mentales, tanto cognitivos como emocionales, y requiere la participación de todo el cerebro. Para escribir, es fundamental tener conocimiento de los códigos del lenguaje, como fonemas, grafemas y palabras. Esto incluye la habilidad de convertir fonemas en grafemas, un entendimiento del sistema grafémico, destrezas psicomotoras, y la capacidad visoespacial para organizar, unir y separar palabras. Además, se necesita un cúmulo de conocimientos y recuerdos acerca del mundo y de nosotros mismos.
    
        .bg-color-2.p-5(data-aos="fade-left")
          p.mb-0 Al igual que la lectura, la escritura se aprende a partir del lenguaje hablado. Cuando un niño alcanza un nivel competente en el uso del lenguaje, incluyendo vocabulario y gramática, generalmente entre los cinco y seis años, es capaz de narrar una historia sobre un tema o persona.

    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/36.png", data-aos="zoom-in")
      .col-lg-7.order-lg-1
        .bg-color-11.p-5(data-aos="fade-left").text-white
          p.mb-0 Para Rodríguez (2017), la escritura involucra el funcionamiento conjunto y coordinado de diversas estructuras cerebrales asociadas al pensamiento, el lenguaje y la memoria. Este proceso requiere un alto grado de especialización y coordinación entre los hemisferios, ya que implica la integración de movimiento, tacto e ideas, lo cual es esencial para transferir nuestras ideas a un soporte físico. Por lo tanto, la escritura contribuye al desarrollo de la inteligencia.

    .row.justify-content-center.align-items-center.bg-color-4.p-4.py-lg-0.px-lg-4.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
            p Al escribir, realizamos las siguientes actividades mentales:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Organizar nuestras ideas para expresarlas.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Coordinar la vista con el movimiento de la mano.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Sintetizar nuestras ideas.
          .col-lg-5(data-aos="zoom-in").order-lg-1
            img.img-fluid(src='@/assets/curso/tema2/37.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-5 Según Rodríguez (2017), los lóbulos cerebrales desempeñan un papel fundamental en este proceso:

    .row.align-items-center.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/38.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        LineaTiempoD.color-primario.large-2(data-aos="fade-left")
          p(numero="1" titulo="Lóbulo frontal") Es el encargado del razonamiento, la abstracción y la planificación de la disposición de las palabras en el soporte. Esta región del cerebro nos ayuda a estructurar nuestras ideas antes de escribirlas, permitiendo que el contenido tenga coherencia y fluidez.
          p(numero="2" titulo="Lóbulo temporal") Su función principal es la discriminación gráfico-fonológica, lo que significa que nos permite asociar cada sonido con su correspondiente representación escrita. Gracias a esta área, podemos transformar el lenguaje hablado en palabras escritas de manera precisa.
          p(numero="3" titulo="Lóbulo parietal") Facilita la coordinación óculo-manual, lo que es esencial para la escritura. Nos ayuda a controlar los movimientos de la mano y los dedos, asegurando que las letras y palabras sean trazadas correctamente en el papel o en una pantalla.
          p(numero="4" titulo="Lóbulo occipital") Se encarga del reconocimiento de las diferentes letras escritas. Esta área nos permite identificar y diferenciar los caracteres, asegurando que podamos leer y escribir con claridad.
    
    p.mb-5 El sistema neuroescritural es un conjunto de procesos que involucran la activación y coordinación de estas áreas cerebrales. La escritura no solo depende de la motricidad fina, sino también de la integración de la percepción visual, el procesamiento del lenguaje y la planificación cognitiva (Rodríguez, 2017).

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/39.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-5.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/40.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Para finalizar este apartado es importante mencionar algunas alteraciones que se pueden presentar en este proceso de la escritura; para Lebrero, Fernández y García (2015), dado que la escritura involucra la activación de múltiples áreas del cerebro, que pueden verse afectadas, según el tipo de lesión, los síntomas de las agrafías son diversos. Existen varios modelos de clasificación de las agrafías por Ardila y Rosselli (2007), citados por estos tres autores, una clasificación clásica distingue entre agrafías afásicas y no afásicas. 
        p(data-aos="fade-left") Las agrafías afásicas están relacionadas con las afasias del habla. Por ejemplo:
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5
      
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-6.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/41.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Afasia de Broca
                p.mb-0 La agrafia se caracteriza por una escritura lenta y esforzada, con una caligrafía torpe, producción abreviada, agramatismo y simplificaciones silábicas.
          .col-lg-6.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema2/42.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Afasia de Wernicke
                p.mb-0 La escritura es fluida y las letras están bien formadas, pero mal combinadas, resultando en un texto sin sentido.
        
    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/43.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Es común observar paragrafías literales, que incluyen adiciones, sustituciones y omisiones de letras, así como la creación de neologismos. La gramática permanece intacta, aunque las oraciones pueden carecer de límites claros y ausentar nombres.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/44.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") En la afasia de conducción, la escritura espontánea suele ser mejor que la escritura al dictado. El paciente es consciente de que una palabra está mal escrita, pero al intentar corregirla introduce nuevos errores, y su escritura está llena de tachaduras. Aunque afirma conocer la palabra, no puede recordar su ortografía. La escritura es lenta y complicada, con letras mal formadas pero reconocibles. También se observan agrafías correspondientes en otras variantes de afasia. Por otro lado, las agrafías no afásicas se caracterizan por dificultades motoras que afectan la escritura y problemas visoespaciales que alteran la organización de las palabras en el texto.
    
        .bg-color-9.p-4(data-aos="fade-left")
          p.mb-0 En este orden de ideas, los desarrollos en neurociencia demuestran que la escritura es un ejercicio valioso para todos, especialmente para los niños. Este proceso es un recurso indispensable con un valor pedagógico incalculable, dado que la escritura contribuye al desarrollo de su inteligencia (Rodríguez, 2017).
    
    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/45.png", data-aos="zoom-in")
      .col-lg-7
        .bg-color-2.px-4.py-5(data-aos="fade-left")
          p.mb-0 La escritura manual es mucho más que un simple acto de plasmar palabras en papel. Es un ejercicio mental que involucra múltiples áreas del cerebro y fortalece las conexiones neuronales. Al escribir a mano, el cerebro activa circuitos que favorecen la memoria, la concentración y el pensamiento crítico. Este proceso requiere la coordinación de la percepción visual, el control motor fino y la planificación cognitiva, lo que lo convierte en una actividad altamente beneficiosa para el desarrollo intelectual (Rodríguez, 2017).

    .bg-full-width.bg-color-6
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.bg-color-8.bordes.p-4.py-lg-0.px-lg-4.mb-5
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0
                p Desde la perspectiva de la neurociencia, se ha demostrado que la escritura manual contribuye a la expansión cerebral y al fortalecimiento de habilidades cognitivas. Al realizar trazos con la mano, se estimulan regiones cerebrales relacionadas con el aprendizaje y la creatividad. Además, escribir a mano ayuda a mejorar la autorregulación, puesto que requiere paciencia y precisión, lo que fomenta la autodisciplina y la capacidad de concentración (Rodríguez, 2017).
                p.mb-0 Otro aspecto clave es la voluntad y la perseverancia. La escritura manual exige esfuerzo y práctica, lo que refuerza la capacidad de mantener la atención en una tarea y desarrollar hábitos de trabajo estructurados. En un mundo cada vez más digitalizado, mantener la práctica de la escritura manual puede ser una herramienta poderosa para mejorar la inteligencia y el desarrollo personal (Rodríguez, 2017).

              .col-lg-3(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/46.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
        
        p.mb-5 La escritura refleja la actividad cognitiva de cada individuo y la escritura a mano proporciona información personal única. Este proceso involucra tres etapas esenciales, según Rodríguez (2017):

        div.row.justify-content-center.align-items-stretch
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/47.svg" alt="" style="width: 90px")
              h5.text-center Percepción
              p.mb-0.text-center Captar los estímulos necesarios, como el tipo de superficie para escribir, las herramientas utilizadas y las instrucciones sobre lo que se debe escribir.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/48.svg" alt="" style="width: 90px")
              h5.text-center Decisión
              p.mb-0.text-center Planificar y decidir el contenido que se va a escribir.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/49.svg" alt="" style="width: 90px")
              h5.text-center Ejecución
              p.mb-0.text-center Coordinar los movimientos necesarios para plasmar el texto.

    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        p.mb-0.text-white Es importante ofrecer a los niños oportunidades para escribir, permitiéndoles desarrollar y refinar esta habilidad. La escritura no sólo estimula su inteligencia, sino que también es una actividad integral que requiere un funcionamiento cognitivo completo, contribuyendo a su lenguaje, pensamiento, memoria, emociones, entre otros aspectos (Rodríguez, 2017).




    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/174786?page=1" target="_blank" rel="noopener noreferrer") Massion, J. (2021). Cerebro y motricidad: funciones sensoriomotrices: ( ed.). Editorial INDE. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/91946?page=1" target="_blank" rel="noopener noreferrer") Moreno Manso, J. M. (2005). Características de la personalidad y alteraciones del lenguaje en educación infantil y primaria: ( ed.). Organización de Estados Iberoamericanos (OEI). 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=t5GA18JZw54 " target="_blank" rel="noopener noreferrer") Sinapsis EMP. (2023, 9 de septiembre). Neuroanatomía y fisiología del lenguaje [Vídeo]. YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Neuropedagogía',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál es la principal función del lóbulo frontal en el aprendizaje?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Procesamiento de la información visual',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Regulación del movimiento involuntario',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Razonamiento, planificación y abstracción',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Identificación de sonidos y palabras',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué área del cerebro está relacionada con la escritura y la coordinación motora fina?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Área de Exner',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Área de Wernicke',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Área de Broca',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Giro angular',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál de las siguientes es una alteración del lenguaje que afecta la capacidad de hablar y comprender?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Agnosia',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Afasia',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Ataxia',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Disfagia',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué área cerebral permite asociar cada sonido con su correspondiente letra al escribir?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Lóbulo temporal',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Lóbulo occipital',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Lóbulo parietal',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Cerebelo',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Cuál es la función del giro angular en el proceso de escritura?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Control de la motricidad fina de la mano',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Conversión de fonemas en grafemas y procesamiento del lenguaje escrito',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Regulación del movimiento corporal general',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Coordinación de la visión con el entorno',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
