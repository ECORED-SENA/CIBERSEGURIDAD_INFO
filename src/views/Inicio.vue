<template lang="pug">
section
  BannerPrincipal.mb-5


  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 1. Presentación

    p El manejo de los datos en el entorno mundial juega un papel fundamental en el desarrollo de las actividades cotidianas de empresas y en general del ámbito productivo; esto ha generado grandes ventajas en dado que la tecnología es la herramienta que soporta la gestión de datos, sin embargo, en la actualidad se ha notado que en las redes de datos e infraestructura tecnológica, aplicaciones informáticas y digitales ha ido aumentando la inseguridad, convirtiéndose en un problema crítico, por tanto la anticipación a este fenómeno es esencial y debe ser comprendido para poder administrar y gestionar los activos de información e infraestructura.
      br
      br
      | De acuerdo al informe de IT RESEARCH PARA IT TRENDS 2019 que muestra las tendencias para la seguridad y los riesgos de información, cada vez crecen las dificultades para este ámbito, implica entonces tener una comprensión profunda de las herramientas de protección y la utilización de las mismas para blindar las organizaciones, esto obliga a tener un talento humano cualificado.
      br
      br
      | Según el estudio de la Comisión de Regulación de Comunicaciones (CRC) y el Departamento Nacional de Planeación, plasmado en el CONPES 3854, proyecta que para el año 2020 se generán alrededor de 307.000 empleos relacionados con la seguridad digital.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 2. Justificación<br>del programa

    p El manejo de los datos en el entorno mundial juega un papel fundamental en el desarrollo de las actividades cotidianas de empresas y en general del ámbito productivo; esto ha generado grandes ventajas en dado que la tecnología es la herramienta que soporta la gestión de datos, sin embargo, en la actualidad se ha notado que en las redes de datos e infraestructura tecnológica, aplicaciones informáticas y digitales ha ido aumentando la inseguridad, convirtiéndose en un problema crítico, por tanto la anticipación a este fenómeno es esencial y debe ser comprendido para poder administrar y gestionar los activos de información e infraestructura.
      br
      br
      | De acuerdo al informe de IT RESEARCH PARA IT TRENDS 2019 que muestra las tendencias para la seguridad y los riesgos de información, cada vez crecen las dificultades para este ámbito, implica entonces tener una comprensión profunda de las herramientas de protección y la utilización de las mismas para blindar las organizaciones, esto obliga a tener un talento humano cualificado. Según el estudio de la Comisión de Regulación de Comunicaciones (CRC) y el Departamento Nacional de Planeación, plasmado en el CONPES 3854, proyecta que para el año 2020 se generarán alrededor de 307.000 empleos relacionados con la seguridad digital. El factor de éxito para mitigar los riesgos asociados a la Ciberseguridad es la educación como pilar fundamental, por ello es necesario propender por una formación de calidad y que cumpla con los retos que se presentan en la actualidad y en escenarios futuros, los cuales prospectivamente se prevé que tendrán un crecimiento exponencial.
      br
      br
      | En concordancia con las estrategias del Gobierno y su plan nacional de desarrollo 2018 2022, específicamente en el pacto por la transformación digital, y su línea de trabajo Promocionaremos una política de Estado para la transformación digital y el aprovechamiento de la cuarta revolución industrial, a través de la interoperabilidad de plataformas, contacto a través del portal único del estado, uso de tecnologías emergentes, seguridad digital, formación en talento digital, y fomento del ecosistema de emprendimiento, por ende el SENA liderará el proyecto de formación en Ciberseguridad atendiendo a la demanda constante de personal con competencias específicas en el área. El SENA conocedor de la necesidad del sector, ofrece este programa de formación complementaria, lo cual permite que los instructores fortalezcan las competencias técnicas, garantizando que estén capacitados, calificados y certificados para responder a estas necesidades de formación y poder aportar a la calidad y pertinencia de los aprendices en el mercado tecnológico y laboral nacional e internacional, alineado con las estrategias de gobierno y en concordancia al avance de las tecnologías a nivel mundial.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 3. Población<br>objetivo

    p La formación está dirigida a personas interesadas en afianzar sus conocimientos en ciberseguridad mediante la formación complementaria virtual SENA.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 3. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.
      br
      br
      | La estrategia didáctica integradora está basada en un estudio de caso, dividido en cuatro fases, el cual traslada al aprendiz a una situación real que le permitirá poner en marcha los contenidos conceptuales y procedimentales, aplicando sus conocimientos y habilidades para resolver un problema, frente a la mitigación de impactos y eliminación/reducción del uso del mercurio.
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 Créditos

    CreditosComp

  Footer
  

</template>
<script>
import { menuPrincipal } from '../config/global'
import BannerPrincipal from '../components/plantilla/BannerPrincipal'
import CreditosComp from '../components/plantilla/CreditosComp'
import Footer from '../components/plantilla/Footer'
export default {
  name: 'Inicio',
  components: {
    BannerPrincipal,
    CreditosComp,
    Footer,
  },
  data: () => ({
    menuPrincipalData: menuPrincipal,
  }),
  computed: {
    desarrolloContenidosData() {
      const allMenuData = [
        ...this.menuPrincipalData.menu,
        ...this.menuPrincipalData.subMenu,
      ]
      return allMenuData.filter(item => item.desarrolloContenidos)
    },
  },
}
</script>

<style lang="sass" scoped>
.resultados-aprendizaje
  &__item
    margin-bottom: 20px
    &:last-child
      margin-bottom: 0

.desarrollo-contenidos
  &__item
    display: flex
    align-items: center
    justify-content: space-between
    margin-bottom: 25px
    padding: 5px
    border-radius: $base-border-radius

    &__texto
      display: flex
      align-items: center

    &__icono
      display: block
      background-color: $color-sistema-g
      font-size: 20px
      font-weight: $base-black-font-weight
      text-align: center
      padding: 10px
      line-height: 1em
      width: 40px
      margin-right: 15px

    &:last-child
      margin-bottom: 0

    &:hover
      background-color: $color-sistema-g
      font-weight: $base-black-font-weight
      color: $color-sistema-a
</style>
