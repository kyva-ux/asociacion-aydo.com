<template lang="pug">
.layout
  Header
  slot
  Footer
</template>

<style>
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-Regular.ttf) format("truetype");
  font-weight: 400;
  font-style: normal;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-Italic.ttf) format("truetype");
  font-weight: 400;
  font-style: italic;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-Light.ttf) format("truetype");
  font-weight: 300;
  font-style: normal;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-LightItlic.ttf) format("truetype");
  font-weight: 300;
  font-style: italic;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-Medium.ttf) format("truetype");
  font-weight: 500;
  font-style: normal;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-MediumItlic.ttf) format("truetype");
  font-weight: 500;
  font-style: italic;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-Bold.ttf) format("truetype");
  font-weight: 700;
  font-style: normal;
}
@font-face {
  font-family: Montserrat;
  src: url(/fonts/Montserrat-BoldItalic.ttf) format("truetype");
  font-weight: 700;
  font-style: italic;
}

* {
  box-sizing: border-box;
}

body {
  font-family: Montserrat,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
  background: #222629;
}

.layout {
  margin: 0 auto;
}

a {
  text-decoration: none;
  color: inherit;
}

h2 {
  text-transform: uppercase;
  color: white;
  text-align: center;
}

h3 {
  font-size: 24px;
  font-weight: 600;
  font-style: normal;
  margin-bottom: 36px;
}

h4 {
  text-transform: uppercase;
  font-size: 24px;
}


</style>
