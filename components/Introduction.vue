<template>
  <b-card class="testimonial">
    <b-card-img
      src="~assets/profilepic.JPG"
      alt="profilepic"
      class="testimonial-image"
    ></b-card-img>

    <div>
      <h1 class="testimonial__text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam quibusdam
        rerum modi nihil a vero doloremque earum exercitationem, similique
        ratione. a VUE Front End Developer
      </h1>
    </div>
  </b-card>
</template>

<style>
.testimonial {
  display: inline-block;
  width: 500px;
  height: 500px;
}

.testimonial__text {
  color: rgb(173, 16, 55);
  font-size: 2rem;
}
</style>

<script>
export default {
  name: "Introduction",
};
</script>
