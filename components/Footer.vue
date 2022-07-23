<template lang="pug">
footer
  .container
    .left
      .logo
        NuxtLink(to='/') ASOCIACIÓN AYDO
        .subheader LOS CUATRO ELEMENTOS
      div  &copy; 2022 Todos los derechos reservados.
    .right
      .title
        | CONTACTO:
      div hola@asociacion-aydo.com
      div (+34) 652 793 390 / (+34) 606 981118
      .title
        | S&Iacute;GUENOS:
      .social-links
        img.bg-image(alt='Instagram icon' src='/instagram-icon.svg')
        img.bg-image(alt='Facebook icon' src='/facebook-icon.svg')
</template>

<style>
footer {
width: 100%;
background: #ced1d1;
color: #505354;
font-size: 14px;
max-width: 1366px;
margin: auto;
}

footer .container {
padding: 80px 120px;
max-width: 1366px;
display: flex;
margin: auto;
}

footer .container > div {
flex-basis: 50%;
}

footer .right {
padding: 0 80px;
border-left: 1px solid #8b8b8b;
}

footer .logo {
font-size: 24px;
letter-spacing: 2px;
font-weight: 500;
margin-bottom: 32px;
}

footer .subheader {
font-weight: 300;
font-size: 14px;
}

footer .title {
font-size: 16px;
font-weight: 500;
margin-bottom: 16px;
margin-top: 32px;
letter-spacing: 2px;
}

footer .title:first-child {
margin-top: 0;
}
</style>
