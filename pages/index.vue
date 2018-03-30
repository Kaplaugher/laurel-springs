<template>
  <div class="home-wrapper">
    <section class="hero">
      <div class="hero-text">
        <h1>Laurel Springs Animal Hospital</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quo?</p>
      </div>
    </section>
    <HoursBar />
  </div>
</template>

<script>
import HoursBar from '~/components/UI/HoursBar'
export default {
  components: {
    HoursBar
  }

};
</script>

<style scoped>
.hero {
  display: grid;
  grid-template-columns: 1fr;
  background: url("https://static.pexels.com/photos/374825/pexels-photo-374825.jpeg");
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


</style>
