<template>
  <div class="home">
    <div class="row">
      <div class="col-2"></div>
      <div class="col-7">
        <instagram-card/>
        <instagram-card/>
        <instagram-card/>
        
      </div>
      <div class="col-3">... ovdje ide desni stupac!</div>
    </div>
  </div>
</template>

<script>

import InstagramCard from "@/components/InstagramCard.vue";

export default {
  name: "home",
  components: {
    InstagramCard,
  },
};
</script>


