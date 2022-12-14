<template>
  <div>
    <BodyCompetencies />
    <BodyTeam />
    <BodyLastCase />
  </div>
</template>
  
<script>
import BodyCompetencies from './bodyComponents/BodyCompetencies.vue'
import BodyLastCase from './bodyComponents/BodyLastCase.vue'
import BodyTeam from './bodyComponents/BodyTeam.vue'

export default {
  name: 'PageBody',
  components: {
    BodyCompetencies,
    BodyLastCase,
    BodyTeam
  }

}
</script>

<style scoped>
</style>