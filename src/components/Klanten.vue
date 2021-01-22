<template>
  <div class="hello">
    <h1>{{ klant }}</h1>
  </div>
</template>

<script>
export default {s
  name: "Klanten",
  props: {
    klant: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color:#0f2fe2;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #0f2fe2;
}
</style>
