<template>
  <div class="list-group-component">
    <ul class="list-group">
      <li class="list-group-item" v-for="item in items" v-bind:key="item">{{item.description}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "ListGroupComponent",
  data: function() {
    return {
      items: [
        {
          description: "Description one"
        },
        {
          description: "Description two"
        },
        {
          description: "Description three"
        }
      ]
    };
  }
};
</script>
