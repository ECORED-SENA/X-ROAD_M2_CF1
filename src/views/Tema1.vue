<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero.title-number
        .h3 1
      .h3 Arquitectura de Software 
    .h3 ¿Qué es Arquitectura de Software?       
    .row.justify-content-center.align-items-center
      .col-12.col-md-7
        p la #[b arquitectura de software] es el conjunto de estructuras necesarias para #[b razonar] acerca de un sistema de software, las cuales comprenden:
        ol.lista-ol--cuadro.mt-5
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Elementos de software.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Relaciones entre elementos de software.
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Propiedades asociadas a los elementos y relaciones.
        p.mt-5 La #[b arquitectura de software] es la disciplina encargada de soportar las #[b decisiones de diseño] de más #[b alto nivel], definidas para un sistema de software.            
      .col-12.col-md-5
        img.img-t.img-a(src='@/assets/ilustraciones/img1.svg', alt='') 

    .titulo-segundo#t_1_1.mt-5
      .h4 1.1 Elementos Arquitectónicos 
    p Un #[b elemento arquitectónico] es una pieza fundamental a partir de la cual se puede construir un sistema de software.
    ol.lista-ol--cuadro.mt-5
      li 
        .lista-ol--cuadro__vineta
          span 1
        p 
          | Los principales elementos arquitectónicos son los  
          strong componentes.
      li 
        .lista-ol--cuadro__vineta
          span 2
        p 
          |Las 
          strong interacciones 
          | entre componentes se dan por medios de conectores.
    .row.justify-content-center.align-items-center.mt-5
      .col-10        
        img.img-t.img-a(src='@/assets/ilustraciones/img2.svg', alt='') 

    .titulo-segundo#t_1_2.mt-5
      .h4 1.2 Componentes y Conectores

    TabsA.color-acento-contenido.my-5

      .tarjeta.nav-bg.p-4(titulo="Componentes")
        .h6 Componentes
        p Representan los principales elementos computacionales y almacenes de datos que están presentes en tiempo de ejecución.
        img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img3.svg', alt='') 

      .tarjeta.nav-bg.p-4(titulo="Conectores")
        .h6 Conectores
        p Son una vía de interacción en tiempo de ejecución entre dos o más componentes
        img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img4.svg', alt='') 
      

      .tarjeta.nav-bg.p-4(titulo="Componentes - Conectores ")
        .h6 Componentes - Conectores 
        img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img5.svg', alt='') 

    .row.justify-content-center.align-items-center.mt-5
      .col-10        
        img.img-t.img-a(src='@/assets/ilustraciones/img6.svg', alt='')

    .titulo-segundo#t_1_3.mt-5
      .h4 1.3 Estructuras estáticas
    .row.justify-content-between.align-items-center.mt-5
      .col-12.col-md-6
        p Las #[b estructuras estáticas] de un sistema de software definen:
        ol.lista-ol--cuadro.mt-5
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Los elementos que tienen presencia en tiempo de diseño.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | La disposición de los elementos. 

        p.mt-5 #[b Tiempo de diseño]: escenario previo al proceso de despliegue.
        img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img7.svg', alt='')
        ul.lista-ul--color.mt-4
          li 
            i.lista-ul__vineta
            | #[b Aplicación]
        .p #[b Diseño interno de un componente lógico:] código fuente, estructura de archivos, modelado a nivel del paradigma de programación. 

      .col-12.col-md-5
        img.img-t.img-a(src='@/assets/ilustraciones/img8.svg', alt='')
        ul.lista-ul--color.mt-4
          li 
            i.lista-ul__vineta
            | #[b Base de datos - Modelo de datos]

    .row.justify-content-between.align-items-center.row-bg.p-4.mt-5
      .col-12.col-md-6 
        img.img-t.img-a(src='@/assets/ilustraciones/img9.svg', alt='')
      .col-12.col-md-6  
        .titulo-segundo#t_1_4.mt-5
          .h4 1.4 Estructuras Dinámicas 
        p Las #[b estructuras dinámicas] de un sistema de software definen: 
        ol.lista-ol--cuadro.mt-3
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Los elementos que tienen presencia en tiempo de ejecución.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Las Interacciones entre los elementos.      

        .p Estructuras conformadas por un conjunto de componentes y conectores en ejecución.

        .p #[b Tiempo de ejecución:] escenario posterior al proceso de despliegue.

        .titulo-segundo#t_1_5.mt-5
          .h4 1.5 Comportamiento Externamente Visible 
        p El comportamiento externamente visible de un sistema de software define las interacciones funcionales entre el sistema y su entorno.  

    .titulo-segundo#t_1_6.mt-5
      .h4 1.6 Atributos de Calidad         
    p Una #[b propiedad / atributo] de calidad de un software es una propiedad no funcional, visible externamente.
    
    .row.justify-content-center.align-items-center.mt-5
      .col-12.col-md-6
        TabsB
          .py-4.py-md-5(titulo="Seguridad")

            .nav-bg.p-5
              p Capacidad del sistema de software de proteger la información a partir de tres pilares: confidencialidad, integridad y disponibilidad.

          .py-4.py-md-5(titulo="Interoperabilidad")
            .nav-bg.p-5
              p Capacidad de un software para intercambiar información.

            
          .py-4.py-md-5(titulo="Rendimiento")
            .nav-bg.p-5
              p Capacidad del sistema de software de procesar tareas.
          
          .py-4.py-md-5(titulo="Escalabilidad")
            .nav-bg.p-5
              p Capacidad del sistema de software de manejar el aumento de la carga de trabajo.
          
          .py-4.py-md-5(titulo="Disponibilidad")
            .nav-bg.p-5
              p Capacidad del sistema de software de mantenerse en operación cuando sea necesario.

              .p Esta propiedad posee una característica importante: corresponde a un atributo de calidad de software (alta disponibilidad), y constituye uno de los tres pilares de la seguridad (otro atributo de calidad)
          
          .py-4.py-md-5(titulo="Resiliencia")
            .nav-bg.p-5
              p Capacidad del sistema de software de manejar los fallos que puedan afectar la disponibilidad.

              .p Esta propiedad garantiza la continuidad de los servicios ofrecidos por un sistema de software.

    .row.justify-content-center.align-items-center.mt-5
      .col-10
        img.img-t.img-a(src='@/assets/ilustraciones/img10.svg', alt='')


</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
