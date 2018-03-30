<template>
  <div class="home-wrapper">
    <section class="hero">
      <div class="hero-text">
        <h1>About Us</h1>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
  display: grid;
  grid-template-columns: 1fr;
  background: url("https://static.pexels.com/photos/35638/labrador-breed-dogs-animal.jpg");
  background-size: cover;
  height: 50vh;
  width: 100%;
}

.hero-text {
  align-self: center;
  justify-self: start;
  color: white;
  padding: 5rem;
}
.hero-text h1{
  font-size: 3rem;
}

</style>
