<script setup lang="ts">
import { Metaport } from "@skalenetwork/metaport/build/index"
const metaport = new Metaport({
  chains: ["mainnet", "elated-tan-skat", "honorable-steel-rasalhague"],
  openOnLoad: true,
  openButton: true,
  
})
</script>

<template>
  <div id="metaport">
    <h2>Vite/Vue with Basic SKALE Metaport Integration</h2>
  </div>
</template>

<style scoped>
  div {
    height: 100vh;
    width: 100vw;
    overflow: hidden;
    background:darkslateblue;
    color: white;
  }
</style>
