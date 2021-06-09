<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero.title-number
        .h3 3
      .h3 Atributo de calidad de Interoperabilidad
    
    .h4 Interoperabilidad
    .row.justify-content-center.align-items-center.mt-5
      .col-2
        img.img-t.img-a(src='@/assets/ilustraciones/img17.svg', alt='')

      .col-12.col-md-8
        img.img-t.img-a(src='@/assets/ilustraciones/img18.svg', alt='')
        .p Desde el punto de vista arquitectónico, la interoperabilidad es el grado en el que dos o más sistemas de software (o componentes) pueden intercambiar información significativa a través de interfaces, en un contexto particular.

        .p En este contexto se hace referencia a la #[b interoperabilidad técnica], presentada en el #[b Marco de Interoperabilidad para el Estado Colombiano.]
      .col-2
        img.img-t.img-a(src='@/assets/ilustraciones/img19.svg', alt='')
    .titulo-segundo#t_3_1.mt-5
      .h4 3.1 Tipos de Interoperabilidad 
    p.mt-5 Un sistema no puede ser interoperable, si este se encuentra aislado.
    .row.justify-content-center.align-items-center.mt-5
      .col-12.col-md-4
        img.img-t.img-a(src='@/assets/ilustraciones/img20.svg', alt='')
        .h6.mt-3 Sintáctica
        .p Capacidad de intercambiar datos
      .col-12.col-md-4
        img.img-t.img-a(src='@/assets/ilustraciones/img21.svg', alt='')
        .h6.mt-3 Semántica
        .p Capacidad de interpretar los datos intercambiados.

    .titulo-segundo#t_3_2.mt-5
      .h4 3.2 Servicio

    p En este contexto se hace referencia al concepto de servicio de intercambio de información, presentado en el #[b Marco de Interoperabilidad] para el #[b Estado Colombiano:]

    .p Recurso tecnológico que mediante el uso de un conjunto de protocolos y estándares permite el intercambio de información. Es una representación lógica de una actividad de negocio repetible que tiene un resultado específico (por ejemplo, verificar el crédito del cliente, proporcionar datos del clima, consolidar informes de perforación) y que tiene las siguientes características: Autocontenido, puede estar compuesto por otros servicios y es una #[b caja negra] para los consumidores del servicio.      

    .row.justify-content-center.align-items-center.mt-5
      .col-9
        TabsA.color-acento-contenido

          .tarjeta.nav-bg.p-4(titulo="Servicio")
            .h6 Servicio 
            p Un servicio es un elemento arquitectónico que funciona como interfaz de una funcionalidad encapsulada por un componente o sistema de software.
            img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img22.svg', alt='') 

          .tarjeta.nav-bg.p-4(titulo="Consumidor de un servicio")
            .h6 Consumidor de un servicio 
            p El #[b consumidor] de un servicio debe descubrir la ubicación, la identidad y la interfaz del servicio.
            img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img23.svg', alt='') 
          

          .tarjeta.nav-bg.p-4(titulo="Manejo de la respuesta")
            .h6 Manejo de la respuesta
            p Tres posibilidades:

            .p El servicio informa al solicitante con la respuesta.
            .p El servicio envía su respuesta a otro componente (o sistema).
            .p El servicio transmite su respuesta a las partes interesadas.
            img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img24.svg', alt='') 
          .tarjeta.nav-bg.p-4(titulo="Servicio web")
            .h6 Servicio web
            p Un #[b servicio web] es un servicio que usa como canal de comunicación el protocolo #[b HTTP], es decir, el protocolo de comunicación de la Web.

            p Los #[b servicios web] proporcionan un #[b medio estándar de interoperabilidad] para sistemas de software que se ejecutan en una gran variedad de plataformas.

      .col-3
        img.img-t.img-a(src='@/assets/ilustraciones/img25.svg', alt='')

    .titulo-segundo#t_3_3.mt-5
      .h4 3.3 SOAP 
    .row.justify-content-center.align-items-center.mt-5
      .col-8
        img.img-t.img-a(src='@/assets/ilustraciones/img26.svg', alt='')
        p.mt-5 #[b SOAP (Simple Object Access Protocol)] es una especificación de protocolo para #[b información] basada en #[b XML], que los sistemas de software pueden utilizar para intercambiar información y, por tanto, interoperar.

        .p SOAP hace uso del protocolo #[b HTTP] como canal de comunicación y por lo tanto es uno de los esquemas que permite la definición e implementación de #[b servicios web].

    .titulo-segundo#t_3_4.mt-5
      .h4 3.4 REST
    .row.justify-content-center.align-items-center.mt-5
      .col-8
        img.img-t.img-a(src='@/assets/ilustraciones/img27.svg', alt='')
        p.mt-5 #[b REST (Representational State Transfer)] es un estilo arquitectónico basado #[b en cliente-servidor] que se estructura en torno a un pequeño conjunto de operaciones de #[b creación, lectura, actualización, eliminación] (CRUD) (llamadas #[b POST, GET, PUT], DELETE, respectivamente en el mundo REST) y un esquema de #[b direccionamiento] único, basado en un identificador uniforme de recursos (URI).

        .p REST hace uso del protocolo #[b HTTP] como canal de comunicación y por lo tanto es otro de los esquemas que permite la definición e implementación de #[b servicios web.]

    .titulo-segundo#t_3_5.mt-5
      .h4 3.5 Arquitecturas Basadas en Servicios 
    p.mt-5 Una Arquitectura Basada en Servicios (Service-Based Architecture - SBA) es una arquitectura de software basada en un conjunto de componentes que usan servicios web como conectores.   

    .row.justify-content-center.align-items-center.mt-5
      .col-10
        .row.justify-content-between.align-items-center
          .col-12.col-md-6 
            .row.justify-content-center
              .col-11
                .card-media
                    .card-media__body
                      figure.card__figure
                          img(src='@/assets/ilustraciones/img28.svg', alt='')   
                      .h6 #[b Descubrimiento de servicios] 
                      .p Localizar un servicio mediante la búsqueda de un servicio de directorio conocido.  
                        
          .col-12.col-md-6 
            .row.justify-content-center
              .col-11
                .card-media
                    .card-media__body
                      figure.card__figure
                          img(src='@/assets/ilustraciones/img29.svg', alt='')   
                      .h6 #[b Orquestación] 
                      .p Mecanismo de control para coordinar, gestionar y secuenciar la invocación de diferentes servicios. 
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
