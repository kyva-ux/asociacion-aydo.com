<template lang="pug">
header.header
  div
    NuxtLink.logo(to='/')
      strong ASOCIACIÓN AYDO
      .subheader LOS CUATRO ELEMENTOS
    nav.nav
      NuxtLink.nav__link(to='/sobre-nosotros') Sobre nosotros
      NuxtLink.nav__link(to='/eventos/') Eventos
      NuxtLink.nav__link(to='/contacto/') Contacto
</template>

<style>
.header {
  color: white;
}

.header > div {
  box-sizing: border-box;
  margin: auto;
  max-width: 1366px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 80px;
  padding: 0 16px;
  border: 1px solid #4f5252;
}

.logo {
  padding: 0 16px;
}

.nav__link {
  margin-left: 20px;
  padding: 8px 16px;
  margin: 0;
  transition: all 0.25s ease-in-out;
}

.nav {
  height: 100%;
  display: flex;
  justify-content: flex-end;
}

.nav__link {
  display: flex;
  align-items: center;
  height: 100%;
  font-weight: 600;
}

.nav .nav__link:hover {
  background: #30363b;
}
</style>
