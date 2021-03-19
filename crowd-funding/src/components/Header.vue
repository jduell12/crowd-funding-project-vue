<template>
  <header>
    <img class="logo" src="../../images/logo.svg" alt="logo" />
    <img
      class="hamburger"
      src="../../images/icon-hamburger.svg"
      alt="hamburger icon"
    />
    <nav>
      <a href="">About</a>
      <a href="">Discover</a>
      <a href="">Get Started</a>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: flex-end;
  margin-top: 3%;
}
img {
  margin-right: 45%;
}

.hamburger {
  display: none;
}

nav {
  width: 20%;
  display: flex;
  justify-content: space-between;
  margin-right: 10%;
}
a {
  color: white;
  text-decoration: none;
}

a:hover {
  cursor: pointer;
}

@media (max-width: 375px) {
  nav {
    display: none;
  }
  .logo {
    width: 50%;
    margin: 3%;
    margin-right: 30%;
  }
  .hamburger {
    display: inline;
    margin: 5%;
  }
}
</style>
