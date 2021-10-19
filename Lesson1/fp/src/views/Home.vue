<template>
  <div class="home">
    <!--<img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <geek-calculator />
  </div>
</template>

<script>
// @ is an alias to /src
import GeekCalculator from "@/components/Calculator.vue";

export default {
  name: "Home",
  components: {
    GeekCalculator,
  },
};
</script>
