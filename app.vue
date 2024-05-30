<template>
  <div>
    <main class="main container">
      <app-sidebar />
      <div class="main__content">
        <app-navbar />
        <NuxtPage />
      </div>
    </main>
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  list-style: none;
  text-decoration: none;
  box-sizing: border-box;
  font-family: sans-serif;
}

body {
  background: #121212;
}

.container {
  max-width: 1200px;
  width: 100%;
  margin: 60px auto;
  padding: 0 15px;
}

.main {
  display: flex;
  gap: 20px;  

  &__content {
    position: relative;
    background: #1e1e1f;
    border: 1px solid #383838;
    width: 100%;
    border-radius: 20px;
    padding: 30px;
  }
}
</style>