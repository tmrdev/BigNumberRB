<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Running Balance Tests</h3>
  </div>
</template>

<script>
import BigNumber from "bignumber.js";
export default {
  name: "RunningBalance",
  props: {
    msg: String,
  },

  mounted() {
    console.log("** BigNumber **");
    const nb = BigNumber(0.7);
    const nb2 = nb.minus(0.1);
    console.log(nb2.toString());
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
a {
  color: #42b983;
}
</style>
