<template>
  <b-container class="container">
    <b-nav class="navbar">
      <h1 class="navbar-name">Abey Thomas</h1>
      <b-nav-item class="navbar-list__item">EXPERIENCE</b-nav-item>
      <b-nav-item class="navbar-list__item">EDUCATION</b-nav-item>
      <b-nav-item class="navbar-list__item">SKILLS</b-nav-item>
      <b-nav-item class="navbar-list__item">CONTACT</b-nav-item>
    </b-nav>
  </b-container>
</template>
<style lang="scss">
.container {
  max-width: inherit;
  padding-left: 0px;
  padding-right: 0px;
}
.navbar {
  background-color: white;
  display: flex;
  flex-flow: row wrap;
  justify-content: flex-end;
  list-style: none;
  margin: 0;
  border: 3px solid gray;

  &-name {
    flex-grow: 1;
    color: rgb(173, 16, 55);
  }

  &-list__item {
    padding: 0px 10px;
    color: rgb(173, 16, 55);
  }
  @media all and (max-width: 800px) {
    .navbar {
      justify-content: space-around;
    }
  }

  @media all and (max-width: 600px) {
    .navbar {
      flex-flow: column wrap;
      padding: 0;
    }
  }
}
</style>

<script lang="ts" setup></script>
