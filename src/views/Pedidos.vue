<template>
  <div class="main-conteiner">
    <h1>Gerenciar pedidos:</h1>
    <Dashboard />
  </div>
</template>

<script>
import Dashboard from '@/components/Dashboard.vue';
export default {
  name: "Pedidos",
  components: {
    Dashboard
  }
};
</script>