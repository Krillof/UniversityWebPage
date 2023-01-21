<template>
  <div>
    <BodyCompetencies />
    <BodySupport />
    <BodyTeam />
    <BodyTariffs />
    <BodyLastCase />
  </div>
</template>
  
<script>
import BodyCompetencies from './bodyComponents/BodyCompetencies.vue'
import BodySupport from './bodyComponents/BodySupport.vue'
import BodyLastCase from './bodyComponents/BodyLastCase.vue'
import BodyTeam from './bodyComponents/BodyTeam.vue'
import BodyTariffs from './bodyComponents/BodyTariffs.vue'

export default {
  name: 'PageBody',
  components: {
    BodyCompetencies,
    BodySupport,
    BodyLastCase,
    BodyTeam,
    BodyTariffs
  }

}
</script>

<style scoped>
</style>