<template>
  <div id="app">
    <div class="container mt-5 mb-5">
      <main-title-component></main-title-component>
      <div class="row">
        <div class="col">
          <list-group-component></list-group-component>
        </div>
        <div class="col">
          <card-component></card-component>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainTitle from "./components/MainTitle";
import ListGroupComponent from "./components/ListGroupComponent";
import CardComponent from "./components/CardComponent";

export default {
  name: "App",
  components: {
    MainTitle,
    ListGroupComponent,
    CardComponent
  }
};
</script>

<style>
@import "https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css";
</style>