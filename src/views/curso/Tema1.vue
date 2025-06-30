<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Funcionamiento del sistema nervioso, basado en el cerebro'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    
    div.bg-color-4.mb-5.px-4.px-md-5.py-4
      .row.align-items-center
        .col-lg-auto
          img(src="@/assets/curso/tema1/1.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 Para dar inicio a esta primera unidad, hablaremos sobre qué es el cerebro, qué es el sistema nervioso central y luego pasaremos a desarrollar, cómo se relacionan ambos.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") En las décadas recientes, ha habido un notable incremento en la investigación dedicada al cerebro humano. Indagar sobre el cerebro implica una fascinación por las funciones cognitivas avanzadas que los seres humanos podemos llevar a cabo. En este ámbito convergen diversos intereses: la curiosidad innata por comprender la naturaleza, el afán por el conocimiento y la urgencia de abordar las vulnerabilidades y patologías, ya sean congénitas o adquiridas y manifestadas con el transcurso de la vida.
    
        .bg-color-5.p-4(data-aos="fade-left")
          p.mb-0 Asimismo, es fundamental reconocer el interés en optimizar al máximo las capacidades cerebrales inherentes a cada individuo. De hecho, en los últimos años se han logrado avances significativos que nos han permitido descubrir aspectos asombrosos sobre la intrincada complejidad y el funcionamiento de este órgano vital.

    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] El cerebro     
    
    p.mb-4 Imagine que el cerebro es como el centro de mando principal de nuestro cuerpo y ocupa casi todo el espacio dentro de nuestra cabeza. Está dividido en dos grandes mitades, como dos equipos que trabajan juntos, aunque cada uno tiene sus especialidades. Estas mitades, llamadas hemisferios, no son exactamente iguales:

    .bg-full-width.bg-fondo-1
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-6
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema1/3.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="37%" y="59.5%" numero="+")
                h5 1
                p El hemisferio izquierdo se encarga más de las tareas lógicas, como cuando resolvemos un problema de matemáticas o analizamos algo.
    
              .bg-color-white.box-shadow.p-3(x="65%" y="59.5%" numero="+")
                h5 2
                p El hemisferio derecho está más relacionado con nuestras emociones, sentimientos y nuestro lado creativo, como cuando pintamos o imaginamos historias.
    
    .bg-full-width.bg-color-6
      .px-4.px-md-5
        div.bg-color-3.mb-5.px-4.px-md-5.py-4
          p.mb-0.text-white A su vez, cada una de estas dos grandes mitades, se subdivide en cuatro secciones principales llamadas lóbulos, y cada lóbulo tiene funciones más o menos específicas. 
        
        p Piensa en ellos como departamentos especializados:
         
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/4.svg" alt="" style="width: 90px")
              h5.text-center Lóbulo frontal
              p.mb-0.text-center Tiene que ver con la capacidad de pensar, planificar y la inteligencia.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/5.svg" alt="" style="width: 90px")
              h5.text-center Lóbulo temporal
              p.mb-0.text-center Se relaciona con lo que oímos.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/6.svg" alt="" style="width: 90px")
              h5.text-center El lóbulo parietal
              p.mb-0.text-center Procesa la información de los sentidos, como el tacto.
          
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/7.svg" alt="" style="width: 90px")
              h5.text-center Lóbulo occipital
              p.mb-0.text-center Es el encargado de la visión.
              
    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0.text-white
            h2.mb-4(data-aos="flip-up") El cerebro
            p.mb-4(data-aos="fade-right") En el PDF <b>El cerebro</b>, se estudia la composición, estructura y funcionamiento de este órgano, con énfasis en las neuronas, sus conexiones sinápticas y el modo en que estas células procesan información a velocidades extraordinarias. Además, se explora su desarrollo desde etapas embrionarias y se destacan aspectos neurobiológicos que permiten dimensionar su asombrosa capacidad organizativa y funcional.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> El cerebro.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/8.png', alt='')
    
    #t_1_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.2] Sistema nervioso central
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/9.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") El sistema nervioso central se desarrolla a partir de una capa celular denominada ectodermo, la cual envuelve al embrión en las primeras etapas de gestación. Este proceso es fundamental para la formación de estructuras claves del organismo, permitiendo la diferenciación de células especializadas que darán origen al cerebro y la médula espinal.
    
        .bg-color-8.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 A lo largo de los nueve meses de desarrollo embrionario, las células nerviosas se multiplican de manera acelerada, alcanzando una tasa de producción de aproximadamente 250,000 nuevas neuronas por minuto. Este crecimiento es indispensable para la construcción de una red neuronal compleja, capaz de regular funciones vitales y permitir el procesamiento de estímulos externos.
    
    p.mb-4 Al finalizar el periodo de gestación, el cerebro humano alcanza una estructura completamente formada, compuesta por cerca de 100,000 millones de células. La sofisticación de este órgano permite el desarrollo de habilidades cognitivas, motoras y sensoriales, consolidando su papel como centro de control del organismo.

    .row.justify-content-center.align-items-center.bg-color-5.p-4.py-lg-0.px-lg-4.mb-5.bordes
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
            p La formación del <b>sistema nervioso central</b> es un proceso que refleja la extraordinaria capacidad de las células embrionarias para organizarse y diferenciarse en estructuras especializadas. Esta evolución garantiza el adecuado funcionamiento del cuerpo y la interacción con el entorno a lo largo de la vida.
            p El sistema nervioso central <b>tiene la función</b> de regular tanto las acciones que realizamos de forma consciente, como las que ocurren de manera automática.
            p.mb-0 Esto incluye no solo las manifestaciones físicas, sino también los <b>procesos</b> relacionados con el pensamiento.
          .col-lg-4(data-aos="zoom-in")
            img.img-fluid(src='@/assets/curso/tema1/10.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 A través de este sistema, podemos reaccionar de diversas maneras a los estímulos siempre variables, que nuestro cuerpo enfrenta, además de coordinar los diferentes procesos fisiológicos que son esenciales para nuestra supervivencia.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/12.png", data-aos="zoom-in")
      .col-lg-8
        h2.mb-5(data-aos="fade-left") Partes del sistema nervioso central
        .bg-color-9.p-4(data-aos="fade-left")
          p(data-aos="fade-left") El sistema nervioso central está formado por dos estructuras esenciales para el funcionamiento del cuerpo y la vida en general: el cerebro (considerado en su totalidad como encéfalo, no solo la corteza cerebral) y la médula espinal. El cerebro como lo vimos anteriormente, se encuentra dentro del cráneo e incluye componentes como el cerebelo, la corteza cerebral, el diencéfalo, entre otros, que son vitales para nuestra supervivencia. La médula espinal, por otro lado, se extiende a lo largo de la columna vertebral, conectando el encéfalo con los nervios del Sistema Nervioso Periférico, que no están protegidos por huesos y se distribuyen por todo el cuerpo.
    
    p.mb-4 A continuación, examinaremos las funciones de cada uno de estos componentes de forma individual y cómo se interconectan para que nuestro organismo responda a cualquier estímulo

    h2(data-aos="fade-left") a. El cerebro

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/13.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Este órgano es, sin duda, el más complejo del cuerpo humano, en términos de funcionamiento. Según investigaciones en neurociencias, el cerebro está compuesto por aproximadamente 100 mil millones de neuronas que interactúan entre sí, formando una cantidad inmensa de conexiones. Sin embargo, la mayoría de las células nerviosas en el cerebro no son neuronas, sino células gliales. Se estima que el cerebro consume alrededor del 20 % del oxígeno que inhalamos, a pesar de representar solo el 2 % del peso total de un ser humano promedio.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/14.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Según Francia (2021), cuando se menciona el cerebro, la primera idea que viene a la mente suele ser la de las neuronas y sus redes de comunicación. Esto es correcto, dado que el cerebro y el sistema nervioso operan gracias a la interacción entre neuronas, las cuales intercambian información y desempeñan un papel esencial en la trama de la vida. Sin embargo, ¿qué ocurriría si no hubiera glía?
    
    h2(data-aos="fade-left") b. La glía, o neuroglia
    
    .row.justify-content-center.align-items-center.bg-color-2.px-4.mb-5.bordes
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
            p Es el componente celular más significativo del sistema nervioso, siendo de 10 a 50 veces más grande que las neuronas. Este término fue utilizado por primera vez a mediados del siglo XIX, para referirse a la sustancia amorfa, o "cemento nervioso", que rodea y sostiene las neuronas. Con el tiempo, se reconoció su naturaleza celular y la existencia de diferentes tipos especializados.
            p.mb-0 Las células gliales son, por definición, un tipo de células del sistema nervioso que, junto con las neuronas, forman el sistema nervioso central y periférico. Francia (2021), explica que esta fue descrita inicialmente por el fisiólogo alemán Rudolf Virchow en 1860; estas células realizan numerosas funciones auxiliares que son vitales para el funcionamiento y la supervivencia de las neuronas, proporcionando principalmente soporte mecánico y nutricional, así como control metabólico del entorno intercelular.
          .col-lg-3(data-aos="zoom-in").order-lg-1
            img.img-fluid(src='@/assets/curso/tema1/15.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-4 Estas células se pueden clasificar en dos grandes grupos, según su tamaño y origen:

    .row.align-items-center.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/16.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        LineaTiempoD.color-primario.large-2(data-aos="fade-left")
          p(numero="1" titulo="Las macroglías") Son las células más grandes y tienen un origen neuroectodérmico. En el sistema nervioso central, hay tres tipos principales: los astrocitos, que brindan soporte y regulan sustancias en el cerebro; los oligodendrocitos, que forman la mielina para proteger los axones de las neuronas; y las células ependimales, que recubren los ventrículos cerebrales y regula el líquido cefalorraquídeo. En el sistema nervioso periférico, las macroglías incluyen las células de Schwann, que cumplen una función similar a los oligodendrocitos, y las células satélites, que protegen las neuronas en los ganglios.
          p(numero="2" titulo="Las microglías") Son las células más pequeñas y de origen mesodérmico, tienen un papel fundamental en el sistema inmunológico del cerebro. Actúan como defensa eliminando residuos celulares y agentes dañinos. También ayudan a regular la actividad de las neuronas y pueden influir en la respuesta inmune.
    
    .bg-color-5.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema1/17.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") Las células gliales tienen diversas funciones en el sistema nervioso. Además de ofrecer protección y apoyo estructural a las neuronas, regulan sustancias químicas, forman la barrera hematoencefálica y ayudan en la reparación de daños. También están involucradas en diversas enfermedades neurológicas y pueden dar origen a tumores llamados gliomas.
    
    

    .bg-full-width.bg-color-10
      .px-4.px-md-5.pb-md-3
        p.mb-4 Cada tipo de célula glial tiene una función específica:
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/19.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Células satélites
                p.text-center Regulan el entorno químico de las neuronas en los ganglios.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Células de schwann
                p.text-center Recubren los axones en el sistema nervioso periférico y ayudan en su reparación.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/21.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Células ependimales
                p.text-center Producen y regulan el líquido cefalorraquídeo.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/22.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Oligodendrocitos
                p.text-center Crean mielina para proteger los axones del sistema nervioso central.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/23.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Astrocitos
                p.text-center Mantienen el equilibrio químico y ayudan a reparar lesiones.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/24.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Microglía
                p.text-center Actúa como defensa, eliminando residuos y protegiendo contra infecciones.
    
          .col-lg-4
            figure
              img(src='@/assets/curso/tema1/18.png', alt='')
    
    .row.justify-content-center.align-items-center.bg-color-1.p-4.py-lg-0.px-lg-4.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Las células satélites regulan el entorno químico de las neuronas en los ganglios.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Las células de Schwann recubren los axones en el sistema nervioso periférico y ayudan en su reparación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Las células ependimales producen y regulan el líquido cefalorraquídeo.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Los oligodendrocitos crean mielina para proteger los axones del sistema nervioso central.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Los astrocitos mantienen el equilibrio químico y ayudan a reparar lesiones.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 La microglía actúa como defensa, eliminando residuos y protegiendo contra infecciones.
            h5 Estas células son esenciales para el funcionamiento y la salud del sistema nervioso.

          .col-lg-4(data-aos="zoom-in").order-lg-1
            img.img-fluid(src='@/assets/curso/tema1/25.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2(data-aos="fade-left") c. Nervios
    p Otro elemento importante son los nervios, estos son como cables que transportan información en el cuerpo. Son grupos de fibras nerviosas que llevan señales desde el cerebro y la médula espinal hacia otras partes del cuerpo. También reciben información del exterior y la llevan al cerebro para que podamos sentir y reaccionar.
    p.mb-5 Existen dos tipos principales de nervios, según su origen:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/26.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Nervios raquídeos
              p Salen de la médula espinal y llevan mensajes entre el cuerpo y el cerebro. Están formados por fibras nerviosas que pueden ser motrices, encargadas del movimiento, o sensitivas, responsables de la sensibilidad
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/27.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Nervios craneales
              p Son 12 pares de nervios que vienen del cerebro. Su función principal es ayudar a los sentidos de la cara y la cabeza, como la vista, el olfato y el gusto. Algunos de estos nervios también controlan el movimiento de los músculos faciales.
    
    h2(data-aos="fade-left") d. La médula espinal
    p.mb-5 La médula espinal cumple un papel esencial en la comunicación entre el cerebro y el resto del cuerpo, posibilitando tanto movimientos voluntarios como respuestas automáticas ante estímulos.

    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.order-2
            h2.mb-4(data-aos="flip-up") La médula espinal
            p.mb-4(data-aos="fade-right") En el PDF <b>La médula espinal</b>, se aborda su estructura, funciones y componentes, destacando su papel como vía principal de transmisión nerviosa y su participación en los reflejos. Este análisis permite comprender cómo esta parte del sistema nervioso central asegura la conexión eficiente entre el encéfalo, los órganos sensoriales y los músculos.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> La médula espinal.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/28.png', alt='')
    
    h2(data-aos="fade-left") Funciones del sistema nervioso central
    p.mb-5 Las funciones del sistema nervioso central son esenciales para comprender cómo el cuerpo humano percibe, interpreta y responde a su entorno.

    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Funciones del sistema nervioso central
            p.mb-4(data-aos="fade-right") En el PDF <b>Funciones del sistema nervioso central</b>, se explican los principales procesos que realiza este sistema: desde la recepción de información sensorial hasta el almacenamiento de experiencias. Este contenido permite identificar la relevancia del cerebro y la médula espinal en la toma de decisiones, la ejecución de acciones y la adaptación inteligente al medio.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Funciones del sistema nervioso central.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/29.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/43244?page=30 " target="_blank" rel="noopener noreferrer") Velayos, J. L. & Diéguez, G. (2015). Anatomía y fisiología del sistema nervioso central: (ed.). CEU Ediciones. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=fqXOg4T2pzY " target="_blank" rel="noopener noreferrer") Facultad de Ciencias Médicas. (2018, 13 de septiembre). FISIOLOGÍA: Sistema nervioso. PARTE I [Vídeo]. YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
