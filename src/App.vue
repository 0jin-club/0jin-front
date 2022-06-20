<template>
  <div class="container2">
    <HeaderItem/>
    <transition>
      <router-view/>
    </transition>
  </div>
</template>

<script>
import HeaderItem from './components/HeaderItem.vue'

export default {
  components: {
    HeaderItem
  }
}
</script>

<style>
@import './assets/style.css';
</style>
