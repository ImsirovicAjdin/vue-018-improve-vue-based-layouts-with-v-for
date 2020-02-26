<template>
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">{{title}}</h5>
      <p class="card-text">{{text}}</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardComponent",
  data: function() {
    return {
      title: "This is the card title",
      text: "This is the card text"
    };
  }
};
</script>