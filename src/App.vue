<template>
  <HelloWorld msg="Welkom bij de Vue cursus" fiets="We leren van alles :)" />
  <Counter />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import CounterVue from "./components/Counter.vue";

export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    Counter: CounterVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
