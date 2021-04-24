<template>
  <div>
    <h1>Welcome to {{ title2 }}!</h1>
    <input type="text" v-model="input1" />
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "개발자의 품격",
      title2: "Seoul",
      input1: "abcd",
    };
  },
};
</script>
