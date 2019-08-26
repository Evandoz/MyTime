<template>
  <div class="home">
    <Time :color="color" :border="border" :bg="bg" :size="size" />
  </div>
</template>

<script>
// @ is an alias to /src
import Time from "@/components/Time.vue";

export default {
  name: "home",
  components: {
    Time
  },
  data () {
    return {
      color: "#fff",
      border: "#fefefe",
      bg: "#000",
      size: "500px"
    }
  }
};
</script>

<style lang="stylus" scoped>
.home
  padding-bottom 10vh
</style>
