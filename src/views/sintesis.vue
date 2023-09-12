<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 El direccionamiento estratégico se refiere a los planes que deben aplicar empresas del sector salud para que  avance hacia su visión y cumpla sus objetivos. Garantiza de gestión de la entidad ofrezca información al usuario de acuerdo con necesidades y portafolio de servicios de salud y que los propietarios y la dirección puedan comunicar la importancia del trabajo de los empleados y su contribución a la consecución de los objetivos empresariales.


    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="El mapa conceptual recoge el resumen de los temas abordados en el componente denominado: Direccionamiento estratégico que mediante el reconocmiento y la comprensión, permite a la organización a través de la misión, visión, y los objetivos brindar una información clara y concreta sobre el portafolio de servicios que posee.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
