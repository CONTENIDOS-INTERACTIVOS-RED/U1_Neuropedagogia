<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Predominancia cerebral'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-5 Para comenzar con el estudio de la temática, lo invitamos a ver el siguiente video.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/9cqLwqWDCzs?si=F1b2M6SlLRnGqFf9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Preferencia manual y factores hereditarios
    
    p.mb-5 La comprensión de la preferencia manual y su relación con la lateralización cerebral ofrece una mirada profunda a la interacción entre genética, ambiente y neurodesarrollo.

    .bg-full-width.bg-color-7.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.text-white.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Preferencia manual y factores hereditarios
            p.mb-4(data-aos="fade-right") En el PDF <b>Preferencia manual y factores hereditarios</b>, se exploran los fundamentos neuroanatómicos y evolutivos que explican la dominancia lateral, así como su impacto en el aprendizaje, la conducta y las prácticas educativas. Esta revisión teórica y empírica permite identificar cómo el cerebro se especializa y cómo esta especialización puede orientar enfoques pedagógicos más integrales e inclusivos.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_6.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Preferencia manual y factores hereditarios.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/1.png', alt='')

    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Características, procesos de pensamiento y competencias de los cuadrantes cerebrales 
    
    p.mb-5 Según Ned Herrmann, citado por Alonso y Mendieta (2017), las características de los cuadrantes, son:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/2.png")
            .col-lg-7
              h5 Cortical izquierdo (CI)
              p Este cuadrante se caracteriza por ser frío, distante, y tener pocos gestos. Su voz es elaborada y es intelectualmente brillante, capaz de evaluar y criticar. Manifiesta ironía, competitividad e individualismo. Entre los procesos cognitivos que desarrolla se encuentran el análisis, el razonamiento, la lógica, el rigor y la claridad. Prefiere modelos y teorías, colecciona hechos y trabaja a partir de hipótesis, utilizando un lenguaje preciso. Sus competencias incluyen la abstracción y la resolución de problemas.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/3.png")
            .col-lg-7
              h5 Límbico izquierdo (LI)
              p Las características de este cuadrante son la introversión, emotividad, control, minuciosidad y un enfoque maniático. Tiende a homologar, tiene una inclinación por las fórmulas, es conservador y leal, y defiende su territorio. Está vinculado a la experiencia y tiene una afinidad por el poder. Los procesos cognitivos que desarrolla incluyen la planificación, formalización, estructuración, definición de procedimientos, secuencialidad, verificación, ritualismo y método. Sus competencias abarcan la administración, el sentido organizativo, la implementación y liderazgo, así como habilidades de oratoria y dedicación al trabajo.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/4.png")
            .col-lg-7
              h5 Límbico derecho (LD)
              p Este cuadrante se define por ser extrovertido, emotivo, espontáneo, gesticulador, lúdico y hablador. Es espiritual y tiende a ser aquiescente, reaccionando mal a las críticas. Fomenta la integración a través de la experiencia y se mueve por el principio del placer, mostrando una fuerte implicación afectiva. Trabaja basado en sentimientos, escucha y formula preguntas, y busca compartir y vivir en armonía, evaluando comportamientos. Sus competencias son relacionales, incluyendo el contacto humano, el diálogo, la enseñanza, trabajo en equipo y expresión tanto oral como escrita.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/5.png")
            .col-lg-7
              h5 Cortical derecho (CD)
              p Este cuadrante se distingue por su originalidad, sentido del humor, gusto por el riesgo y capacidad espacial. Disfruta de las discusiones, tiene una visión futurista y presenta un discurso brillante, mostrando independencia. Los conceptos que desarrolla incluyen la conceptualización, síntesis, imaginación, globalización, intuición, visualización, asociación e integración de imágenes y metáforas. Sus competencias abarcan la creación, el espíritu empresarial, la visión futurista, el arte y la investigación.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/6.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") Se identifican las características, procesos y habilidades de las personas, según su dominancia cerebral. Aquellas personas que tienen una predominancia cortical (izquierdo-derecho) son vistas como cognitivas; los que presentan dominancia límbica (izquierdo-derecho) se consideran viscerales. Quienes predominan en el hemisferio izquierdo (cortical-límbico) son catalogados como realistas, mientras que aquellos que predominan en el hemisferio derecho (cortical-límbico) son considerados idealistas.
    
        .bg-color-5.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/7.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 En conclusión, la dominancia cerebral y el modelo de los cuadrantes de Herrmann, ofrecen perspectivas complementarias sobre el funcionamiento del cerebro y su impacto en el aprendizaje y la conducta humana. Mientras que la dominancia cerebral explica la especialización funcional de los hemisferios, el modelo de los cuadrantes amplía esta visión, reconociendo que el pensamiento humano se organiza en diferentes estilos cognitivos.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/8.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-8.p-4.h-100(data-aos="fade-left")
          p.mb-0 Ambos enfoques destacan la importancia de integrar los distintos procesos mentales para potenciar el desarrollo personal y educativo. La enseñanza tradicional, al priorizar el pensamiento lógico y racional del hemisferio izquierdo, ha dejado de lado la creatividad, la intuición y la emoción, aspectos esenciales para un aprendizaje equilibrado. Comprender estas teorías permite diseñar estrategias más inclusivas que consideren las diferencias individuales, promoviendo una educación más holística y eficiente (Alonso y Mendieta, 2017- Silva Rodríguez y Escobar Izquierdo, 1996).

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/118682?page=1" target="_blank" rel="noopener noreferrer") Bueno i Torrens, D. (2019). Neurociencia para educadores: todo lo que los educadores siempre han querido saber sobre el cerebro de sus alumnos y nunca nadie se ha atrevido a explicárselo de manera comprensible y útil: ( ed.). Ediciones Octaedro, S.L.  


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=Mln5fduVCOo" target="_blank" rel="noopener noreferrer") Rosa María Rodríguez Coach. (2018, 3 de marzo). Cuál es tu hemisferio cerebral predominante. [Vídeo]. YouTube.  



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema3',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
