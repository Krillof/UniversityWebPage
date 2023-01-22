<template>
  <div id="team">
    <div id="header">КОМАНДА</div> 
    <div id="t1">
      <img alt="photo" :src='require("@/assets/BodyTeam1.svg")'>
      <div class="th">Лёша <br></div>
      <div class="tf">руководитель поддержки,<br> планирование задач</div>
    </div>
    <div id="t2">
      <img alt="photo" :src='require("@/assets/BodyTeam2.svg")'>
      <div class="th">Роман<br></div>
      <div class="tf">инфраструктура веб-проектов</div>
    </div>
    <div id="t3">
      <img alt="photo" :src='require("@/assets/BodyTeam3.svg")'>
      <div class="th">Ирина<br></div>
      <div class="tf">менеджер по работе<br>с клинетами, организация<br>оказания услуг</div>
    </div>
    <div id="t4">
      <img alt="photo" :src='require("@/assets/BodyTeam3.svg")'>
      <div class="th">Даша<br></div>
      <div class="tf">SEO, веб-маркетинг</div>
    </div>
    <div id="t5">
      <img alt="photo" :src='require("@/assets/BodyTeam1.svg")'>
      <div class="th">Сергей<br></div>
      <div class="tf">технический директор, 14 лет<br>опыт работы с Drupal</div>
    </div>
    <div id="t6">
      <img alt="photo" :src='require("@/assets/BodyTeam2.svg")'>
      <div class="th">Вадим<br></div>
      <div class="tf">UX/UI дизайн</div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'BodyTeam',
  components: {

  }
}
</script>

<style scoped>


#header{
  position: absolute;
  width: 201px;
  height: 51px;
  left: 619px;
  top: 6053px;
  font-weight: 700;
  font-size: 42px;
  line-height: 51px;
  text-align: center;
}

#t1{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 180px;
  top: 6184px;
}
#t2{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 580px;
  top: 6184px;
}
#t3{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 980px;
  top: 6184px;
}
#t4{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 180px;
  top: 6640px;
}
#t5{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 580px;
  top: 6640px;
}
#t6{
  position: absolute;
  width: 280px;
  height: 280px;
  left: 980px;
  top: 6640px;

}

.th{
  margin-top : 10%;
  text-align: left;
  font-weight: 700;
  font-size: 16px;
  line-height: 22px;
}

.tf{
  margin-top : 3%;
  text-align: left;
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;
}
</style>