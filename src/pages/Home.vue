<template>
  <section class="home">

    <div class="image">
        <img src="images/mob.png" alt="">
    </div>

    <div class="content">
        <h3>hi, {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
        <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
    </div>

</section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
  data() {
      return {
        name: 'Phuet Phongkheaw',
        motto: 'great power comes with great responsibility',
        content: 'Hi',
      }
 }

}
</script>

<style>

</style>