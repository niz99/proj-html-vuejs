<template>
    <div>
        <FirstHeaderComp/>
        <SecondHeaderComp/>
    </div>
</template>

<script>
import FirstHeaderComp from './FirstHeaderComp.vue'
import SecondHeaderComp from './SecondHeaderComp.vue'

export default {
  name: 'HeaderComp',
  components: {
    FirstHeaderComp,
    SecondHeaderComp
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
