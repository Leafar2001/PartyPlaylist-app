<script setup lang="ts"></script>

<template>
  <section class="section1">
    <div class="wrapper">
      <div>
        <input type="text" placeholder="Search song" class="inputSong" />
        <div style="width: 100%; height: 1px; background-color: #fff; margin-top: 3px"></div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section1 {
  width: 100vw;
  height: 100vh;
}
.wrapper {
  display: flex;
  justify-content: center;
  margin-top: 20vh;
}
.inputSong {
  background-color: var(--background-color);
  border: none;
  color: white;
  font-size: 2rem;
}
textarea:focus,
.inputSong:focus {
  outline: none;
}
</style>
