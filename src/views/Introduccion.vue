<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.align-items-center
      .col-lg-8.order-2.order-lg-1(data-aos="fade-right")
        p La selección del talento humano es un proceso que consta de varias etapas. La finalidad es escoger o lograr proveer mediante el reclutamiento, al mejor candidato para la organización.
        .row.mb-3
          .col-12
            .p-4.bg-c1
              p.mb-0 De acuerdo con el perfil o la vacante que se quiere proveer y las características de la organización que se realice el proceso, los procedimientos que se adelanten podrán tener ciertos grados de dificultad, es decir, habrá empresas en las que el proceso de selección tendrá una forma más larga y una serie mayor de pruebas de selección, esto ocurre por políticas internas que la organización tiene establecidas.
        .row
          .col-12
            .p-4.bg-c2
              p.text-white.mb-0 Cabe resaltar que en la actualidad, existen organizaciones especializadas o personas naturales que ofrecen el servicio de cazatalentos, conocidas como outsourcing, lo que permite a las organizaciones dedicarse a su filosofía misional.
      .col-lg-4.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/intro/img1.svg', style='width: 350px', alt='').m-auto
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
