<template>
    <div class="locations-container">
      <div v-for="location in locations" :key="location.id" class="location-card">
        <img class="location-image" :src="location.image" :alt="location.name" />
        <div class="location-details">
          <h3 class="location-name">{{ location.name }}</h3>
          <p class="location-description">{{ location.description }}</p>
        </div>
      </div>
    </div>
  </template>

  <style scoped>
  @import '@/assets/css/locations-styles.css';
  </style>

<script>
export default {
  data () {
    return {
      locations: [
      ]
    }
  }
}
</script>
