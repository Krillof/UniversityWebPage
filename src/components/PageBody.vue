<template>
  <div>
    <BodyCompetencies />
    <BodyLastCase />
  </div>
Привет!
  Hello
</template>
  
<script>
import BodyCompetencies from './bodyComponents/BodyCompetencies.vue'
import BodyLastCase from './bodyComponents/BodyLastCase.vue'

export default {
  name: 'PageBody',
  components: {
    BodyCompetencies,
    BodyLastCase
  }

}
</script>

<style scoped>
</style>