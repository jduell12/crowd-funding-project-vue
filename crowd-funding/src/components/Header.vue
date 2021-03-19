<template>
  <header>
    <img src="../../images/logo.svg" alt="logo" />

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
</style>
