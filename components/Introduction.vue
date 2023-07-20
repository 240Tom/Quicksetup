<template>
  <section class="testimonial">
    <img
      src="~assets/profilepic.JPG"
      alt="profilepic"
      class="testimonial-image"
    />

    <div class="testimonial-text-container">
      <h1 class="testimonial-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam quibusdam
        rerum modi nihil a vero doloremque earum exercitationem, similique
        ratione. a VUE Front End Developer
      </h1>
    </div>
  </section>
</template>

<style>
.testimonial {
  display: flex;
  max-width: 800px;
  border: 2px, solid, gray;
  margin: auto;

  height: 500px;
}
.testimonial-image {
  flex-grow: 1;
}

.testimonial-text {
  flex-grow: 2;
  color: rgb(173, 16, 55);
  font-size: 2rem;
  flex-basis: auto;
  text-align: center;
  padding: 16px;
}
</style>

<script lang="ts" setup>
// export default {
//   name: "Introduction",
// };
</script>
