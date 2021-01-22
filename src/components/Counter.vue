<template>
  <div>
    <h2 v-on:mouseover="increment()">Counter: {{ counter }}</h2>
    <button @click="increment()">+1</button><br />
    <button @click="decrement()">-1</button><br />
    <button @click="reset()">Reset</button><br />
    <button @click="save()">Save..</button>
  </div>
</template>

<script>
export default {
  name: "Counter",
  props: {
    msg: String,
  },
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
    increment() {
      this.counter = this.counter + 1;
    },
    decrement() {
      this.counter = this.counter - 1;
    },
    reset() {
      this.counter = 0;
    },
    save() {
      alert("Opslaan van de waarde: " + this.counter);
    },
  },
};
</script>
