<template>
  <div class="home">
    <HeartSvg :style="{ color: 'green', fontSize: '30px' }" />
  </div>
</template>

<script>
import HeartSvg from "./Heart.svg";

export default {
  name: "Home",
  components: {
    HeartSvg
  }
};
</script>