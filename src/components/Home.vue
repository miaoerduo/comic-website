<template>
<div id='home'>
  <div v-for='(comic, index) in comicList' :key='index' :id="index">
    <div>{{ comic }}</div>
  </div>
</div>

</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      comicList: ['犬夜叉', '火影', '海贼王']
    }
  }
}
</script>

<style scoped>

</style>
