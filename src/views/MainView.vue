<template>
  <main class="main-container">


    <section class="itemsListContainer">



    </section>

    <!-- Background Image -->
    <img src="../assets/images/brand/foodImage-transparent.png"
         alt="Food Image"
         class="foodImage">
  </main>
</template>

<script setup>
</script>

<style>
.main-container {
  position: relative;
  width: 100%;
  min-height: 100vh;
  overflow: hidden;
}

.itemsListContainer {
  position: relative;
  z-index: 1;
}

.foodImage {
  position: absolute;
  top: 50%;
  left: 50%;
  max-width: 25rem;
  object-fit: cover;
  transform: translate(-50%, -50%);
  z-index: -1;
  opacity: 0.7;
  pointer-events: none;
}
</style>
