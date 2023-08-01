<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Fortalezas, Oportunidades, Debilidades y Amenazas (matriz FODA)

    p La matriz FODA o DOFA (Fortalezas, Oportunidades, Debilidades y Amenazas), es una importante herramienta de diagnóstico, que contribuye con la formulación de estrategias para intervenir la empresa. Las siglas provienen del acrónimo en inglés SWOT (Strenghts, Weaknesses, Opportunities, Threats).
    p.mb-5 Algunas de sus características son reconocibles en la siguiente figura:
    
    .row.justify-content-md-center.px-5
      .col-10
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 12
          span Características FODA
        figure.mb-5
          img(src="@/assets/tema4/img-1.svg")     

        p.text-center.mb-5 Nota. SENA (2021).

        
</template>

<script>
export default {
  name: 'Tema3',
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

<style lang="sass" scoped></style>
