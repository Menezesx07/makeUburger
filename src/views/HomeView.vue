<template>
    
    <Banner />
    
    <div class="main-container">
       <h1>
            Monte Seu Burguer:
       </h1>

       <BurgerFormVue />
    </div>

</template>

<script>

import Banner from '../components/Banner.vue';
import BurgerFormVue from '../components/BurgerForm.vue';

export default {
  name: "Home",
  components: {
    Banner,
    BurgerFormVue
  }
}
</script>
