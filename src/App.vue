<template>
  <div id="app">
    <p>App</p>
    <router-view />
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Nunito+Sans:200,200i,300,300i,400,400i,600,600i,700,700i,800,800i,900&display=swap");
// VARIAVEIS CSS
:root {
  // LAYOUT
  --layout-mobile: 375px;
  --layout-desktop: 1440px;
  //FONT
  --font: "Nunito Sans";
  //CORES
  --DK-blue: hsl(209, 23%, 22%);
  --BG-dark: hsl(207, 26%, 17%);
  --TX-light: hsl(200, 15%, 8%);
  --TF-light: hsl(0, 0%, 52%);
  --BG-light: hsl(0, 0%, 98%);
  --TX-dark: hsl(0, 0%, 100%);
  //TAMANHOS
  --Items: 0.875rem;
  --Page: 1rem;
}
// RESET CSS
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
body {
  font-family: var(--font);
}
body,
img,
h1,
h2,
h3,
h4,
h5,
h6,
p,
span,
ul,
li,
a,
form {
  margin: 0px;
  padding: 0px;
  list-style: none;
  text-decoration: none;
  font-size: var(--Page);
}
img {
  display: block;
  max-width: 100%;
}
</style>
