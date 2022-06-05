<template>
  <div>
    <main>
      <NavBar />
      <b-container class="main_container">
        <Nuxt />
      </b-container>
      <Footer />
    </main>
  </div>
</template>

<style scoped>
.main_container {
  height: calc(100vh - 56px - 56px);
}

@media (max-width: 991px) {
  .main_container {
    height: calc(100vh - 176px - 56px);
  }
}
</style>
