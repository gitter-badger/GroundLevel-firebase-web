<!--
- src/pages/SomeIn.vue
-->
<template>
  <section id="here">
    <div>
      TO BE DONE 🏂
    </div>

    <h2>Hi {{ user ? user.displayName : '...' }}</h2>
  </section>
</template>

<style scoped>
  #here {
    text-align: center;
  }
</style>

<script>
  import { userMixin } from '@/mixins/user.js';

  export default {
    name: 'SomeIn',
    mixins: [userMixin]
  }
</script>

