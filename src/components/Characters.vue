<template>
    <div class="character-container">
      <img class="character-image" :src="character.image" :alt="character.name" />
      <h3 class="character-name">{{ character.name }}</h3>
      <p class="character-description">{{ character.description }}</p>
    </div>
  </template>

  <style scoped>
  @import '@/assets/css/characters.css';
  </style>
<script>
export default {
  props: {
    character: {
      type: Object,
      required: true
    }
  },
  data () {
    return {
      characters: [
        {
          id: 1,
          name: 'Character 1',
          image: 'path/to/image1.jpg',
          description: 'Description for Character 1.'
        },
        {
          id: 2,
          name: 'Character 2',
          image: 'path/to/image2.jpg',
          description: 'Description for Character 2.'
        }
      ]
    }
  }
}

</script>
