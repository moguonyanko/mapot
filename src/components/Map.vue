<script setup>
  import 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.js'
  import "./map.js"
  const mapEle = '<div id="map"></div>'
</script>

<template>
  <link href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
    integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=" rel="stylesheet" crossorigin="" />
  <!-- <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
    integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script> -->
    <div id="map"></div>
</template>

<style scoped>
#map {
  width: 100%;
  height: 400px;
  max-width: 600px;
}
</style>
