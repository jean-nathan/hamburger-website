<template>
  <Banner />
  <div class="main-conteiner">
    <h1>Monte o seu burguer:</h1>
    <burger-form />
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';
export default {
  name: "Home",
  components: {
    Banner,
    BurgerForm
  }
}
</script>
