<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
  <div> 
   <Header> Welcome </Header>
   <footer> CopyRight </footer>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
header {
  color: rgb(0, 62, 177);
  padding: auto;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
footer {
  color: rgb(0, 62, 177);
  padding: auto;
}
textarea {
  color-adjust: black;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
}
image {
  padding: auto;
  border-image-width: 25%;
  align-content: center;
}
</style>
