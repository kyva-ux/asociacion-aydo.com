<template lang="pug">
div
  .landing-header
    NuxtLink.page-btn.yugdo-btn(to="/yug-do/")
      img(alt="Example image" src="/yugdo-logo.svg")
      div
        div YUG DO
        span.tagline ASOCIACIÓN AYDO
      img.bg-image(alt="Imagen boletin" src="/yugdo-btn.png")
    NuxtLink.page-btn.kaido-btn(to="/kai-do/")
      img(alt="Example image" src="/kaido-logo.svg")
      div
        div KAI DO
        span.tagline CENTRO DE TERAPIAS NATURALES
      img.bg-image(alt="Imagen boletin" src="/kaido-btn.png")
    NuxtLink.page-btn.shindo-btn(to="/shin-do/")
      img(alt="Example image" src="/shindo-logo.svg")
      div
        div SHIN DO
        span.tagline ESCUELA DE SABIDURÍA
      img.bg-image(alt="Imagen boletin" src="/shindo-btn.png")
    NuxtLink.page-btn.zhendo-btn(to="/zhen-do/")
      img(alt="Example image" src="/zhendo-logo.svg")
      div
        div ZHEN DO
        span.tagline ESCUELA DE ACUPUNTURA
      img.bg-image(alt="Imagen boletin" src="/zhendo-btn.png")
  .section.section-about
    .container
      .left
        h3 ¿Qué es la Asociación AYDO?
        p La asociación AYDO es un lugar de encuentro para personas que busquen ampliar sus fronteras y desarrollar su conciencia en una comunidad de personas con las mismas inquietudes.
        p Se compone de cuatro elementos básicos, inspirado en los cuatro elementos de la tierra. Por un lado, Yug Do, es el lugar donde desarollaremos la parte más física en su respectivo dojo, así como nos guiará en el camino de nuestro desarrollo espiritual. Por otro lado, Kai Do representa el lugar de sanación, un centro de terapia y bienestar. En la parte de Shin Do, por el contrario, desarrollaremos la parte más teórica, donde ampliaremos nuestro conocimiento y sabiduría del mundo que nos rodea. Por último, Zhen Do es la escuela de acupuntura, para aquellos que quieran aprender a autosanarse y comprender mejor sus puntos energéticos.
      .right
        .box
          img(alt="AYDO logo image" src="/aydo-logo.svg")
          div ASOCIACIÓN AYDO
          span LOS CUATRO ELEMENTOS
  //- .section-news.section
  //-   h2 novedades
  //-   .carrusel
  //-     .news-box
  //-       img(alt="AYDO logo image" src="/section-yugdo.png")
  //-       div Próximo curso
  //-     .news-box
  //-       img(alt="AYDO logo image" src="/section-kaido.png")
  //-       div Próxima convivencia
  .section.section-involve
    .container
      .left
        h3 ¿Cómo formar parte?
        p Para formar parte de esta comunidad consciente no debes cumplir ningún requisito ni comprometerte en los cuatro elementos que conforman la Asociación AYDO. Puedes participar en todo aquello que desees libremente según tus inquietudes y necesidades. Todo dependerá de lo que requieras tú, como persona. Contacta con nosotros para saber más sobre nuestros cursos y talleres o sobre lo que implica cada una de las áreas que trabajamos.
        Button(to='/contacto') Contactar
      .right
        img.image-box(alt="AYDO logo image" src="/section-yugdo.png")
    .container
      .left
        img.image-box(alt="AYDO logo image" src="/section-yugdo.png")
      .right
        p Estamos seguros que, tu implicación en cualquiera de las áreas que conforman AYDO, te aportará una nueva visión de la vida, pues podrás enriquecerte, junto a otras personas, de una experiencia totalmente renovadora. En esta comunidad, además de desarrollar tu conciencia y conocimientos, tendrás a tu disposición diversas actividades como convivencias o salidas al campo en grupo. Esto te permitirá crecer y evolucionar mientras te rodeas de personas con tu misma vibración.
        Button(to='/eventos') Ver eventos
  .section.section-yugdo.pattern
    .container
      .left
        .logo-box
          img(alt="Example image" src="/yugdo-logo.svg")
          div
            div YUG DO
            span.tagline EL ARTE MARCIAL DEL BAMBÚ
        p Para formar parte de esta comunidad consciente no debes cumplir ningún requisito ni comprometerte en los cuatro elementos que conforman la Asociación AYDO. Puedes participar en todo aquello que desees libremente según tus inquietudes y necesidades. Todo dependeré de lo que requieras tú, como persona. Aquí todo el mundo es bienvenido.
        p Contacta con nosotros para saber más sobre nuestros cursos y talleres o sobre lo que implica cada una de las áreas que trabajamos.
        Button(to='/yug-do') Saber más
      .right
        img.image-box(alt="Example image" src="/section-yugdo.png")
  .section.section-kaido.pattern
    .container
      .left
        img.image-box(alt="Example image" src="/section-kaido.png")
      .right
        .logo-box
          img(alt="Example image" src="/kaido-logo.svg")
          div
            div KAI DO
            span.tagline CENTRO DE TERAPIAS NATURALES
        p Para formar parte de esta comunidad consciente no debes cumplir ningún requisito ni comprometerte en los cuatro elementos que conforman la Asociación AYDO. Puedes participar en todo aquello que desees libremente según tus inquietudes y necesidades. Todo dependeré de lo que requieras tú, como persona. Aquí todo el mundo es bienvenido.
        p Contacta con nosotros para saber más sobre nuestros cursos y talleres o sobre lo que implica cada una de las áreas que trabajamos.
        Button(to='/kai-do') Saber más
  .section.section-shindo.pattern
    .container
      .left
        .logo-box
          img(alt="Example image" src="/shindo-logo.svg")
          div
            div SHINDO DO
            span.tagline ESCUELA DE SABIDURÍA
        p Para formar parte de esta comunidad consciente no debes cumplir ningún requisito ni comprometerte en los cuatro elementos que conforman la Asociación AYDO. Puedes participar en todo aquello que desees libremente según tus inquietudes y necesidades. Todo dependeré de lo que requieras tú, como persona. Aquí todo el mundo es bienvenido.
        p Contacta con nosotros para saber más sobre nuestros cursos y talleres o sobre lo que implica cada una de las áreas que trabajamos.
        Button(to='/shin-do')  Saber más
      .right
        img.image-box(alt="Example image" src="/section-shindo.png")
  .section.section-zhendo.pattern
    .container
      .left
        img.image-box(alt="Example image" src="/section-zhendo.png")
      .right
        .logo-box
          img(alt="Example image" src="/zhendo-logo.svg")
          div
            div ZHEN DO
            span.tagline ESCUELA DE ACUPUNTURA
        p Para formar parte de esta comunidad consciente no debes cumplir ningún requisito ni comprometerte en los cuatro elementos que conforman la Asociación AYDO. Puedes participar en todo aquello que desees libremente según tus inquietudes y necesidades. Todo dependeré de lo que requieras tú, como persona. Aquí todo el mundo es bienvenido.
        p Contacta con nosotros para saber más sobre nuestros cursos y talleres o sobre lo que implica cada una de las áreas que trabajamos.
        Button(to='/zhen-do')  Saber más
  .section.section-newsletter
    .container
      .left
        h4 únete a nuestra comunidad
        input(type="text" name="" value="" placeholder="Email")
        .btn Enviar
      .right
        div Recibiras nuestro boletín mensual
        img(alt="Imagen boletin" src="/boletin.svg")
</template>

<script setup>
metaInfo: {
  title: 'About us'
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}

.landing-header {
  width: 100%;
  max-width: 1366px;
  margin: auto;
  height: calc(100vh - 100px);
  display: flex;
  flex-wrap: wrap;
  gap: 80px;
  padding: 120px 160px;
  border: 1px solid #4f5252;
  border-top: none;
  position: relative;
}

.landing-header::before {
  content: "";
  width: 50%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  aspect-ratio: 1/1;
  position: absolute;
  background: url('/kaido-logo.svg') no-repeat;
  background-position: center;
  background-size: cover;
  filter: grayscale(100%);
  opacity: .1;
}

.page-btn {
  flex: 1 40%;
  border-radius: 16px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  font-size: 32px;
  position: relative;
  overflow: hidden;
  background-size: cover;
  background-position: center;
  border: 1px solid #4f5252;
  cursor: pointer;
  transition: all .5s ease-in-out;
}

.page-btn .bg-image {
  width: 101%;
  height: 101%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  position: absolute;
  z-index: 0;
  transition: all .6s ease-in-out;
}

.page-btn:hover .bg-image {
  width: 110%;
  height: 110%;
}

.page-btn:hover:after {
  background-color: rgba(54, 54, 54, 0.5);
}

.page-btn:after {
  position: absolute;
  content: " ";
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  background-color: rgba(54, 54, 54, 0.7);
  transition: all .6s ease-in-out;
}

.page-btn > div {
  display: flex;
  justify-content: center;
  flex-direction: column;
  z-index: 1;
  color: white;
}

.page-btn img {
  width: 80px;
  margin-right: 16px;
  z-index: 1;
}

.page-btn span {
  font-size: 12px;
  color: #aaaaaa;
}

.section {
  width: 100%;
  margin: auto;
  height: 100vh;
  padding: 80px 120px;
  position: relative;
  max-width: 1366px;
  border: 1px solid #4f5252;
  border-top: none;
  border-bottom: none;
}

.section .image-box {
  border-radius: 16px;
  height: 100%;
  width: 100%;
}

.section .container > div {
  padding: 40px 60px;
  flex-basis: 50%;
  text-align: justify;
}

.pattern:after {
  width: 35%;
  height: 100%;
  content: " ";
  background-size: cover;
  position: absolute;
  top: 0;
  right: 0;
  z-index: 0;
}

.container {
  display: flex;
  max-width: 1366px;
  z-index: 1;
  position: relative;
}

.logo-box {
  display: flex;
  align-items: center;
  font-size: 40px;
  font-weight: 600;
  letter-spacing: 2px;
  text-align: left;
}

.logo-box .tagline {
  font-size: 16px;
  color: #888888;
}

.logo-box img {
  width: 100px;
  margin-right: 16px;
}

.logo-box > div {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.section-about {
  background: #f8f5f0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.section-about .right {
  display: flex;
  justify-content: center;
  align-items: center;
}

.section-about .box {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  background: #222629;
  padding: 40px;
  border-radius: 16px;
  color: white;
  height: 100%;
  width: 100%;
}

.section-about img {
  width: 120px;
  margin-bottom: 40px;
}

.section-about:after {
  width: 35%;
  height: 100%;
  content: " ";
  background: url('/trama-aydo.svg');
  position: absolute;
  top: 0;
  right: 0;
  z-index: 0;
}

.section-news {
  width: 100%;
  margin: auto;
  height: 100vh;
  padding: 80px 120px;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
}

.carrusel {
  display: flex;
  align-items: center;
  flex: 1;
  padding: 80px;
}

.carrusel .news-box {
  padding: 40px;
  color: white;
  text-transform: uppercase;
  text-align: center;
  font-weight: 600;
}

.section-news img {
  width: 500px;
}

.section-involve {
  height: auto;
  background: #f8f5f0;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  max-width: 1366px;
}

.section-involve .container {
  display: flex;
}

.section-yugdo {
  color: white;
  display: flex;
  align-items: center;
}

.section-yugdo:after {
  background-image: url('/trama-yugdo.png');
}

.section-yugdo .container {
  align-items: center;
}

.section-kaido {
  color: white;
  display: flex;
  align-items: center;
}

.section-kaido:after {
  left: 0;
  background-image: url('/trama-kaido.png');
}

.section-shindo {
  color: white;
  display: flex;
  align-items: center;
}

.section-shindo:after {
  background-image: url('/trama-shindo.png');
}

.section-zhendo {
  color: white;
  display: flex;
  align-items: center;
}

.section-zhendo:after {
  left: 0;
  background-image: url('/trama-yugdo.png');
}

.section-newsletter {
  height: auto;
  background: #f8f5f0;
  color: #686b6a;
}

.section-newsletter .container {
  display: flex;
  max-width: 1366px;
}

.section-newsletter .container > div {
  text-align: left;
}

.section-newsletter .container .left {
  flex-basis: 60%;
}

.section-newsletter input {
  margin-right: 24px;
  background: #b2b7b8;
  color: rgb(74, 74, 74);
  border-radius: 10px;
  display: inline-block;
  padding: 8px 48px;
  font-size: 16px;
  width: 100%;
  font-weight: 600;
  border: 2px solid #919191;
}
</style>
