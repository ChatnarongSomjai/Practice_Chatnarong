<template>
  <dir>
    <p v-for="manu in manufacturer" :key="manu.id">
      {{ manu.id }} -{{ mau.Title }}
    </p>
    <input placeholder="id" v-model="id" />
    <input placeholder="Title" v-model="Title" />
    <button @click="post()">Post</button>
    <button @click="post()">Put</button>
    <button @click="remove()">Delete</button>
  </dir>
</template>
<script>
import axios from "axios";

export default {
  data() {
    return {
      text: "Test",
      manufacturer: [{ id: 1, Title: "test1" }],
      id: "",
      Title: "",
    };
  },
  created() {
    this.get();
  },
  methods: {
    get() {
      //axios get("") .then((respone) => {
      //  this.manufacturer = respone.data;
      //});
    },
    // post(){
    //   axios
    //   .post("")
    // }
  },
};
</script>