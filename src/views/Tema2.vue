<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5    
    .titulo-principal
      .titulo-principal__numero.title-number
        .h3 2
      .h3 Atributo de Calidad de Seguridad
    .titulo-segundo
      .h4  La Triada de la Seguridad 
    .row.justify-content-center.align-items-center.mt-5
      .col-8
        p CIA: Sigla en inglés que equivale a Confidentiality (Confidencialidad), Integrity (Integridad) y Availability (Disponibilidad), los cuales constituyen los tres pilares de la seguridad de la información.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img11.svg', alt='') 

    .row.justify-content-between.align-items-center.row-bg.p-4.mt-5
      .col-12.col-md-6 
        .titulo-segundo#t_2_1.mt-5
          .h4 2.1 Confidencialidad
        p #[b Evitar el acceso no autorizado] 
        .p Esto comprende dos requisitos separados: 
        ol.lista-ol--cuadro.mt-3
          li 
            .lista-ol--cuadro__vineta
              span 1
            | El observador no puede acceder al contenido del mensaje.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | El observador no puede identificar al remitente y al receptor.
        .titulo-segundo#t_2_2.mt-5
          .h4 2.2 Integridad
        p #[b No modificación de la información existente.] 
        .p Esto comprende que no haya ningún tipo de #[b manipulación] del mensaje y que este se conserve en su #[b estado original] sin sufrir alteraciones (#[b veracidad] del dato).
      .col-12.col-md-6 
        img.img-t.img-a(src='@/assets/ilustraciones/img12.svg', alt='')

    .titulo-segundo#t_2_3.mt-5
      .h4 2.3 Disponibilidad 
    .row.justify-content-between.align-items-center.mt-5
      .col-12.col-md-6
        img.img-t.img-a(src='@/assets/ilustraciones/img13.svg', alt='')

      .col-12.col-md-6
        p #[b La información debe estar disponible cuando se necesite] 
        .p Esto requiere que los siguientes elementos funcionen correctamente:
        ol.lista-ol--cuadro.mt-3
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Los sistemas informáticos utilizados para almacenar y procesar la información.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Los controles de seguridad utilizados para proteger la información. 
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Los canales de comunicación utilizados para acceder a la información.  

    .titulo-segundo#t_2_4.mt-5
      .h4 2.4 Características de la Seguridad
    img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img14.svg', alt='')

    .titulo-segundo#t_2_5.mt-5
      .h4 2.5 Tácticas Arquitectónicas para Seguridad

    p #[b Táctica arquitectónica]
    img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img15.svg', alt='')

    p.mt-5 #[b Mapa de tácticas arquitectónicas para seguridad]
    img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img16.svg', alt='')


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
