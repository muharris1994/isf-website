
<script setup>
// Vuetify imports
import { ref } from 'vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <h1>Welcome to ISF Website</h1>
  </header>
  <main>
    <section>
      <h2>About</h2>
      <p>This is the main page of your application. Customize this section with your content.</p>
    </section>
    <!-- Example Vuetify-like card (replace with real Vuetify if installed) -->
    <div class="card">
      <h3>Get Started</h3>
      <ul>
        <li>Update this page with your content</li>
        <li>Add more components as needed</li>
      </ul>
    </div>
  </main>
</template>

<style scoped>

header {
  line-height: 1.5;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.logo {
  display: block;
  margin: 0 auto 2rem;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 60vh;
}

section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-bottom: 2rem;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

h1 {
  text-align: center;
  margin-bottom: 1rem;
}

.card {
  margin: 2rem auto;
  padding: 1.5rem;
  max-width: 400px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  background: #fff;
  display: flex;
  flex-direction: column;
  align-items: center;
}
h2, h3, p, ul {
  text-align: center;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
