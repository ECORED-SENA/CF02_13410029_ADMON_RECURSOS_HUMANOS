<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Importancia de la selección del talento humano
    .row.align-items-center.bg-c3.mb-5
      .col-lg-5.ps-0.d-none.d-lg-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1/img1.png', style='width: 450px', alt='')
      .col-lg-7(data-aos="fade-left")
        .p-4.p-lg-0
          p La gerencia de talento humano está comprometida con la realización del proceso de selección, cuando se tiene la necesidad de la consecución de un perfil para cubrir una vacante. Es de gran responsabilidad tomar la mejor decisión en el momento de escoger al candidato. Para ello, esta gerencia se apoyará en técnicas establecidas por expertos, como los manuales (funciones y procedimientos).
          p.mb-0 Es necesario conocer los procedimientos a la hora de elegir cuál es el perfil que se necesita para proveer un cargo, logrando de esta manera dar cumplimiento a cada una de las funciones inherentes al mismo. Nuevamente, la alta gerencia del talento humano debe tener estructurado el proceso para llegar a realizar la selección y contar con el futuro colaborador idóneo para cubrir la vacante.
    .row.align-items-center.mb-5
      .col-lg-10.order-2.order-lg-1(data-aos="fade-right")
        .p-4.bg-c4
          p Por ello, los manuales de funciones y procedimientos de los cargos, deben estar diseñados, estructurados y elaborados. Esto permite contar con las pautas necesarias para diseñar la oferta del cargo con sus respectivas descripciones.
          p.mb-0 A continuación, conozcamos los pasos en la selección de personal:
      .col-lg-2.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/img1.svg', style='width: 150px', alt='').m-auto
    .row.justify-content-center
      .col-lg-8
        .row.justify-content-center.mb-3.mb-lg-5(data-aos="fade-down")
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema1/img2.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Análisis del cargo.]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema1/img3.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Reclutamiento de candidatos.]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema1/img4.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Selección de candidatos.]
          .col-10.col-md-5.col-lg-3.mb-4.mb-lg-0
            .p-4.bg-c2.h-100
              figure.mb-3
                img(src='@/assets/curso/tema1/img5.svg', style='width: 60px', alt='').m-auto
              p.text-center.text-white.mb-0 #[b Decisión de contratación.]
        .bloque-texto-d.color-secundario.p-4(data-aos="fade-right")
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            p #[b Cuando se tiene claridad en la necesidad de la organización, se puede llegar a hacer un buen proceso desde el momento de hacer la publicación y llegar a tener un buen filtro en la recolección de las hojas de vida, para avanzar de manera eficiente y no tener retrasos ni pérdida de tiempo al momento de realizar el proceso de selección.]
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .p.mb-0 (Manosalva, 2009)
      
</template>

<script>
export default {
  name: 'Tema1',
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
