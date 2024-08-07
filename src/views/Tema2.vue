<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Proceso de selección
    .row.bg-c5.mb-5
      .col-12
        .px-5
          p.mb-5(data-aos="fade-right") Dentro del proceso de selección,  se encuentran varias etapas, las cuales son:
          .row.justify-content-center.mb-5
            .col-lg-9(data-aos="fade-left")
              .titulo-sexto.color-acento-contenido
                p.mb-0 #[b Figura 1.] Etapas o pasos en el proceso de selección
              figure.d-none.d-lg-block
                img(src='@/assets/curso/tema2/img1.svg', style='width: 600px', alt='Imagen que presenta las etapas o pasos en el proceso de selección.').m-auto
              figure.d-block.d-lg-none
                img(src='@/assets/curso/tema2/img1m.svg', style='width: 240px', alt='Imagen que presenta las etapas o pasos en el proceso de selección.').m-auto
          p.mb-0(data-aos="fade-right") Ahora, ampliemos la información y conozcamos un poco más sobre estas etapas.
    .row.mb-5(data-aos="fade-down")
      .col-auto.bg-c6
        .row.align-items-end
          .col-auto
            figure
              img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
          .col
            h2.mb-0 Análisis de necesidades
    p(data-aos="fade-right") Esta primera etapa se basa en el proceso de selección, el cual busca realizar estudios en los puestos de trabajo, con el fin de proveer el talento humano con las mejores habilidades, destrezas y capacidades físicas e intelectuales, que brinden el mejor desarrollo en las organizaciones.
    p.mb-5(data-aos="fade-right") Encontramos dos tipos de selección:
    .row.bg-c7
      .col-12
        .px-5
          .row.justify-content-center.mb-5
            .col-md-8.col-xl-4.mb-4.mb-xl-0(data-aos="fade-right")
              .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = true")
                .indicador--hover(v-if="indicadorTarjetaFlip")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img3.png')})`}")
                  .tarjeta-flip__contenido.p-4.p-xl-5
                    .row.align-items-center.h-100
                      .col-12
                        h3.text-center.text-white Interna
                        p.text-center.text-white Se distingue porque se realiza, como su nombre lo indica, al interior de las organizaciones, a través de convocatorias, recomendación de los líderes y banco de hojas de vida.
            .col-md-8.col-xl-4.mb-4.mb-xl-0(data-aos="fade-left")
              .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = true")
                .tarjeta-flip__contenedor
                  .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img4.png')})`}")
                  .tarjeta-flip__contenido.p-4.p-xl-5
                    .row.align-items-center.h-100
                      .col-12
                        h3.text-center.text-white Externa
                        p.text-center.text-white Se reconoce porque es abierta y presentada en avisos clasificados, bolsas de empleo, bases de datos de universidades e incluso, redes sociales.
          .row.mb-5(data-aos="fade-down")
            .col-auto.bg-c6
              .row.align-items-end
                .col-auto
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
                .col
                  h2.mb-0 Reclutamiento
          .row.justify-content-center.mb-5
            .col-md-8.col-lg-12.shadow.bg-c8(data-aos="fade-left")
              .row.align-items-center
                .col-lg-8.order-2.order-lg-1
                  .p-4
                    .row.align-items-center
                      .col-auto.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/tema2/img4.svg', style='width: 80px', alt='').m-auto
                      .col
                        P.mb-0 Con este procedimiento, se conoce el interés que tiene el solicitante de obtener el empleo. Contiene la información suficiente para realizar la entrevista inicial.
                .col-lg-4.mb-4.mb-lg-0.order-1.order-lg-2
                  figure
                    img(src='@/assets/curso/tema2/img6.png', style='width: 160px', alt='').m-auto
          .row.mb-5(data-aos="fade-down")
            .col-auto.bg-c6
              .row.align-items-end
                .col-auto
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
                .col
                  h2.mb-0 Entrevista inicial
          p(data-aos="fade-right") Permite la evaluación del candidato para ofrecerle el empleo. Para esta entrevista existe una serie de puntos que deben ser tomados en cuenta. Antes de comenzar ,se deben determinar las preguntas que se le hará al solicitante.
          .row.align-items-center.mb-5.mb-lg-0
            .col-lg-8(data-aos="fade-right")
              p Durante la entrevista se recomienda:
              ul.lista-ul
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 Realizarla en un ambiente tranquilo.
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 Dedicarle toda la atención posible al aspirante.
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 Observar detenidamente la forma de hablar y el comportamiento del entrevistado.
            .col-lg-4(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema2/img7.png', style='width: 500px', alt='').m-auto
          p.mb-5 Existen diferentes tipos de entrevista, como son:
    .row.justify-content-center
      .col-lg-8(data-aos="fade-up")
        .row.justify-content-center.mb-3.mb-lg-5(data-aos="fade-down")
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema2/img5.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Entrevista preliminar]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema2/img6.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Entrevista personal]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema2/img7.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Entrevista grupal]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema2/img8.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Entrevista técnica]
    .row.bg-c9.mb-5
      .col-12
        .px-5
          .row.mb-5(data-aos="fade-down")
            .col-auto.bg-c6
              .row.align-items-end
                .col-auto
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
                .col
                  h2.mb-0 Pruebas
          p(data-aos="fade-right") Con ellas se evalúan, de una manera muy general, las capacidades y aptitudes que tienen los candidatos.
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6(data-aos="fade-right")
              p Los tipos de pruebas son:
              ul.lista-ul
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 De personalidad.
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 De aptitud.
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 De conocimiento.
                li.d-flex
                  i.fas.fa-check-circle(style="color: #8746F8")
                  |
                  p.mb-0 De muestreo de trabajo.
            .col-lg-4(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema2/img9.svg', style='width: 500px', alt='').m-auto
          .row.mb-5(data-aos="fade-down")
            .col-auto.bg-c6
              .row.align-items-end
                .col-auto
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
                .col
                  h2.mb-0 Investigación de antecedentes y verificación de referencias
          .row.justify-content-center
            .col-lg-8(data-aos="fade-left")
              .p-4.bg-c1
                .row.align-items-center
                  .col-md-auto.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema2/img10.svg', style='width: 100px', alt='').m-auto
                  .col
                    p.mb-0 Este procedimiento pretende comprobar la veracidad de la información proporcionada por el candidato en el cuestionario de solicitud y en la entrevista.
    .row.mb-5(data-aos="fade-down")
      .col-auto.bg-c6
        .row.align-items-end
          .col-auto
            figure
              img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
          .col
            h2.mb-0 Exámenes físicos
    p(data-aos="fade-right") Es prioritario que el examen físico reconozca todo un conjunto de evaluaciones físicas que proporcionan los resultados sobre el estado de salud en el que se encuentra el aspirante.
    p.mb-5(data-aos="fade-right") Los tipos de exámenes son:
    .row.justify-content-center.mb-0.mb-lg-5(data-aos="fade-left")
      .col-10.col-md-6.col-lg-3.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema2/img11.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b.txt-c1 Examen ocupacional.]
      .col-10.col-md-6.col-lg-3.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema2/img12.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b.txt-c1 Examen de laboratorio:]
              p.text-center.text-white.mb-0 #[b parcial de orina, serología.]
      .col-10.col-md-6.col-lg-3.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema2/img13.svg' alt='AvatarTop')
          .tarjeta.color-primario
            .p-4
              p.text-center #[b.txt-c1 Exámenes específicos y ocupacionales:]
              p.text-center.text-white.mb-0 #[b cuadro hemático, audiometría, optometría, electrocardiograma, colesterol, triglicéridos.]
    .row.mb-5(data-aos="fade-down")
      .col-auto.bg-c6
        .row.align-items-end
          .col-auto
            figure
              img(src='@/assets/curso/tema2/img2.svg', style='width: 50px', alt='').m-auto
          .col
            h2.mb-0 Vinculación y contratación
    .row.justify-content-center
      .col-md-8.col-lg-12.shadow.bg-c8(data-aos="fade-right")
        .row.align-items-center
          .col-lg-8.order-2.order-lg-1
            .p-4
              .row.align-items-center
                .col-auto.d-none.d-lg-block
                  figure
                    img(src='@/assets/curso/tema2/img14.svg', style='width: 80px', alt='').m-auto
                .col
                  P.mb-0 Finalmente y superada todas las etapas en el proceso de selección, esta parte es la culminación, en la que la organización dispone del proceso de contratación.
          .col-lg-4.mb-4.mb-lg-0.order-1.order-lg-2
            figure
              img(src='@/assets/curso/tema2/img9.png', style='width: 160px', alt='').m-auto

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
