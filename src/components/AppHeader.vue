<template>
    <header>
      <h1>Ласкаво просимо на вікіпедію по грі Dark Souls:Remastered!</h1>
      <nav>
        <router-link to="/characters">Персонажі</router-link>
        <router-link to="/locations">Локації</router-link>
      </nav>
    </header>
  </template>

<script>
export default {
  name: 'AppHeader'
}
</script>

  <style scoped>
  header {
    background-color: #333;
    padding: 15px;
    color: white;
    position:center;
  }

  nav {
    margin-top: 10px;
  }

  router-link {
    margin-right: 15px;
    color: white;
    text-decoration: none;
  }

  router-link:hover {
    text-decoration: underline;
  }
  </style>
