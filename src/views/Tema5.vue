<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 5
        h1 Textiles
      .row.justify-content-center.mb-5(data-aos='fade-right')
        .col-sm-12.col-lg-6
          p.mb-5 Los textiles en general ya sea para uso de vestuario o industrial se elaboran a partir de fibras que dan origen a un filamento, este es hilado, después se convierte en hilo y posteriormente a partir de diversas clases de tejidos se elaboran las telas, a continuación, encontrará los procesos generales dentro de cada apartado.
          .bg-color-13.p-5.br-3.mb-cus
            p.mb-0 #[b Fibras textiles:] es la materia sólida unitaria de cualquier estructura textil, fibra es cada uno de los filamentos que componen las unidades fundamentales en la fabricación de hilos, textiles y telas, se considera filamento cuya longitud de esta es superior a su diámetro.
        .col-sm-12.col-lg-6
          .titulo-sexto.color-acento-contenido
              p.mb-0 #[b Figura 27.] Fibras textiles

          figure.mb-0
            img(src='@/assets/curso/temas/t5/1.png', alt='Hombre organizando fibras vegetales teñidas de varios colores, como azul, verde, rosa, rojo y amarillo, posiblemente utilizadas para artesanías o tejidos tradicionales.')
      p.mb-4(data-aos='fade-right') #[b Clasificación de las fibras:] las fibras se clasifican según su origen, entre ellas se tienen dos grandes grupos, las naturales y químicas y estas a su vez se subdividen, en la siguiente tabla se presenta la clasificación.
      
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        p.mb-0 #[b Tabla 10.] Clasificación de las fibras
      .tabla-a.color-acento-contenido.tabla-custom.mb-5(data-aos='fade-right')
        table(alt="Clasificación las fibras textiles en dos grandes grupos: fibras naturales y fibras químicas, según su origen y composición.")
          caption Fuente: El rincón de celeste cielo, (2015)
          thead
            tr
              th Fibras textiles
              th Origen
              th Subcategoría
              th Ejemplos
          tbody
            tr
              td(rowspan="7").fw-bold Fibras naturales
              td(rowspan="2") Animales
              td Procedentes de glándulas sedosas.
              td Seda, seda salvaje.
            tr
              td Procedentes de folículos pilosos.
              td Pelo de alpaca, angora, buey, caballo, conejo, castor, camello, cachemira, cabra guanaco, llama, nutria, vicuña, yak.
            // Fibras naturales - Vegetales
            tr
              td(rowspan="4") Vegetales
              td Procedentes de las semillas.
              td Algodón.
            tr
              td Procedentes del tallo.
              td Lino, cáñamo, yute, ramio.
            tr
              td Procedentes de la hoja.
              td Esparto, sisal.
            tr
              td Procedentes del fruto.
              td Coco.
            tr
              td Minerales
              td(colspan="2") Asbestos, fibra de vidrio, fibra de carbono.
            tr
              td(rowspan="7").fw-bold Fibras químicas
              td(rowspan="3")  Artificiales
              td Base proteínica.
              td De la caseína de la leche (fibroína), de algas (alginato).
            tr
              td Base celulósica.
              td Rayones (viscosa, cupro, acetato).
            tr
              td Base metálica.
              td Oro, plata, cobre.
            tr
              td(rowspan="3") Sintéticas
              td Por polimerización.
              td Polivinilo, poliacrílicos.
            tr
              td Por condensación.
              td Poliéster (tergal), poliamida (#[em nylon]).
            tr
              td Por poliadición.
              td Poliuretano, poliespanoes.
      
      .row.justify-content-center.mb-5(data-aos='fade-right')
        .col-sm-12.col-lg-10
            p.mb-0 #[b Hilos e hilatura:] hilo, se denomina hilo al conjunto de fibras textiles, continuas o discontinuas, que se tuercen juntas alcanzando una gran longitud y que es directamente empleado para la fabricación de tejidos, a su vez, hilatura al arte de hilar los filamentos para obtener un conjunto de hebras preparadas para el proceso de construcción de hilos y tejidos.
        .col-sm-12.col-lg-2.d-none.d-lg-block
          img(src='@/assets/curso/temas/t5/2.svg', alt='')
      
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          p.mb-0 #[b Figura 28.] Hilaturas

      figure.mb-5(data-aos='fade-right')
        img(src='@/assets/curso/temas/t5/3.png', alt='Tres escenas relacionadas con las hiladuras: a la izquierda, husos con hilos enrollados; al centro, un telar en funcionamiento con hilos de colores; y a la derecha, unas manos sostienen madejas de lana teñida.')
      
      
      
      .row.justify-content-center.mb-5(data-aos='fade-right')
        .col-sm-12.col-lg-2.d-none.d-lg-block
          img(src='@/assets/curso/temas/t5/4.svg', alt='')
        .col-sm-12.col-lg-10
            p.mb-0 #[b Tejidos:] es el manufacturado de fibras o hilos que tienen una relación sustancial entre su longitud, área y su espesor con suficiente resistencia mecánica para otorgarle una cohesión (Textile terms and definitions, the textile institute) citado por SENA. Los tejidos tienen una clasificación que se da en dos grupos, tejidos planos y de punto, también se contemplan aquellas no tejidas en las que diversas técnicas a nivel tecnológico permiten su impresión, en el siguiente esquema permite observar esta clasificación:
      


      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        p.mb-0 #[b Tabla 11.] Clasificación de los tejidos
      .tabla-a.color-acento-contenido.tabla-custom.mb-5(data-aos='fade-right')
        table(alt="Tabla con la clasificación de los tejidos en dos grandes grupos: telas tejidas y telas no tejidas. Dentro de las telas tejidas se encuentran los tejidos planos, que incluyen ligamentos fundamentales como tafetán, sarga y raso; ligamentos derivados como esterilla, espina y sarga interrumpida; y otros como dobby, jacquard y afelpados. También se clasifican los tejidos de punto, divididos en tejidos por trama (jersey, lacoste, rib, interlock, piqué) y por urdimbre (tricot y raschell). Por último, las telas no tejidas comprenden materiales como interlones, guatas y entretelas.")
          caption Fuente: El rincón de celeste cielo, (2015)
          thead
            tr
              th Tipo de fibra
              th Origen
              th Subcategoría
              th Ejemplos
          tbody  
            tr
              td(rowspan="6").fw-bold.wcus-9 Telas tejidas
            tr
              td(rowspan="3").w-25.text-left.wcus-9 Plano
              td.text-left Ligamentos fundamentales.
              td.text-left • Tafetán #[br]
                | • Sarga (diagonal)#[br]
                | • Raso
            tr
              td.text-left Ligamentos derivados.
            
              td.text-left • Esterilla / canastra #[br]
               | • Espina / espiga #[br]
               | • Sarga interrumpida #[em (broken twill)]
            tr
              td.text-left.wcus-9 Otros.
              td.text-left Dobby, jacquard, riso, afelpados, etc
            tr
              td(rowspan="2").w-25.text-left.wcus-9 Punto
              td.text-left Por trama
              td.text-left • Sencillo (jersey, lacoste) #[br]
                | •  Doble (rib o resortado, #[em interlock], piqué)
            tr
              td.text-left Por urdimbre
              td.text-left •  #[em Tricot] #[br]
                | •  #[em Raschell]
            tr
              td.fw-bold.wcus-10 Telas no tejidas
              td.text-left No aplica
              td.text-left No aplica
              td.text-left.wcus-9
                br
                | Guatas
                br
                | Entretelas
      
      p.mb-3(data-aos='fade-right') #[b Caracterización de los textiles:] las caracterizaciones de los textiles se organizan en función de su comportamiento, está relacionado con el peso del material, desde su estructura, fluidez, expansión y comprensión, a continuación, se relacionan los aspectos más relevantes de cada una.
      p.mb-5(data-aos='fade-right') Para profundizar más en relación a como se caracterizan se invita al aprendiz a seguir el siguiente llamado a la acción:
      .tarjeta.bg-color-12.p-3.mb-0(data-aos='fade-right')
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-1.d-none.d-lg-block
              img.w-75.mx-auto(src="@/assets/curso/temas/t1/18.svg")
            .col-sm-12.col-lg-11
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Caracterización de los textiles
                  p.mb-0 Se invita a consultar el video para conocer las características, usos y aplicaciones de los textiles en la creación de prendas, una base clave para tomar decisiones acertadas en diseño y confección.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(href="https://www.youtube.com/watch?v=kL9UYOzJD3o" target="_blank")
                    span Ir al video
                    i.fas.fa-play-circle 
      
      
      
      Separador
      #t_5_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 5.1 Aprovechamiento
      p.mb-3(data-aos='fade-right') El aprovechamiento por metro de tela consiste en determinar cuánta tela se utiliza realmente para confeccionar una prenda en relación con la cantidad total comprada. Este cálculo es crucial para optimizar costos, minimizar desperdicios y mejorar la eficiencia en producción.
      p.mb-5(data-aos='fade-right') Pasos para determinar el aprovechamiento:
      .bg-full-width.bg-fondo-2.mb-0(data-aos='fade-right')
        .p-full-width
          .tarjeta.p-5.bg-color-white.br-4
            PasosB.color-acento-contenido
              .row.justify-content-center.mb-0(titulo="Paso 1")
                .col-sm-12.col-lg-8.mb-cus
                  h4.mb-5  Trazado de las piezas del patrón
                  p.mb-4 Colocar las piezas del patrón sobre la tela respetando:
                  ul.lista-ul--color.mb-0
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 El sentido del hilo (dirección de la urdimbre).
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 Los márgenes de costura.
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 El sentido del diseño o estampado, si aplica.
                .col-sm-12.col-lg-4.d-none.d-lg-block
                    img(src='@/assets/curso/temas/t5/5.png')

              .row.justify-content-center.mb-0(titulo="Paso 2")
                .col-sm-12.col-lg-8.mb-cus
                  h4.mb-5  Distribución y encaje de piezas
                  p.mb-0 Organizar las piezas para que ocupen el menor espacio posible dentro del ancho de la tela (normalmente 1,40 m o 1,50 m). Aquí se busca una disposición eficiente, como encajar piezas en ángulos o rotarlas si el diseño lo permite.
                .col-sm-12.col-lg-4.d-none.d-lg-block
                    img(src='@/assets/curso/temas/t5/6.png')


              .row.justify-content-center.mb-0(titulo="Paso 3")
                .col-sm-12.col-lg-8.mb-cus
                  h4.mb-5  Medición de tela usada
                  p.mb-0 Medir el largo total de tela utilizado una vez acomodadas todas las piezas. Por ejemplo, si las piezas distribuidas ocupan 0,95 metros del total de 1 metro adquirido, ese será su valor de uso real.
                .col-sm-12.col-lg-4.d-none.d-lg-block
                    img(src='@/assets/curso/temas/t5/7.png')

              .row.justify-content-center.mb-0(titulo="Paso 4")
                .col-sm-12.col-lg-12.mb-0
                  h4.mb-5  Cálculo del aprovechamiento
                  .row.justify-content-center.mb-5
                    .col-sm-12.col-lg-6.mb-cus
                        p.mb-4 La fórmula para calcular el aprovechamiento es:
                        .titulo-sexto.color-acento-contenido
                            p.mb-0 #[b Figura 29.]   Fórmula de aprovechamiento
                        figure.mb-0
                          img(src='@/assets/curso/temas/t5/8.svg', alt='Fórmula utilizada para calcular el porcentaje de aprovechamiento de tela. Se obtiene dividiendo el área útil utilizada por los patrones entre el área total del metro de tela, y multiplicando el resultado por 100.')
                    .col-sm-12.col-lg-6
                      p.mb-0 Tela: 1 metro de largo x 1,50 metros de ancho = 1,5 m²
                      p.mb-4 Área ocupada por los patrones: 1,15 m²
                      .titulo-sexto.color-acento-contenido
                          p.mb-0 #[b Figura 30.]   Ejemplo de aplicación
                      figure.mb-0
                        img(src='@/assets/curso/temas/t5/9.svg', alt='Ejemplo aplicado de la fórmula de aprovechamiento de tela. Se divide un área útil de 1,15 metros cuadrados entre un área total de 1,5 metros cuadrados, y el resultado se multiplica por 100. El aprovechamiento obtenido es del 76,67 %, lo que indica que se utiliza eficientemente esa proporción del material disponible.')

              .row.justify-content-center.mb-0(titulo="Paso 5")
                .col-sm-12.col-lg-8.mb-cus
                  h4.mb-5  Factores que afectan el aprovechamiento
                  ul.lista-ul--color.mb-0
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 Forma y número de piezas: prendas con muchas piezas pequeñas tienden a generar más sobrantes.
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 Ancho de la tela: a mayor ancho, más oportunidades de optimización.
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 Diseño o estampado: telas con dibujos direccionados limitan la rotación de piezas.
                    li.d-flex
                      i.fas.fa-check-circle.bg-color-11
                      p.mb-0 Técnicas de corte: el uso de #[em software] de corte o corte manual puede influir en el rendimiento.
                .col-sm-12.col-lg-4.d-none.d-lg-block
                    img(src='@/assets/curso/temas/t5/10.png')
              
              .row.justify-content-center.mb-0(titulo="Paso 6")
                .col-sm-12.col-lg-8.mb-cus
                  h4.mb-5  Consideraciones adicionales
                  p.mb-4 Siempre se recomienda dejar un margen de seguridad del 5 - 10 % al comprar tela.
                  p.mb-0 El uso de retales sobrantes en otras prendas o complementos puede mejorar el rendimiento general.
                .col-sm-12.col-lg-4.d-none.d-lg-block
                    img(src='@/assets/curso/temas/t5/11.png')
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
