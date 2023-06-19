<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'
export default {
  components:{
    AppTitle,
    AppHero
  }
}
</script>
<template>
    <div>
      <AppTitle/>
    </div>
    <div>
      <AppHero/>
    </div>
</template>
<style>
body{
  background-color:rgb(224, 221, 216)
}
</style>