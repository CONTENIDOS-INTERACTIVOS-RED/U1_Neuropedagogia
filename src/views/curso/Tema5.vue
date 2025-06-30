<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'5. Componentes y sistemas de representación del cerebro'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema5/1.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") Según el equipo Lifeder (2024), retomando conceptos de la primera unidad, el cerebro humano es el órgano central del sistema nervioso, ubicado en la cabeza y resguardado por el cráneo. Aunque comparte similitudes estructurales y anatómicas con los cerebros de otros mamíferos, su córtex cerebral está significativamente más desarrollado, lo que permite funciones cognitivas avanzadas como el lenguaje, el pensamiento abstracto y la resolución de problemas.
    
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema5/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Algunos animales, como las ballenas y los elefantes, tienen cerebros más grandes en comparación con otros, pero el tamaño absoluto no es lo único que importa. Para evaluar la capacidad del cerebro en relación con el cuerpo, se usa el coeficiente de encefalización, que ajusta el tamaño cerebral según el tamaño corporal. Según esta medida, el cerebro humano es casi el doble de eficiente que el del delfín común y tres veces más que el del chimpancé. 
    
    .row.align-items-center.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema5/3.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        LineaTiempoD.color-primario.large-2(data-aos="fade-left")
          p(numero="1" titulo="Córtex cerebral") Esta diferencia se debe principalmente al córtex cerebral, que ha crecido más en los humanos, especialmente en los lóbulos frontales. Esta parte del cerebro es clave para habilidades avanzadas como el razonamiento, la planificación, el autocontrol y el pensamiento abstracto.
          p(numero="2" titulo="Córtex visual") Lifeder (2024), sostiene que, el córtex visual, que es el área del cerebro encargada de la vista, también es más grande en los humanos, lo que nos permite procesar imágenes y detalles con mayor precisión. Esta evolución ha sido fundamental para el desarrollo del pensamiento complejo y la capacidad de adaptarnos a nuestro entorno.
          p(numero="3" titulo="Estructura compleja") Triglia ( 2016), sustenta que, el cerebro humano es una estructura compleja que procesa información a través de diversos componentes y sistemas de representación. Estos sistemas permiten la percepción, el aprendizaje y la toma de decisiones, influyendo en la manera en que los individuos interpretan su entorno.
    
    p.mb-5 El cerebro recibe constantemente información del cuerpo a través de los sentidos (vista, oído, tacto, gusto y olfato). Esta información es interpretada y procesada en diferentes áreas cerebrales, permitiendo respuestas adaptativas. Según Lifeder (2024), algunos ejemplos serían:

    .bg-full-width.bg-fondo-2.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema5/4.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="22%" y="62.5%" numero="+")
                h5 Olores
                p Se procesan en el bulbo olfatorio, influyendo en la memoria y las emociones.
    
              .bg-color-white.box-shadow.p-3(x="5%" y="42%" numero="+")
                h5 Sonidos
                p Se procesan en el lóbulo temporal, permitiendo la comprensión del lenguaje y la percepción auditiva.
    
              .bg-color-white.box-shadow.p-3(x="31%" y="22%" numero="+")
                h5 Luz
                p Se interpreta en el córtex visual, ubicado en el lóbulo occipital, facilitando la visión y el reconocimiento de formas y colores.
    
              .bg-color-white.box-shadow.p-3(x="59%" y="23%" numero="+")
                h5 Dolor y tacto
                p Se gestionan en el lóbulo parietal, permitiendo la percepción sensorial y la respuesta motora.

    .bg-full-width.bg-color-13
      .p-4.p-md-5
        p.mb-5 Además de procesar estímulos externos, el cerebro desempeña funciones esenciales para la homeostasis del organismo, regulando procesos internos como:
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/5.svg" alt="" style="width: 90px")
              h5.text-center Respiración
              p.mb-0.text-center Controlada por el tronco encefálico, asegurando el suministro de oxígeno.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/6.svg" alt="" style="width: 90px")
              h5.text-center Liberación de hormonas
              p.mb-0.text-center Coordinada por el hipotálamo, regulando el metabolismo, el crecimiento y el estado emocional.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/7.svg" alt="" style="width: 90px")
              h5.text-center Presión arterial y ritmo cardíaco
              p.mb-0.text-center Gestionados por el bulbo raquídeo, manteniendo la estabilidad cardiovascular.
    
    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema5/8.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p El cerebro para Lifeder (2024), permite la interacción con el mundo a través de la comunicación verbal y no verbal, facilitando el desarrollo de relaciones sociales y el aprendizaje. También coordina la interacción con objetos inanimados, permitiendo el uso de herramientas, la escritura y la manipulación de elementos físicos. 
            p.mb-0 El cerebro es un órgano altamente especializado que no solo garantiza la supervivencia, sino que también permite   el pensamiento complejo, la expresión emocional y la adaptación al entorno. Su funcionamiento integrado es clave para la vida cotidiana y el desarrollo humano. 

    #t_5_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.1] Componentes del cerebro
    
    p.mb-5 El estudio de las estructuras cerebrales y sus funciones es fundamental para comprender cómo se procesan las emociones, los pensamientos y las conductas humanas.

    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.order-2
            h2.mb-4(data-aos="flip-up") Componentes del cerebro
            p.mb-4(data-aos="fade-right") En el PDF <b>Componentes del cerebro</b>, se abordan detalladamente el neocórtex, el sistema límbico y el cerebro reptiliano, explicando su evolución, características anatómicas y roles en el aprendizaje, la memoria, la toma de decisiones y la supervivencia. Esta exploración permite comprender cómo interactúan estos tres sistemas en la vida cotidiana, y cómo su integración impacta en la formación de la personalidad y el comportamiento humano.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_7.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Componentes del cerebro.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/9.png', alt='')
    
    #t_5_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.2] Sistemas de representación
    
    p.mb-5 Los sistemas de representación son los mecanismos a través de los cuales recopilamos, almacenamos e interpretamos la información que seleccionamos, del entorno, en nuestra mente. En otras palabras, son las formas en que percibimos lo que sucede en el mundo. Generalmente, existen tres sistemas primarios de percepción, Accresio (2020). Se pueden clasificar en:

    .row.align-items-center.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema5/10.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        LineaTiempoD.color-primario.large-2(data-aos="fade-left")
          div(numero="1" titulo="Sistema visual (SV)")
            p Se basa en la capacidad de percibir el mundo a través de la vista. 
            p Incluye dos aspectos fundamentales:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Percepción externa</b>. La habilidad de ver objetos, colores, formas y movimientos, en el entorno.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Visualización interna</b>. La capacidad de imaginar imágenes en la mente, lo que facilita la creatividad y la memoria visual. 
            p Las personas con predominancia en este sistema, suelen aprender mejor mediante diagramas, gráficos, mapas mentales y videos. También tienen una gran facilidad para recordar imágenes y detalles visuales.
          div(numero="2" titulo="Sistema auditivo")
            p Está centrado en la percepción de sonidos y la interpretación de información verbal.  
            p Se divide en:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Escucha externa</b>. La capacidad de captar sonidos del entorno, como voces, música y ruidos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Escucha interna</b>. Relacionada con el pensamiento verbal y la reflexión interna, lo que permite procesar ideas a través del lenguaje.  
            p Las personas con predominancia en este sistema, aprenden mejor mediante explicaciones orales, debates, música y grabaciones. Suelen recordar información escuchada con facilidad y tienen habilidades para la comunicación verbal. 

          div(numero="3" titulo="Sistema kinestésico")
            p Involucra los sentidos del tacto, olfato y gusto, además de la percepción del movimiento y equilibrio. 
            p Se enfoca en la experiencia sensorial y emocional, permitiendo interpretar el mundo a través de sensaciones físicas. 
            p Las personas con predominancia en este sistema, aprenden mejor mediante experiencias prácticas, actividades físicas, experimentos y juegos interactivos. Suelen necesitar movimiento para concentrarse y procesar información de manera efectiva.

    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema5/11.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Cada persona tiene una combinación única de estos sistemas, lo que influye en su estilo de aprendizaje y en la manera en que interactúa con el entorno. Comprender estos sistemas permite adaptar estrategias educativas y mejorar la comunicación interpersonal (Accresio, 2020).
    
    .row.justify-content-center.align-items-center.bg-color-9.bordes.p-4.py-lg-0.px-lg-4.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0
            p Es importante destacar que estos sistemas no son fijos, sino que son dinámicos e interactúan entre sí. Accresio (2020), sostiene que una persona puede tener un sistema predominante, pero también beneficiarse de los otros dos. A medida que se profundiza en cada uno de estos sistemas y se practican, se facilita el movimiento entre ellos, lo que proporciona herramientas más efectivas para la comunicación. 
            p.mb-0 De esta manera, los sistemas de representación, son formas de interactuar con el mundo que nos rodea. Conocer en qué sistemas nos encontramos y cómo nos movemos entre ellos, es información valiosa que permite hacerlo de manera fluida y natural, aprovechando las ventajas que cada uno ofrece en diversas situaciones.

          .col-lg-3(data-aos="zoom-in")
            img.img-fluid(src='@/assets/curso/tema5/12.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema5/13.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Además, facilita una mejor comunicación con los demás. Al identificar en qué sistema se encuentra otra persona, por ejemplo, en el auditivo, podemos ingresar a ese sistema y adaptarnos a su lógica. Estos sistemas influyen en el aprendizaje y la comunicación, puesto que cada persona puede tener una preferencia por uno de ellos, lo que afecta su estilo de aprendizaje y la forma en que adquiere conocimientos (Accresio, 2020).
    
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema5/14.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Además, facilita una mejor comunicación con los demás. Al identificar en qué sistema se encuentra otra persona, por ejemplo, en el auditivo, podemos ingresar a ese sistema y adaptarnos a su lógica. Estos sistemas influyen en el aprendizaje y la comunicación, puesto que cada persona puede tener una preferencia por uno de ellos, lo que afecta su estilo de aprendizaje y la forma en que adquiere conocimientos (Accresio, 2020).
          

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
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/283011?page=1 " target="_blank" rel="noopener noreferrer") Pellicer, I. (2024). Programación NeuroEF: la ciencia del cerebro en tus clases de Educación Física: (1 ed.). Editorial INDE. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=YV-pQY1Vy14 " target="_blank" rel="noopener noreferrer") NEWMEDIA UFM. (2022, 23 de septiembre). Sistema límbico vs. corteza prefrontal [Vídeo]. YouTube. 



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
