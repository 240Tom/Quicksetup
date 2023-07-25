<template>
  <b-container class="header">
    <b-nav class="nav">
      <h1 class="nav-name">Abey Thomas</h1>
      <b-nav-item d-flex justify-content-end>EXPERIENCE</b-nav-item>
      <b-nav-item d-flex justify-content-end>EDUCATION</b-nav-item>
      <b-nav-item d-flex justify-content-end>SKILLS</b-nav-item>
      <b-nav-item d-flex justify-content-end>CONTACT</b-nav-item>
    </b-nav>
  </b-container>
</template>
<style lang="scss">
.header {
  max-width: inherit;
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 50px;
}
.nav {
  background-color: white;
  display: flex;
  flex-flow: row wrap;
  list-style: none;
  margin: 0;

  &-name {
    flex-grow: 1;
    color: rgb(173, 16, 55);
  }

  &-list__item {
    padding: 0px 10px;
    color: rgb(173, 16, 55);
  }
  @media all and (max-width: 800px) {
    .nav {
      justify-content: space-around;
    }
  }

  @media all and (max-width: 600px) {
    .nav {
      flex-flow: column wrap;
      padding: 0;
    }
  }
}
</style>

<script lang="ts" setup></script>
