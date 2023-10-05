<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Organigrama
    p(data-aos="fade-left") El organigrama institucional permite a la organización tener una estructura establecida con todas las áreas que componen la entidad, teniendo en cuenta los requerimientos de: recursos humanos, niveles de centralización y descentralización, grados de decisión, autoridad otorgada y complejidad de las unidades. Para tener claridad frente a los aspectos generales del organigrama, se deben contemplar los siguientes aspectos:
    .row.justify-content-center.align-items-center
      .col-lg-11.p-4(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-4
          p.mb-0 #[b Figura 10]. Organigrama
        figure.mb-3
          img(src="@/assets/tema2/img-1.svg", alt='Figura 10. Muestra ejemplo del organigrama de una empresa donde se representa su estructura interna y los elementos esenciales de la misma.')
        p.text-center Nota. SENA (2021).
    p.text-bold(data-aos="fade-right").mb-5 Según el tipo de información, los organigramas se clasifican en:
    .row.fond3.p-3.p-lg-4.mb-5(data-aos="fade-down")
      SlyderA(tipo="b")
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-2.svg", style="width:550px", alt='Imagen de un organigrama analítico.').m-auto
            p.text-center.mb-0 #[b Analíticos:] muestran datos detallados y específicos de la organización.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-3.svg", style="width:750px", alt='Imagen que muestra la estructura de un organigrama informativo que tiene: Gerente, Presidente, Secretaria, Productos, Marketing, Recursos humanos, Finanzas.').m-auto
            p.text-center.mb-0 #[b Informativos:] solo muestran la información más relevante.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-4.svg", style="width:750px", alt='Imagen que muestra la estructura de un organigrama formal, donde las áreas tienen gerentes existe presidente pero las decisiones se someten a aprobación de la junta directiva.').m-auto
            p.text-center.mb-0 #[b Formales:] representan la parte formal de una empresa y requieren de aprobación previa.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-5.svg", style="width:750px", alt='Imagen de un tipo de organigrama informal, es decir su estructura tiene una dirección no hay gerentes por área, pero cada persona conoce sus funciones dentro del esquema.').m-auto
            p.text-center.mb-0 #[b Informales:] no han sido aprobados por la empresa; sin embargo, cada integrante conoce sus funciones.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-6.svg", style="width:750px", alt='Organigrama de tipo jerárquico, sostiene un diseño piramidal donde se cuenta con gerente y direcciones de área como segunda instancia luego compras y diversos servicios y finalmente lo operativo.').m-auto
            p.text-center.mb-0 #[b Jerárquico:] depende del poder o control dentro de la empresa (de mayor a menor), siguiendo un diseño piramidal.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-7.svg", style="width:750px", alt='Imagen que expone el tipo de organigrama matricial, que cuenta con jefes de áreas, directores de proyectos y los encargados de la ejecución de estos proyectos.').m-auto
            p.text-center.mb-0 #[b Matricial:] empresas con más de un director, o más de un responsable por proyecto, o más de un superior por departamento o trabajador.
        .row.m-1
          .col-12
            figure.mb-3
              img(src="@/assets/tema2/img-8.svg", style="width:750px", alt='Imagen que expone un tipo de organigrama plano donde se cuenta con un director y trabajadores.').m-auto
            p.text-center.mb-0 #[b Plano:] organigrama sin cargos de mandos intermedios, dos roles: directivos y empleados.
    p(data-aos="fade-right").mb-5 Los organigramas pueden tener diversas representaciones gráficas, lo que ayuda en la comprensión de los elementos que los componen. Acorde con esto, se pueden identificar por representación visual, los siguientes organigramas:
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta-morada")(data-aos="fade-right")
      .row(titulo="Organigrama vertical")
        figure
          img(src='@/assets/tema2/img-9.svg', alt='Imagen de ejemplo de un organigrama vertical donde en la parte superior esta el nombre de la directora general y hacía abajo en ambos sentidos el nombre de los directores de áreas.')
      div(titulo="Organigrama horizontal")
        figure
          img(src='@/assets/tema2/img-10.svg', alt='Imagen que muestra la forma de un organigrama horizontal, que viene de izquierda a derecha en jerarquía, comenzando a mano izquierda con el nombre del director general y a mano derecha los directores de área.')
      div(titulo="Organigrama circular")
        figure
          img(src='@/assets/tema2/img-11.svg', alt='Imagen que expone la estructura del organigrama circular, que como su nombre lo indica viene en el centro el gerente general y a su alrededor en círculo los gerentes de área y en círculo final  los analistas, técnicos y supervisores.')

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({}),
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
