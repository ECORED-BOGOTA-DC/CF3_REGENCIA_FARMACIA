<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Fortalezas, Oportunidades, Debilidades y Amenazas (matriz FODA)
    p(data-aos="fade-right") La matriz FODA o DOFA (Fortalezas, Oportunidades, Debilidades y Amenazas), es una importante herramienta de diagnóstico, que contribuye con la formulación de estrategias para intervenir la empresa. Las siglas provienen del acrónimo en inglés SWOT (Strenghts, Weaknesses, Opportunities, Threats).
    p(data-aos="fade-right") Algunas de sus características son reconocibles en la siguiente figura:
    .row.justify-content-center(data-aos="fade-left")
      .col-lg-11
        .titulo-sexto.color-acento-contenido.mb-4
          p.mb-0 #[b Figura 12]. Características FODA
        figure.mb-4
          img(src="@/assets/tema4/img-1.svg", alt='Figura 12. Muestra las características de la matriz DOFA o FODA, que significa: fortalezas, oportunidades, debilidades y amenazas. Las características para cada una de estas son:<br>Fortalezas: funciones que se realizan correctamente.<br>Oportunidades: elementos potenciales de crecimiento.<br>Debilidades: factores que hacen vulnerable a la organización y finalmente<br>Amenazas: que son fuerzas ambientales no controlables, que representan un problema.' style="width:900px").m-auto
        p.text-center.mb-0 Nota. SENA (2021).
        
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
