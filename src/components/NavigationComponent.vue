<template>
  <nav class="navigation">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "NavigationComponent"
};
</script>

<style scoped>
.navigation ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
}

.navigation li {
  margin: 0 10px;
}

.navigation a {
  text-decoration: none;
  color: #333;
}
</style>
