<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Servicio al cliente 

    p(data-aos="fade-right") Un cliente se define como la persona u organización que realiza una compra. Puede comprar y disfrutar la propiedad o el servicio que compró usted mismo, o puede comprarla para una tercera persona. Los clientes son la parte más importante de un negocio. Con base en lo anterior, un cliente de atención médica puede definirse como una persona que manifiesta necesidades o deseos para sí mismo, o para los demás.
    p.mb-5(data-aos="fade-left") Se puede recordar cuáles son los tipos de clientes en la siguiente figura:

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-right")
      h5 Figura 16.
      span Tipos de clientes


    .row.mb-5(data-aos="fade-left")
      .col-12
        p.mb-0 #[strong.span.square a] #[strong Según su nivel de fidelización:]  
   
        
    .row.mb-5
      .col-md-6.col-lg.tarjeta--tabla.p-4.r-r.tt
        .row.justify-content-center.mb-3
          .col-10
            img(src='@/assets/tema8/img-1.svg', alt='Imágen decorativa')

        p.text-center #[strong Cliente ocasional:] sus adquisiciones no tienen una frecuencia establecida.

      .col-md-6.col-lg.tarjeta--tabla.p-4.r-r.tt
        .row.justify-content-center.mb-3
          .col-10
            img(src='@/assets/tema8/img-1-.svg', alt='Imágen decorativa')
        
        p.text-center #[strong Cliente de compra regular:] la mayor parte de las compras las realiza en el establecimiento, pero también hay momentos donde adquiere en otra parte.


      .col-md-6.col-lg.tarjeta--tabla.p-4.r-r.tt
        .row.justify-content-center.mb-3
          .col-10
            img(src='@/assets/tema8/img-1.svg', alt='Imágen decorativa')
        
        p.text-center #[strong Cliente de compra frecuente:] normalmente adquiere los productos del establecimiento.


      .col-md-6.col-lg.tarjeta--tabla.p-4.tt
        .row.justify-content-center.mb-3
          .col-10
            img(src='@/assets/tema8/img-1-.svg', alt='Imágen decorativa')
        
        p.text-center #[strong Clientes-embajadores:] son los clientes frecuentes que, además, hacen propaganda con sus conocidos, sobre la calidad de nuestros productos. 

    p.text-center.mb-5 Nota. SENA (2021).

    .row
      .col-12(data-aos="fade-left")
        p.mb-5 #[strong.span.square B] #[strong Según su comportamiento:]  

    .row.justify-content-center.align-items-center.mb-5
      LineaTiempoA.color-acento-contenido.mb-5(:datos="datosLineaTiempoA")       

    .row.justify-content-center.align-items-center.mb-5
      LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")


    .row.mb-5
      .col-12(data-aos="fade-left")
        p.mb-0 #[strong.span.square c] #[strong Según su satisfacción:] 

    .tarjeta.tarjeta--azul.p-4.mb-5.fond9
      SlyderA
        .row.p-5
          figure
              img(src='@/assets/tema8/img-12.svg', alt='Imágen decorativa')
              

        div
          figure
              img(src='@/assets/tema8/img-13.svg', alt='Imágen decorativa')
              

        .row
          figure
              img(src='@/assets/tema8/img-14.svg', alt='Imágen decorativa')
             

        div
          figure
              img(src='@/assets/tema8/img-15-.svg', alt='Imágen decorativa')
              
        div
          figure
              img(src='@/assets/tema8/img-16.svg', alt='Imágen decorativa')
              

    p Para entender mejor su concepto, a continuación se listan los factores que intervienen en el servicio al cliente:
    .col-md-10.img-c 
      PasosA.color-acento-contenido.mb-5(tipo="n")
        .row(data-aos="fade-left")
          h3 Amabilidad
          p Hace referencia al trato amable, cortés y servicial. 
          
        .row(data-aos="fade-right")
          h3 Atención personalizada
          p Cuando el profesional de la salud le indica que ingrese a consulta médica y lo acompaña durante todo su proceso.
        .row(data-aos="fade-left")
          h3 Rapidez en la atención
          p Cuando se cuenta con procesos simples y eficientes, cuando se cuenta con una cantidad suficiente de personal, cuando se le capacita al personal para que brinde una rápida atención, etc.
        .row(data-aos="fade-right")
          h3 Ambiente agradable
          p Cuando los trabajadores le brindan al usuario un trato amable y amigable.
        .row(data-aos="fade-left")
          h3 Comodidad
          p Cuando las instalaciones de la Institución cuentan con espacios amplios y cómodos.
        .row(data-aos="fade-right")
          h3 Seguridad
          p Cuando se cuenta con suficiente personal de seguridad, cuando se tienen claramente marcadas las zonas de seguridad, cuando se tienen claramente señalizadas las vías de escape, cuando se cuenta con botiquines médicos, etc.
        .row(data-aos="fade-left")
          h3 Higiene
          p Por ejemplo, cuando se evidencian los baños de la institución siempre limpios, con todos sus implementos de higiene como jabón, papel, etc., pisos y sanitarios aseados.                                      



    .row.justify-content-center.mb-5.fond2.align-self-center.mx-3
      .col-5
          img(src="@/assets/tema8/img-17.svg", alt='Imágen decorativa') 
      .col-7.align-self-center.p-5.px-0
          p.mb-0.mx-5
            b El buen servicio al cliente debe estar presente en todos los servicios que solicite el usuario. Debe prevalecer la interacción con el usuario, desde el saludo hasta el final de la atención del paciente y su posterior egreso. Para esto es necesario capacitar y motivar permanentemente, no solo al personal que está en contacto con el usuario sino en general a todo el talento humano de la institución, para la prestación de un servicio con calidad.       
    br
    .row.col-8.img-c.mb-5 
      .row.my-5
        .col-7
          p.mb-4(data-aos="fade-up") En el protocolo de atención al ciudadano sector salud del Ministerio de Salud y Protección Social, es muy importante tener en cuenta: 

          ul.lista-ul--color
            li(data-aos="fade-up")
              i.ii.fas.fa-atom  
              | Atributos del buen servicio. 
            li(data-aos="fade-up")
              i.ii.fas.fa-atom  
              | Actitud.
            li(data-aos="fade-up") 
              i.ii.fas.fa-atom  
              | Atención a personas alteradas

        .col-5.img-c
          figure
                img(src='@/assets/tema8/img-18.svg', alt='Imágen decorativa')

    .row.justify-content-around.align-items-center.mb-5
      .col-lg-10.justify-content-md-center.align-self-center
        .tarjeta.color-primario.mb-5.fond1.px-4.p-3.degra
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/tema8/img-19.svg", alt='Imágen decorativa')
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.bb Protocolo de atención al ciudadano sector salud
                  p.mb-1.texto-blanco Conoce el protocolo de atención establecido para el ciudadano, en el cual se especifican los enfoques para este.
                  
                .col-sm-auto
                  a.boton.bb(:href="obtenerLink('/downloads/protocolo-atencion-ciudadano-sector-salud.pdf')" target="_blank")
                    span.px-4 Descargar  
                    i.fas.fa-file-download 

    .row.mb-5
      .row.traslape2.mb-5
          .col-lg-7.col-z1.f-right(data-aos="fade-left")
            img(src="@/assets/tema8/img-20.svg" alt="Mujer farmacéutica en dispensario de fármacos")
          .col-lg-4_5.col-z2.f-left(data-aos="fade-right")
            .contenedor3c.p-4
              p Los elementos del servicio al cliente son:
              p.mb-0 #[strong Contacto cara a cara] 
              p Brindar atención personalizada. 

              p.mb-0 #[strong Relación clientelar]
              p Fortalecer la relación con el usuario, es clave en los servicios de salud.

              p.mb-0 #[strong Correspondencia]
              p Fortalece la identificación entre ambos y la resolución de los problemas que se presenten.

              p.mb-0 #[strong Reclamos y cumplidos]
              p El cliente debe contar con alguna línea que le permita ejercer sus deberes y derechos.

              p.mb-0 #[strong Instalaciones]
              p Debe brindársele al usuario la seguridad y acogida durante su asistencia a la Institución.

    p.mb-5(data-aos="fade-left") Durante el proceso de prestación del servicio, se debe generar un ciclo de servicio adecuado, el cual debe estar enfocado en los siguientes aspectos reconocibles en la figura:  

    .row.justify-content-center.align-items-center.mb-3
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 17.
          span Ciclo de servicio
                 
    .row.col-10.img-c
      .row.justify-content-around.align-items-center 
        .col-12.col-lg-auto.justify-content-md-center.mb-4.mx-3  
          figure.mb-3
            img.img-400(src="@/assets/tema8/img-21.svg", alt='Figura 17. Muestra el ciclo de servicio que contiene 5 aspectos que son:<br>1. Identificación de los momentos de verdad.<br>2. Requerimientos de clientes.<br>3. Planes de acción enfocados a la atención y solución de casos detectados.<br>4. Priorización de áreas.<br>5. Evaluación de la satisfacción del cliente.')  

          p.text-center.mb-5 Nota. SENA (2021).

        .col-lg.justify-content-md-center.align-self-center
          .cajon.color-secundario.p-4.mb-4.fond1.py-5(data-aos="flip-left")            
              p.mb-0 #[strong Tenga en cuenta:] momento de verdad es el momento exacto en el que un cliente contacta con nuestro servicio y se forma una opinión sobre la calidad del servicio, basado en este contacto. El momento de la verdad se puede revelar no solo directamente, sino también a través de todos los canales, como la comunicación técnica y la comunicación informal.
        p(data-aos="fade-left") Existen unos síntomas y signos que muestran que la estructura de servicio al cliente tiene falencias. Estos son, ver tabla 2:

    .row.justify-content-center.align-items-center.mb-3
      .col-lg-11
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span Síntomas y signos de mal servicio al cliente
    
    .tabla-b.color-acento-contenido.mb-5      
        table(alt="Expone todos los síntomas y los signos de un mal servicio al cliente.")
          tr.tabla-b__header
            td
              strong Síntoma
            td
              strong Signo
          tr
            td
              strong Quejas permanentes de clientes y usuarios
            td
              ul.lista-ul--color.fa-ul2
                li 
                  i.ii.fas.fa-atom  
                  | Allá nunca contestan.
                li 
                  i.ii.fas.fa-atom  
                  | Me pasan de un lado al otro. 
                li 
                  i.ii.fas.fa-atom  
                  | Todos me dicen cosas distintas. 
                li 
                  i.ii.fas.fa-atom  
                  | No parece que me contestaran de una empresa.
                li 
                  i.ii.fas.fa-atom  
                  | Siempre me dejan esperando. 

          tr
            td
              strong Base de datos no confiable
            td
              ul.lista-ul--color.fa-ul2
                li 
                  i.ii.fas.fa-atom  
                  | Cada asesor maneja su archivo de clientes. 
                li 
                  i.ii.fas.fa-atom  
                  | Dificultad para decidir cuál base de datos usar para ejecutar diversos análisis.
                li 
                  i.ii.fas.fa-atom  
                  | No se está seguro de qué tan actualizada se encuentre.

          tr
            td
              strong La organización no aprende con el proceso
            td
              ul.lista-ul--color.fa-ul2
                li 
                  i.ii.fas.fa-atom  
                  | No se utilizan los casos de quejas y reclamos, para mejorar los procesos de negocio.
                li 
                  i.ii.fas.fa-atom  
                  | No se usan las preguntas frecuentes (PQRS), para ajustar las comunicaciones.
                li 
                  i.ii.fas.fa-atom  
                  | El proceso no es un semillero útil para suplir vacantes de otras dependencias.

          tr
            td
              strong No ha desarrollado todo el potencial de su proceso
            td
              ul.lista-ul--color.fa-ul2
                li 
                  i.ii.fas.fa-atom  
                  | Para mejorar la experiencia del cliente.
                li 
                  i.ii.fas.fa-atom  
                  | Para conocer mejor a sus clientes. 
                li 
                  i.ii.fas.fa-atom  
                  | Para vender más.
                li 
                  i.ii.fas.fa-atom  
                  | Para recuperar cartera.
                li 
                  i.ii.fas.fa-atom  
                  | Para fidelizar clientes.
                li 
                  i.ii.fas.fa-atom  
                  | Para promocionar su negocio. 
                li 
                  i.ii.fas.fa-atom  
                  | Para hacer encuestas.
                li 
                  i.ii.fas.fa-atom  
                  | Para recibir quejas y reclamos.
                li 
                  i.ii.fas.fa-atom  
                  | Para resolver inquietudes.
                li 
                  i.ii.fas.fa-atom  
                  | Para solucionar requerimientos.
                li 
                  i.ii.fas.fa-atom  
                  | Para sistematizar información. 
                li 
                  i.ii.fas.fa-atom  
                  | Para actualizar y enriquecer las bases de datos.
                li 
                  i.ii.fas.fa-atom  
                  | Para apoyar a los equipos de ventas.
                li 
                  i.ii.fas.fa-atom  
                  | Para apoyar a sus canales.

          tr
            td
              strong Proceso difícil de gerenciar
            td
              ul.lista-ul--color.fa-ul2
                li 
                  i.ii.fas.fa-atom  
                  | Las instrucciones no se distribuyen entre los destinatarios. 
                li 
                  i.ii.fas.fa-atom  
                  | No sabe si los recursos que tiene son suficientes o no. 
                li 
                  i.ii.fas.fa-atom  
                  | No sabe como medir el proceso en sus diferentes aspectos.
                li 
                  i.ii.fas.fa-atom  
                  | Es complicado conocer los costos reales incurridos. 
                li 
                  i.ii.fas.fa-atom  
                  | Tiene dudas acerca de si es mejor hacerlo usted, o tercerizarlo. 
                li 
                  i.ii.fas.fa-atom  
                  | No cuenta con las herramientas adecuadas.
                li 
                  i.ii.fas.fa-atom  
                  | El proceso no marcha solo.
                li 
                  i.ii.fas.fa-atom  
                  | No monitorea la calidad del servicio. 
                li 
                  i.ii.fas.fa-atom  
                  | Realiza actividades propias del proceso, en diferentes dependencias. 
                li 
                  i.ii.fas.fa-atom  
                  | No sabe cuáles son las actividades del proceso.
                li 
                  i.ii.fas.fa-atom  
                  | No tiene ningún proceso que soporte el servicio al cliente.
                li 
                  i.ii.fas.fa-atom  
                  | No tiene ningún proceso que soporte el servicio al cliente.
                li 
                  i.ii.fas.fa-atom  
                  | La ausencia de una sola persona del grupo afecta el desempeño del negocio.
                li 
                  i.ii.fas.fa-atom  
                  | No cuenta con informes periódicos que reflejen la realidad del proceso.
                li 
                  i.ii.fas.fa-atom  
                  | No sabe si la tecnología que utiliza es adecuada para el momento de su negocio.

  
    .col-lg.justify-content-md-center.align-self-center.img-c.mb-5
        .col-10.cajon.color-secundario.p-4.mb-4.fond1.py-5.img-c(data-aos="flip-down")           
          p Se debe tener en cuenta #[strong que la satisfacción del cliente es muy importante para las instituciones médicas. Basado en su experiencia, se recomiendan los servicios de la organización a otros usuarios. También hay que decir que la satisfacción es una de las claves para incrementar la rentabilidad de una organización.]

    p(data-aos="fade-right") Actualmente, los usuarios utilizan diferentes unidades (EPS o sus operadores logísticos) y pueden elegir la unidad que mejor se adapte a su salud. Sin embargo, si tiene una experiencia de servicio satisfactoria, puede aumentar la cantidad de usuarios de EPS y empresas de logística y mejorar la calidad del servicio.
    p(data-aos="fade-left") La satisfacción del cliente se logra con las siguientes actividades:

    .row.justify-content-around.align-items-center.m-5.p-3.fond10.p-5
      .col-lg.justify-content-md-center.align-self-center

        ul.lista-ul--color.px-5.fa-ul2
          li 
            i.ii.fas.fa-atom  
            | Desarrollar un producto o servicio que satisfaga sus necesidades. 
          li 
            i.ii.fas.fa-atom  
            | Establecer comunicación directa.
          li 
            i.ii.fas.fa-atom  
            | Evaluar la satisfacción y mejorarla en función de estos resultados. 
          li 
            i.ii.fas.fa-atom  
            | Proporcionar muestras o realizar pruebas previas de productos y servicios. 
          li 
            i.ii.fas.fa-atom  
            | Continuar utilizando la experiencia del usuario. 
          li 
            i.ii.fas.fa-atom  
            | Mantener siempre a los empleados, con un trato favorable al cliente. 
          li 
            i.ii.fas.fa-atom  
            | No discutir con los clientes.
          li 
            i.ii.fas.fa-atom  
            | No prometer lo imposible. 
          li 
            i.ii.fas.fa-atom  
            | Evitar esperar el mayor tiempo posible. 
          li 
            i.ii.fas.fa-atom  
            | Brindar a los clientes, beneficios cuestionables.


      .col-12.col-lg-auto.justify-content-md-center.mb-4.p-0 
        figure
              img(src='@/assets/tema8/img-22.svg', alt='Imágen decorativa')


    p(data-aos="fade-right") Algunos instrumentos muy eficientes que se utilizan para conocer la satisfacción del cliente son:
    .row.justify-content-around.align-items-center
      .col-10
        .crd_02.mb-3(data-aos="fade-left")
          .crd_02__icon
            img(src="@/assets/tema8/img-23.svg", alt='Imágen decorativa').class          
          .crd_02__txt
            p.mb-0 #[strong Entrevista:] es el sistema de comunicación que permite conocer la opinión de otros sobre algún tema en específico. Esto implica conocimiento previo del entrevistado y objetivos planteados por parte del entrevistador.

        .crd_02.mb-3(data-aos="fade-left")
          .crd_02__icon
            img(src="@/assets/tema8/img-24.svg", alt='Imágen decorativa').class          
          .crd_02__txt
            p.mb-0 #[strong Encuesta:] es un instrumento usado para conocer la opinión de las personas que conforman un determinado sector. Estas encuestas ayudan a determinar qué le gusta y qué no les gusta a los clientes; áreas de posibles mejoras, incluso ayuda para saber qué otro tipo de necesidades tienen los clientes. 

        .crd_02.mb-3(data-aos="fade-left")
          .crd_02__icon
            img(src="@/assets/tema8/img-25.svg", alt='Imágen decorativa').class          
          .crd_02__txt
            p.mb-0 #[strong Buzón de sugerencias:] este instrumento permite a los usuarios depositar, de manera escrita, sus necesidades, recomendaciones, quejas, reclamos o incluso felicitaciones hacia la entidad o a las personas en específico, dependiendo del motivo por el cual se utiliza el buzón. Los buzones deben estar a la vista del público, tener fácil acceso y contar con los elementos necesarios para poder interponer la queja o sugerencia.       


</template>

<script>
export default {
  name: 'Tema8',
  data: () => ({
    datosLineaTiempoA: [
      {
        ano: '<img src="@/assets/componentes/ej-05.svg" />',
        titulo: 'Período Paleolítico',
        texto: 'Pieles, pelo de animales, hojas, huesos y conchas.',
      },
      {
        ano: '10.000 - 5.000 A.C.',
        titulo: 'Periodo Mesolítico',
        texto:
          'Broches hechos con hueso, abrigos, gorros, botas y zapatillas de cuero.',
      },
      {
        ano: '10.000 - 5.000 A.C.',
        titulo: 'Periodo Neolítico',
        texto: 'Vestimenta de fibras animales y vegetales, pulseras de marfil.',
      },
    ],
    datosLineaTiempoB: [
      {
        texto:
          '<b>Cliente amable:</b> su actitud es amigable, asiente con un sí a todo lo que se le dice, pero no muestra claridad en las cosas, por lo que la mejor estrategia es enseñarle pocos productos.',
        icono: require('@/assets/tema8/img2.svg'),
      },
      {
        texto:
          '<b>Cliente entusiasta:</b> es muy conversador y no siempre sus temas tienen que ver con la compra del producto, por lo que el vendedor es quien debe enfocar la conversación en el producto, pero con sutileza. ',
        icono: require('@/assets/tema8/img3.svg'),
      },
      {
        texto:
          '<b>Cliente reflexivo:</b> le gusta tener las cosas claras y la información completa, antes de realizar cualquier compra, porque es muy organizado. Requiere ser atendido con paciencia, tranquilidad y datos precisos del producto. ',
        icono: require('@/assets/tema8/img4.svg'),
      },
      {
        texto:
          '<b>Cliente indeciso:</b> no tiene muy claro si realizar la compra o no, por lo que pregunta mucho. Ante esto, se debe tener paciencia y explicarle todo lo que requiera sin presionarlo.',
        icono: require('@/assets/tema8/img5.svg'),
      },
      {
        texto:
          '<b>Cliente tímido:</b> no se acerca mucho y no sostiene miradas con el vendedor. Requiere sentirse en confianza, por lo que no se debe mirar muy fijamente a los ojos, o hacerle preguntas personales.',
        icono: require('@/assets/tema8/img6.svg'),
      },
      {
        texto:
          '<b>Cliente silencioso:</b> es de pocas palabras, pero muy buen escuchante de todo lo que se le dice. No manifiesta de entrada lo que necesita. Se debe ser amable, darle opciones y mostrar interés.',
        icono: require('@/assets/tema8/img7.svg'),
      },
      {
        texto:
          '<b>Cliente discutidor:</b> llega en actitud desafiante y soberbia. Ante este tipo de cliente se debe conservar la calma y evitar a toda costa caer en una discusión con él.',
        icono: require('@/assets/tema8/img8.svg'),
      },
      {
        texto:
          '<b>Cliente orgulloso:</b> es muy bueno con la labia y cree sabérselas todas, por lo que no permite que lo asesoren. Si permite un consejo, se le brinda con certeza y claridad.',
        icono: require('@/assets/tema8/img9.svg'),
      },
      {
        texto:
          '<b>Cliente escéptico:</b> es desconfiado y prevenido, por lo que pregunta las ventajas y desventajas del producto, pues teme ser engañado. ',
        icono: require('@/assets/tema8/img10.svg'),
      },
      {
        texto:
          '<b>Cliente ocupado:</b> desde el inicio, su saludo va acompañado de un “cuento con poco tiempo”, suele ser impaciente y querer que lo atiendan de inmediato.',
        icono: require('@/assets/tema8/img11.svg'),
      },
    ],
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
